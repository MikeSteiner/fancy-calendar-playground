# Fancy

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

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


# Helpful links and information

## Generate multi-project workspace and projects + libs
[https://angular.io/guide/file-structure#multiple-projects]()

`ng new fancy-calendar-playground --create-application false`

`cd fancy-calendar-playground`

`ng generate application birthdays`

`ng generate application todos`

`ng generate application events`

`ng generate application lib-shared`

`ng generate application lib-components`


### How to remove an Angular library created with CLI (ng generate library)
- Delete the folder projects/my-lib.
- Go to the angular.json file and remove the "my-lib" object section contained in "projects".
- Go to tsconfig.json and remove "my-lib" object section from paths.

If you are using Nx workspace 9.1.3 you can achieve that with remove workspace schematics plugin e.g.

`nx g @nrwl/workspace:remove <project-name>`

[https://nx.dev/plugins/workspace/schematics/remove]()

