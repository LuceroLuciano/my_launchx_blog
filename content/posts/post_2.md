---
title: "Creación de objetos y clases en JS"
date: 2022-04-23
description: 'En este post estare compartiendo mi aprendizaje sobre objetos y clases con JS'
---

# Hola de nuevo!, ¿Sabías que somos objetos?.

Un pocoo de contexto. Los objetos son cosas de la videa real, sí, son todas aquellas cosas que puedes 
ver o tocoar, por ejemplo: una guitarra, un lapiz, una planta, un perro o un gato, ademas de 
ser seres vivos son objetos como nosotros pero, ¿qué tienen en comun todos ellos?, sencillo, todos y
cada uno de los objetos mencionados tienen: 
  - nombre
  - color
  - tamaño
  - material (en el caso de la guitarra y el lapíz)
  - raza (en el el caso del perro y el gato)
  - edad

Todos estos atributos son carateristicas de un objeto y a continuacón te mostrare como se crea un objeto
en Java Script.

1. Crear una variable que contendra los atributos del objeto. Ejemplo:
```
  const dog = {
    name: "Raspi",
    age: 2
    color: "Black"
    size: 50    
  }
  
  console.log(gog)
```
2. Crear un objeto _humano_ con sus atributos (Por esta razón es que somos objetos, porque tenemos caracteristicas, en programación
  son conocidos como **Atributos**).
Para este ejemplo los atributos son los siguientes:
- nombre
- edad
- genero
- nacionalidad
- actividades que reaiza: comer, caminar, trabajar, estudiar, dormir

Ahora modelemos el objeto. Ejemplo:
```
  const human = {
    name: "Yuri",
    age: 20
    gender: "Female"
    nationality: "Japanese"
    activities: ["Eat", "Walk", "Work", "Study", "Sleep"]
  }
  
  console.log(human)
```

### Clases
Las clases son el molde con el que podemos crear n cantidad de objetos, por ejemplo; la clase humana,
dentro de esta clase hay objetos como, hombres, mujeres, niños, niñas, adultos, etc. Para entender este 
concepto, veamos un ejemplo.

1. Para este caso hablaremos de animales. Como primer punto, tendremos una clase animal, con los siguientes parametros:
- nombre, raza, edad, alimentación
  ```
    class Animal {
      constructor(name, breed, age, food){
        this.name = name
        this.breed = breed
        this.age = age
        this.food = food
      }
    }
    
    // Aqui creamos un objeto y a esto se le llama (INSTANCIAR OBJETO)
    const dog = new Animal("Astro", "Pastor Aleman", 3, "Croqueta Chapete")
    console.log(dog)
    
    //Aqí creamos un segundo objeto (INSTANCIAMOS OBJETO 2)
    const cat = new Animal("Kiera", "Michi", 3, "Wiskas")
    console.log(cat)
    
    const cat2 = new Animal("Kucha", "Silvestre", 5, "Atun")
    console.log(cat2)
    
    const cat3 = new Animal("Bruno", "Silvestre", 1, "Croquetas gato fiel")
    console.log(cat3)               
    
  ```
CONCEPTOS NUEVOS: 
**Constructor** es para inicializar los valores de un objeto
**this** es una palabra reservada de Java Script para hacer referencia a los valores del objeto
**Instanciar un objeto** es crear un nuevo objeto con los valores definidos en la clase

Objetos sin clase:
```
  // Objetos sin clase
    
    const cat = {
      name: "Kiera",
      breed: "Michi",
      age: 3,
      food: "Wiskas"
    }    
    console.log(cat)
    
    const cat2 = {
      name: "Kucha",
      breed: "Silvestre",
      age: 5,
      food: "Atun",
    }    
    console.log(cat2)
    
    const cat3 = {
      name: "Bruno",
      breed: "Silvestre",
      age: 1,
      food: "Croquetas gato fiel"
    }    
    console.log(cat3)
```

Como viste en el ejemplo anterior, las clases nos ayudan a reutilizar código y nos ayudan bastante para optimizar 
un proyecto, qué pasaria si NO utilizaras clases y tuvieras que crear/escribir las caracteristicas de 10 michis, 
talvez seria facil para 10 michis, pero, ¿Qué pasaria si fueran 100, 1000 o más michis? 😱

#### Gracias por leerme. Nos vemos en el siguiente post 🚀.
