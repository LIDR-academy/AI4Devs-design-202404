
### Historias de Usuario para el Sistema ATS

1. **Historia de Usuario: Registro de Administrador**
   - **Como** administrador,
   - **Quiero** poder registrar mi perfil y el de mi empresa en el sistema,
   - **Para que** pueda gestionar la información de la empresa y añadir usuarios al sistema.
   - **Criterios de Aceptación**:
     1. El administrador debe poder completar un formulario con la información de la empresa.
     2. El sistema debe validar y almacenar la información de la empresa.
     3. El administrador debe poder añadir nuevos usuarios con roles específicos.

2. **Historia de Usuario: Publicación de Oferta de Empleo**
   - **Como** reclutador,
   - **Quiero** poder crear y publicar ofertas de empleo,
   - **Para que** los candidatos puedan encontrar y aplicar a las oportunidades laborales.
   - **Criterios de Aceptación**:
     1. El reclutador debe poder completar un formulario con detalles de la oferta de empleo, incluyendo título, descripción, habilidades requeridas, salario y modalidad de trabajo.
     2. El sistema debe permitir guardar y publicar la oferta de empleo en el perfil de la empresa.
     3. Los candidatos deben poder ver la oferta de empleo publicada.

3. **Historia de Usuario: Aplicación a Oferta de Empleo**
   - **Como** candidato,
   - **Quiero** poder buscar ofertas de empleo y enviar mi aplicación,
   - **Para que** pueda ser considerado para posiciones que coincidan con mis habilidades y experiencia.
   - **Criterios de Aceptación**:
     1. El candidato debe poder buscar ofertas de empleo utilizando filtros como posición, ubicación y salario.
     2. El candidato debe poder enviar su aplicación incluyendo su currículum y cualquier información adicional requerida.
     3. El sistema debe confirmar la recepción de la aplicación al candidato.

4. **Historia de Usuario: Evaluación de Aplicaciones**
   - **Como** reclutador,
   - **Quiero** que el sistema evalúe automáticamente las aplicaciones recibidas,
   - **Para que** pueda identificar rápidamente los candidatos más adecuados.
   - **Criterios de Aceptación**:
     1. El sistema debe utilizar un modelo de LLM para evaluar las aplicaciones basándose en criterios predefinidos.
     2. El reclutador debe recibir un resumen de las puntuaciones y recomendaciones para cada aplicación.
     3. El reclutador debe poder acceder a un panel donde se muestren todas las evaluaciones y sus detalles.



### Criterios de Priorización

1. **Valor para el Usuario**: Cuánto impacta la historia en la experiencia del usuario y en la consecución de sus objetivos.
2. **Urgencia/Necesidad**: Qué tan crítico es implementar esta funcionalidad pronto para el funcionamiento del sistema o para cumplir con plazos o requisitos legales/regulatorios.
3. **Dependencias**: Si la historia depende de otras historias o si otras historias dependen de ella, lo que puede alterar el orden de implementación.
4. **Esfuerzo de Desarrollo**: Evaluación del tiempo y recursos necesarios para implementar la historia, considerando la complejidad y los desafíos técnicos.

### Product Backlog Priorizado

1. **Historia de Usuario: Registro de Administrador**
   - **Prioridad**: Alta
   - **Razón**: Esta historia es fundamental para iniciar la configuración del sistema y permitir la gestión de usuarios y de la empresa. Es un bloque constructor esencial para todas las operaciones futuras dentro del sistema.

2. **Historia de Usuario: Publicación de Oferta de Empleo**
   - **Prioridad**: Alta
   - **Razón**: La capacidad de publicar ofertas de empleo es central para la funcionalidad del sistema ATS. Permite a los reclutadores comenzar el proceso de reclutamiento y es un paso necesario para atraer candidatos.

3. **Historia de Usuario: Aplicación a Oferta de Empleo**
   - **Prioridad**: Media
   - **Razón**: Aunque es crucial para la interacción de los candidatos con el sistema, depende de que las ofertas de empleo estén disponibles. Su prioridad sigue a la de la publicación de ofertas de empleo.

4. **Historia de Usuario: Evaluación de Aplicaciones**
   - **Prioridad**: Media
   - **Razón**: Esta historia aporta eficiencia y apoyo analítico al proceso de selección. No obstante, su implementación puede seguir a la de las aplicaciones, ya que requiere que haya datos de candidatos y ofertas para ser verdaderamente útil.

Esta priorización asegura que el desarrollo comience con las funcionalidades que establecen la base y estructura del sistema, permitiendo luego expandirse hacia características que mejoran y enriquecen la experiencia y eficiencia del proceso de reclutamiento.


