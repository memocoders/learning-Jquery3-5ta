# Jquery
jQuery es una biblioteca de JavaScript rápida, pequeña y rica en funciones. Hace que cosas como el recorrido y la manipulación de documentos HTML, el manejo de eventos, la animación y Ajax sean mucho más simples con una API fácil de usar que funciona en una multitud de navegadores. Con una combinación de versatilidad y extensibilidad, jQuery ha cambiado la forma en que millones de personas escriben JavaScript.

> __Se desarrollo el libro de Packt Book o Oreilly__

<a href="https://imgbb.com/"><img src="https://i.ibb.co/Pj1GDV4/descarga.jpg" alt="descarga" border="0"></a> 

## JQuery en acción
La biblioteca jQuery proporciona una capa de abstracción de propósito general para secuencias de comandos web comunes y, por lo tanto, es útil en casi todas las situaciones de secuencias de comandos.En tanto sus características principales nos ayudan a realizar las siguientes tareas:

- __Acceder a elementos en un documento :__ sin una biblioteca de JavaScript, los desarrolladores web a menudo necesitan escribir muchas líneas de código para recorrer el árbol del Modelo de objetos del documento ( DOM ) y ubicar partes específicas de la estructura de un documento HTML. Con jQuery, los desarrolladores tienen a su disposición un mecanismo de selección robusto y eficiente, lo que facilita la recuperación de la parte exacta del documento que debe inspeccionarse o manipularse.
```
$('div.contenido').find('p'); 
```
- __Modificar la apariencia de una página web :__ CSS ofrece un método poderoso para influir en la forma en que se representa un documento, pero se queda corto cuando no todos los navegadores web admiten los mismos estándares. Con jQuery, los desarrolladores pueden cerrar esta brecha, confiando en el mismo soporte de estándares en todos los navegadores. Además, jQuery puede cambiar las clases o las propiedades de estilo individuales aplicadas a una parte del documento, incluso después de que se haya renderizado la página.

```
$('ul > li:primero').addClass('activo'); 
```
- __Alterar el contenido de un documento :__ sin limitarse a meros cambios estéticos, jQuery puede modificar el contenido de un documento en sí mismo con unas pocas pulsaciones de teclas. El texto se puede cambiar, las imágenes se pueden insertar o intercambiar, las listas se pueden reordenar o la estructura completa del HTML se puede reescribir y ampliar, todo con una única interfaz de programación de aplicaciones ( API ) fácil de usar.

```
$('#contenedor').append('<a href="más.html">más</a>'); 
```
- __Responda a la interacción de un usuario :__ incluso los comportamientos más elaborados y poderosos no son útiles si no podemos controlar cuándo ocurren. La biblioteca jQuery ofrece una manera elegante de interceptar una amplia variedad de eventos, como un usuario que hace clic en un enlace, sin necesidad de saturar el código HTML con controladores de eventos.
```
$('botón.mostrar-detalles').click(() => { 
  $('div.detalles').mostrar(); 
});
```
- __Animar los cambios que se están realizando en un documento :__ para implementar de manera efectiva tales comportamientos interactivos, un diseñador también debe proporcionar comentarios visuales al usuario. La biblioteca jQuery facilita esto al proporcionar una variedad de efectos, como fundidos y borrados, así como un conjunto de herramientas para crear otros nuevos.
```
$('div.detalles').slideDown(); 
```
- __Recuperar información de un servidor sin actualizar una página :__ este patrón se conoce como Ajax , que originalmente significaba Asynchronous JavaScript and XML , pero desde entonces ha llegado a representar un conjunto mucho mayor de tecnologías para la comunicación entre el cliente y el servidor. La biblioteca jQuery elimina la complejidad específica del navegador de este proceso, lo que permite a los desarrolladores centrarse en la funcionalidad del lado del servidor.
```
$('div.detalles').load('más.html #contenido');
```