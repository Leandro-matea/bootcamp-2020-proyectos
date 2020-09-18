# Módulo 3 - Mateify API

El proyecto del módulo 3 tiene como objetivo poner en práctica y evaluar los conocimientos de backend con Express y MongoDB.
El proyecto se realizará de forma **individual.**
El proyecto consiste en 2 grandes partes, una api y un frontend. Se realizará una api para manejar usuarios y canciones(agregar, buscar, modificar y eliminar).  Los usuarios tienen una lista de canciones favoritas. 
Por otro lado, el frontend tiene como objetivo mostrar 2 listas:
- una lista que muestra los usuarios existentes.
Al seleccionar un usuario de la lista
- se muestra la lista de canciones favoritas.


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

- Presentación del proyecto - Martes 22 Setiembre
- Análisis de requerimientos en conjunto - Martes 22 de Setiembre
- Pre entrega (repositorio creado y contrato de la api en en readme.md) - Jueves 24 de Setiembre
- Entrega final - Domingo 4 de Octubre
- Seguimiento del proyecto con cada uno - Todos los días
- Dudas y consultas - Todos los días

## Requerimientos no funcionales

A continuación se listan los requerimientos que no corresponden a como debe funcionar la aplicación pero que serán evaluados y se deberán cumplir para aprobar el proyecto.
- Subir el proyecto a un repositorio de GitHub personal.
- Utilizar [Express](https://expressjs.com/es/guide/routing.html)
- Utilizar [Mongoose](https://mongoosejs.com/docs/guide.html).
- Utilizar create-react-app y materail-ui para el forntend.
- Hacer un [deploy del frontend en GitHub Pages](https://github.com/gitname/react-gh-pages)
- Hacer un [deploy del backend en Vercel](https://vercel.com/)

## Funcionalidades

Se deberá crear una api para el manejo de usuarios y canciones. Los usuarios podrán tener canciones favoritas.
Los usuarios deben tener un nombre, apellido, correo electrónico y edad.
Las canciones deben tener el siguiente formato:
         <code>   {
                "name": String,
                "album": String,
                "duration": String,
                "artist": {
                    "name": String
                    "coverUrl": String
                }
            }
           </code>

Por otra parte, se debe hacer una aplicación frontend en React, donde se muestre la lista de usuarios y al seleccionar un usuario, 
se muestre el listado de sus canciones favoritas como muestra el diseño.
 
## Funcionalidades api

- Mostrar toda la lista de usuarios.

- Agregar, modificar y eliminar usuarios.

- Agregar, modificar y eliminar canciones.

- Agregar y eliminar canciones a favoritos de un usuario.

## Funcionalidades frontend

- Al seleccionar un usuario, se deben mostrar las canciones favoritas del mismo en otra lista.

El diseño del frontend será libre para esta entrega. Si debe seguir esta [estructura](https://drive.google.com/file/d/1u3WJ8dKQnH4k6Ba3hrHLEg7ICmq3XDrr/view?usp=sharing), pero los colores y estilos los define cada uno.

# Importante
- Este proyecto tiene como prioridad evaluar los conceptos de api y base de datos. 
- Tendrán 2 proyectos diferentes en Github, uno con la api y otro con el frontend
- La api se debe deployar en Vercel y el frontend en github pages.
- La **prioridad es la api**. No comenzar el frontend sin tener la api andando
