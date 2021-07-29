# Email

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.2.

## Data Endpoint
https://fun-app-sa-inscorep.azurewebsites.net/api/emails?code=pVKbInrPv3LOasejCUoULNj%2F8VNdgleY3W4h6B3HO7I2DRBFWG1KDQ%3D%3D

We decided to only have one data endpoint containing everything for the different sections to simplify things. 
You may hit the endpoint wherever needed to extract the relevant data.

## Data Structure
- account
  - accountName
  - inbox
  - sent

## Task
- create an email client 
- list of accountNames
  - inbox
  - sent

By selecting an account the relative data should be displayed.
All can be done with or without a css framework.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
