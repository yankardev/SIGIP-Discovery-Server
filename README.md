# SIGIP Discovery Server

Servidor de descubrimiento de servicios para SIGIP usando Spring Boot y Netflix Eureka.

## Requisitos
- JDK 21 o superior
- Maven 3.9 o superior

## Ejecutar
```bash
mvn spring-boot:run
```

Con el servidor iniciado:
- Panel Eureka: http://localhost:8761
- Health: http://localhost:8761/actuator/health

## Configuración
- Puerto: 8761
- Nombre: sigip-discovery-server
- El servidor no se registra a sí mismo como cliente Eureka.

Este repositorio contiene solo el servidor de descubrimiento. El API Gateway y los microservicios funcionales se mantienen en repositorios independientes.
