

## 🚀 Mi API FastAPI - Semana 2

### 📋 Visión General

Esta versión de la API incorpora **validación automática de datos** y la implementación de **type hints**, elevando la calidad del código y la funcionalidad del proyecto.

-----

### 🌟 Nuevas Funcionalidades

Las mejoras de esta semana incluyen:

  - **Type Hints:** Integración de **sugerencias de tipo** en todas las funciones, mejorando la legibilidad y el mantenimiento del código.
  - **Validación con Pydantic:** Uso de **Pydantic** para validar automáticamente los datos de entrada, asegurando la integridad de la información recibida por la API.
  - **Manejo de Endpoints:** Implementación de un **endpoint** `POST` para la creación de datos, además de **parámetros de ruta** (ej. `/products/{id}`) y **parámetros de consulta** para búsquedas más flexibles.

-----

### 💻 Instrucciones de Uso

#### Ejecución Local

Para iniciar la API, asegúrate de tener las dependencias instaladas y luego ejecuta el servidor **Uvicorn** con el modo de recarga activado.

```bash
pip install fastapi pydantic uvicorn
uvicorn main:app --reload
```

#### Subir a GitHub

Utiliza los siguientes comandos en tu terminal para versionar y publicar tus cambios en el repositorio de GitHub.

```bash
git add .
git commit -m "Semana 2: API con Pydantic y Type Hints"
git push
```

-----

### 🔑 Puntos Clave del Proyecto

  - **Operaciones CRUD:** La API ahora soporta las operaciones básicas de **creación (POST), lectura (GET), actualización (PUT) y eliminación (DELETE)**.
  - **Manejo de Errores:** Se implementó `HTTPException` para devolver respuestas claras y estructuradas cuando los datos solicitados no se encuentran.
  - **Almacenamiento Temporal:** Los datos se gestionan en una lista en memoria, lo que simula de forma sencilla el funcionamiento de una base de datos para este proyecto de aprendizaje.
