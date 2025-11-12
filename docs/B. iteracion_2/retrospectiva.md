Iteración 2: Retrospectiva

Fecha: (Fin del Sprint 2)

¿Qué salió bien?

La acción de mejora de "hacer mockups" (de la retro anterior) fue un éxito. La vista del Historial Clínico (HU8) se desarrolló rápidamente porque el diseño estaba claro.

Reutilizamos muchos componentes de UI del Sprint 1, lo que ahorró tiempo.

La lógica de negocio de las consultas (HU6) y procedimientos (HU7) quedó bien encapsulada.

¿Qué no salió tan bien?

La consulta SQL para el historial (HU8) fue más compleja de lo pensado, ya que combinar dos tablas (Consultas y Procedimientos) en una sola línea de tiempo requirió un UNION en lugar de un JOIN simple.

El filtro por tipo de procedimiento (HU8) no se pudo implementar; solo se completó el filtro por fecha.

Acciones de Mejora (Para el próximo Sprint)

Refinamiento de HU: Ser más detallados al estimar HUs que involucren consultas complejas a la BD. Si una consulta es difícil, debe listarse como una tarea técnica separada y de alta prioridad.

Deuda Técnica: Se anota la falta del "filtro por tipo" (HU8) en el Product Backlog. El Product Owner decidirá si se prioriza en el siguiente sprint o más adelante.
