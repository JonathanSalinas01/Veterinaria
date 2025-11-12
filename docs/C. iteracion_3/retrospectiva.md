## Iteración 3: Retrospectiva

**Fecha:** (Fin del Sprint 3)

---

##  ¿Qué salió bien?

- La **HU13** y **HU14** se complementaron muy bien.  
  El equipo **B (Juan y María)** logró integrar la librería de **PDF** sin mayores problemas.  
- La **funcionalidad de Backup (HU16)** fue simple pero muy valorada por el cliente (**Product Owner**) por la seguridad que brinda.  
- Los **recordatorios visuales (HU9)** funcionan correctamente y abren la posibilidad de futuras automatizaciones de correos.

---

##  ¿Qué no salió tan bien?

- La **generación de PDF (HU14)** es algo lenta cuando el **informe de consultas (HU13)** devuelve más de **500 resultados**.  
- Se detectó un **bug menor del Sprint 1**: si se elimina un Dueño, las mascotas quedan “huérfanas”, ya que no se implementó el **borrado en cascada o restricción** correspondiente.

---

##  Acciones de Mejora (para el próximo Sprint)

- **Optimización:** Investigar formas de optimizar la generación de PDF, considerando la **generación en segundo plano** para reportes extensos.  
- **Manejo de Bugs:** Crear una **política formal de gestión de bugs**.  
  El bug de *Dueños huérfanos* se añade al **Product Backlog** y será priorizado por el Product Owner
