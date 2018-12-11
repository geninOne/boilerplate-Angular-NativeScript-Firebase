# Boilerplate

## Dependencies
This project use following tools
 - [Node.js](https://nodejs.org/en/) (10.14.0)
 - [Angular CLI](https://github.com/angular/angular-cli) (7.1.2)
 - [Angular](https://angular.io/) (7.1.0) 
 - [AngularMaterial](https://material.angular.io/) (7.1.1)
 - [NativeScript](https://www.nativescript.org/)
 - [Firebase](https://firebase.google.com/)
 - [Angularfire 2](https://github.com/angular/angularfire2)

The Structure of the angular and nativeScript you can follow the the description in [this post](https://blog.angular.io/apps-that-work-natively-on-the-web-and-mobile-9b26852495e7)

## Prerequisites
1. Install [Node.js](https://nodejs.org/en/)
2. Install Angular CLI: npm i -g @angular/cli
3. Install Angular CLI: npm install -g nativescript
4. From project root folder install all the dependencies: npm i
## Angular (Web)
#### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

#### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

#### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

#### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

#### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## NativeScript (Android, IOS)
#### Use the Playground
To use the **NatvieScript Playground** you must install the NativeScript App
 - [NativeScript Android](https://play.google.com/store/apps/details?id=org.nativescript.play)
 - [NativeScript IOS](https://itunes.apple.com/us/app/nativescript-playground/id1263543946?mt=8&ls=1)
#### Start NativeScript
Run `npm run android` or `npm run ios`

#### More Information
If you need more information about the nativescript cli look [here](https://docs.nativescript.org/angular/start/cli-basics)

## Firebase
To setup firebase in the app, you must edit the files in /src/enviroments 
```
firebase: {
        apiKey: '<your-key>',
        authDomain: '<your-project-authdomain>',
        databaseURL: '<your-database-URL>',
        projectId: '<your-project-id>',
        storageBucket: '<your-storage-bucket>',
        messagingSenderId: '<your-messaging-sender-id>'
    }
```

to get the settings go to firebase => Settings => General => My Apps => click on Firebase add to my Web-App
