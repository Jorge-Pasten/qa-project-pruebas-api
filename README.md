# Pruebas de API para Urban Grocers

## Descripción del Proyecto

Este proyecto forma parte del cuarto sprint del programa de formación en QA Engineer de TripleTen. El objetivo principal fue analizar, diseñar y ejecutar pruebas para la nueva funcionalidad de la API de *Urban Grocers*.

*Urban Grocers* es una aplicación web que permite a los usuarios registrados realizar pedidos de productos comestibles a domicilio. En esta fase del proyecto, el enfoque estuvo en validar la funcionalidad de la gestión de kits de comestibles y la disponibilidad del servicio de entrega "Order and Go".

## Objetivos del Proyecto

- Analizar y descomponer los requisitos de la nueva funcionalidad de la API.
- Diseñar una lista de comprobación para evaluar los nuevos endpoints.
- Ejecutar pruebas en **Postman** para verificar el correcto funcionamiento de la API.
- Documentar los hallazgos y reportar errores en **Jira**.
- Elaborar un informe de pruebas con los resultados obtenidos.

## Actividades Realizadas

### 1. Análisis de Requisitos y Documentación de la API

Se revisaron los requisitos del backend y la documentación en **ApiDoc** para comprender el comportamiento esperado de los nuevos endpoints. Se identificaron los posibles casos de prueba y las validaciones necesarias.

### 2. Diseño de la Lista de Comprobación

Se elaboró una lista de comprobación en **Google Sheets** para cubrir los siguientes aspectos:

- Validación del límite de productos en los kits de comestibles.
- Verificación de la correcta respuesta de error `400 Bad Request` al exceder el límite.
- Cálculo correcto del precio del servicio de entrega "Order and Go".
- Confirmación de la disponibilidad del servicio de entrega.

### 3. Ejecución de Pruebas en Postman

Se realizaron pruebas manuales enviando solicitudes a la API a través de **Postman**:

- Pruebas con datos válidos e inválidos.
- Evaluación de respuestas HTTP y mensajes de error.
- Simulación de diferentes escenarios para los endpoints implementados.

### 4. Documentación de Resultados y Reporte de Errores

- Se documentaron los resultados en una hoja de cálculo de **Google Sheets**.
- Se reportaron errores y posibles mejoras en **Jira**.
- Se redactó un informe de pruebas detallando el estado de la funcionalidad evaluada.

Consulta los resultados dando clic [aquí](https://docs.google.com/spreadsheets/d/1_Qyzx2WAQzQs0djtE5j3p-kthi0Fw2ZR/edit?usp=sharing&ouid=100155335199930450797&rtpof=true&sd=true).

## Conclusión

Este proyecto permitió aplicar metodologías de análisis de requisitos, ejecución de pruebas de API y documentación de QA. La experiencia adquirida refuerza la importancia de validar la lógica de negocio y el manejo de errores en sistemas basados en microservicios.

---
📌 **Autor:** Jorge Luis Pasten Peña
📅 **Sprint:** 4
🚀 **Estado:** Finalizado
