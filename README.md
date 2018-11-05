# @umerrinayat/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@umerrinayat/tiny.svg)](https://www.npmjs.com/package/@umerrinayat/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@umerrinayat/tiny.svg)](https://www.npmjs.com/package/@umerrinayat/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @umerrinayat/tiny
```

## Usage

```js
const tiny = require("@umerrinayat/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```