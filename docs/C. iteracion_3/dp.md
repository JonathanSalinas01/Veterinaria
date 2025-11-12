🐾 Sistema de Gestión Veterinaria – Iteración 3: Development Plan (Sprint Backlog)

Objetivo: Implementar recordatorios automáticos y reportes básicos dentro del sistema.

HU	DESCRIPCIÓN	CRITERIOS DE ACEPTACIÓN	TAREAS TÉCNICAS	PAREJA ASIGNADA	OBSERVACIONES
HU9 – Recordatorios de Vacunaciones, Controles y Tratamientos	Como veterinario, quiero que el sistema genere recordatorios de vacunaciones, controles o tratamientos, para mantener un seguimiento oportuno de los pacientes.	• Se generan recordatorios según las fechas programadas.
• (Versión Sprint 3): Se muestra una alerta visual dentro del sistema (sin envío por correo).	• Añadir campo fecha_recordatorio en las tablas Consultas y Procedimientos.
• Crear módulo “Recordatorios Pendientes” en el dashboard principal.
• Implementar consulta SQL que busque recordatorios con fecha_recordatorio ≤ hoy.
• Probar visualización y actualización automática del listado.	Pareja A (Ana y Carlos)	La HU10 (configuración de envío de recordatorios) se implementará en un sprint futuro.
HU13 – Generación de Reportes de Consultas	Como veterinario o administrador, quiero generar informes de consultas por periodo de tiempo, para analizar la atención clínica y la carga de trabajo.	• Se puede filtrar por fechas y veterinario.
• El informe se muestra correctamente en pantalla.	• Diseñar vista “Generador de Reportes” (UI).
• Añadir selectores de fecha (“Desde”, “Hasta”) y de Veterinario (Usuario).
• Implementar lógica de negocio para consultar Consultas según filtros.
• Mostrar resultados en tabla dinámica.
• Validar precisión de los datos.	Pareja B (Juan y María)	La arquitectura MVC facilita la implementación gracias a la separación de lógica y vista.
HU14 – Exportación de Reportes a PDF	Como usuario, quiero exportar los informes a PDF o Excel, para compartir y respaldar la información generada.	• Se permite elegir el formato (solo PDF en este sprint).
• El archivo generado contiene los datos visibles en pantalla (de HU13).	• Investigar e integrar una librería para generación de PDF en C# (iTextSharp o similar).
• Añadir botón “Exportar a PDF” en la vista de reportes (HU13).
• Tomar los datos de la tabla y formatearlos correctamente en el PDF.
• Probar descarga y visualización del archivo generado.	Pareja B (Juan y María)	Tarea vinculada a HU13. Se aplican aprendizajes del Sprint 1 (investigación de librerías externas).
HU16 – Copias de Seguridad de la Base de Datos	Como administrador del sistema, quiero realizar copias de seguridad de la base de datos, para proteger la información ante posibles fallos o pérdidas.	• Permite generar backups manuales.
• El sistema confirma la creación correcta del respaldo.	• Crear sección “Administración” visible solo para usuarios con rol admin.
• Implementar lógica para ejecutar mysqldump desde C#.
• Añadir botón “Generar Backup” que solicite ubicación para guardar el archivo .sql.
• Probar creación y restauración del respaldo generado.	Pareja A (Ana y Carlos)	La programación automática de backups queda fuera del alcance de este sprint por su complejidad.
