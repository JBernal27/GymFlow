# GymFlow

GymFlow es una aplicación web diseñada para la administración integral de gimnasios: gestión de usuarios, planes, suscripciones y control de acceso/afiliaciones.

Contenido
--------
- [Descripción larga](#descripción-larga)
- [Funcionalidades principales](#funcionalidades-principales)
- [Casos de uso típicos](#casos-de-uso-típicos)
- [Modelo de datos (resumen)](#modelo-de-datos-resumen)
- [Tecnologías sugeridas](#tecnologías-sugeridas)
- [Autores](#autores)

Descripción larga
------------------

GymFlow centraliza las operaciones administrativas propias de un gimnasio, permitiendo a los equipos gestionar clientes, crear y modificar planes de entrenamiento y suscripción y controlar pagos. Está pensada para ser adaptable a centros de distintos tamaños —desde estudios pequeños hasta cadenas con múltiples sedes— y ofrece flujos claros para administradores, recepcionistas e instructores.

Funcionalidades principales
- Gestión de usuarios: alta, baja y edición de perfiles de clientes; historial de pagos y asistencias; notas y observaciones.
- Gestión de planes y productos: creación de planes mensuales, anuales o personalizados; definir precios, duración, beneficios y restricciones.
- Suscripciones y facturación: asignación de planes a usuarios, control de vigencia, renovaciones automáticas o manuales, y registro de pagos.
- Roles y permisos: perfiles para administradores, recepcionistas y usuarios
- Reportes y métricas: resumen de ingresos, usuarios activos, vencimientos próximos y tasa de retención.
- Integraciones opcionales: pasarelas de pago, sistemas de control de acceso/empuertas, y sincronización con calendarios.

Casos de uso típicos
- Registro de un nuevo cliente y asignación de plan.
- Renovación o cancelación de suscripción.

Modelo de datos (resumen)
- Usuario: datos personales, contacto, fecha de suscripción, historial de pagos y asistencias.
- Plan: nombre, descripción, duración, precio, beneficios.
- Suscripción: relación Usuario↔Plan, fecha de inicio, fecha de fin, estado (activa, vencida, cancelada), número de renovaciones.
- Pago: id, usuario, plan, método, fecha.
- Sede: nombre, descripcion, direccion, imagenes, horario.

Tecnologías sugeridas
- Backend: Python, JavaScript
- Base de datos: SQL Server
- Frontend: Por fijar
- Autenticación: Por fijar
- Control de versiones: Git, GitHub

Autores
-------
- Jose Manuel Bernal Yepes
    - GitHub: [JBernal27](https://github.com/JBernal27)
    - LinkedIn: [Jose Manuel Bernal Yepes](https://www.linkedin.com/in/jose-manuel-bernal-yepes-510315267/)
    - Correo: jomabeye@gmail.com

- Emmanuel Cardona Alvarez
    - GitHub: [Emmael2005](https://github.com/Emmael2005)
    - LinkedIn: [Emmanuel Cardona Alvarez](www.linkedin.com/in/emmanuel-cardona-39839b380)
    - Correo: emmaca1995@gmail.com 

-------
