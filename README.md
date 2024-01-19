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

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/f29ee335-86dc-4a02-9667-2cb9f68cad02)

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

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/f73daf55-9dbd-4e34-a3b9-fa8ba3e75940)

En este caso, si la puntuación es menor o igual a 40, se ejecutará el bloque de código dentro del `else`, imprimiendo un mensaje indicando que el estudiante no ha aprobado.

Este enfoque de `if` y `else` proporciona una estructura básica para tomar decisiones en la programación, y se destaca su importancia como un fundamento fundamental en JavaScript.

#### if, else if y switch

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

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/4cbf89a9-b9bc-4f9b-8778-d7ee939c6ebf)

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

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/0a382e11-8af0-4da4-8bf0-0b63d5195b87)

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

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e2142bb3-f4bb-4783-8535-0504ba179f20)

### Bucles en JavaScript: For y While

En la programación, a menudo nos encontramos con situaciones en las que necesitamos realizar tareas repetitivas. Esto es similar a las acciones cotidianas que realizamos de forma repetida, como cerrar botones, lavar platos o contar hasta uno antes de cantar "Feliz Año Nuevo". En JavaScript, para manejar estas tareas repetitivas, utilizamos construcciones de bucles.

**Bucle For:**

El bucle `for` es una estructura de bucle estructurada que se utiliza para repetir un bloque de código un número específico de veces. Su estructura básica incluye la inicialización de un contador, una condición que se evalúa antes de cada iteración, y una expresión de incremento o decremento. Veamos un ejemplo de un bucle `for` que cuenta hasta tres:

```javascript
for (let i = 1; i <= 3; i++) {
  console.log(i);
}
```

En este caso, `let i = 1` inicializa el contador, `i <= 3` establece la condición, y `i++` incrementa el contador después de cada iteración.

**Bucle While:**

El bucle `while`, por otro lado, también se utiliza para repetir un bloque de código mientras una condición dada sea verdadera. A diferencia del bucle `for`, el contador se inicializa fuera del bucle y se incrementa dentro del bloque. Aquí hay un ejemplo que realiza la misma tarea de contar hasta tres utilizando un bucle `while`:

```javascript
let contador = 1;

while (contador <= 3) {
  console.log(contador);
  contador++;
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/29fa323d-ac61-4dde-856f-183b591ea37e)

En este caso, `contador` se inicializa antes del bucle, y dentro del bucle, se comprueba la condición `contador <= 3`, y se incrementa el contador.

Ambos bucles proporcionan resultados similares, pero la elección entre `for` y `while` depende del contexto y las preferencias del desarrollador. Es fundamental recordar actualizar el valor del contador en cada iteración para evitar bucles infinitos.

### Bucles For en JavaScript:

#### Estructura del Bucle For:

En programación, cuando se enfrenta a situaciones en las que es necesario realizar una tarea repetitiva, como contar o realizar una acción específica varias veces, los bucles son fundamentales. El bucle `for` es especialmente útil en estos casos debido a su estructura concisa y controlada.

**Ejemplo de Conteo de 1 a 3:**

Supongamos que queremos realizar la tarea de contar de 1 a 3 y luego decir "go". Podríamos lograrlo registrando cada paso en la consola, pero este método se vuelve ineficiente cuando se trata de contar hasta números más grandes. Aquí es donde entra en juego el bucle `for`. A continuación se presenta un ejemplo:

```javascript
for (let i = 1; i <= 3; i++) {
  console.log(i);
}

console.log('go');
```

En este código, `let i = 1` inicializa el contador, `i <= 3` establece la condición de salida, y `i++` incrementa el contador después de cada iteración. El bucle se ejecutará mientras `i` sea menor o igual a 3.

**Conteo Regresivo de 10 a 1:**

Además, el texto muestra cómo adaptar el bucle para realizar un conteo regresivo de 10 a 1, seguido por un saludo de "Feliz Año Nuevo":

```javascript
for (let i = 10; i > 0; i--) {
  console.log(i);
}

console.log('Feliz Año Nuevo');
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/be71cbf9-c3c2-4f14-a917-f31c7f79799e)

En este caso, el bucle inicia con `i = 10`, la condición de salida es `i > 0`, y `i--` decrementa el contador en cada iteración.

**Condiciones de un Bucle For:**

El bucle `for` consta de tres partes: la inicialización del contador, la condición de salida y el incremento o decremento del contador. Estas partes trabajan en conjunto para controlar la ejecución del bucle. La condición de salida es crucial para evitar bucles infinitos.

### Bucle While en JavaScript: 

A diferencia del bucle `for`, el bucle `while` tiene el contador definido antes del bucle y solo requiere especificar la condición de salida. La estructura básica es la siguiente:

```javascript
let contador = 3; // Inicialización del contador

while (contador > 0) {
  console.log(contador);
  contador = contador - 1; // Actualización del contador
}

console.log('¡Feliz Año Nuevo!');
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e7618071-4b2b-40b4-97ba-ff72b98d3622)

**Explicación del código:**

1. **Inicialización del contador:** Se crea una variable llamada `contador` y se establece su valor en 3, que es el punto de inicio para la cuenta regresiva.

2. **Condición de salida:** La condición del bucle `while` se establece como `contador > 0`. Mientras esta condición sea verdadera, el bucle se ejecutará.

3. **Bloque de código del bucle While:** Dentro del bucle, se utiliza `console.log(contador)` para imprimir el valor actual del contador en la consola. Luego, se actualiza el contador restando 1 en cada iteración.

4. **Actualización del contador:** `contador = contador - 1` reduce el valor del contador en 1 en cada iteración.

5. **Finalización del bucle:** Una vez que el contador llega a 0 y la condición `contador > 0` devuelve falso, el bucle while se detiene.

6. **Mensaje de feliz año nuevo:** Después de salir del bucle, se emite un mensaje adicional en la consola: `'¡Feliz Año Nuevo!'`.

**Flujo del Bucle While:**

Se detalla cómo el bucle `while` funciona, mostrando cómo el valor del contador se actualiza en cada iteración. Comienza con 3, reduce a 2, luego a 1, y finalmente llega a 0, deteniendo el bucle.

### Bucles Anidados en JavaScript

Cuando se necesitan realizar varias tareas simultáneamente, como procesar dos conjuntos de datos A y B, los bucles anidados en JavaScript ofrecen una solución eficiente. A través del uso de bucles anidados, se pueden ejecutar tareas dentro de tareas, proporcionando flexibilidad en la automatización de código.

**Ejemplo Práctico: Plan de Dos Semanas**

**Código utilizando bucles anidados con bucles for:**

```javascript
for (let i = 1; i <= 2; i++) { // Bucle exterior para las semanas
  for (let j = 1; j <= 5; j++) { // Bucle interior para los días
    console.log(`Semana ${i}, Día ${j}`);
  }
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/fe602d9d-fa3c-4588-8e22-a919d1a86e6c)

**Explicación:**

- Se utilizan dos bucles `for`. El primero (bucle exterior) itera sobre las semanas (1 y 2).
- El segundo (bucle interior) itera sobre los días (1 al 5).
- La consola emite la salida correspondiente para cada semana y día.

### **Ejemplo Adicional: Visualización de meses de verano a lo largo de dos años**

**Código con bucles anidados for:**

```javascript
for (let year = 2023; year < 2025; year++) { // Bucle exterior para los años
  console.log(`Año: ${year}`);
  
  for (let month = 6; month < 9; month++) { // Bucle interior para los meses de verano
    console.log(`------${month}`);
  }
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/896b4a58-699c-4400-82a7-5ba92a7974da)

**Explicación:**

- Se utilizan dos bucles `for`, uno para los años (2023 y 2024) y otro para los meses de verano (junio, julio y agosto).
- La consola emite la salida correspondiente para cada año y mes.

### **Simplificación de Nombres de Variables:**

```javascript
for (let i = 2023; i < 2025; i++) {
  console.log(`Año: ${i}`);
  
  for (let j = 6; j < 9; j++) {
    console.log(`------${j}`);
  }
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/8af64c51-20f8-4ebe-befd-df57b5d6d83a)


**Notas:**

- La utilización de nombres cortos como `i` y `j` es una convención común y práctica estándar en desarrollo.

### Funciones en JavaScript 

Se explicará el concepto de funciones en JavaScript y cómo se pueden utilizar para evitar la repetición de código. 

1. **Creación de una función sin parámetros:**

   ```javascript
   // Declaración de la función
   function sumarDosNumeros() {
       // Cuerpo de la función
       var a = 10;
       var b = 20;
       var resultado = a + b;
       console.log(resultado);
   }

   // Llamada a la función
   sumarDosNumeros();
   ```

   Este código crea una función llamada `sumarDosNumeros` que suma dos números fijos (10 y 20) y muestra el resultado en la consola.

2. **Creación de una función con parámetros:**

   ```javascript
   // Declaración de la función con parámetros
   function sumarDosNumerosConParametros(a, b) {
       // Cuerpo de la función utilizando parámetros
       var resultado = a + b;
       console.log(resultado);
   }

   // Llamada a la función con argumentos
   sumarDosNumerosConParametros(10, 20);
   ```

   Este código crea una función llamada `sumarDosNumerosConParametros` que acepta dos parámetros (a y b) y muestra la suma de los valores proporcionados como argumentos al llamar la función.

Estos ejemplos demuestran cómo declarar funciones, utilizar parámetros para hacerlas más flexibles y cómo llamar a funciones con argumentos. Las funciones permiten encapsular bloques de código que pueden ser reutilizados con diferentes valores, lo que hace que el código sea más eficiente y fácil de mantener.

Ya que se tiene mucho más contexto de las funciones, se entiende que las funciones en JavaScript son bloques de código reutilizables que realizan una tarea específica. Proporcionan modularidad al dividir el código en partes más pequeñas y autónomas. A continuación, se detallan algunos aspectos adicionales sobre funciones en JavaScript:

#### Declaración de Funciones

La sintaxis básica para declarar una función es la siguiente:

```javascript
function nombreDeLaFuncion(parametro1, parametro2, ...) {
    // Cuerpo de la función
    // Operaciones y lógica de la función
    return resultado; // Opcional: Devolver un valor
}
```

- `nombreDeLaFuncion`: Es el identificador de la función, un nombre descriptivo que se utiliza para invocar la función.
- `parametro1`, `parametro2`: Son los parámetros que la función espera recibir. Pueden ser utilizados en el cuerpo de la función.
- `return resultado`: Opcionalmente, la función puede devolver un resultado utilizando la palabra clave `return`.

#### Invocación de Funciones

Para ejecutar o invocar una función, se utiliza su nombre seguido de paréntesis que pueden contener argumentos. Los argumentos son valores que se pasan a la función para que los utilice en su lógica interna.

```javascript
nombreDeLaFuncion(valor1, valor2, ...);
```

#### Ámbito de Variables

Las variables declaradas dentro de una función tienen un alcance local. Esto significa que solo son accesibles dentro de esa función. Las variables declaradas fuera de una función tienen un alcance global y son accesibles desde cualquier parte del código.

```javascript
function ejemplo() {
    var variableLocal = "Solo visible dentro de la función";
    console.log(variableLocal);
}

console.log(variableLocal); // Error: variableLocal no definida fuera de la función
```

#### Funciones Anónimas

Una función anónima es una función sin un nombre declarado. Se pueden asignar a variables o pasar como argumentos a otras funciones.

```javascript
var funcionAnonima = function(parametro) {
    // Cuerpo de la función anónima
};

funcionAnonima(valor);
```

#### Funciones Flecha (Arrow Functions)

Las funciones flecha son una forma más concisa de escribir funciones en JavaScript. Tienen una sintaxis más corta y heredan el contexto de `this` del ámbito circundante.

```javascript
const suma = (a, b) => a + b;
console.log(suma(5, 3)); // 8
```

#### Callback Functions

Las funciones pueden ser pasadas como argumentos a otras funciones. Cuando una función se pasa como argumento y se ejecuta más tarde, se llama función de devolución de llamada o callback.

```javascript
function operacionAsync(valor, callback) {
    // Simulación de operación asíncrona
    setTimeout(() => {
        const resultado = valor * 2;
        callback(resultado);
    }, 1000);
}

operacionAsync(5, function(resultado) {
    console.log(resultado); // Se ejecuta cuando la operación asíncrona está completa
});
```

#### Recursividad

Una función puede llamarse a sí misma, lo que se conoce como recursividad. Es útil para resolver problemas que se pueden dividir en subproblemas más pequeños.

```javascript
function factorial(n) {
    if (n <= 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}

console.log(factorial(5)); // 120
```

### Objetos en JavaScript
En JavaScript, los objetos son estructuras de datos que permiten almacenar y organizar información de manera más compleja que las variables simples. Los objetos son fundamentales en la programación orientada a objetos, y ofrecen una forma de agrupar datos y funciones relacionadas en una única entidad.

Un objeto en JavaScript puede contener propiedades y métodos. Las propiedades son pares clave-valor que almacenan datos, mientras que los métodos son funciones asociadas al objeto. Estos elementos permiten modelar entidades del mundo real de manera más cercana, ya que puedes representar características y comportamientos específicos.

La notación de objetos en JavaScript es bastante flexible. Puedes crear objetos de forma literal utilizando llaves `{}`, y luego definir las propiedades y métodos dentro de esas llaves. Además, puedes acceder a las propiedades y métodos de un objeto utilizando la notación de puntos (`objeto.propiedad`) o la notación de corchetes (`objeto['propiedad']`).

Los objetos en JavaScript ofrecen una manera poderosa de estructurar y organizar código, facilitando la creación de programas más modulares y mantenibles. Al comprender cómo trabajar con objetos, los programadores pueden construir aplicaciones más eficientes y expresivas.

#### Literales de objeto y la notación de puntos

Como bien se mencioncó, una de las formas más comunes de construir un objeto en JavaScript es utilizando la sintaxis de literal de objeto: {}.

Para poder acceder a este literal de objeto, es muy común asignarlo a una variable, como:

```javascript
var user = {}; //create an object
```

Ahora se asigna un literal de objeto a la variable user, lo que significa que el objeto al que está ligado puede ampliarse y manipularse de infinidad de formas.

A veces, se puede construir inmediatamente un objeto completo, utilizando la sintaxis del literal de objeto, especificando las propiedades del objeto, delimitadas como pares clave-valor, utilizando la sintaxis que ya se trató en un punto anterior de esta lección.

He aquí uno de esos objetos construidos previamente:

```javascript
//creating an object with properties and their values
var assistantManager = {
    rangeTilesPerTurn: 3,
    socialSkills: 30,
    streetSmarts: 30,
    health: 40,
    specialAbility: "young and ambitious",
    greeting: "Let's make some money"
}
```

Esta sintaxis consta esencialmente de dos pasos: 

1. Declarar una nueva variable y asignarle un literal de objeto - en otras palabras, esto:var assistantManager = {}

2. Asignar los valores a cada una de las claves del objeto, utilizando el operador de asignación, =

Observe que es muy fácil construir cualquier tipo de objeto en JavaScript utilizando esta sintaxis de ejemplo.

Por ejemplo, aquí tiene un objeto table:

```javascript
var table = {
    legs: 3,
    color: "brown",
    priceUSD: 100,
}
```

Para acceder al objeto table, puedo simplemente registrar por consola el objeto completo:  

```javascript
console.log(table);//display the object in the developer console 
```

El valor devuelto es el objetotable completo:  

```javascript
{legs: 3, color: 'brown', priceUSD: 100}
```

Además, puedo registrar por consola cualquier propiedad individual, así:  

```javascript
console.log(table.color); // 'brown'
```

Ahora que tengo esta "receta sintáctica", puedo construir cualquier otro objeto de forma similar: 

```javascript
var house = {
    rooms: 3,
    color: "brown",
    priceUSD: 10000,
}
```

Un enfoque alternativo de la construcción de objetos es guardar primero un literal de objeto vacío en una variable, luego utilizar la notación de puntos para declarar nuevas propiedades sobre la marcha, y utilizar el operador de asignación para añadir valores a esas propiedades; por ejemplo:

```javascript
var house2 = {};
house2.rooms = 4;
house2.color = "pink";
house2.priceUSD = 12345;
```

Además, nada me impide combinar ambos enfoques. Por ejemplo:  

```javascript
console.log(house); // {rooms: 3, color: "brown", priceUSD: 10000}
house.windows = 10;
console.log(house); // {rooms: 3, color: "brown", priceUSD: 10000, windows: 10}
```

Esta flexibilidad significa además que puedo actualizar propiedades ya existentes, no sólo añadir nuevas:  

```javascript
house.windows = 11;
console.log(house); // {rooms: 3, color: "brown", priceUSD: 10000, windows: 11}
```




