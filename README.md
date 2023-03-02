# @power137/tiny

[![npm (scoped)](https://img.shields.io/badge/npm-0.0.1-blue)](https://www.npmjs.com/package/@power137/tiny)
[![license](https://img.shields.io/badge/license-MIT-green)](https://www.npmjs.com/package/@power137/tiny)


## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@power137/tiny");
tiny("So much space!");
//=> "Somuchspace!"
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```