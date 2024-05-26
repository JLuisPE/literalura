# Literalura

Literalura es una aplicación de gestión de libros que utiliza la API de [Gutendex](https://www.gutenberg.org/ebooks/) para consultar y obtener información sobre los libros disponibles. Una vez obtenidos los datos de la API de Gutendex, estos se guardan en una base de datos local para su posterior acceso y consulta por parte de los usuarios.

## Características Principales

- Búsqueda de libros por título.
- Listado de libros registrados.
- Listado de autores registrados.
- Búsqueda de autores vivos en un año específico.
- Listado de libros por idioma.
- Estadísticas

## Tecnologías Utilizadas
- Java
- Spring Boot
- Hibernate
- Spring Data JPA
- Gutendex API
- Maven

## Instalación y Uso

### Requisitos Previos

- Java 17 instalado en el sistema.
- Maven para la gestión de dependencias.
- PostgreSQL instalado y configurado.

### Instalación

1. **Clona el repositorio de Literalura desde GitHub.**

2. **Ejecución de la aplicación:**
   - Abre tu IDE preferido (por ejemplo, IntelliJ IDEA).
   - Importa el proyecto clonado.
   - Configura las propiedades de la aplicación en el archivo `application.properties`.
   - Ejecuta la aplicación desde la clase principal (`LiteraluraApplication.java`).

### Uso

- Una vez que la aplicación esté en funcionamiento, utiliza el menú principal para acceder a las diferentes funciones. Puedes elegir entre las siguientes opciones:
    - **1 - Buscar libro por título:** Permite buscar un libro por su título.
    - **2 - Listar libros registrados:** Muestra libros almacenados en la base de datos.
    - **3 - Listar autores registrados:** Muestra todos los autores almacenados en la base de datos.
    - **4 - Listar autores vivos en un determinado año:** Muestra los autores que estuvieron vivos en un año específico.
    - **5 - Listar libros por idioma:** Muestra los libros disponibles en un idioma especificado.
    - **6 - Mostrar estadísticas:** Muestra estadísticas sobre la colección de libros, como el total de libros, el libro más descargado, el libro menos descargado y la media de descargas.
    - **0 - Salir**: Cierra la aplicación.

El usuario puede seleccionar la opción deseada e introducir la información requerida siguiendo las instrucciones proporcionadas por la aplicación.

## Contribución

¡Las contribuciones son bienvenidas! Si deseas contribuir al proyecto, por favor sigue los siguientes pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/feature-name`).
3. Realiza tus cambios y haz commit de los mismos (`git commit -am 'Add new feature'`).
4. Sube los cambios a tu repositorio remoto (`git push origin feature/feature-name`).
5. Haz un pull request a la rama principal del repositorio.

**Esta guía detallada te ayudará a configurar y utilizar la aplicación de manera efectiva. Si encuentras algún problema durante la instalación o el uso, no dudes en contactar al desarrollador para obtener ayuda.**
## Autores

- [José Luis Pineda](https://www.linkedin.com/in/jlpineda) - Desarrollador principal