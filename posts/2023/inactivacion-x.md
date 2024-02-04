---
title: 'Proyecto de la inactivación del X'
date: 2023-10-02
permalink: /posts/2023/10/inactivacion-x/
author: María de los Ángeles Benavides Guaca
categories:
 - Inactivación del X
 - Biología computacional
bibliography: xci.bib
---

Breve introducción al mecanismo de inactivación del cromosoma X en mamíferos
placentarios.

## Búsqueda del factor autosómico responsable del X activo en la lionización

La lionización, nombre por el que también se conoce **el silenciamiento del
cromosoma X** en hembras mamíferas placentarias fue descubierto por la
genetista **Mary Lyon** en 1961 [@lyon1961]. Es un proceso crucial en el temprano
desarrollo embrionario porque produce la **igualación de expresión de
genes** ya que el sexo en estos organismos esta definido por la combinación
de un par de cromosomas sexuales *X* y *Y*, hembras XX y machos XY. El
cromosoma X, que posee al rededor de 1000 genes más que el Y, lo supera con
creces, por lo que el silenciamiento de uno de los X en las mamíferas es
uno de los tantos mecanismos de dosis de compensación que se han
desarrollado en animales que tienen este problema.

El resultado final es la presencia de un cromosoma X activo y otro inactivo
en la mayoría de sus genes, convertido en un **cuerpo de Barr** [@barr1949].

![corpusculo de Barr](https://slideplayer.es/14598364/90/images/slide_10.jpg)

En el caso de organismos diploides, para llegar a la inactivación se debe
pasar anteriormente por una serie de pasos de *conteo* de los cromosomas X
que posee la célula respecto a sus autosomas. Una vez la celula ha censado
la presencia de más de un cromosoma X respecto a su juego de cromosomas 2n
recurre a la *elección* de cual de ellos silenciará y dará *inicio* a la
expresión del **Xist**, factor clave de la inactivacion, desde el futuro X
inactivo. El producto de ARN del Xist tendrá un *espacimiento* a lo largo de
todo el cromosoma, promoviendo la cascada de inactivación que conlleva una
serie de modificaciones epigenéticas que incluyen la modificación de
histonas, metilaciones de ADN y, que finalemnte puede heredarse a las
futuras células hijas y mantenrse a lo largo de la vida post-embrionaria del
organismo mediante el *establecimiento*.

Aquí nos centramos en los pasos de conteo y elección de los futuros
cromosomas x activo **Xa** e inactivo **Xi**, basándonos en la evidencia de
su relación con los autosomas, a razón de la presencia de un solo X activo
en organismos diploides con trisomía del X, pero que se puede presentar dos
Xa en los casos de tetraploidía. Se estima que esta relacion está dada por
un represor sensible a la dosis con origen en los autosomas dadas las
anteriores proporciones según los juegos de cromosomas que posea la célula.

![conteo de cromosomas X en relación a los autosomas](https://www.researchgate.net/publication/316079372/figure/fig1/AS:482594723766273@1492070956423/The-XIST-repressor-model-for-the-single-active-X-Our-model-depicts-the-putative-dosage.png)

En adición, dada la amplitud de los genomas, es necesario reducir los
candidatos a este factor, por lo que nos podemos referir a una serie de
estudios recientes en genomas humanos que sugiere que este factor puede
encontrarse en el cromosoma 19 entre una región de 4.5 a 12.5 MB en el brazo
corto y otra de 41 a 41.5 MB en el brazo largo del cromosoma [@migeon2017].

![Regiones de interés en el cromosoma 19 humano](https://journals.plos.org/plosone/article/figure/image?size=inline&id=10.1371/journal.pone.0170403.g003)

Nuestro objetivo es hallar este factor de conteo autosómico mediante el
análisis con herramientas computacionales y bases de datos disponibles en
línea.

