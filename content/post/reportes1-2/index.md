---
title: 'Reportes 1 y 2 del grupo GUIAD-COVID 19'
subtitle: ''
summary: Están disponibles los dos primeros reportes realizados en el marco del espacio GUIAD-COVID19. Pueden descargarse desde [Reportes técnicos](#publications). 
authors:
- guiad
tags:
- Reportes
categories:
- Reportes
date: "2020-04-04"
lastmod: "2020-04-04"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---


Los dos reportes ahondan en una serie de ideas que creemos son importantes comprender a esta altura de la situación. Se basan en el análisis de datos de Covid-19 en Uruguay, en el estudio de modelos internacionales y en bagaje académico de las áreas de matemática, computación, epidemiología, ecología y medicina. Puede descargarlos desde la sección [Reportes Técnicos](/#publications).

Modelar la dinámica de la enfermedad en Uruguay en tiempo real es muy valioso pero es difícil, debido a la alta tasa de contagio de la enfermedad, su tiempo de incubación, la gran variedad de cuadros en los que se presenta, pasando desapercibida en un gran porcentaje de infectados, hasta la internación en otro tanto y la heterogeneidad de sus efectos según la edad.
 
Las herramientas de modelado epidemiológico están siendo usadas en todo el mundo para seguir el transcurso de la epidemia. A pesar de que los científicos nos podemos basar en los trabajos que surgen del exterior, es de vital importancia establecer y validar modelos específicos para las características de nuestro país.

Para poder hacerlo, es clave contar con datos fiables y lo más completos posibles. Los datos nos permiten, por ejemplo, calcular parámetros de crecimiento de la enfermedad. Si utilizamos datos de otros países vemos una gran incertidumbre acerca de el futuro de la enfermedad. Necesitamos mejores datos para tener una mejor estimación específica para Uruguay. Estos datos nos permitirían, entre otras muchas posibilidades  estimar el efecto que nuestro distanciamiento social tiene en el crecimiento de la enfermedad, o estimar la cantidad de casos reales en nuestro país. 

### ¿Qué sabemos de la enfermedad a partir de los datos mundiales? 

El contagio a nivel mundial tiene dinámicas de crecimiento exponencial. Esto quiere decir que el crecimiento diario del número de casos en el mundo sería proporcional al número de casos de ese día. Esa es la esencia de lo que ha trascendido en el mundo, donde los países han implementado medidas de aislamiento social para enlentecer dicho crecimiento exponencial y lograr "achatar" la curva de nuevos contagios por día. Puntualmente, el crecimiento en Uruguay y en cualquier punto del planeta depende de las dinámicas propias de la enfermedad así como de las características locales y de  las acciones que tomemos en el transcurso de la epidemia las personas y las organizaciones. Razón por la cual es importante estudiarlo localmente. 
 

### ¿Que sabemos hoy  a partir de los datos disponibles en Uruguay?

Nuestros recientes estudios sugieren que, para Uruguay, los datos de casos publicados oficialmente presentan lo que se llama un crecimiento *subexponencial*. El crecimiento subexponencial es un crecimiento que no acelera con las características exponenciales anteriormente mencionadas. Este tipo de crecimiento es común en muchas epidemias y puede tener diferentes razones de ser. Tales razones pueden ser interpretadas como escenarios tanto positivos como negativos. 

Sugerimos **dos explicaciones posibles** para el  crecimiento subexponencial de datos confirmados en uruguay

1. La enfermedad crece de manera subexponencial. 
Las intervenciones sociales impuestas por el estado han tenido un efecto de retrasar el crecimiento de la enfermedad y están actuando como fuerzas que contraponen el crecimiento exponencial. 
2. El crecimiento subexponencial de los datos se debe al muestreo. 
Este crecimiento subexponencial no se debe necesariamente a un crecimiento resistido de la enfermedad, sino a desviaciones producidas por nuestras capacidades y decisiones de testeo. Es decir, que lo que se mide, no es proporcional a la cantidad de contagios real.

Nuevamente, para poder saber cuál es la causa, y con ello que se puedan mejorar aún más las medidas necesarias, es fundamental tener más datos de las estrategias de muestreo diagnóstico en Uruguay. Por ahora, es importante notar que en cualquiera de los dos casos, **las tasas de crecimiento subexponenciales pueden rápidamente revertirse en un crecimiento exponencial**. Esto significa que a pesar de que los datos parecen crecer lentamente, y de forma subexponencial, es importante **mantener las medidas recomendadas por el MSP**.