CSS

#Aprendiendo CSS
CSS son hojas de estilo para dar formato especial a páginas HTML.


##Tipos de CSS

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

##Selectores

1. Tag(s) 
2. Clase(s)
3. Identificador(es)


