# Sistema de Gestión Veterinaria  
### Historias de Usuario – Documento Funcional

---

## Gestión de Mascotas

###  **HU1 – Registrar Mascota**
**Como veterinario,**  
quiero registrar una nueva mascota con sus datos básicos (nombre, especie, raza, edad, sexo y peso),  
**para** mantener un control completo de los pacientes.

**Criterios de aceptación:**
- Permite ingresar todos los datos obligatorios.
- El sistema valida que no existan campos vacíos.

---

###  **HU2 – Modificar o Eliminar Mascota**
**Como veterinario,**  
quiero poder editar o eliminar los datos de una mascota existente,  
**para** mantener actualizada la información del sistema.

**Criterios de aceptación:**
- La edición permite guardar los cambios correctamente.
- La eliminación requiere confirmación del usuario.

---

###  **HU3 – Asociar Mascota a Dueño**
**Como veterinario,**  
quiero vincular cada mascota con su respectivo dueño,  
**para** acceder rápidamente a la información del propietario.

**Criterios de aceptación:**
- La mascota queda asociada a un dueño registrado.
- No se permite registrar mascotas sin dueño.

---

##  Gestión de Dueños

###  **HU4 – Registrar o Editar Dueño**
**Como veterinario o asistente,**  
quiero registrar y actualizar los datos personales de los dueños (nombre, DNI, teléfono, correo, dirección),  
**para** mantener una base de datos precisa de clientes.

**Criterios de aceptación:**
- Los datos se almacenan correctamente.
- Los campos obligatorios se validan antes de guardar.

---

###  **HU5 – Consultar Historial de Mascotas por Dueño**
**Como veterinario,**  
quiero consultar todas las mascotas asociadas a un dueño,  
**para** conocer su historial de atención.

**Criterios de aceptación:**
- Se muestra una lista con las mascotas y su información básica.
- Desde la lista se puede acceder al historial clínico de cada mascota.

---

##  Gestión Clínica

###  **HU6 – Registrar Consulta Clínica**
**Como veterinario,**  
quiero registrar una consulta con fecha, motivo, diagnóstico, tratamiento y veterinario responsable,  
**para** llevar un seguimiento médico de cada mascota.

**Criterios de aceptación:**
- Todos los campos pueden completarse.
- La consulta se asocia automáticamente a la mascota y al veterinario.

---

###  **HU7 – Registrar Procedimientos Médicos**
**Como veterinario,**  
quiero registrar intervenciones, vacunas o estudios realizados,  
**para** mantener actualizado el historial clínico.

**Criterios de aceptación:**
- Se indica tipo de procedimiento y fecha.
- La información queda asociada a la mascota.

---

###  **HU8 – Consultar Historial Clínico**
**Como veterinario,**  
quiero consultar el historial clínico completo de una mascota,  
**para** conocer su evolución médica.

**Criterios de aceptación:**
- Se listan consultas, vacunas e intervenciones.
- Permite filtrar por fecha o tipo de procedimiento.

---

##  Recordatorios Automáticos

###  **HU9 – Generar Recordatorios Automáticos**
**Como veterinario,**  
quiero que el sistema genere recordatorios de vacunaciones, controles o tratamientos,  
**para** asegurar el cumplimiento del calendario médico.

**Criterios de aceptación:**
- Se generan recordatorios según las fechas programadas.
- Los recordatorios pueden visualizarse o enviarse automáticamente.

---

###  **HU10 – Configurar Frecuencia y Medio de Recordatorios**
**Como usuario del sistema,**  
quiero configurar la frecuencia y el medio de envío de los recordatorios,  
**para** adaptarlos a las preferencias de los clientes.

**Criterios de aceptación:**
- Se puede elegir entre correo electrónico o notificación local.
- El sistema guarda las preferencias de cada usuario.

---

##  Gestión de Usuarios del Sistema

###  **HU11 – Inicio de Sesión de Veterinarios**
**Como veterinario,**  
quiero iniciar sesión con usuario y contraseña,  
**para** acceder al sistema de forma segura.

**Criterios de aceptación:**
- El sistema valida credenciales.
- Se muestran mensajes de error si los datos son incorrectos.

---

###  **HU12 – Control de Acceso por Roles**
**Como administrador,**  
quiero definir permisos según el rol del usuario,  
**para** restringir el acceso a ciertas funciones.

**Criterios de aceptación:**
- Solo administradores pueden modificar roles.
- Cada usuario visualiza solo las funciones que le corresponden.

---

##  Reportes e Informes

###  **HU13 – Generar Informes de Consultas**
**Como veterinario o administrador,**  
quiero generar informes de consultas por periodo de tiempo,  
**para** analizar la actividad del consultorio.

**Criterios de aceptación:**
- Se puede filtrar por fechas y veterinario.
- El informe se muestra en pantalla.

---

### ✅ **HU14 – Exportar Informes**
**Como usuario,**  
quiero exportar los informes a PDF o Excel,  
**para** archivarlos o compartirlos.

**Criterios de aceptación:**
- Se permite elegir el formato.
- El archivo generado contiene los datos visibles en pantalla.

---

##  Base de Datos y Seguridad

###  **HU15 – Almacenamiento de Información**
**Como desarrollador o administrador,**  
quiero que toda la información se guarde en una base de datos MySQL,  
**para** asegurar integridad y persistencia de datos.

**Criterios de aceptación:**
- La base de datos debe estar normalizada y correctamente estructurada.

---

###  **HU16 – Copias de Seguridad**
**Como administrador del sistema,**  
quiero realizar copias de seguridad de la base de datos,  
**para** prevenir pérdidas de información.

**Criterios de aceptación:**
- Permite generar backups manuales o programados.
- El sistema confirma la creación correcta del respaldo.

---
 **Documento completo, estilizado y listo para entregar.**

Si querés, también puedo:
 agregar numeración de HU en tabla resumen  
 versión para Trello, Jira o Notion  
 añadir diagramas UML, ERD o casos de uso  
¿Querés que lo convierta en PDF o presentación?
