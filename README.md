# Getting Started
This app has been created with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.7

To start the project use `npm start`.

The first functional component which we start with it is HelloWorldApp.

To deploy to production use `ng build`.

To deploy to `GitHub Pages` I have used `angular-cli-ghpages`. Then I generate the build with `ng build --base-href https://jonatanpelaezblanco.github.io/my-angular-app/`
and the next step is to use `npx ngh --dir=dist/my-angular-app`.
In order to automating the integration and delivering'process using Github Actions see (this article)[https://dev.to/vanessamarely/despliegue-de-tu-aplicacion-en-angular-usando-github-actions-4pph]
