# LiterAlura: Catálogo de Libros

Este proyecto es parte del challenge back-end LiterAlura de Alura Latam, donde construimos un catálogo de libros utilizando Java, Spring Boot y Postgres.

## Descripción

LiterAlura permite a los usuarios registrar libros en una base de datos y obtener información sobre ellos. La aplicación consume la API Gutendex para buscar información de los libros y ofrece funcionalidades para gestionar y consultar la base de datos.

## Funcionalidades

-   **Buscar libro por título:** Permite buscar un libro en la API Gutendex por su título y registrarlo en la base de datos.
-   **Listar libros registrados:** Muestra todos los libros almacenados en la base de datos.
-   **Listar autores:** Muestra todos los autores registrados en la base de datos.
-   **Listar autores vivos en un año específico:** Permite buscar autores que estaban vivos en un año determinado.
-   **Listar libros por idioma:** Permite filtrar los libros por idioma (ES, EN, FR, PT).

## Tecnologías Utilizadas

-   Java            | ☕
-   Spring Boot     | 🔧
-   PostgreSQL      | 🐘   
-   Maven           | 📚

## Dependencias

-   Spring Data JPA
-   PostgreSQL Driver

## API Utilizada

-   Gutendex ([gutendex.com](https://gutendex.com/)): API basada en el Proyecto Gutenberg, una biblioteca digital con más de 70 mil libros gratuitos.

## Configuración Inicial

1.  **Crear el proyecto en Spring Initializer:**
    -   Ir a [start.spring.io](https://start.spring.io/).
    -   Seleccionar:
        -   Proyecto: Maven
        -   Lenguaje: Java
        -   Spring Boot: (la última versión estable)
    -   Configurar:
        -   Group: `com.alura` (o el que prefieras)
        -   Artifact: `literalura` (o el que prefieras)
        -   Packaging: JAR
        -   Java: 17
    -   Añadir dependencias:
        -   Spring Data JPA
        -   PostgreSQL Driver
    -   Generar el proyecto y descargarlo.

2.  **Importar el proyecto en tu IDE (IntelliJ IDEA, Eclipse, etc.).**

3.  **Configurar la conexión a la base de datos PostgreSQL.**

## Uso

1.  **Ejecutar la aplicación:**
    -   Navegar al directorio del proyecto.
    -   Ejecutar el comando: `mvn spring-boot:run`

2.  **Interactuar con la aplicación a través de la consola.**

## Próximos Pasos

-   Implementar las funcionalidades básicas.
-   Manejar los casos de error, como libros no encontrados o intentos de insertar el mismo libro múltiples veces.
-   Añadir funcionalidades adicionales para mejorar la experiencia del usuario.

## Recursos Adicionales

-   [Documentación de Spring Boot](https://spring.io/projects/spring-boot)
-   [Documentación de Spring Data JPA](https://spring.io/projects/spring-data-jpa)
-   [Documentación de PostgreSQL](https://www.postgresql.org/docs/)
-   [API Gutendex](https://gutendex.com/)
