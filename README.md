# Proyecto de Consulta de Libros con GUTENDEX ![Estado](https://img.shields.io/badge/estado-finalizado-brightgreen)

---

## Descripción del Proyecto

El **Proyecto de Consulta de Libros con GUTENDEX** es una aplicación desarrollada en Java que permite a los usuarios interactuar con una base de datos de libros a través de la API de GUTENDEX. Los usuarios pueden buscar libros por título, listar libros registrados, listar autores registrados, listar autores vivos en un determinado año y listar libros por idioma. Esta herramienta es ideal para amantes de la lectura, investigadores, y cualquier persona interesada en acceder a una amplia colección de libros de manera eficiente y organizada.

## Tecnologías Usadas

- **Java**: Lenguaje de programación utilizado para desarrollar la lógica del programa.
- **Gson.jar**: Librería de Google para convertir objetos Java a JSON y viceversa, facilitando la manipulación de datos de la API.
- **API GUTENDEX**: API utilizada para acceder a una base de datos extensa de libros y autores.
- **Spring Boot**: Framework de Java para crear aplicaciones web robustas y escalables de manera rápida y sencilla.
- **PostgreSQL**: Sistema de gestión de bases de datos utilizado para almacenar y gestionar los datos de los libros y autores.
- **Jackson Databind**: Librería para procesar JSON en aplicaciones Java, utilizada para deserializar y serializar objetos.

## Funcionalidades del Programa

- **Buscar libro por título**: Permite a los usuarios buscar libros en la base de datos de GUTENDEX ingresando un título específico.
- **Listar libros registrados**: Muestra una lista de todos los libros disponibles en la base de datos.
- **Listar autores registrados**: Muestra una lista de todos los autores registrados en la base de datos.
- **Listar autores vivos en un determinado año**: Filtra y muestra los autores que estaban vivos en un año específico.
- **Listar libros por idioma**: Permite a los usuarios listar libros según el idioma en el que fueron escritos.

## Instalación y Uso

1. **Clonar el repositorio**: `git clone https://github.com/tu_usuario/proyecto-consulta-libros.git`
2. **Abrir el proyecto en IntelliJ IDEA**.
3. **Configurar la base de datos PostgreSQL**: Crear una base de datos y actualizar las credenciales en el archivo de configuración de Spring Boot.
4. **Agregar las dependencias**: Asegurarse de que las dependencias de Gson.jar y Jackson Databind estén incluidas en el archivo `pom.xml`.
5. **Configurar la API Key de GUTENDEX**: Si es necesario, obtener una API key y configurarla en el archivo de configuración del proyecto.
6. **Ejecutar la aplicación**.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o realiza un pull request con tus cambios.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
