---
title: "Aprendiendo a usar Markdown"
date: 2022-05-06
description: 'Markdown:'
---



# Titulo 1

## Titulo 2

### Titulo 3

#### Titulo 4

##### Titulo 5

###### Titulo 6

<!--Esto es un comentario -->

Hola

Este es un textomen *Italica*

Este es un texto en **negrita**

Este es un texto en ~~tachado~~

<!-- Listas-->

* Apple
* Banana
* Orange

- Azul 
- Rojo

1. Apple
2. Orange
3. Banana

Lista anidada:

- Apple
  - Apple 2
  - Apple 3
    - Apple 3.1   

1. Naranja  
  1.1 Naranja 1 

[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com " Texto que deseamos se vea")

> this is a quote

--- 

___

`console.log("Hello World")`

```
[
  {
    "id": "6264d5d89f1df827eb84bb23",
    "name": "Warren",
    "email": "Todd@visualpartnership.xyz",
    "credits": 508,
    "enrollments": [
      "Visual Thinking Intermedio",
      "Visual Thinking Avanzado"
    ],
    "previousCourses": 1,
    "haveCertification": true
  }
  ]
```

___

```javascript
// Ejemplo 16: Ordenando una lista de objetos
const users = [
    { name: 'A', age: 150 },
    { name: 'B', age: 50 },
    { name: 'C', age: 100 },
    { name: 'D', age: 22 },
  ]
  
  users.sort((a, b) => { // podemos invocar una función
    if (a.age < b.age) return -1
    if (a.age > b.age) return 1
    return 0
  })
  
  console.log("Ejemplo 16: Ordenando una lista de objetos por la edad")
  console.log(users) // sorted ascending
```

```python
print("Hello world")
```

|Tables         |Are         |cool |
|---------------|------------|-----|
|col 3 is       |rigth-aliged|$1600|
|col 2 is       |centered    |  $12|
|zebfra stripes |are neat    |   $1|


<!-- los : son para definir por donde estara justificada la Info -->

|Tables         |Are         |cool |
|---------------|:----------:|----:|
|col 3 is       |rigth-aliged|$1600|
|col 2 is       |centered    |  $12|
|zebfra stripes |are neat    |   $1|

![Visual studio Code]()
