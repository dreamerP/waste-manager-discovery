# waste-manager-discovery
# Microservicio de Descubrimiento (Discovery Service) - Spring Boot

Este es un microservicio de descubrimiento implementado utilizando Spring Boot y Spring Cloud Netflix Eureka. Proporciona una solución para la detección automática y el registro de servicios en un entorno de arquitectura de microservicios.

## Funcionalidades

- **Registro automático de servicios:** Los servicios pueden registrarse automáticamente en el servicio de descubrimiento y recibir un nombre único que pueden utilizar otros servicios para encontrarlos.
- **Detección dinámica de servicios:** Los servicios pueden descubrir automáticamente otros servicios registrados en el servicio de descubrimiento, lo que permite la comunicación entre servicios sin necesidad de conocer las ubicaciones de red específicas.
- **Alta disponibilidad y escalabilidad:** El servicio de descubrimiento es altamente disponible y puede escalar horizontalmente para manejar un gran número de servicios y solicitudes.

## Tecnologías Utilizadas

- Java
- Spring Boot
- Spring Cloud Netflix Eureka

## Configuración

Para usar este microservicio de descubrimiento en tu proyecto, simplemente importa la dependencia de Spring Cloud Eureka Server en tu archivo `pom.xml` y configura las propiedades de la aplicación en `application.properties` o `application.yml`.

## Uso

1. Inicia la aplicación Spring Boot del microservicio de descubrimiento.
2. Registra otros microservicios en el servicio de descubrimiento utilizando las anotaciones de Spring Cloud Netflix Eureka.
3. Los servicios registrados estarán disponibles para ser descubiertos por otros servicios dentro de la misma red.

## Contribución

Si encuentras algún error o deseas contribuir con nuevas características, siéntete libre de crear un pull request o abrir un issue en este repositorio.

## Autor

Patricia M. Castelo
