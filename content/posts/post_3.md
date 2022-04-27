---
title: "Diferencia entre == y === en JS"
date: 2022-04-27
description: 'Aquí encontraras la diferencia entre los operadore == y ==='
---

# Bienvenidx a mi nuevo post 🛸

En este post quiero agradecerte por el tiempo que te tomas a leer lo que escribo y esque yo solo 
comparto lo que mi MC [Carlo](https://github.com/carlogilmar) me enseña ⭐. Hoy quiero explicarte la diferencia que existe entre
`==` y `===`

1.- `==` Compara solo los valores, sin importar el tipo de dato. Para el caso del siguiente ejemplo la respuesta es `true`. 
Ejemplo:
```
let numberOne = 3
let numberTwo = "3"
console.log(numberOne == numberTwo) // true
```

2.- `===` Compara el tipo de dato y el valor. En este ejemplo el resultado es `False`.
```
let numberOne = 3   // tipo de dato Int
let numberTwo = "3"  // tipo de dato String
console.log(numberOne === numberTwo)  // false
```

Asi que ten cuidato cuando quiras comparar valores y/o tipos de datos.

Espero que te haya gustado este post, nos vemos en el siguiente. 🚀
