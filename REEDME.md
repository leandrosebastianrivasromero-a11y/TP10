# Trabajo Práctico Nº 10: Aplicación Web y Operaciones CRUD con PHP y MySQL

-----------------------------

alumno:leandro rivas
curso: 6 e
especialidad: programacion
instituto: cassaffousth

----------------------------------

Aplicación web interactiva desarrollada con **PHP, HTML, CSS (Bootstrap) y MySQL** para realizar operaciones completas de lectura, creación, actualización y eliminación (CRUD) sobre la tabla de clientes de la base de datos[cite: 1, 3].

## Requisitos y Ejecución Local
1. La aplicación se ejecuta de forma local mediante **XAMPP** (servidor Apache y motor MySQL)[cite: 1] en la ruta `http://localhost/nombre_proyecto/`[cite: 1].
2. Importar el script SQL de la base de datos en **phpMyAdmin**.
3. Copiar el archivo `conexion.php.example`, renombrarlo a `conexion.php` y configurar los accesos correspondientes.

## Estructura del Código
- `conexion.php`: Conexión a la base de datos mediante PDO.
- `index.php`: Vista principal que lista los registros con Bootstrap y acciones de gestión[cite: 1].
- `crear.php`: Formulario e inserción de nuevos registros (Create)[cite: 1].
- `editar.php`: Formulario y actualización de datos (Update)[cite: 1].
- `eliminar.php`: Script de baja de registros (Delete)[cite: 1].