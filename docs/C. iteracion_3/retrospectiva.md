Iteración 3: Retrospectiva

Fecha: (Fin del Sprint 3)

¿Qué salió bien?

La HU13 y HU14 se complementaron muy bien. El equipo B (Juan y María) logró integrar la librería de PDF sin mayores problemas.

La funcionalidad de Backup (HU16) fue simple pero muy valorada por el cliente (Product Owner) por la seguridad que brinda.

Los recordatorios visuales (HU9) funcionan y dan pie a la futura automatización de correos.

¿Qué no salió tan bien?

La generación de PDF (HU14) es un poco lenta cuando el informe de consultas (HU13) devuelve muchos resultados (más de 500).

Se detectó un bug menor en el Sprint 1: Si se elimina un Dueño, las mascotas quedan "huérfanas" (no se implementó borrado en cascada o restricción).

Acciones de Mejora (Para el próximo Sprint)

Optimización: Investigar cómo optimizar la generación de PDF (posiblemente con generación en segundo plano si los reportes son muy grandes).

Manejo de Bugs: Crear una política para bugs. El bug de "Dueños huérfanos" se añade al Product Backlog y será priorizado por el Product Owner para el siguiente sprint.

Revisión de Arquitectura: Asegurar que todas las relaciones de BD tengan las restricciones de borrado (DELETE) correctas.
