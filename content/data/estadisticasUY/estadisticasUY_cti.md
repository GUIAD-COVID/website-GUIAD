---
title: Estadísticas sobre ocupación de CTI
linktitle: Descripción y enlaces
toc: true
type: docs
date: "2021-04-11T00:00:00Z"
draft: false
menu:
  example:
    name: Estadísticas sobre CTI
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

## Origen de los datos

Los datos son extraídos de los [informes de situación publicados por la Sociedad Uruguaya de Medicina Intesiva](https://sumi.uy/reporte-historico-de-estadisticas/).


## Enlaces

* [Estadísticas diarias de ocupación de CTI en formato CSV](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY_cti.csv)


## Metadatos


Columna   | Descripción
----------|---------------------------------------------------
id	  |autonumerado
fecha	  |día calendario en que se informaron estos datos
cant_pacientes| cantidad de pacientes con COVID-19 en CTI
ocupacion_total	| porcentaje de camas de CTI ocupadas
ocupacion_covid	| porcentaje de camas de CTI ocupadas con pacientes con COVID-19 
camas_operativas	| cantidad de camas de CTI operativas en todo el pais
camas_ocupadas	| cantidad de camas de CTI ocupadas en todo el pais
ingresos	| cantidad de pacientes con COVID-19 que ingresaron a CTI en el dia de la fecha
fallecimientos	| cantidad de pacientes con COVID-19 que estaban en CTI y fallecieron en el dia de la fecha
altas_medicas	| cantidad de pacientes con COVID-19 que estaban en CTI y fueron dados de alta en el dia de la fecha

