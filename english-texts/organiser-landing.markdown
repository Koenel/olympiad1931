---
layout: collectionindex
title: Organiser Collection
permalink: /organiser-collection/
language: en
finder: collection-organiser
---
<h1>Welcome to the organiser collection!</h1>
<p><span class="information">An event like the Second Workers' Winter Olympics require a solid organisation and a reliable team. Theodor Hüttenegger was a key figure in the organisation team of the events in Mürzzuschlag. Hüttenegger organised volunteering activities such as building the ski jump before the games, and he was responsible for all technical issues during the event. Later in life, he founded the Winter!Sport!Museum! in Mürzzuschlag. In the picture, you can see him standing with other organisers and judges on the jury stand at the ski jump.</span>
<p><span class="information">Below, you can click through the collection content.</span></p>
<div class="grid-item" id="exhibit-image"><img src="../media/IMG_20210624_121654_long.jpg" class="img-fluid" alt="Judges at the Ganzsteinschanze">Judges at the Ganzsteinschanze ski jump. Organisers were responsible for a smooth conduction of the event. They took care of spectators, athletes and judges.</div>
<!--This adds the collection's objects.-->
{% for object in site.organiser %}
    {% include collection-button.html %}
{% endfor %}