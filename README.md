# tiny-error


[![Build Status](https://img.shields.io/apm/v/npm?label=npm)](https://github.com/ibhargavgajjar/tiny-error)
[![npm bundle size(minified)](https://img.shields.io/bundlephobia/min/minified?label=minified%20size)](https://github.com/ibhargavgajjar/tiny-error)

A example of error module for npm.

## Install

```
npm install @ibhargavgajjar/tiny-error
```

## Usage

```js
const tiny = require("@ibhargavgajjar/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
