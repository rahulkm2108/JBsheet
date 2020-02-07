# DataAnalytics

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.12.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

# Installation Notes
* To use the google API's we need run our angulal application over `https` secure protocol.
So we are running our build with `http-server` module and to run our angular application over https we are using `ngrok`(ngrok exposes local servers behind NATs and firewalls to the public internet over secure tunnels.) we will use this public url to preview our Application.
* This public URL lasts for 6 to 7 hours.
* Until our application got deployed/hosted we will use `ngrok` to preview the Application.

## Install `http-server` and `ngrok` globally
   `npm install http-server -g`
   `npm install ngrok -g` 

## Install node modules.
    `npm install`

## Run build prod
    `ng build --prod`

## Change directory to `dist/project_name` generated in the root folder.

## Run the build with http-server module.
    `http-server -p 4200`

## Run `ngrok` to listen our local server
   `ngrok http 4200` 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.


## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
