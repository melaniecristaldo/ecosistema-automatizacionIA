# Ecosistema de Automatización IA

## Descripción

Sistema de automatización inteligente para la gestión de consultas de clientes.

El flujo integra Gmail, OpenAI y Airtable para recibir solicitudes, analizarlas mediante IA, estructurar la información y almacenarla automáticamente.

## Flujo de automatización

1. Gmail recibe el correo del cliente.
2. OpenAI analiza el contenido y genera una respuesta estructurada.
3. JSON Parse organiza los datos obtenidos.
4. Airtable almacena la información del cliente.
5. El sistema asigna estado y permite realizar seguimiento.
6. Se contemplan rutas de error y revisión humana cuando es necesario.

## Integraciones

- Gmail
- OpenAI
- JSON
- Airtable
- Make

## Datos gestionados

El sistema procesa:

- Nombre
- Email
- Teléfono
- Intención
- Solicitud
- Resumen
- Categoría
- Prioridad
- Acción recomendada
- Estado

## Seguridad y resiliencia

El flujo contempla validación de datos, control de errores y puntos de revisión humana para los casos que requieren intervención.

No se incluyen claves API, contraseñas ni credenciales sensibles dentro del repositorio.

## Optimización de costos

Se prioriza el uso eficiente de modelos de IA según la complejidad de cada tarea y se busca minimizar el consumo innecesario de tokens y operaciones.

## Documentación

Este repositorio contiene la documentación y evidencias necesarias para la entrega final:

- Diagrama de arquitectura
- Documentación de estructuras de datos
- Matriz comparativa de costos
- Documentación de seguridad y resiliencia
- Dashboard de control
- Blueprint del escenario de Make
- Capturas de evidencia del funcionamiento

## Proyecto final

Proyecto realizado como entrega final del curso de AI Automation.

**Estado:** Proyecto realizado y flujo funcional.

DASHBOARD DE CONTROL {VER DASHBOARD DEL CONTROL} https://airtable.com/appyejfCbzxaMhaM5/shrI8wzKq0raCAV0r
