## Introducci贸n 馃

_Este desarrollo es un CRUD simple de notas usando una aplicaci贸n Spring Boot, Mysql, JPA y Hibernate Rest API_

### Pre-requisitos 馃搵

1. Java - 1.8.x

2. Maven - 3.x.x

3. Mysql - 5.x.x

## Pasos para la instalci贸n

**1. Crea Mysql database**
```bash
create database notes_app
```

**2. Cambia mysql username y password antes de corre**

+ esto lo editas de aca `src/main/resources/application.properties`

+ cambia `spring.datasource.username` y `spring.datasource.password` por la configuracion mysql de tu instalaci贸n

**3. Compila y corre la app usando maven**

```bash
mvn package
java -jar target/easy-notes-1.0.0.jar
```

_puede hacerlo asi tambien 馃_

```bash
mvn spring-boot:run
```

La aplicaci贸n se levantara aca <http://localhost:8080>.

## Explora las Rest APIs

Definimos las siguientes CRUD APIs.

    GET /api/notes
    
    POST /api/notes
    
    GET /api/notes/{noteId}
    
    PUT /api/notes/{noteId}
    
    DELETE /api/notes/{noteId}

Puedes usar postman o soap ui para probar.
## Expresiones de Gratitud 馃巵

* Comenta a otros sobre este proyecto 馃摙
* Da las gracias p煤blicamente 馃.
* etc.

---
鈱笍 con 鉂わ笍 por [bcarcamo](https://github.com/bcarcamo-working) 馃槉

