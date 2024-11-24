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

## Commit 3 - Sets the stage for customizing the demo app "Tracker" 

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

## Commit 4 - Building the First Custom Component - Tracker's Header Component

1. **Create custom component using Angular’s @Component decorator `header.component.ts`**:
   - Learning the structure of a component file and the core idea of templates and styles for modular UI building blocks. Component-specific files: `header.component.ts`, `header.component.html`, and `header.component.css`

2. **Updated `app.component.html`**:
   - Replaced original header section with `<app-header></app-header>` because the header content was moved to a separate Angular component, named `app-header`. This is a common practice in Angular development, where a larger application is broken down into smaller, reusable components.
   - By using `<app-header></app-header>`, the application is now rendering the app-header component in place of the original header content. The actual content of the header is now defined within the app-header component, which is likely defined in a separate file

3. **Defined style in `header.component.scss`, `app.component.scss`**:
   - The styles defined in this file are applied to the header element and its child elements, such as img, h1, and p. 
   - The styles include layout, typography, and visual effects. The use of media queries `(@media (min-width: 768px))` allows the styles to adapt to different screen sizes. It defines a media query that applies styles when the screen width is at least 768px. It increases the padding of the header element, widens the img element, and enlarges the font size of the h1 element for larger screens.
 