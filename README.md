#Migration to Angular version 10:
Ce qui a changé dans cette version c'est que les fonctions utilisant des fonctionnalités Angular sans utiliser les decorators Angulars ne seront plus supportés

#Migration to Angular version 11:
On permet au type d'un parent d'être "null" pour améliorer la précision de la valeur pendant l'éxecution.
Les utilisations de ViewEncapsulation.Native sont supprimés (car enlevé de Angular v11) et remplacés par ViewEncapsulation.ShadowDom
Des options du fichier angular.json ont été enlevés car plus présentes dans la v11.
Beaucoup de propriétés ont été mis à jours où remplacés car supprimées dans la v11.
async a été renommée par waitForAsync

# SimpleApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
