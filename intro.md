
# Introducción. Algunas palabras sobre el libro.

## Una breve historia sobre este libro

¿Por qué otro libro en JavaScript? Por mucho que me guste "Tú no sabes JS" y "Elocuente JavaScript", siento que hay una necesidad de un libro que lleve al lector de la mano. Todos tienen un punto de vista único sobre temas técnicos y a mis lectores les encanta mi estilo de enseñanza. Este libro se publicó originalmente en italiano, pero muchos de sus compañeros desarrolladores pidieron una traducción. Y aquí está. El "Pequeño libro de JavaScript" pretende ser una referencia para las partes difíciles de JavaScript y al mismo tiempo ser fácil para principiantes. Espero que lo aprecies. Disfruta la lectura!

## Estructura del libro

El "Pequeño libro de JavaScript" está organizado en tres partes. La primera parte cubre el funcionamiento interno de los motores de JavaScript y las “partes difíciles” del lenguaje: *closures* o clausuras , el sistema *prototype* o prototipo, *this* y *new*. Cada capítulo termina con una prueba de autoevaluación, que es útil, para hacer que los conceptos se mantengan. La segunda parte del libro tiene una gran cantidad de ejercicios prácticos sobre el *DOM* con una gran cantidad de páginas que reúnen: la organización de códigos y las mejores prácticas. La tercera y última parte contiene soluciones para los ejercicios y futuras adiciones al libro.

## ¿Para quién es este libro?

Mientras escribo el libro, tengo en mente a los desarrolladores web que siempre trabajaban con jQuery o JavaScript sin profundizar en el lenguaje. El libro no es una introducción completa a la programación, pero con un poco de trabajo, deberías poder seguir adelante aunque nunca hayas programado antes. Recomiendo leer el libro incluso si eres un programador experimentado en JavaScript o si vienes de otro idioma. Puede que te sorprenda lo mucho que te olvidaste de JavaScript.

## ¿Qué debo saber antes de leer este libro?

El "Pequeño libro de JavaScript" no es una guía completa de ES6, la versión de JavaScript 2015. Supongo que el lector está familiarizado con ES6, pero lo introduciré un poco en el capítulo 2. Sin embargo, no se preocupe, le explicaré la sintaxis de ES6 a medida que la encontremos durante los capítulos.

## Convenciones tipográficas

Este libro utiliza JavaScript y encontrará ejemplos escritos dentro de un bloque:

```js
function generateTableHead(table, data) {
  var thead = table.createTHead();
  var row = thead.insertRow();
  for (var i = 0; i < data.length; i++) {
    var th = document.createElement("th");
    var text = document.createTextNode(data[i]);
    th.appendChild(text);
    row.appendChild(th);
  }
}
```
o en línea: `th.appendChild (texto)`. Encontrará tanto el código ES5 como el ES6 en el libro, el primero utilizado para no abrumar al lector al principio, el último utilizado para refactorizar código más tarde durante los ejercicios.

## ¿Cuál es la mejor manera de seguir los ejemplos?

Sugiero experimentar con el código y no solo copiar y pegar. Puede usar el editor que prefiera para escribir HTML y JavaScript. Luego, puede ver las páginas en un navegador. También puede utilizar una herramienta en línea como [Jsbin](https://jsbin.com) or [Codesandbox](https://codesandbox.io/).

## Errata y otras peticiones

Este libro no es una guía definitiva para JavaScript y es posible que me haya perdido algo que les gustaría leer. Lo bueno es que puedo actualizar el libro cuando quiera en Leanpub. Si desea que cubra algunos temas con mayor profundidad, no dude en enviarme un correo electrónico a valentino@valentinog.com.

## Sobre el Autor

Me enamoré de las computadoras desde que mi madre me regaló la primera PC cuando tenía 6 años. En 1999 creé las primeras páginas HTML y desde entonces la web se convirtió en mi vida. Hoy ayudo a las empresas ocupadas a implementar este loco y moderno JavaScript Hago entrenamiento y consultoría sobre JavaScript, React, Redux. Además de JavaScript, también estoy activo en la comunidad de Python. Me desempeño como coach para [Django Girls](https://djangogirls.org/) y he hablado en Pycon Italia. Echa un vistazo a [mis conversaciones aquí](https://www.valentinog.com/talks). En mi tiempo libre puedes encontrarme en el campo cerca de Siena. Si desea ponerse en contacto para tomar una cerveza, no dude en enviarme un correo electrónico a valentino@valentinog.com. ¿Te apetece leer algunas cosas sobre JavaScript o Python? Dirígete a [mi blog](https://www.valentinog.com/blog/)!

## Agradecimientos

Este libro no hubiera sido posible sin las preguntas inteligentes que he tenido durante los años gracias a docenas de desarrolladores. Un enorme agradecimiento también a todas las personas que ayudaron a dar forma a la versión beta de este libro: Caterina Vicenti, Alessandro Muraro, Cristiano Bianchi, Irene Tomaini, Roberto Mossetto, Ricardo Antonio Piana, Alessio Forti, Valentino Pellegrino, Mauro De Falco, Sandro Cantagallo , Maurizio Zannoni.

