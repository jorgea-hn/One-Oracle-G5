# Diferencias entre HTML, CSS y JavaScript

Estos 3 lenguajes son los principales en el lado del Frontend, se utiliza en el lado del cliente.


## Un poco de Historia
Antes las empresaas para compartir informacion requerian de mucho tiempo, sin embargo en "1991, Tim Berners-Lee" diseño HTML, con el fin de facilitar compartir documentos, sin embargo en "1992" se creo "wordl wide web - www", una red de alcance mundial, CSS surgio por la parte de volver estetico los documentos HTML, sin embargo esto se agregaba en el mismo documento HTML lo cual hacia que fueran extensos por ende en 1995 se creo el CSS aparte del documento HTML.

Finalmente, se creó Javascript, fue a partir de una gran competencia entre los gigantes del mercado en ese momento: Microsoft y Netscape.

Todo empezo con la creacion de un lenguaje del lado del servidor por Netscape, por ende Microsoft replico la idea y creo JScript para implementarlo en sus servidores, Netscape al ver que su idea estaba siendo copiada decidio desarrollar una tecnologia del lado del cliente que se ejecutaria en el propio navegador,y de igual manera Microsoft lo replico.

Por ende habian dos tecnologias "client-side, JScript de Microsoft y JavaScript de Netscape, sin embargo este ultimo envio su tecnologia a ECMA lo cual permitio la incorporacion en los navegadores existentes.


### HTML
Su nombre proviene de "Hyper Text Markup Language" lo que singnifica lenguaje de marcado de hipertexto

Este no se considera un lenguaje de programacion, toda la organizacion de una pagina web, titulos, encabezado, parrafos, imagenes, HTML se utiliza para crear toda la estructura de la pagina, y para eso utiliza las tags o etiquetas, para indicar donde se implementara cada elemento.

por ejemplo:

```
<p>Este es un parrafo<p>
```


### CSS
Su nombre significa "Cascading Style Sheet", significa hoja de estilo en cascada, es un lenguaje de estilo, tampoco se considera un lenguaje de programacion.

por ejemplo:
```
selector{
    propiedad:valor;
}
```

donde selector es el tag, una clase o un identificador, la propiedad es lo que vamos a cambiar, sea color, letra, ancho, etc y el valor sera el cambio, como rojo, 18px,etc.

por ejemplo:

```
p{
    color:blue;
}
```

con esto, todos los parrafos seran de letra azul.


CSS se puede escribir dentro del archivo HTML, usando el estilo como elemento `<style>` o como atributo `<p style="">`, tamien se puede utilizar como archivo externo 
`<link rel="stylesheet" href="nombre_del_archivo_css.css">`

### Javascript
Es el lenguaje de programacion, donde:
* HTML -> estructura de la pagina
* CSS -> estilos de la pagina 
* JS -> funcionalidades

JavaScript le brinda movimiento a la pagina, ademas permite el procesamiento y la tarnsformacion de los datos enviados y recibidos.

Permite crear contenidos que se actualizan de forma dinamica y animada, dando vida a las aplicaciones.

Cuando se logra apreciar un cuadro de alerta es porque javascript esta funcionando, por ejemplo:

```
alert(‘Hello World’); 
```

al igual que CSS, JavaScript puede escribirse dentro del codigo HTML

```
<script>  alert(‘Hello World’); </script>
```

como en un archivo separado, se importa de la siguiente manera

```
<script src="nombre_del_archivo_js.js"></script>
```

Este lenguaje se puede utilizar tanto en el lado del cliente como en el del servidor, utilizando Node.js












