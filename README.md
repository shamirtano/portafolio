<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Acerca del proyecto

Para este proyecto se utilizó el framework Laravel, el cual es un framework de código abierto para desarrollar aplicaciones y servicios web con PHP 7 y posterior. Su filosofía es desarrollar código PHP de forma elegante y simple, evitando el "código espagueti". Fue creado en 2011 y tiene una gran influencia de frameworks como Ruby on Rails, Sinatra y ASP.NET MVC. Se plantea crear un portafolio o curriculum vitae en el cual se pueda mostrar información personal, educación, experiencia laboral, proyectos, habilidades, entre otros. El sistema contará con un panel administrativo donde se podrá modificar la página principal, agregar o quitar contenido. El proyectos se alojara en un servidor de [CreaSoft Corp](https://shamirtano.creasoft.com.co/)

## Requisitos

- PHP >= 7.3
- Composer
- Node.js >= 12.14
- NPM >= 6.13
- MySQL >= 5.7

## Instalación

1. Clonar el repositorio
2. Ejecutar el comando `composer install`
3. Ejecutar el comando `npm install`
4. Crear una base de datos en MySQL
5. Crear un archivo `.env` en la raíz del proyecto, copiar el contenido del archivo `.env.example` y pegarlo en el archivo `.env`
6. Configurar las variables de entorno en el archivo `.env`
7. Ejecutar el comando `php artisan key:generate`
8. Ejecutar el comando `php artisan migrate`
9. Ejecutar el comando `php artisan db:seed`

## Ejecución

1. Ejecutar el comando `php artisan serve`
2. Abrir el navegador en la dirección `http://localhost:8000`

### Usuarios

- Administrador
    - Correo: admin@admin.com
    - Contraseña: password

- Usuario
    - Correo: usuario@usuario.com
    - Contraseña: password

## Desarrolladores

- **[Shamir Tano](https://github.com/shamirtano)**

## Capturas de pantalla

### Página principal

![Página principal](https://raw.githubusercontent.com/shamirtano/portafolio/master/public/images/screenshots/home.png)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
