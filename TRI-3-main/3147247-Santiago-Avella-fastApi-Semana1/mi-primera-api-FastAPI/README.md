
## 💻 Guía de Inicio Rápido

### 1\. Configuración del Entorno

Para empezar, asegúrate de tener las dependencias necesarias.

```bash
pip install -r requirements.txt
```

### 2\. Ejecución de la Aplicación

Inicia la aplicación para probarla localmente. El comando `--reload` reinicia el servidor automáticamente con cada cambio en el código.

```bash
uvicorn main:app --reload
```

-----

## ☁️ Subir a GitHub

Sigue estos pasos para versionar y publicar tu proyecto en GitHub.

### 1\. Inicialización

Crea un nuevo repositorio en GitHub (ej. `tu-apellido-primera-api`). Luego, inicializa Git en tu proyecto local.

```bash
git init
```

### 2\. Adición y Confirmación

Agrega todos los archivos a la "staging area" y luego confirma los cambios con un mensaje claro.

```bash
git add .
git commit -m "Mi primera API FastAPI"
```

### 3\. Publicación

Sube tu código al repositorio remoto en GitHub.

```bash
git push
```

-----

## ✅ Criterios de Éxito y Verificación

### Criterios de Éxito

  - **Código en GitHub:** Tu repositorio debe contener un mínimo de tres archivos.
  - **`README` visible:** El archivo `README.md` debe mostrarse correctamente en la página principal de tu repositorio de GitHub.

### Verificación de la API

  - **Funcionalidad:** La API debe tener de tres a cuatro **endpoints** que funcionen correctamente.
  - **Documentación:** La página de documentación interactiva en `/docs` debe estar accesible y mostrar tus **endpoints**.
  - **Sensación de Logro:** ¡Debes sentirte satisfecho con lo que has creado\! 🎉

-----

## 💡 Solución de Problemas Comunes

Si encuentras dificultades, no te frustres. Estos son problemas comunes y sus soluciones rápidas:

  - **Git no funciona:** Levanta la mano, el instructor te asistirá.
  - **Endpoints no responden:** Revisa la sintaxis de tu código en el archivo principal.
  - **`/docs` no se carga:** Intenta reiniciar el servidor **uvicorn**.

Si la ayuda de un compañero no funciona, levanta la mano y pide ayuda al instructor. Enfócate en los aspectos que sí funcionan para mantener el impulso.

-----

## 📈 Autoevaluación Rápida

Responde honestamente para evaluar tu progreso:

  - **¿Lograste crear tu primera API?** ✅ Sí / ❌ No
  - **¿Está funcionando `/docs`?** ✅ Sí / ❌ No
  - **¿Subiste tu código a GitHub?** ✅ Sí / ❌ No

Si respondiste **"Sí" a 2 o más preguntas, ¡Excelente trabajo\!** Estás listo para continuar.

-----

## 🗺️ Próximos Pasos: Preparación para la Semana 2

Con los fundamentos ya establecidos, la próxima semana exploraremos temas más avanzados que te permitirán construir aplicaciones más robustas:

  - **Python Type Hints:** Profundizaremos en cómo las sugerencias de tipo mejoran la claridad y el mantenimiento del código.
  - **Pydantic Models:** Aprenderás a usar modelos de datos para validar y estructurar la información.
  - **Endpoints Adicionales:** Implementaremos **endpoints** con métodos `POST`, `PUT` y `DELETE` para operaciones completas de gestión de datos.

¡Felicidades por completar tu primera semana de **FastAPI**\! 🚀