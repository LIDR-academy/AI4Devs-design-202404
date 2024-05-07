## User Stories

1. **Como** reclutador, **quiero** publicar trabajos en múltiples plataformas **para** poder llegar a un grupo más amplio de candidatos potenciales.

2. **Como** reclutador, **quiero** utilizar la IA para clasificar automáticamente currículums vítae y candidatos **para** poder identificar rápidamente a los candidatos más calificados.

3. **Como** reclutador, **quiero** tener una plataforma centralizada para gestionar a todos los candidatos en el proceso de contratación **para** poder seguir fácilmente su progreso y comunicarme con ellos.

4. **Como** reclutador, **quiero** programar entrevistas con los candidatos fácilmente **para** ahorrar tiempo y esfuerzo.

5. **Como** reclutador, **quiero** integrar LTI ATS con proveedores de verificación de antecedentes **para** poder verificar rápidamente los antecedentes de los candidatos.

6. **Como** gerente de contratación, **quiero** acceder a datos y análisis sobre el proceso de contratación **para** poder tomar decisiones informadas sobre cómo mejorarlo.

7. **Como** candidato, **quiero** postularme a trabajos fácilmente a través de LTI ATS **para** poder aumentar mis posibilidades de ser contratado.

8. **Como** candidato, **quiero** poder rastrear el estado de mi solicitud **para** saber en qué punto me encuentro del proceso de contratación.

9. **Como** candidato, **quiero** recibir comunicación oportuna de los reclutadores **para** estar informado sobre los próximos pasos en el proceso de contratación.

## Estimación de backlog de producto para LTI ATS

| Historia de usuario | Impacto en el usuario y valor del negocio | Urgencia | Complejidad y esfuerzo estimado de implementación | Riesgos y dependencias |
|---|---|---|---|---|
| **1. Publicar trabajos en múltiples plataformas** | Permite a los reclutadores llegar a un grupo más amplio de candidatos potenciales, lo que aumenta las posibilidades de encontrar a los mejores candidatos para el puesto. | Alta | Media | Integración con plataformas de publicación de trabajos, desarrollo de interfaces de usuario específicas para cada plataforma. |
| **2. Clasificar automáticamente currículums vítae y candidatos** | Reduce el tiempo y el esfuerzo que los reclutadores dedican a la revisión manual de currículums vítae, lo que les permite enfocarse en tareas más estratégicas. | Alta | Media | Desarrollo y entrenamiento de algoritmos de IA, integración con el sistema de gestión de candidatos. |
| **3. Gestionar a todos los candidatos en una plataforma centralizada** | Facilita el seguimiento del progreso de los candidatos, la comunicación con ellos y la organización de la información relevante. | Alta | Media | Desarrollo de un sistema de gestión de candidatos robusto, integración con otros sistemas de RR.HH. |
| **4. Programar entrevistas fácilmente** | Agiliza el proceso de programación de entrevistas, ahorra tiempo y esfuerzo a los reclutadores y mejora la experiencia del candidato. | Media | Media | Integración con calendarios, desarrollo de un sistema de programación de entrevistas automatizado. |
| **5. Integrar LTI ATS con proveedores de verificación de antecedentes** | Permite verificar rápidamente los antecedentes de los candidatos, lo que aumenta la confianza en el proceso de contratación y reduce el riesgo de contratar a candidatos no calificados o problemáticos. | Media | Media | Integración con proveedores de verificación de antecedentes, desarrollo de interfaces de usuario específicas. |
| **6. Acceder a datos y análisis sobre el proceso de contratación** | Brinda información valiosa para tomar decisiones informadas sobre cómo mejorar el proceso de contratación y aumentar la eficiencia. | Media | Baja | Desarrollo de herramientas de análisis de datos, integración con el sistema de gestión de candidatos. |
| **7. Postularse a trabajos fácilmente a través de LTI ATS** | Simplifica el proceso de postulación para los candidatos, lo que aumenta la participación y la satisfacción de los candidatos. | Media | Baja | Desarrollo de un formulario de solicitud de empleo fácil de usar, integración con el sistema de gestión de candidatos. |
| **8. Rastreo del estado de la solicitud** | Permite a los candidatos saber en qué punto del proceso de contratación se encuentran, lo que aumenta la transparencia y reduce la ansiedad. | Media | Baja | Desarrollo de un sistema de seguimiento del estado de la solicitud, integración con el sistema de gestión de candidatos. |
| **9. Recibir comunicación oportuna de los reclutadores** | Mantiene a los candidatos informados sobre los próximos pasos en el proceso de contratación, lo que mejora la experiencia del candidato y aumenta la probabilidad de que acepten una oferta de trabajo si se les ofrece una. | Media | Baja | Desarrollo de un sistema de comunicación con los candidatos, integración con el sistema de gestión de candidatos. |

**Priorización:**

Basándonos en la estimación de impacto, urgencia, complejidad y riesgos, se recomienda priorizar las historias de usuario de la siguiente manera:

1. **Alta prioridad:**
    * Publicar trabajos en múltiples plataformas (Impacto alto, Urgencia alta, Complejidad media)
    * Clasificar automáticamente currículums vítae y candidatos (Impacto alto, Urgencia alta, Complejidad media)
    * Gestionar a todos los candidatos en una plataforma centralizada (Impacto alto, Urgencia alta, Complejidad media)
2. **Prioridad media:**
    * Programar entrevistas fácilmente (Impacto medio, Urgencia media, Complejidad media)
    * Integrar LTI ATS con proveedores de verificación de antecedentes (Impacto medio, Urgencia media, Complejidad media)
    * Acceder a datos y análisis sobre el proceso de contratación (Impacto medio, Urgencia media, Complejidad baja)
3. **Baja prioridad:**
    * Postularse a trabajos fácilmente a través de LTI ATS (Impacto medio, Urgencia baja, Complejidad baja)
    * Rastreo del estado de la solicitud (Impacto medio, Urgencia baja, Complejidad baja)
    * Recibir comunicación oportuna de los reclutadores (Impacto medio, Urgencia baja, Complejidad baja)

**Consideraciones adicionales:**

* La priorización final puede ajustarse en función de las necesidades específicas de la empresa y los comentarios de los usuarios.
* Es importante desarrollar un plan de implementación detallado que incluya plazos, recursos y responsabilidades.
* Se deben realizar pruebas exhaustivas de cada historia de usuario

## Tickets de trabajo para la historia de usuario #2: Clasificar automáticamente currículums vítae y candidatos

| **Ticket de trabajo** | **Descripción** | **Estimación de puntos (Método Poker)** |
|---|---|---|
| **1. Recopilación de requisitos** | Recopilar y documentar los requisitos específicos para la clasificación automática de currículums vítae y candidatos. | 2 |
| **2. Análisis de datos** | Analizar los datos de currículums vítae y candidatos existentes para identificar patrones y características relevantes para la clasificación. | 5 |
| **3. Selección de algoritmos de IA** | Seleccionar algoritmos de IA adecuados para la clasificación de currículums vítae y candidatos, en función del análisis de datos y los requisitos específicos. | 3 |
| **4. Entrenamiento de modelos de IA** | Entrenar los modelos de IA seleccionados con los datos de currículums vítae y candidatos. | 8 |
| **5. Evaluación de modelos de IA** | Evaluar el rendimiento de los modelos de IA entrenados utilizando métricas relevantes, como precisión, recuperación y F1-score. | 5 |
| **6. Integración con el sistema LTI ATS** | Integrar los modelos de IA entrenados con el sistema LTI ATS para habilitar la clasificación automática de currículums vítae y candidatos. | 5 |
| **7. Pruebas y validación** | Realizar pruebas exhaustivas para validar el correcto funcionamiento de la clasificación automática de currículums vítae y candidatos. | 3 |
| **8. Documentación** | Documentar el proceso de desarrollo, los modelos de IA utilizados y la integración con el sistema LTI ATS. | 2 |

**Estimación total de puntos:** 31

**Estimación de tiempo utilizando el método Poker:**

* **1 punto:** 1 hora
* **2 puntos:** 2 horas
* **3 puntos:** 3 horas
* **5 puntos:** 4 horas
* **8 puntos:** 8 horas
* **13 puntos:** 13 horas
* **20 puntos:** 20 horas
* **40 puntos:** 40 horas

**Escala de tiempo:**

* **Pequeño:** 1-2 días
* **Mediano:** 3-5 días
* **Grande:** 6-10 días
* **Muy grande:** Más de 10 días

**Estimación de tiempo total:** 31 puntos * 2 horas/punto = 62 horas

**Escala de tiempo:** Grande

**Consideraciones adicionales:**

* La estimación de tiempo es solo una aproximación y puede variar en función de la complejidad del proyecto, la experiencia del equipo y los recursos disponibles.
* Es importante realizar reuniones de planificación regulares para refinar las estimaciones y ajustar el plan de proyecto según sea necesario.
* Se deben utilizar herramientas de gestión de proyectos para realizar un seguimiento del progreso y gestionar las tareas de manera efectiva.

**Sugerencias para mejorar la precisión de la clasificación automática:**

* Utilizar una variedad de algoritmos de IA para aprovechar diferentes fortalezas y minimizar sesgos.
* Entrenar los modelos de IA con una gran cantidad de datos de alta calidad.
* Implementar técnicas de aprendizaje continuo para mejorar los modelos de IA con el tiempo.
* Realizar una evaluación continua del rendimiento de los modelos de IA y realizar ajustes según sea necesario.

**Espero que esta información sea útil!**
