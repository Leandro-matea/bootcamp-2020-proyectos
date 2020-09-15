# Módulo 3 - Mateify API

El proyecto del módulo 3 tiene como objetivo poner en práctica y evaluar los conocimientos de backend con Express y MongoDB.

El proyecto se realizará de forma **individual.**

#### Conceptos a aplicar

- Diseño de una API: variables, rutas, verbos http, request, response.
- Uso de Express.
- Uso de MongoDB.
- Uso de Mongoose.
- Manejo de errores y status.
- Buenas prácticas de apis, arquitectura.
- Integración de fontend con backend.
- Deploy de una api.

#### Método de evaluación

Evaluaremos tanto la funcionalidad de la aplicación como el uso de buenas prácticas en el código. 

Les daremos una devolución personal a cada uno.

## Cronograma

- Presentación del proyecto - Lunes 21 Setiembre
- Análisis de requerimientos en conjunto - Lunes 21 de Setiembre
- Pre entrega (repositorio creado y contrato de la api en en readme.md) - Miércoles 23 de Setiembre
- Entrega final - Domingo 4 de Octubre
-----------------------------------------------------------------------
- Seguimiento del proyecto con cada uno - Todos los días
- Dudas y consultas - Todos los días

## Requerimientos no funcionales

A continuación se listan los requerimientos que no corresponden a como debe funcionar la aplicación pero que serán evaluados y se deberán cumplir para aprobar el proyecto.

- Subir el proyecto a un repositorio de GitHub personal.
- Utilizar [Express](https://expressjs.com/es/guide/routing.html)
- Utilizar [Mongoose](https://mongoosejs.com/docs/guide.html).
- Hacer un [deploy del frontend en GitHub Pages](https://github.com/gitname/react-gh-pages)
- Hacer un [deploy del backend en Vercel](https://vercel.com/)

## Funcionalidades

Se deberá crear una api para el manejo de usuarios y canciones. Los usuarios podrán tener canciones favoritas.
Los usuarios deben tener un nombre, apellido, correo electrónico y edad.
Las canciones deben tener el siguiente formato:

{
    "name": String,
    "album": String,
    "duration": String,
    "artist": {
        "name": String
        "coverUrl": String
    }
}

Por otra parte, se debe hacer una aplicación frontend en React, donde se muestre la lista de usuarios y al seleccionar un usuario, 
se muestre el listado de sus canciones favoritas como muestra el diseño.
 
## Funcionalidades api

- Mostrar toda la lista de usuarios.

- Agregar, modificar y eliminar usuarios.

- Agregar, modificar y eliminar canciones.

- Agregar y eliminar canciones a favoritos de un usuario.

