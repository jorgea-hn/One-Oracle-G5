# Construir Pagina WEB

Construiremos una pagina web con HTML y CSS


* creamos un archivo HTML
Los titulos son las etiquetas <h1> a <h6>
Los parrafos son la etiqueta <p>
Para darle negrita <strong>
Para darle enfasis o cursiva <em>

Para darle al navegador para que entienda que es HTML5 <!DOCTYPE html>
Inicio y fin del documento <html>
A la etiqueta html se le agrega el atributo lang para que se maneje en un idioma especifico <html lang="en">

etiqueta para que el navegador reconozca los diccionarios de palabras <meta charset="UTF-8"> por ejemplo caracteres especiales


titulo de la pestaña <title>

Etiqueta donde van las etiquetas informativas <head>

etiquetas donde van las etiquetas de contenido <body>

Unordered list o lista no ordenada <ul>
Item de lista <li>


Para nombrar o mostrar el encabezado de la pagina se guarda dentro de un contenedor div pero en la ultima version esta se actualizo a la etiqueta <header> la cual tiene el mismo funcionamiento que un <div>




## Comenzando CSS

Agregando el atributo `style="text-align:center;"` dentro de las etiquetas para poder darle estilo al documento.


para referenciar el archivo css externo 
<link rel="stylesheet" href="style.css">
donde rel dice que tomaremos una hoja de estilos y  el href es la referencia al archivo.


Empezamos a dar estilos llamando la etiqueta y dandole el estilo que queramos de la siguiente manera 
```
body{
    background: #ccc;
}
```

Tambien podemos darle estilo a etiquetas especificas hijas
```
em strong{
    color: red;
}
```
de esta manera le dara color rojo solo a las etiquetas strong que sean hijas de la etiqueta em.


Hexadecimal
rrggbb - red red green green blue blue
color negro - #000000
color blanco - #ffffff

RGB
0-255


color
red - blue - green


Para agregar imagenes se utiliza la etiqueta <img>


width -> se utiliza para modificar el ancho
height -> se utiliza para modificar el alto

margin -> se utiliza para el margen externo
padding -> se utiliza para el margen interno


### Equipo Front-end
* Programador Frontend, responsable del codigo

* Diseñador 
    * Responsable por UX (user experience), 
    * Responsable por UI (user interface)
    Responsable de especificaciones, interfaz amigable y con buen diseño
* Copywriter (Generador de contenido)
* SEO (Search Engine Optimization), optimiza la pagina para ser visible en intenet.


