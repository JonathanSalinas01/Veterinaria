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





