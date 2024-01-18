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

**Comentarios en JavaScript: la sintaxis**

Existen dos variedades de comentarios en JavaScript: 
1. Comentarios de una sola línea 
2. Comentarios multilínea

Un comentario de una sola línea se crea cuando se añaden dos caracteres de barra diagonal uno detrás de otro, sin espacios. 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/f189f38d-1cb4-4eb1-bde3-ae89eeefe713)

Todo lo que sigue a un comentario de una sola línea en JavaScript es ignorado por el navegador. Esto significa que, esencialmente, puede escribir cualquier tipo de texto, código, caracteres, emojis, lo que sea, y el navegador lo ignorará. Un comentario de varias líneas, como su nombre indica, abarca varias líneas de código y se crea con una barra diagonal y una estrella. Por ejemplo: 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/a1428f3f-5b0b-4694-8564-f236dfd33fa9)

También puede utilizar la sintaxis de comentario multilínea en una sola línea de código, de la siguiente manera: 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/d4345e91-a587-4f1e-b474-b51c7537195b)

### El uso del punto y coma

En la lengua inglesa, el punto y aparte -el carácter.- se utiliza para separar pensamientos en frases.
Al separar claramente los pensamientos con el punto final, evita que se le malinterprete.
En JavaScript, el punto y coma -el carácter;- tiene un propósito similar: se utiliza para delimitar claramente unas partes del código de otras.

### Inserción Automática de Punto y Coma (ASI) en JavaScript

La "Inserción Automática de Punto y Coma" (ASI) es una función del navegador que completa los espacios en blanco en casos donde falta un punto y coma. Esta característica tiene implicaciones en la forma en que los desarrolladores escriben su código en JavaScript.
- **Función de Inserción Automática:**
  - El navegador, mediante la función ASI, puede detectar y corregir la ausencia de punto y coma en el código.

- **Impacto en Desarrolladores:**
  - La mayoría del tiempo, la función ASI hace que la adición o no de punto y coma no tenga una diferencia sustancial.
  - Algunos desarrolladores argumentan que debido a la ASI, no es necesario preocuparse por agregar punto y coma.

- **Posturas Divergentes de Desarrolladores:**
  - Existen dos opiniones entre los desarrolladores:
    - Algunos sostienen que no es necesario molestarse en agregar punto y coma, confiando en la función ASI.
    - Otros argumentan que es preferible utilizarlo siempre que sea necesario para mejorar la claridad del código.

- **Naturaleza Opcional y Estilística:**
  - En general, se percibe que la adición de punto y coma en JavaScript es opcional.
  - Se considera más como una preferencia estilística del desarrollador que como una regla estricta.

**Extra:** Si necesitas escribir varias líneas de código antes de ejecutarlas, asegúrese de pulsar la tecla de acceso directo MAYÚS + INTRO para pasar a la siguiente línea.
Fíjese en la distinción entre pulsar la tecla ENTER para ejecutar el código JavaScript que ha escrito, frente a pulsar el atajo de teclado SHIFT + ENTER para pasar a la siguiente línea de código (en lugar de ejecutar el código que ya ha escrito).

### Hello, World
Ahora que ha aprendido cómo instalar JavaScript en Visual Studio Code, procederemos a utilizarla dentro de este software.

En Visual Studio Code, creamos un nuevo archivo y vamos a utilizar la función console.log para imprimir las palabras "Hola, Mundo".

Ingrese el siguiente comando en la consola:

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/814422db-0ded-46d0-89ac-a29d59ff09ac)

Si ha hecho todo según las instrucciones, le debe de salir como en la imagen anterior.

He aquí otro comando más complejo, para mostrarle que el comando console.log viene con una serie de trucos.

En este fragmento de código, hay algunos añadidos: el tamaño de la fuente es diferente y el color es azul: 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/b170df7d-40b3-43f3-916b-10d9254c6b3c)

El resultado de este no se muestra muy bien Visual Studio Code, pero si usamos las herramientas para desarrolladores abiertas de Chrome, se tiene:

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/f0375a65-1c53-433f-81b4-606d9a0aeb19)

Si copia y pega este fragmento de código, o quizás, simplemente lo escribe en la consola, una vez que pulse la tecla ENTER para ejecutarlo, obtendrá como salida en la consola las palabras "Hola, mundo". Esta vez, sin embargo, el color de las letras será azul, y el tamaño de la fuente será de 40px. Acaba de aprender un buen truco con la consola. 

Si añade el %c justo después del carácter ", podrá dar estilo a la salida de la consola añadiendo el carácter , después del segundo "y luego, dentro de otro par de caracteres " y ", utilizar código CSS válido para dar estilo a las palabras que desea que salgan en la consola.

El motivo de mostrarle este pequeño truco era, con un poco de suerte, motivarle para que practique escribiendo varias palabras en el comando console.log, y utilice sus conocimientos de CSS para cambiar el estilo de estas palabras en la salida de la consola. De esta forma, puede que le resulte divertido practicar esta habilidad recién adquirida - y el aprendizaje y la diversión siempre van bien juntos.

### Salida de múltiples palabras en la consola

Para dar salida a múltiples palabras en la consola, puede unirlas utilizando el carácter +, conocido formalmente como el "operador de concatenación" cuando estamos uniendo trozos de texto, o el "operador de suma", para realizar la operación matemática de sumar dos números. 

He aquí un ejemplo de unión de tres trozos de texto separados: 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/4be444ac-e4af-466f-88a2-4ab8e77c1cf9)

La salida de este comando será Hello there, World.

He aquí un ejemplo de salida de tres trozos de texto separados utilizando el carácter , en su lugar:

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/f3570d54-0b26-4b8a-8a7c-3646daa0cf87)

La salida de este comando seguirá siendo: Hello there, World.
