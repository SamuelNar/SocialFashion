# Social Fashion - Proyecto Final Integrador

Proyecto Final Integrador para Social Fashion.

## Requisitos

- Java JDK 1.8
- MySQL
- Maven

## Configuración

1. **Clona el repositorio:**

    ```bash
    git clone https://github.com/tuusuario/socialfashion.git
    cd socialfashion
    ```

2. **Configura la base de datos MySQL en `application.properties`:**

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/tu_base_de_datos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña
    ```

3. **Ejecuta la aplicación:**
    ```bash
    mvn spring-boot:run
    ```
## Estructura del Proyecto
La estructura del proyecto sigue la convención estándar de Spring Boot:

```plaintext
/src
  /main
    /java
      /proyecto
        /socialfashion
          Application.java
    /resources
      application.properties
  /test
    ...
  ```
## Dependencia principales 
```plaintext
Spring Boot Data JPA: org.springframework.boot:spring-boot-starter-data-jpa
Spring Boot Thymeleaf: org.springframework.boot:spring-boot-starter-thymeleaf
Spring Boot Web: org.springframework.boot:spring-boot-starter-web
Spring Boot Security: org.springframework.boot:spring-boot-starter-security
Spring Boot DevTools: org.springframework.boot:spring-boot-devtools
MySQL Connector: com.mysql:mysql-connector-j
Spring Boot Starter Tomcat: org.springframework.boot:spring-boot-starter-tomcat
Spring Boot Starter Test: org.springframework.boot:spring-boot-starter-test
Thymeleaf Extras Spring Security: org.thymeleaf.extras:thymeleaf-extras-springsecurity5
