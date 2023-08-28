<p>
<img src="/src/img/TOP ECOMMERCE.png" width="200" alt="Ecommerce">
</p>

# ECCOMERCE API

## Descripción del proyecto

## Plataforma de comercio electrónico

Este proyecto es una API web que te permite crear usuarios, productos, categorías, imágenes de los productos, agregar, eliminar y actualizar productos al carrito de compras. La aplicación está construida usando Node.js y Express y utiliza una base de Datos PostgreSQL para almacenar la información.

## Características principales

1. Crear usuarios: Puedes crear usuarios con información como nombre, apellido, dirección, email, contraseña y foto.
2. Iniciar sesión y gestionar el perfil de manera eficiente.
3. Gestionar pedidos y carritos de compra: agregar y eliminar productos al carrito y realizar pedidos
4. Categorización de productos: Permite organizar por categoría para facilitar la búsqueda
5. Gestión imágenes: La Aplicación permite cargar imágenes de los productos y almacenarlas en la Base de Datos

## Tecnologías utilizadas

1. Express: Un framework minimalista de Node.js que facilita la creación de aplicaciones web y API'S

2. Express-rate-limit: Middleware de Express que limita la cantidad de solicitudes que un cliente puede hacer en un periodo de tiempo especificado.

3. Express-validator: Middelware de Express que valida los datos de entrada antes de que se procesen.

4. Firebase: Una plataforma de desarrollo de aplicaciones móviles y web que proporciona herramientas para crear, mejorar y hacer crecer aplicaciones.

5. Helmet: Middelware de Express que ayuda a proteger la aplicación de varias vulnerabilidades web mediante la configuración adecuada de las cabeceras HTTP.

6. HPP: Middleware de Express que previene los ataques de envenenamiento de parámetros HTTP.

7. Morgan: Middleware de Express que registra solicitudes HTTP para el registro y análisis.

8. Multer: Middleware de Express que maneja la carga de archivos multipart/form-data

9. PostgreSQL: Un sistema de gestión de base de datos relacionales de código abierto

10. Sequelize: un ORM (Objet-Relational Mapping) para base de datos SQL que simplifica la interacción con la base de datos y proporciona una capa de abstracción sobre SQL.

11. XSS-clean: Middleware de Express que limpia las entradas de usuario para evitar ataques de XSS (cross-site scripting)

## Requisitos previos

Antes de ejecutar el proyecto asegurate de tener instalado Node.js, PostgreSQL, nodemon en tu máquina.

## Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Ejecutar `npm install`
3. Clonar el archivo `.env.template` y renombrarlo a `.env`
4. Cambiar las variables de entorno
5. Ejecutar la base de datos
6. Ejectuar el modo de desarrollo: `npm run start:dev`
