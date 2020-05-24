---
title: Estadísticas por departamento
linktitle: Descripción y enlaces
toc: true
type: docs
date: "2020-04-12T00:00:00Z"
draft: false
menu:
  example:
    name: Estadísticas por departamento
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---

Se publican dos conjuntos de datos: uno que tiene el total de casos activos por departamento para cada fecha, y otro que tiene el detalle por departamento y fecha de casos activos, casos nuevos, fallecidos y recuperados (a partir del 29-04-2020).


## Origen de los datos

Hasta el 7/4/2020 los datos son extraídos de los [informes de situación publicados por el MSP](https://www.gub.uy/sistema-nacional-emergencias/comunicacion/noticias/informacion-interes-actualizada-sobre-coronavirus-covid-19-uruguay).
El valor `N/A` se utiliza para indicar valores no disponibles o faltantes en los reportes.

A partir del 9/4/2020 los datos se extraen del [Visualizador de casos coronavirus COVID-19 en Uruguay] (https://www.gub.uy/sistema-nacional-emergencias/pagina-embebida/visualizador-casos-coronavirus-covid-19-uruguay)



## Enlaces

* [Cantidad de activos por departamento en formato CSV](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY_porDepto.csv)

* [Datos detallados por departamento en formato CSV](https://github.com/GUIAD-COVID/datos-y-visualizaciones-GUIAD/blob/master/datos/estadisticasUY_porDepto_detalle.csv)


## Metadatos

### Metadatos para los datos detallados de cada departamento

Columna   | Descripción
----------|---------------------------------------------------
fecha	  |día calendario en que se informaron estos datos
departamento	    | departamento de Uruguay 
enCurso |	cantidad de personas que actualmente cursan la infección
cantCasosNuevos| **cantidad de casos nuevos** <sup>2</sup> identificados ese dia 
cantFallecidos |	cantidad de fallecidos reportados ese día
acumFallecidos |acumulado de la cantidad de fallecidos hasta ese día
cantRecuperados	| cantidad de pacientes recuperados reportados ese día
acumRecuperados |acumulado de la cantidad de recuperados hasta ese día
acumCasos| cantidad de casos acumulados hasta el momento 


<sup>2</sup> La cantidad de casos nuevos se computa como enCurso(hoy)-enCurso(ayer)+cantRecuperados(hoy)+cantFallecidos(hoy)

### Metadatos para el total de activos por departamento

Columna   | Descripción
----------|---------------------------------------------------
fecha	  |día calendario en que se informaron estos datos
día	 | día correlativo desde el 13 de marzo, cuando se anunció el primer caso
cantDeptosAfectados	|cantidad de departamentos que presentan alguna persona con infección en curso
Artigas (UY-AR )| **cantidad de casos**<sup>1</sup> en el departamento de Artigas (UY-AR ) 
Canelones (UY-CA )| cantidad de casos en el departamento de Canelones (UY-CA )
Cerro Largo (UY-CL )|cantidad de casos en el departamento de Cerro Largo (UY-CL )
Colonia (UY-CO )|cantidad de casos en el departamento de Colonia (UY-CO )
Durazno (UY-DU )|cantidad de casos en el departamento de Durazno (UY-DU )
Flores (UY-FS )|cantidad de casos en el departamento de Flores (UY-FS )
Florida (UY-FD )|cantidad de casos en el departamento de Florida (UY-FD )
Lavalleja (UY-LA )|cantidad de casos en el departamento de Lavalleja (UY-LA )
Maldonado (UY-MA )|cantidad de casos en el departamento de Maldonado (UY-MA )
Montevideo (UY-MO )|cantidad de casos en el departamento de Montevideo (UY-MO )
Paysandú (UY-PA )|cantidad de casos en el departamento de Paysandú (UY-PA )
Río Negro (UY-RN )|cantidad de casos en el departamento de Río Negro (UY-RN )
Rivera (UY-RV )|cantidad de casos en el departamento de Rivera (UY-RV )
Rocha (UY-RO )|cantidad de casos en el departamento de Rocha (UY-RO )
Salto (UY-SA )|cantidad de casos en el departamento de Salto (UY-SA )
San José (UY-SJ )|cantidad de casos en el departamento de San José (UY-SJ )
Soriano (UY-SO )|cantidad de casos en el departamento de Soriano (UY-SO )
Tacuarembó (UY-TA )|cantidad de casos en el departamento de Tacuarembó (UY-TA )
Treinta y Tres (UY-TT )|cantidad de casos en el departamento de Treinta y Tres (UY-TT )

<sup>1</sup> La cantidad de casos se reporta de la siguiente manera:

Antes del 9/4/2020:
* SI indica que hay algún caso reportado a la fecha
* 0 si no hay hasta el momento casos reportados

Luego del 9/4/2020
* el número indica la cantidad de casos activos a esa fecha en ese departamento, los recuperados se van restando.





