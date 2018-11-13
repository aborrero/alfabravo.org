---
layout: post
title:  "Programar walkie-talkie Baofeng con CHIRP para aventuras"
date:   2017-09-30 20:14:33 +0200
tags:	[walkie-talkie]
---

![Walkie][walkie]

Si finalmente nuestra [elección para walkies de aventuras][elegir] es un 
aparato de la marca Baofeng, un mundo de posibilidades se abre ante nosotros.
El walkie-talkie suele venir configurado, o no, depende de donde lo compremos
y dependiendo del modelo en cuestión.

En mi caso, compré un Baofeng UV5R en una tienda online que no venia
pre-configurado, y compŕe otro en la web baofeng.es que sí venia
pre-configurado (con un coste adicional de 5€).

<!--more-->

En cualquier caso, para adaptarlo a nuestras aventuras, será interesante
realizar una configuración adicional.

* canales predeterminados
* niveles de umbrales, squelch y demás
* colores de pantallas (si el aparato tiene)
* configuraciones por defecto para sonidos y beeps
* establecer nombre del aparato (si lo soporta)

Para realizar la programación necesitamos un cable específico, que por un lado
conecta con el walkie-talkie y por el otro tiene USB para el ordenador.
Este cable es barato y se vende en multitud de tiendas online.

![Cable][cable]

El software que usamos para programar el aparato se llama [CHIRP][chirp], y es
[software libre][sw], muy potente. Está disponible para la mayoría de sistemas
operativos, pero mi recomendación es usar [Debian GNU/Linux][debian].

Antes de iniciar CHIRP, apagamos el walkie-talkie, conectamos el cable al
aparato y al ordenador por USB.
Iniciamos CHIRP y en el menú "Radio" seleccionamos "Descargar desde Radio".
Después de seguir las instrucciones que se nos muestran, tendremos disponibles
todos los parámetros de que dispone nuestro aparato.

![Frecuencias][freq]

Yo, en primer lugar, configuraría las memorias de canales. Es interesante, para
aventuras, guardar los canales típicos [PMR446][pmr], y con especial atención
al canal [PMR 7.7 de seguridad en montaña][pmr7].

Podemos configurar el aparato para que se inice por defecto con una
configuracion lista para usar, de manera que podamos encenderlo y usarlo
directamente.

![Configuraciones][conf]

La cantidad de opciones de configuración que tiene el Baofeng UV5R es muy
grande. Y debemos tener cuidado de no introducir configuraciones extrañas
que pudieran resultar en un mal funcionamiento del aparato.
De hecho, recomiendo que antes de realizar nuestra configuración, realicemos
una copia de la configuración de fábrica que trae el aparato, por si acaso.

La configuración se puede guardar y leer de ficheros de nuestro disco duro,
de manera que podamos aplicar la misma a distintos aparatos.

Una vez tengamos una configuración, será necesario _subirla_ al aparato usando
el menú "Radio" de CHIRP. Simple y eficaz.

[walkie]:	{{site.url}}/assets/zahara_pmr77.jpg
[conf]:		{{site.url}}/assets/20170930-01-chirp_conf.png
[freq]:		{{site.url}}/assets/20170930-02-chirp_freq.png
[cable]:	{{site.url}}/assets/20170930-03-cable.jpg
[elegir]:	{{site.url}}/2016/10/19/eligiendo-walkies.html
[chirp]:	http://chirp.danplanet.com/projects/chirp/wiki/Home
[sw]:		https://es.wikipedia.org/wiki/Software_libre
[debian]:	https://www.debian.org/
[pmr]:		https://es.wikipedia.org/wiki/PMR446
[pmr7]:		http://www.canal77pmr.com/
