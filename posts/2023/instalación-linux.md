---
title: 'Tutorial de instalación de Linux'
date: 2023-09-21
author: Juan Camilo Arboleda Rivera
permalink: /posts/2023/09/instalar-linux/
categories:
  - Biología computacional
  - Linux
  - Tutorial
  - Educación
---

¡Hola a todos! En este tutorial hablaremos sobre el proceso de instalación
de Linux que nos permitirá tener nuestro equipo con Windows y Linux al mismo
tiempo.

Además de leer este tutorial te recomiendo también que veas el [video
tutorial](#video-tutorial) **antes de iniciar la instalación** para que
tengas una idea más clara sobre el proceso.

## Paso 1: Descargar una distribución de Linux

Linux tiene muchas versiones diferentes, también conocidas como
distribuciones o *distros*. Cada una tiene sus particularidades o está
diseñada para un propósito en específico. A continuación encontrarás enlaces
a algunas distribuciones:

Distribuciones diseñadas para computadores viejos o con pocos recursos:

- [Linux Lite](https://www.linuxliteos.com/index.html)
- [Lubuntu](https://lubuntu.me/)
- [Puppy Linux](http://puppylinux.com/)
- [Linux Mint](https://linuxmint.com/)

Distribuciones más usadas:

- [Ubuntu](https://ubuntu.com/)
- [Debian](https://www.debian.org/index.es.html)
- [Fedora](https://fedoraproject.org/es/)
- [OpenSUSE](https://es.opensuse.org/Bienvenidos_a_openSUSE.org)

Distribuciones enfocadas en educación o escuelas:

- [Huayra](https://huayra.educar.gob.ar/)
- [Edubuntu](https://www.edubuntu.org/)
- [openSUSE:Education-Li-f-e](https://es.opensuse.org/openSUSE:Education-Li-f-e)
- [DoudouLinux](https://www.doudoulinux.org/web/espanol/index.html)

Otras distribuciones:

- [Kali Linux](https://www.kali.org/): Distribución especializada en
  seguridad informática e informática forense.
- [Tails](https://tails.net/index.es.html): Distribución enfocada en la
  privacidad y el anonimato. Busca promover el libre acceso al internet y
  evitar la vigilancia y la censura.

Luego de que hayas elegido cuál distribución te gusta solo tienes que
descargar el archivo `.iso` que normalmente se ofrece en su página web de
manera gratuita.

## Paso 2: Crear una USB booteable

El siguiente paso es conseguirte una USB. El tamaño de esta USB depende de
la distribución de Linux que vayas a instalar, lo importante es que el
archivo `.iso` quepa en la memoria; así que si descargaste un archivo de 4.7
GB tienes que conseguir una USB con una capacidad mayor, por ejemplo una de
8 GB.

Es importante que la USB se pueda formatear, así que debes hacer una copia
de los datos que no quieras perder, porque el siguiente paso es usar un
programa como [Etcher](https://etcher.balena.io/) o
[Rufus](https://rufus.ie/es/) para escribir el archivo `.iso` en la USB de
manera que la USB sea booteable, es decir, que tu computador pueda usarla
para arrancar el sistema.

## Paso 3: Liberar espacio en el disco duro

Ahora hay que liberar espacio en el disco ya que ahí es donde vamos a
instalar luego el sistema Linux. Esto puede hacerse fácilmente desde Windows
abriendo el explorador de archivos, dando clic derecho en "Este quipo",
luego en "Administrar" y luego en "Administrar discos". Allí podrás ver las
particiones que tienes, elije la que tenga suficiente espacio para liberar
aproximadamente 30 GB. Dale click derecho a la partición y luego en "Reducir
volumen". Te saldrá una ventana donde debes especificar el tamaño a reducir,
que en nuestro caso sería 30000 MB (es decir, aproximadamente 30 GB), y
luego das click en "Reducir".

Eso sería todo, ahora verás un nuevo espacio que dice "No asignado". NO es
necesario hacer pasos adicionales como crear una partición en el espacio
liberado.

También puedes ver el siguiente video donde se muestra el proceso. Puedes
saltarte el final del video desde la parte donde dan click a "Nuevo volumen
simple":

<iframe width="560" height="315" src="https://www.youtube.com/embed/s2TKizTY4s4" title="Cómo reducir y crear particiones en Windows 10" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

::: {.callout-note}
**Problemas liberando espacio:**
Al intentar liberar espacio en tu disco te puedes encontrar con que a pesar
de que tienes más de 30 GB disponibles, no puedes liberar esa cantidad de
espacio. Esto puede deberse a que tu disco duro está fragmentado y lo que
debes hacer es
[desfragmentarlo](https://www.xataka.com/basics/desfragmentar-el-disco-duro-como-se-hace-y-para-que-sirve).
:::

## Paso 4: Acceder a la BIOS

Con el nuevo espacio en el disco duro listo para instalar Linux en él,
solo tenemos que arrancar nuestro computador desde la USB que creamos en el 
[paso 2](#paso-2-crear-una-usb-booteable). Para esto debemos buscar en
Google cómo acceder a la BIOS en nuestro modelo de computador, puesto que el
proceso puede ser diferente entre diferentes equipos, pero básicamente
consiste en apagar el equipo, luego apretar el botón de encendido y
rápidamente apretar continuamente una tecla como F2 o F12.

Luego de hacer procede a apagar tu equipo, luego conecta la USB con Linux y
luego procede a acceder a la BIOS.

Cada BIOS es diferente, pero debes buscar una sección llamada "Boot" y
desde allí indicarle a tu computador que arranque el sistema desde la USB.

## Paso 5: Iniciar el proceso de instalación

Luego de configurar la BIOS, debes guardar los cambios y salir de la BIOS.
Tu computador iniciará el arranque pero lo hará desde la memoria USB en
lugar de iniciar Windows. Te aparecerá una pantalla donde puedes iniciar
Linux y su proceso de instalación.

Para el resto de instrucciones sobre el proceso te remito al siguiente video
que está muy bien explicado. Debes poner atención sobre todo a la parte
donde se elige el espacio de disco duro donde se va a instalar Linux, no
vaya a ser que formatees la partición de Windows y pierdas todos tus
archivos.

¡Mucha suerte con el proceso y disfruta de tu nuevo sistema libre!

::: {.callout-note}
**Problemas con RST:** Algunos computadores no permiten instalar Linux si
está habilitada la tecnología de RST (Rapid Storage Technology). En [este
video](https://youtu.be/wDrCaAdGuMk) se explica la solución, aunque en
nuestro grupo no la hemos probado y deberías documentarte muy bien sobre el
tema antes de intentarlo.
:::

## Video tutorial

<iframe width="560" height="315" src="https://www.youtube.com/embed/yMgzz1fvVCc" title="Linux &amp; Windows, Instalación Dual Boot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
