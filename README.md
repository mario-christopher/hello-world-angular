# hello-world-angular !
**Hello World Angular** is a simple starter application built using [Angular4](https://angular.io/). It is configured using [Webpack](https://webpack.github.io/docs/).

The purpose of this application is to demonstrate the ease with which an Angular4 SPA can be setup with Webpack. This can also be used as a **starter project** for any Angular4 project as it is not opinionated with any design patterns, architecture or extra third-party libraries.

## Setup
* `git https://github.com/mario-christopher/hello-world-angular.git`
* `cd hello-world-angular`
* `npm install`
* `npm run start`
* Browse to http://localhost:8080 *( tested on Chrome and IE.11 ).*

For production build, edit file `webpack.config.js` and replace

`module.exports = require('./config/webpack.dev.js');`

with

`module.exports = require('./config/webpack.prod.js');`

Then run `npm run build` in the terminal. You could also code for checking `process.env.NODE_ENV` in `webpack.config.js` and use the appropriate config file.


##  Application features:

* Uses the stable build for Angular 4.3.x.
* Webpack configured for Dev and Prod environments.
* Can be used as a Starter project for any Angular4 based client.
* Uses Typescript.
* Configured to use ES6 features.
* Uses polyfills to cover most modern browsers.

##   License

Shared under MIT License.