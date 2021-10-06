---
layout: orderedbytopic
title: Explore the exhibition by topic
permalink: /explore-by-topic/
---
<!-- taken from: https://stackoverflow.com/questions/28100220/jekyll-display-collection-by-category-->

{% assign educat = site.participant | where: "category", "education" %}

{% assign classsolsorted = site.organiser | sort: "category" %}

<!--assign given categories into groups in order to process them in a for-loop-->

{% assign groups = site.participant | group_by: "category" | sort: "name" %}

<!--This for-loop displays the groups that have been assigned above, however, displaying the title does not work yet-->
<!--{% for group in groups %}
    {{ group.name }}
    {% for item in groups.item %}
        {{item.title}}
    {% endfor %}
{% endfor %}-->

<h1 class="category-title"> Class struggle </h1>
<div class="abstract-listing">{% include education-collection.html %}</div>

<h1 class="category-title"> Education </h1>
<div class="abstract-listing">{% include education-collection.html %}</div>

<h1 class="category-title"> Equality </h1>
<div class="abstract-listing">{% include equality-collection.html %}</div>


<h1 class="category-title"> International </h1>
<div class="abstract-listing">{% include international-collection.html %}</div>

<h1 class="category-title"> Solidarity </h1>
<div class="abstract-listing">{% include solidarity-collection.html %}</div>