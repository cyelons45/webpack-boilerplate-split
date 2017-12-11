# Split Webpack Boilerplate

A webpack boilerplate with separate development and production configurations
and no repeated code.

Both configurations support:
* loading of CSS, image and font assets,
* transpilation of JavaScript down to ES5,
* generation of an HTML index file.

The production build additionally supports [minification][Minification] and
[tree shaking][TreeShaking] for reducing bundle size.

The development build supports [hot module reloading][HMR] for easier
development.

## Split/Main Branch

This branch (generally in line with `master`) contains the full split build
configuration. If you want to know exactly how the boilerplate code was put
together, please read my [webpack configuration
tutorial](https://alexthorne.io/2017/12/10/webpack-boilerplate-from-scratch/).


[Minification]: https://en.wikipedia.org/wiki/Minification_(programming)
[TreeShaking]: https://developer.mozilla.org/en-US/docs/Glossary/Tree_shaking
[HMR]: https://webpack.js.org/concepts/hot-module-replacement/
