# CSS

## Selectores

- Selector por tipo: `a` selecciona todos los elementos del tipo `<a>`.

- Selector por id: `#miId` selecciona todos los elementos con el atributo `id="miId"`.

- Selector por clase: `.miClase` selecciona todos los elementos con el atributo `class="miClase"`.

- Selector universal: Selecciona todos los elementos con `*`.

- Selector por descendencia: `A B` selecciona todos los elementos de `B` que se encuentran dentro de `A`.

- Selector múltiple (por comas): `A, B` selecciona todos los elementos de `A` y `B`.

- Selector por hermanos adyacentes: `A + B` selecciona _sólo_ los elementos de `B` que van después de `A`.

- Selector general por hermanos: `A ~ B` Selecciona todos los elementos de `B` que van después de `A`

- Selector por hijos: `A > B` selecciona todos los `B` que son hijos directos de `A`.
  
### Pseudoclases
- `:hover`: Se activa el selector al pasar el mouse encima del elemento. 

- `:focus`: Se activa el selector al hacer click o presionar con un táctil encima del elemento.
  
- `:active`: Se activa el selector mientras que se está interactuando con el elemento. Si se va a utilizar junto con `:hover`, este debe después.
 
- `:visited`: Se activa el selector cuando ya se visitó un determinado enlace con la etiqueta `<a>...<\a>`.

## Propiedades

### Estilos de texto

- `color`: Cambia el color del texto.

- `font-family`: Cambia la fuente del texto.

- `font-size`: Cambia el tamaño del texto.

- `font-weight`: Cambia el grosor del texto.

- `font-style`: Cambia el estilo del texto (cursiva)

- `line-height`: Define el espaciado entre párrafos con unidades de medida.

- `text-align`: Define la alineación del texto (izquierda, derecha, justificado, centrado)

- `text-decoration`: Estiliza el texto con subrayados de diferentes tipos. La opcion `none` quita todos los estilos.

- `text-transform`: Cambia el texto a mayúscula, minúscula u otros.
  
### Estilos de listas

- `list-style-type`: Cambia el tipo de punteo de una lista, `none` para desactivarlo.

- `list-style-position`: Cambia la posición del contenido de una lista aumentando o disminuyendo la tabulación con `inside` y `outside`.

### Dimensiones

- `width`: Define el ancho de un elemento.

- `height`: Define el alto de un elemento.

- `max-width`: De no utilizar `width`, este define el ancho máximo de un elemento.

- `min-width`: De no utilizar `width`, este define el alto mínimo de un elemento.

- `min-height`: De no utilizar `height`, este define el ancho máximo de un elemento.

- `min-height`: De no utilizar `height`, este define el alto mínimo de un elemento.