# Prompts

Conversacion completa: https://chat.openai.com/share/a375432d-c237-45a4-98f4-a18ca67dead9

He mantenido dos conversaciones, ambas con Chat GPT 3.5. En una de ellas he ido ampliando conocimientos sobre historias de usuarios, backlog, técnicas para priorizar, le he pedido que me genere una plantilla para describir con detalle las historias de usuario y le he pedido que me genere un script para poder generar los tickets de forma automática en Trello. En otra he ido generando las historias de usuario, el backlog y los tickets.

## Generación de plantilla para las historias de usuario y tickets de Trello

-- **Prompt**: Quiero que actues como product manager de LTI. Crearemos User Stories en Trello. No te concentres en ellas en este momento. 
En su lugar, piensa y explicame cuales son las campos que consideras que deberian contener las User Stories

-- **Prompt**: Quita "historial de cambios" y "asignado a", así como estimación de esfuerzo. Escribe el template en formato Markdown


## Generación del backlog
He pensado en usar la API de Trello para generar de manera programática el backlog, pero siendo que no tenía todavía claro todos los campos, así como etiquetas y dependencias, he pensado que se generarían demasiados backlogs en Trello que acabarían a la basura.

Por otro lado, la generación en formato markdown, no me ha resultado lo útil que esperaba, ya que al copiar en el campo de descripción, se pega en modo código fuente.  Lo que funcionana bien era copiar con el formato que aparece en HTML.

-- **Prompt**: Generame, en formato markdown, las user stories necesarias para el primer usecase que se definió durante este chat. Aquí escribo, como referencia, de qué se trataba
### Caso de Uso 1: Creación y Gestión de Ofertas de Trabajo
Los reclutadores pueden crear nuevas ofertas de trabajo dentro de la aplicación LTI. Los reclutadores pueden especificar detalles como el título del puesto, la descripción del trabajo, los requisitos y los beneficios. Una vez creada la oferta, pueden gestionarla, editarla o eliminarla según sea necesario.


-- **Prompt**: La user story de "eliminar" debería de entenderse más bien como "cerrar" o "dejar inactiva" la oferta de trabajo. Puede tener cierta utilidad que se puedan ver ofertas pasadas que ya no están activas.
Asimismo, la gestion de ofertas, debería de incluir el poder listarlas, así como filtrarlas en función de estado, y otros campos de la misma. 
Reescribe las user stories teniendo en cuenta esto, y acuerdate de hacerlo en formato markdown

-- **Prompt**: escribelas en formato markdown, que yo lo pueda copiar, como si fuera código


-- **Prompt**: Generame, de nuevo en formato markdown y basado en el template anterior, las user stories necesarias para el segundo use case:
**Caso de Uso 2: Revisión de Candidatos**
En este caso de uso, los técnicos de RRHH revisan las solicitudes de los candidatos que han aplicado a una oferta de trabajo. Pueden ver los perfiles de los candidatos, evaluar sus habilidades y experiencia, y tomar decisiones de contratación, como programar entrevistas o rechazar una solicitud. 


-- **Prompt**: Has olvidado mencionar las dependencias de estas user stories respecto a las de los use cases anteriores


## Generación de los tickets de trabajo

-- **Prompt**: Teniendo en cuenta todo lo anterior, incluyendo el modelo de datos y la arquitectura técnica de la aplicación LTI, te voy a pedir que me generes las tareas técnicas para algunas user stories. Me puedes confirmar que tienes todos los elementos que he mencionado? Contéstame con un sí o un no

-- **Prompt**: Entonces, genera las tareas técnicas, separando backend, frontend y otros, si necesiario, acerca de la primera user story "US1: Crear nueva oferta de trabajo"

-- **Prompt**: Dame estimaciones, en story points, de cada una de las tareas
