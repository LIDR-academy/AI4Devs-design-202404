# Prompts

Creado con ChatGPT 3.5

**Prompt 1:** 

Actua como un product Owner experto y ayudame a construir 5 historias de usuario prioritarias relacionadas con los requerimientos de software del siguiente Sistema LTI que definimos previamente:

1. **Creación de la vacante**:
    - RF1: El Reclutador LTI debe poder crear nuevas vacantes ingresando detalles como título del puesto, descripción del trabajo, ubicación, requisitos de habilidades y experiencia requerida.
    - RF2: Debe haber un campo para establecer la fecha límite de solicitud.
    - RF3: El Recrutador LTI debe poder asignar responsabilidades a otros reclutadores o equipos para cada vacante creada.
2. **Publicación de vacante en la plataforma y redes sociales**:
    - RF4: El sistema debe permitir al Recrutador LTI publicar automáticamente las vacantes en la plataforma LTI y en las redes sociales asociadas.
    - RF5: Debe haber opciones para personalizar el contenido y el formato de las publicaciones en diferentes plataformas.
3. **Aceptación de vacantes por parte del candidato**:
    - RF6: Los candidatos deben poder buscar y aplicar a las vacantes publicadas en la plataforma LTI.
    - RF7: El sistema debe permitir a los candidatos aceptar las vacantes que se ajusten a su perfil mediante un proceso de solicitud en línea.
4. **Revisión de la vacante (filtro inicial)**:
    - RF8: El sistema debe permitir al Reclutador LTI revisar las aplicaciones recibidas y filtrar automáticamente los candidatos que cumplen con los requisitos básicos del perfil.
    - RF9: Debe haber herramientas de búsqueda y filtrado avanzadas para facilitar la revisión de las aplicaciones.
5. **Examen de conocimientos online para los candidatos que pasen el filtro inicial**:
    - RF10: El sistema debe permitir al Reclutador LTI enviar exámenes de conocimientos online a los candidatos que pasen el filtro inicial.
    - RF11: Debe haber opciones para programar y gestionar los exámenes de manera eficiente.
6. **Envío preliminar a la empresa de candidatos que cumplen el perfil**:
    - RF12: El sistema debe permitir al Reclutador LTI enviar una lista preliminar de candidatos seleccionados a la empresa para su revisión y aprobación.
    - RF13: Debe haber un proceso de revisión por parte de la empresa para validar los candidatos seleccionados antes de proceder con el siguiente paso.
7. **Agendamiento de entrevistas para candidatos con las empresas**:
    - RF14: El sistema debe facilitar el agendamiento de entrevistas entre los candidatos seleccionados y los representantes de la empresa.
    - RF15: Debe haber herramientas de calendarización integradas y opciones para gestionar las disponibilidades de los candidatos y los representantes de la empresa.
8. **Selección de candidatos seleccionados y cierre del proceso**:
    - RF16: Una vez completadas las entrevistas, el Reclutador LTI debe poder seleccionar a los candidatos finalistas y cerrar el proceso de contratación.
    - RF17: El sistema debe generar automáticamente documentos relevantes, como ofertas de trabajo, contratos y otras comunicaciones para finalizar el proceso de contratación.

Importante en las historias de usuario, garantizar esta estructura de referencia:

- Estructura basica de una User Story
- Formato estándar: "Como [tipo de usuario], quiero [realizar una acción] para [obtener un beneficio]".
- Descripción: Una descripción concisa y en lenguaje natural de la funcionalidad que el usuario desea.
- Criterios de Aceptación: Condiciones específicas que deben cumplirse para considerar la User Story como "terminada", éstos deberian de seguir un formato similar a “Dado que” [contexto inicial], "cuando” [acción realizada], “entonces” [resultado esperado].
- Notas adicionales:  Notas que puedan ayudar al desarrollo de la historia
Tareas: Lista de tareas y subtareas para que esta historia pueda ser completada

Ejemplos que podrían  servir de contexto es:

1. Desarrollo de Productos:"Como gerente de producto, quiero una manera en que los miembros del equipo puedan entender cómo las tareas individuales contribuyen a los objetivos, para que puedan priorizar mejor su trabajo."
2. Experiencia del Cliente:"Como cliente recurrente, espero que mi información quede guardada para crear una experiencia de pago más fluida, para que pueda completar mis compras de manera rápida y sencilla."
3. Aplicación Móvil:"Como usuario frecuente de la aplicación, quiero una forma de simplificar la información relevante de la manera más rápida posible, para poder acceder a la información que necesito de manera eficiente."

**Prompt 2:**

Para cerrar el proceso de selección , agrega las historias de usuario necesarias para que garantizar que el sistema LTI notifique los candidatos seleccionados a las empresas. Involucra adicionalmente el rol de empresario ****

**Prompt 3:**

Bien, ahora con las 7 historias de usuario definidas y las funcionalidades vamos a crear el producto backlog del sistema LTI

**Prompt 4:**

Bien, ahora con las 7 historias de usuario definidas y las funcionalidades vamos a crear el producto backlog del sistema LTI.Considera el backlog de producto creado anteriormente y estima por cada item en el backlog (genera una tabla markdown). Importante tener en cuenta los siguientes aspectos :

1.Impacto en el usuario y valor del negocio.
2.Urgencia basada en tendencias del mercado y feedback de usuarios.
3.Complejidad y esfuerzo estimado de implementación.
4.Riesgos y dependencias entre tareas.

Al final de la tabla, dame una explicación detallada justificando el porque de las estimaciones y los criterios que se tuvieron en cuenta para dicho propósito 

**Prompt 5:**

Ajusta los riesgos. Recuerda que se catalogan como bajos, medios y altos

**Prompt 6:**

Examina la tabla que enumera las historias de usuario del backlog junto con sus prioridades, considerando varios criterios. Elabora una nueva tabla que incluya todos los tickets necesarios para completar el backlog, y proporciona una estimación de puntos para cada uno. Esta tabla debe contener tres columnas: "ID del Ticket", "Descripción" y "Estimación de Puntos". Por último, describe el proceso detallado que utilizaste para la estimación de puntos.

**Prompt 7:**

Ahora ayudame con una descripción detallada de cada Ticket para poder asignarlo al equipo de desarrollo en formato markdown. La estructura que requiero para este propósito  es la siguiente:

- Título:
- Descripción:
- Criterios de Aceptación:
- Estimación:
- Asignado a:
- Etiquetas:
- Comentarios:
- Enlaces:
- Historial de Cambios:

Finalmente considera la tabla donde se detallan las historias de usuario del backlog y sus prioridades en función de varios factores y genera una tabla con todos los tickets de trabajo necesarios para completar el backlog, y añade tu sugerencia de estimación de puntos y al final justifica el porque se dio la estimación . Tener en cuenta ademas:

- El sprint es de 10 días  (2 semanas donde no se incluyen sábados  y domingos)
- El equipo cuenta con un desarrollador de frontend Junior con disponibilidad total de tiempo para el proyecto (40 horas por semana - tope de jornada laboral)
- El equipo cuenta con un desarrollador de Backedn MID con disponibilidad de medio tiempo para el proyecto (20 horas por semana)