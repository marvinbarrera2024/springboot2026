# Portal de práctica Spring Boot — Grupo 3

Sitio web desarrollado con Spring Boot, Thymeleaf y CSS adaptable a dispositivos móviles para practicar la implementación de aplicaciones web.

## Requisitos

- Java 17 o superior
- Maven 3.6 o superior

## Ejecutar

```bash
mvn spring-boot:run
```

Abre [http://localhost:8080](http://localhost:8080) para ver el portal.

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