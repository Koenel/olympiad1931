---
layout: collectionindex-de
title: Spectator Collection
permalink: /spectator-collection-de/
language: de
finder: collection-spectator
---

<h1>Willkommen in der Zuseher-Sammlung!</h1>
<p><span class="information">Internationale Sportveranstaltungen hatten das Ziel die Mitglieder der Arbeiterklasse anzuziehen und sie zu motivieren politisch aktiv zu werden. Allerdings wurde diese Veranstaltungen nicht immer von allen anderen Gesellschaftsschichten unterstützt, ging es doch um das Wohl der Arbeiterklasse und gesellschaftliche Veränderungen. Die Besucher der Wettbewerbe konnten billiger als üblich anreisen und mit etwas Glück sich auch ein Bett für den Aufenthalt in Mürzzuschlag sichern, um so auch am abendlichen Rahmenprogramm teilnehmen zu können.</span>
<p><span class="information"> Unten können Sie durch die Sammlung klicken.</span></p>
<div class="grid-item" id="exhibit-image"><img src="../media/bets-dneueblatt130206_long.png" class="img-fluid" alt="Zuschauer studieren den Streckenverlauf des Schirennens und wetten auf das Siegerteam">Zuschauer studieren den Streckenverlauf des Schirennens und wetten auf das Siegerteam.</div>
<!--This adds the collection's objects.-->
{% for object in site.spectator %}
    {% include collection-button.html %}
{% endfor %}