# Que es ASSCII
___
El código ASCII es un estándar para la representación de caracteres en cualquier dispositivo electrónico, haciendo referencia a una codificación fija que asigna a caracteres imprimibles como letras, números y signos de puntuación y a caracteres de control no imprimibles un código concreto, que al pasar por el dispositivo lo traduce y muestra el carácter deseado.

Debemos recordar que los ordenadores actúan siempre sobre el sistema binario para realizar sus cálculos, por lo que todas las operaciones hechas en ellos se basan en el uso de ceros y unos. ASCII se creó bajo la misma premisa definiendo sus caracteres en siete bits, es decir, siete posiciones que muestran un 0 o un 1 y un octavo bit que se reserva para hacer análisis. Las versiones ampliadas basadas en el American Standard Code for Information Interchange emplean dicho bit para incrementar los caracteres existentes a 256.

Por ponernos brevemente en el contexto histórico, en 1963 la American Standards Association aprobó el lanzamiento del American Standard Code for Information Interchange (ASCII), sentando las bases de lo que sería el futuro de los dispositivos electrónicos a la hora de representar los diversos caracteres que utilizamos las personas al manejar ordenadores u otro aparato que funcione con esta codificación.

## Cómo se estructura el código ASCII

Los caracteres en el sistema ASCII se reparten de la siguiente forma:

* En primer lugar tenemos los caracteres de control (0–31 & 127), que se encargan de transmitir comandos a un ordenador o a un periférico conectado a un dispositivo principal (como una impresora) para que ejecuten determinadas acciones. Por ejemplo, el carácter 10 (en binario 0000 1010) representa la función «salto de línea», que hace que una impresora baje una línea de escritura en una hoja de papel, o por ejemplo el carácter 27 (0001 1011 en binario) representa la tecla «Escape», situada en la esquina superior izquierda de los teclados comunes.
* Dentro de los caracteres de control, debemos mencionar el último código en el sistema ASCII, marcado con el número 127 (0111 1111) y que fue creado para activar la opción «Suprimir» (Delete en los teclados).
* En segundo lugar tenemos los caracteres denominados imprimibles (agrupados en los grupos 32–47, 58–64, 91–96 y 123–126). Aquí se incluyen todos los caracteres que no son ni letras ni números, es decir, son los grupos asignados para signos de puntuación, símbolos matemáticos, y la tecla del espacio en blanco, considerado bajo este sistema como un carácter imprimible.
* El tercer gran grupo lo conforman los caracteres numéricos (30–39), que recogen las diez cifras del cero al nueve que usamos en nuestra vida diaria.
* Por último, no podía faltar el grupo de caracteres relacionados con las letras (65–90 / 97–122), que se divide en dos partes: un bloque dedicado para las letras escritas en mayúscula y el segundo bloque para las letras en minúscula.

# Que es UTF-8
___

UTF-8 (Unicode Transformation Format-8) es un formato de codificación de caracteres, en el que cada caracter es representado por un octeto (8 bits). También existen UTF-16 y UTF-32. La ventaja de UTF-8 respecto a estos otros es que es compatible con versiones anteriores de ASCII.

Unicode está reemplazando al código ASCII ya que permite a los usuarios gestionar todos los lenguajes del planeta además de símbolos matemáticos que simplifican el intercambio de información científica.

Para usar utf-8, UTF 8, en nuestros documentos se deberá especificar que se quiere usar este formato de codificación de forma explícita, en documentos de tipo HTML, XML, etc si no lo hacemos es posible que veamos caracteres extraños al abrirlos con el navegador.

Para usar este formato de codificación en páginas web HTML debemos escribir la siguiente instrucción en los encabezados del documento:

```
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">

```

En un archivo XML:


```
<?xml version="1.0" encoding="UTF-8" ?>
```
En los archivos de configuración del servidor Apache (httpd.conf) o en un archivo .htaccess


```
AddDefaultCharset UTF-8
```
En scripts PHP


```
<?php header("content-type: text/html; charset: utf-8"); ?>
```