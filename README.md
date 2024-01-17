# Programación con JavaScript

## Introducción

JavaScript, a menudo denominado el "lenguaje de la web", se ha convertido en un pilar esencial en el mundo del desarrollo de software. Este lenguaje de programación, diseñado para brindar dinamismo e interactividad a las páginas web, ha evolucionado más allá de su función inicial y se ha convertido en una herramienta integral en el desarrollo tanto del front-end como del back-end. Desde la creación de elementos interactivos en páginas web hasta el desarrollo de aplicaciones móviles modernas utilizando tecnologías como React, JavaScript impulsa gran parte de la experiencia en línea que damos por sentado en la vida cotidiana.

JavaScript proporciona a los desarrolladores una capacidad única para crear funciones dinámicas y atractivas en sus proyectos. A través de su sintaxis flexible y su capacidad para ejecutarse directamente en el navegador, permite la manipulación de elementos HTML, la gestión de eventos del usuario y la creación de aplicaciones completas. Este lenguaje, con una comunidad activa y en constante evolución, sigue desafiando los límites del desarrollo de software y ofrece oportunidades emocionantes para aquellos que buscan incursionar en el mundo de la programación. En esta introducción a JavaScript, exploraremos desde los fundamentos hasta aspectos más avanzados, permitiendo a los desarrolladores entender y aprovechar plenamente el potencial de este lenguaje versátil.

## Instalación

Antes de comenzar a programar con JavaScript, es necesario configurar el Visual Studio Code (VS Code). VS Code es un editor de código que los desarrolladores utilizan para escribir su código JavaScript de manera eficiente. Al finalizar este proceso, podrás instalar VS Code, Node.js y la extensión Code Runner en tu sistema operativo Windows. A continuación, se detalla el procedimiento:

1. Abre un motor de búsqueda y busca "VS Code" o "Visual Studio Code". Accede al sitio web oficial en https://code.visualstudio.com/ y selecciona el botón de descarga para Windows. 
2. Después de descargar el archivo, inicia el proceso de instalación. Acepta el contrato de licencia y elige la configuración de destino predeterminada.
3. Configura tareas adicionales, como la creación de un icono en el escritorio y la adición de acciones al menú contextual del Explorador de Windows. Haz clic en "Siguiente" y, finalmente, selecciona "Instalar".
4. Inicia Visual Studio Code y selecciona "Finalizar" una vez completada la instalación.
5. Abre el panel de extensiones de VS Code desde la esquina inferior izquierda de la ventana. Busca la extensión "Code Runner", instálala y confirma que está habilitada.
6. En paralelo, busca "Node.js" en tu navegador https://nodejs.org/en y descarga la versión para Windows desde el sitio oficial de Node.js. Completa el proceso de instalación.
7. De regreso en VS Code, verifica que Code Runner esté instalado y habilitado.
8. Abre un nuevo archivo JavaScript en VS Code, escribe código, y ejecútalo utilizando Code Runner. Puedes utilizar el comando "console.log" para imprimir mensajes en la consola.
   
![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/ebcff072-fd87-4b60-807f-0d46ce1790b5)

Este proceso te permite configurar con éxito Visual Studio Code con Code Runner, lo que te permite escribir y ejecutar código JavaScript.

## Importancia

JavaScript es esencial para la interactividad en las páginas web y se ha convertido en el lenguaje predominante en el lado del cliente desde sus inicios en 1995. Proporciona actualizaciones en tiempo real, facilitando funciones como mapas interactivos y validación de formularios. Es el único lenguaje que permite interactuar directamente con las páginas web dinámicamente en el cliente. Su popularidad se debe a la retrocompatibilidad, asegurando que las páginas web antiguas sigan funcionando. Los desarrolladores lo eligen por su facilidad de uso y accesibilidad. Se puede interactuar con el motor JavaScript a través de la consola del navegador, lo que simplifica el proceso para los principiantes.
JavaScript se utiliza en todo tipo de sitios web, desde el lado del cliente hasta frameworks como React y en el servidor a través de Node.js y Deno. La comunidad de desarrollo de JavaScript es amplia y accesible, lo que facilita la obtención de ayuda y orientación. Además, las habilidades en JavaScript están en alta demanda, lo que lo convierte en una opción valiosa para los desarrolladores.
En resumen, aprender JavaScript no solo es esencial para el desarrollo web, sino que también es accesible, versátil y ofrece oportunidades laborales significativas en la industria tecnológica.

## Programación en JavaScript
### Comentarios

Se ha elegido los comentarios como punto de partida por dos razones: 

**Su sintaxis:** la forma en que se escriben los comentarios es fácil de entender. 

Escribir comentarios puede potenciarle como desarrollador.

En primer lugar, explicaré la sintaxis, y después, discutiré por qué poder escribir comentarios es tan potenciador.

Comentarios en JavaScript: la sintaxis
Existen dos variedades de comentarios en JavaScript: 

Comentarios de una sola línea 

**Comentarios multilínea**

Un comentario de una sola línea se crea cuando se añaden dos caracteres de barra diagonal uno detrás de otro, sin espacios. 

// this is a comment!

Todo lo que sigue a un comentario de una sola línea en JavaScript es ignorado por el navegador.

Esto significa que, esencialmente, puede escribir cualquier tipo de texto, código, caracteres, emojis, lo que sea, y el navegador lo ignorará.

Un comentario de varias líneas, como su nombre indica, abarca varias líneas de código y se crea con una barra diagonal y una estrella. Por ejemplo: 

/*
this
is
a
multi-line
comment
*/

También puede utilizar la sintaxis de comentario multilínea en una sola línea de código, de la siguiente manera: 

/* this is a multi-line comment on a single line */
