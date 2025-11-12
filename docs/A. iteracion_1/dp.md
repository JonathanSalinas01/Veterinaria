🐾 Sistema de Gestión Veterinaria – Iteración 1: Development Plan (Sprint Backlog)

Objetivo: Establecer las entidades centrales (Dueños, Mascotas) y la autenticación del sistema.

HU	DESCRIPCIÓN	CRITERIOS DE ACEPTACIÓN	TAREAS TÉCNICAS	PAREJA ASIGNADA	OBSERVACIONES
HU4 – Registro y Actualización de Dueños	Como veterinario o asistente, quiero registrar y actualizar los datos personales de los dueños (nombre, DNI, teléfono, correo, dirección), para mantener actualizada la información de los clientes.	• Los datos se almacenan correctamente.
• Los campos obligatorios (Nombre, DNI, Teléfono) se validan antes de guardar.	• Diseñar modelo de datos Dueño (C#).
• Crear tabla Dueños en MySQL.
• Desarrollar formulario de Alta/Edición de Dueño (UI).
• Implementar lógica de negocio (CRUD) para Dueños.
• Validar que el DNI sea único.
• Pruebas unitarias para el servicio de Dueños.	Pareja A (Ana y Carlos)	Se prioriza esta HU para poder asociar mascotas en HU3.
HU1 – Registro de Mascota	Como veterinario, quiero registrar una nueva mascota con sus datos básicos (nombre, especie, raza, edad, sexo y peso), para mantener un control completo de los pacientes.	• Permite ingresar todos los datos obligatorios.
• El sistema valida que no existan campos vacíos.	• Diseñar modelo de datos Mascota (C#).
• Crear tabla Mascotas en MySQL.
• Desarrollar formulario de Alta de Mascota (UI).
• Implementar lógica de negocio (CRUD) para Mascotas.
• Probar inserción y validación de datos en la base de datos.	Pareja B (Juan y María)	El formulario de alta debe incluir la selección del dueño (HU3).
HU3 – Asociación Mascota–Dueño	Como veterinario, quiero vincular cada mascota con su respectivo dueño, para mantener la relación entre pacientes y sus propietarios.	• La mascota queda asociada a un dueño registrado.
• No se permite registrar mascotas sin dueño.	• Añadir clave foránea id_dueño en la tabla Mascotas.
• Modificar el formulario de alta de mascota para incluir un buscador/selector de Dueños (usando HU4).
• Pruebas de integridad referencial en base de datos.	Pareja B (Juan y María)	Se desarrolla en conjunto con HU1.
HU11 – Autenticación de Usuario	Como veterinario, quiero iniciar sesión con usuario y contraseña, para acceder de forma segura al sistema.	• El sistema valida credenciales correctamente.
• Se muestran mensajes de error si los datos son incorrectos.
• Las contraseñas se almacenan cifradas.	• Diseñar modelo de datos Usuario (C#).
• Crear tabla Usuarios (usuario, password_hash).
• Implementar lógica de cifrado (hashing) de contraseñas.
• Desarrollar vista de Login (UI).
• Implementar el servicio de autenticación.
• Crear usuario admin por defecto.	Pareja A (Ana y Carlos)	Se usará para restringir el acceso al sistema.
