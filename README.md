# Código fuente del sitio del [Grupo Uruguayo Interdisciplinario de Análisis de Datos - Covid 19](https://guiad-covid.github.io/)

## Instrucciones para realizar sugerencias de cambios o reportes de errores

Las sugerencias de cambios o modificaciones y los reportes de errores en el sitio se deben ingresar como tickets en la sección [Issues](https://github.com/GUIAD-COVID/website-GUIAD/issues)


## Instrucciones para realizar modificaciones al sitio

Este sitio se genera usando [Hugo](https://gohugo.io/), y se basa en el tema [Academic](https://sourcethemes.com/academic). Para probar localmente, es necesario instalar Hugo, se puede bajar desde [aquí](https://gohugo.io/getting-started/installing/#binary-cross-platform). Es simplemente un archivo ejecutable que debemos incluir en el path.   Por más información sobre Hugo, consultar su [documentación](https://gohugo.io/documentation/).

Las instrucciones generales son las siguientes:

1. Clonar localmente el repo.
2. Verificar que el sitio corre localmente. Para eso, cambiarse al directorio local del repo y ejecutar 

`hugo server`

Esto levantará el sitio en localhost:1313/

Lo dejamos corriendo, que el sitio se va a regenerar automáticamente cada vez que haya un cambio .

2. Realizar las modificaciones necesarias.

3. Subir los cambios al repositorio central. 

4. Para hacer el deploy del sitio, ejecutar el script ``deploy.sh`` que genera el sitio y hace un ``push`` del directorio ``public``al [repositorio del sitio](https://github.com/GUIAD-COVID/GUIAD-COVID.github.io)

### Principales archivos de configuración

- El directorio "principal" con todos los widgets que aparecen es https://github.com/GUIAD-COVID/website-GUIAD/tree/master/content/home
- Allí, cada archivo es un widget (una de las secciones). Para que se vea, tiene que tener `active=true`, y `weigth` asigna el orden.
- El archivo `hero.md` tiene la presentación 

### Quiénes somos

- Hay un directorio de autores: https://github.com/GUIAD-COVID/website-GUIAD/tree/master/content/authors
- Cada autor definido tien un directorio con el formato inicial-apellido y adentro un archivo con sus datos (copiar el directorio para crear uno nuevo)
- Hay un autor especial "guiad", que tiene como descripción lo que aparece en la sección quiénes somos 

### Como agregar un nuevo post en Novedades

-- Los posts (que aparecen en novedades), están en https://github.com/GUIAD-COVID/website-GUIAD/tree/master/content/post
-- Allí, cada post es un directorio con un archivo `_index.md` con el texto y la configuración. Hoy existe uno, copiarlo para agregar otro. 

### Cómo agregar un nuevo Reporte técnico
-- Igual al anterior, pero en https://github.com/GUIAD-COVID/website-GUIAD/tree/master/content/publication

### Cómo agregar un enlace 
-- Está todo en https://github.com/GUIAD-COVID/website-GUIAD/tree/master/content/links/_index.md


