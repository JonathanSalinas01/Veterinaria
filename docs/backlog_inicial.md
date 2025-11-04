Gestión de mascotas
HU1 – Registrar mascota

Como veterinario,

quiero registrar una nueva mascota con sus datos básicos (nombre, especie, raza, edad, sexo y peso),

para mantener un control completo de los pacientes.
Criterios de aceptación:

Se debe poder ingresar todos los datos obligatorios.

El sistema valida que no existan campos vacíos.

HU2 – Modificar o eliminar mascota

Como veterinario,

quiero poder editar o eliminar los datos de una mascota existente,

para mantener actualizada la información del sistema.
Criterios de aceptación:

Se debe permitir guardar los cambios realizados.

La eliminación debe requerir confirmación del usuario.

HU3 – Asociar mascota a dueño

Como veterinario,

quiero vincular cada mascota con su respectivo dueño,

para poder acceder rápidamente a la información del propietario.
Criterios de aceptación:

La mascota debe quedar asociada a un dueño registrado.

No se permite una mascota sin dueño asignado.

👤 Gestión de Dueños

HU4 – Registrar o editar dueño

Como veterinario o asistente,

quiero registrar y actualizar los datos personales de los dueños (nombre, DNI, teléfono, correo, dirección),

para mantener una base de datos precisa de los clientes.
Criterios de aceptación:

Los datos deben almacenarse correctamente en la base de datos.

Los campos obligatorios deben validarse antes de guardar.

HU5 – Consultar historial de mascotas por dueño

Como veterinario,

quiero consultar todas las mascotas asociadas a un dueño,

para conocer su historial de atención.
Criterios de aceptación:

Se debe mostrar la lista de mascotas y su información básica.

Desde el listado se debe poder acceder al historial clínico de cada mascota.

🩺 Gestión Clínica

HU6 – Registrar consulta clínica

Como veterinario,

quiero registrar una consulta con fecha, motivo, diagnóstico, tratamiento y veterinario responsable,

para llevar un seguimiento médico de cada mascota.
Criterios de aceptación:

Todos los campos deben poder completarse.

La consulta se asocia automáticamente a la mascota y al veterinario.

HU7 – Registrar procedimientos médicos

Como veterinario,

quiero registrar intervenciones, vacunas o estudios realizados,

para mantener actualizado el historial clínico.
Criterios de aceptación:

Se debe indicar tipo de procedimiento y fecha.

La información queda asociada a la mascota.

HU8 – Consultar historial clínico

Como veterinario,

quiero consultar el historial clínico completo de una mascota,

para conocer su evolución médica.
Criterios de aceptación:

El sistema debe listar todas las consultas, vacunas e intervenciones.

Debe permitir filtrado por fecha o tipo de procedimiento.

🔔 Recordatorios Automáticos

HU9 – Generar recordatorios automáticos

Como veterinario,

quiero que el sistema genere recordatorios de vacunaciones, controles o tratamientos,

para asegurar el cumplimiento del calendario médico.
Criterios de aceptación:

El sistema debe crear recordatorios según las fechas programadas.

Los recordatorios deben visualizarse o enviarse automáticamente.

HU10 – Configurar frecuencia y medio de recordatorios

Como usuario del sistema,

quiero configurar la frecuencia y el medio de envío de los recordatorios,

para adaptarlos a las preferencias de los clientes.
Criterios de aceptación:

Se debe poder elegir entre correo electrónico o notificación local.

El sistema guarda las preferencias de cada usuario.

👩‍⚕️ Gestión de Usuarios del Sistema

HU11 – Inicio de sesión de veterinarios

Como veterinario,

quiero iniciar sesión con usuario y contraseña,

para acceder a las funciones del sistema de forma segura.
Criterios de aceptación:

El sistema valida credenciales y muestra mensajes de error si son incorrectas.

HU12 – Control de acceso por roles

Como administrador,

quiero definir permisos según el rol del usuario,

para restringir el acceso a ciertas funciones.
Criterios de aceptación:

Solo los administradores pueden modificar roles.

Cada usuario ve únicamente las funciones que le corresponden.

📊 Reportes e Informes

HU13 – Generar informes de consultas

Como veterinario o administrador,

quiero generar informes de consultas realizadas por periodo de tiempo,

para analizar la actividad del consultorio.
Criterios de aceptación:

Se debe poder filtrar por fechas y veterinario.

El sistema genera el informe en pantalla.

HU14 – Exportar informes

Como usuario,

quiero exportar los informes a PDF o Excel,

para compartir o archivar la información.
Criterios de aceptación:

El sistema debe permitir elegir el formato.

El archivo generado debe contener los datos visibles en pantalla.

💾 Base de Datos y Seguridad

HU15 – Almacenamiento de información

Como desarrollador o administrador,

quiero que toda la información se guarde en una base de datos MySQL,

para asegurar la integridad y persistencia de los datos.
Criterios de aceptación:

La base de datos debe estar correctamente estructurada y normalizada.

HU16 – Copias de seguridad

Como administrador del sistema,

quiero poder realizar copias de seguridad de la base de datos,

para prevenir pérdida de información ante fallos.
Criterios de aceptación:

Se debe poder generar un backup manual o programado.

El sistema confirma la correcta creación del archivo de respaldo.
