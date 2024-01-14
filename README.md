# spring security jwt authentication and authorization

Si encuentras útil este repositorio, ¡por favor ayúdanos marcándolo con una ⭐! 😊

## Tecnologías Utilizadas

- JDK 17
- Spring Boot 3
- Spring Data Jpa
- Spring security 6
- PostgreSQL 15
- Java JWT
- Docker

## Prerrequisitos

Asegúrate de tener instalados los siguientes componentes en tu entorno de desarrollo antes de comenzar:

1. [Git](https://git-scm.com/downloads)
2. [Docker](https://docs.docker.com/compose/install/)

## Configuración del Entorno 

#### Clonar el repositorio en tu máquina local

```
git clone https://github.com/Angel-Raa/spring-security-jwt-authentication-and-authorization.git
```
#### Navegar al directorio del proyecto
Dirígete al directorio del proyecto recién clonado utilizando el siguiente comando:
```
cd spring-security-jwt-authentication-and-authorization
```
#### Crear y Configurar file.env y db.env

Debes crear dos archivos de configuración, `file.env` y `db.env`, en el directorio raíz del repositorio clonado. 

**file.env** 
Este archivo contiene las variables de entorno para la aplicación.
```bash
SPRING_DATASOURCE_URL=jdbc:postgresql://database:5432/tu_basedatos
SPRING_DATASOURCE_USERNAME=tu_usuario
SPRING_DATASOURCE_PASSWORD=tu_contraseña
SPRING_JPA_PROPERTIES_HIBERNATE_DIALECT=org.hibernate.dialect.PostgreSQLDialect
SPRING_JPA_HIBERNATE_DDL_AUTO=update
SPRING_JPA_SHOW=true
```
**db.env** 
Este archivo contiene las credenciales para la base de datos.
```bash
POSTGRES_DB=nombre_de_tu_basedatos
POSTGRES_PASSWORD=contraseña_de_la_base_de_datos
POSTGRES_USER=usuario_de_la_base_de_datos
```
Asegúrate de reemplazar `nombre_de_tu_basedatos`, `contraseña_de_la_base_de_datos` y `usuario_de_la_base_de_datos` con los valores adecuados para tu configuración.

#### Construir y ejecutar los contenedores de Docker Compose
```
docker compose up -d
```

### Swagger Documentation
```
http://localhost:8000/api/v1/swagger-ui/index.html#/
```
![](https://github.com/Angel-Raa/spring-security-jwt-authentication-and-authorization/blob/main/src/main/resources/img/docs.png)


## Recursos Adicionales

Aquí hay algunos recursos adicionales que podrían ser útiles:
- [Documentacion de Spring Data](https://spring.io/projects/spring-data)
- [Documentación de Java JWT](https://github.com/jwtk/jjwt)
- [Documentacion de open jdk 17](https://docs.oracle.com/en/java/javase/17/docs/api/)
- [Documentacion de Spring boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Documentacion de Maven](https://maven.apache.org/guides/getting-started/)
- [Documentacion de Docker](https://docs.docker.com/)
- [Documentacion de Spring Security](https://docs.spring.io/spring-security/reference/index.html)
- [Documentacion de Git](https://git-scm.com/doc)




