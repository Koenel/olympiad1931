---
layout: collectionindex
title: Participant Collection
permalink: /participant-collection/
language: en
finder: collection-participant
---

<h1>Welcome to the participant collection!</h1>
<p><span class="information">Athletes from Austria, Germany, Latvia, Finland, Hungary and Czechoslovakia participated in the competitions. For many clubs, it was challenging to send their teams to Mürzzuschlag because of travelling costs and distance. But those who were able to come, were eager to win and warmly welcomed.</span>
<p><span class="information">Below, you can click through collection content.</span></p>
<div class="grid-item" id="exhibit-image"><img src="../media/IMG_20210624_112333_long.jpg" class="img-fluid" alt="Medals for winners">Athletes were awarded a medal with the Workers Winter Olympics logo</div>
<!--This adds the collection's objects.-->
{% for object in site.participant %}
    {% include collection-button.html %}
{% endfor %}