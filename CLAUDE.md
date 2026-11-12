## Spec-Driven Development (SDD) Workflow

Cuando se solicite crear una especificación o nueva funcionalidad (incluso al invocar `/spec-driven-development` o `/planning-and-task-breakdown`), NO generes un único `SPEC.md`. Crea siempre una carpeta en `specs/<nombre-kebab-case>/` con exactamente estos 3 archivos en orden secuencial, pidiendo aprobación antes de pasar al siguiente:

1. `01-requirements.md`: Contexto, historias de usuario, requisitos funcionales/no funcionales, casos borde, no-objetivos y criterios de aceptación verificables.
2. `02-design.md`: Arquitectura técnica, modelo de datos, contratos/interfaces, flujo de componentes y decisiones técnicas (basado estrictamente en `01-requirements.md`).
3. `03-tasks.md`: Lista de tareas atómicas con checkboxes (`- [ ]`), ordenadas por dependencia, indicando los archivos exactos a crear/modificar y su criterio de verificación.

Al implementar, actualiza los checkboxes en `03-tasks.md` conforme completes cada tarea.
