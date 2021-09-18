CSS

# Aprendiendo CSS
CSS son hojas de estilo para dar formato especial a páginas HTML.


## Tipos de CSS

1. Inline CSS
Tiene mayor prioridad a Internal y External.
```html
<p style="color:#CAA; font-weight: bold; text-align:center;">Texto</p>
```


2. Internal CSS
Tiene mayor prioridad a External, pero menor a Inline.
```html

<head>
<style type="text/css">

  p{
    color:#CAA; 
    font-weight: bold; 
    text-align:center;
  }

</style>

</head>
```


3. External CSS
Tiene menor prioridad a Inline e Internal.

```html
<head>
<link href="css/estilos.css" rel="stylesheet"/>
</head>
```

## Selectores

1. Tag(s). Son las etiquetas HTML. 
```css
h1, h2{
   color:#CA0;
}

header{
  background-color:#EDEFEE;
}

a: link{
   color: orange;
}

a: hover{
   color: magenta;
}

a: active{
   color: white;
}

a: visited{
  color: gray;
}
```
2. Clase(s). Son pseudo clases que se pueden compartir.
```css
.texto-grande{
   font-size: 25px;
}

.texto-centrado{
   text-align: center;
}

```
Para invocar 
```html
<element class="texto-grande"/>
<element class="texto-centrado"/>
<element class="texto-grande texto-centrado"/>

```


3. Identificador(es). Un identificador que debe estar presente una sola vez.
```css
#textoGrande{
   font-size: 25px;
   font-weight: bold;
}

#textoGrandeCentrado{
  font-size: 25px;
  font-weight: bold;
  text-align: center;
}

```
Para invocar 
```html
<element id="textoGrande"/>
<element id="textoGrandeCentrado"/>
```
