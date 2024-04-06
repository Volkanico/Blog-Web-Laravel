### Proyecto Laravel MVC SOAP
Este proyecto es una aplicación web desarrollada con el framework Laravel que utiliza el patrón de arquitectura Modelo-Vista-Controlador (MVC) y SOAP para la comunicación con servicios externos.

## Descargar el proyecto

Puede descargar el proyecto desde el repositorio de GitHub utilizando el siguiente enlace: [Enlace al repositorio](https://github.com/Volkanico/Blog-Web-Laravel)

## Instalación de dependencias

Una vez descargado el proyecto, acceda a la carpeta del proyecto en su terminal y ejecute el siguiente comando para instalar las dependencias:

# composer install

Es posible que se requiera un token de GitHub para descargar algunas dependencias.

## Configuración del entorno

Deberá crear el archivo .env con las credenciales requeridas, como ejemplo tiene .env.example.

El proyecto utiliza un enlace dinámico de public/storage a storage, si lo tiene deberá eliminarlo y ejecutar el siguiente comando:

# php artisan storage:link

## Ejecución del seeder

Para crear un usuario administrador que permita crear posts, ejecute el siguiente comando:

# php artisan db:seed

## Iniciar el servidor

Finalmente, para ejecutar la aplicación y visualizarla en el navegador, ejecute el siguiente comando:

# php artisan serve

# La aplicación estará disponible en localhost:8000.

¡Disfrute explorando la aplicación! Si tiene alguna pregunta o problema, no dude en ponerse en contacto con nosotros.


# Updated and changed repository from https://github.com/Volkanico/LaravelLaracastsCurso

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.


