PROBLEMATICA (ENUNCIADO)

En muchas instituciones educativas, los docentes necesitan calcular y registrar el promedio final de sus estudiantes de manera rápida y organizada. 
Sin embargo, en algunos casos este proceso se realiza manualmente o utilizando herramientas poco prácticas como calculadoras físicas o anotaciones en papel, 
lo que puede provocar errores en los cálculos, pérdida de información o retrasos en la entrega de resultados.

Además, cuando se manejan varios estudiantes, se vuelve complicado llevar un control acumulado de promedios y datos sin un sistema que automatice el proceso.




Sectores a los que va enfocada la solución

La solución propuesta mediante una página web interactiva está enfocada en los siguientes sectores:

 Sector educativo (escuelas, colegios y universidades)

 Docentes y profesores

 Instituciones académicas y centros de formación técnica

 Departamentos administrativos encargados del control de notas



 PREGUNTAS

1. ¿Qué valor agregado tiene el uso de Web Components en su proyecto?

El uso de Web Components permite encapsular funcionalidades específicas dentro de componentes reutilizables y personalizados. En nuestro proyecto, se creó un componente personalizado para mostrar los registros de estudiantes y sus promedios.

El valor agregado es que:

Permite reutilizar código fácilmente.

Mejora la organización del proyecto.

Separa la lógica de la interfaz principal.

Hace el código más modular y mantenible.

Facilita futuras mejoras sin afectar toda la aplicación.


2. ¿De qué forma manipularon los datos sin recargar la página?

Los datos fueron manipulados utilizando JavaScript mediante la captura de eventos del formulario (submit) y el uso de métodos como:

addEventListener

preventDefault()

createElement()

appendChild()

innerHTML

Cuando el usuario presiona el botón guardar, se evita la recarga de la página usando event.preventDefault(). Luego,
los datos ingresados se procesan y se agregan dinámicamente al DOM, mostrando el resultado inmediatamente en pantalla.



3. ¿De qué forma validaron las entradas de datos?

Las entradas fueron validadas de dos formas:

Validación HTML:

Uso del atributo required en los campos obligatorios (nombre y carrera).

Validación con JavaScript:

Se verificó que los campos obligatorios no estuvieran vacíos.

Se comprobó que las notas ingresadas fueran valores numéricos válidos.

Se mostró un mensaje de error cuando los datos no cumplían los requisitos.



4. ¿Cómo manejaría la escalabilidad futura en su página?

Para manejar la escalabilidad futura del proyecto se podrían implementar las siguientes mejoras:

Conectar la aplicación a una base de datos para almacenar información permanentemente.

Implementar un backend con tecnologías como Node.js.

Separar el proyecto en módulos.

Agregar autenticación de usuarios.

Convertir la aplicación en una SPA (Single Page Application).

Utilizar frameworks modernos como React, Vue o Angular.

Implementar almacenamiento en la nube.
