---
layout: collectionindex-de
title: Participant Collection
permalink: /participant-collection-de/
language: de
finder: collection-participant
---
<h1>Willkommen in der Teilnehmenden-Sammlung!</h1>
<p><span class="information">Athleten aus Österreich, Deutschland, Lettland, Finnland, Ungarn und der Tschechoslowakei nahmen an der Wettkämpfen teil. Für viele Vereine war es eine Herausforderung ein Team nach Mürzzuschlag zu schicken, vor allem aufgrund der fehlenden finanziellen Mittel und der weiten Anreise. Aber diejenigen, die kommen konnten, waren hoch motiviert zu gewinnen und wurden herzlichst empfangen.</span>
<p><span class="information">Unten können Sie durch die Sammlung klicken.</span></p>
<div class="grid-item" id="exhibit-image"><img src="../media/IMG_20210624_112333_long.jpg" class="img-fluid" alt="Medaillen für die Sieger">Sieger und Siegerinnen erhielten einen Medaille mit dem Logo der Arbeiterwintersport-Olympiade.</div>
<!--This adds the collection's objects.-->
{% for object in site.participant-de %}
    {% include collection-button.html %}
{% endfor %}