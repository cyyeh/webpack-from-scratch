# Webpack from Scratch

This repo demonstrates that how can we configure webpack, babel, etc. to work with react.

## [Webpack Core Concepts](https://webpack.js.org/concepts/)

### Entry

By default its value is `./src/index.js`

### Output

It defaults to `./dist/main.js` for the main output file and to the `./dist` folder for any other generated file.

### Loaders

Out of the box, webpack only understands JavaScript and JSON files. Loaders allow webpack to process other types of files and convert them into valid modules that can be consumed by your application and added to the dependency graph.


### Plugins

While loaders are used to transform certain types of modules, plugins can be leveraged to perform a wider range of tasks like bundle optimization, asset management and injection of environment variables.

### Mode

By setting the mode parameter to either development, production or none, you can enable webpack's built-in optimizations that correspond to each environment. The default value is production.

### Browser Compatibility

Webpack supports all browsers that are ES5-compliant (IE8 and below are not supported). 
