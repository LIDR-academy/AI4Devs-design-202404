## User stories

### User Story 1: Crear nueva oferta de trabajo
**Título:**
Crear nueva oferta de trabajo

**Descripción:**
Como reclutador, quiero poder crear una nueva oferta de trabajo en la aplicación LTI. Debo poder especificar detalles como el título del puesto, la descripción del trabajo, los requisitos y los beneficios.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
Ninguna

**Comentarios:**
Esta user story cubre la funcionalidad básica de crear una nueva oferta de trabajo en la aplicación.

**Etiquetas:**
Ofertas de Trabajo, Creación

---

### User Story 2: Gestionar ofertas de trabajo
**Título:**
Gestionar ofertas de trabajo

**Descripción:**
Como reclutador, quiero poder gestionar las ofertas de trabajo existentes en la aplicación LTI. Debo poder listar todas las ofertas, filtrarlas por estado (activas/inactivas), así como por otros campos relevantes como título, fecha de creación, etc.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
User Story 1: Crear nueva oferta de trabajo

**Comentarios:**
Esta user story proporciona la capacidad de listar y filtrar las ofertas de trabajo existentes en la aplicación, lo que facilitará la gestión y navegación de las mismas por parte de los reclutadores.

**Etiquetas:**
Ofertas de Trabajo, Gestión

---

### User Story 3: Cerrar oferta de trabajo
**Título:**
Cerrar oferta de trabajo

**Descripción:**
Como reclutador, quiero poder cerrar una oferta de trabajo existente en la aplicación LTI. Debo poder marcar una oferta como inactiva para que ya no sea visible en las listas principales, pero aún se pueda acceder a ella para referencia histórica.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
User Story 1: Crear nueva oferta de trabajo

**Comentarios:**
Esta user story proporciona la capacidad de cerrar una oferta de trabajo que ya no está activa, permitiendo que se mantenga en la base de datos pero no sea visible para futuros candidatos.

**Etiquetas:**
Ofertas de Trabajo, Cierre


---


### User Story 4: Ver perfiles de candidatos
**Título:**
Ver perfiles de candidatos

**Descripción:**
Como técnico de RRHH, quiero poder ver los perfiles de los candidatos que han aplicado a una oferta de trabajo en la aplicación LTI. Debo poder acceder a información como el currículum, habilidades, experiencia laboral, educación y cualquier otra información relevante proporcionada por los candidatos.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
User Story 2 de Caso de Uso 1: Crear nueva oferta de trabajo

**Comentarios:**
Esta user story permitirá a los técnicos de RRHH revisar los perfiles de los candidatos para evaluar su idoneidad para el puesto.

**Etiquetas:**
Revisión de Candidatos, Perfiles


---


### User Story 5: Evaluar habilidades y experiencia
**Título:**
Evaluar habilidades y experiencia

**Descripción:**
Como técnico de RRHH, quiero poder evaluar las habilidades y experiencia de los candidatos que han aplicado a una oferta de trabajo en la aplicación LTI. Debo poder revisar detalladamente el historial laboral, proyectos anteriores y otras actividades relevantes para determinar la idoneidad de los candidatos.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
User Story 1: Ver perfiles de candidatos

**Comentarios:**
Esta user story proporciona la capacidad de evaluar en detalle las habilidades y experiencia de los candidatos para tomar decisiones informadas de contratación.

**Etiquetas:**
Revisión de Candidatos, Evaluación


---

### User Story 6: Tomar decisiones de contratación
**Título:**
Tomar decisiones de contratación

**Descripción:**
Como técnico de RRHH, quiero poder tomar decisiones de contratación basadas en la evaluación de los candidatos en la aplicación LTI. Debo poder programar entrevistas con candidatos prometedores, rechazar solicitudes de candidatos no aptos y avanzar en el proceso de selección según sea necesario.

**Prioridad:**
Alta

**Estado:**
Pendiente

**Dependencias:**
User Story 2: Evaluar habilidades y experiencia

**Comentarios:**
Esta user story proporciona la capacidad de tomar decisiones de contratación basadas en la evaluación de habilidades y experiencia de los candidatos.

**Etiquetas:**
Revisión de Candidatos, Contratación



## Tareas técnicas 

### Tareas técnicas - User Story 1: Crear nueva oferta de trabajo

#### Backend:
1. Crear un endpoint REST para manejar la solicitud de creación de una nueva oferta de trabajo. (2 SP)
2. Implementar la lógica de negocio para procesar la creación de la oferta de trabajo en el servicio correspondiente. (3 SP)
3. Validar los datos de entrada proporcionados por el reclutador para garantizar que sean correctos y completos. (1 SP)
4. Integrar la lógica de persistencia para almacenar la nueva oferta de trabajo en la base de datos PostgreSQL. (3 SP)
5. Implementar pruebas unitarias para verificar el correcto funcionamiento de la creación de la oferta de trabajo. (2 SP)

#### Frontend:
6. Diseñar y desarrollar la interfaz de usuario para que el reclutador pueda ingresar los detalles de la nueva oferta de trabajo. (3 SP)
7. Implementar la validación de formularios para asegurar que se proporcionen los campos requeridos y que los datos ingresados sean válidos. (2 SP)
8. Conectar la interfaz de usuario con el backend a través de llamadas API para enviar los datos de la nueva oferta de trabajo. (2 SP)
9. Desarrollar la lógica de respuesta para manejar los casos de éxito y error al crear la oferta de trabajo. (2 SP)

#### Otros:
10. Actualizar la documentación del API para incluir el nuevo endpoint y su funcionalidad. (1 SP)
11. Realizar pruebas de integración para garantizar que el frontend y el backend se comuniquen correctamente y que la creación de la oferta de trabajo funcione según lo esperado. (3 SP)
12. Desplegar la aplicación en un entorno de prueba para que los stakeholders puedan revisar y probar la funcionalidad de creación de ofertas de trabajo. (2 SP)
13. Implementar mecanismos de seguridad, como autenticación y autorización, para proteger el endpoint de creación de ofertas de trabajo contra accesos no autorizados. (3 SP)


