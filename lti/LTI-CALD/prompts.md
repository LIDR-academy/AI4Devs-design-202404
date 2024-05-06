# Promtps usados para el Diseño de un sistema de gestión de candidatos
# Asistente: Claude Sonnet

## Tabla de contenido
1. [Prompts Etapa de análisis de mercado](#etapa-de-análisis-de-mercado) 
2. [Prompts Etapa Backlog del producto](#backlog-del-producto-promtps-usados-para-el-diseño-de-historias-de-usuario)


## Etapa de análisis de mercado 
## Asistente: Claude Sonnet

#### Eres un experto en producto, con experiencia en sistemas ATS (Applicant-Tracking System). ¿Qué funcionalidades básicas tiene un sistema ATS? Descríbemelas en un listado, ordenado de mayor a menor prioridad.

#### ¿Qué beneficios obtiene el cliente de un sistema ATS para considerar su uso?

#### ¿Qué alternativas tiene a usar un sistema ATS y cuando pueden ser relevantes?

### ¿Cómo es el customer journey normal de un cliente que usa un sistema ATS? Descríbeme paso a paso todas las interacciones

#### ¿Qué sistemas ATS open source son más conocidos? Genera una lista Top cinco incluyendo para cada una: Descripción, Ventajas, Desventajas y dirección de enlace a su sitio web.


#### ¿Qué sistemas ATS comerciales son más conocidos? Compáralos en función de popularidad, costos y experiencia de usuario, y valora cuál sería mejor opción. Genera la lista top cinco y para cada uno agrega: Descripción, ventaja, desventaja y dirección de enlace a su sitio web.


## Etapa de Diseño básico del producto. Asistente: Claude Sonnet
#### Eres un analista de software experto. Estoy construyendo un sistema ATS (Applicant-Tracking System). Enumera y describe brevemente los casos de uso más importantes a implementar para lograr una funcionalidad básica

#### Representa estos casos de uso en el tipo de diagrama más adecuado usando el formato plantUML. Identifica claramente los diferentes actores, diferencia entre usuarios visitantes y usuarios autenticados. Acorde a la sintaxis y buenas prácticas UML, define y describe lo que sea necesario.


#### Eres un brillante arquitecto de software. Eres capaz de diseñar, explicar y diagramar los diferentes aspectos de un sistema de software. Estoy construyendo el sistema ATS. He aceptado las entidades que propones, con sus campos y relaciones. Se necesita agregar las siguientes funcionalidades para ser competitivos y que deben ser tomadas en cuenta en el modelo Entidad Relación:
1. El candidato podrá tener varias ubicaciones registradas para indicar su disponibilidad geográfica.
2. El candidato puede tener varios currículos de diferentes perfiles profesionales.
3. Las vacantes deben poseer fecha de publicación.
4. Todas las entidades deben tener fecha de creación del registro y fecha de última modificación.

¿Qué otras entidades del modelo de datos son importantes en un sistema ATS? Dame los campos más importantes de cada una y cómo se relacionan entre entidades.

El formato del diagrama  debe ser Mermaid


#### consolida todas las entidades propuestas en un único Diagrama ER en formato Mermaid.


## Visión del producto

#### a este nuevo sistema ATS lo llamaremos LTI, dame un descripción de este competitivo producto, el cual está orientado a:
1. Brindar la mejor experiencia a sus usuarios, dado que el sistema contará  con  asistente IA que les ayuda intuitivamente a alcanzar sus objetivos fácilmente.
2. El servicio será en la nube.
3. Se podrá interconectar fácilmente con otras aplicaciones.

Agrega y resalta cualquier otro aspecto que  maximice  el valor añadido de este nuevo producto y sus ventajas competitivas.


#### Genera un diagrama Lean Canvas para entender el modelo de negocio con esta nuevo producto LTI


#### Se necesita el Diseño del sistema LTI a alto nivel, tanto explicado como diagrama en formato Mermaid

#### Genera el Diagrama C4 del Sistema LTI hasta el nivel 1, El Contexto, en formato Mermaid


#### Se tiene como objetivo generar los cuatro niveles  del Diagrama C4 para el componente "API Gategate" del sistema LTI, para ello se requiere en formato Mermaid los cuatro diagramas:
- Nivel 1 Contexto.
- Nivel 2 Contenedores.
- Nivel 3 Componentes.
- Nivel 4 Código.



#### ¿en el sistema LTI cuáles son los componentes del contenedor "API Gateway"?


#### genera un diagrama de los componentes de "Api Gateway" en formato Mermaid


#### genera un diagrama de bloques de los componentes de "Api Gateway" en formato Mermaid


#### Genera un diagrama de bloques para el código del componente "Enrutamiento" del contenedor "Api Gateway"

#### Actuando como un excelente analizador y redactor de documentos, se requiere agregar una introducción y una conclusión al documento adjunto. Toma en cuenta los principios de escritura clara y concisa definidos por William Zinsser en 'Sobre escribir bien'. Mi objetivo es la simplicidad, la brevedad y un toque humano. Se requiere redacción en tercera persona.



## BACKLOG del Producto: Promtps usados para el Diseño de Historias de usuario
## Asistente: Claude Sonnet  
  
#### El en documento adjunto se establece el diseño inicial del sistema gestión de candidatos llamado LTI. Genera la lista de casos de uso identificados en el documento, incluye para cada caso de uso:

Título.
Descripción.
Actores.
Nivel de importancia.
Notas adicionales.  
  
### En la lista de casos de usos identificados, encuentro que faltan los siguientes que están presentes en el documento:

Publicar vacantes.
Realizar seguimiento de candidatos.
Evaluar candidatos.

Se requiere incluirlos a la lista cumpliendo con la plantilla:

Título.
Descripción.
Actores.
Nivel de importancia.
Notas adicionales.

Adicionalmente, se requiere un nuevo caso de uso donde el candidato pueda consultar las vacantes publicadas para realizar su postulación a la misma.  
  

### dado que eres un experto en UML, genera un diagrama de los 14 casos de usos identificados, toma en cuenta los actores y los tipos de asociaciones. Agrega comentarios donde se considere relevante.
La salida se espera en formato PlantUML  
  
### en el ámbito de metodologías ágiles de Desarrollo de software, ¿conoces el concepto "Historias de Usuario" y sus mejores prácticas? De ser afirmativo:
1. Genera una lista de las características de historias de usuario.
2. Genera una lista de las mejores prácticas para crear buenas historias de usuario.  

### ¡Excelente! aplicando en esas características y mejores prácticas descritas, genera las historias de usuario de los 14 casos de uso del sistema LTI.
Toma en cuenta la siguiente plantilla:
Template para Crear la Historia de Usuario:

Título de la Historia de Usuario.
Como [rol del usuario],
quiero [acción que desea realizar el usuario],
para que [beneficio que espera obtener el usuario].

Criterios de Aceptación:

[Detalle específico de funcionalidad]
[Detalle específico de funcionalidad]
[Detalle específico de funcionalidad]

Notas Adicionales:

[Cualquier consideración adicional]

Historias de Usuario Relacionadas:

[Relaciones con otras historias de usuario]

Prioridad.
Para la redacción toma en cuenta los principios de escritura clara y concisa definidos por William Zinsser en 'Sobre escribir bien'. Mi objetivo es la simplicidad, la brevedad y un toque humano.  


### continúa

### continúa

### Dadas las historias de usuario anteriores, ¿qué requisitos técnicos se necesitarían?

### Analiza las funcionalidades del sistema de gestión de candidatos LTI para identificar los cinco problemas más comunes que los usuarios podrían enfrentar y sugerir mejoras.

### Considera el backlog de producto conformado por las 14 historias definidas anteriormente para el sistema de gestión de candidatos LTI. Estima por cada historia de usuario en el backlog (genera una tabla markdown):

Impacto en el usuario y valor del negocio.
Urgencia basada en tendencias del mercado y feedback de usuarios.
Complejidad y esfuerzo estimado de implementación.
Riesgos y dependencias entre tareas.

### continúa






