# webpack-js-boilerplate
_Webpack JS Boilerplate_ is a simple (but usefull) _Vanilla JS front-end boilerplate_ for building small (but robust), and adaptable demos, web apps or sites.

## Features
- [EditorConfig](https://editorconfig.org/) ready;
- [ESLint](https://eslint.org/) ready (with [airbnb style guide integration](https://github.com/airbnb/javascript);
- [Babel](https://babeljs.io/) ready;
- Webpack Environment Splitting (Development e Production);
- Dev-Server (with hot-reload) ready;
- Production Bundle package build ready.

## Quick Start
- Make sure that you have Node.js v8 and npm v5 or above installed;
- Clone this repo using `git clone https://github.com/fsciuti/webpack-js-boilerplate.git <YOUR_PROJECT_NAME>`;
- Move into the appropriate <YOUR_PROJECT_NAME> directory;
- Run from terminal: `npm i` in order to install dependencies;
- Use _src/index.js_ file like a project entry point script;
- Use _src/index.html_ file like a project entry point template.

## How to run 
- development environment: run `npm run start` and open _http://localhost:8080_ into your browser;
- production environment: run `npm run build` and enjoy.

_N.B. If 8080 port is busy, Webpack-Dev-Server will change the port dinamically. ;)_

## How to update
### Webpack
- update _build-utils/webpack.common.js_ file;
- update _build-utils/webpack.dev.js_ or _build-utils/webpack.prod.js_ files depending on enviroment to be updated.

### ESLint
- update _.eslintrc.json_ file.


Maintained with ❤️ by me and [Acadevmy](https://github.com/acadevmy/)!
