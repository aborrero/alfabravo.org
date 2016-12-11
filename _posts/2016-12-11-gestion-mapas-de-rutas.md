---
layout: post
title:  "Rutas y trazas GPS en el smartphone"
date:   2016-12-11 14:30:00 +0200
tags:	[gps, mapas, android]
---

![Traza mapa de ruta Mulhacen][traza_mulhacen]

Para llevar un control y poder usar de manera efectiva rutas y trazas GPS
en aventuras en la naturaleza hay dos alternativas principales: usar un
dispositivo dedicado o usar un smartphone.

La opción del smartphone es más asequible para principiantes, pero tiene la
contrapartida de que estás solo frente a un mar de aplicaciones, mapas y
configuraciones que tendrás que hacer tu mismo.

Con el paso del tiempo, he conseguido montar mi propio flujo de trabajo para
estos casos, y voy a describirlo en este artículo.

<!--more-->

Lo primero, nuestro smartphone necesitará tener GPS (o Glonass) y disponer de
cierto almacenamiento interno y batería, pues son los principales elementos
que usaremos. No es mala idea llevar, además, una batería externa.

Necesitamos alguna aplicación que nos permita hacer uso del
GPS, de nuestras trazas y de los mapas.
Después de probar bastantes de ellas, he llegado a la conclusión de que una de
las mejores (la que se ajusta a mis necesidades) es
[View Ranger][play_viewranger]. Otra buena alternativa es
[OsmAnd][play_osmand].

View Ranger permite descargar trazas desde la propia aplicación, pero cuestan
dinero. Y el mio es un enfoque low-cost :-)

![Descargando desde Wikiloc][descarga]

Para conseguir las trazas y rutas, busco en internet, [Wikiloc][wikiloc]
o similares, de donde descargo los ficheros **.gpx**, con todos los
waypoints posibles.

Una vez conseguido el fichero .gpx, lo importo en View Ranger, usando la opción
"Importar desde un dispositivo externo", que nos permitirá seleccionar
cualquier fichero del dispositivo (e incluso desde Dropbox o similares).

![Importando traza en View Ranger][viewranger_import]

Una vez que se ha importado el fichero .gpx, si vamos al apartado personal de
View Ranger, podemos tener una visión de todas las trazas que tenemos en el
dispositivo.

Al acceder a los detalles de una traza podemos ver los detalles, y
mostrarla/ocultarla en el mapa (que será lo que haremos para usar la traza una
vez que estemos en la aventura).

![Mis tracks en View Ranger][viewranger_tracks]

Es interesante navegar por el mapa hasta la zona de la traza, de manera que se
nos descarge automáticamente el mapa de la zona. Esto nos permitirá usarlo
más adelante cuando el smartphone no tenga conexión a internet.

View Ranger dispone de muchas más opciones para su manejo: seguimiento de
rutas, control de trayectos, etc.. Es importante saber manejar un poco la
aplicación antes de empezar la aventura.

Me gustaría dejar una referencia al
[Grupo de Montaña - Patapumparriba][gmpatapumparriba], un blog del que he
conseguido algunas trazas GPS magníficas para Andalucía (y hay también
para otros muchos lugares).

En su dia, mi complañero Javi me enseño la aplicación
[GPS Status][play_gpsstatus], que es un complemento interesante para llevar
junto con View Ranger.

[traza_mulhacen]:		{{site.url}}/assets/traza_mulhacen.png
[play_osmand]:			https://play.google.com/store/apps/details?id=net.osmand
[play_viewranger]:		https://play.google.com/store/apps/details?id=com.augmentra.viewranger.android
[descarga]:			{{site.url}}/assets/descarga_wikiloc.png
[viewranger_import]:		{{site.url}}/assets/viewranger_import.png
[viewranger_tracks]:		{{site.url}}/assets/viewranger_tracks.png
[gmpatapumparriba]:		http://gmpatapumparriba.blogspot.com.es/
[play_gpsstatus]:		https://play.google.com/store/apps/details?id=com.eclipsim.gpsstatus2
[wikiloc]:			http://es.wikiloc.com/
