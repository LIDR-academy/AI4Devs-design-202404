# Producto Backlog LTI-DV

### **Historia de Usuario 1: Creación de la vacante**

**Como Reclutador LTI, quiero poder crear nuevas vacantes ingresando detalles como título del puesto, descripción del trabajo, ubicación, requisitos de habilidades y experiencia requerida, para iniciar el proceso de reclutamiento de manera efectiva.**

### **Criterios de Aceptación:**

- Dado que estoy autenticado en el sistema LTI, puedo acceder a la función de creación de vacantes desde el panel de control.
- Puedo completar un formulario que incluya campos para el título del puesto, descripción del trabajo, ubicación, requisitos de habilidades y experiencia requerida.
- Una vez completado el formulario, puedo guardar la vacante en el sistema para su revisión y publicación.
- Debo recibir una confirmación de que la vacante se ha creado correctamente y está lista para su revisión.

### **Notas adicionales:**

- El formulario de creación de vacantes debe ser intuitivo y fácil de usar para facilitar la entrada de datos por parte del reclutador.

### **Tareas:**

1. Diseñar la interfaz de usuario para el formulario de creación de vacantes.
2. Implementar la funcionalidad para guardar y validar los datos ingresados en el formulario.
3. Configurar la confirmación de creación de vacantes y el proceso de guardado en la base de datos.

### **Historia de Usuario 2: Publicación de vacante en la plataforma y redes sociales**

**Como Reclutador LTI, quiero poder publicar automáticamente las vacantes en la plataforma LTI y en las redes sociales asociadas, para maximizar la visibilidad y el alcance de las oportunidades de trabajo.**

### **Criterios de Aceptación:**

- Después de crear una vacante, tengo la opción de publicarla en la plataforma LTI y en redes sociales como LinkedIn, Twitter y Facebook.
- Puedo seleccionar las redes sociales en las que deseo publicar la vacante y personalizar el contenido y el formato de las publicaciones.
- Una vez publicada, la vacante debe aparecer de manera destacada en la plataforma LTI y en las redes sociales seleccionadas.
- Debo recibir una confirmación de que la vacante se ha publicado correctamente en cada canal.

### **Notas adicionales:**

- Se requerirá una integración con las APIs de las redes sociales seleccionadas para publicar automáticamente las vacantes.

### **Tareas:**

1. Desarrollar la integración con las APIs de las redes sociales para la publicación automática de vacantes.
2. Diseñar la interfaz de usuario para seleccionar las redes sociales y personalizar el contenido de las publicaciones.
3. Implementar la lógica para la publicación y confirmación de vacantes en cada canal seleccionado.

### **Historia de Usuario 3: Aceptación de vacantes por parte del candidato**

**Como Candidato, quiero poder buscar y aplicar a las vacantes publicadas en la plataforma LTI, para acceder a oportunidades laborales relevantes y aplicar fácilmente a ellas.**

### **Criterios de Aceptación:**

- Desde la página principal de la plataforma LTI, puedo acceder a una sección de vacantes disponibles.
- Puedo filtrar las vacantes por título, ubicación y tipo de trabajo para encontrar las oportunidades que se ajusten a mi perfil.
- Al seleccionar una vacante, puedo ver los detalles del trabajo y aplicar a ella mediante un proceso de solicitud en línea.
- Debo recibir una confirmación de que mi solicitud se ha enviado correctamente.

### **Notas adicionales:**

- El proceso de solicitud en línea debe ser simplificado y requerir la menor cantidad de pasos posibles para completarlo.

### **Tareas:**

1. Diseñar la página de inicio de la plataforma LTI para mostrar las vacantes disponibles.
2. Implementar los filtros de búsqueda para las vacantes basados en título, ubicación y tipo de trabajo.
3. Desarrollar el proceso de solicitud en línea con un formulario para recopilar la información del candidato.
4. Configurar la confirmación de envío de la solicitud y su almacenamiento en la base de datos.

### **Historia de Usuario 4: Revisión de la vacante (filtro inicial)**

**Como Reclutador LTI, quiero poder revisar las aplicaciones recibidas y filtrar automáticamente los candidatos que cumplen con los requisitos básicos del perfil, para agilizar el proceso de selección de candidatos.**

### **Criterios de Aceptación:**

- Después de recibir aplicaciones para una vacante, puedo acceder a una lista de candidatos y revisar sus perfiles individualmente.
- Puedo aplicar filtros automáticos para identificar rápidamente a los candidatos que cumplen con los requisitos básicos del perfil, como la experiencia laboral y las habilidades requeridas.
- Debo poder ajustar manualmente los criterios de filtrado y revisar las aplicaciones que no cumplen con los requisitos automáticos.
- Una vez completada la revisión, puedo guardar una lista de candidatos seleccionados para proceder con la siguiente etapa del proceso de selección.

### **Notas adicionales:**

- Los filtros automáticos deben ser configurables y ajustables según las necesidades específicas de cada vacante.

### **Tareas:**

1. Diseñar la interfaz de usuario para la lista de candidatos y los controles de filtro automático.
2. Implementar la lógica para aplicar filtros automáticos basados en los requisitos de la vacante.
3. Desarrollar la funcionalidad para ajustar manualmente los criterios de filtrado y revisar las aplicaciones.
4. Configurar la opción de guardar una lista de candidatos seleccionados y almacenarla en la base de datos.

### **Historia de Usuario 5: Examen de conocimientos online para los candidatos que pasen el filtro inicial**

**Como Reclutador LTI, quiero poder enviar exámenes de conocimientos online a los candidatos que pasen el filtro inicial, para evaluar sus habilidades y competencias específicas requeridas para el puesto.**

### **Criterios de Aceptación:**

- Después de revisar las aplicaciones y seleccionar a los candidatos que cumplen con los requisitos básicos, puedo programar y enviar exámenes de conocimientos específicos a través del sistema LTI.
- Puedo seleccionar el tipo de examen y las preguntas a incluir, así como establecer la fecha límite para su completación.
- Los candidatos reciben notificaciones sobre los exámenes asignados y pueden acceder a ellos desde su cuenta en la plataforma LTI.
- Debo recibir una confirmación de que los exámenes se han enviado correctamente y están disponibles para los candidatos.

### **Notas adicionales:**

- Se requerirá una integración con una plataforma de pruebas en línea para crear y administrar los exámenes.

### **Tareas:**

1. Desarrollar la integración con la plataforma de pruebas en línea para programar y enviar exámenes.
2. Diseñar la interfaz de usuario para la selección de tipo de examen, preguntas y fecha límite.
3. Implementar la lógica para enviar notificaciones a los candidatos sobre los exámenes asignados.
4. Configurar la confirmación de envío de exámenes y su disponibilidad para los candidatos.

### **Historia de Usuario 6: Notificación de candidatos seleccionados a las empresas**

**Como Reclutador LTI, quiero poder notificar a las empresas sobre los candidatos seleccionados para su revisión y aprobación final, para cerrar el proceso de selección de manera eficiente.**

### **Criterios de Aceptación:**

- Dado que he completado la revisión de los candidatos y seleccionado a los finalistas, puedo generar una lista de candidatos seleccionados para cada vacante.
- Puedo enviar automáticamente esta lista de candidatos seleccionados a las empresas asociadas a través del sistema LTI.
- Las empresas reciben notificaciones sobre los candidatos seleccionados y pueden revisar sus perfiles en el sistema para tomar una decisión final.
- Las empresas pueden aprobar o rechazar a los candidatos seleccionados, lo que actualiza su estado en el sistema y finaliza el proceso de selección para esa vacante.

### **Notas adicionales:**

- Se requerirá una integración con el sistema de notificaciones para enviar automáticamente los mensajes a las empresas.
- La lista de candidatos seleccionados debe incluir información detallada sobre cada candidato, como su perfil, experiencia y habilidades relevantes.

### **Tareas:**

1. Implementar la funcionalidad para generar la lista de candidatos seleccionados.
2. Desarrollar el mecanismo de envío automático de notificaciones a las empresas.
3. Diseñar la interfaz de usuario para que las empresas revisen y respondan a las notificaciones.

### **Historia de Usuario 7: Confirmación de selección por parte de las empresas**

**Como Empresario, quiero poder revisar los perfiles de los candidatos seleccionados y confirmar su selección para avanzar en el proceso de contratación, para asegurarme de que estoy tomando decisiones informadas y contratando al mejor talento disponible.**

### **Criterios de Aceptación:**

- Dado que he recibido la lista de candidatos seleccionados, puedo acceder al sistema LTI y revisar los perfiles de cada candidato.
- Puedo evaluar las habilidades, experiencia y ajuste cultural de cada candidato para determinar si son adecuados para el puesto.
- Para cada candidato seleccionado, puedo confirmar su selección y avanzar en el proceso de contratación.
- Si decido no seleccionar a un candidato, puedo rechazar su selección y proporcionar comentarios opcionales sobre mi decisión.

### **Notas adicionales:**

- Se debe proporcionar una funcionalidad de retroalimentación para que las empresas puedan expresar sus razones para rechazar a un candidato.

### **Tareas:**

1. Desarrollar la funcionalidad para que las empresas revisen los perfiles de los candidatos seleccionados.
2. Implementar la capacidad de confirmar o rechazar la selección de cada candidato.
3. Crear un sistema de registro de comentarios de las empresas sobre los candidatos rechazados.

# **PRODUCT BACKLOG**

| Item | Impacto en el usuario y valor del negocio | Urgencia | Complejidad y esfuerzo estimado | Riesgos y dependencias |
| --- | --- | --- | --- | --- |
| Creación de la vacante | Alta | Alta | Media | Bajo |
| Publicación de vacante en la plataforma y redes sociales | Alta | Alta | Alta | Medio |
| Aceptación de vacantes por parte del candidato | Alta | Media | Alta | Medio |
| Revisión de la vacante (filtro inicial) | Alta | Alta | Alta | Bajo |
| Envío preliminar a la empresa de candidatos que cumplen el perfil | Alta | Alta | Media | Medio |
| Agendamiento de entrevistas para candidatos con las empresas | Alta | Alta | Alta | Alto |
| Examen de conocimientos online para los candidatos que pasen el filtro inicial | Alta | Media | Media | Bajo |

**Explicación detallada de las estimaciones:**

- **Impacto en el usuario y valor del negocio:** Se estimó el impacto en función de cómo cada funcionalidad afecta a los usuarios y contribuye al valor del negocio. Aquellas funcionalidades que tienen un impacto directo en la experiencia del usuario y en los objetivos comerciales fueron calificadas como de alta importancia.
- **Urgencia:** La urgencia se basó en las tendencias del mercado y el feedback de los usuarios. Funcionalidades que abordan necesidades críticas del mercado o solicitudes frecuentes de los usuarios fueron consideradas como de alta urgencia.
- **Complejidad y esfuerzo estimado de implementación:** Se evaluó la complejidad y el esfuerzo requerido para implementar cada funcionalidad, considerando los aspectos técnicos, el diseño de la interfaz de usuario y la integración con sistemas externos. Funcionalidades que requieren una mayor cantidad de trabajo fueron calificadas como de alta complejidad.
- **Riesgos y dependencias:** Se identificaron posibles riesgos y dependencias entre tareas que podrían afectar la implementación de cada funcionalidad. Aquellas funcionalidades con riesgos potenciales o dependencias críticas fueron calificadas como de alta prioridad para abordar.

# Detalle del Ticket

### 

### Ticket 1

**Título:** Implementar la creación de la vacante

**Descripción:** Esta tarea implica desarrollar la funcionalidad que permitirá a los reclutadores LTI crear nuevas vacantes ingresando detalles como título del puesto, descripción del trabajo, ubicación, requisitos de habilidades y experiencia requerida. También incluirá la implementación de un campo para establecer la fecha límite de solicitud y la capacidad de asignar responsabilidades a otros reclutadores o equipos para cada vacante creada.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden crear una nueva vacante con título, descripción, ubicación, requisitos y fecha límite.
- Los reclutadores pueden asignar responsabilidades a otros reclutadores o equipos para cada vacante creada.

**Estimación:** 8 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Creación de Vacante, Reclutadores, Funcionalidad

**Comentarios:** Esta funcionalidad es fundamental para el sistema ya que permite a los reclutadores LTI iniciar el proceso de reclutamiento.

**Enlaces:** [RF1], [RF2], [RF3]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 2

**Título:** Implementar la publicación automática en redes sociales

**Descripción:** Esta tarea consiste en desarrollar la funcionalidad que permitirá al sistema LTI publicar automáticamente las vacantes en la plataforma LTI y en las redes sociales asociadas. Se deben proporcionar opciones para personalizar el contenido y el formato de las publicaciones en diferentes plataformas.

**Criterios de Aceptación:**

- Las vacantes creadas se publican automáticamente en la plataforma LTI y en las redes sociales asociadas.
- Se pueden personalizar el contenido y el formato de las publicaciones en diferentes plataformas.

**Estimación:** 5 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Publicación en Redes Sociales, Automatización, Personalización

**Comentarios:** Esta funcionalidad mejora la visibilidad de las vacantes y atrae a más candidatos al sistema.

**Enlaces:** [RF4], [RF5]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 3

**Título:** Implementar la aceptación de vacantes por parte del candidato

**Descripción:** Esta tarea implica desarrollar la funcionalidad que permitirá a los candidatos buscar y aplicar a las vacantes publicadas en la plataforma LTI. También incluirá la implementación de un proceso de solicitud en línea que permita a los candidatos aceptar las vacantes que se ajusten a su perfil.

**Criterios de Aceptación:**

- Los candidatos pueden buscar y aplicar a las vacantes publicadas en la plataforma LTI.
- Los candidatos pueden aceptar las vacantes que se ajusten a su perfil mediante un proceso de solicitud en línea.

**Estimación:** 7 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Aceptación de Vacantes, Candidatos, Proceso de Solicitud

**Comentarios:** Esta funcionalidad mejora la experiencia del candidato y facilita el proceso de reclutamiento.

**Enlaces:** [RF6], [RF7]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 4

**Título:** Implementar el filtro inicial de revisión de vacantes

**Descripción:** Esta tarea consiste en desarrollar la funcionalidad que permitirá a los reclutadores LTI revisar las aplicaciones recibidas y filtrar automáticamente los candidatos que cumplen con los requisitos básicos del perfil. Se deben proporcionar herramientas de búsqueda y filtrado avanzadas para facilitar la revisión de las aplicaciones.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden revisar las aplicaciones recibidas.
- El sistema filtra automáticamente los candidatos que cumplen con los requisitos básicos del perfil.
- Se proporcionan herramientas de búsqueda y filtrado avanzadas.

**Estimación:** 6 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Filtro de Aplicaciones, Reclutadores, Búsqueda Avanzada

**Comentarios:** Esta funcionalidad agiliza el proceso de revisión de aplicaciones y ayuda a identificar candidatos calificados.

**Enlaces:** [RF8], [RF9]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 5

**Título:** Implementar exámenes de conocimientos online para candidatos

**Descripción:** Esta tarea implica desarrollar la funcionalidad que permitirá a los reclutadores LTI enviar exámenes de conocimientos online a los candidatos que pasen el filtro inicial. Se deben proporcionar opciones para programar y gestionar los exámenes de manera eficiente.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden enviar exámenes de conocimientos online a los candidatos.
- Se pueden programar y gestionar los exámenes de manera eficiente.

**Estimación:** 4 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Exámenes Online, Reclutadores, Gestión de Exámenes

**Comentarios:** Esta funcionalidad ayuda a evaluar las habilidades de los candidatos de manera efectiva y eficiente.

**Enlaces:** [RF10], [RF11]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 6

**Título:** Implementar el envío preliminar de candidatos a las empresas

**Descripción:** Esta tarea consiste en desarrollar la funcionalidad que permitirá a los reclutadores LTI enviar una lista preliminar de candidatos seleccionados a las empresas para su revisión y aprobación. También incluirá la implementación de un proceso de revisión por parte de la empresa para validar los candidatos seleccionados antes de proceder con el siguiente paso.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden enviar una lista preliminar de candidatos seleccionados a las empresas.
- Las empresas pueden revisar y validar los candidatos seleccionados.

**Estimación:** 7 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Envío Preliminar, Reclutadores, Validación de Candidatos

**Comentarios:** Esta funcionalidad facilita la comunicación entre los reclutadores y las empresas, agilizando el proceso de selección.

**Enlaces:** [RF12], [RF13]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 7

**Título:** Implementar el agendamiento de entrevistas para candidatos con las empresas

**Descripción:** Esta tarea implica desarrollar la funcionalidad que permitirá al sistema facilitar el agendamiento de entrevistas entre los candidatos seleccionados y los representantes de la empresa. Se deben proporcionar herramientas de calendarización integradas y opciones para gestionar las disponibilidades de los candidatos y los representantes de la empresa.

**Criterios de Aceptación:**

- El sistema facilita el agendamiento de entrevistas entre los candidatos seleccionados y los representantes de la empresa.
- Se proporcionan herramientas de calendarización integradas.
- Se pueden gestionar las disponibilidades de los candidatos y los representantes de la empresa.

**Estimación:** 6 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Agendamiento de Entrevistas, Calendarización, Gestión de Disponibilidad

**Comentarios:** Esta funcionalidad simplifica el proceso de coordinación de entrevistas y mejora la experiencia tanto para candidatos como para empresas.

**Enlaces:** [RF14], [RF15]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 8

**Título:** Implementar la selección de candidatos finalistas y cierre del proceso

**Descripción:** Esta tarea consiste en desarrollar la funcionalidad que permitirá al reclutador LTI seleccionar a los candidatos finalistas y cerrar el proceso de contratación una vez completadas las entrevistas. El sistema debe generar automáticamente documentos relevantes, como ofertas de trabajo, contratos y otras comunicaciones para finalizar el proceso de contratación.

**Criterios de Aceptación:**

- El reclutador LTI puede seleccionar a los candidatos finalistas.
- El proceso de contratación se cierra una vez completadas las entrevistas.
- El sistema genera automáticamente documentos relevantes para finalizar el proceso de contratación.

**Estimación:** 8 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Selección de Candidatos, Cierre de Proceso, Generación de Documentos

**Comentarios:** Esta funcionalidad concluye el proceso de reclutamiento y garantiza una finalización eficiente del mismo.

**Enlaces:** [RF16], [RF17]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 9

**Título:** Implementar notificaciones a candidatos seleccionados

**Descripción:** Esta tarea implica desarrollar la funcionalidad que permitirá al sistema LTI notificar a los candidatos seleccionados una vez que han sido aceptados por la empresa. Las notificaciones deben incluir detalles sobre el estado de su aplicación y los próximos pasos en el proceso de contratación.

**Criterios de Aceptación:**

- El sistema envía notificaciones a los candidatos seleccionados una vez que han sido aceptados por la empresa.
- Las notificaciones incluyen detalles sobre el estado de su aplicación y los próximos pasos en el proceso de contratación.

**Estimación:** 5 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Notificaciones, Candidatos, Proceso de Contratación

**Comentarios:** Esta funcionalidad mantiene a los candidatos informados sobre su estado en el proceso de contratación, mejorando la comunicación y la experiencia del usuario.

**Enlaces:** [RF18], [RF19]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 10

**Título:** Implementar notificaciones a empresas sobre candidatos seleccionados

**Descripción:** Esta tarea consiste en desarrollar la funcionalidad que permitirá al sistema LTI notificar a las empresas una vez que los candidatos han sido seleccionados y aceptados en el proceso de contratación. Las notificaciones deben incluir detalles sobre los candidatos seleccionados y los próximos pasos en el proceso.

**Criterios de Aceptación:**

- El sistema envía notificaciones a las empresas una vez que los candidatos han sido seleccionados y aceptados en el proceso de contratación.
- Las notificaciones incluyen detalles sobre los candidatos seleccionados y los próximos pasos en el proceso.

**Estimación:** 6 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Notificaciones, Empresas, Proceso de Contratación

**Comentarios:** Esta funcionalidad mantiene a las empresas informadas sobre el estado de sus solicitudes de contratación, mejorando la transparencia y la eficiencia del proceso.

**Enlaces:** [RF20], [RF21]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 11

**Título:** Implementar panel de control para reclutadores

**Descripción:** Esta tarea implica desarrollar un panel de control para los reclutadores LTI que les permita gestionar y supervisar todas las actividades relacionadas con el proceso de reclutamiento. El panel de control debe incluir funciones como la visualización de vacantes, el seguimiento de candidatos y la generación de informes.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden acceder a un panel de control que les permite gestionar y supervisar todas las actividades relacionadas con el proceso de reclutamiento.
- El panel de control incluye funciones como la visualización de vacantes, el seguimiento de candidatos y la generación de informes.

**Estimación:** 9 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Panel de Control, Reclutadores, Gestión de Actividades

**Comentarios:** Esta funcionalidad proporciona a los reclutadores LTI una herramienta centralizada para gestionar eficientemente el proceso de reclutamiento.

**Enlaces:** [RF22], [RF23]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

### Ticket 12

**Título:** Implementar sistema de gestión de candidatos

**Descripción:** Esta tarea consiste en desarrollar un sistema de gestión de candidatos que permita a los reclutadores LTI almacenar, organizar y gestionar la información de los candidatos de manera eficiente. El sistema debe incluir funciones como la creación de perfiles de candidatos, la actualización de estados de aplicación y la programación de entrevistas.

**Criterios de Aceptación:**

- Los reclutadores LTI pueden acceder a un sistema de gestión de candidatos que les permite almacenar, organizar y gestionar la información de los candidatos de manera eficiente.
- El sistema incluye funciones como la creación de perfiles de candidatos, la actualización de estados de aplicación y la programación de entrevistas.

**Estimación:** 10 puntos

**Asignado a:** Equipo de Desarrollo

**Etiquetas:** Gestión de Candidatos, Reclutadores, Eficiencia

**Comentarios:** Esta funcionalidad proporciona una plataforma integral para gestionar todo el proceso de reclutamiento de manera efectiva y eficiente.

**Enlaces:** [RF24], [RF25]

**Historial de Cambios:**

- 2024-05-28: Creación del ticket

## **Preparación del Spring**

| ID del Ticket | Descripción | Estimación de Puntos |
| --- | --- | --- |
| Ticket 1 | Crear formulario para ingreso de detalles de vacante | 3 puntos |
| Ticket 2 | Implementar campo para establecer fecha límite de solicitud | 2 puntos |
| Ticket 3 | Desarrollar funcionalidad para asignar responsabilidades a otros reclutadores | 5 puntos |
| Ticket 4 | Automatizar la publicación de vacantes en la plataforma LTI y redes sociales | 8 puntos |
| Ticket 5 | Personalizar contenido y formato de publicaciones en diferentes plataformas | 5 puntos |
| Ticket 6 | Desarrollar función de búsqueda y filtrado avanzadas para revisión de aplicaciones | 8 puntos |
| Ticket 7 | Implementar envío de exámenes de conocimientos online a candidatos | 6 puntos |
| Ticket 8 | Implementar selección de candidatos finalistas y cierre del proceso | 8 puntos |
| Ticket 9 | Desarrollar notificaciones a candidatos seleccionados | 5 puntos |
| Ticket 10 | Implementar notificaciones a empresas sobre candidatos seleccionados | 6 puntos |
| Ticket 11 | Desarrollar panel de control para reclutadores | 9 puntos |
| Ticket 12 | Implementar sistema de gestión de candidatos | 10 puntos |

### **Justificación de la Estimación de Puntos:**

1. **Ticket 1 (Crear formulario para ingreso de detalles de vacante):** Dado que implica la creación de un formulario básico para ingresar los detalles de una vacante, se estima en 3 puntos debido a su relativa simplicidad y bajo nivel de complejidad.
2. **Ticket 2 (Implementar campo para establecer fecha límite de solicitud):** Este ticket implica agregar un campo adicional al formulario para establecer la fecha límite de solicitud de la vacante. Se estima en 2 puntos debido a su simplicidad.
3. **Ticket 3 (Desarrollar funcionalidad para asignar responsabilidades a otros reclutadores):** Esta tarea implica implementar una función que permita asignar responsabilidades a otros reclutadores. Dado que involucra cierta lógica de usuario y gestión de roles, se estima en 5 puntos.
4. **Ticket 4 (Automatizar la publicación de vacantes en la plataforma LTI y redes sociales):** Debido a la complejidad de la integración con múltiples plataformas y la necesidad de asegurar la consistencia de la publicación, se estima en 8 puntos.
5. **Ticket 5 (Personalizar contenido y formato de publicaciones en diferentes plataformas):** Esta tarea implica agregar opciones para personalizar el contenido y formato de las publicaciones en diferentes plataformas, lo cual requiere cierta complejidad en el desarrollo. Se estima en 5 puntos.
6. **Ticket 6 (Desarrollar función de búsqueda y filtrado avanzadas para revisión de aplicaciones):** Dado que implica el desarrollo de funciones avanzadas de búsqueda y filtrado, se estima en 8 puntos debido a la complejidad de implementar algoritmos de búsqueda eficientes.
7. **Ticket 7 (Implementar envío de exámenes de conocimientos online a candidatos):** Esta tarea implica la integración con herramientas de gestión de exámenes online y el desarrollo de la funcionalidad para enviar exámenes a los candidatos. Se estima en 6 puntos debido a la complejidad técnica involucrada.
8. **Ticket 8 (Implementar selección de candidatos finalistas y cierre del proceso):** Dado que involucra la implementación de la funcionalidad para seleccionar candidatos finalistas y cerrar el proceso de contratación, se estima en 8 puntos debido a la lógica de negocio y la generación de documentos relevantes.
9. **Ticket 9 (Desarrollar notificaciones a candidatos seleccionados):** Esta tarea implica la implementación de la funcionalidad para enviar notificaciones a los candidatos seleccionados. Se estima en 5 puntos debido a su relativa simplicidad.
10. **Ticket 10 (Implementar notificaciones a empresas sobre candidatos seleccionados):** Dado que implica el desarrollo de la funcionalidad para enviar notificaciones a las empresas sobre candidatos seleccionados, se estima en 6 puntos debido a su complejidad y la necesidad de gestionar múltiples destinatarios.
11. **Ticket 11 (Desarrollar panel de control para reclutadores):** Esta tarea implica la creación de un panel de control para que los reclutadores gestionen todas las actividades relacionadas con el proceso de reclutamiento. Se estima en 9 puntos debido a la complejidad del desarrollo frontend y backend.
12. **Ticket 12 (Implementar sistema de gestión de candidatos):** Dado que implica el desarrollo de un sistema integral para gestionar candidatos, se estima en 10 puntos debido a su complejidad y la cantidad de funcionalidades involucradas, como la creación de perfiles, la actualización de estados y la programación de entrevistas.