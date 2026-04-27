# Etiquetas HTML

## Etiquetas obligatorias
- `<!DOCTYPE html>`: Indica que el documento es tipo HTML.
- 
- `<html>...</html>`: Espacio donde se alojan las etiquetas para la página.

- `<head>...</head>`: Contiene los metadatos de la página. Es decir, configuraciones o informacion relevante para el navegador e indexadores de motores de búsqueda.

- `<body>...</body>`: Espacio donde se alojan las etiquetas correspondientes a lo visual de la página.

- `<meta>`: Datos y configuraciones relevantes para el navegador y los motores de búsqueda.

- `<title>...</title>`: Ttulo que aparece en la pestaña del navegador.

## Etiquetas visuales

- `<button>...</button>`: Crea botones. Tiene etiqueta de apertura y cierre. Ejemplo `<button type="button">Haz clic aquí </button>`

- `<h1>...</h1>`: Títulos de la página.

### Inserción de imágenes
- `<img>`: Inserta imagenes. Se necesita el atributo `src` para agregar la ruta de la imagen. `alt` en caso de que la etiqueta no cargue. `title` para que aparezca el titulo de la imagen al poner el cursor encima. Ejemplo `<img src="ruta" alt="texto alternativo">`

- `<figure>...</figure>`: Seccion donde se colocan imagenes.

- `<figcaption>...</figcaption>`: Texto descriptor de una imagen.

### Texto y semántica

- `<p>...</p>`: Informacion de tipo párrafo.

- `<span>...</span>`: Informacion breve/abreviada de tipo texto.

- `<blockquote>...</blockquote>`: Bloques largos de texto con sangria.

- `<q>...</q>`: Citas cortas.

- `<cite>...</cite>`: citado de titulo de una obra en cursiva.

- `<code>...</code>`: Muestra un fragmento de codigo.

- `<b>...</b>`: Texto en negrita.

- `<strong>...</strong>`: Negrita pero con violencia (con enfasis).

- `<i>...</i>`: Texto en cursiva.

- `<u>...</u>`: Texto subrayado. (El canal no...)

### Tablas

- `<table>...</table>`: Indica seccion con tabla.

- `<th>...<th>`: Encabezado de la tabla.

- `<tr>...</tr>`: Indica una fila.

- `<td>...</td>`: Datos dentro de una fila.

- `<thead>.../thead>`: Categorías de la tabla.

- `<tbody>...</tbody>`: Cuerpo de la tabla con los datos.

- `<caption>...</caption>`: Descripción de la tabla.

### Listas

- `<ul>...</ul>`: Seccion de lista desordenada.

- `<ol>...</ol>`: Lista ordenada.

- `<li>...</li>`: Indica un item de la lista.

### Formularios

- `<form action="index.html">`...`</form>`: Crea un "formulario". (Guarda todos los datos de inputs que el usuario haga dentro de este espacio) En este caso, cuando el usuario finalize el formulario, lo redireccionará a `index.html`

- `<button name="button">` [texto] `</button>`: Muestra un boton con el texto en pantalla. Cuando el usuario haga click, siempre y cuando esté dentro de un form, verifica las condiciones de todos los campos dentro del form. En caso de que se cumplan, da como finalizado el form y redirecciona al usuario a donde esté direccionado el form.

- `<label for="">`Titulo:`</label>`: Muestra texto en pantalla. Al asociarse a un elemento, usando `<select id="..." name="...">` y luego ingresando esa id en otra etiqueta, como por ejemplo un input type, si el usuario hace click en este texto se selecciona el espacio donde este puede ingresar datos.

- `<input>`: Permite al usuario ingresar un dato que puede ser utilizado por la página. Este comando puede recibir muchos atributos para configurar información sobre el dato y parámetros sobre cómo se va a usar después. Usar `type` para especificar que tipo de atributo se quiere recibir.

- `<input type="password">`: No hace visible lo que el usuario está escribiendo.

- `<input type="number">`: Hace que solo se permitan ingresar numeros.

- `<input type="email">,`: Agrega un campo para el formato email.

- `<input type="checkbox">`: Crea un campo seleccionable.

- `<input type="submit">`: Cumple la misma función que `<button>` cuando está adentro de un form.

#### Atributos relacionados al input type

- `required`: Hace que el campo sea obligatorio.

- `autocomplete="name"`: Permite autocompletar un campo.

- `placeholder="..."`: Agrega un ejemplo en los campos.

- `accept=".extension"`: Permite ciertas extensiones de archivos (solo en un input type file).

- `pattern="[0-9]{8}"`: Pone como condición un patron. En este caso, los datos que ingrese el usuario deben ser únicamente números naturales del 0 al 9, y deben ser 8, ni más ni menos.

- `autofocus`: Hace que esté seleccionado el campo automáticamente al ingresar a la página.

- `maxlength` : Limita el máximo de caracteres que se pueden utilizar.

- `minlength` : Limita el minimo de caracteres que se pueden utilizar.

### Miscelaneos

- `<a>...</a>`: Hipervinculo. `href` para ingresar la ruta/url a la cual redirigirse. `target` indica si abrirlo en la misma pestania o en otra, para abrirlo en otra se usa `target="_blank`. Se usa `mailto` en el atributo `href` para redirigir al usuario a enviar un correo, ejemplo: `href="mailto:correo@aol.com"`. Lo mismo de mailto ocurre con `tel`. Ejemplo: `<a href="otraPagina.html" target="_blank">Enlace</a>`