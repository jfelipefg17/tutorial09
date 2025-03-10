# Tutorial09a
## Descripción
Este es un proyecto en Spring Boot que implementa un sistema de carrito de compras con persistencia en MySQL.
## Requisitos   Antes de ejecutar la aplicación, asegúrate de contar con los siguientes requisitos:
- Java 17 o superior
- Maven instalado
- MySQL corriendo en el sistema
## Configuración de la Base de Datos
Antes de ejecutar la aplicación, asegúrate de que la base de datos MySQL está configurada correctamente y crea la base de datos:

```sql
CREATE DATABASE product;
INSERT INTO products (name, price) VALUES ('MacBook Pro', 3000), ('iPad', 1000), ('iPhone', 1200), ('Apple Watch', 500);
```

 ## Configuración .properties
 spring.datasource.url=jdbc:mysql://localhost:3306/product
 
 spring.datasource.username=TU_USUARIO

 spring.datasource.password=TU_CONTRASEÑA
 
 ## Correrlo
 mvn clean install
 
 mvn spring-boot:run 
