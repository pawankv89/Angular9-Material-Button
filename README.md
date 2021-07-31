# Angular9-Material-Button

### Angular9-Material-Button for Angular 9 with Material Library

![](https://github.com/pawankv89/Angular9-Material-Button/blob/main/images/screen_1.png)

## Version 1.0
This Sample for Learning Material Button Module.

```xml

```

## Requirements

### Visual Studio Code 1.58.2

Version: 1.58.2
Date: 2021-07-14T22:09:06.581Z
Electron: 12.0.13
Node.js: 14.16.0
V8: 8.9.255.25-electron.0
OS: Darwin x64 19.4.0

## Links

https://material.angular.io/components/button/overview

## setup

1) Add primeng & primeicons in dependencies inside package.json

```xml
 "dependencies": {
    "@angular/animations": "~12.0.4",
    "@angular/common": "~12.0.4",
    "@angular/compiler": "~12.0.4",
    "@angular/core": "~12.0.4",
    "@angular/forms": "~12.0.4",
    "@angular/platform-browser": "~12.0.4",
    "@angular/platform-browser-dynamic": "~12.0.4",
    "@angular/router": "~12.0.4",
    "rxjs": "~6.6.0",
    "tslib": "^2.1.0",
    "zone.js": "~0.11.4",
    "primeicons": "^4.1.0",
    "primeng": "^11.0.0",
    "@angular/animations": "^12.0.5",
    "@angular/cdk": "^12.1.4",
    "@angular/material": "^12.1.4"
  }
  ```

2) Add animations, cdk & material css in styles inside angular.json

```xml

 "styles": [
              "src/styles.scss",
              "node_modules/primeicons/primeicons.css",
              "node_modules/primeng/resources/themes/saga-blue/theme.css",
              "node_modules/primeng/resources/primeng.min.css",
              "node_modules/@angular/material/prebuilt-themes/indigo-pink.css"
            ]
```

3) Add Material ButtonModule in your Component or module file

```xml
import { MatButtonModule } from '@angular/material/button'
```

4) Add Button in your html file

```xml
<button mat-raised-button (click)='clickButton()'>Button Click Me</button>
```
5) install prime ng in your project

- Install Angular Material, Angular CDK and Angular Animations
- Using the Angular CLI ng the add command will update your Angular project with the correct dependencies, perform configuration changes and execute initialization code.
```xml
npm install @angular/material @angular/cdk @angular/animations --save
ng add @angular/material
```

## Run Code your Machine

ng serve

## License

This code is distributed under the terms and conditions of the [MIT license](LICENSE).

## Change-log

A brief summary of each this release can be found in the [CHANGELOG](CHANGELOG.mdown). 
