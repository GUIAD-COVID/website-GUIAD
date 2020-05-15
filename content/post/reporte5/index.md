---
title: 'Reporte 5 del grupo GUIAD-COVID 19'
subtitle: ''
summary: 'Publicamos un nuevo reporte que analiza una aproximación lineal de un modelo SEIR, la cual permite analizar el comportamiento de la cantidad de infectados. Puede descargarse desde [Reportes técnicos](#publications).'

authors:
- guiad
tags:
- Reportes
categories:
- Reportes
date: "2020-05-15"
lastmod: "2020-05-15"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Créditos: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


En este nota se analiza una aproximación lineal de un modelo compartimental SEIR (Susceptible, Expuestos, Infectados, Recuperados) considerando los Infectados separados en dos grupos: Documentados y No Documentados. Esta aproximación (justificada por el bajo número de infectados registrados en Uruguay) permite de manera sencilla analizar el comportamiento de la cantidad de infectados. En particular, se pueden resolver explícitamente las ecuaciones involucradas y se obtienen soluciones que se expresan mediante combinaciones lineales de exponenciales, ajustando a los datos de Uruguay mediante un método de regresión no lineal. Se detectan tres dinámicas que se superponen  y generan la dinámica que observamos. De éstas, dos tienen coeficientes negativos y una coeficiente levemente positivo, lo que apoyaría la idea que el crecimiento observado es efectivamente subexponencial. Si los coeficientes se mantuvieran igual, la epidemia seguiría controlada. Estos ajustes permiten una predicción del número de individuos infectados con 20-30% de error con dos semanas de antelación y en condiciones de parámetros constantes, aunque no permiten efectuar predicciones sobre el efecto de cambios en el nivel de aislamiento social (como, por ejemplo, la vuelta de la actividad en el sector de la construcción). De todos modos modos, podrían usarse para detectar cambios en el comportamiento de la dinámica de la epidemia El reporte completo puede  descargarse desde [Reportes técnicos](#publications)