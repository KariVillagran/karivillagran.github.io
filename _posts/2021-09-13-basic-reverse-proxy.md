---
layout: post
title: Basic - Proxy
subtitle: Red
cover-img: /assets/img/path.jpeg
thumbnail-img: /assets/img/thumb.jpeg
share-img: /assets/img/path.jpeg
tags: [nginx]
---

En este articulo me gustaria abordar el desarrollo de un tutorial muy simple de como configurar tu propio proxy reverso.

## ¿Que es un proxy?
Imagina que estas frente a un rio y necesitas pasar desde el lado A hacia el lado B. Probablemente necesitaras buscar un puente. Cuando llegas al puente e intentas cruzarlo ves una caseta de guardia que, sin tu saberlo, esta mirando todo lo que pasa de lado a lado en el puente.

Dada esa analogia, un proxy funciona muy similar, ya que aparece como un punto intemerdio de conexion entre tu origen (probablemente tu computador) y un destino en internet (quizas instagram, google, etc).

## ¿Que es un proxy reverso?
Si en la analogia anterior queriamos ir desde lado A hacia lado B, esto se interpreta de igual forma en el caso del proxy reverso, pero valga la redundancia, inversamente. O sea, vas desde el lado B hacia el lado A.

## ¿Que problema busca resolver?

* Cache
* Control de acceso
* Equilibrio de carga
* Filtrado de contenido


