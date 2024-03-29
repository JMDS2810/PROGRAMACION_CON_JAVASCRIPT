## Introducción

JavaScript, a menudo denominado el "lenguaje de la web", se ha convertido en un pilar esencial en el mundo del desarrollo de software. Este lenguaje de programación, diseñado para brindar dinamismo e interactividad a las páginas web, ha evolucionado más allá de su función inicial y se ha convertido en una herramienta integral en el desarrollo tanto del front-end como del back-end. Desde la creación de elementos interactivos en páginas web hasta el desarrollo de aplicaciones móviles modernas utilizando tecnologías como React, JavaScript impulsa gran parte de la experiencia en línea que damos por sentado en la vida cotidiana.

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

Para acceder al objeto table, se puede simplemente registrar por consola el objeto completo:  

```javascript
console.log(table);//display the object in the developer console 
```

El valor devuelto es el objetotable completo:  

```javascript
{legs: 3, color: 'brown', priceUSD: 100}
```

Además, se puede registrar por consola cualquier propiedad individual, así:  

```javascript
console.log(table.color); // 'brown'
```

Ahora que se tiene esta "receta sintáctica", se puede construir cualquier otro objeto de forma similar: 

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

#### Literales de objeto y la notación de corchetes

Existe una sintaxis alternativa a la notación de puntos que he utilizado hasta ahora. Esta sintaxis alternativa se conoce comola notación de corchetes.

Para entender cómo funciona, lo mejor es utilizar un ejemplo, así que volverá a pasar por el proceso de codificación del objeto house2, de la misma forma que se hizo con la notación de puntos, sólo que esta vez, se utilizará la notación de corchetes.

```javascript
var house2 = {};
house2["rooms"] = 4;
house2['color']= "pink";
house2["priceUSD"] = 12345;
console.log(house2); // {rooms: 4, color: 'pink', priceUSD: 12345}
```

Debe de tener en cuenta que utilizando la notación de corchetes, esencialmente sólo envuelvo la clave de cada propiedad **como una cadena**, dentro de las comillas simples o dobles - al igual que con las cadenas regulares. 

A continuación, se envuelve toda la clave de la propiedad dentro de un corchete de apertura y otro de cierre.

Se puede tanto acceder como actualizar propiedades en objetos utilizando la notación de puntos, o la notación de corchetes, o una combinación de ambas, como en el siguiente ejemplo:

```javascript
var car = {};
car.color = "red";
car["color"] = "green";
car["speed"] = 200;
car.speed = 100;
console.log(car); // {color: "green", speed: 100}
```

Con la notación de corchetes, también se puede añadir caracteres de espacio dentro de los nombres de las propiedades, de esta manera:  

```javascript
car["number of doors"] = 4;
console.log(car); // {color: 'green', speed: 100, number of doors: 4}
```

Además, se pueden añadir números (como el tipo de datos cadena) como claves de propiedades:  

```javascript
car["2022"] = 1901;
console.log(car); // {2022: 1901, color: 'green', speed: 100, number of doors: 4}
```

Sin embargo, se desaconseja hacer esto, debido a las razones obvias de que tener una clave de propiedad como una cadena de números no transmite realmente mucha información útil. Por último, hay una cosa realmente útil que tiene la notación de corchetes pero que no está disponible en la notación de puntos: Puede evaluar expresiones.

Para entender lo que eso significa, considere el siguiente ejemplo:

```javascript
var arrOfKeys = ['speed', 'altitude', 'color'];
var drone = {
    speed: 100,
    altitude: 200,
    color: "red"
}
for (var i = 0; i < arrOfKeys.length; i++) {
    console.log(drone[arrOfKeys[i]])
}
```

El código anterior dará como resultado la siguiente salida: 

```javascript
100
200
red
```

Utilizando el hecho de que la notación de corchetes puede evaluar expresiones, se puede acceder a la propiedad arrOfKeys[i] del objeto drone. 

Este valor cambió en cada bucle mientras se ejecutaba el bucle for.

Concretamente, la primera vez que se ejecutó, se evaluó así: 

- El valor de i era 0
- El valor de arrOfKeys[i] era arrOfKeys[0], que era "speed"
- Así, drone[arrOfKeys[i]] se evaluó como drone["speed"], que es igual a 100

Esto permitió realizar un bucle sobre cada uno de los valores almacenados dentro del objeto drone, basándose en cada una de las claves de sus propiedades.

#### Matrices

En JavaScript, las matrices son objetos. Eso significa que las matrices también tienen algunas propiedades y métodos incorporados.

Uno de los métodos incorporados más utilizados en las matrices son los métodos push() y pop().

Para añadir nuevos elementos a una matriz, puedo utilizar el método push():

```javascript
var fruits = [];
fruits.push("apple"); // ['apple']
fruits.push('pear'); // ['apple', 'pear']
```

Para eliminar el último elemento de una matriz, puedo utilizar el método pop(): 

```javascript
fruits.pop();
console.log(fruits); // ['apple']
```

Enlazando con algunas lecciones anteriores, ahora se puede construir una función que tome todos sus argumentos y los introduzca en una matriz, así: 

```javascript
function arrayBuilder(one, two, three) {
    var arr = [];
    arr.push(one);
    arr.push(two);
    arr.push(three);
    console.log(arr);
}
```

Ahora puedo llamar a la función arrayBuilder(), por ejemplo, así:  

```javascript
arrayBuilder('apple', 'pear', 'plum'); // ['apple', 'pear', 'plum']
```

Aún mejor, no se tiene que registrar en la consola el array recién construido. En su lugar, se puede devolver de la siguiente manera:

```javascript
function arrayBuilder(one, two, three) {
    var arr = [];
    arr.push(one);
    arr.push(two);
    arr.push(three);
    return arr;
}
```

Además, se puede guardar esta llamada a la función en una variable. Asiminismo, se le puede colocar cualquier nombre, pero esta vez se le pondrá el nombre: simpleArr.

```javascript
var simpleArr = arrayBuilder('apple', 'pear', 'plum');
```

Y ahora se puede registrar en consola los valores almacenados en simpleArr: 

```javascript
console.log(simpleArr); // ['apple','pear','plum']
```

### Objetos numéricos

JavaScript dispone de prácticos objetos incorporados. Uno de estos populares objetos incorporados es el objeto Math.

#### Constantes numéricas

Estas son algunas de las constantes numéricas incorporadas que existen en el objeto Math: 

- **El número PI:** Math.PI que es aproximadamente 3,14159
- **La constante de Euler:** Math.E que es aproximadamente 2.718
- **El logaritmo natural de 2:** Math.LN2 que es aproximadamente 0.693

#### Métodos de redondeo

Estos incluyen: 

- **Math.ceil():** redondea hacia arriba al entero más próximo 
- **Math.floor():** redondea hacia abajo al entero más cercano 
- **Math.round():** redondea hacia arriba al entero más cercano si el decimal es.5 o superior; en caso contrario, redondea hacia abajo al entero más cercano 
- **Math.trunc():** recorta el decimal, dejando sólo el entero

#### Métodos aritméticos y de cálculo

He aquí una lista no exhaustiva de algunos métodos aritméticos y de cálculo comunes que existen en el objetoMath: 

- **Math.pow(2,3):** calcula el número2 a la potencia de3, el resultado es8
- **Math.sqrt(16):** calcula la raíz cuadrada de16, el resultado es4
- **Math.cbrt(8):** halla la raíz cúbica de8, el resultado es2
- **Math.abs(-10):** devuelve el valor absoluto , el resultado es10
- **Métodos logarítmicos:** Math.log(), Math.log2(), Math.log10()
- Devuelven los valores mínimo y máximo de todas las entradas: Math.min(9,8,7) devuelve 7, Math.max(9,8,7) devuelve 9.
- **Métodos trigonométricos:** Math.sin(),Math.cos(),Math.tan(), etc.

Ya indicados los Objetos Numéricos, ahora se abordaránn dos métodos útiles del objeto `Math` en JavaScript: `random` y `ceil`. Estos métodos proporcionan herramientas valiosas para generar números aleatorios y redondear valores decimales.

Primero, se explora el método `random`, el cual genera un número decimal aleatorio en el rango de 0 a 0.99. Para utilizarlo, se sugiere asignar el resultado del método a una variable. A continuación, se muestra cómo ampliar el rango para obtener números mayores multiplicando el resultado por 10.

```javascript
// Utilizando el método random de Math
var decimal = Math.random();
console.log(decimal);

// Ampliando el rango multiplicando por 10
var ampliado = decimal * 10;
console.log(ampliado);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/c3fdcf10-cec3-4c9e-b324-e977ee042425)

Luego, se introduce el método `ceil`, que redondea un número decimal al entero más cercano. Se demuestra que este método siempre redondea hacia arriba y se ilustra con varios ejemplos.

```javascript
// Utilizando el método ceil de Math
var rounded = Math.ceil(0.0001);
console.log(rounded); // Salida: 1

// Confirmación del comportamiento
console.log(Math.ceil(0.5)); // Salida: 1
console.log(Math.ceil(0.99)); // Salida: 1

// Ejemplos con números más grandes
console.log(Math.ceil(1.01)); // Salida: 2
console.log(Math.ceil(1.5)); // Salida: 2
console.log(Math.ceil(2.99)); // Salida: 3
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/b117808a-7da1-4639-8358-e3acbbdbf587)

Finalmente, se combina el método `random` con `ceil` para generar un entero aleatorio entre 0 y 10. Esto se logra multiplicando el resultado de `random` por 10 y redondeándolo hacia arriba.

```javascript
// Generando un entero aleatorio entre 0 y 10
var decimal = Math.random() * 10;
var rounded = Math.ceil(decimal);
console.log(rounded);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/eb1a5f51-c1e4-45ed-a7b6-93d6e1cbd076)

Este código devuelve un entero aleatorio entre 0 y 10 en la consola cada vez que se ejecuta.

En este fragmento, se aborda el concepto de iterable en JavaScript y se explora la iteración sobre matrices y cadenas. Además, se presenta la manipulación de cadenas, haciendo hincapié en que, aunque las cadenas comparten algunas similitudes con las matrices, no son exactamente lo mismo.

En JavaScript, un iterable se define como cualquier tipo de datos que puede ser recorrido utilizando algún tipo de bucle. Se destaca que tanto las matrices como las cadenas son ejemplos de datos sobre los cuales se puede iterar.

En el ejemplo de las matrices, se utiliza una matriz llamada `veggies` que contiene nombres de verduras. Se muestra la longitud de la matriz y se accede a elementos individuales mediante índices. Luego, se utiliza un bucle for para recorrer y mostrar cada elemento de la matriz.

```javascript
var veggies = ['cebolla', 'perejil', 'zanahoria'];

console.log(veggies.length); // Salida: 3
console.log(veggies[0]); // Salida: cebolla
console.log(veggies[1]); // Salida: perejil

for (var i = 0; i < veggies.length; i++) {
  console.log(veggies[i]);
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/b3155a1c-860e-4f7d-a9aa-ed913797f2d2)

Se enfatiza que aunque las cadenas se comportan de manera similar a las matrices en la iteración, no son matrices en sí mismas. Se muestra un ejemplo de iteración sobre una cadena llamada `greeting` y se utiliza un bucle for para acceder a sus caracteres.

```javascript
var greeting = 'howdy';

console.log(greeting.length); // Salida: 5
console.log(greeting[0]); // Salida: h
console.log(greeting[1]); // Salida: o

for (var i = 0; i < greeting.length; i++) {
  console.log(greeting[i]);
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/3fbccefc-c10f-482e-9308-1bb9f80c32a4)

Luego, se demuestra que no se pueden utilizar todos los métodos de matriz en cadenas. Por ejemplo, intentar ejecutar el método `pop` en una cadena resulta en un error. Sin embargo, se presenta el uso del operador de concatenación (`+`) y el método `concat` para unir cadenas.

```javascript
var greet = 'hello';
var user = 'Lisa';

// Esto genera un error, ya que pop no es una función válida en cadenas
// console.log(greet.pop());

// Concatenación de cadenas con el operador +
console.log(greet + user); // Salida: helloLisa

// Uso del método concat para unir cadenas
console.log(greet.concat(user)); // Salida: helloLisa
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/5501d2c4-ec35-40aa-973c-0674e3b44601)

### Typeof

El operador `typeof` en JavaScript es utilizado para identificar el tipo de datos de un elemento. Acepta un parámetro y devuelve el nombre del tipo de datos representado como una cadena. Para un mejor entendimiento, se tiene el siguiente código:

```javascript
// Creación de varias instancias de la variable test
var test1 = "Hola";         // Una cadena
var test2 = 42;             // Un número entero
var test3 = 3.14;           // Un número decimal
var test4 = true;           // Un valor booleano verdadero
var test5 = false;          // Un valor booleano falso
var test6 = 1 < 2;          // Una comparación que evalúa a verdadero (true)
var test7 = [1, 2, 3];      // Un array
var test8 = function() {};  // Una función

// Uso del método log de la consola para dar salida al valor de la variable test
console.log(typeof test1);  // Salida: string
console.log(typeof test2);  // Salida: number
console.log(typeof test3);  // Salida: number
console.log(typeof test4);  // Salida: boolean
console.log(typeof test5);  // Salida: boolean
console.log(typeof test6);  // Salida: boolean
console.log(typeof test7);  // Salida: object (los arrays son objetos en JavaScript)
console.log(typeof test8);  // Salida: function
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/5d5f6e24-5e3f-411f-a6f4-1bd414f7b00d)

Explicación:

- Se crean instancias de la variable `test` con diferentes tipos de datos.
- Se utiliza `typeof` junto con `console.log` para imprimir el tipo de cada variable.
- Se observa que para arrays y funciones, el resultado es "object" y "function", respectivamente.

El operador `typeof` es útil para verificar el tipo de datos de una variable antes de realizar operaciones específicas para ese tipo, y se puede utilizar para lidiar con situaciones donde se espera un tipo de datos particular.

### Fallos y errores 

Un fallo hace que el código se comporte de manera inesperada pero siga ejecutándose, mientras que un error detiene la ejecución del código. Se puede poner de ejemplo a una función suma dos números y que genera el resultado, pero al pasar una cadena y un número, debido a la coerción de JavaScript, se produce una concatenación en lugar de una suma, y el programa sigue ejecutándose.

Luego, se tiene un escenario donde se intenta usar variables (`c` y `d`) que no han sido declaradas ni asignadas, lo que lleva a un error de referencia. Este tipo de error ocurre cuando intentas usar un valor que no está definido en el código.

Se destaca que JavaScript envía mensajes de error a la consola para informar sobre errores, lo que ayuda a identificar problemas en el código. Se tienen otros tipos de errores comunes, como errores de sintaxis y errores de tipo. Un error de sintaxis ocurre cuando se escribe un fragmento de código que JavaScript no puede leer, como olvidar un símbolo de comillas finales. Un error de tipo ocurre cuando intentas realizar una operación no válida en un tipo de dato, como ejecutar el método `pop` en un número.

En resumen, la importancia radica en comprender los fallos y errores en JavaScript, además de identificar algunos errores comunes y destaca la utilidad de los mensajes de error de JavaScript para diagnosticar problemas en el código.

#### Bloques de captura

Se verá el uso de las sentencias `try`, `catch`, y `throw` en JavaScript para manejar errores y evitar que el programa se detenga abruptamente. A continuación, se proporcionan ejemplos de códigos en JavaScript que ilustran estos conceptos:

1. **Ejemplo de uso de `try` y `catch`:**

   ```javascript
   try {
     // Bloque de código que puede lanzar un error
     console.log(a + b);
   } catch (err) {
     // Bloque catch que maneja el error
     console.error("Hubo un error:", err);
   } finally {
     // Bloque opcional de código que se ejecuta siempre, ocurra o no un error
     console.log("Mi programa no se detiene");
   }
   ```

En este ejemplo, el bloque `try` contiene una operación (`console.log(a + b)`) que puede arrojar un error si las variables `a` y `b` no están definidas. Si ocurre un error, el bloque `catch` captura el error, lo almacena en una variable llamada `err` y ejecuta un bloque de código para manejar el error. El bloque `finally` es opcional y se ejecutará independientemente de si se lanzó un error o no.

2. **Ejemplo de uso de `throw`:**

   ```javascript
   try {
     // Bloque de código que puede lanzar un error
     throw new Error("Hubo un error de referencia");
   } catch (err) {
     // Bloque catch que maneja el error
     console.error("Error:", err.message);
   } finally {
     // Bloque opcional de código que se ejecuta siempre, ocurra o no un error
     console.log("Mi programa no se detiene");
   }
   ```

En este ejemplo, el bloque `try` contiene la palabra clave `throw`, que se utiliza para lanzar manualmente un error. El bloque `catch` captura el error, lo almacena en una variable llamada `err` y maneja el error. El bloque `finally` es opcional y se ejecutará independientemente de si se lanzó un error o no.

#### Errores de sintaxis, lógicos y de ejecución

##### ReferenceError

Un ReferenceError se lanza cuando, por ejemplo, se intenta utilizar variables que no han sido declaradas en ninguna parte.

Un ejemplo puede ser intentar registrar en la consola una variable que no existe:

```javascript
console.log(username);
```

Si la variable llamada username no ha sido declarada, la línea de código anterior dará como resultado la siguiente salida:

```javascript
Uncaught ReferenceError: username is not defined
```

##### SyntaxError

Cualquier tipo de código JavaScript no válido provocará un SyntaxError.

Por ejemplo:

``` javascript
var a "there's no assignment operator here";
```

La línea de código anterior arrojará el siguiente error:  

```javascript
Uncaught SyntaxError: Unexpected string
```

Hay una advertencia interesante con respecto al SyntaxError en JavaScript: no se puede atrapar utilizando el bloque try-catch.  

##### TypeError

Un TypeError se lanza cuando, por ejemplo, se intenta ejecutar un método en un tipo de datos no soportado.

Un ejemplo sencillo es intentar ejecutar el métodopop() sobre una cadena:

``` javascript
"hello".pop() // Uncaught TypeError: "hello".pop is not a function
```

El comportamiento tipo array de las cadenas ya se trató en una lección anterior de este curso. 

Sin embargo, como se puede confirmar ejecutando la línea de código anterior, las cadenas no tienen todos los métodos de array a su disposición, e intentar utilizar algunos de esos métodos provocará que se lance un TypeError.  

##### RangeError

Un RangeError se lanza cuando estamos dando un valor a una función, pero ese valor está fuera del rango permitido de valores de entrada aceptables.

He aquí un ejemplo sencillo de conversión de un número cotidiano de Base 10 (un número del sistema decimal común) a un número de Base 2 (es decir, un número binario).

Por ejemplo

```javascript
(10).toString(2); // '1010'
```

El valor de 2 cuando se pasa al métodoto String(), es como decirle a JavaScript: "convierta el valor de10 del sistema numérico de Base 10, a su homólogo en el sistema numérico de Base 2".

JavaScript obliga y "traduce" el número "normal" 10 a su contraparte binaria.

Además de utilizar el sistema numérico de Base 2, también se puede utilizar el de Base 8, de esta forma:

```javascript
(10).toString(8); // 12
```

Obtengo de vuelta el valor 12, que es el número normal 10, escrito en el sistema numérico de Base 8.

Sin embargo, si se intenta utilizar un sistema numérico inexistente, como un imaginario Base 100, ya que este sistema numérico efectivamente no existe en JavaScript, obtendré el RangeError, porque un sistema Base100 inexistente está fuera del rango de los sistemas numéricos que están disponibles para el método toString():

```javascript
(10).toString(100); // Uncaught RangeError: toString() radix argument must be between 2 and 36
```

#### Valores indefinidos, nulos y vacíos

El texto menciona tres tipos de valores vacíos en JavaScript: `null`, `undefined`, y cadenas vacías. A continuación, se proporcionan ejemplos de códigos en JavaScript para ilustrar estos conceptos:

1. **Ejemplo de `null`:**

   ```javascript
   // Ejemplo de uso de null
   let letters = "abc";
   
   // Buscar la letra 'a' en la cadena
   let resultA = letters.match(/a/);
   console.log(resultA); // Devuelve una matriz con información sobre la coincidencia
   
   // Buscar la letra 'd' en la cadena
   let resultD = letters.match(/d/);
   console.log(resultD); // Devuelve null, indicando que no se encontró la letra 'd'
   ```

   En este ejemplo, la función `match` busca la presencia de ciertas letras en la variable `letters`. Cuando no encuentra la letra 'd', devuelve `null` para indicar la ausencia de un objeto.

2. **Ejemplo de `undefined`:**

   ```javascript
   // Ejemplo de uso de undefined
   let name;
   
   // Intentar imprimir el valor de una variable no asignada
   console.log(name); // Devuelve undefined, ya que la variable existe pero no tiene valor asignado
   
   // Asignar un valor a la variable después de su declaración
   name = "John";
   console.log(name); // Imprime "John"
   ```

   En este ejemplo, la variable `name` se declara pero no se le asigna un valor inicial, por lo que su valor es `undefined`. Después, se le asigna el valor "John".

3. **Ejemplo de cadena vacía:**

   ```javascript
   // Ejemplo de uso de cadena vacía
   let emptyString1 = '';
   let emptyString2 = "";
   
   console.log(emptyString1); // Imprime una cadena vacía
   console.log(emptyString2); // Imprime una cadena vacía
   ```

   En este ejemplo, se crean dos variables, `emptyString1` y `emptyString2`, que contienen cadenas vacías. Ambas variables se imprimen y muestran como cadenas vacías.

### Programación funcional

La programación funcional se caracteriza por su enfoque en la clara separación entre datos y funciones, permitiendo que los datos existan fuera de las funciones. A continuación, se presenta un ejemplo práctico de programación funcional mediante la creación de un programa para la conversión de divisas.

```javascript
// Declaración de variables
var currencyOne = 100;
var currencyTwo = 0;
var exchangeRate = 1.2;

// Función de conversión de divisas
function convertirDivisa(amount, rate) {
  return amount * rate;
}

// Actualización de currencyTwo usando la función
currencyTwo = convertirDivisa(currencyOne, exchangeRate);

// Registro en la consola para probar el código
console.log(currencyTwo); // Salida: 120
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/3e7b3b9c-ccdb-4fdb-bcff-c064fa92c946)

En el código de ejemplo, se declaran variables como currencyOne, currencyTwo, y exchangeRate, a las cuales se les asignan valores. La función convertirDivisa(amount, rate) se introduce para realizar la conversión, devolviendo el resultado de la multiplicación de amount por rate. La actualización de la variable currencyTwo se realiza llamando a esta función con los argumentos apropiados.

Finalmente, se prueba el código registrando el valor actualizado de currencyTwo en la consola. Este ejemplo práctico ilustra cómo la programación funcional puede abordar un problema al separar claramente los datos y las funciones.

### Llamada a funciones y recursividad

A continuación, se mostrará un ejemplo para poder entender este punto. Se crea una función llamada "example" con varias líneas de registro de puntos en la consola. Se demuestra cómo, al agregar una línea que llama a la función dentro de sí misma, se crea un bucle infinito.

Para evitar que la función se ejecute sin parar, se mejora el código introduciendo una condición de parada. En este caso, se agrega un contador y una estructura "if" que verifica si el contador llega a cero, deteniendo así la recursión. Este ejemplo práctico ilustra el concepto de recursión, que es una forma alternativa de ejecutar código repetitivo sin el uso de bucles.

```javascript
// Definición de la función recursiva llamada "example"
function example(counter) {
  // Imprimir el valor del contador en la consola
  console.log(counter);

  // Verificar si el contador llega a cero para detener la recursión
  if (counter > 0) {
    // Llamada recursiva reduciendo el contador en 1 en cada iteración
    example(counter - 1);
  } else {
    // Si el contador llega a cero, detener la recursión
    return;
  }
}

// Llamar a la función "example" con un valor inicial para el contador (por ejemplo, 3)
example(3);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/ab35af87-3c70-4460-a3a2-9542ab44fa4f)

En este ejemplo, la función countDown toma un parámetro llamado counter que representa el número desde el cual comenzará a contar. La función imprime el valor actual del contador en la consola, luego se llama a sí misma con un contador reducido en 1 en cada iteración. La recursión se detiene cuando el contador llega a cero, momento en el cual se imprime un mensaje indicando que la recursión ha terminado.

### Ámbito con var, let y const

En JavaScript, el ámbito determina la accesibilidad del código, definiendo qué partes del programa pueden acceder a ciertas variables. Existen dos tipos de ámbito: global y local. El ámbito local se aplica a variables declaradas dentro de funciones, mientras que el ámbito global abarca todo el código fuera de las funciones.

En la versión ES5 de JavaScript, solo las funciones podían crear un ámbito local. Con la introducción de ES6, se añadió un nuevo ámbito conocido como ámbito de bloques, el cual establece que las variables declaradas con `let` o `const` solo son accesibles dentro del bloque de código donde se crean.

La palabra clave `var` es menos estricta que `let` y `const`, ya que permite el uso de la variable antes de declararla y permite la redeclaración de la misma variable. Además, las variables declaradas con `var` tienen un ámbito de función si se declaran fuera de funciones, siendo globales.

En contraste, `let` y `const` son más estrictas. No permiten el uso de la variable antes de declararla y no permiten su redeclaración. Además, el alcance de las variables declaradas con `let` o `const` está limitado al bloque donde se crean, incluso dentro de instrucciones `if` y bucles. La recomendación es utilizar `let` si el valor de la variable puede cambiar y `const` si el valor es constante. 

### Comparación de var, let y const

#### Variables con `var`

```javascript
// Ejemplo con la palabra clave var
console.log(user); // Error: user is not defined

var user = "Mark";
console.log(user); // Salida: Mark

// Reasignación y redeclaración permitidas
var user = "Mary";
var user = "Joanna";
var user = "Mark";
console.log(user); // Salida: Mark
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/bacc0862-9614-4120-97e3-823d33c1a2e0)

**Explicación:**
- Se muestra que una variable `var` puede ser accedida antes de su declaración, devolviendo `undefined`.
- Se resalta que la reasignación y redeclaración de la misma variable con `var` no generan errores.

### Variables con `let`:
```javascript
// Ejemplo con la palabra clave let
// console.log(user); // Error: Cannot access 'user' before initialization

let user;
console.log(user); // Salida: undefined

user = "Anna";
// let user; // Error: Identifier 'user' has already been declared
console.log(user); // Salida: Anna
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/97d4e860-755c-487c-82c6-432f1b3f6f50)

**Explicación:**
- Se muestra que no se puede acceder a una variable `let` antes de su declaración.
- Se destaca que, a diferencia de `var`, no se puede volver a declarar una variable `let`, pero sí se puede reasignar.

### Variables con `const`:
```javascript
// Ejemplo con la palabra clave const
// console.log(userConst); // Error: Cannot access 'userConst' before initialization

const userConst = undefined;
// const userConst = "Anna"; // Error: Missing initializer in const declaration
console.log(userConst); // Salida: undefined

// const userConst = "Anna"; // Error: Identifier 'userConst' has already been declared
console.log(userConst); // Salida: undefined

```

**Explicación:**
- Se demuestra que una variable const debe ser inicializada en el momento de la declaración, y se muestra un error si no se proporciona un valor.
- Se destaca que una vez que una variable const es declarada e inicializada, no puede ser reasignada ni redeclarada.
  
![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/8e712d31-4f74-41d4-b7da-e0a77d04a910)

Se aconseja elegir `let` o `const` en función de si se reasignarán o no los valores, indicando que `var` es más indulgente, mientras que `const` es más estricta.

### Programación Orientada a Objetos (POO)

#### Programación Orientada a Objetos (POO) - JavaScript

En programación, existen paradigmas que representan estilos o formas de escribir código. Uno de estos paradigmas es la Programación Orientada a Objetos (POO), que organiza programas mediante objetos que agrupan datos y funcionalidades. A continuación se tiene un ejemplo práctico para poder explorar cómo funciona esto, utilizando un ejemplo de cálculo del costo total de comprar un par de zapatos.

1. **Definición del Objeto `purchase1`:**
   ```javascript
   let purchase1 = {
     shoesPrice: 100,
     taxRate: 1.2,
     totalPrice: function () {
       return this.shoesPrice * this.taxRate;
     },
   };
   ```

   En este código, creamos un objeto `purchase1` que tiene propiedades como `shoesPrice` y `taxRate`. Además, tiene un método `totalPrice` que calcula el costo total multiplicando el precio de los zapatos por el impuesto.

2. **Acceso y Uso del Método `totalPrice`:**
   ```javascript
   console.log(purchase1.totalPrice()); // Output: 120
   ```

   Aquí accedemos al método `totalPrice` del objeto `purchase1` para obtener el resultado del cálculo, que es 120.

3. **Uso de la Palabra Clave `this` para Reutilización:**
   ```javascript
   let purchase2 = {
     shoesPrice: 50,
     taxRate: 1.2,
     totalPrice: purchase1.totalPrice,
   };

   console.log(purchase2.totalPrice()); // Output: 60
   ```
   
![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/7421139f-d8fb-4670-a8fc-5f320ad85b7c)

   En este fragmento, creamos otro objeto `purchase2`, y al asignarle el método `totalPrice` de `purchase1`, estamos reutilizando el mismo método. La palabra clave `this` se utiliza para referirse al objeto actual, permitiendo la reutilización eficiente del código.

#### Programación Funcional - JavaScript

En contraste con POO, la Programación Funcional mantiene separados los datos de las funciones. Veamos cómo realizar el mismo cálculo utilizando un enfoque funcional.

```javascript
// Programación Funcional para el cálculo del costo total
function calculateTotalPrice(shoesPrice, taxRate) {
  return shoesPrice * taxRate;
}

let shoesPrice = 100;
let taxRate = 1.2;
let totalPrice = calculateTotalPrice(shoesPrice, taxRate);

console.log(totalPrice); // Output: 120
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/95af9e55-e279-45c4-9be4-b1a8aadf915b)

En este ejemplo, creamos una función `calculateTotalPrice` que toma los valores de `shoesPrice` y `taxRate` como argumentos y devuelve el resultado del cálculo. Luego, llamamos a esta función con valores específicos para obtener el mismo resultado, que es 120.

#### Programación Orientada a Objetos (POO) - Clases en JavaScript

En programación, cuando necesitas construir múltiples objetos con un conjunto específico de propiedades y métodos, las clases son una herramienta eficiente. En JavaScript, las clases se definen con la palabra clave `class`, seguida del nombre de la clase con mayúscula y un bloque de código. Aquí se utiliza una función constructora dentro de la clase para asignar parámetros a las propiedades de los objetos que se crearán a partir de la clase. Además, se pueden agregar métodos a la clase sin utilizar la palabra clave `function`, solo especificando el nombre del método.

**Ejemplo de Clase en JavaScript:**
```javascript
class Car {
  constructor(make, model, year) {
    this.make = make;
    this.model = model;
    this.year = year;
    this.turbo = false;
  }

  turboOn() {
    this.turbo = true;
    console.log("Turbo activated!");
  }
}

// Instanciación de la clase Car
let carOne = new Car("Toyota", "Camry", 2022);

// Acceso a métodos y propiedades
carOne.turboOn(); // Activación del turbo
console.log(carOne.make); // Salida: Toyota
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/4866349f-adea-451a-aa5d-9fe5f58a8715)

En este ejemplo, se crea la clase `Car` con un constructor que inicializa propiedades como `make`, `model`, `year`, y una propiedad adicional `turbo` que se establece en `false`. Se agrega un método `turboOn` para activar el turbo y se instancia la clase creando un objeto `carOne`. Los métodos y propiedades de la clase se acceden a través de este objeto.

#### Principios fundamentales de la Programación Orientada a Objetos (POO)

La Programación Orientada a Objetos (POO) es un paradigma que se basa en cuatro principios fundamentales: herencia, encapsulación, abstracción y polimorfismo. Estos principios proporcionan un marco sólido para el diseño de software, mejorando la modularidad, la reutilización de código y la organización de sistemas complejos.

1. **Herencia:**
   La herencia en JavaScript se logra mediante la palabra clave `extends`. Una clase hija hereda propiedades y métodos de la clase padre.

   **Ejemplo en JavaScript:**
   ```javascript
   class Animal {
       constructor(name) {
           this.name = name;
       }

       speak() {
           console.log(`${this.name} makes a sound`);
       }
   }

   class Dog extends Animal {
       speak() {
           console.log(`${this.name} barks`);
       }
   }

   const myDog = new Dog('Buddy');
   myDog.speak();  // Salida: "Buddy barks"
   ```
   
![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e8f2686e-fcc4-48d1-95f9-d02729daf65e)

2. **Encapsulación:**
   JavaScript no tiene modificadores de acceso, pero se puede lograr cierto nivel de encapsulación utilizando funciones de cierre (closures).

   **Ejemplo en JavaScript:**
   ```javascript
   function BankAccount() {
       let balance = 0;

       return {
           deposit: function(amount) {
               balance += amount;
           },
           getBalance: function() {
               return balance;
           }
       };
   }

   const myAccount = BankAccount();
   myAccount.deposit(100);
   console.log(myAccount.getBalance());  // Salida: 100
   ```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/b65c8d4b-6ba9-4b02-b7b1-bfc2319e29f9)

3. **Abstracción:**
   En JavaScript, la abstracción se logra al definir clases e interfaces que representan conceptos generales.

   **Ejemplo en JavaScript:**
   ```javascript
   // Abstracción a través de una interfaz
   class Shape {
       area() {
           throw new Error("Método 'area' debe ser implementado");
       }
   }

   class Circle extends Shape {
       constructor(radius) {
           super();
           this.radius = radius;
       }

       area() {
           return Math.PI * this.radius ** 2;
       }
   }

   const myCircle = new Circle(5);
   console.log(myCircle.area());  // Salida: 78.54
   ```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/ef9bb5d0-d961-418b-b53e-5e39108b06c6)

4. **Polimorfismo:**
   En JavaScript, el polimorfismo se logra a través de la capacidad de los objetos de responder a métodos de manera dinámica.

   **Ejemplo en JavaScript:**
   ```javascript
   class Animal {
       sound() {
           console.log("Animal makes a sound");
       }
   }

   class Dog extends Animal {
       sound() {
           console.log("Dog barks");
       }
   }

   const myAnimal = new Dog();
   myAnimal.sound();  // Salida: "Dog barks"
   ```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/c4f46734-0b4b-4de5-8bb0-f5008d14459a)

   Aquí, el mismo método `sound()` produce resultados diferentes según el objeto con el que se llama.

#### Constructores en JavaScript

Los constructores en JavaScript son funciones especiales utilizadas para crear e inicializar objetos. Estos se invocan usando la palabra clave `new` y son útiles para crear múltiples instancias de un objeto con propiedades y métodos específicos. Aquí hay una explicación detallada junto con ejemplos de código:

En la programación orientada a objetos (POO) de JavaScript, los constructores son funciones especiales que se utilizan para crear e inicializar objetos. Estas funciones actúan como plantillas para la creación de instancias de objetos y suelen comenzar con una letra mayúscula por convención. Vamos a definir los constructores y proporcionar ejemplos de código para ilustrar su uso:

**Ejemplos de Código:**

1. **Constructor Básico:**
   
```javascript
// Definir un constructor
function Persona(nombre, edad) {
    this.nombre = nombre;
    this.edad = edad;
}

// Crear una instancia utilizando el constructor
const persona1 = new Persona('Juan', 30);

// Acceder a las propiedades del objeto
console.log(persona1.nombre);  // Salida: "Juan"
console.log(persona1.edad);    // Salida: 30
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/33424864-6c12-40ac-9c7b-ac1d1137b79c)

2. **Métodos en el Constructor:**

```javascript
function Coche(marca, modelo) {
    this.marca = marca;
    this.modelo = modelo;

    this.mostrarDetalles = function() {
        console.log(`Marca: ${this.marca}, Modelo: ${this.modelo}`);
    };
}

const coche1 = new Coche('Toyota', 'Corolla');
coche1.mostrarDetalles();  // Salida: "Marca: Toyota, Modelo: Corolla"
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e7d17b5f-25cf-4b8d-bd7f-9876ee49693e)

3. **Uso de Prototipos:**
   
```javascript
function Libro(titulo, autor) {
    this.titulo = titulo;
    this.autor = autor;
}

// Agregar un método utilizando el prototipo
Libro.prototype.mostrarInfo = function() {
    console.log(`${this.titulo} por ${this.autor}`);
};

const libro1 = new Libro('Harry Potter', 'J.K. Rowling');
libro1.mostrarInfo();  // Salida: "Harry Potter por J.K. Rowling"
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e4d3c285-88e2-4670-b783-d1538f31cff9)

4. **Uso de Clases (ES6 y posteriores):**

```javascript
class Pelicula {
    constructor(titulo, director) {
        this.titulo = titulo;
        this.director = director;
    }

    reproducir() {
        console.log(`Reproduciendo: ${this.titulo} dirigida por ${this.director}`);
    }
}

const pelicula1 = new Pelicula('Inception', 'Christopher Nolan');
pelicula1.reproducir();  // Salida: "Reproduciendo: Inception dirigida por Christopher Nolan"
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e237432a-03ad-4a22-a3b0-4e17d8332676)

Estos ejemplos muestran diferentes formas de utilizar constructores en JavaScript para crear objetos con propiedades y métodos específicos. Los constructores son fundamentales en la programación orientada a objetos, ya que permiten la creación de instancias de objetos con una estructura predefinida.

#### Herencia

Para entender este principio, se define al prototipo, el cual es un objeto que puede contener propiedades compartidas por varios otros objetos, y este principio forma la base de la herencia en JavaScript.

A continuación, se presenta un ejemplo de código que demuestra la creación de objetos utilizando un prototipo. Se define un objeto "pájaro" con propiedades como "tiene alas", "puede volar" y "tiene plumas". A través de la función `Object.create`, se crean instancias como "águila1" y "pingüino1" con el prototipo del objeto "pájaro".

Se enfatiza la capacidad de los objetos instanciados de acceder a las propiedades del prototipo. Se muestra cómo anular propiedades específicas en un objeto concreto sin afectar a otros objetos que comparten el mismo prototipo.

Finalmente, se sugiere que, aunque es posible crear herencia con el método de creación de objetos, en casos más complejos, la sintaxis de clase es preferible. Esta sintaxis de clase sigue operando con prototipos, pero mejora la experiencia del desarrollador en situaciones más elaboradas.

```javascript
// Definición del objeto pájaro como prototipo
const bird = {
    hasWings: true,
    canFly: true,
    hasFeathers: true,
};

// Creación de objetos instanciados con el prototipo
const eagle1 = Object.create(bird);
console.log("Eagle1 has wings:", eagle1.hasWings); // Salida: true

const penguin1 = Object.create(bird);
penguin1.canFly = false;
console.log("Penguin1 can fly:", penguin1.canFly); // Salida: false
console.log("Penguin1 has feathers:", penguin1.hasFeathers); // Salida: true
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/7a26382c-3a37-4ba9-b52c-dbbf96c1f6b0)

Este código refleja la creación de objetos ("águila1" y "pingüino1") utilizando un prototipo común ("pájaro"). Se destaca la capacidad de anular la propiedad `canFly` en el objeto "pingüino1" sin afectar al prototipo o a otros objetos.

### Funciones avanzadas en JavaScript

#### Desestructuración de matrices y objetos

Para poder entender, se presenta un ejemplo práctico utilizando un objeto matemático incorporado en JavaScript. Se utiliza la palabra clave `let` y la sintaxis de desestructuración `{}` para crear una copia independiente de la propiedad `PI` del objeto matemático, almacenándola en una nueva variable llamada `pie`.

Se destaca que intentar desestructurar una propiedad que no existe resultará en un valor indefinido. Además, se enfatiza que las variables desestructuradas son completamente independientes de las propiedades originales, demostrado mediante la comparación de valores y tipos de datos utilizando el operador de comparación estricta `===`.

En el ejemplo, se modifica el valor de la variable `pie` y se muestra que ya no es igual a la propiedad original `PI`, lo que confirma la independencia de ambas.

Con todo lo mencionado, se concluye que la desestructuración en JavaScript crea variables independientes sin conexión con las propiedades originales de los objetos.

```javascript
// Ejemplo de desestructuración de la propiedad PI de un objeto matemático
let { PI: pie } = Math; // Creación de una variable independiente "pie"

// Intentar desestructurar una propiedad que no existe resultará en un valor indefinido
let { pi: piMinusc } = Math; // Esto devuelve undefined

// Confirmar la independencia comparando valores y tipos de datos
console.log(pie === Math.PI); // Devuelve false

// Modificar el valor de la variable "pie"
pie = 1;

// Volver a comparar para demostrar la independencia
console.log(pie === Math.PI); // Devuelve false
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/ffeb217f-2891-4a8e-aebc-55f098af4ca0)

Este código ejemplifica el proceso de desestructuración de la propiedad `PI` del objeto matemático y cómo la variable resultante es independiente de la propiedad original.

#### For de bucles y objetos

Para poder ver las diferencias entre los bucles `for...in` y `for...of` aplicados a objetos en JavaScript se proporciona un código que utiliza un objeto "coche" y su derivado "coche deportivo" para ilustrar las particularidades de estos bucles.

El código comienza creando un objeto "coche" con propiedades como motor, dirección y velocidad. Luego, se crea un "coche deportivo" utilizando `Object.create()` para heredar las propiedades del "coche" y se le asigna una propiedad de velocidad rápida.

Se presentan dos bucles `for`: el primero utiliza `for...in` para iterar sobre las propiedades del "coche deportivo" y el segundo utiliza `for...of` para iterar sobre las propiedades propias del "coche deportivo".

El bucle `for...in` es señalado como poco fiable porque también itera sobre las propiedades del prototipo del objeto, no solo sobre las propias. Esto se ilustra al iterar sobre el "coche deportivo" y obtener propiedades del prototipo, como motor y dirección, además de la velocidad propia del "coche deportivo".

En cambio, el bucle `for...of` se considera fiable ya que solo itera sobre las propiedades propias del objeto. En este caso, al iterar sobre el "coche deportivo", solo se obtiene la velocidad propia, como se espera.

Se presenta una versión simplificada del código con comentarios eliminados y se ejecuta, confirmando la diferencia en la salida entre ambos bucles. El bucle `for...in` muestra propiedades del prototipo, mientras que el bucle `for...of` muestra solo propiedades propias.

```javascript
// Creación de un objeto "coche" con propiedades
let coche = { motor: true, direccion: true, velocidad: 'lento' };

// Creación de un "coche deportivo" heredando propiedades de "coche"
let cocheDeportivo = Object.create(coche);
cocheDeportivo.velocidad = 'rápida';

// Bucle for...in para iterar sobre propiedades del "coche deportivo"
for (let prop in cocheDeportivo) {
    console.log(prop); // Itera sobre propiedades propias y del prototipo
}

// Bucle for...of para iterar sobre propiedades propias del "coche deportivo"
for (let prop of Object.keys(cocheDeportivo)) {
    console.log(prop); // Itera solo sobre propiedades propias
}
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e90b26c5-e715-422a-b216-6cf7f267e9d3)

Este código ejemplifica la creación de objetos, herencia de propiedades y la diferencia en la iteración de propiedades utilizando `for...in` y `for...of`.

Para tener un mayor entendimiento, se presenta otro código similar al anterior.

```javascript
const car = {
    engine: true,
    steerign: true,
    speed: "slow"
}
const sportsCar = Object.create(car);
sportsCar.speed = "fast";
console.log("The sportsCar Object: ", sportsCar);

console.log('----- for-in is unreliable -----');
for(prop in sportsCar){
    console.log(prop);
}
console.log('🧐', "Iterating over object AND its prototype!");

console.log('----- for-of is reliable -----');
for(prop of Object.keys(sportsCar)){
    console.log(prop + ":" + sportsCar[prop]);
}
console.log('🎯', "Iterating over object's OWN PROPERTIES only!");
```

**Explicación**

El código crea dos objetos en JavaScript: un objeto básico llamado `car` y un objeto derivado llamado `sportsCar`. Luego, utiliza bucles `for...in` y `for...of` para iterar sobre las propiedades de `sportsCar` y muestra la diferencia en la salida.

1. **Definición de Objetos:**
   ```javascript
   const car = {
       engine: true,
       steering: true,
       speed: "slow"
   }
   ```
   Se define un objeto llamado `car` con tres propiedades: `engine`, `steering`, y `speed`.

   ```javascript
   const sportsCar = Object.create(car);
   ```
   Se crea un nuevo objeto llamado `sportsCar` utilizando `Object.create(car)`, lo que significa que `sportsCar` hereda las propiedades del objeto `car`.

   ```javascript
   sportsCar.speed = "fast";
   ```
   Se modifica la propiedad `speed` del objeto `sportsCar` para asignarle el valor "fast".

   ```javascript
   console.log("The sportsCar Object: ", sportsCar);
   ```
   Se imprime en la consola el objeto `sportsCar` después de la modificación.

2. **Bucle `for...in`:**
   ```javascript
   console.log('----- for-in is unreliable -----');
   for(prop in sportsCar){
       console.log(prop);
   }
   console.log('🧐', "Iterating over object AND its prototype!");
   ```
   Se utiliza un bucle `for...in` para iterar sobre las propiedades del objeto `sportsCar`. Sin embargo, se señala como "unreliable" porque también itera sobre las propiedades del prototipo (`car` en este caso). La salida incluirá tanto las propiedades propias como las heredadas.

3. **Bucle `for...of`:**
   ```javascript
   console.log('----- for-of is reliable -----');
   for(prop of Object.keys(sportsCar)){
       console.log(prop + ":" + sportsCar[prop]);
   }
   console.log('🎯', "Iterating over object's OWN PROPERTIES only!");
   ```
   Se utiliza un bucle `for...of` para iterar sobre las propiedades del objeto `sportsCar`. Se utiliza `Object.keys(sportsCar)` para obtener solo las propiedades propias y, por lo tanto, evita iterar sobre las propiedades del prototipo. La salida incluirá solo las propiedades propias del objeto `sportsCar`.

**Salida esperada:**
```
The sportsCar Object:  { speed: 'fast' }
----- for-in is unreliable -----
speed
engine
steering
🧐 Iterating over object AND its prototype!
----- for-of is reliable -----
speed:fast
🎯 Iterating over object's OWN PROPERTIES only!
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/0e8f4508-90a4-4b5d-9b53-775076fff8d3)

En resumen, el código destaca la diferencia entre `for...in` y `for...of` al iterar sobre las propiedades de un objeto y cómo `for...of` puede utilizarse para iterar de manera confiable solo sobre las propiedades propias del objeto.

#### Literales de plantilla 

Los literales de plantilla en JavaScript ES6, son una poderosa característica que mejora la manipulación y creación de cadenas en comparación con el método convencional en ES5. Para empezar, se tiene una comparación básica de cómo se construyen las cadenas en JavaScript ES5 utilizando comillas simples o dobles. A continuación, se muestra un ejemplo con una variable `noMultiLine` y se imprime en la consola con `console.log`:

```javascript
let noMultiLine = "did you know, no multiline strings in ES5";
console.log(noMultiLine);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/e757a7ea-05db-4529-b19e-272c6f5940c5)

Aquí, se destaca la limitación al intentar dividir una cadena en varias líneas en ES5, lo que provoca un error. Ahora, introduzcamos los literales de plantilla en ES6 para abordar esta restricción y proporcionar una solución más flexible. Se muestra la variable `multiLine` con una cadena distribuida en varias líneas encerrada por comillas inversas (`):

```javascript
let multiLine = `multiline
string
using template literals`;

console.log(multiLine);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/8cf2f28a-cf70-4d63-8faf-0aadafd7e8e9)

Este enfoque demuestra la flexibilidad de los literales de plantilla al permitir la creación de cadenas multilínea sin preocuparse por errores de formato. Además, los literales de plantilla facilitan la interpolación de variables dentro de las cadenas. Creemos variables `first` y `second`, luego usemos la interpolación de variables dentro de una cadena más amplia:

```javascript
let first = "Hello";
let second = "World";

let interpolatedString = `${first}: ${second}`;
console.log(interpolatedString);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/227ff0b5-cab8-4dc7-9628-b382f778d916)

Aquí, se observa cómo las comillas dentro de las variables no generan conflictos al usar literales de plantilla. Este enfoque simplifica la concatenación y mejora la legibilidad del código. En resumen, los literales de plantilla en JavaScript ES6 ofrecen una sintaxis más poderosa y versátil para trabajar con cadenas, permitiendo la creación de cadenas multilínea e interpolación de variables de manera más eficiente.

#### Estructura de datos

Se conocen diversas estructuras de datos comunes en JavaScript, como objetos, matrices, mapas y conjuntos, y se destaca que la elección de la estructura de datos influye en cómo se codifica la solución.

Las estructuras de datos se presentan como una forma de organizar la información. Se ejemplifica que representar los datos como cadenas podría resultar poco eficiente, ya que sería necesario extraer los números para realizar cálculos. En cambio, almacenar las calificaciones en una matriz se propone como una opción más eficiente, agrupando datos relacionados bajo una única etiqueta. Por ejemplo:

```javascript
const gradesArray = [90, 85, 78, 92, 88];
```

Se introduce la idea de que JavaScript tiene ciertas limitaciones en comparación con otros lenguajes, pero se destacan las estructuras más comunes:

1. **Objetos:** Colección inalterable de pares clave-valor, útil en situaciones donde se necesitan asociaciones de clave-valor. Por ejemplo, en programación orientada a objetos. Ejemplo:

```javascript
const student = {
  name: "John Doe",
  grade: 95,
  subject: "Math",
};
```

2. **Arrays:** Colección iterable ordenada de valores, donde se accede a los valores mediante índices. Un bucle, como el bucle for, es una herramienta común para acceder y manipular datos en un array. Ejemplo:

```javascript
for (let i = 0; i < gradesArray.length; i++) {
  console.log("Grade:", gradesArray[i]);
}
```

3. **Mapas:** Similar a una matriz, pero consta de pares clave-valor, y permite cualquier tipo de valor como clave. A diferencia de los objetos, que limitan las claves a cadenas o símbolos. Ejemplo:

```javascript
const gradeMap = new Map();
gradeMap.set("Math", 90);
gradeMap.set("English", 85);
```

4. **Conjuntos:** Colección donde cada elemento debe ser único. Al intentar agregar un elemento no único, la operación no se ejecutará, sin lanzar errores ni realizar actualizaciones. Ejemplo:

```javascript
const uniqueGrades = new Set([90, 85, 78, 92, 88]);
uniqueGrades.add(92); // No se realiza la adición, ya que 92 ya está en el conjunto
```

#### Operadores de dispersión

El operador de propagación, es una característica introducida en la actualización ES6 de JavaScript, que se presenta como una herramienta versátil para copiar propiedades de objetos y concatenar elementos de matrices. Se destaca que este operador se representa mediante tres puntos.

Como ejemplo inicial, se crea una matriz llamada "top3" que contiene los tres mejores lugares para visitar en Roma: el Coliseo, la Fontana de Trevi y la Ciudad del Vaticano. Luego, se construye una función llamada "showItinerary" que enumera estos lugares utilizando tres argumentos. La función se invoca con los elementos de la matriz "top3", lo que requiere escribir cada elemento individualmente.

```javascript
// Creación de una matriz "top3" con los mejores lugares para visitar en Roma
let top3 = ["Coliseo", "Fontana de Trevi", "Ciudad del Vaticano"];

// Función que enumera los lugares utilizando argumentos
function showItinerary(lugar1, lugar2, lugar3) {
    console.log(`Visita ${lugar1}, luego visita ${lugar2} y termina con una visita a ${lugar3}.`);
}

// Invocación de la función utilizando elementos de la matriz "top3" sin el operador de propagación
showItinerary(top3[0], top3[1], top3[2]);

// Creación de una nueva matriz "top7" con siete destinos
let top7 = ["Destino1", "Destino2", "Destino3", "Destino4", "Destino5", "Destino6", "Destino7"];

// Invocación de la función utilizando elementos de la matriz "top7" con el operador de propagación
showItinerary(...top7);

// Utilizando el operador de propagación con la matriz "top3"
showItinerary(...top3);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/0e78fd62-eda9-4f9b-9c97-6bb5d44a07f1)

Luego, se plantea la pregunta sobre cómo manejar una función que debe mostrar siete lugares, lo que resultaría en una sintaxis poco práctica y repetitiva al pasar los argumentos. Se crea una nueva matriz llamada "top7" con siete destinos, y se muestra cómo invocar la función "showItinerary" con todos los elementos de esta matriz utilizando el método tradicional.

A continuación, se introduce el operador de propagación como una solución más eficiente y concisa. Se muestra cómo usar el operador de propagación en la función "showItinerary" al pasar la matriz "top7", simplificando significativamente la sintaxis. Esto elimina la necesidad de enumerar cada miembro individualmente.

Finalmente, se demuestra que el operador de propagación también se puede aplicar a la matriz más corta "top3", resaltando su versatilidad y facilidad de uso. En resumen, el video explora el concepto y la aplicación práctica del operador de propagación en JavaScript.

#### Operador de Rest en JavaScript

El operador de rest (`...`) en JavaScript es una característica introducida en ES6 (ECMAScript 2015). Se utiliza principalmente para trabajar con un número variable de elementos en funciones o al desestructurar arreglos. A continuación, se explica su uso en el contexto del código proporcionado:

**Desestructuración con Operador de Rest:**
```javascript
const [first, second, third, ...secondVisit] = top7;
```
En este ejemplo, el operador de rest se utiliza en la desestructuración de un arreglo (`top7`). Las primeras tres atracciones se asignan a las variables `first`, `second` y `third`, respectivamente. El operador de rest (`...secondVisit`) recoge el resto de los elementos en un nuevo arreglo llamado `secondVisit`. Esto proporciona una forma concisa de dividir una matriz en partes conocidas y el resto.

**Operador de Rest en Funciones:**
```javascript
function addTaxToPrices(taxRate, ...items) {
    const itemsWithTax = items.map(item => `${item} - Taxed at ${taxRate}%`);
    return itemsWithTax;
}

const taxedItems = addTaxToPrices(10, "Item1", "Item2", "Item3", "Item4");
```
En este caso, el operador de rest se utiliza en la definición de la función `addTaxToPrices`. Permite que la función acepte un número variable de parámetros después del primer parámetro (`taxRate`). Los elementos adicionales se agrupan en un arreglo llamado `items`. La función luego aplica un impuesto a cada artículo utilizando el método `map`.

**Teoría del Operador de Rest:**
- El operador de rest se utiliza para manejar situaciones en las que el número de elementos es variable o desconocido.
- Debe ser el último parámetro en la lista de parámetros de una función.
- Al desestructurar arreglos, el operador de rest recoge el resto de los elementos en una nueva variable.
- Facilita trabajar con un número variable de elementos, mejorando la flexibilidad y legibilidad del código.
  
Para un mejor entendimiento, se tomará de ejemplo el código anteriormente visto.

```javascript
// Creación de una matriz "top7" con siete lugares para visitar en Roma
const top7 = ["Coliseo", "Foro Romano", "Vaticano", "Fontana de Trevi", "Panteón", "Plaza Venecia", "Colina Palatina"];

// Uso del operador rest para desestructurar la matriz y obtener las primeras tres atracciones y el resto
const [first, second, third, ...secondVisit] = top7;

// Inspección de las variables obtenidas
console.log("First Attraction:", first);
console.log("Second Attraction:", second);
console.log("Third Attraction:", third);
console.log("Second Visit Attractions:", secondVisit);

// Definición de la función "addTaxToPrices" con el operador rest para recibir una lista de artículos
function addTaxToPrices(taxRate, ...items) {
    // Aplicación del tipo impositivo a cada artículo utilizando el método "map"
    const itemsWithTax = items.map(item => `${item} - Taxed at ${taxRate}%`);
    return itemsWithTax;
}

// Ejemplo de uso de la función "addTaxToPrices" con el operador rest
const taxedItems = addTaxToPrices(10, "Item1", "Item2", "Item3", "Item4");

// Mostrar los artículos con el tipo impositivo
console.log("Taxed Items:", taxedItems);
```

![image](https://github.com/JMDS2810/PROGRAMACION_CON_JAVASCRIPT/assets/112999455/06bfb23f-6b86-4125-9723-3216aa1496a2)

En este código, se utiliza el operador rest para desestructurar la matriz "top7" y obtener las primeras tres atracciones en variables individuales (`first`, `second`, `third`) y el resto de las atracciones en una nueva matriz llamada `secondVisit`. Además, se muestra un ejemplo de cómo el operador rest se puede utilizar en una función, en este caso, para crear una función `addTaxToPrices` que aplica un tipo impositivo a una lista de artículos utilizando el operador rest para recibir una cantidad variable de parámetros.

### JavaScript en el navegador

#### Módulos en JavaScript

La introducción de los módulos en JavaScript, especialmente con ES6, ha permitido una mayor modularidad y reutilización de código. Antes de ES6, el manejo de funciones globales generaba problemas en proyectos más grandes. CommonJS surgió como un intento de solución, pero su sintaxis no era plenamente compatible con los navegadores. La llegada de los módulos ES6 ha mejorado esta situación, ofreciendo unidades de código independientes y reutilizables.

A continuación, se presenta un ejemplo práctico utilizando etiquetas de script en un documento HTML. Se destaca la importancia del atributo `type` en la etiqueta `script` para especificar el tipo de contenido. Se menciona que, para evitar problemas de seguridad, es necesario ejecutar el archivo HTML en un servidor local, y se proporciona información adicional sobre la configuración de dicho servidor.

```html
<script type="module">
  import greetingModule from 'greeting.js';
  console.log(greetingModule.sayHello());
</script>
```
#### DOM en JavaScript

Se introduce el concepto de DOM (Modelo de Objeto del Documento) en JavaScript, comparándolo con un control remoto de televisión que permite cambiar el contenido de una página web. Se destaca que el DOM brinda un control detallado sobre las propiedades de los objetos de una página web, actuando como un "mando a distancia superpoderoso". 

1. **Acceso a DevTools para interactuar con el DOM:**
   ```javascript
   // Acceso a las DevTools: Hacer clic derecho en la ventana del navegador y seleccionar "Inspeccionar"
   ```

2. **Ejemplo de manipulación del DOM con JavaScript:**
   ```javascript
   // Creación de un elemento h2
   const h2 = document.createElement('h2');

   // Actualización del elemento h2 con atributos y texto
   h2.innerText = 'Esto es un encabezado h2';
   h2.setAttribute('ID', 'sub-heading');
   h2.setAttribute('class', 'secondary');

   // Añadir el elemento al DOM
   document.body.appendChild(h2);
   ```
   
   Este código demuestra la creación de un elemento `h2`, actualización con atributos y texto, y su posterior añadido al DOM.

#### Selectores en JavaScript

La capacidad de JavaScript para manipular el DOM, permite realizar cambios dinámicos en el contenido HTML en tiempo real, como cambiar colores o mostrar mensajes emergentes al hacer clic en un botón. La clave para esta manipulación es la capacidad de localizar objetos específicos en el documento HTML utilizando selectores en JavaScript.

El uso de selectores comienza con el objeto documento, que representa la página web almacenada en la memoria del navegador (DOM). Se introduce el método `querySelector` para localizar un elemento específico. Por ejemplo, al escribir `document.querySelector('p')`, se obtiene el primer elemento de párrafo, y este método puede utilizarse con otros elementos HTML, como anclas.

Se presenta el método `querySelectorAll` para obtener todas las coincidencias de un selector en la página. Luego, se tienen métodos específicos, como `getElementById` para encontrar elementos por su ID y `getElementsByClassName` para localizar elementos por su clase. Ejemplos prácticos incluyen la búsqueda de un elemento con el ID "heading" y aquellos con la clase "txt".

Se resalta la importancia de tener en cuenta que la palabra "element" es singular para ID y plural para nombres de clase. Se menciona que si un elemento no se encuentra, se devuelve `null` para ID y una colección vacía para nombres de clase. A continuación, se presentan los códigos de estos selectores en JavaScript.

1. **querySelector para obtener el primer elemento de un tipo:**
   ```javascript
   const primerParrafo = document.querySelector('p');
   ```

2. **querySelectorAll para obtener todas las coincidencias de un tipo:**
   ```javascript
   const todosLosParrafos = document.querySelectorAll('p');
   ```

3. **getElementById para encontrar elementos por ID:**
   ```javascript
   const elementoHeading = document.getElementById('heading');
   ```

4. **getElementsByClassName para encontrar elementos por clase:**
   ```javascript
   const elementosConClaseTxt = document.getElementsByClassName('txt');
   ```

#### Gestión de eventos

Se resalta la importancia de los eventos activados por el usuario en JavaScript, tales como el clic en un botón, y cómo dichos eventos pueden gestionarse mediante código JavaScript. Además, se señala la necesidad de escuchar eventos en secciones específicas de la página, introduciendo la idea de un controlador de eventos, una función dedicada a gestionar los eventos capturados.

En el proceso, se emplea el método `addEventListener` como una de las formas más simples para escuchar eventos en elementos HTML. Se presenta un ejemplo concreto de cómo escuchar un clic en el cuerpo de una página web, abordando la obtención de una referencia al elemento, la creación de una función de manejo de clics y la vinculación de dicha función al evento de clic utilizando `addEventListener`.

Adicionalmente, se aborda una alternativa para detectar eventos mediante el uso de atributos de eventos HTML. Se ofrece un segundo ejemplo en el cual se crea la función de manejo de clics denominada `handleClick2`. Se muestra cómo asignar esta función como un atributo `onclick` en un elemento HTML, específicamente, el encabezado (`H1`), lo cual activa el detector de eventos correspondiente.

1. **addEventListener para escuchar clic en el cuerpo:**
   ```javascript
   const target = document.querySelector('body');

   function handleClick() {
     console.log('Se hizo clic en el cuerpo.');
   }

   target.addEventListener('click', handleClick);
   ```

2. **Atributos de eventos HTML para escuchar clic en el encabezado:**
   ```javascript
   function handleClick2() {
     console.log('Se hizo clic en el encabezado.');
   }
   ```
   ```html
   <h1 onclick="handleClick2()">Encabezado</h1>
   ```

Estos ejemplos muestran cómo configurar detectores de eventos tanto con `addEventListener` como con atributos de eventos HTML.

#### Actualización del contenido de una página web

La actualización del contenido de una página web en JavaScript es un aspecto fundamental que involucra la manipulación del DOM y la gestión de eventos. A continuación, se explica cómo realizar esta actualización, tomando como referencia los temas previamente mencionados.

1. **Captura de Entrada del Usuario:**
   - La entrada del usuario se puede capturar mediante el método `prompt()`. Por ejemplo:

     ```javascript
     let answer = prompt('What is your name?');
     ```

2. **Manipulación del Contenido:**
   - La entrada capturada se almacena en la variable `answer`. Para manipular este contenido, se puede emplear un elemento HTML `<h1>`. Se verifica que la entrada sea de tipo cadena antes de proceder.

     ```javascript
     let answer = prompt('What is your name?');
     if (typeof(answer) === 'string') {
         var h1 = document.createElement('h1');
         h1.innerText = answer;
         document.body.innerText = '';
         document.body.appendChild(h1);
     }
     ```

3. **Uso de Formularios HTML:**
   - Se introducen formularios HTML como una alternativa más eficiente para manejar entradas del usuario. Un ejemplo de creación dinámica de un formulario con un campo de texto y un elemento `<h1>`:

     ```javascript
     var h1 = document.createElement('h1');
     h1.innerText = "Type into the input to make this text change";

     var input = document.createElement('input');
     input.setAttribute('type', 'text');

     document.body.innerText = '';
     document.body.appendChild(h1);
     document.body.appendChild(input);
     ```

4. **Escuchadores de Eventos:**
   - Se configura un escuchador de eventos para el evento `change`, que se activa al presionar ENTER después de escribir en el campo de entrada. Se muestra cómo actualizar el contenido del `<h1>` con el valor obtenido del campo de entrada.

     ```javascript
     var h1 = document.createElement('h1');
     h1.innerText = "Type into the input to make this text change";

     var input = document.createElement('input');
     input.setAttribute('type', 'text');

     document.body.innerText = '';
     document.body.appendChild(h1);
     document.body.appendChild(input);

     input.addEventListener('change', function() {
         h1.innerText = input.value;
     });
     ```
La combinación de la manipulación del DOM y el manejo de eventos en JavaScript permite la creación de sitios web interactivos y notables. Este enfoque proporciona flexibilidad para actualizar dinámicamente el contenido de una página web en respuesta a las acciones del usuario.

#### Mover datos en la web

**Mover Datos en la Web con JSON:**

La web moderna se compone de innumerables páginas web, servicios conectados y bases de datos. Para facilitar el intercambio de datos entre estos diversos componentes, se emplea el formato JSON (JavaScript Object Notation), ideado por Douglas Crockford en 2001.

Antes de JSON, XML era el formato común para el intercambio de datos, pero su sintaxis compleja y la falta de interoperabilidad con JavaScript condujeron a la adopción de JSON. Este formato se destaca por su ligereza y su sintaxis similar a la de un objeto JavaScript encadenado, lo que lo hace ideal para el manejo eficiente en código JavaScript.

JSON no solo sirve como formato de intercambio de datos, sino también como formato de archivo. Por ejemplo, al acceder a datos de terceros, se pueden obtener archivos JSON y convertirlos en objetos JavaScript para su manipulación local.

**Uso Práctico de JSON:**

Supongamos que se descarga un archivo JSON llamado `stockPrices.json` que contiene información sobre movimientos de precios de acciones. Este archivo puede convertirse en un objeto JavaScript, y su estructura permitirá acceder fácilmente a información específica.

```javascript
const currencyInfo = {
    USD: {
        // ...
    },
    GBP: {
        // ...
    },
    EUR: {
        // ...
    }
};
```

En este ejemplo, se accede a datos específicos, como los relacionados con la propiedad USD, para obtener la información necesaria en un momento dado.

**Reglas y Consideraciones de JSON:**

JSON es una cadena que debe seguir reglas específicas. Solo un subconjunto de valores JavaScript puede ser encadenado y analizado, incluyendo primitivas como cadenas, números, booleanos y nulos, así como objetos y matrices (sin funciones).

Algunas reglas clave incluyen el uso de comillas dobles para todas las claves de objetos, la delimitación por comas en objetos y matrices, y la representación adecuada de propiedades de cadena, número y booleana.

Es importante notar que JSON es más estricto que JavaScript en cuanto a la formación del código, siendo considerado un subconjunto de este lenguaje.

En resumen, JSON facilita la transferencia y manipulación de datos en la web, ofreciendo un formato ligero y fácilmente manejable en código JavaScript. Su adopción generalizada se debe a su eficiencia y compatibilidad con el entorno web moderno.

#### Notación de objetos JavaScript - JSON

**Conversión entre JSON y Objetos JavaScript:**

Se va a explorar el proceso de conversión entre cadenas JSON y objetos JavaScript, una habilidad esencial al trabajar con datos en la web. Se explicará cómo transformar una cadena JSON en un objeto JavaScript y viceversa.

**Conversión de JSON a Objeto JavaScript:**

Cuando se maneja una cadena JSON en JavaScript, es común convertirla en un objeto JavaScript para facilitar su manipulación. Utilizamos el objeto JSON global y su método `parse` para lograr esto. Aquí tienes un ejemplo:

```javascript
const JSONstr = '{"saludo": "hola"}';
const aPlainObj = JSON.parse(JSONstr);

// Manipulación del objeto JavaScript resultante
aPlainObj.saludo = "¡Hola de nuevo!";
console.log(aPlainObj.saludo);  // Salida: ¡Hola de nuevo!
```

En este código, se firma una cadena JSON a la variable `JSONstr` y luego se utiliza `JSON.parse` para convertirla en un objeto JavaScript (`aPlainObj`). Posteriormente, se manipula la propiedad `saludo` del objeto como cualquier otro objeto JavaScript.

**Conversión de Objeto JavaScript a JSON:**

Asimismo, es posible convertir un objeto JavaScript en una cadena JSON utilizando el método `stringify` del objeto JSON. Aquí tienes un ejemplo:

```javascript
const datos = { nombre: "John", edad: 25, ciudad: "New York" };
const JSONString = JSON.stringify(datos);

// Resultado: '{"nombre": "John", "edad": 25, "ciudad": "New York"}'
```

En este caso, se declara un objeto llamado `datos` y se utiliza `JSON.stringify` para convertirlo en una cadena JSON (`JSONString`). Es importante notar que las claves y valores en la sintaxis JSON deben estar entre comillas dobles.

**Consideraciones y Limitaciones:**

Al trabajar con JSON, es crucial recordar que las cadenas JSON no pueden contener funciones y no permiten comentarios JavaScript. Además, al usar `stringify` en un objeto JavaScript que contiene métodos, esos métodos se excluyen del resultado. Esto es esencial al interactuar con APIs para recuperar datos.

Esta habilidad de convertir entre JSON y objetos JavaScript se vuelve fundamental al procesar y manipular datos en aplicaciones web, especialmente al trabajar con APIs. Practicar esta técnica es esencial para cualquier desarrollador web.

#### Entornos de JavaScript - Node y NPM

**Análisis y Resumen del Texto:**

En la transición a Node.js, se destaca que antes de su introducción, los desarrolladores utilizaban diferentes tecnologías para crear backends, como PHP, Python, C-sharp, Ruby y Java. Node.js permitió el uso de JavaScript tanto en el front-end como en el back-end, facilitando la creación de aplicaciones web completas con un único lenguaje.

Node.js es presentado como un entorno independiente que puede ejecutarse en diversos contextos, como la línea de comandos, una aplicación de escritorio o el back-end de una aplicación web. Se menciona la existencia del administrador de paquetes npm, que permite la gestión de bibliotecas y frameworks como módulos de Node.js.

El proceso de instalación y uso de Node.js y npm se explica detalladamente. Se muestra cómo ejecutar comandos como `node` para ejecutar archivos JavaScript o `npm` para instalar módulos desde el repositorio npm. Además, se introduce el concepto de `package.json`, un archivo que contiene las instrucciones y dependencias del proyecto, facilitando su portabilidad y compartición con otros desarrolladores.

Finalmente, se destaca que al ejecutar `npm install`, se instalan las dependencias del proyecto, y se enfatiza que a veces estas dependencias pueden tener sus propias dependencias, lo que se traduce en un volumen significativo de datos que se descargan en la carpeta de módulos de Node.js.

1. **Ejecución de Comandos Básicos:**
   ```javascript
   // Ejecutar el comando node desde la línea de comandos
   node archivo.js

   // Ejecutar el comando npm desde la línea de comandos
   npm install
   ```

2. **Uso de npm para Instalar un Módulo:**
   ```javascript
   // Instalar el módulo llamado 'lowercase'
   npm install lowercase

   // Importar y usar el módulo en el código
   const lowercase = require('lowercase');
   ```

3. **Creación de un Proyecto y archivo `package.json`:**
   ```bash
   // Crear un nuevo proyecto e interactuar con Node.js y npm
   npm init

   // Contenido del archivo package.json
   {
     "name": "nombre-proyecto",
     "version": "1.0.0",
     "dependencies": {
       "lowercase": "^1.0.0"
     }
   }
   ```

Estos fragmentos de código y ejemplos resumen las acciones clave mencionadas en el texto relacionadas con Node.js y npm.

**Instalación de Node y NPM**

A continuación, se proporciona la orientación sobre la verificación y la instalación de Node.js y npm en diferentes sistemas operativos, específicamente en Windows, Mac OS utilizando Homebrew, y Ubuntu. Además, se sugiere mejorar la redacción para una mayor claridad y estructura.

1. **Verificación de la Instalación:**

   - **Windows:**
     Para verificar la instalación de Node.js y npm en Windows, utilice la combinación de teclas WINKEY+r para abrir la ventana Ejecutar. Ingrese `cmd` y presione Enter para abrir el símbolo del sistema. Luego, ejecute `node --version` y `npm --version` para confirmar las versiones instaladas.

   - **Ubuntu (Linux):**
     En Ubuntu, abra una nueva ventana bash (terminal) con CTRL+ALT+t. Dentro de la ventana, ejecute `node --version && npm --version` para visualizar ambas versiones de Node.js y npm.

2. **Instalación:**

   - **Windows:**
     Si Node.js y npm no están instalados en Windows, se sugiere visitar el sitio web oficial de Node.js (https://nodejs.org). Descargue la versión LTS y siga las instrucciones de instalación.

   - **Mac OS con Homebrew:**
     En el caso de Mac OS, se requiere instalar Xcode antes de Homebrew. Ejecute `xcode-select --install` en un terminal para instalar Xcode. Luego, instale Homebrew desde su sitio web oficial (https://brew.sh) utilizando el comando proporcionado. Después de instalar Homebrew, ejecute `brew install node` para instalar Node.js.

   - **Ubuntu:**
     En Ubuntu, abra una ventana bash con CTRL+ALT+t. Actualice los repositorios con `sudo apt update` y luego instale Node.js con `sudo apt install nodejs`.

Estas instrucciones proporcionan una guía detallada para verificar la instalación existente y realizar una instalación nueva en diferentes sistemas operativos. La mejora en la redacción busca ofrecer una estructura más clara y fácil de seguir para los usuarios.

#### Pruebas

**Resumen y Análisis:**

Se sabe de la importancia de probar el código JavaScript durante el proceso de desarrollo. Por ende, se destaca la necesidad de verificar que el código funcione correctamente antes de implementarlo. El enfoque principal se centra en la creación de pruebas para una función específica, en este caso, la función `concatStrings`. También se introduce el concepto de refactorización y el ciclo rojo-verde-refactor, fundamental en el Desarrollo Dirigido por Pruebas (TDD).

1. **Creación de Pruebas:**
   
   - Se inicia codificando una función `concatStrings` que une dos cadenas dadas como argumentos.
   - Se menciona la limitación de los comentarios para describir expectativas y se introduce la utilidad de los marcos de pruebas en JavaScript.

   ```javascript
   // Ejemplo de función concatStrings
   function concatStrings(a, b) {
     return a + b;
   }

   // Uso de comentarios para describir expectativas
   // concatStrings('abc', 'def') debe devolver 'abcdef'
   ```

2. **Uso de Pruebas Automatizadas:**

   - Se introduce el uso de pruebas automatizadas para verificar el comportamiento esperado de la función.

   ```javascript
   // Uso de pruebas con JEST
   test('concatStrings debe devolver la concatenación de las cadenas', () => {
     expect(concatStrings('abc', 'def')).toBe('abcdef');
   });
   ```

3. **Ciclo Rojo-Verde-Refactor (TDD):**

   - Se explica el ciclo TDD, donde se escribe una prueba que falla (rojo), se ajusta el código para que pase la prueba (verde), y luego se refactoriza el código sin cambiar los resultados.

   ```javascript
   // Ejemplo de ciclo TDD
   test('concatStrings debe devolver la concatenación de las cadenas', () => {
     expect(concatStrings('abc', 'def')).toBe('abcdef');
   });
   ```

4. **Ventajas de las Pruebas:**

   - Se resalta la utilidad de las pruebas, como la capacidad de ejecutarlas automáticamente, repetirlas sin esfuerzo y verificar expectativas.

   ```javascript
   // Ventajas de las pruebas
   // - Ejecutable automáticamente
   // - Repetible sin costo significativo
   ```

Este enfoque ayuda a garantizar la concisión, claridad y repetibilidad del código, así como a mantener la integridad del mismo durante su desarrollo continuo. Además, destaca la importancia de seguir el ciclo TDD para mejorar y optimizar el código de manera constante.

**Tipos de pruebas**

Se tienen 3 principales tipos de pruebas: pruebas de integración, pruebas unitarias y pruebas end-to-end (E2E). Se enfatiza que las pruebas son esenciales para confirmar que el software se comporta según los requisitos establecidos. Además, se menciona que la forma de abordar las pruebas puede variar según el rol y las motivaciones del profesional de desarrollo.

1. **Definición de Pruebas de Software:**
   
   - Las pruebas de software son el acto de confirmar que el software funciona según los requisitos establecidos.
   - Se registran las expectativas como requisitos de software.

   ```javascript
   // Definición de pruebas de software
   // Confirmar que el software funciona según los requisitos
   ```

2. **Tipos de Pruebas:**

   - **Pruebas End-to-End (E2E):**
     - Ejemplo: Un fabricante de ordenadores portátiles prueba portátiles encendiéndolos y usándolos como lo haría un usuario normal.
     - Enfoque: Mímica de la interacción del usuario con la aplicación web.
     - Observación: No es necesario que la persona que realiza las pruebas sea un desarrollador.

   ```javascript
   // Ejemplo de pruebas E2E
   // Imitar la interacción del usuario con la aplicación web
   ```

   - **Pruebas de integración:**
     - Comprueban cómo interactúan las partes del sistema entre sí.
     - Ejemplos: Pruebas de reacción de software, pruebas de integración de bibliotecas y enzimas.
     - Observación: Más rápidas y económicas que las pruebas E2E, pero más lentas y costosas que las pruebas unitarias.

   ```javascript
   // Ejemplos de pruebas de integración
   // Comprobar la interacción de las partes del sistema
   ```

   - **Pruebas unitarias:**
     - Proceso de probar las unidades más pequeñas del código fuente de forma aislada.
     - Ejemplo: Pruebas de funciones o métodos, unidades más pequeñas de código comprobable en JS.
     - Observación: Independientes, rápidas de ejecutar y fáciles de escribir.

   ```javascript
   // Ejemplo de pruebas unitarias
   // Probar unidades pequeñas del código de forma aislada
   ```

3. **Pirámide de pruebas:**

   - Representación de tres niveles de pruebas: Unitarias en la base, Integración en el centro y End-to-End en la cima.
   - Se describe la velocidad y el costo relativos de cada tipo de prueba.

   ```javascript
   // Representación de la pirámide de pruebas
   // - Pruebas unitarias (base): Mayor velocidad, menor costo
   // - Pruebas de integración (centro): Velocidad y costo promedio
   // - Pruebas E2E (cima): Más lentas y caras de ejecutar
   ```

#### Introducción a Jest

**Resumen y Análisis:**

Siempre es necesario probar el código en JavaScript y por ende, en esta parte se destaca el uso del marco de pruebas Jest para abordar este requisito. Se mencionan características clave del Jest, como la cobertura del código, simulaciones y pruebas de instantáneas. A continuación, se analizan los puntos clave:

1. **Pruebas en JavaScript:**
   
   - Se destaca la importancia de probar el código para asegurarse de que funcione según lo previsto.
   - JavaScript no tiene funcionalidades de prueba integradas, y se mencionan bibliotecas como Jasmine, Mocha, Karma y QUnit.

   ```javascript
   // Destacar la necesidad de pruebas en JavaScript
   // Mencionar bibliotecas de prueba como Jasmine, Mocha, Karma y QUnit
   ```

2. **Marco de pruebas Jest:**

   - Jest es un marco de pruebas de JavaScript utilizado comúnmente para probar código en React y otros frameworks.
   - Admite la cobertura del código para medir el porcentaje de código cubierto por pruebas.
   - Mayor cobertura del código reduce la probabilidad de errores no identificados.
   - Introducción al concepto de burla (mocking) para separar código de dependencias y realizar pruebas unitarias independientes.

   ```javascript
   // Destacar características de Jest: Cobertura de código, burlas, pruebas unitarias
   ```

3. **Cobertura del código:**

   - La cobertura del código mide el porcentaje de código cubierto por pruebas.
   - Mayor cobertura reduce la probabilidad de errores no identificados.

   ```javascript
   // Definición de cobertura del código y su importancia
   ```

4. **Simulaciones (Burlas):**

   - La simulación permite separar el código de las dependencias para realizar pruebas unitarias independientes.
   - Ejemplo de simulación: Simular datos como si vinieran del servidor cuando provienen del cliente.
   - Evita cuellos de botella al permitir que los desarrolladores trabajen de manera independiente en diferentes partes de la aplicación.

   ```javascript
   // Introducción a la simulación y su utilidad
   ```

5. **Pruebas asincrónicas en Jest:**

   - Jest facilita la prueba de código asincrónico sin configuraciones difíciles.
   - Las pruebas asincrónicas son relativamente fáciles de codificar, incluso para principiantes en el framework.

   ```javascript
   // Destacar la facilidad de prueba de código asincrónico en Jest
   ```

6. **Pruebas de instantáneas:**

   - Se mencionan las pruebas de instantáneas utilizadas para verificar la ausencia de regresiones en el DOM después de cambios en el código.

   ```javascript
   // Descripción de las pruebas de instantáneas y su utilidad
   ```

7. **Conclusión:**

   - Se concluye señalando que el lector ahora está familiarizado con el proceso de prueba en JavaScript utilizando Jest.

   ```javascript
   // Conclusión
   // El lector está familiarizado con las pruebas en JavaScript con Jest
   ```

**Pruebas en Jest**

A continuación se muestran los pasos para instalar los paquetes necesarios para probar código JavaScript con el marco de Jest y configura una prueba básica. 

1. **Creación de la función AddFive:**
   
   - Se menciona la necesidad de escribir una función que sume cinco a un valor.
   - Se crea un nuevo archivo llamado `addFive.js`.
   - El código de la función `addFive` se define en el archivo.

   ```javascript
   // Creación del archivo addFive.js y la función addFive
   ```

2. **Configuración del entorno de pruebas:**

   - Se verifica si Node.js y NPM están instalados en el sistema.
   - Se identifica que Jest no está instalado globalmente en la máquina.

   ```javascript
   // Verificación de la instalación de Node.js y NPM
   // Identificación de falta de instalación global de Jest
   ```

3. **Configuración de Package.json y instalación de Jest:**

   - Se utiliza el comando `npm init` para crear un archivo `package.json`.
   - Jest se instala localmente para el proyecto usando el comando `npm install --save-dev jest`.

   ```javascript
   // Configuración de package.json
   // Instalación local de Jest
   ```

4. **Configuración de pruebas:**

   - Se crea un archivo de prueba llamado `AddFive.test.js`.
   - La función `addFive` se importa para ser probada.

   ```javascript
   // Creación de archivo de prueba AddFive.test.js
   // Importación de la función addFive para la prueba
   ```

5. **Configuración y ejecución de la Prueba:**

   - Se utiliza el método de prueba (`test`) de Jest para definir expectativas.
   - La función de prueba comprueba que `addFive` devuelve el número más cinco.

   ```javascript
   // Configuración y ejecución de la prueba usando Jest
   ```
Se presenta el ejemplo de AddFive:

**Código de la Función addFive:**

```javascript
// Archivo addFive.js
function addFive(value) {
  return value + 5;
}

module.exports = addFive;
```

**Configuración del Package.json:**

```json
// Contenido del archivo package.json después de ejecutar npm init
{
  "name": "mi-proyecto",
  "version": "1.0.0",
  "description": "Proyecto de ejemplo",
  "main": "index.js",
  "scripts": {
    "test": "jest"
  },
  "author": "Tu Nombre",
  "license": "ISC"
}
```

**Instalación de Jest:**

```bash
npm install --save-dev jest
```

**Archivo de Prueba AddFive.test.js:**

```javascript
// Archivo AddFive.test.js
const addFive = require('./addFive');

test('Suma cinco al valor', () => {
  expect(addFive(7)).toBe(12);
});

test('Suma cinco al valor negativo', () => {
  expect(addFive(-3)).toBe(2);
});
```

Estos ejemplos asumen que los archivos se encuentran en el mismo directorio. Puedes ajustar las rutas según la estructura de tu proyecto. Luego, para ejecutar las pruebas, simplemente usa el comando:

```bash
npm run test
```

Esto ejecutará Jest y mostrará los resultados de las pruebas en la consola.

#### TDD (desarrollo basado en pruebas)

El TDD es un proceso de escritura de código que busca satisfacer los requisitos mediante la creación de pruebas antes de la implementación real. El enfoque TDD implica un ciclo de trabajo que incluye las fases de prueba fallida (Rojo), prueba pasada (Verde) y refactorización (mejora del código sin cambiar la funcionalidad). Entre los beneficios del TDD se destaca la minimización de regresiones, la obtención de pruebas automatizadas y rápidas, así como la documentación efectiva del sistema, facilitando la integración de nuevos miembros al equipo de desarrollo. En resumen, el TDD, al invertir la secuencia tradicional de desarrollo, contribuye significativamente a la calidad y mantenimiento eficiente del software a lo largo del tiempo.

A continuación se muestra un ejemplo.

*Ejemplo de prueba (TDD):*

```javascript
// Archivo de prueba (ej. Keys.test.js)
test('Existencia de la función estadoDeLasLlaves', () => {
  expect(estadoDeLasLlaves).toBeDefined();
});

test('Registro del estado de las llaves', () => {
  const keysState = true;
  expect(estadoDeLasLlaves(keysState)).toBe('Keys state: true');
});
```

Este ejemplo representa una prueba ficticia que se ajusta al ciclo de TDD.

