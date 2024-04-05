# LearnAngularApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.2.

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


# HelloWord

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.2.

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
https://www.youtube.com/watch?v=MD1mVLBJCU4&list=PL5Agzt13Z4g_8lPIq5BgS4mkHwuxAFob-&index=4


# How to build Angular
Install VS code
Install Node.Js https://nodejs.org/en/download and install LTS version
Install Package Manager or NPM (node package manage for javascript - auto install when install node.js)
Install Angular cli>  
	npm install -g @angular/cli@latest 
    or 
    npm i @angular/cli@8.3.8 
npm install -g Typescript

# Command
    npm install -g @angular/cli@latest
    npm install -g Typescript
    node -v
    npm -v
    ng -v or ng v
    ng new projectname
    ng serve (Complie angular)
    ng serve o (Complie angular app and run)
Create component
    ng generate component componentName or ng g c componentName (student)
Create module
    ng g module moduleName (student-list)

# Error
Can't run application and get error with "cannot be loaded. the file ..... is not digitally signed."
    Remove ng.ps1 from the directory C:\Users\janji\AppData\Roaming\npm
    and run application again


# Fix
  ## Missing app.module.ts file in Angular17
    Run this command "ng new newproject --no-standalone" // create a new project with out standalone then app.module.ts

# Tips
- Open project in IDE by go to directory of project and run command >> "code .". It will open project in IDE from command line  

# Local of project
C:\Users\janji\Desktop\angular\hello-word

# Note
- Decorators '@'
    class decorators > @ngModule @Component etc.,
    property decorators > @input @output
    method decorators > @HosstListener
    parameter decorators > @Inject

# Note 05/04/2024
    package.json is all dependencies

    When you run application it will go to main.ts the app.coomponent.ts. Angular component has 3 parts.

    1. Template
    is View and html 
       templateUrl: './app.component.html',

    2. Class is code typescipt, data
    export class AppComponent {
    title: string; 
    numberOne: number = 1;
    numberTwo: number = 2;
    isShow: boolean = false;

    constructor() {
        this.title = "janjira"
    }

    3. Metadata -- information , decorator
    Ex:
     @Component({
        selector: 'app-root',
        standalone: true,
        imports: [RouterOutlet],
        templateUrl: './app.component.html',
        styleUrl: './app.component.css'
    })
  
  ## Property Binding []
  ![alt text](image.png)

  ## Two-way Binding  [()] - "banana box"
    - ngModel >> hook up 

Resources:
- Turorial > https://www.youtube.com/watch?v=CB3XOsaTEbM&list=PL82C6-O4XrHdf0LMDVl1Y-4_BFbNmdrGc&index=2
- Draw online > https://miro.com/online-whiteboard/?utm_source=bing&utm_medium=cpc&utm_campaign=S%7CBNG%7CNB%7CSCND%7CEN-EN%7CPhrase%7CPareto-Low&utm_adgroup=1144592558670775&utm_term=kwd-71537707456437:loc-174&matchtype=e&utm_content=&device=c&location=145974&msclkid=831e6eede71918032b6408e218f72bcd



