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

A partir de los comunicados publicados diariamente por el [SINAE](https://www.gub.uy/sistema-nacional-emergencias/comunicacion/comunicados) y de los datos disponibles diariamente en el [Visualizador de casos coronavirus COVID-19 en Uruguay](https://www.gub.uy/sistema-nacional-emergencias/pagina-embebida/visualizador-casos-coronavirus-covid-19-uruguay) extraemos variables epidemiológicas sobre COVID-19 en Uruguay, y las publicamos como Datos Abiertos.

Los conjuntos de datos, actualizados diariamente, son los siguientes:

* [Estadísticas de todo el pais](./estadisticasuy/) - :chart_with_downwards_trend:[Visualizar](/estadisticasuy.html)
* [Estadísticas por departamento](./estadisticasuy_dpto/)


A partir de estos datos calculamos el índice p7 por departamento (media de casos nuevos en los últimos 7 días cada 100.000 habitantes), el cual utilizamos para realizar esta [animación](/evolucionP7.html). Disponibilizamos la serie temporal desde el 6/5/2020 al 2/12/2020.

* [Descargar la serie temporal en formato CSV](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/P7.csv)
