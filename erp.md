# Especificación de requisitos de software

## Enunciado del problema

La veterinaria enfrenta actualmente el desafío de manejar una gran cantidad de datos relacionados con las mascotas. El área que presenta mayores dificultades es la clínica, debido a la necesidad de registrar individualmente a cada mascota. La principal expectativa con respecto a la solución es el ahorro de tiempo. 

## Clientes potenciales
 
El usuario principal será el veterinario y cuenta con un dispositivo para su implementación. 

## Solución propuesta 

Desarrollar una aplicación de escritorio que facilite la administración de datos clínicos de mascotas, el seguimiento de consultas e intervenciones y envío automatizado de recordatorios importantes de los dueños de las mascotas.

## Requisitos




ChatGPT
Dijiste:
Que requisitos funcionales y no funcionales podria tener este software? Cabe recalcar que esto es para una simulacion de metodologias agiles scrum.
# Especificación de requisitos de software

## Enunciado del problema

La veterinaria enfrenta actualmente el desafío de manejar una gran cantidad de datos relacionados con las mascotas. El área que presenta mayores dificultades es la clínica, debido a la necesidad de registrar individualmente a cada mascota. La principal expectativa con respecto a la solución es el ahorro de tiempo. 

## Clientes potenciales
 
El usuario principal será el veterinario y cuenta con un dispositivo para su implementación. 

## Solución propuesta 

Desarrollar una aplicación de escritorio que facilite la administración de datos clínicos de mascotas, el seguimiento de consultas e intervenciones y envío automatizado de recordatorios importantes de los dueños de las mascotas.

## Requisitos

- requisitos funcionales

 
## Arquitectura de software

Será una aplicación de escritorio hecha con el lenguaje C#, siguiendo una arquitetura MVC, la base de datos será MySQL
ChatGPT dijo:
Perfecto. Dado el contexto (una aplicación de escritorio en C# con arquitectura MVC y base de datos MySQL, desarrollada como simulación de metodología ágil Scrum), los requisitos funcionales y no funcionales deberían reflejar tanto la lógica del dominio (veterinaria) como las expectativas técnicas y de calidad del sistema.

🧩 Requisitos funcionales (RF)
Gestión de mascotas

RF1: El sistema debe permitir registrar una nueva mascota con datos como nombre, especie, raza, edad, sexo y peso.

RF2: El sistema debe permitir modificar y eliminar los datos de una mascota existente.

RF3: El sistema debe permitir asociar cada mascota con su dueño (cliente).

Gestión de dueños

RF4: El sistema debe permitir registrar y editar los datos personales del dueño (nombre, DNI, teléfono, correo, dirección).

RF5: El sistema debe permitir consultar el historial de mascotas asociadas a un dueño.

Gestión clínica

RF6: El sistema debe permitir registrar una consulta clínica indicando fecha, motivo, diagnóstico, tratamiento y veterinario responsable.

RF7: El sistema debe permitir registrar intervenciones quirúrgicas, vacunas o estudios realizados.

RF8: El sistema debe permitir consultar el historial clínico completo de una mascota.

Recordatorios automáticos

RF9: El sistema debe generar recordatorios automáticos para vacunaciones, controles o tratamientos programados.

RF10: El sistema debe permitir configurar la frecuencia y medio de envío de recordatorios (por ejemplo, correo electrónico o notificación local).

Gestión de usuarios del sistema

RF11: El sistema debe permitir el inicio de sesión de veterinarios mediante usuario y contraseña.

RF12: El sistema debe restringir el acceso a funciones según el rol del usuario (por ejemplo, administrador o veterinario asistente).

Reportes e informes

RF13: El sistema debe permitir generar informes de consultas realizadas por periodo de tiempo.

RF14: El sistema debe permitir exportar informes a formato PDF o Excel.

Base de datos

RF15: El sistema debe almacenar toda la información en una base de datos MySQL.

RF16: El sistema debe permitir realizar copias de seguridad (backups) de la base de datos.

⚙️ Requisitos no funcionales (RNF)
1. Rendimiento
RNF1: Las consultas y operaciones CRUD deben ejecutarse en menos de 2 segundos bajo condiciones normales de carga.

RNF2: El sistema debe soportar al menos 10.000 registros de mascotas sin degradación perceptible del rendimiento.

2. Usabilidad
RNF3: La interfaz debe ser intuitiva y fácil de usar para personal no técnico.

RNF4: Debe utilizar componentes visuales consistentes (menús, formularios, botones, íconos).

RNF5: Debe incluir mensajes de error y confirmación claros.

3. Mantenibilidad
RNF6: El sistema debe estar desarrollado bajo el patrón de arquitectura MVC para facilitar mantenimiento y escalabilidad.

RNF7: El código debe seguir convenciones de nomenclatura y estar documentado.

4. Seguridad
RNF8: Las contraseñas de los usuarios deben almacenarse cifradas en la base de datos.

RNF9: El sistema debe validar los datos ingresados por el usuario para evitar inyecciones SQL o errores de tipo.

5. Confiabilidad y disponibilidad
RNF10: El sistema debe permitir recuperarse de fallos mediante restauración desde una copia de seguridad.

RNF11: La aplicación debe garantizar la persistencia de los datos ante cierres inesperados.

6. Compatibilidad
RNF12: La aplicación debe ser compatible con sistemas operativos Windows 10 y superiores.

RNF13: El sistema debe conectarse a una instancia local o remota de MySQL 8.0 o superior.

7. Portabilidad
RNF14: La aplicación debe poder instalarse fácilmente mediante un ejecutable (.exe) con dependencias incluidas (.NET Runtime).

RNF15: No debe requerir conexión a Internet para su funcionamiento principal (solo para recordatorios por correo, si aplica).

¿Querés que te los formatee en una tabla tipo documento de requisitos de producto (Product Backlog inicial) como se usa en Scrum (con prioridad y descripción resumida)? Podría servirte para presentarlo como parte de la simulación ágil.

Dijiste:
Simplifica esto y agregalos en la seccion de requerimientos funcionales del archivo.md que te copie. 
# Especificación de requisitos de software

## Enunciado del problema

La veterinaria enfrenta actualmente el desafío de manejar una gran cantidad de datos relacionados con las mascotas. El área que presenta mayores dificultades es la clínica, debido a la necesidad de registrar individualmente a cada mascota. La principal expectativa con respecto a la solución es el ahorro de tiempo. 

## Clientes potenciales
 
El usuario principal será el veterinario y cuenta con un dispositivo para su implementación. 

## Solución propuesta 

Desarrollar una aplicación de escritorio que facilite la administración de datos clínicos de mascotas, el seguimiento de consultas e intervenciones y envío automatizado de recordatorios importantes de los dueños de las mascotas.

## Requisitos

 #Requisitos funcionales
-Permitir registrar, editar y eliminar datos de mascotas (nombre, especie, raza, edad, peso, etc.).

-Asociar cada mascota con su respectivo dueño.

-Registrar y consultar datos de dueños (nombre, contacto, dirección, etc.).

-Registrar consultas clínicas con información de diagnóstico, tratamiento y veterinario responsable.

-Registrar intervenciones, vacunaciones o estudios realizados.

-Consultar el historial clínico completo de una mascota.

-Generar recordatorios automáticos de vacunación, controles o tratamientos.

-Gestionar usuarios del sistema con autenticación mediante usuario y contraseña.

-Generar reportes de consultas y tratamientos por periodo.

-Almacenar toda la información en una base de datos MySQL.

-Permitir realizar copias de seguridad de la base de datos.

 #Requisitos no funcionales
-Interfaz simple e intuitiva, orientada a uso por personal veterinario.

-Respuesta rápida en operaciones CRUD (menos de 2 segundos en condiciones normales).

-Cumplimiento del patrón MVC para facilitar mantenimiento y escalabilidad.

-Cifrado de contraseñas y validación de datos de entrada.

-Compatible con Windows 10 o superior y MySQL 8.0 o superior.

-Funcionamiento local sin requerir conexión a Internet (excepto para recordatorios por correo).

## Arquitectura de software

Será una aplicación de escritorio hecha con el lenguaje C#, siguiendo una arquitetura MVC, la base de datos será MySQL
