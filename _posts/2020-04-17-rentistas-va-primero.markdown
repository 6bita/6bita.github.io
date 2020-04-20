---
layout: post
title: "¡Rentistas va primero!"
description: "Todos quieren dar un pronostico sobre cuando se reanudara la actividad futbolistica este anio"
name: 2020-04-17-rentistas-va-primero.md
entrada: "3"
date: 2020-04-17T19:38
fecha: Abril 17, 2020
image: /images/Sci6Bitaeicon.png
author: El 6Ceibita
---

### ¡Rentistas va primero!

`Ronchi` de Sport 890, cundo recomienza?, Ja, ja, ja... `Moar` decia yas ta, ja, ja, ja... `Hanania` de futbol a lo PENAROL... tiro, me acuerdo ahora, la reanudacion era para mediados o fines de abril (sic) ja, ja, ja... ja, ja, ja...

Yo creo que habria que empezar a saborear la idea que ...`Rentistasss`!!! va primero, seniores y senioras. Si terminara asi: El `Campeonato Uruguayo`, `Rentistas` seria el campeon y ni `Penarol` ni `Nacional` irian a la `Copa Libertadores`. `Hanania` se desmayaria, queria en abril y se suspendio por este anio.

Y mira si los clubes cn desarrollo, votan suspender el futbol por este anio. ¿O no son ellos los que deciden el futbol yoruguiya?

En `Europa` se baraja que los campeonatos de `Europa` podrian terminar y no jugarse mas por este semestre, empezaria en agosto la temporada 20/21 y esta temporada quedaria como va la tabla de posiciones y el que va primero ganaria. Lo escuche en la `BBC Europe News` donde calculaban la perdida economica de la `Premiere League` este anio.

La `Libertadores` ya esta suspendida, segun los argentinos, basandose en que la `Champions` y la `Europa League` estan en la cuerda floja. El `Bayer Mũnich` es el unico que empezo a entrenar y yo creo que el `Barcelona` ya piensa en la proxima temporada basandose en su tecnico.

Y `Rentistas` va primero solo en `Uruguay` ¿Como van a votar los cuadros cn desarrollo? Y los periodistas uruguayos haciendo pronosticos para abril y mayo proximo quieren garpar y los bolasos que dicen en los programas deportivos, si andaran en la cuerda floja, el virus nos trajo una alarma importante, creo que es verdad que el mundo debe bajar un par de cambios!!!

### Tambien te puede interesar

{% for post in site.posts %}


{% if post.entrada == "1" %}


<div class="content">
  <img src="{{ post.image }}" class="picB floatleft" alt="" />
  {{ post.description }}
</div>
<div class="footer">
  <ul>
    <button type="button" class="btn btn-light" style="margin-right: 5px;"><center><li class="comments"><a href="{{ site.url }}/{{ post.url }}">Comentarios</a></li></center></button>
    <button type="button" class="btn btn-light" style="margin-right: 5px;"><center><li class="readmore"><a href="{{ site.url }}/{{ post.url }}">Mostrar Mas</a></li></center></button>
  </ul>
</div>

{% endif %}

{% endfor %}

<br>

{% for post in site.posts %}


{% if post.entrada == "2" %}


<div class="content">
  <img src="{{ post.image }}" class="picB floatleft" alt="" />
  {{ post.description }}
</div>
<div class="footer">
  <ul>
    <button type="button" class="btn btn-light" style="margin-right: 5px;"><center><li class="comments"><a href="{{ site.url }}/{{ post.url }}">Comentarios</a></li></center></button>
    <button type="button" class="btn btn-light" style="margin-right: 5px;"><center><li class="readmore"><a href="{{ site.url }}/{{ post.url }}">Mostrar Mas</a></li></center></button>
  </ul>
</div>

{% endif %}

{% endfor %}
