---
layout: collectionindex
title: Spectator Collection
permalink: /spectator-collection/
language: en
finder: collection-spectator
---
<h1>Welcome to the spectator collection!</h1>
<p><span class="information">International sport events were created to attract members of working class and motivate them to become politically active. However, these activities were not always met with unanimous support but also with reservations from other groups in society. Those who wanted to visit and watch the competitions could travel cheaper than usual and with a bit of luck, they could secure a bed to stay for several days and enjoy the evening events too.</span>
<p><span class="information">Below, you can click through collection content.</span></p>
<div class="grid-item" id="exhibit-image"><img src="../media/bets-dneueblatt130206_long.png" class="img-fluid" alt="Spectators study the skiing track map and place bets on the winning teams">Spectators study the skiing track map and place bets on the winning teams.</div>
<!--This adds the collection's objects.-->
{% for object in site.spectator %}
    {% include collection-button.html %}
{% endfor %}