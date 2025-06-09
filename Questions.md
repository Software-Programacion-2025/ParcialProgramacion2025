# Preguntas de Evaluación

## Comprensión del Proyecto de Flask y REST API

1. **Arquitectura y Estructura del Proyecto (2 puntos)**

   - Explique la diferencia entre las rutas definidas con `@app.route()` y las creadas con `api.add_resource()` en este proyecto.
   - Porque es beneficio la modularizacion de entidiades.
2. **REST API y Recursos (2 puntos)**

   - En la clase `Task`, se implementan los métodos GET y POST. ¿Qué otros métodos HTTP se podrían implementar y para qué funcionamiento?
   - Explique cómo se maneja la relación entre usuarios y tareas en la API. ¿Cómo se podría mejorar este diseño?
3. **Templates y Frontend (2 puntos)**

   - ¿Cómo se comunican las rutas de Flask con los templates? Explique el flujo de datos desde la base de datos hasta la vista final.
   - En el template `tasks.html`, ¿cómo funciona el filtrado de tareas y cómo se podría mejorar la experiencia del usuario?
4. **Seguridad y Mejores Prácticas (2 puntos)**

   - El proyecto actual no implementa autenticación. ¿Qué problemas de seguridad podría tener ?
