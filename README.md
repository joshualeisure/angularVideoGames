# NgVideoAngularApp

While still in progress, I am creating an Angular 11 project using a public API to create a video game database. The API is called RAWG Video Games Database and provides many details like popularity and rating. I began the project by using Angular CLI and then I created components, http calls using HttpClient module for the API, http interceptors to intercept incoming and outgoing HTTP requests, and services within the project. I also performed data passing with routes (RouterModule and Routes) and pipes as well as Angular directives like ngFor and ngIf statements. Other classes I used were HttpHandler and Injectable for dispatching requests, HttpRequest for outgoing requests such as headers, and Observable and observableThrowError for passing messages between components. For styling, I used SCSS and mat-form-fields, mat-select, and mat-option. 
The main features the user has is the ability to sort different categories of the video games based on popularity, release date, etc… Eventually, the user will be able to view the details of the game such as the plot and trailers. 



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
