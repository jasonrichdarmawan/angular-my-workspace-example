# Non Priority To Do

`dependencies` instead of `peerDependencies` in `package.json` of a library

in `package.json`
```
{
    "$schema": "../../node_modules/ng-packagr/ng-package.schema.json",
    "dest": "../../dist/login-lib",
    "lib": {
      "entryFile": "src/public-api.ts"
    },
    "allowedNonPeerDependencies": [
      "@ng-select/ng-select"
    ]
  }
```

in `ng-package.json`
```
    "allowedNonPeerDependencies": [
      "@ng-select/ng-select"
    ]
```

`styles.scss` of a library instead of the `styles.scss` of the `my-first-app` application.

in `styles.scss` of a library.
```
@import "~@ng-select/ng-select/themes/material.theme.css";
```

# AngularMyWorkspaceExample

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.11.

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
