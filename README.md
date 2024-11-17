# Tracker

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.11.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Commit 3

1. **Updated `angular.json`**:
   - Added an **assets array** to be included in the build specifying:
     - `favicon.ico` from the `src` directory.
     - All files in the `assets` directory.

2. **Enhanced `tsconfig.json`**:
   - Enabled `forceConsistentCasingInFileNames` to enforce case sensitivity in file names.
   - Set `moduleResolution` to `"node"`, ensuring Node.js-style module imports.
   - Disabled `useDefineForClassFields` to simplify class field syntax, allowing for more concise syntax. 

3. Simplify `app.component.html` by focusing on introducing the ToDo demo application:
   - Eliminate distracting elements like external links, focusing instead on the ToDo application.
   - Align the content with the demo app's learning objectives.
   - Use the logo and heading to emphasize Angular's branding and set the tone for the course material.  