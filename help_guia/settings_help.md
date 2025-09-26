# Ayuda sobre la seccion de settings

## ¿Que hace el archivo ´dash_header´

Este archivo nos sirve para poder darnos una bienvenida en nuestro archivo home
MUY importante tener instalado  el plugin *dataview* y activar la opcion de ejecutar js
Este archivo es configurable para que puedas agregar cualquier mensaje que se te ocurra.
Asegurate de agregar una (coma) al agregar nuevos mensajes de bienvenida.
- Por ejemplo:

```js
let morning = [
    "primer mensaje",
    "segundo mensaje"
]
```

## ¿Qué hace el archivo TO-DO
Este archivo funciona como vizualizador de tareas programadas para el archivo home.md
Se hace uso de  *tasks* un plugin que nos ayuda a administrar tareas y agregarlas donde nosotros configuremos, agregarlos a un archivo en especifico, estados, eh incluso a varios archivos.
En este archivo basicamente agrego vistas para diferentes tipos de tareas que se asignaran o listaran de acuerdo a ese estado.
Yo agrego las siguientes:

- Tareas de objetivos semanales
- Tareas organizadas para la semana actual
- Tareas Diarias y para Mañana
- Tareas Mensuales

Despues vienen las tareas personalizadas:
Que estan se pueden agregar en funcion de su tipo personalizado, en este tenemos las siguientes:
- Investigar
- Lecturas
- Pendientes Proyectos
- Canceladas

## ¿Qué hace el archivo home?
En este archivo tenemos un compilado de información dentro del vault, es decir, podemos hacer una pagina principal que nos permite revisar de manera breve lo que tenemos en nuetro vault.

