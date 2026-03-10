# ForoHub API

API REST para un sistema de foro desarrollada con Spring Boot como parte de un challenge.
# Tecnologías

-Java 17

-Spring Boot

-Spring Security

-Spring Data JPA

-Maven

-MySQL

-JWT para autenticación

# Requisitos

-Java 17 o superior

-Maven

-MySQL

# Configuración

Antes de ejecutar el proyecto debes configurar la base de datos en el archivo:

src/main/resources/application.properties

Ejemplo:

spring.datasource.url=jdbc:mysql://localhost/forohub
spring.datasource.username=root
spring.datasource.password=tu_password

También debes crear la base de datos:

CREATE DATABASE forohub;