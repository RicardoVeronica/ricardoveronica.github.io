---
title: Tú sabes ¿qué es la programación?
date: 2022-08-28 10:30:00 +0800
categories: [programacion, tutoriales]
tags: [programacion, tutoriales]
---

> La programación en realidad es simple, solo se trata de darle instrucciones a una computadora para que haga lo que queremos que haga.

![Tú sabes ¿qué es la programación?](https://miro.medium.com/max/1400/1*S9V5L2DeaUnsDQ13huHMxA.jpeg)
_Photo by Nicole Wolf on Unsplash_

[La programación](https://es.wikipedia.org/wiki/Programaci%C3%B3n) se trata de meter datos en la computadora, y esperar la salida de estos cuando ya han sido trabajados dentro de la máquina.

Por ejemplo, Microsoft Word, metes unos datos, (es decir las letras que escribes en el teclado), después la computadora hace lo suyo y esperas que en tu monitor se vean reflejadas palabras. Bueno esa es la base de todo en la programación.

**Entrada de datos -> La computadora hace su función -> Resultado**

Las computadoras son herramientas y como tales fueron creadas para facilitarnos la vida (y la comunicación), de hecho ya hay miles de programas que nos facilitan mucho las tareas cotidianas de nuestro mundo moderno, por ejemplo la calculadora de Windows, nos ayuda mucho a la hora de hacer operaciones matemáticas, las alarmas de tu celular, que te ayudan a despertar a la hora que necesitas despertar (Si, aunque a veces las odiemos), pero para algunas cosas es posible que no existan los programas que necesites.

*Aquí es donde entra la programación.*

Programar en ocasiones puede ser frustrante y en otras ocasiones gratificante, lo que es una constante aquí es que **al igual que las matemáticas, ayuda a tu cerebro a ejercitarse**, ejercita el pensamiento abstracto, ejercita el razonamiento lógico, entre otras cosas, es por eso que talvez has escuchado la frase: **“Todo el mundo debería aprender a programar”.**

## Lenguajes de programación

Para poder darle órdenes a una computadora es esencial que te entienda; de otra forma, sería como gritarle a tu perro que vaya a la tienda por una cerveza y que te la sirva en tu tarro favorito. Para esto se inventaron los [lenguajes de programación](https://es.wikipedia.org/wiki/Lenguaje_de_programaci%C3%B3n), que es la forma más amigable de tener una “conversación” con tu computadora, recuerda que estas máquinas solo entienden de unos y ceros, así que entablar una conversación a base de código binario seria por decirlo de una manera educada, **WTF!!.**

Existen lenguajes de alto y de bajo nivel, (No, no estoy siendo elitista o clasista) esto se refiere a, que tan cerca o lejos está de los unos y ceros dicho lenguaje de programación, por ejemplo, el lenguaje de más bajo nivel por excelencia es [Assembly](https://es.wikipedia.org/wiki/Lenguaje_ensamblador), este lenguaje es muy difícil de aprender para los programadores, pero para la máquina es sumamente fácil, en cambio [Python](https://www.python.org/) es un lenguaje de alto nivel que utiliza palabras como if, and, for, else, etc. para poder comunicar el mensaje a la máquina, es decir mientras más alto nivel sea el lenguaje de programación, más abstracción tiene, en pocas palabras, es incomprensible para la computadora, pero para ti que eres humano (Eso espero) es más sencillo entender. Y sí, necesitas Inglés para poder programar, por lo menos un poquito, si entendiste las palabras que escribí arriba, vas por buen camino.

También existen los [Paradigmas](https://es.wikipedia.org/wiki/Paradigma) de programación, como, imperativa, declarativa, orientada a objetos, funcional, estructurada, entre otras, pero si estás empezando, no te preocupes, solo concéntrate en - tipos de datos, variables, condiciones, ciclos y funciones de tu lenguaje favorito, pues estos conceptos son los más básicos y se aplican a cualquier lenguaje de programación.

## Lógica de programación

Bueno como dije anteriormente lo más básico en la programación se aplica a cualquier lenguaje, iniciando con los tipos de datos que puedes usar en tu lenguaje favorito y las variables para almacenar estos datos, por ejemplo:

- String o Cadena de caracteres

```js
// Variable llamada name que almacena en memoria un string "ricardo"
let name = "ricardo"
```

- Number o número, enteros y decimales

```py
# Variable money que almacena en memoria el number 100
money = 100
```

- Condicionales

```js
let x = 100
let y = 99

// Con la condicion if preguntamos si 99 es menor que 100,
// si es verdad que imprima en pantalla el string "verdadero"
if (y < x) console.log("verdadero")
```

- Ciclos

```py
# Litas, es decir un lugar en memoria que almacena varios datos.
my_list = [1, 2, 3]

# Con el ciclo for, pedimos que se imprima cada uno de los numbers
# de la variable my_list
for number in my_list:
  print(number)
```

- Funciones

```ts
// Funcion hello que pide un nombre con el tipo de dato string
// para imprimir un saludo personalizado
function hello(name: string) {
  console.log("hello " + name)
}

// Pasamos el string "Ricardo" a la funcion que nos pide un nombre
hello("Ricardo")

// Esto nos da como resultado - Hello Ricardo
```

> Y así de fácil es iniciar tu viaje en la programación espero que esta pequeña introducción te guste y te anime a seguir aprendiendo y divirtiéndote

## Disclaimer

Lo aquí expuesto es solo una pequeña parte del mundo tan complejo de lo que es la programación, espero te ayude al menos un poco si estás iniciando o estás interesado en aprender a programar.
