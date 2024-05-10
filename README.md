# Inicio del proyecto

- Se realiza la estructura básica de carpetas y archivos, utilizando este script `mkdir -p assets/css assets/img assets/js assets/sass assets/sass/base assets/sass/abstract assets/sass/themes assets/sass/components assets/sass/pages assets/sass/layout assets/sass/vendors && touch .gitignore assets/css/style.css index.html README.md assets/js/index.js assets/sass/main.scss`.
- Se crea el `package.json` con `npm init -y`.
- Se instala de manera local bootstrap por medio de la consola `Gitbash`.
- Se integra `Jquery` por medio de un `<script>` en el `head` y se agrega también por medio de un `<script>` en el `head` la ruta del archivo de `Js`.
- Se integra la fuente `Open-sans` por medio de un `@import` desde `GoogleFonts` en el archivo `typography.scss`.
- Se incorpora bootstrap al proyecto con un `@import` al `main.scss` y el resto de `parciales` de Sass para que así se compilen todos los archivos a un `Style.css`.
- Se da inicio en index.html con '!' para formar la base del 'Documento'.
- Se realiza un 'git init' por la terminal de `Gitbash`.
- Se realiza un 'git add .' para agregar al area de 'staging' los archivos.
- Se realiza un 'git commit -m ""' para agregar los cambios a git y un mensaje.
- Se crea en 'Github.com' la carpeta del repositorio y se enlaza con el documento en VScode con la terminal.
- Se realiza un 'git push origin main' y se verifica que se hayan cargado los archivos.

## Realización del proyecto

### Se usa la grilla de bootstrap para todo el proyecto, EXCEPTO la sección `testimonios`

- Se integra una `navbar` de bootstrap con sus enlaces correspondientes a cada sección por medio de `id`.
- Se integra un `carousel` de bootstrap, modificando el `height` para vistas `desktop` y `mobile` con un media query.
- se crea una sección `quiénes somos` con una imagen y una descripción, la imagen por medio de una `media query` desaparece en `mobile`
- Se integran `Cards` horizontales de bootstrap.
- Se crea una sección `testimonios` con Css puro `sin bootstrap` y además su tuliza la metodolgía `BEM` para las clases.
- Se crea una sección `contacto` con un `form`, un `checkbox input` y un `button`.

=> La `checkbox` tiene un "input" a un lado con los 'terminos y condiciones' los cuales aparecen por medio de un `modal` integrado con bootstrap.
=> El ``button` al presionarlo arroja un `alert` de bootstrap y Js.

Se integran iconos de `font awesome` por medio de un de un `<script>` en el `head`.

para las cards
1. fa-plane

para los inputs
1. fa-circle-info

para los datos de contacto
1. fa-phone
2. fa-envelope
3. fa-brands fa-linkedin
4. fa-brands fa-instagram


## JS

- Se importa por medio de un `<script>` en el `head` el archivo de `Js`

- Se integran 'Tooltips' a los iconos `fa-circle-info` del footer.
- Se integra a la `navbar` un estilo al `scroll` para que vaya apareciendo, a medida que sube la página, un color cada vez más solido.
- Se integra el codígo para el `modal`

## CSS

- Se aplican estilos para las la sección `testimonios`.

`height` y `width` de las imagenes, centrado de texto, color, paddings.

### NO se modifican los colores de bootstrap

# Se finaliza el proyecto y se pushea a `Github`, donde se 'deployea'.
