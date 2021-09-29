---
layout: aboutpages
title: Explore the exhibition by topic
permalink: /explore-by-topic/
---
<!-- taken from: https://stackoverflow.com/questions/28100220/jekyll-display-collection-by-category-->
{{ page.category }}

{% assign educat = site.participant | where: "category", "education" %}

{% assign classsolsorted = site.organiser | sort: "category" %}

{% assign groups = site.participant | group_by: "category" | sort: "name" %}

{% for group in groups %}
    {{ group.name }}
    {% for item in groups.item %}
        {{item.title}}
    {% endfor %}
{% endfor %}