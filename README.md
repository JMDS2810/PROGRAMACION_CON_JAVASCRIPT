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

### Variables
En el proceso de aprendizaje de JavaScript, se compara un programa JavaScript vacío con el primer nivel de un juego sandbox, donde el mundo está vacío pero hay una estructura subyacente para construir. El programador, al utilizar JavaScript, tiene la tarea de construir ese mundo. Las variables desempeñan un papel crucial en este proceso, permitiendo almacenar y reutilizar datos.

Veremos como declarar e inicializar variables en JavaScript. Se utiliza el ejemplo siguiente, en el cual se asigna el nombre "John" a una variable llamada "persona". Se observa la distinción entre la declaración y la asignación de variables. 

También, se destaca el uso del operador de asignación (=) para asignar valores a variables y cómo estas variables pueden utilizarse en el código.

La función console.log se presenta como una herramienta para emitir valores en la consola. Se muestra cómo combinar texto estático con variables dinámicas y cómo reasignar valores a las variables para lograr resultados diferentes. 

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/cc0681a8-a9c4-45aa-95a9-3da35edf8417)

**Ejercicio:**
- Declare una nueva variable denominada petDog y dele el nombre Rex.
- Declare una nueva variable llamada petCat y dele el nombre Pepper.
- Consola.log la variable petDog.
- Consola.log la variable petCat.
- Consola.log el texto "My pet dog's name is: " y la variable petDog.
- Consola.log el texto "My pet cat's name is: " y la variable petCat.
- Declare otra variable y nómbrela catSound. Asígnele la cadena "purr".
- Declare otra variable y nómbrela dogSound. Asígnele la cadena de texto "woof".
- Consola.log la variable petDog, luego la cadena "says", luego la variable dogSound.
- Consola.log la variable petCat, luego la cadena "says", luego la variable catSound.
- Reasigne el valor almacenado en catSound a la cadena "meow".
- Consola.log la variable petCat, luego la cadena "now says", luego la variable catSound.

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/2d6ff2c4-7c2e-4945-a6e4-68e2972faaae)

### Tipos de datos

#### Tipos de Datos Fundamentales:

- **Cadena (String):** Se utiliza para almacenar valores de texto. En el ejemplo, se menciona almacenar el nombre y la descripción de una guitarra.
- **Número (Number):** Se utiliza para almacenar valores numéricos. En el ejemplo, se utiliza para almacenar el precio de la guitarra.
 
**Diferencias en la Construcción:**
 - La construcción de números implica simplemente escribir los valores numéricos.
 - Para construir una cadena en JavaScript, los caracteres deben ir entre comillas simples o dobles.
   
**Rangos y Capabilidades:**

- El tipo de datos número tiene un rango amplio, pero está limitado por las capacidades de cálculo de JavaScript.
- El tipo de datos cadena tiene prácticamente un número ilimitado de combinaciones de caracteres.

**Otros Tipos de Datos Primitivos:**

- **Booleano (Boolean):** Útil para tomar decisiones con solo dos valores posibles: verdadero o falso.
- **Nulo (Null):** Representa la ausencia de valor.
- **Indefinido (Undefined):** Se refiere a una variable a la que aún no se le ha asignado un valor.
- **BigInt:** Introducido en ES6, permite almacenar números más grandes que el tipo de datos number.
  **Símbolo (Symbol):** Puede utilizarse como un identificador único.
  
**Analogía con Cajas:** Se compara cada tipo de dato con una caja, resaltando que cada uno tiene un propósito específico.

### Operaciones
Se verán los operadores en JavaScript, estos se utilizan para realizar operaciones en variables y valores. Destacan los operadores de asignación y comparación, además de los operadores aritméticos como suma, resta, multiplicación y división. Además, se abordan los operadores lógicos "AND", "OR" y "NOT" para evaluar condiciones booleanas.

1. **Operadores de Asignación y Aritméticos:**
   - Los operadores de asignación se utilizan para realizar cálculos simples y complejos.
   - Se verán ejemplos de operadores aritméticos (suma, resta, multiplicación, división) en el código siguiente para mostrar las operaciones matemáticas básicas

2. **Operadores de Comparación y Lógicos:**
   - Los operadores de comparación se utlizan para evaluar condiciones y devolver valores booleanos (verdadero/falso).
   - Los operadores lógicos "AND" (&&), "OR" (||) y "NOT" (!) son presentados para combinar condiciones booleanas.

**Código en JavaScript:**
```javascript
// Ejemplos de operadores aritméticos
console.log(2 + 2);   // Suma: 4
console.log(20 - 18);  // Resta: 2
console.log(2 * 3);    // Multiplicación: 6
console.log(8 / 1);    // División: 8

// Ejemplos de operadores de comparación
console.log(3 > 2);    // Mayor que: true
console.log(2 > 3);    // Mayor que: false
console.log(10 === 10); // Igualdad: true
```

Este código en JavaScript refleja los ejemplos mencionados en el texto, proporcionando resultados en la consola para cada operación.

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/53d6bcf8-27a7-4fde-a405-c80dbd970893)

### Números en JavaScript

1. **Representación de Números:**
   Pueden ser enteros y decimales. Por ejemplo, 123, 123.456.

2. **Operaciones Matemáticas:**
   - Suma: `+`.
   - Resta: `-`.
   - Multiplicación: `*`.
   - División: `/`.
   - Exponenciación: `**`.
   - Resto o módulo: `%`.
     
3. **Uso de Paréntesis:**
   El uso de los paréntesis y su importancia radica en son de mucha ayuda para controlar el orden de las operaciones y al realizar cálculos más complejos.
       
- **Código en JavaScript:**
  ```javascript
  // Ejemplo de números y operaciones matemáticas en JavaScript

  // Representación de Números
  console.log(123);
  console.log(123.456);

  // Operaciones Matemáticas
  console.log(2 + 2);      // Suma
  console.log(4 - 2);      // Resta
  console.log(4 * 4);      // Multiplicación
  console.log(16 / 4);     // División
  console.log(10 ** 2);    // Exponenciación
  console.log(9 % 8);      // Resto o módulo

  // Uso de Paréntesis
  console.log((2 * 4) + 8);  // Control de Prioridad
  ```

- **Observaciones:**
  - Los operadores matemáticos básicos (`+`, `-`, `*`, `/`) son fundamentales.
  - El operador de módulo (`%`) es útil para obtener el resto de una división.
  - El uso de paréntesis permite controlar el orden de las operaciones.

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/fad18c9b-a218-4b82-ad55-690b88364696)

### Cadenas y cuerdas

En JavaScript, las cadenas son fundamentales y se utilizan para representar y manipular secuencias de caracteres en el código. Estas cadenas se definen encerrando los caracteres entre comillas simples ('') o dobles (""). Este tipo de dato es común y esencial en el contexto de la programación.

Para crear una cadena vacía, se utilizan comillas simples o dobles sin ningún carácter entre ellas. En cambio, para una cadena con contenido, se pueden incluir letras, símbolos y números. Es importante tener en cuenta que las cadenas no admiten saltos de línea, y si se intenta introducir un salto de línea en el código, se generará un error.

Un aspecto a considerar es el manejo de comillas y apóstrofos en las cadenas. Si se necesita incluir una contracción como "it's", es necesario ser precavido para evitar confusiones y errores en el código. Por ejemplo, anidar comillas simples dentro de comillas dobles o viceversa puede ser necesario para resolver estos problemas.

- **Código en JavaScript:**
  ```javascript
  // Ejemplo de Cadenas en JavaScript

  // Cadena vacía
  let cadenaVacia = '';

  // Cadena no vacía
  let saludo = '¡Hola!';

  // Cadena con símbolos y números
  let cadenaCompleja = '¡Hola!@#$%^&123';

  // Problema con saltos de línea
  // let cadenaConSalto = 'Hola
  // Mundo'; // Error

  // Solución al problema de apóstrofos
  let nuevaCadena = "Hace un día precioso. It's amazing!";
  ```

### Booleanos
El tipo de dato booleano en JavaScript desempeña un papel fundamental al evaluar la veracidad o falsedad de afirmaciones. En este contexto, se centra en cómo obtener resultados de comparaciones para determinar si dos valores son iguales o no. Un valor booleano, en esencia, puede ser verdadero o falso, y esta distinción es clave para la lógica de programación.

```javascript
// Ejemplos de comparaciones con operador menor que y mayor que
console.log(1 < 2); // true
console.log(1 > 2); // false
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/c5ab848f-7ed7-4caa-af25-7e829c0880dd)

Los operadores de comparación, como menor que (<) y mayor que (>), permiten evaluar condiciones y obtener un resultado booleano. Este principio se extiende a otros operadores, como los de igualdad y desigualdad.

```javascript
// Ejemplos de operadores de igualdad y desigualdad
console.log(1 === 2); // false (igualdad estricta)
console.log(1 == "1"); // true (igualdad no estricta)
console.log(1 !== 2); // true (desigualdad estricta)
console.log(1 != "1"); // false (desigualdad no estricta)
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/55b07d58-eebc-4fe1-b318-70105c12a1bd)

La distinción entre el operador de igualdad simple (==) y el de igualdad estricta (===) es esencial. El primero evalúa solo el valor, ignorando el tipo de datos, mientras que el segundo compara tanto el valor como el tipo.

```javascript
// Ejemplos de operadores de igualdad estricta y desigualdad estricta
console.log(1 === "1"); // false
console.log(1 !== "1"); // true
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/285b28eb-42e7-4c1a-afec-dd9b15e77ce3)

Además, se explora el operador de desigualdad simple (!=) y el de desigualdad estricta (!==), mostrando cómo manejan las comparaciones en función del valor y el tipo de datos.

### Condicionales

En el contexto de la programación, al referirse a condicionales, se utiliza reucurrentemente las sentencias `if`, las cuales permiten ejecutar un bloque de código si una condición dada es evaluada como verdadera. Por ejemplo, si queremos determinar si un estudiante aprueba o suspende un examen de conducir, podríamos usar la sentencia `if` para comprobar si su puntuación es mayor a 40.

```javascript
let puntuacion = 45;

if (puntuacion > 40) {
  console.log("¡Felicidades! Has aprobado el examen.");
}
```

Aquí, el bloque de código dentro del `if` se ejecutará solo si la condición (`puntuacion > 40`) es verdadera. En este caso, imprimirá en la consola el mensaje de aprobación.

Luego, se introduce la sentencia `else`, que permite ejecutar un bloque de código alternativo si la condición en el `if` resulta ser falsa. Siguiendo el ejemplo anterior:

```javascript
let puntuacion = 35;

if (puntuacion > 40) {
  console.log("¡Felicidades! Has aprobado el examen.");
} else {
  console.log("Lo siento, no has aprobado esta vez.");
}
```

En este caso, si la puntuación es menor o igual a 40, se ejecutará el bloque de código dentro del `else`, imprimiendo un mensaje indicando que el estudiante no ha aprobado.

Este enfoque de `if` y `else` proporciona una estructura básica para tomar decisiones en la programación, y se destaca su importancia como un fundamento fundamental en JavaScript.

#### if, else y switch

Se tienen las sentencias condicionales en JavaScript, en particular las sentencias `if`, `else if` y la sentencia `switch`. Se hace énfasis en la utilidad de estas estructuras para ejecutar bloques de código basándose en la evaluación de condiciones, ya sea verdaderas o falsas.

##### Sentencia `if` y `else`
La sentencia `if`, como anteriormente se mencionó, se utiliza para ejecutar un bloque de código si una condición dada es verdadera. Se presenta un ejemplo donde se asigna un valor a la variable `resultado` y se verifica si es mayor que 40. Además, se introduce la sentencia `else` para manejar el caso en que la condición es falsa.

```javascript
let resultado = 50;

if (resultado > 40) {
  console.log("Pasa la prueba");
} else {
  console.log("Usted no pasó la prueba");
}
```

##### Sentencia `else if`
Se aborda el escenario en el que hay múltiples condiciones y se introduce la sentencia `else if` para manejar estas situaciones de manera más estructurada. Se presenta un ejemplo con la variable `place` que puede tener varios valores y se utilizan múltiples sentencias `else if` para evaluar distintas condiciones.

```javascript
let place = "Primero";

if (place === "Primero") {
  console.log("Oro");
} else if (place === "Segundo") {
  console.log("Plata");
} else if (place === "Tercero") {
  console.log("Bronce");
} else {
  console.log("Sin medalla");
}
```

##### Sentencia `switch`
Se introduce la sentencia `switch` como una alternativa para manejar múltiples condiciones. Se proporciona un ejemplo similar al anterior, pero implementado con `switch`, destacando la diferencia de sintaxis y su capacidad para gestionar varias condiciones de manera más concisa.

```javascript
let place = "Primero";

switch (place) {
  case "Primero":
    console.log("Oro");
    break;
  case "Segundo":
    console.log("Plata");
    break;
  case "Tercero":
    console.log("Bronce");
    break;
  default:
    console.log("Sin medalla");
    break;
}
```



