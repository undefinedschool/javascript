# Capítulo 1

## Referencias

- [The JS Way -  capítulo 1](https://github.com/bpesquet/thejsway/blob/master/manuscript/chapter01.md)
- [You Don't Know JS: Up & Going - capítulo 1](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch1.md)

## Mostrando mensajes en pantalla

**Ejemplo:** 

```
console.log("Hello from JavaScript!");
```

`console.log()` muestra por la consola el **valor** que recibe por parámetro. En el caso del ejemplo anterior, estamos mostrando un valor de tipo _string_.

### Ejercicio

[Exercism: Hello World](https://exercism.io/my/solutions/b1f98d79300a47bc94be6f8b8a03e14a)

## Valores y tipos de datos

Un **valor** es una pieza de información o dato utilizado en un programa. Los valores pueden clasificarse, según su _forma_ en lo que llamamos **tipos**. El tipo de un valor determina sus características y las operaciones que podemos realizar con él.

Cada lenguaje de programación tiene definidos sus valores y tipos propios.

### Number

Utilizamos el tipo **number** para representar valores numéricos, sin distinguir entre números naturales, enteros, reales, etc.

**Ejemplo:** 

```
-1
```

```
0
```

```
3.14
```

```
1/3
```

### Ejercicio

[number](http://www.asmarterwaytolearn.com/js/3.html)

### String

Representa valores de texto, conocidos como _cadenas de caracteres_. Se escriben entre comillas simples o dobles, sin mezclar.

**Ejemplo:** 

```"JavaScript no es Java"```

```'JavaScript se hizo en 10 días'```

Si queremos _unir_ diferentes strings, utilizamos una operación que se llama _concatenación_, con el operador **+** (el mismo que usamos para sumar números, pero en este caso *no estamos sumando*).

**Ejemplo:** 

```'Java' + 'Script' => 'JavaScript'```

### Ejercicio

[string](http://www.asmarterwaytolearn.com/js/2.html)

## Estructura de un programa

Vimos que un _programa_ es una lista *finita* y *ordenada* de instrucciones, que le dicen a una computadora qué tareas realizar. Para escribir estas instrucciones utilizamos archivos de texto, lo que se conoce como el _código fuente_ de nuestro programa. Cada línea de código fuente se denomina _línea de código_.

Para escribir código JavaScript válido, debemos seguis las reglas de _sintaxis_ definidas en el lenguaje. Un conjunto de reglas sintácticas se denomina _gramática_.

> ✨ El código que escribimos no es para la máquina, sino para comunicar ideas a otras personas. Por eso, queremos que sea lo más claro posible

### Instrucciones

Una instrucción es un conjunto válido (según la sintaxis del lenguaje) de palabras, números, operadores y otros símbolos que realizar una tarea particular.

**Ejemplo:** 

```a = b * 2;```   

En JavaScript, terminamos las instrucciones con el símbolo `;`.   

Un programa está compuesto por una serie de instrucciones.  

> ✨ En lo posible, escribir 1 instrucción por línea de código

### Expresiones

Las instrucciones están compuestas de 1 o más _expresiones_. Una expresión es cualquier referencia a una variable, valor, o conjuntos de variables y valores combinados con operadores. Volviendo al ejemplo anterior `a = b * 2`, tenemos la siguiente expresión

- `2` es una expresión de un valor literal
- `a` es una expresión variable, que significa obtener su valor actual
- `b` es una expresión variable, que significa obtener su valor actual
- `b * 2` es una expresión aritmética, que significa multiplicar el valor de `b`por 2
- `a = b * 2` es una expresión de asignación, que significa asignarle el valor resultante de la expresión `b * 2` a la variable `a`.

### Operadores

Un operador es un _símbolo_ que le dice al compilador/intérprete que ejecute cierta operación aritmética o lógica y produzca un resultado.

Es importante tener en claro que los operadores, igual que en las matemáticas, siguen un [orden de evaluación](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence).

### Flujo de ejecución

Cuando se ejecuta un programa, las instrucciones que forman parte del código fuente del mismo son _ejecutadas_ una tras otra. Para esto, el _engine_ (el cual utilizamos a través de nuestro _browser_ o de Node) primero debe traducir el código fuente escrito en JavaScript a _código máquina_, es decir, código que entiende y puede ejecutar la computadora. Este proceso lo lleva a cabo el compilador/intérprete.

### Comentarios

Son líneas de código que **no se ejecutan**.

Como referencia, leer la sección sobre comentarios en el artículo _[The Exceptional Beauty of Doom 3's Source Code](https://kotaku.com/the-exceptional-beauty-of-doom-3s-source-code-5975610)_.

> ✨ Si estamos escribiendo muchos comentarios, tomarlo como señal de que tal vez nuestro código no sea lo suficientemente claro

## 🚀 [Coding time!](https://github.com/bpesquet/thejsway/blob/master/manuscript/chapter01.md#coding-time)
