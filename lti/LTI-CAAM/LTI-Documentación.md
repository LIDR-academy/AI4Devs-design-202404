
### Documentación del Proyecto de Sistema ATS con Evaluación de Ajuste de Candidato Mediante LLM

#### 1. **Introducción**

La introducción proporciona una visión general del proyecto, destacando la necesidad de optimizar el proceso de reclutamiento en las empresas mediante el uso de tecnologías avanzadas.

   - **Descripción General**: Este sistema de seguimiento de candidatos (ATS) está diseñado para modernizar y mejorar el proceso de reclutamiento de empresas de todos los tamaños. Al integrar un modelo de lenguaje de aprendizaje automático (LLM), el sistema es capaz de analizar las solicitudes de los candidatos y evaluar su adecuación a las ofertas de empleo publicadas. Esto permite a los reclutadores tomar decisiones más informadas y eficientes, mejorando la precisión y reduciendo el tiempo de selección.
   
   - **Objetivos**: 
     - Automatizar y simplificar la publicación y gestión de ofertas de empleo.
     - Facilitar el proceso de envío y gestión de solicitudes por parte de los candidatos.
     - Utilizar inteligencia artificial para evaluar la adecuación de los candidatos a las ofertas, optimizando la selección inicial.
     - Mejorar la eficiencia del proceso de reclutamiento, reduciendo costos y tiempo invertido en la selección de personal.

#### 2. **Planificación Inicial**

La planificación inicial establece las bases del proyecto, definiendo el alcance, los usuarios objetivo y el equipo que llevará a cabo el desarrollo del sistema.

   - **Objetivo del Proyecto**: El principal objetivo es desarrollar un sistema de seguimiento de candidatos que no solo automatice las tareas rutinarias de reclutamiento, sino que también integre análisis avanzados para evaluar la adecuación de los candidatos, proporcionando una herramienta robusta y eficiente para la selección de personal.
   
   - **Público Objetivo**: 
     - Pequeñas y medianas empresas que no cuentan con equipos de reclutamiento dedicados y buscan mejorar su eficiencia en la selección de candidatos.
     - Departamentos de recursos humanos en empresas más grandes que necesitan optimizar sus procesos de selección y reducir la carga administrativa.
   
   - **Definición del MVP**: 
     - **Funcionalidades del MVP**:
       - Publicación y gestión de ofertas de empleo.
       - Registro y actualización de perfiles de candidatos.
       - Envío de solicitudes con currículums adjuntos.
       - Análisis automático de las solicitudes mediante LLM para evaluar la adecuación de los candidatos.
       - Herramientas para el filtrado y seguimiento de candidatos.
       - Programación de entrevistas y comunicación automatizada con los candidatos.
   

#### 3. **Requerimientos Funcionales**

Los requerimientos funcionales describen en detalle lo que el sistema debe hacer para satisfacer las necesidades de los usuarios y los objetivos del proyecto.

   - **Publicación de Ofertas de Trabajo**:
     - Los reclutadores deben poder crear y publicar ofertas de empleo, especificando información como el título del puesto, descripción detallada, habilidades requeridas y fecha de publicación.
     - Debe existir una funcionalidad para editar o eliminar ofertas existentes.
   
   - **Gestión de Candidatos**:
     - Los candidatos deben poder registrarse en el sistema, proporcionando datos como nombre, email, teléfono, experiencia laboral, educación y habilidades.
     - Los candidatos deben tener la capacidad de actualizar su perfil y currículum en cualquier momento.
   
   - **Envío de Solicitudes**:
     - Los candidatos deben poder enviar solicitudes a ofertas específicas, adjuntando su currículum.
     - Cada solicitud debe registrar la fecha de envío y actualizar su estado según avance en el proceso de selección (por ejemplo, "En revisión", "Seleccionado para entrevista").
   
   - **Análisis Automático de Solicitudes con LLM**:
     - El sistema debe utilizar un modelo de lenguaje de aprendizaje automático para analizar las solicitudes y currículums, generando una puntuación o evaluación de la adecuación del candidato a la oferta de empleo.
     - Los reclutadores deben poder ver estas evaluaciones para ayudar en la selección inicial de candidatos.
   
   - **Filtrado y Seguimiento de Candidatos**:
     - Debe haber herramientas que permitan a los reclutadores filtrar candidatos por puntuación de ajuste, habilidades, experiencia y otros criterios relevantes.
     - El sistema debe permitir el seguimiento del estado de cada candidato en el proceso de selección.
   
   - **Programación de Entrevistas**:
     - El sistema debe facilitar la programación de entrevistas, permitiendo a los reclutadores seleccionar candidatos, establecer fechas y horarios, y notificar a los candidatos.
   
   - **Comunicación Automatizada**:
     - El sistema debe enviar correos electrónicos automáticos a los candidatos para informarles sobre cambios en el estado de sus solicitudes, invitaciones a entrevistas y otros eventos importantes.


### Diagrama de casos de uso:

graph TD
    subgraph Reclutador
    P1[Publicar Oferta de Trabajo]
    E1[Editar Oferta de Trabajo]
    F1[Filtrar y Seguimiento de Candidatos]
    S1[Programar Entrevistas]
    V1[Ver Evaluaciones de Candidatos]
    end

    subgraph Candidato
    B1[Buscar Ofertas de Empleo]
    S2[Enviar Solicitud]
    A1[Actualizar Perfil y Currículum]
    V2[Ver Estado de Solicitud]
    end

    Reclutador --> P1
    Reclutador --> E1
    Reclutador --> F1
    Reclutador --> S1
    Reclutador --> V1

    Candidato --> B1
    Candidato --> S2
    Candidato --> A1
    Candidato --> V2


**Explicación del Diagrama:**

- **Reclutador**:
  - **Publicar Oferta de Trabajo**: Crear y publicar nuevas ofertas de empleo.
  - **Editar Oferta de Trabajo**: Modificar o eliminar ofertas de empleo existentes.
  - **Filtrar y Seguimiento de Candidatos**: Usar herramientas para filtrar candidatos por diversos criterios y hacer seguimiento de su progreso en el proceso de selección.
  - **Programar Entrevistas**: Organizar entrevistas con candidatos seleccionados, estableciendo fecha y hora.
  - **Ver Evaluaciones de Candidatos**: Consultar las puntuaciones y evaluaciones generadas por el LLM para los candidatos.

- **Candidato**:
  - **Buscar Ofertas de Empleo**: Navegar y buscar ofertas de empleo disponibles en el sistema.
  - **Enviar Solicitud**: Enviar solicitudes a ofertas específicas, adjuntando el currículum.
  - **Actualizar Perfil y Currículum**: Modificar la información de su perfil y actualizar su currículum.
  - **Ver Estado de Solicitud**: Revisar el estado actual de sus solicitudes en el proceso de selección.

Este diagrama muestra cómo los dos tipos principales de usuarios interactúan con las funcionalidades del sistema, proporcionando una visión clara de las operaciones y flujos principales dentro del sistema ATS.




### Modelo de Datos y Diagrama de Entidad-Relación a Alto Nivel

El modelo de entidad-relación actualizado para el sistema ATS refleja la estructura y las relaciones clave necesarias para gestionar eficientemente el proceso de reclutamiento y selección de candidatos. Este modelo se ha diseñado para soportar una gestión clara y efectiva de roles dentro de la empresa, permitiendo una operación fluida y segura. A continuación se describen las principales entidades y sus roles dentro del sistema:

1. **Usuarios y Roles**:
   - **Usuarios (User)**: Son la base de la autenticación en el sistema. Cada usuario tiene un rol que define sus permisos y capacidades dentro del ATS. Los usuarios también están vinculados a un perfil de empresa, lo que permite una gestión centralizada y una visión clara de su relación con la empresa.
   - **Roles (Role)**: Identifican los diferentes tipos de usuarios dentro del sistema, como administradores, reclutadores y candidatos. Cada rol tiene asociados permisos específicos que definen lo que el usuario puede y no puede hacer dentro del sistema.

2. **Gestión de la Empresa**:
   - **Perfil de Empresa (CompanyProfile)**: Contiene la información esencial sobre la empresa, como el nombre, dirección, teléfono y correo electrónico de contacto. Este perfil es gestionado por administradores y es el núcleo alrededor del cual se organizan los reclutadores y las ofertas de empleo.

3. **Perfiles de Usuarios**:
   - **Perfil de Candidato (CandidateProfile)**: Alberga detalles específicos sobre los candidatos, incluyendo su experiencia laboral, educación y habilidades. También incluye la URL del currículum para facilitar el acceso y la revisión por parte de los reclutadores.
   - **Perfil de Reclutador (RecruiterProfile)**: Contiene información sobre el reclutador, como su nombre, y está asociado al perfil de la empresa, reflejando la estructura donde los reclutadores operan bajo una empresa centralizada.

4. **Ofertas de Empleo**:
   - **Ofertas de Empleo (JobOffer)**: Representan las oportunidades laborales disponibles y están vinculadas directamente al perfil de la empresa, mostrando que pertenecen a la empresa y no a un reclutador individual. Cada oferta incluye información como el título, descripción, habilidades requeridas, rango salarial, modalidad de trabajo y entorno laboral. Además, se registra quién publicó la oferta para facilitar el seguimiento.

5. **Aplicaciones y Evaluaciones**:
   - **Aplicaciones (Application)**: Son las solicitudes que los candidatos envían a las ofertas de empleo. Estas están relacionadas con el perfil del candidato y la oferta específica, y mantienen un registro de su estado a lo largo del proceso.
   - **Evaluaciones de Aplicaciones (ApplicationEvaluation)**: Almacenan las evaluaciones automáticas realizadas por el LLM para cada aplicación, incluyendo la puntuación y comentarios adicionales.

6. **Entrevistas**:
   - **Entrevistas (Interview)**: Gestionan la organización de entrevistas con candidatos, incluyendo detalles como fecha, hora, formato y observaciones adicionales.

7. **Permisos y Control de Acceso**:
   - **Permisos (Permission)**: Definen las acciones específicas que los roles pueden realizar dentro del sistema, garantizando una gestión de acceso segura y estructurada.
   - **Asociación de Roles y Permisos (RolePermission)**: Vincula roles con permisos específicos, asegurando que cada usuario tenga acceso solo a las funciones que le corresponden dentro del sistema.

Este modelo estructurado no solo facilita la implementación técnica del sistema ATS, sino que también proporciona una base sólida para la expansión y adaptación futura según evolucionen las necesidades de reclutamiento y selección.


erDiagram
    User {
        int UserID "Identificador único"
        string Username "Nombre de usuario"
        string PasswordHash "Hash de la contraseña"
        string Email "Correo electrónico"
        int RoleID "Clave foránea a Rol"
        int CompanyProfileID "Clave foránea a Perfil de Empresa"
    }

    Role {
        int RoleID "Identificador único"
        string RoleName "Nombre del rol"
        text Description "Descripción del rol"
    }

    CompanyProfile {
        int CompanyProfileID "Identificador único"
        string Name "Nombre de la empresa"
        string Address "Dirección de la empresa"
        string Phone "Número de teléfono"
        string ContactEmail "Correo electrónico de contacto"
    }

    CandidateProfile {
        int CandidateProfileID "Identificador único"
        int UserID "Clave foránea a Usuario"
        string Name "Nombre completo"
        string Phone "Número de teléfono"
        text WorkExperience "Experiencia laboral"
        text Education "Educación"
        text Skills "Habilidades"
        string ResumeURL "URL del currículum almacenado"
    }

    JobOffer {
        int JobOfferID "Identificador único"
        int CompanyProfileID "Clave foránea a Perfil de Empresa"
        int PostedByUserID "Clave foránea a Usuario que publicó la oferta"
        string Title "Título del puesto"
        text Description "Descripción del puesto"
        text RequiredSkills "Habilidades necesarias"
        date PublicationDate "Fecha de publicación"
        float MinSalary "Salario mínimo ofrecido"
        float MaxSalary "Salario máximo ofrecido"
        string WorkModality "Modalidad de trabajo (Full Time, Part Time)"
        string WorkEnvironment "Entorno de trabajo (Remoto, Presencial, Híbrido)"
    }

    Application {
        int ApplicationID "Identificador único"
        int CandidateProfileID "Clave foránea a Perfil de Candidato"
        int JobOfferID "Clave foránea a Oferta de Empleo"
        datetime SubmissionDate "Fecha y hora de envío"
        string Status "Estado de la solicitud"
    }

    ApplicationEvaluation {
        int EvaluationID "Identificador único"
        int ApplicationID "Clave foránea a Solicitud"
        float Score "Puntuación de ajuste por LLM"
        text Comments "Comentarios sobre la evaluación"
    }

    Interview {
        int InterviewID "Identificador único"
        int ApplicationID "Clave foránea a Solicitud"
        datetime Date "Fecha y hora de la entrevista"
        string Format "Formato de la entrevista"
        text Notes "Observaciones adicionales"
    }

    Permission {
        int PermissionID "Identificador único"
        string PermissionName "Nombre del permiso"
        text Description "Descripción del permiso"
    }

    RolePermission {
        int RoleID "Clave foránea a Rol"
        int PermissionID "Clave foránea a Permiso"
    }

    Role ||--|{ User : "define"
    User ||--|{ CandidateProfile : "pertenece"
    User ||--|{ CompanyProfile : "incluye"
    CompanyProfile ||--|{ JobOffer : "publica"
    CandidateProfile ||--|{ Application : "envía"
    Application ||--|| ApplicationEvaluation : "evalúa"
    Application ||--|| Interview : "programa"
    Role ||--|{ RolePermission : "asigna"
    Permission ||--|{ RolePermission : "permite"




### Arquitectura de Alto Nivel del Sistema ATS

La arquitectura de alto nivel del sistema ATS está diseñada para proporcionar una solución robusta y escalable que facilite el proceso de reclutamiento y selección de candidatos. Esta arquitectura está estructurada en diferentes capas y servicios que interactúan entre sí para garantizar un funcionamiento eficiente y seguro del sistema. A continuación, se describen los componentes principales y su interacción:

1. **Interfaz de Usuario (UI)**: 
   - La interfaz de usuario es el punto de entrada para todos los usuarios del sistema, proporcionando una experiencia interactiva y accesible para administradores, reclutadores y candidatos.
   - **Panel de Administradores**: Permite gestionar la información de la empresa, añadir y configurar roles de usuarios, y tener una visión global de las operaciones dentro del sistema.
   - **Panel de Reclutadores**: Facilita la creación, gestión y seguimiento de ofertas de empleo, además de permitir la revisión de aplicaciones y la programación de entrevistas.
   - **Portal de Candidatos**: Permite a los candidatos buscar ofertas, enviar aplicaciones, actualizar su perfil y currículum, y monitorizar el estado de sus solicitudes.

2. **Capa de Servicios**:
   - **Servicio de Autenticación**: Gestiona el registro, inicio de sesión y autenticación de usuarios, asegurando que cada usuario acceda solo a las áreas y funcionalidades permitidas según su rol.
   - **Servicio de Gestión de Usuarios**: Administra la creación y actualización de perfiles de usuario, incluyendo la gestión de currículums, que se comunica con el sistema de almacenamiento externo para una gestión eficiente de los currículums de los candidatos.
   - **Servicio de Ofertas de Empleo**: Responsable de la creación, actualización y eliminación de ofertas de empleo, así como de la gestión de la publicación y visibilidad de estas.
   - **Servicio de Aplicaciones y Evaluaciones**: Maneja la recepción de aplicaciones de candidatos, la evaluación mediante el LLM, y la provisión de resultados y comentarios a los reclutadores.
   - **Servicio de Programación de Entrevistas**: Coordina la logística de las entrevistas, incluyendo la programación de fechas y la comunicación con los candidatos.

3. **Capa de Datos**:
   - **Base de Datos**: Almacena y mantiene toda la información relevante del sistema, incluyendo datos de usuarios, roles, perfiles de candidatos y reclutadores, ofertas de empleo, aplicaciones, evaluaciones y entrevistas. La base de datos es esencial para mantener la integridad y coherencia de los datos.
   - **Almacenamiento de Currículums**: Un sistema de almacenamiento externo, como AWS S3 o Google Cloud Storage, que guarda de manera segura los currículums de los candidatos y proporciona accesibilidad mediante URLs almacenadas en la base de datos.

4. **Integraciones Externas**:
   - **Servicio de LLM (LLMAPI)**: Un sistema externo o API que provee la funcionalidad de aprendizaje automático para evaluar las aplicaciones de los candidatos. Este servicio procesa la información de las aplicaciones y devuelve puntuaciones y comentarios que ayudan a los reclutadores en la selección de candidatos.
   - **Servicio de Correo Electrónico (EmailService)**: Utilizado para enviar notificaciones automáticas a usuarios sobre eventos importantes como cambios en el estado de las aplicaciones, invitaciones a entrevistas y comunicaciones generales.

Esta arquitectura garantiza que el sistema ATS sea eficiente y capaz de adaptarse a las necesidades cambiantes del proceso de reclutamiento y selección. La organización modular y la clara separación de responsabilidades entre los componentes permiten una fácil expansión y mantenimiento del sistema.

graph TD
    UI[Interfaz de Usuario]
    Auth[Servicio de Autenticación]
    UserMgmt[Servicio de Gestión de Usuarios]
    JobMgmt[Servicio de Ofertas de Empleo]
    AppEval[Servicio de Aplicaciones y Evaluaciones]
    InterviewMgmt[Servicio de Programación de Entrevistas]
    DB[Base de Datos]
    Storage[Almacenamiento de Currículums]
    LLMAPI[Servicio de LLM]
    EmailService[Servicio de Correo Electrónico]
    Monitoring[Monitoreo y Registro]

    UI --> Auth
    UI --> UserMgmt
    UI --> JobMgmt
    UI --> AppEval
    UI --> InterviewMgmt

    Auth --> DB
    UserMgmt --> DB
    UserMgmt --> Storage
    JobMgmt --> DB
    AppEval --> DB
    AppEval --> LLMAPI
    InterviewMgmt --> DB
    InterviewMgmt --> EmailService

    Monitoring --> DB



