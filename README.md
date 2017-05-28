# Savvy CSS Normalize

[![Latest NPM release][npm-badge]][npm-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]
[![Dev Dependencies][devDependencies-badge]][devDependencies-badge-url]
[![License][license-badge]][license-badge-url]

Normalization settings for Savvy CSS.

Read more about [Savvy CSS's design principles](https://github.com/savvy-css/savvy/doc).

## Installation

```shell
yarn add --dev @savvy-css/normalize
``` 

## Usage

### What's Normalization?

This module is essentially Savvy CSS's take on CSS normalization.
It's inspired heavily -- but with slightly deviating opinions -- by the excellent
[Normalize.css](https://necolas.github.io/normalize.css/) project.


Whereas a CSS reset focuses on "unstyling" things, _normalization_ aims to patch
minor bugs or tweak standard elements while still preserving
the built-in browser settings outside of its scope.

Though somewhat dated, this [introductory blog post to Normalize CSS](http://nicolasgallagher.com/about-normalize-css/)
goes into great details about its overall purpose.

It's also important to recognize what normalization _isn't_: a
full set of style rules for HTML elements. For example, whereas
normalization is concerned with ensuring that the `<body>` element always has
`margin` set to `0`, a separate typography module should be concerned
with defining a `font-family` stack for the `<body>` element.


[npm-badge]: https://img.shields.io/npm/v/@savvy-css/normalize.svg
[npm-badge-url]: https://www.npmjs.com/package/@savvy-css/normalize
[license-badge]: https://img.shields.io/npm/l/@savvy-css/normalize.svg
[license-badge-url]: LICENSE
[dependencies-badge]: https://img.shields.io/david/savvy-css/normalize.svg
[dependencies-badge-url]: https://david-dm.org/savvy-css/normalize
[devDependencies-badge]: https://img.shields.io/david/dev/savvy-css/normalize.svg
[devDependencies-badge-url]: https://david-dm.org/savvy-css/normalize#info=devDependencies