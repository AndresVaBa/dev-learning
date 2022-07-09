# TODO LIST
* Formatear Laptop
* Windows 11 - 10 > WSL
    * Que es WSL


* Ubuntu

* **Que es Github**
   * Crear cuenta Github
Un repositorio es un espacio centralizado donde se almacena, organiza, mantiene y difunde información digital, habitualmente archivos informáticos, que pueden contener trabajos científicos, conjuntos de datos o software. Los repositorios tienen sus inicios en los años 90, en el área de la física y las matemáticas, donde los académicos aprovecharon la red para compartir sus investigaciones con otros colegas. Este proceso era valioso porque acelera el ciclo científico de publicación y revisión de resultados.
Son sistemas de información que preservan y organizan materiales científicos y académicos como apoyo a la investigación y el aprendizaje, a la vez que garantizan el acceso a la información. En los últimos años también se han creado repositorios de patrimonio cultural que contribuyen a la organización, preservación y difusión de colecciones de objetos culturales resguardadas por museos y otras instituciones de la memoria.

* **¿Credenciales SSH?**

SSH significa Secure Shell, y es una forma segura de acceder remotamente al servidor de un sitio. Las credenciales SSH son los datos de acceso:

* Dirección del servidor
* Número de puerto
* Nombre de usuario
* Contraseña

No todos los hosts o planes de hospedaje permiten el acceso SSH, pero si tienes credenciales SSH.

## **El protocolo SSH tiene tres capas:**
* La capa de transporte. Garantiza una comunicación segura entre el servidor y el cliente, controla el cifrado/descifrado de datos y protege la integridad de la conexión. También realiza el almacenamiento en caché y la compresión de los datos.
* La capa de autenticación. Lleva a cabo el procedimiento de autenticación del cliente.
* La capa de conexión. Gestiona los canales de comunicación tras la autenticación.

* Git 
   * Que es git

Es un software para el seguimiento de los cambios en cualquier conjunto de archivos, normalmente utilizado para coordinar el trabajo entre los programadores que desarrollan el código fuente en colaboración durante el desarrollo de software. Sus objetivos son la velocidad, la integridad de los datos y la compatibilidad con flujos de trabajo distribuidos y no lineales (miles de ramas paralelas que se ejecutan en diferentes sistemas).

* **Comandos básicos de git**

```
git init

Como alternativa, puedes crear un repositorio dentro de un nuevo directorio especificando el nombre del proyecto:
git init [nombre del proyecto]

git clone se usa para copiar un repositorio. Si el repositorio está en un servidor remoto, usa:
git clone nombredeusuario@host:/path/to/repository

A la inversa, ejecuta el siguiente comando básico para copiar un repositorio local:
git clone /path/to/repository

git add se usa para agregar archivos al área de preparación. Por ejemplo, el siguiente comando de Git básico indexará el archivo temp.txt:
git add <temp.txt>

git commit creará una instantánea de los cambios y la guardará en el directorio git.
git commit –m “El mensaje que acompaña al commit va aquí”

git config puede ser usado para establecer una configuración específica de usuario, como el email, nombre de usuario y tipo de formato, etc. Por ejemplo, el siguiente comando se usa para establecer un email:
git config --global user.email tuemail@ejemplo.com
La opción -global le dice a GIT que vas a usar ese correo electrónico para todos los repositorios locales. Si quieres utilizar diferentes correos electrónicos para diferentes repositorios, usa el siguiente comando:
git config --local user.email tuemail@ejemplo.com

git status muestra la lista de los archivos que se han cambiado junto con los archivos que están por ser preparados o confirmados.
git status

git push se usa para enviar confirmaciones locales a la rama maestra del repositorio remoto. Aquí está la estructura básica del código:
```

* **Terminal**
  * Comandos básicos de terminal (ls, clear, cd, pwd)

[![Alt text](https://img.youtube.com/vi/pbgkJkGBY2I/0.jpg)](https://www.youtube.com/watch?v=pbgkJkGBY2I)

* **Desarrollo**
  * HTML (Buscar definición y etiquetas)


HTML es un HyperText markup language, lo que significa que está escrito con códigos que puede leer una persona sin que sea necesario compilarlo primero. En otras palabras, el texto en una página web está «marcado» con estos códigos para dar instrucciones al navegador web sobre cómo mostrar el texto. Estas etiquetas de marcado son las propias etiquetas HTML.

*¿Cuáles son las etiquetas HTML básicas?*

Hay una serie de etiquetas que son las más usadas para crear cualquier documento HTML, a continuación las explicamos:

``` HTML
<body> para el contenido
<head> para información sobre el documento
<div> división dentro del contenido
<a> para enlaces
<strong> para poner el texto en negrita
<br> para saltos de línea
<H1>…<H6> para títulos dentro del contenido
<img> para añadir imágenes al documento
<ol> para listas ordenadas, <ul> para listas desordenadas, <li> para elementos dentro de la lista
<p> para parágrafos
<span> para estilos de una parte del texto

```

* **CSS (Buscar la definición)**

La solución vino de la mano de CSS (siglas en inglés de Cascading Style Sheets), en español "Hojas de estilo en cascada", un lenguaje de marcas enfocado a definir, crear y mejorar la presentación de un documento basado en HTML. Para muchos diseñadores gráficos CSS significó la puerta de entrada al mundo de la web y junto con otras tecnologías como JavaScript, CSS se ha ido imponiendo como uno de los pilares imprescindibles de la web de hoy en día.

El código CSS hace la vida más fácil al desarrollador front-end al separar las estructura de un documento HTML de su presentación. Dicho de otro modo el HTML actuaría como es esqueleto de la web, definiendo su estructura básica, y el CSS añadiría toda la capa de personalización sobre el que la web define su aspecto final.

* **REST**
  * Métodos

***Definición***

Los métodos HTTP definen la acción que se realizará sobre un determinado recurso. Los métodos HTTP, también suelen ser llamados HTTP Verbs. Aunque el nombre correcto es Verbs, la realidad es que, en la práctica, casi siempre son llamados “métodos”, por lo que utilizaremos el nombre “métodos” para referirnos a ellos.


----

* **GET:** Es utilizado únicamente para consultar información al servidor, muy parecidos a realizar un **SELECT** a la base de datos. No soporta el envío del payload
* **POST:** Es utilizado para solicitar la creación de un nuevo registro, es decir, algo que no existía previamente, es decir, es equivalente a realizar un INSERT en la base de datos. Soporta el envío del payload.
* **PUT:** Se utiliza para actualizar por completo un registro existente, es decir, es parecido a realizar un UPDATE a la base de datos. Soporta el envío del payload.
* **PATCH:** Este método es similar al método PUT, pues permite actualizar un registro existente, sin embargo, este se utiliza cuando actualizar solo un fragmento del registro y no en su totalidad, es equivalente a realizar un UPDATE a la base de datos. Soporta el envío del payload
* **DELETE:** Este método se utiliza para eliminar un registro existente, es similar a DELETE a la base de datos. No soporta el envío del payload.
* **HEAD:** Este método se utilizar para obtener información sobre un determinado recurso sin retornar el registro. Este método se utiliza a menudo para probar la validez de los enlaces de hipertexto, la accesibilidad y las modificaciones recientes.
 
Hasta aquí los métodos más utilizados en la construcción de servicios REST con JAX-RS, sin embargo, existen algunos métodos más que son interesantes conocer, pues no los encontraremos al momento de depurar o analizar el tráfico de red.
* **CONNECT:** Se utiliza para establecer una comunicación bidireccional con el servidor. En la práctica no es necesario ejecutarlo, si no el mismo API de HTTP se encarga de ejecutarlo para establecer la comunicación previo a lanzar alguna solicitud al servidor.
* **OPTIONS:** Este método es utilizado para describir las opciones de comunicación para el recurso de destino. Es muy utilizado con CORS (Cross-Origin Resource Sharing) para validar si el servidor acepta peticiones de diferentes orígenes.

---
**Backend**

Un backend es un los sistema corporativo que se utilizan para dirigir una web o empresa, tales como sistemas de gestión de pedidos, inventario y procesamiento de suministro. Este sistema recoge información de los usuarios u otros sistemas de tratamiento de datos en la compañía. Es el encargado de gestionar la información que proporciona el usuario recogida por el sitio web.

Un sistema de backend es cualquier sistema que soporta aplicaciones de “back office”. Estos sistemas se utilizan como parte de la gestión social y funcionan mediante la obtención de los datos de la entrada del usuario en el sitio y reunir las aportaciones de otros sistemas para proporcionar una salida de respuesta.

**Frontend**

El Front end es la parte de una web que conecta e interactúa con los usuarios que la visitan. Es la parte visible, la que muestra el diseño, los contenidos y la que permite a los visitantes navegar por las diferentes páginas mientras lo deseen. Es una de las dos mitades en las que se divide la estructura de cualquier página web.
Junto a esta se encuentra el Back end, que es el polo completamente opuesto, la capa que accede a datos y software en general para su comunicación. Ambas se reúnen en cualquier 

site que visite una persona y son las que, trabajando, hacen que funcione en todo momento tal y como lo hace.
Esta parte es la que engloba y muestra todo el trabajo de diseño web y, por lo general, reúne en su interior hasta 3 lenguajes de programación diferentes: HTML, CSS y JavaScript. Cada uno orientado a determinados fines en concreto, se suman para conseguir el resultado final que aparece por la pantalla de cada usuario que entra en una web, sea cual sea.

* **Lenguajes**
 * Golang (Que es y por que fue creado?)
    * Definición

Go, también conocido como Golang, es un lenguaje de programación creado por Google.
El lenguaje de Go proporciona un excelente soporte para subprocesos múltiples y por lo tanto, está siendo utilizado por muchas empresas que dependen en gran medida de los sistemas distribuidos.
Desde su invención, Go ha crecido enormemente a lo largo de los años. Golang tiene una sintaxis mínima bastante similar a otras secuencias de comandos idiomas. Fue construido para mejorar la productividad de los desarrolladores permitiéndoles escribir programas de una mejor manera.

JavaScript (No confundir Java con JavaScript)
Definición
JavaScript es un lenguaje de programación o de secuencias de comandos que te permite implementar funciones complejas en páginas web, cada vez que una página web hace algo más que sentarse allí y mostrar información estática para que la veas, muestra oportunas actualizaciones de contenido, mapas interactivos, animación de Gráficos 2D/3D, desplazamiento de máquinas reproductoras de vídeo, etc., puedes apostar que probablemente JavaScript está involucrado. Es la tercera capa del pastel de las tecnologías web estándar, dos de las cuales (HTML y CSS) hemos cubierto con mucho más detalle en otras partes del Área de aprendizaje.

***Notas:***

[Trata de buscar todo en inglés.](https://www.deepl.com/translator)

[Descarga de libros: ***Libro negro del programador***](https://z-lib.org/ )



## Commits Convencionales

[![Alt text](https://img.youtube.com/vi/Cp_SHttVTi0/0.jpg)](https://www.youtube.com/watch?v=Cp_SHttVTi0)

* Fix

Una confirmación del tipo fix corrige un error en su código base (esto se correlaciona con PATCH en el versionado semántico).

* BREAKING CHANGE

Una confirmación que tiene el texto CAMBIO DE RUPTURA: al principio de su cuerpo opcional o sección de pie de página introduce un cambio de ruptura en la API (se correlaciona con MAYOR en el versionado semántico). Un cambio de ruptura puede formar parte de commits de cualquier tipo. Por ejemplo, los tipos fix:, 

* Feat

Un commit del tipo feat introduce una nueva característica en el código base (esto se correlaciona con MINOR en el versionado semántico).
feat: y chore: serían todos válidos, además de cualquier otro tipo.
Otros: se permiten otros tipos de commit además de fix: y feat:, por ejemplo @commitlint/config-conventional (basado en la convención de Angular) recomienda chore:, docs:, style:, refactor:, perf:, test:, y otros. También recomendamos improvement para los commits que mejoran una implementación actual sin añadir una nueva característica o corregir un error. Tenga en cuenta que estos tipos no son obligatorios por la especificación de commits convencional, y no tienen ningún efecto implícito en el versionado semántico (a menos que incluyan un BREAKING CHANGE, que NO es recomendable). Se puede proporcionar un ámbito al tipo de una confirmación, para proporcionar información contextual adicional y está contenido entre paréntesis, por ejemplo, feat(parser): añadir la capacidad de analizar matrices.


 
* Refactor

Solamente se indica que se arreglo u ordeno el codigo.

* Realese

Indica que se ha hecho una nueva publicacion

* Doc

Indica que se a tocado la documentación

* Chore 

Commit de limpieza

### Ejemplos
Mensaje de confirmación con descripción y cambio de ruptura en el cuerpo

>feat: allow provided config object to extend other configs

* BREAKING CHANGE: 

La clave `extends` en el archivo de configuración se utiliza ahora para extender otros archivos de configuración
Mensaje de confirmación sin cuerpo
docs: corregir la ortografía de CHANGELOG
Mensaje de confirmación con alcance
feat(lang): añadido el idioma polaco
Mensaje de confirmación para una corrección utilizando un número de incidencia (opcional).
corrección: errores tipográficos menores en el código

véase la cuestión para conocer los detalles de los errores tipográficos corregidos



















