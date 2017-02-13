# Angular JS 1.5 - ES6 Module Unit testing and Karma Integration testing seed by [@tomastrajan](https://twitter.com/tomastrajan) [![Build Status](https://travis-ci.org/tomastrajan/angular-js-es6-testing-example.svg?branch=master)](https://travis-ci.org/tomastrajan/angular-js-es6-testing-example)

## Getting started

1. Clone repository `git clone https://github.com/tomastrajan/angular-js-es6-testing-example.git`
2. Enter project directory `cd angular-js-es6-testing-example`
3. Install dependencies `npm i` or `npm install`

## Scripts

All scripts are run with `npm run [script]`, for example: `npm run test`.

* `start` - start development server, try it by opening `http://localhost:8081/webpack-dev-server/index.html`

* `build` - create dev build, check `build` directory
* `dist` - create production build, check `dist` directory

* `server_build` - serve content from `build` directory
* `server_dist` - serve content from `dist` directory

* `lint` - lint code (with ESLint)
* `mocha` - run all unit tests (with Mocha)
* `watch` - run and watch all unit tests (with Mocha)
* `karma` - run all integration tests (with Karma / Jasmine)
* `test` - lint code and run all tests (with Mocha and Karma)

# Tests

For more detailed info about tests check the original [blog post](https://medium.com/@tomastrajan/proper-testing-of-angular-js-applications-with-es6-modules-8cf31113873f).


* `*.test.js` - mocha unit tests
* `*.integration.test.js` - mocha integration tests (manual)
* `*.spec.js` - karma integration tests (spin up Angular JS app context)
