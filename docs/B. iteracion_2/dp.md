🐾 Sistema de Gestión Veterinaria – Iteración 2: Development Plan (Sprint Backlog)

Objetivo: Implementar el módulo de gestión clínica, permitiendo registrar consultas, procedimientos y acceder al historial médico de cada mascota.

HU	DESCRIPCIÓN	CRITERIOS DE ACEPTACIÓN	TAREAS TÉCNICAS	PAREJA ASIGNADA	OBSERVACIONES
HU6 – Registro de Consulta Veterinaria	Como veterinario, quiero registrar una consulta con fecha, motivo, diagnóstico, tratamiento y veterinario responsable, para mantener un registro completo de la atención clínica.	• Todos los campos pueden completarse.
• La consulta se asocia automáticamente a la mascota y al veterinario logueado.	• Diseñar modelo Consulta (C#).
• Crear tabla Consultas en MySQL (FK a Mascotas y Usuarios).
• Desarrollar formulario de “Nueva Consulta” (UI).
• Implementar lógica de negocio para guardar la consulta.
• Pruebas de guardado y asociación automática.	Pareja B (Juan y María)	Se debe poder acceder al formulario desde la ficha de la mascota.
HU7 – Registro de Procedimientos (Vacunas, Intervenciones, Estudios)	Como veterinario, quiero registrar intervenciones, vacunas o estudios realizados, para mantener el seguimiento de los procedimientos clínicos.	• Se indica tipo de procedimiento y fecha.
• La información queda asociada a la mascota.	• Diseñar modelo Procedimiento (C#).
• Crear tabla Procedimientos (FK a Mascotas).
• Añadir campo tipo (Vacuna, Intervención, Estudio).
• Desarrollar formulario de “Nuevo Procedimiento” (UI).
• Reutilizar componentes del formulario de consulta si es posible.	Pareja A (Ana y Carlos)	Similar a HU6, pero más simple. Evaluar reutilización de vistas.
HU8 – Historial Clínico de Mascota	Como veterinario, quiero consultar el historial clínico completo de una mascota, para acceder a todas las consultas y procedimientos realizados.	• Se listan consultas, vacunas e intervenciones.
• Permite filtrar por fecha o tipo de procedimiento.	• Desarrollar vista “Historial Clínico” (UI).
• Crear consulta SQL (JOIN) que combine Consultas y Procedimientos.
• Mostrar resultados ordenados por fecha (más reciente primero).
• Añadir filtros por fecha y tipo en la UI.
• Validar rendimiento y usabilidad de la vista.	Pareja B (Juan y María)	Vista central del sprint: debe ser clara, ordenada e intuitiva.
HU5 – Consulta de Mascotas por Dueño	Como veterinario, quiero consultar todas las mascotas asociadas a un dueño, para acceder fácilmente al historial clínico de cada una.	• Se muestra una lista con las mascotas y su información básica.
• Desde la lista se puede acceder al historial clínico (HU8) de cada mascota.	• Modificar vista “Detalle de Dueño” (HU4).
• Añadir pestaña o sección “Mascotas Asociadas”.
• Implementar consulta SQL para traer las mascotas del dueño.
• Añadir botón “Ver Historial” en cada mascota.
• Probar navegación entre vistas (Dueño → Mascota → Historial).	Pareja A (Ana y Carlos)	Mejora la navegación general y conecta el trabajo del Sprint 1.
