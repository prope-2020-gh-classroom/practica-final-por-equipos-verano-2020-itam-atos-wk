# Práctica final del propedéutico por equipo

## Integrantes:

|Integrante|User github|
|:--:|:--:|
|Aarón Torrijos Solís (project manager)|[https://github.com/atos-wk]()|
|Oscar Arturo Bringas López|[Acturio](https://github.com/Acturio)|

## Tema: 
Análisis de incidencia delictiva en la Ciudad de México mediante series de tiempo y análisis bayesiano 

## Descripción:
Usando los datos proporcionados por la Secretaría de Seguridad Ciudadana de la Ciudad de México, se realiza un análisis de series de tiempo para conocer el comportamiento, frecuencia y patrón de ocurrencia de delitos en la Ciudad de México. A través de este estudio se logra identificar los días en los que se reportan más delitos. Se observa la cantidad de delitos en cada una de las alcaldías de la Ciudad y se realiza un análisis de correlación entre la cantidad poblacional en cada alcaldía y el volumen de delitos reportados.

Adicionalmente, se realiza un análisis bayesiano que tiene por objetivo...

## Datos:
* [Delitos en la Ciudad de México](https://datos.cdmx.gob.mx/explore/dataset/carpetas-de-investigacion-pgj-cdmx/export/)

* [Índice y nivel de Marginación (CONAPO)](http://www.conapo.gob.mx/es/CONAPO/Datos_Abiertos_del_Indice_de_Marginacion)

* [Población en Ciudad de México (INEGI)](https://www.inegi.org.mx/programas/ccpv/2010/default.html#Tabulados)

## Lenguaje: 
R

## Librerías:

* library(dplyr)
* library(lubridate)
* library(magrittr)
* library(readr)
* library(forecast)
* library(tidyverse)
