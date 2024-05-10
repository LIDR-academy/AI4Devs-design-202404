# Ejercicio de Sesión 5

Contenido completo publicado en Notion: <https://mpizarrocuevas.notion.site/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51>

---

Teniendo en cuenta todo el análisis realizado en el apartado anterior y los siguientes puntos claves de producto:

**Visión del Producto**

- **Descripción General:** Sistema de gestión de candidatos para optimizar la planificación y documentación en procesos de selección de personal.
- **Objetivo:** Simplificar y mejorar la gestión de candidatos mediante IA.
- **Usuario Objetivo:** Reclutadores, gerentes de RRHH y equipos de selección.

**Estrategia del Producto**

- **Mercado Objetivo:** Empresas medianas y grandes con alta demanda de selección de personal.
- **Propuesta de Valor:** Reducción del tiempo de contratación, Identificación de talento mediante IA, Optimización de procesos de selección.
- **KPIs Clave:** Tiempo promedio de contratación, Tasa de retención de empleados, Satisfacción de candidatos y reclutadores.

Disponemos de toda la información necesaria que conformará el PRD.

<aside>
⚠️ Como siguiente ejercicio se requiere preparar la documentación necesaria para empezar a implementar LTI:

1. ~~Generar las **User Stories**. Puedes implementar tantas como quieras y puedas, el mínimo son 2. Utiliza lo aprendido sobre buenas prácticas de este capítulo para que contenga toda la información necesaria, y como consejo, usa una plantilla común para todas ellas (recuerda que dejamos un ejemplo de plantilla en el [módulo de introducción](https://training.lidr.co/posts/ai-4-devs-202404-%F0%9F%93%84-prompt-engineering-basico-%F0%9F%94%B4-20-min)).~~
2. ~~Arma el **Backlog de producto** con las User Stories, priorizándolas como consideres conveniente acorde a alguna metodología concreta. experimenta con diferentes formas de generar un prompt que te pueda genera tu back log basado en la documentación que has generado previamente. Entrega los diferentes prompts que usaste e indica cual prompt te dio mejores resultados. Entrega junto a los prompts tus conclusiones, por qué crees este prompt fue efectivo.~~
3. (Extra 🎁) Elige la User Story que prefieras, y **genera los Tickets de trabajo**. Aterrízalos técnicamente, tal y como se hace en las reuniones de planificación, estimando esfuerzo en la metodología (fibonacci, poker, tallas de camiseta) y unidades (horas, puntos de historia) que prefieras.
</aside>

 **🤖 Conversación completa:** https://chat.openai.com/share/e3e18495-784d-46bf-b7e8-5581f202b058

- **Primera respuesta:** *se solicitó una distinta porque, a pesar de que la definición fue buena, las historias estaban ligadas a un proceso de desarrollo más avanzado, lo que no me es útil para las siguientes tareas del proyecto.*

    ### Historias de usuario

    **1. Evaluación Automatizada de Currículums**

    - **Como:** Reclutador (usuario con rol reclutador)
    - **Quiero:** Automatizar la evaluación de currículums usando IA
    - **Para que:** Se reduzca el tiempo de revisión manual y se encuentren candidatos más relevantes
    - **Criterios de Aceptación:**
        - El sistema debe identificar automáticamente habilidades y experiencia relevantes.
        - El sistema debe proporcionar una puntuación general basada en los criterios definidos.
        - La evaluación debe generarse en menos de 10 segundos por currículum.
    - **Notas Adicionales:** La puntuación puede ser ajustada manualmente si se considera necesario.
    - **Historias de Usuario Relacionadas:** [Filtrado de Candidatos](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21), [Comparación de Candidatos](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21)

    **2. Filtrado Automático de Candidatos**

    - **Como:** Reclutador (usuario con rol reclutador)
    - **Quiero:** Filtrar automáticamente candidatos con base en criterios específicos
    - **Para que:** Pueda enfocarme solo en los candidatos que cumplen los requisitos básicos
    - **Criterios de Aceptación:**
        - El sistema debe permitir establecer filtros como experiencia, habilidades, ubicación.
        - El filtrado debe completarse en menos de 5 segundos por grupo de candidatos.
        - Los candidatos filtrados deben visualizarse en un listado ordenado por relevancia.
    - **Notas Adicionales:** Los filtros deben poder guardarse para futuras búsquedas.
    - **Historias de Usuario Relacionadas:** [Evaluación Automatizada de Currículums](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21), [Notificaciones Automatizadas a Candidatos](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21)

    **3. Comparación de Candidatos Basada en IA**

    - **Como:** Gerente de RRHH (usuario con rol manager)
    - **Quiero:** Comparar candidatos automáticamente en función de habilidades y experiencia
    - **Para que:** Se pueda seleccionar al candidato más adecuado para el puesto
    - **Criterios de Aceptación:**
        - El sistema debe comparar candidatos según criterios predefinidos (habilidades, experiencia).
        - La comparación debe completarse en menos de 10 segundos por grupo de candidatos.
        - Los candidatos deben mostrarse en una tabla de comparación fácil de leer.
    - **Notas Adicionales:** La tabla debe permitir la personalización de los criterios de comparación.
    - **Historias de Usuario Relacionadas:** [Evaluación Automatizada de Currículums](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21), [Filtrado Automático de Candidatos](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21)

    **4. Notificaciones Automatizadas a Candidatos**

    - **Como:** Reclutador (usuario con rol reclutador)
    - **Quiero:** Enviar notificaciones automáticas a los candidatos sobre el estado de su solicitud
    - **Para que:** Los candidatos estén informados y el proceso sea transparente
    - **Criterios de Aceptación:**
        - El sistema debe enviar notificaciones automáticas en función del estado de la solicitud (aceptado, rechazado, en espera).
        - Las notificaciones deben personalizarse con el nombre del candidato y el puesto solicitado.
        - Deben enviarse correos electrónicos en un plazo no superior a 24 horas tras el cambio de estado.
    - **Notas Adicionales:** Las plantillas de notificación deben ser editables.
    - **Historias de Usuario Relacionadas:** [Evaluación Automatizada de Currículums](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21), [Filtrado Automático de Candidatos](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21)

    ### **Backlog Priorizado (Scrum)**

    **Sprint 1 (2 semanas):**

    1. **Evaluación Automatizada de Currículums** (8 días)
        - Identificación de habilidades y experiencia relevantes: 2 días
        - Generación de puntuación basada en criterios definidos: 3 días
        - Generación de evaluación en menos de 10 segundos por currículum: 3 días
    2. **Filtrado Automático de Candidatos** (6 días)
        - Establecer filtros (experiencia, habilidades, ubicación): 3 días
        - Visualización ordenada por relevancia: 3 días

    **Sprint 2 (2 semanas):**

    1. **Comparación de Candidatos Basada en IA** (8 días)
        - Comparación basada en criterios predefinidos: 4 días
        - Tabla de comparación personalizable: 4 días
    2. **Notificaciones Automatizadas a Candidatos** (6 días)
        - Envío automático según estado de solicitud: 3 días
        - Personalización de notificaciones (nombre, puesto): 2 días
        - Envío de correos electrónicos en menos de 24 horas: 1 día

    **Plan de Entregas Iterativas**

    **Release 1 (MVP):** Evaluación Automatizada de Currículums y filtrado Automático de Candidatos

    **Release 2:** Comparación de Candidatos Basada en IA y notificaciones Automatizadas a Candidatos

    **Release 3:** Mejoras incrementales según feedback (Ej. personalización avanzada de notificaciones)


---

- **Segunda respuesta**

    ### Historias de Usuario para la Fase Inicial de Desarrollo

    **1. Configuración de la Base de Datos de Candidatos**

    - **Como:** Desarrollador Backend
    - **Quiero:** Configurar la base de datos para almacenar la información de los candidatos
    - **Para que:** Los datos de los candidatos estén organizados y listos para su procesamiento posterior
    - **Criterios de Aceptación:**
        - La base de datos debe contener las tablas necesarias (candidatos, solicitudes, roles, etc.).
        - Las tablas deben estar correctamente relacionadas entre sí.
        - La base de datos debe estar conectada al backend de la aplicación.
    - **Notas Adicionales:** Utilizar MongoDB como sistema de gestión de base de datos.
    - **Historias Relacionadas:** Configuración de la API de Candidatos, Gestión de Roles de Usuario

    **2. Configuración de la API de Candidatos**

    - **Como:** Desarrollador Backend
    - **Quiero:** Configurar una API REST para gestionar los datos de los candidatos
    - **Para que:** La aplicación frontend pueda acceder y modificar los datos de los candidatos
    - **Criterios de Aceptación:**
        - La API debe permitir crear, leer, actualizar y eliminar (CRUD) candidatos.
        - Debe validar la información antes de almacenar los datos.
        - Los endpoints deben estar documentados con Swagger.
    - **Notas Adicionales:** Seguir las normas de REST y usar OpenAPI para la documentación.
    - **Historias Relacionadas:** Configuración de la Base de Datos de Candidatos, Gestión de Roles de Usuario

    **3. Gestión de Roles de Usuario**

    - **Como:** Desarrollador Backend
    - **Quiero:** Implementar un sistema de roles para controlar el acceso a las funcionalidades
    - **Para que:** Los usuarios solo puedan acceder a las funcionalidades según su rol
    - **Criterios de Aceptación:**
        - Debe haber al menos dos roles: reclutador y gerente de RRHH.
        - Cada rol debe tener permisos específicos para acceder a diferentes endpoints.
        - La autenticación debe basarse en tokens JWT.
    - **Notas Adicionales:** Implementar un middleware para verificar los roles de los usuarios.
    - **Historias Relacionadas:** Configuración de la API de Candidatos, Configuración del Sistema de Autenticación

    **4. Configuración del Sistema de Autenticación**

    - **Como:** Desarrollador Backend
    - **Quiero:** Implementar un sistema de autenticación para la aplicación
    - **Para que:** Los usuarios puedan iniciar sesión de manera segura
    - **Criterios de Aceptación:**
        - Los usuarios deben poder registrarse con un correo electrónico y una contraseña.
        - Debe haber un proceso seguro de inicio de sesión con tokens JWT.
        - La autenticación debe estar conectada a la base de datos de roles y permisos.
    - **Notas Adicionales:** Utilizar JWT para la autenticación y bcrypt para encriptar contraseñas.
    - **Historias Relacionadas:** Gestión de Roles de Usuario, Configuración de la Base de Datos de Candidatos

    ### Plan de Prioridad

    1. **Sprint 1 (2 semanas):**
        - Configuración de la Base de Datos de Candidatos (5 días)
        - Configuración de la API de Candidatos (5 días)
    2. **Sprint 2 (2 semanas):**
        - Gestión de Roles de Usuario (6 días)
        - Configuración del Sistema de Autenticación (4 días)

    ### Tickets de Trabajo: Configuración de la Base de Datos de Candidatos

    **Descripción General:** Configurar la base de datos para almacenar la información de los candidatos y relacionarla correctamente con las demás tablas necesarias para el proyecto siguiendo el diagrama entidad-relación.

    <aside>
    1️⃣ **Crear la Estructura de la Base de Datos**

    - **Descripción:** Crear las tablas principales de la base de datos siguiendo el diagrama entidad-relación.
    - **Subtareas:**
        - Crear tabla **`Candidate`**
        - Crear tabla **`Interview`**
        - Crear tabla **`Evaluation`**
        - Crear relaciones entre las tablas **`Candidate`**, **`Interview`** y **`Evaluation`**.
    - **Poker Planning Estimación:** 5 puntos (8 horas)
    </aside>

    <aside>
    2️⃣ **Definir Modelos en el Backend**

    - **Descripción:** Crear modelos de objetos en el backend para representar las tablas de la base de datos.
    - **Subtareas:**
        - Crear modelo **`Candidate`** para la tabla **`Candidate`**.
        - Crear modelo **`Interview`** para la tabla **`Interview`**.
        - Crear modelo **`Evaluation`** para la tabla **`Evaluation`**.
    - **Poker Planning Estimación:** 3 puntos (5 horas)
    </aside>

    <aside>
    3️⃣ **Implementar Migraciones para la Base de Datos**

    - **Descripción:** Crear e implementar migraciones para la creación y actualización de las tablas.
    - **Subtareas:**
        - Crear migración inicial para las tablas **`Candidate`**, **`Interview`** y **`Evaluation`**.
        - Probar migraciones para asegurar que las tablas se crean correctamente.
    - **Poker Planning Estimación:** 2 puntos (4 horas)
    </aside>

    <aside>
    4️⃣ **Crear Seeds con Datos Iniciales**

    - **Descripción:** Crear semillas (seeds) para insertar datos iniciales de candidatos y evaluadores de ejemplo.
    - **Subtareas:**
        - Crear seed para insertar candidatos de ejemplo.
        - Crear seed para insertar evaluadores de ejemplo.
    - **Poker Planning Estimación:** 2 puntos (4 horas)
    </aside>

    **Resumen Total de Horas Estimadas:** 21 horas

    ---

- 💡 Se ha escogido **Scrum** tras analizarlo con el asistente de IA en la siguiente parte de la [conversación](https://www.notion.so/Proyecto-LTI-e7ef38ba5346489cad67f0d316ea8c51?pvs=21)

    > *CHATGPT 4*
    ***Implementación en el Proyecto LTI***
    >
    > - ***Metodología Recomendada:** Scrum, combinada con Story Mapping para una mejor visión global del prod*ucto.
    >
    > https://lh3.googleusercontent.com/a/AEdFTp7jhJ3al8OTubA59-jzYqUuGhSc7KDvxxHA9bgAWCc=s96-c
    >
    > por qué consideras la metodologia recomendada scrum junto a story mapping?
    >
    > ---
    >
    > *CHATGPT 4*
    >
    > *Recomiendo usar Scrum junto a Story Mapping para el Proyecto LTI porque:*
    >
    > 1. ***Scrum**:*
    >     - *Ofrece un marco ágil y adaptable que incluye sprints y revisiones continuas.*
    >     - *Alinea al equipo mediante roles claros (Product Owner, Scrum Master) y un backlog priorizado.*
    > 2. ***Story Mapping**:*
    >     - *Proporciona una visión general del producto en forma de mapa.*
    >     - *Ayuda a priorizar, identificar dependencias y planificar releases iterativos.*
    >     - *Visualiza el flujo de valor y permite dividir historias complejas.*
    >
    > ### ***Ventajas Combinadas:***
    >
    > - ***Alineación**: Todos los involucrados entienden el flujo de trabajo y los objetivos.*
    > - ***Priorización Efectiva**: El Product Owner prioriza con claridad, enfocándose en el MVP.*
    > - ***Adaptabilidad**: Flexibilidad para refinar el backlog según el feedback recibido.*
    >
    > *Esta combinación asegura un desarrollo centrado en el valor y entrega continua de funcionalidades significativas para los usuarios.*
    >
    > ---
    >
    > https://lh3.googleusercontent.com/a/AEdFTp7jhJ3al8OTubA59-jzYqUuGhSc7KDvxxHA9bgAWCc=s96-c
    >
    > por qué el resto de metodologías no son recomendables?
    >
    > *ChatGPT*
    >
    > *Las metodologías alternativas no son las más recomendables para el Proyecto LTI debido a:*
    >
    > 1. ***Kanban:***
    >     - *Mejor para equipos con flujo de trabajo continuo.*
    >     - *LTI tiene entregas iterativas más que un flujo continuo.*
    > 2. ***Lean:***
    >     - *Se enfoca más en la eliminación de desperdicios en procesos existentes.*
    >     - *LTI requiere más estructuración inicial en desarrollo de producto.*
    > 3. ***MoSCoW:***
    >     - *Priorización simple, pero carece de la estructura iterativa de Scrum.*
    >     - *No ofrece un marco para planificación y seguimiento.*
    > 4. ***Value Stream Mapping:***
    >     - *Excelente para la mejora de procesos, pero LTI es un proyecto de desarrollo de software que necesita un enfoque más amplio.*
    >
    > *La combinación de Scrum y Story Mapping ofrece un marco ágil, iterativo y visual, ideal para estructurar un producto con entregas incrementales.*
    >