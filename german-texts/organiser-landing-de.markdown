---
layout: collectionindex-de
title: Organiser Collection
permalink: /organiser-collection-de/
language: de
finder: collection-organiser
---
<h1>Willkommen in der Organisator-Sammlung!</h1>
<p><span class="information">Eine Großveranstaltung wie die Zweiter Arbeiter-Wintersport-Olympiade benötigt eine gute Organisation und ein verlässliches Team. Theodor Hüttenegger war eine Schlüsselfigur im Organisationsteam in Mürzzuschlag. Hüttenegger trommelte Freiwillige zusammen um die Schischanze zu bauen und ähniches. Während der Veranstaltung war er für den technischen Ablauf verantwortlich. Einige Jahre später gründete er das Winter!Sport!Museum! in Mürzzuschlag. Auf dem Bild steht er mit anderen Organisatoren am Schanzentisch.</span></p>
<p><span class="information">Unten können Sie durch die Sammlung klicken.</span>
<div class="grid-item" id="exhibit-image"><img src="../media/IMG_20210624_121654_long.jpg" class="img-fluid" alt="Sprungrichter an der Ganzsteinschanze">Sprungrichter an der Ganzsteinschanze. Organisatoren waren für den reibungslosen Ablauf der Veranstaltung verantwortlich. Sie versorgten Zuschauer, Athleten und Richter.</div>
<!--This adds the collection's objects.-->
{% for object in site.organiser %}
    {% include collection-button.html %}
{% endfor %}