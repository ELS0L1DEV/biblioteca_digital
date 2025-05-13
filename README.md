## Bienvenido al repositorio para el proyecto de la materia de Verificacion y Validacion de Software

## El proyecto esta hecho por
Naranjo Torres Joshua Emmanuel
<br>
Maya Martínez Esteban.
<br>
Rodríguez Fernando.
<br>
González García José Ángel.
<br>
Espinoza Palacios Stephany.
<br>
Mejia Morales Jonathan Mishel. 

## Especificaciones:
<br>

## Introduccion
Este proyecto consiste en el desarrollo de una aplicación móvil para la biblioteca del Tecnológico de Estudios Superiores de Coacalco (TESCo), 
utilizando Android Studio como entorno de desarrollo y Azure Cosmos DB como base de datos en la nube. 
La aplicación tiene como objetivo optimizar la gestión de préstamos, mejorar el acceso a la información bibliográfica 
y brindar una mejor experiencia a los estudiantes y usuarios de la biblioteca mediante herramientas tecnológicas modernas.


## 2. Objetivos
## Objetivo General
Desarrollar una aplicación móvil para la biblioteca del TESCo que facilite la gestión de préstamos de libros,
permita la búsqueda y reserva en línea de material bibliográfico, muestre información detallada de los libros disponibles 
y registre el historial de préstamos de cada usuario, utilizando Android Studio para el desarrollo y Azure Cosmos DB como base de datos en la nube.

## Objetivos Específicos
1.	Implementar un sistema de registro y autenticación para usuarios (alumnos y docentes), permitiendo la creación de perfiles personalizados.
2.	Desarrollar un módulo de búsqueda y reserva de libros, facilitando el acceso al catálogo bibliográfico desde la aplicación.
3.	Diseñar una interfaz intuitiva y funcional que permita a los usuarios consultar la disponibilidad de libros y realizar reservaciones.
4.	Crear un historial de préstamos para cada usuario, registrando fechas de préstamo, devoluciones y renovaciones.
5.	Integrar un sistema de notificaciones push para recordar fechas de devolución, vencimientos o reservas disponibles.
6.	Optimizar el almacenamiento de datos mediante Azure Cosmos DB, garantizando la seguridad y disponibilidad de la información en la nube.
7.	Desarrollar un módulo de administración para el personal de la biblioteca, con funciones como registrar nuevos libros, actualizar información y gestionar reservas.

## 4. Funcionalidades Principales
4.1. Registro y Gestión de Usuarios
•	Registro de alumnos y docentes con datos personales y credenciales institucionales.
•	Creación de perfiles individuales con historial de préstamos y reservas.
•	Autenticación de usuarios mediante correo institucional y contraseña.
4.2. Consulta y Reserva de Libros
•	Búsqueda de libros por título, autor, categoría o ISBN.
•	Visualización de disponibilidad y ubicación dentro de la biblioteca.
•	Opción de reservar libros desde la aplicación.
4.3. Historial de Préstamos
•	Registro de todos los libros prestados, con fechas de préstamo y devolución.
•	Posibilidad de renovar préstamos desde la aplicación.
•	Control del estado de cada libro (prestado, disponible, en espera).
 4.4. Notificaciones y Recordatorios
•	Notificaciones push para recordar fechas de devolución y disponibilidad de reservas.
•	Alertas sobre nuevos libros o materiales agregados a la biblioteca.
•	Comunicaciones institucionales desde la biblioteca hacia los usuarios.
 4.5. Gestión Administrativa
•	Módulo para personal de la biblioteca con funciones como agregar, editar o eliminar libros.
•	Administración de reservas, devoluciones y renovaciones.
•	Reportes básicos de uso y estadísticas de préstamos.
4.6. Integración con Azure Cosmos DB
•	Almacenamiento seguro y estructurado de todos los datos de usuarios, libros y préstamos.
•	Sincronización en tiempo real entre múltiples dispositivos.
•	Escalabilidad y alta disponibilidad garantizada mediante la nube.
## 5. Tecnologías Utilizadas
•	Android Studio: Desarrollo nativo en Java/Kotlin.
•	Firebase Authentication: Para registro e inicio de sesión seguro.
•	Google Books API (opcional): Para enriquecer la información de libros.
•	Azure Cosmos DB: Base de datos NoSQL en la nube para almacenar información de usuarios y libros.
•	FCM (Firebase Cloud Messaging): Para el envío de notificaciones push.


## Diagrama de caso de uso:
![Diagrama CU Biblioteca drawio](https://github.com/user-attachments/assets/7f89dba4-314c-4089-97ba-10e547241705)


## Tablas de flujo:
<br>

## Registrar prestamo (Student):
![image](https://github.com/user-attachments/assets/bed93ecd-1f88-480a-8535-d29261f06ad9)
## Ver prestamo(s) (Student):
![image](https://github.com/user-attachments/assets/488fc900-bed1-4a86-b859-575abbb853bd)
## Verificar préstamo(s) (Administrador):
![image](https://github.com/user-attachments/assets/833f24ba-67f0-42dc-8ac3-8dc94a43e3dd)
## Registrar devolución (Administrador):
![image](https://github.com/user-attachments/assets/718774c9-647b-4920-933f-32f11c22117d)
## Gestionar libros (Administrador):
![image](https://github.com/user-attachments/assets/6dde9983-d6bf-4fa9-a800-b17766b2e526)
## Modificar libro:
![image](https://github.com/user-attachments/assets/40736b9a-7ec9-4d13-833f-fc86ae3a9e7a)
## Eliminar libro:
![image](https://github.com/user-attachments/assets/63ebcf37-77e2-4053-b068-0af5c45be719)

## ✅ Conclusión
Este proyecto representa un paso significativo hacia la digitalización de los servicios bibliotecarios del TESCo, mejorando la experiencia de estudiantes y personal académico mediante 
una aplicación móvil moderna, eficiente y segura. Al integrar tecnologías como Android Studio y Azure Cosmos DB, se logra una solución escalable y accesible que responde a las 
necesidades reales de la comunidad escolar. Con este desarrollo, se fortalece el compromiso institucional con la innovación tecnológica y la optimización de procesos educativos.


