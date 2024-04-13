---
title: 'Espaciadores autodirigidos: dilucidando las funciones no canónicas de los sistemas CRISPR'
date: 2024-04-12
author:
  - name: Ana María López Pérez
    email: ana.lopez23@udea.edu.co
    url: '/members/current/ana-maría-lópez-pérez/ana-maría-lópez-pérez.md'
  - name: Haminton Alexander Poveda Alonso
    email: alexander.poveda@udea.edu.co
    url: '/members/current/haminton-alexander-poveda-alonso/haminton-alexander-poveda-alonso.md'
description: "¿Autoinmunidad? ¿Nuevas funciones desconocidas? ¿Qué misterios
encierran los sistemas CRISPR en bacterias? ¿Tienen relación con la
resistencia a los antibióticos?"
image: crispr.webp
bibliography: refs.bib
categories:
  - Biología computacional
  - CRISPR
  - Bioinformática
  - Investigación
lightbox: true
---

## ¿Qué son los sistemas CRISPR?

En los últimos años, CRISPR ha tomado gran relevancia en el ámbito de la
biología gracias al enorme potencial en edición genómica mostrado por las
“tijeras genéticas” CRISPR-Cas9, que fueron desarrolladas por Emmanuelle
Charpentier y Jennifer A. Doudna lo que las hizo acreedoras del premio Nobel
de Química en el año 2020; su trabajo publicado en el año 2012 titulado: *"A
programmable dual-RNA-guided DNA endonuclease in adaptive bacterial
immunity"* dio la vuelta al mundo y fue de gran importancia para el
desarrollo de este método de edición genómica. El descubrimiento principal
para la creación de esta herramienta se dio por casualidad: durante los
estudios de Emmanuelle Charpentier sobre el patógeno *Streptococcus pyogenes*,
Charpentier identificó que una molécula previamente conocida como ARNtracr
era parte de los sistemas CRISPR/Cas cuya función **canónica** es conferir
resistencia a patógenos externos como los virus, con base en esto
Charpentier y Doudna recrearon las “tijeras genéticas” de las bacterias en
un tubo de ensayo y revolucionaron la historia de la medicina. [Alcalde,
2020]

Los sistemas CRISPR/Cas funcionan como sistemas inmunes en las bacterias y
arqueas; estos les permiten defenderse de virus que las han infectado
previamente: ¡tienen memoria! CRISPR por sus siglas en inglés Clustered
Regularly Interspaced Short Palindromic Repeats son  una serie de secuencias
de ADN presentes en el genoma de algunos organismos procariotas, esta serie
de regiones son responsables del funcionamiento del sistema inmune que
poseen estos organismos contra la integración de material genético exógeno.
Este complejo sistema está formado por el **operón Cas** que alberga los
datos genéticos necesarios para la producción de las endonucleasas Cas
(CRISPR associated) junto con otras proteínas cruciales para el
funcionamiento del sistema CRISPR/Cas, además de la **región CRISPR** que
contiene repeticiones alternadas con cortas secuencias espaciadoras, las
cuales son incorporadas a partir de fuentes externas durante infecciones,
estos espaciadores se unen por complementariedad a la secuencia objetivo
guiando así a las proteínas Cas asociadas y promoviendo la degradación del
material genético exógeno.

![@ghorbani2021](crispr.webp)

## El fenómeno del "self-targeting"

Aunque la principal función conocida de los sistemas CRISPR sea la defensa
ante virus, también se han encontrado espaciadores autodirigidos
(“self-targeting spacers”), es decir, que son complementarios a partes del
propio genoma de la bacteria y presuntamente resultan en una autoinmunidad,
esto representa una paradoja para la cual se han propuesto dos posibles
soluciones: la primera es que sean “accidentes” biológicos que ocurren al
azar y a los cuales la bacteria tiene que hacer frente, mientras que la
segunda propone que estén relacionados con **funciones no canónicas**, es
decir diferentes a la función inmunitaria de los sistemas CRISPR; estas
funciones alternativas son un área de investigación muy poco explorada en
biología que podría tener importantes implicaciones en cuanto al
conocimiento de los sistemas CRISPR y el desarrollo de interesantes
herramientas moleculares.  [@wimmer2020].

![](self-targeting.png)

El objetivo de esta línea de investigación es ahondar en el conocimiento de
las funciones no canónicas de los sistemas CRISPR y ayudar a dilucidar la
paradoja de los espaciadores autodirigidos mediante el uso de herramientas
computacionales para el análisis de datos genómicos disponibles en línea. Te
invitamos a unirte a este fascinante proyecto de investigación, en el que
fusionamos diferentes áreas del conocimiento científico, ¡tu participación
podría contribuir significativamente a la comprensión de estos procesos
biológicos!
