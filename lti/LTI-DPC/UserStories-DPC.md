# User Stories

User Story 1: Creación de Ofertas de Empleo
Historia de Usuario:
Como reclutador en LTI, quiero poder crear nuevas ofertas de empleo en el sistema, para publicar oportunidades laborales y atraer candidatos cualificados.

Criterios de Aceptación:

El usuario debe tener acceso al módulo de creación de ofertas de empleo en el ATS de LTI.
Debe existir un formulario claro y completo para ingresar los detalles de la nueva oferta de empleo, incluyendo título del puesto, descripción del trabajo, requisitos y ubicación.
Se debe proporcionar la opción de seleccionar canales de publicación para difundir la oferta.
Después de crear la oferta, se debe guardar automáticamente y mostrar un mensaje de confirmación al usuario.
La oferta creada debe ser visible y accesible para su gestión posterior en el sistema.
Tareas Técnicas:

Implementar el formulario de creación de ofertas en la interfaz de usuario.
Desarrollar la lógica backend para almacenar y gestionar las nuevas ofertas de empleo.
Asegurar la validación de datos en el formulario para evitar información incompleta o incorrecta.
Realizar pruebas exhaustivas para garantizar que la creación de ofertas funcione correctamente en diferentes escenarios.

User Story 2: Edición de Ofertas de Empleo
Historia de Usuario:
Como reclutador en LTI, quiero poder editar una oferta de empleo para corregir errores o actualizar información, para mantener la precisión y relevancia de las ofertas publicadas.

Criterios de Aceptación:

El usuario debe tener acceso al módulo de gestión de ofertas de empleo en el ATS de LTI.
Debe existir una opción clara para editar una oferta de empleo existente.
Se debe permitir al usuario modificar campos como título del puesto, descripción del trabajo, requisitos y ubicación.
Después de editar la oferta, se debe guardar automáticamente y mostrar un mensaje de confirmación al usuario.
Se debe mantener un registro de las ediciones realizadas en la oferta de empleo para referencia futura.
Tareas Técnicas:

Implementar la funcionalidad de edición en el backend del sistema.
Actualizar la interfaz de usuario para incluir botones o enlaces de edición en las ofertas de empleo.
Asegurar la validación de datos para prevenir cambios no autorizados o datos incorrectos.
Realizar pruebas exhaustivas para garantizar que la edición de ofertas funcione correctamente en diferentes escenarios.

User Story 3: Recordatorios Automáticos de Entrevistas
Historia de Usuario:
Como gerente de contratación en LTI, quiero recibir recordatorios automáticos sobre las entrevistas programadas con candidatos, para asegurar que ninguna cita se pierda y mantener una comunicación efectiva con los candidatos.

Criterios de Aceptación:

El sistema debe enviar automáticamente recordatorios a los gerentes de contratación y a los candidatos antes de cada entrevista programada.
Los recordatorios deben incluir detalles como la fecha, hora y lugar de la entrevista, así como la información de contacto relevante.
Se debe proporcionar una opción para que los usuarios confirmen o reprogramen la entrevista directamente desde el recordatorio.
En caso de cambios en la programación de entrevistas, el sistema debe enviar notificaciones actualizadas a todas las partes involucradas.
Tareas Técnicas:

Desarrollar un sistema de notificaciones automáticas integrado con el calendario de entrevistas en el backend.
Configurar plantillas de mensajes para los recordatorios y notificaciones de cambios.
Implementar la opción de confirmación y reprogramación de entrevistas en la interfaz de usuario.
Probar exhaustivamente el sistema de notificaciones para garantizar su fiabilidad y efectividad en diferentes situaciones.

# Backlog de Producto

| User Story | Impacto en el Usuario y Valor del Negocio | Urgencia Basada en Tendencias y Feedback de Usuarios | Complejidad y Esfuerzo Estimado | Riesgos y Dependencias |
|--------------------------------------------------------------------|-----------------------------------------------------------------------------|------------------------------------------------------|----------------------------------|------------------------------------------------------------|
| Creación de Ofertas de Empleo | Permite a los reclutadores publicar oportunidades laborales. | Alta | Moderada | Depende de la existencia de un módulo de creación en el ATS |
| Edición de Ofertas de Empleo | Mejora la precisión y relevancia de las ofertas publicadas. | Alta | Moderada | Depende de la infraestructura de edición en el ATS |
| Recordatorios Automáticos de Entrevistas | Evita la pérdida de citas de entrevistas y mejora la comunicación con candidatos. | Moderada | Moderada | Integración con calendario y sistemas de notificación |