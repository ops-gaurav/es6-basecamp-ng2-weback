# es6-basecamp angular2
> ## NOTE<br/>
> Using angular-cli for production use is not recommended as it does not provides a configurable webpack file. Angular quickstart is configurable but it uses System.js for configuration which outstands the power and customization power of webpack. If you are not interested in production deployment then you can use angular CLI.
## WITH WEBPACK.
The webpack repository for angular 2 built from scratch instead of using angular CLI. This repository contains the angular configuration with webpack which was not available in angular terminal nor in the angular quickstart. The repository is kept simple so as to quickly get started with angular 2 with relevant comments in webpack config file to customize your build.

## Initialization
1. Clone using <br/>
`git clone https://github.com/sharma02gaurav/es6-basecamp-ng2-weback webpack-angular-basecamp`
2. change directory <br/>`cd webpack-angular-basecamp`.


## Valid commands
> ### `npm run configure`
> to configure the project and run in live watch mode. (run this while developing). Runs the webpack-dev-server in watch mode.

> ### `npm run deploy`
> run this command while deploying. This mode does not run webpack-dev-server in watch mode.

> ### `npm run build`
> run this command to explicitly build the project. This will create the ES5 format code in the <i>dist</i> folder of the project.
(Recommended for testing webpack config only).

> ### `npm run start:livedev`
> Run the server in development mode. This runs the webpack-dev-server in watch mode. It varies from `npm run configure` that it does not install dependencies. (Recommended to run of not running project for the first time).

> ### `npm start`
> Run the server in normal mode. This does not runs the webpack-dev-server in watch mode. This differs from `npm run deploy` as it does not install dependencies first. (Recommended for later deployments).

Tired of git clones? You can install [scaffold from here](https://www.npmjs.com/package/es6-scaffolder) that automates the process of creating popular ES6 scaffolds including this one.
