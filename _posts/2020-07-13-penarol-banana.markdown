---
layout: post
title: "La banana Peñarol"
description: "Todos los cuadros de fútbol dan pérdida en el mundo, así y todo
Peñarol fué banana"
name: 2020-07-13-penarol-banana.markdown
entrada: "10"
date: 2020-07-13T08:00
fecha: Julio 13, 2020
image: /images/banana.png
author: elceibita
lang: 'es-UY'
---

### La banana Peñarol

<img src="{{ site.url }}/images/banana.png" width="480px">


Yo creo que Peñarol fue bien banana en pagar las deudas que tenía con Damiani y
con Evaristo. A ver se supone que Peñarol prefiere pedir préstamo a particulares
porque se supone que como son peñarolenses, no van a caducar y el interés será
benévolo. Digo yo!

La alternativa no sería sacar préstamo del República porque teniendo en cuenta
que todos los clubes de fútbol dan pérdida supongo el interés sería muy alto y
cuando empiezan a vencerse las amortizaciones sería tan grande el interés que le
rematarían todo a Peñarol (digo, de valor que tenga!)

Lo que debería haber hecho Peñarol sería pagarle a Damiani $500.000 y a Evaristo
lo mismo $500.000 y dejar el resto para que lo refinancie la próxima directiva.

Ni Evaristo ni Damiani, como buenos peñarolenses habrían dicho nada y se habría
reinvertido el dinero por los pases de Darwin y de Brian de nuevo en el plantel.

Esto no es tan difícil de entender, lo que significaría tener un par de millones
para armar un plantel competitivo y poder darle continuidad al mismo (el gran
debe de Damiani y de Barrera!)

<br>

### Ver también

<br>

{% for post in site.posts %}


{% if post.entrada == "10" %}


<div class="content" style="margin-top: 35px">
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


{% if post.entrada == "5" %}


<div class="content" style="margin-top: 35px">
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
