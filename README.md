# AngularCRUD

This is the consumer application for the asp.net core web API. It is just to practice angular services for integrating with asp.net core rest apis

Producer REST API Application: https://github.com/imtiajahammad/EmployeeMCrud


Reference : 
https://www.c-sharpcorner.com/article/angular-crud-using-net-core-web-api/

Key features:

                * Create Angular App 
                * Adding Services
                * Adding Components
                * Adding Bootstrap
                * Register modules
                * Add Routing  
                * Navigating menus for routing
                * Adding component codes
                * Filtering & Sorting

Commands: 
* ng new AngularCRUD
* ng serve -o
* ng serve -open
* ng g c department
* ng g c department/add-edit-department
* ng g c department/show-department
* ng g c employee
* ng g c employee/add-edit-employee
* ng g c employee/show-employee
* ng g s apiservice


Adding Bootstrap:
1. Go to https://getbootstrap.com/ 
2. copy bootstrap.min.css and bootstrap.bundle.min.js links
3. Open index.html page and paste .css link in the head section and .js after body section

Register Modules:
1. add services in providers in app.module.ts
2. add imports in app.module.ts for HttpClient,FormsModule,ReactiveFormsModule

Add Routing:
1. adding routes for department in app-routing.module.ts for routes
2. adding routes for employee in app-routing.module.ts for routes

Navigating menus for routing:
1. Open app.component.html
2. add navigations


Adding service, component codes & Filtering & Sorting
1. Injecting httpClient into constractor
2. adding functions for department apis
3. Adding functions for employee apis


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.0.

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
