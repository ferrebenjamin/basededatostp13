# basededatostp13
Instrucciones de instalación y configuración (si usás Clever Cloud, utilizar la base que viene creada automáticamente).

Ejecutar en MySQL el archivo script.sql, que crea las siguientes tablas:

usuarios
libros
prestamos
En Google Colab:

Ejecutar este comando:
!pip install mysql-connector-python
Copiar y pegar el código Python del sistema de biblioteca.
En la función conectar(), colocar los datos de tu base de Clever Cloud:
host="TU_HOST"
user="TU_USUARIO"
password="TU_PASSWORD"
database="TU_BASE"
Ejecutar el programa con:
menu()
🗃️ Descripción de la base de datos y su contexto

El sistema gestiona la información de una biblioteca escolar, registrando usuarios, libros y préstamos.

Tablas principales:

usuarios → guarda nombre, curso y rol (Bibliotecario, Docente, Estudiante)
libros → contiene título, autor, ISBN, categoría y estado (Disponible o Prestado)
prestamos → almacena los préstamos con usuario, libro, fechas y estado (Activo o Devuelto)
El objetivo es permitir una gestión rápida y ordenada de los préstamos dentro de la institución.
