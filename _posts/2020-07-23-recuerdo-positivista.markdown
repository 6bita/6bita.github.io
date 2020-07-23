---
layout: post
title: "El chofo"
description: "Recuerdo al chofo y su afición positivista y dentro del gremio de
los soldadores ..."
name: 2020-07-23-recuerdo-positivista.markdown
entrada: "12"
date: 2020-07-23T01:30
fecha: Julio 23, 2020
image: /images/chofo.png
author: elceibita
lang: 'es-UY'
---

### El chofo

<img src="{{ site.url }}/images/chofo.png" width="480px">


Fue quemando los vagones uno a uno ...

En su oficio tenía que soldar caños, pero no usaba máscara y dos por tres le
caía una chispa en algún ojo. Uno lo tuvo a punto de perder. El oculista le dijo
que si le caía una chispa más, iba a perder la vista de ese ojo.

Creyó en la escuela y trató de organizarla, incluso consiguió componentes de
electrónica para los prácticos y nadie le dió mucha importancia. Yo también
puedo soldar en mi oficio, solo que componentes electrónicos, no caños. Pero
soy nervioso y me tiembla mucho el pulso, así que no soy muy bueno pero me
salvo de las chispas.


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
