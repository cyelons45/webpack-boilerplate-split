# Split Webpack Boilerplate

A webpack boilerplate with separate development and production configurations
and no repeated code.

## Single Branch

This branch in fact contains only a single generic webpack configuration
supporting
* loading of CSS, image and font assets,
* transpilation of JavaScript down to ES5,
* generation of an HTML index file.

It exists mainly as a checkpoint as you follow my [webpack configuration
tutorial](https://alexthorne.io/2017/12/10/webpack-boilerplate-from-scratch/).
It becomes the common base on which the separate production and development
configurations are built.
