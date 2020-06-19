---
title: 'Reporte 7: El efecto de la movilidad en la propagación de la epidemia'
subtitle: ''
summary: '¿Un aumento en la movilidad implica un aumento de la tasa de contagio? Puede descargarse desde [Reportes técnicos](/#publications).'

authors:
- guiad
tags:
- Reportes
categories:
- Reportes
date: "2020-06-19"
lastmod: "2020-06-19"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Analizamos la  siguiente pregunta: ¿un aumento en la movilidad implica un aumento de la tasa de contagio?  Concluimos, con un poco de sorpresa, 
que un aumento de la movilidad tiene un efecto reducido en el aumento de la tasa de contagio. El método utiliza una aproximación lineal de un modelo compartimental de tipo SEIR, 
que permite calcular de forma analítica la solución.  Esta solución es una combinación lineal de exponenciales, cuyos parámetros se estiman ajustando la curva a los datos 
oficiales de infectados. Uno de estos parámetros es la tasa de crecimiento epidémico, relacionada con el tiempo de duplicación de la cantidad de infectados, 
que se puede estimar de de forma más robusta que el conocido número básico de reproducción R. Estimamos este parámetro para cada semana, y hacemos una regresión lineal de estos 
valores a los datos de movilidad publicados por Google. Este resultado muestra la importancia de todas las otras medidas sanitarias adoptadas. 
Puede descargarse desde [Reportes técnicos](/#publications).
