<p align="center">
  <a href="https://www.angular.io/" target="blank"><img src="https://angular.io/assets/images/logos/angular/angular.svg" width="200" alt="Angular Logo"/></a>
</p>

# FrontEnd Auth MEAN App.

Aplicación creada utilizando **CSS** en la que se hace consumo de un sistema de autenticación personalizado realizado con [NestJS](http://nestjs.com/), [Docker](https://www.docker.com/) y [MongoDB](https://www.mongodb.com).

El proceso de comunicación de interacción entre el **FrontEnd** y el **BackEnd** está basado en **Signals** (solo disponible a partir de Angular 16).

La App solo es demostrativa, no contiene información alguna, solo funciona para hacer el registro de Nuevos Usuarios, Login y Logout.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. Formularios Reactivos.
2. Functional Guards.
3. Manejo de autenticación.
4. Signals.
5. Effects.
6. Manejo de Errores.
7. SweetAlert.
8. Determinación de estado de autenticación.
9. Manejo de JWTs.
10. Headers de petición HTTP.
11. CORS.


Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 16.1.1.

## Servidor de Desarrollo

1. Clona el proyecto para extraer los datos del repositorio.

2. Ejecuta `npm install` para descargar e instalar los paquetes necesarios para la ejecución de la app.

3. Ejecuta `ng serve` para generar un servidor de desarrollo. Navega a `http://localhost:4200/`. La aplicación se recargará automáticamente si cambia alguno de los archivos de origen.
