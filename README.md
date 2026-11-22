# Portal de práctica Spring Boot — Grupo 3

Sitio web desarrollado con Spring Boot, Thymeleaf y CSS adaptable a dispositivos móviles para practicar la implementación de aplicaciones web.

## Requisitos

- Java 17 o superior
- Maven 3.6 o superior

## Ejecutar

```bash
mvn spring-boot:run
```

Abre [http://localhost:5000](http://localhost:5000) para ver el portal.

## Generar y ejecutar el archivo JAR

Empaqueta la aplicación con Maven:

```bash
mvn clean package
```

El archivo se genera en `target/portal-bienvenida-0.0.1-SNAPSHOT.jar`. Para ejecutarlo:

```bash
java -jar target/portal-bienvenida-0.0.1-SNAPSHOT.jar
```

## Cambiar el puerto

Modifica `src/main/resources/application.properties` y ajusta la propiedad `server.port`. Actualmente está configurada en `5000`:

```properties
server.port=5000
```

## Ejecutar con Docker

Construye la imagen e inicia el contenedor con Docker Compose:

```bash
docker compose up --build
```

Abre [http://localhost:8080](http://localhost:8080).

Para detener y eliminar los contenedores:

```bash
docker compose down
```

## Pruebas

```bash
mvn test
```