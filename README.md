# Savvy CSS Normalize

[![Greenkeeper badge](https://badges.greenkeeper.io/savvy-css/normalize.svg)](https://greenkeeper.io/)

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
