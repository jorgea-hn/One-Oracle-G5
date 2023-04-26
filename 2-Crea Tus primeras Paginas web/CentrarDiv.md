# Centrar un elemento con css

Primero debemos crear el elementoen HTML

```
<div class="container">
    <p> Aqui tenemos un texto</p>
</div>
```

Si queremos centrar el texto

```
.container{
    text-aling:center;
}
```

Pero si quieres centrar el div

```
.container{
    width:700px;
    margin-left:auto;
    margin-right:auto;
}
```
Este codigo funciona para cualquier elemento block