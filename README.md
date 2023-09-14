# bootstrap-classes
Practica de las clases mas usadas en bootstrap, en detalle y con ejemplos

------------------------------------------------------------------------------------------------
Textos

Clase que se añaden a etiquetas de texto como h1, h2, h2, p, etc.

Colores: 

.text-primary: texto color azul.
.text-light: Texto gris claro
.text-secondary: Texto gris.
.text-muted: Texto gris oscuro.
.text-success: Texto verde.
.text-danger: Texto rojo.
.text-warning: Texto naranja.
.text-info: Texto celeste.
.text-white: Texto blanco.
.text-dark: Texto negro.

------------------------------------------------------------------------------------------------

Colores de Fondo:

Se pueden poner tanto en etiquetas de texto como divs contenedores.

.bg-primary.
.bg-success.
.bg-info.
.bg-warning.
.bg-danger.
.bg-secondary.
.bg-dark.
.bg-light.

------------------------------------------------------------------------------------------------

Estilos de Letras.

.font-weight-bold: Negrita
.font-weight-normal: Normal
.font-weight-light: Fina
.font-italic: Itálica
.lead: Destaca un párrafo
.small: Más pequeño (85% del tamaño del padre)
.text-left: Alineado izquierda
.text-center: Alineado centro
.text-right: Alineado derecha
.text-justify: Justificado
.text-nowrap: Texto nowrap
.text-lowercase: Texto en minúsculas
.text-uppercase: Texto en mayúsculas.text-capitalize Texto capitalizado
.initialism: Muestra el texto en un elemento <abbr> con tamaño más pequeño
.list-unstyled: Quita el list-style y margin-left en elementos de lista (funciona en <ul> y <ol> ). 
.list-inline: Coloca todos los elementos de una lista en una única línea.

------------------------------------------------------------------------------------------------

Etiquetas h:

h1 Bootstrap (2.5rem = 40px)
h2 Bootstrap (2rem = 32px)
h3 Bootstrap (1.75rem = 28px)
h4 Bootstrap (1.5rem = 24px)
h5 Bootstrap (1.25rem = 20px)
h6 Bootstrap (1rem = 16px)

------------------------------------------------------------------------------------------------

Alineacion de Elementos:

align-items-center.
justify-content-center.

------------------------------------------------------------------------------------------------

Display Flex:

d-flex-: display flex column
d-flex: display flex row

------------------------------------------------------------------------------------------------

Etiqueta <small></small>:

Hace mas que chica la palabra o texto que encerremos dentro de ella.

------------------------------------------------------------------------------------------------

Etiqueta <mark></mark>

Resalta el texto que coloquemos dentro de esta etiqueta de color amarillo.

------------------------------------------------------------------------------------------------

Contenedores

.container: el contenido aparece centrado y con un ancho fijo.
.container-fluid: el contenido ocupa todo el ancho disponible (100%).

------------------------------------------------------------------------------------------------

Clases row y col.

Un div con clase row o col, nos va a ordenar el contenido segun su caracteristica.

.row: ordenara los elementos de como filas, de izquierda a derecha.
.col: ordenara los elementos de como columnas, de arriba hacia abajo.

También podríamos hacerlo usando las clases col-xx, donde xx es el tamaño de la columna (como máximo 12 columnas en una fila):

col-3: va a ocupar 3 columnas de 12 (que es el maximo).
col-4: va a ocupar 4 columnas de 12 (que es el maximo).
col-6: va a ocupar la mitad del espacio.
col-12: va a ocupar todo el ancho del div contenedor.

Metodo Responsive en clases row y col

.col-xx: <576px.
.col-sm-xx: ≥576px.
.col-md-xx: ≥768px.
.col-lg-xx: ≥992px.
.col-xl-xx: ≥1200px.

Ocultamiento de contenido.

Oculto en todas	    .d-none
Oculto en xs	    .d-none .d-sm-block
Oculto en sm	    .d-sm-none .d-md-block
Oculto en md	    .d-md-none .d-lg-block
Oculto en lg	    .d-lg-none .d-xl-block
Oculto en xl	    .d-xl-none
Visible en todas    .d-block
Visible en xs	    .d-block .d-sm-none
Visible en sm	    .d-none .d-sm-block .d-md-none
Visible en md	    .d-none .d-md-block .d-lg-none
Visible en lg	    .d-none .d-lg-block .d-xl-none
Visible en xl	    .d-none .d-xl-block  

------------------------------------------------------------------------------------------------

Imagenes

.img-fluid: Para que las imágenes se adapten correctamente a los distintos dispositivos (Responsive).
.rounded: Imagen con esquinas redondeadas.
.rounded-circle: Imagen con forma de circulo.
.img-thumbnail: Da forma de miniatura a la imagen.
.float-left: Alineacion de la imagen hacia la izquierda.
.float-right: Alineacion de la imagen hacia la derecha.

------------------------------------------------------------------------------------------------

Botones

.btn: Boton simple blanco sin contorno, letra negra.

Botones con colores ya vistos:

.btn-primary 
.btn-secondary 
.btn-success 
.btn-info 
.btn-warning 
.btn-danger 
.btn-dark
.btn-light 
.btn-link.

Botones con contornos segun colores ya vistos.

.btn-outline-primary
.btn-outline-secondary
.btn-outline-success
.btn-outline-info
.btn-outline-warning
.btn-outline-danger
.btn-outline-dark
.btn-outline-light.

Tamaños

.btn-sm: Boton pequeño.
.btn-lg: Boton grande.
.btn-block: Ocupa el ancho de su contenedor.

Grupo de Botones

Agregamos las siguentes clases a sus contendores para obtener su estilo.

.btn-group: Grupo de botones horizontales.
.btn-group-vertical: Grupo de botones verticales.

------------------------------------------------------------------------------------------------

Espaciado gap

.gap-xx: <576px.
.gap-sm-xx: ≥576px.
.gap-md-xx: ≥768px.
.gap-lg-xx: ≥992px.
.gap-xl-xx: ≥1200px.

------------------------------------------------------------------------------------------------

Espaciado entre columnas

.offset-md-4: Añade 4 espacios a la izquierda del div.
Se grafica de esta manera:

 <div class="row"> <!-- Clase contenedora -->
 <!-- Div de 4 columnas, lo encontraremos a la izquierda ocupando los 4 primeros lugares -->
  <div class="col-md-4">.col-md-4</div> 
  <!-- Div de 4 columnas, lo encontraremos a la derecha ocupando los 4 ultimos lugares, clase offset ocupara los 4 lugares del medio, entres los 2 divs -->
  <div class="col-md-4 offset-md-4">.col-md-4 .offset-md-4</div>
</div>

------------------------------------------------------------------------------------------------

Margenes

.m-xx: (margin).
.mt-xx: (margin-top).
.mb-xx: (margin-button).
.ml-xx: (margin-left).
.mr-xx: (margin-right).
.ml-auto: (margin-left) Ocupara el margen izquierdo que tenga disponible.
.mr-auto: (margin-right) Ocupara el margen derecho que tenga disponible.

Margenes Responsive

.ml-3: Aparece en todos.	
.ml-3 .ml-sm-0: Aparece solo en xs.	
.ml-sm-3 .ml-md-0: Aparece solo en sm.	
.ml-md-3 .ml-lg-0: Aparece solo en md.	
.ml-lg-3 .d-xl-0: Aparece solo en lg.	
.ml-xl-3: Aparece solo en xl.	