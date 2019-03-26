# HelloWorldApp

This project was generated with [Angular CLI](https://github.com/angular/angular)

**Steps need to follow before create first app in Windows**

- Download [Node Js](https://nodejs.org/en/) and install
- Excute following command to install [@angular/cli](https://cli.angular.io/) 
  
    `npm install -g @angular/cli@latest`

- Check Angular cli version
    
    `ng version`

## Angular cli command used to create HelloWorldApp

`ng new HelloWorldApp --routing --style scss`

Other Angular Cli helpful commands:

    ng g <schematic> [options]

    <schematic>	The schematic or collection:schematic to generate.

    This option can take one of the following sub-commands:

        - appShell
        - application
        - class
        - component
        - directive
        - enum
        - guard
        - interface
        - library
        - module
        - pipe
        - service
        - serviceWorker
        - universal

    options 

        --defaults=true|false	
        When true, disables interactive input prompts for options with a default.

        --dryRun=true|false	
        When true, runs through and reports activity without writing out results.

        Default: false

        Aliases: -d

        --force=true|false	
        When true, forces overwriting of existing files.

        Default: false

        Aliases: -f

        --help=
            true|false|json|JSON	
        Shows a help message for this command in the console.

        Default: false

        --interactive=true|false	
        When false, disables interactive input prompts.

    e.g.:
        ng generate component HelloWorldMain --flat



## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
