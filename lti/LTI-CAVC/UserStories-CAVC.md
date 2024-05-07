### HU-0001
**Acceso al Sistema ATS de LTI**
Como usuario,
quiero poder iniciar sesión en el sistema ATS de LTI,
para acceder a las funcionalidades del sistema según mi rol.

**Criterios de Aceptación:**
1. El usuario debe poder acceder a la página de inicio de sesión del sistema ATS de LTI.
2. Debe haber campos para ingresar el correo electrónico y la contraseña del usuario.
3. El sistema debe autenticar al usuario y permitirle acceder si las credenciales son correctas.
4. Se deben implementar medidas de seguridad, como el uso de HTTPS y la protección contra ataques de fuerza bruta.
5. Se debe proporcionar un mecanismo para recuperar la contraseña en caso de olvido.
6. El acceso al sistema debe estar restringido según el rol del usuario, permitiendo el acceso solo a las funcionalidades correspondientes a ese rol.

**Notas Adicionales:**
- Es crucial garantizar la seguridad y la privacidad de los datos de los usuarios al implementar el acceso al sistema.

**Historias de Usuario Relacionadas:**
- Esta historia de usuario es un requisito previo para todas las demás historias relacionadas con el uso del sistema ATS de LTI.
- - ---
### HU-0002
**Creación de Oferta de Trabajo**
Como reclutador,
quiero crear una nueva oferta de trabajo,
para publicar oportunidades de empleo en la empresa.

**Criterios de Aceptación:**
1. Debe haber una opción claramente identificada para crear una nueva oferta de trabajo.
2. El reclutador debe poder completar los detalles de la oferta, incluyendo título del puesto, responsabilidades, requisitos, ubicación y salario.
3. Debe haber campos disponibles para configurar criterios de filtrado para la selección automática de candidatos.
4. Una vez completados todos los detalles, el reclutador debe poder publicar la oferta en el sitio web y otros canales de reclutamiento.

**Notas Adicionales:**
- Es importante que la interfaz de usuario sea intuitiva y fácil de usar para que el reclutador pueda crear ofertas de trabajo de manera eficiente.

**Historias de Usuario Relacionadas:**
- Esta historia está relacionada con la historia "Gestión de Candidatos", ya que una vez publicada la oferta, el reclutador necesitará gestionar las candidaturas recibidas.

- - -
### HU-0003
**Edición de Oferta de Trabajo**
Como reclutador,
quiero poder editar una oferta de trabajo existente,
para corregir errores o actualizar la información relevante.

**Criterios de Aceptación:**
1. Debe haber una opción claramente identificada para editar una oferta de trabajo existente.
2. El reclutador debe poder modificar los detalles de la oferta, incluyendo título del puesto, responsabilidades, requisitos, ubicación y salario.
3. Debe haber campos disponibles para editar los criterios de filtrado para la selección automática de candidatos.
4. Una vez realizadas las modificaciones, el reclutador debe poder guardar los cambios y actualizar la oferta en el sitio web y otros canales de reclutamiento.

**Notas Adicionales:**
- Es importante proporcionar una opción de edición para que el reclutador pueda mantener actualizadas las ofertas de trabajo según sea necesario.

**Historias de Usuario Relacionadas:**
- Esta historia está relacionada con la historia "Gestión de Candidatos", ya que una vez editada la oferta, el reclutador necesitará gestionar las candidaturas recibidas.

- - -
### HU-0004
**Gestión de Candidatos** 
Como reclutador,
quiero poder revisar, evaluar y hacer un seguimiento de los candidatos que aplican para las vacantes,
para identificar y seleccionar a los candidatos más adecuados para las posiciones disponibles.

**Criterios de Aceptación:**
1. El reclutador debe poder acceder al sistema ATS de LTI e iniciar sesión.
2. Debe haber una opción claramente identificada para revisar los candidatos que han aplicado para una oferta de trabajo.
3. El reclutador debe poder ver los currículums y perfiles de los candidatos, incluyendo información como experiencia laboral, habilidades y educación.
4. Debe haber opciones disponibles para dejar comentarios y calificaciones sobre cada candidato.
5. El reclutador debe poder realizar entrevistas, pruebas de habilidades y evaluaciones técnicas según sea necesario.
6. Debe haber un sistema de seguimiento para mantener un registro del estado de cada candidato a lo largo del proceso de contratación.
7. El reclutador debe poder comunicarse con los candidatos a través del sistema para coordinar entrevistas o proporcionar actualizaciones sobre el proceso de selección.

**Notas Adicionales:**
- Es importante que la interfaz de usuario sea intuitiva y fácil de usar para que el reclutador pueda gestionar eficazmente los candidatos y avanzar en el proceso de contratación de manera eficiente.

**Historias de Usuario Relacionadas:**
- Esta historia está relacionada con las historias de usuario "Creación de Oferta de Trabajo" y "Edición de Oferta de Trabajo", ya que una vez publicadas las ofertas de trabajo, el reclutador necesitará gestionar las candidaturas recibidas para esas ofertas.

- - -
## Priorización de historias

| Historia de Usuario        | Impacto en el Usuario y Valor del Negocio | Urgencia Basada en Tendencias del Mercado y Feedback de Usuarios | Complejidad y Esfuerzo Estimado de Implementación | Riesgos y Dependencias entre Tareas |
|-----------------------------|-------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------|--------------------------------------|
| HU-0001: Acceso al Sistema ATS de LTI | Alta: Sin acceso, los usuarios no pueden utilizar ninguna funcionalidad del sistema. | Alta: Acceso es el primer paso para cualquier actividad en el sistema. | Baja: Implementar un sistema de inicio de sesión estándar. | Alta: Las otras historias dependen directamente de esta, cualquier problema en el acceso afectará a todas las funcionalidades. |
| HU-0002: Creación de Oferta de Trabajo | Alta: Permite a la empresa publicar nuevas oportunidades de trabajo y atraer talento. | Media: Importante para el crecimiento y reputación de la empresa, pero menos urgente que el acceso al sistema. | Media: Requiere un formulario de entrada de datos y lógica de validación. | Medio: Posibles riesgos en la validación de datos y la integración con otros sistemas de reclutamiento. |
| HU-0003: Edición de Oferta de Trabajo | Media: Permite mantener actualizadas las ofertas de trabajo según las necesidades de la empresa. | Baja: Menos urgente que la creación de ofertas, pero sigue siendo importante para mantener la precisión de la información. | Media: Similar a la creación de ofertas, pero con la adición de funcionalidad de edición. | Medio: Riesgo de conflicto de datos si no se gestiona correctamente la edición de ofertas. |
| HU-0004: Gestión de Candidatos | Alta: Facilita el proceso de selección de personal y la contratación de candidatos cualificados. | Alta: Importante para el éxito a largo plazo de la empresa, pero menos urgente que la creación y edición de ofertas. | Alta: Requiere una interfaz de usuario intuitiva y funcionalidades avanzadas de seguimiento y evaluación de candidatos. | Alto: Riesgos potenciales en la integración con sistemas externos, gestión de la privacidad de datos y complejidad de la lógica de negocio. |


Teniendo en cuenta la tabla anterior el orden priorizado de las historias sería:
1. HU-0001
2. HU-0004
3. HU-0002
4. HU-0003

**Conclusiones:**
Teniendo en contexto el sistema completo, las historias de usuario generadas son bastante buenas y coherentes, aun así es necesario guiar con cuidado como se divide el trabajo entre las diferentes historias.