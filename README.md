# Código fuente del sitio del [Grupo Uruguayo Interdisciplinario de Análisis de Datos - Covid 19](https://guiad-covid.github.io/)

## Instrucciones para realizar sugerencias de cambios o reportes de errores

Las sugerencias de cambios o modificaciones y los reportes de errores en el sitio se deben ingresar como tickets en la sección [Issues](https://github.com/GUIAD-COVID/website-GUIAD/issues)


## Instrucciones para realizar modificaciones al sitio

Este sitio se genera usando [Hugo](https://gohugo.io/), y se basa en el tema [Academic](https://sourcethemes.com/academic). Para probar localmente, es necesario instalar Hugo, se puede bajar desde [aquí](https://gohugo.io/getting-started/installing/#binary-cross-platform). Es simplemente un archivo ejecutable que debemos incluir en el path.   Por más información sobre Hugo, consultar su [documentación](https://gohugo.io/documentation/).

Las instrucciones a continuación asumen ciertos conocimientos sobre Git. Por más información se puede consultar algún tutorial (por ejemplo [este](https://youtu.be/USjZcfj8yxE) o si se quiere profundizar [el capítulo 2 del libro Pro Git de Scott Chacon y Ben Straub](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) 

Las instrucciones generales son las siguientes:

1. Para comenzar a trabajar, y sólo la primera vez, clonar localmente el repositorio remoto usando el siguiente comando, el cual habilita los submodulos

`git clone --recurse-submodules https://github.com/GUIAD-COVID/website-GUIAD.git`

Si el repositorio ya ha sido clonado localmente, recordar hacer `git pull` antes de comenzar a trabajar, para trabajar sobre la última versión del código.

2. Verificar que el sitio corre localmente. Para eso, cambiarse al directorio local donde se clonó el repositorio remoto y ejecutar 

`hugo server`

Esto levantará el sitio en http://localhost:1313/

Lo dejamos corriendo, que el sitio se va a regenerar automáticamente cada vez que haya un cambio .

3. Realizar las modificaciones necesarias, más abajo se detallan algunos de los casos más comunes.

4. Gestionar los cambios en el repositorio local del código fuente, usando como es usual los comandos `git status` `git add`y `git commit`. Se aconseja usar mensajes descriptivos al hacer commit. Si se está atendiendo un issue reportado, colocar el número de issue en el mensaje.

5. Subir los cambios al repositorio remoto del código fuente, usando el commando `git push`.

6. Sólo resta publicar el sitio nuevamente. Para hacer esto, ejecutar el script ``deploy.sh`` que genera el sitio y hace un ``push`` del directorio ``public``al [repositorio remoto del sitio](https://github.com/GUIAD-COVID/GUIAD-COVID.github.io)

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


