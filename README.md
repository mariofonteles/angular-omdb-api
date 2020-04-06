# Angular omdbAPI 

This is a simple work-in-progress SPA showcasing some cool Angular, ES6+ and SASS functionalities.

## How to run

First, make sure you have the latest stable releases of Node, npm and the [Angular CLI](https://cli.angular.io/).

Install dependencies:

```
npm install
```

Start dev server:
```
ng serve
```

The app will be located at `http://localhost:4200/`.

Build:

```
ng build
```

## Running Unit Tests

Unit testing in this project is achieved with [Karma](https://karma-runner.github.io) and [Jasmine](https://jasmine.github.io/). The command `ng test` will run all tests.

## Project overview

Some project features:

* Responsive design achieved with some SASS and CSS3 implementations alongside Bootstrap
* Infinite Scrolling movies list
* Simple data persistency(favourited movies) with localStorage
* Unit Tests

TO-DO List:

* Refactor project modules aiming for lazy-loading implementation
* Add Deboucing measures for the movie search component
* Create an Express.js API with session handling to maintain some user features such as favourited movies