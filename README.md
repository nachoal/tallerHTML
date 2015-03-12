# tallerHTML
Taller de HTML, CSS y Javascript

####HTML
`<!DOCTYPE html>` esta tag no es de HTML pero la tenemos que usar para que el navegador sepa que tipo de documento esperar.

`<html></html>` Tag que indica que todo lo que está adentro de ella es HTML.

`<head></head>` Aquí ponemos detalles que no se ven en la página (links, scripts, estilos, título)

`<title></title>` Tag para darle nombre a nuestra página, lo que se ponga aquí se verá como el nombre en la pestaña de nuestro navegador.

`<body></body>` El cuerpo de nuestro documento, aquí va el contenido.

`<h1></h1>` Se usa para títulos (heading) puedes usarla de 1 a 6, entre mayor sea el número, menor la importancia del título. **Regla**: Sólo usamos un H1 en toda la página para nuestro título principal y más importante.

`<ul></ul>` Una lista sin numeración (Unordered List)

`<ol></ol>` Una lista con numeración (Ordered List)

`<li></li>` (List Item) Se usa para indicar cada elemento de la lista

`<img src="" alt="">` Es para insertar una imagen dentro del documento y es la primer tag que vemos que se cierra sola (self closing)

`<div></div>` Significa division y es para darle formato o estilo a un bloque (block) del documento

`<span></span>` No tiene un significado en específico pero se usa como div, para dar formato pero en una línea (inline) del documento


####CSS

CSS (Cascading Style Sheets) es el lenguaje que usamos para darle estilo a nuestro documento y tiene un formato un poco diferente a HTML pero lo podemos entender facilmente. 

Hay 3 formas de implementarlo:

1.Usando el atributo style en nuestros elementos dentro del HTML (inline)

2.Haciendo uso de la tag `<style></style>` dentro de nuestro `<head></head>` e insertando nuestros estilos ahí (internal)

3.Haciendo una hoja de estilos separada con terminacion .css e importandola con`<link rel="stylesheet" type="text/css" href="">` (External)


#####Selectores

En css puedes elegir con selector al elemento al que quieres aplicarle el estilo:

Selectores de elemento: Se usa el nombre de la tag de HTML y se aplicará el estilo a todos los elementos con esa tag, ejemplo: 

`h1{ color:red;  } `

Selectores de clase: Se usa un punto y se aplicará a todo lo que esté adentro de esa clase, ejemplo:

`.container{ width:500px; }`

Selectores de id: Se usa un signo de gato y se aplicará al id, ejemplo: 

`#importante{font-size: 60px;}`

Las clases se pueden repetir en todo el documento, en cambio, por cada id solo puede haber un elemento con ese id.

#####Colores

Podemos cambiar los colores del documento de diferentes maneras

1.Con la palabra (Que nos limita en nuestra elección): 

 `h1{ color:red;  } `

2.Con el código Hexadecimal, con 6 digitos, 2 para el rojo, 2 para el verde y 2 para el azul: 

`h1{ color:#FF0000;  } `

3.Con el código rgb (Red, green, blue): 

`h1{ color: rgb(255, 0, 0);  } `

4.Con rgba(Red,Green,Blue,Alfa) el alfa lo usamos para hacer transparentes nuestros fondos:

`h1{ color: rgba(255, 0, 0, 1);  } `

Hay muchos programas que podemos usar para extraer el código de color yo les recomiendo:

[Sip para mac](https://itunes.apple.com/us/app/sip/id507257563?mt=12)

[Colorzilla (extensión de chrome)](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp)

Para sacar paletas de colores cool:

https://color.adobe.com/

http://www.colourlovers.com/

http://app.coolors.co/3f7cac-95afba-bdc4a7-d5e1a3-e2f89c


#####Margenes y espacios

Para separar los elementos, centrarlos y acomodarlos podemos usar la propiedad Margin y Padding

![contenido](http://www.spsbaumann.com/uploads/5/1/3/9/5139232/1104839_orig.png)

**Margin** es el espacio que dejamos **afuera** del elemento

**Padding** es el espacio que dejamos **adentro** 

Margin tiene 4 parámetros (top, right, bottom, left) es decir: 

`.contanier{ margin-top: 20px; margin-right: 40px; margin-bottom: 20px; margin-left: 40px;  } `

Lo podemos acortar usando el shorthand:

`.contanier{ margin: 20 40 20 40  } `

mucho más simple, ¿no?

Para centrar un contenido con tamaño definido dentro de la página podemos usar margin:

`.contanier{ width: 120px; margin: 0 auto;  } `













