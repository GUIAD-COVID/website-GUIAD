---
title: Estadísticas de todo el pais
linktitle: Descripción y enlaces (todo el pais)
toc: true
type: docs
date: "2020-04-12T00:00:00Z"
draft: false
menu:
  example:
    name: Estadísticas de todo el pais
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---
## Metadata

Columna   | Descripción
----------|---------------------------------------------------
fecha	  |dia calendario en que se informaron estos datos
dia	    | dia correlativo desde el 13 de marzo, cuando se anunció el primer caso
cantTest  |	**cantidad de tests**<sup>1</sup> realizados ese dia
acumTest	|acumulado de la cantidad de tests realizados hasta ese dia
cantTestPositivos |	cantidad de tests positivos de ese dia
acumTestPositivos	  |acumulado de la cantidad de tests positivos hasta ese dia
cantCTI  |	cantidad de pacientes reportados en CTI ese dia
cantCI  |	cantidad de pacientes reportados en CI ese dia
cantFallecidos |	cantidad de fallecidos reportados ese dia
acumFallecidos |acumulado de la cantidad de fallecidos hasta ese dia
cantRecuperados	| cantidad de pacientes recuperados reportados ese dia
acumRecuperados |acumulado de la cantidad de recuperados hasta ese dia

## Origen de los datos

Datos extraídos de los [informes de situación publicados por el MSP](https://www.gub.uy/sistema-nacional-emergencias/comunicacion/noticias/informacion-interes-actualizada-sobre-coronavirus-covid-19-uruguay).
El valor `N/A` se utiliza para indicar valores no disponibles o faltantes en los reportes.

<sup>1</sup> Notar que siempre se hace referencia a cantidad de tests y no cantidad de personas. Sobre algunas personas se realizan tests más de una vez por lo que la cantidad de infectados es menor o igual a la cantidad de tests positivos.


## Enlaces

* [Datos en formato CSV](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY.csv)
* [Metadata](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/explica_estadisticasUY.md)