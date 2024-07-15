# ForoHub
Esta aplicación API de back-end realiza las actividades en un foro. 

## Descripción del proyecto

Ofrece las opciones de CRUD para los tópicos del foro:

- Registro de tópicos y guardarlos en la base de datos topicos
- Listar los tópicos que están en la base de datos
- Mostrar los datos de un tópico seleccionado
- Modificar el tópico seleccionado
- Eliminar el tópico seleccionado de la base de datos

y todo esto únicamente con el acceso autorizado
- usando la forma STATELESS de autenticación con JWT (JSON Web Token)

### Dependencias usadas (el archivo pom.xml)
- pring-boot-starter-web:3.0.2
- spring-boot-devtools:3.0.2
- lombok:1.18.24
- spring-boot-starter-test:3.0.2
- spring-boot-starter-data-jpa:3.0.2
- flyway-core:9.5.1
- flyway-mysql:9.5.1
- mysql-connector-j:8.0.32
- spring-boot-starter-validation:3.0.2
- spring-boot-starter-security:3.0.2
- java-jwt:4.2.1

### Base de datos MySQL

Se usan 2 tablas:
- topicos
- usuarios

## Tecnologías usadas
- Java SE17
- Spring Boot v.3.0.2
- IDE IntelliJ
- Cliente de API Insomnia
- MySQL de Oracle
- lucidchart.com para presentación gráfica
- Editor de Visual Studio Code para este README
