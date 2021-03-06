# APPLOVE

## HTML: Determinar las secciones

1. Presentar la estructura básica y conectar con el archivo de estilo (CSS)

2. Indicar las fuentes a usar.

3. Dividir el html en cajas más pequeñas y manejables: header y footer, home (inicio), services (servicios), work (alguna descripción) y projects (proyectos realizados).

4. Subdividir y agrupar cada sección en estructuras manejables.


## CSS: Estilos

 - Para cada sección, indicar sus dimensiones, colores de fondo, márgenes y/o padding, y posición.

 #### Body

    - Determina características generales, como la fuente y los colores. Luego pueden modificarse para determinada sección.

 ##### 1. Header

    - Dimensionar el header y posicionarlo de forma fixed.
    - Dimensionar los componentes.
    - Determinar las características de los componentes.
    - Quitar punto de lista, y subrayado de links.
    - Posicionarlos mediante float.

 ##### 2. Home

    - Dimensionar y posicionar el contenedor.
    - Mediante z-index, se indica el plano de cada componente.
    - Determinar las características del texto.
    - Posicionar y estilizar el botón "View services".


 ##### 3. Services

    - Dimensionar y posicionar contenedor.
    - Estilizar el texto.
    - Redimensionar imágenes.
    - Dimensionar tabla contenedora.
    - Quitar punto de listas.

 ##### 4. Work

    - Dimensionar y posicionar el contenedor.
    - Dar estilo al texto.

 ##### 5. Projects

    - Dimensionar y posicionar contenedor.
    - Estilizar el texto.
    - Redimensionar imágenes.
    - Redondear esquinas de hover.

 ##### 6. Footer

    - Dimensionar y posicionar contenedor.
    - Estilizar texto.



_______________________________________________________________

# AppLove

Para completar tu web **AppLove** hemos creado este repositorio boilerplate (plantilla inicial) con todos los recursos que necesitas. Esto incluye las imágenes y algunas clases CSS que ya hemos creado para ti :)

## Empieza por realizar un fork y clonar este repositorio

1. Debes realizar un **fork** de este repositorio.

2. Luego deberás **clonar** este repositorio boilerplate, después crear un repositorio remoto en tu cuenta de `GitHub` y vincular tu local con tu remoto. Para esto, sigue los siguientes pasos:

    1. Crea un repositorio remoto en tu cuenta de `GitHub` con el nombre del ejercicio (tip: recuerda usar "New Repository")
    2. Obten el URL del repositorio boilerplate haciendo clic en el _botón verde_ "clone or download"
    3. En tu línea de comandos, clona el repositorio boilerplate y vincúlalo con tu repositorio remoto. Para hacer esto debes usar los comandos `git clone`, `git remote add` y `git push` que se muestran a continuación:

        ```js
        ~ git clone <URL del repositorio _boilerplate_ de Laboratoria>
        ~ git remote add origin <URL del repositorio remoto que creaste en tu cuenta de GitHub>
        ~ git push origin master
        ```

## Objetivo Final

El reto consiste en maquetar la web **AppLove**, este es el resultado final:

![AppLove](https://fotos.subefotos.com/1edc0aab51f1d624da4a24ab86129d87o.png) 

## Detalles adicionales

- Encontrarás un archivo base `index.html` el cual contiene una estructura inicial sobre la que deberás completar tu proyecto.

- En la carpeta `css` tendrás un archivo base `main.css` donde hay clases reutilizables, quiere decir que dichas clases pueden ser usadas más de una vez. Por ejemplo: 

    ```CSS
    .text-uppercase {
      text-transform: uppercase;
    }
    ```

    >Si usamos la clase `.text-uppercase` en algún texto lo que hará es ponerlo en mayúsculas. De esta manera podrás reutilizar esta clase varias veces. **No olvides enlazar tu archivo `CSS` a tu `HTML`**.

- El `header` tiene que estar **estático**, como se muestra en la siguiente _imagen gif_:

![AppLove-gif](https://fotos.subefotos.com/da068e44cb72b36ba6c4458130c00185o.gif) 

- Dentro de la carpeta `assets` se encuentra la carpeta `images` donde encontrarás todas las imágenes necesarias para completar tu proyecto.

- Deberás **actualizar el archivo `README.md`** explicando el contenido de tu repositorio.

- El tipo de fuente a utilizar será `Raleway`.

## Consideraciones generales

Este reto sera evaluado sobre lo siguiente:

- Pixel perfect (replicar el diseño con exactitud)
- Nombramiento de clases, id, etc
- Indentación
- Estructura de tus archivos
- Archivo `README.md` actualizado y correctamente redactado
- Uso de comentarios para hacer tu código más legible



------------------------

