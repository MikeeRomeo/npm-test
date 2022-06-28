# @mikeromeo/npm-test

[![npm (scoped)](https://img.shields.io/npm/v/@mikeromeo/npm-test.svg)](https://www.npmjs.com/package/@mikeromeo/npm-test)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mikeromeo/npm-test.svg)](https://www.npmjs.com/package/@mikeromeo/npm-test)

Testing testing

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
