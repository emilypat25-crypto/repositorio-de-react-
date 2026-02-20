📘 Actividades JavaScript – CRUD y Programación Asíncrona
📌 Información General

Programa: Análisis y Desarrollo de Software
Evidencia: Actividades prácticas JavaScript
Aprendiz: Emily Patiño S
Año: 2026

📝 Descripción del Proyecto

Este proyecto contiene el desarrollo de diferentes actividades prácticas enfocadas en la comprensión y aplicación de conceptos fundamentales de JavaScript moderno.

Se implementa una arquitectura Feature-Based, organizando cada funcionalidad en carpetas independientes para mejorar la estructura, mantenibilidad y escalabilidad del proyecto.

El sistema incluye:

✔️ CRUD con almacenamiento en LocalStorage

✔️ Implementación de Callbacks

✔️ Uso de Promesas

✔️ Async/Await

✔️ Destructuring de objetos

La interfaz fue desarrollada con Bootstrap 5 para garantizar diseño responsive y buena experiencia de usuario.

🛠 Tecnologías Utilizadas

HTML5

CSS3

JavaScript (ES6+)

Bootstrap 5

LocalStorage

📂 Estructura del Proyecto
src/
 ├── features/
 │    ├── crud/
 │    │     ├── index.html
 │    │     └── main.js
 │    ├── callback/
 │    ├── promise/
 │    ├── async/
 │    ├── destructuring/
 │
 ├── shared/
 └── styles.css

La estructura está organizada por funcionalidades (Feature-Based Architecture), lo que permite separar responsabilidades y mantener un código más ordenado.

📌 Módulos Desarrollados
1️⃣ CRUD de Datos

Permite la gestión completa de registros mediante:

Crear nuevos registros

Listar registros almacenados

Editar información existente

Eliminar registros individuales

Eliminar todos los registros

Exportar datos en formato JSON

Los datos se almacenan en el navegador utilizando LocalStorage, simulando una base de datos local.

Campos del formulario:

Nombre completo

Documento

Correo electrónico

2️⃣ Actividad Callback

Se implementa el concepto de Callback en JavaScript.

Incluye:

Explicación teórica del concepto

Ejemplo práctico

Simulación de búsqueda de país

Uso de funciones como parámetros

Objetivo: Comprender cómo una función puede ejecutarse después de otra.

3️⃣ Actividad Promises

Se desarrolla el concepto de Promesas para el manejo de operaciones asíncronas.

Incluye:

Estados de una Promesa:

Pendiente (Pending)

Cumplida (Fulfilled)

Rechazada (Rejected)

Ejemplo práctico de verificación de la última letra de una palabra

Objetivo: Entender el flujo de ejecución asíncrona.

4️⃣ Actividad Async/Await

Se implementa Async/Await para simplificar el manejo de Promesas.

Incluye:

Función asíncrona

Uso de await

Ejemplo práctico para calcular el doble de un número

Objetivo: Mejorar la legibilidad del código asíncrono.

5️⃣ Actividad Destructuring

Se desarrolla el concepto de Destructuring en objetos.

Incluye:

Explicación teórica

Ejemplo con objeto Persona

Extracción de propiedades usando llaves {}

Objetivo: Comprender cómo extraer propiedades de objetos de manera simplificada.

▶️ Instrucciones de Ejecución

Este proyecto no requiere instalación de dependencias.

Clonar el repositorio:

git clone https://github.com/tuusuario/turepositorio.git

Abrir el proyecto en Visual Studio Code.

Ejecutar el archivo:

src/features/crud/index.html

Se recomienda utilizar la extensión Live Server para visualizar el proyecto correctamente.

🎯 Objetivo Académico

Aplicar conceptos fundamentales de JavaScript moderno mediante ejercicios prácticos que demuestran:

Manipulación del DOM

Programación asíncrona

Manejo de almacenamiento local

Organización modular del código

📸 Evidencias

Se adjuntan capturas de pantalla del funcionamiento de cada módulo:

CRUD de datos

Callback

Promises

Async/Await

Destructuring

📄 Conclusión

Este proyecto permitió reforzar conocimientos en JavaScript moderno, especialmente en el manejo de asincronía y estructuración modular del código, aplicando buenas prácticas de organización y diseño.
