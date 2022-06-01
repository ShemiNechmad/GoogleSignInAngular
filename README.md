This repository is an example of how to use Google Identity Sign In with Angular, directly, without using any external library.

You would consider to use Google Identity Library directly because:

1) Google Javascript library platform is deprecated and will be out of use from March 2023.

2) At the moment, the external library for google sign in (angularx-social-login) is deprecated as well because of that.
 
3) If angularx-social-login will upgrade to Google Identity it will be only for Angular13 and above. So if you have an earlier version, this could be a solution for you.

# What to do:

1) Add the Google Identity script tag, shown on file index.html.
2) Add a div with an Id, shown on app.component.html file.
3) Follow the changes in app.component.ts file.
4) Make sure to put your own google client id in its place, in the app.component.ts file.

*Last note, for local development, make sure you mention both http://localhost and http://localhost:4200 in google's cloud platform "Authorized Javascript Origins".

# Angular13

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
