# Mean.Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.4.4.
Se trata de la parte front como proyecto separado de la parte back.

## Despliege de la aplicación
Dos opciones:
1. Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
2. Con Tomcat
2.1 ng build --base-href . --prod
2.2 En index.html: < base href="/" >
2.3 Copiamos todos los archivos de /dist a /webapp/angular
2.4 Probar con: http://localhost:8080/angular

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
