[![npm (scoped)](https://img.shields.io/npm/v/:scope/:package.svg)](https://github.com/hjmendoza/tiny.git)

[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/react.svg)](https://github.com/hjmendoza/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @hjmendoza/tiny
```

## Usage

```js
const tiny = require("@hjmendoza/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

Followed Medium tutorial. 