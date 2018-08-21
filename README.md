# Boilerplate

### Packages & Software Used


The only requirement for the boilerplate to be installed is [NodeJS] & [NPM]. The core of the 
boilerplate was created with [Vue CLI] 3.x and uses [Vue] 2.x as the front-end JS framework.


##### Additional software used within the boilerplate are:

| Package       | Version       | Description |
| ------------- |:-------------:| -----|
| Babel         | 6.x   | JS Compiler for ES6+ syntax. |
| Webpack       | 4.x   | JS Bundler w/SCSS support pre-configured. |
| VueX          | 3.x   | State Management patterns + library for Vue.js applications. |
| Vue Router    | 3.x   | Integrated router for SPAs. |


##### Style, Linting, and Unit Tests
- [SCSS] is used as CSS pre-processor, with webpack configuration baked-in.
- [Airbnb ESLint] configuration is used to standardize JS styles and provides out of the box configuration.
- [Chai] is provided as the unit test framework, if you so desire.



-------------------------------------------------------------------------------


### Installation Instructions

Under the assumption that both, [NodeJS] & [NPM] are already installed globally on your system, a simple
 ``` npm install ``` should build the entire project. 
 


-------------------------------------------------------------------------------

 

### Building Development & Production Environments

The `vue-cli-service` is used for running quick development environment, as well as building and minifying 
your production release.


##### Development:
```
npm run serve
```

##### Production:
```
npm run build
```

##### Other Commands:

- Linting and fixes files: ```npm run lint```
- Run your unit tests: ```npm run test:unit```








[Airbnb ESLint]: https://github.com/airbnb/javascript
[Babel]: https://babeljs.io/
[Chai]: http://www.chaijs.com/
[NodeJS]: https://nodejs.org/en/
[NPM]: https://www.npmjs.com/
[SCSS]: https://sass-lang.com/
[Vue]: https://vuejs.org/
[Vue CLI]: https://cli.vuejs.org/guide/installation.html
[Vue Router]: https://router.vuejs.org/
[Vuex]: https://vuex.vuejs.org/
[Webpack]: https://webpack.js.org/
