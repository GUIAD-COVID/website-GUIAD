---
# Course title, summary, and position.
linktitle: Estadísticas epidemiológicas de Uruguay
summary: Publicación como datos abiertos de los datos reportados por el SINAE.
weight: 1

# Page metadata.
title: Estadísticas epidemiológicas de Uruguay
date: "2020-04-12T00:00:00Z"
lastmod: "2020-04-12T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Descripción
    weight: 1
---


 
## Descripción

A partir de los comunicados publicados diariamente por el [SINAE](https://www.gub.uy/sistema-nacional-emergencias/comunicacion/comunicados) y de los datos disponibles diariamente en el [Visualizador de casos coronavirus COVID-19 en Uruguay](https://www.gub.uy/sistema-nacional-emergencias/pagina-embebida/visualizador-casos-coronavirus-covid-19-uruguay) extraemos variables epidemiológicas sobre COVID-19 en Uruguay, y las publicamos como Datos Abiertos. Además, extraemos y publicamos la información sobre ocupación de CTI que publica a diario la [Sociedad Uruguaya de Medicina Intesiva (SUMI)](https://sumi.uy/)


Los conjuntos de datos son los siguientes:
* [Estadísticas de todo el pais](./estadisticasuy/) 
* [Estadísticas por departamento](./estadisticasuy_dpto/)
* [Estadísticas de fallecimientos](./estadisticasuy_fallecidos/)
* [Estadísticas de CTI (SUMI)](./estadisticasuy_cti/)

A partir de los casos nuevos reportados por el SINAE calculamos el índice p7 a nivel nacional y por departamento (media de casos nuevos en los últimos 7 días cada 100.000 habitantes).

* [Serie temporal de P7 nacional](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY_p7nacional.csv)
* [Serie temporal de P7 por departamento](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY_p7.csv)


En base a todos estos conjuntos de datos actualizamos diariamente una serie de :chart_with_downwards_trend:[visualizaciones](/visual/visualesuy)

[Aquí](/evolucionP7.html) se puede ver una animación de la evolución del P7 a nivel departamental entre Mayo 2020 y Marzo 2021.