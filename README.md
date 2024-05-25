# parseInt <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `parseInt` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@swenkerorg/eaque-nihil).

## Getting started

```sh
npm install --save @swenkerorg/eaque-nihil
```

## Usage/Examples

```js
console.log(parseInt("-3")); // -3
console.log(parseInt("0x10")); // 16
console.log(parseInt("30", 7)); // 21
console.log(parseInt("ef")); // NaN
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@swenkerorg/eaque-nihil
[npm-version-svg]: https://versionbadg.es/swenkerorg/eaque-nihil.svg
[deps-svg]: https://david-dm.org/swenkerorg/eaque-nihil.svg
[deps-url]: https://david-dm.org/swenkerorg/eaque-nihil
[dev-deps-svg]: https://david-dm.org/swenkerorg/eaque-nihil/dev-status.svg
[dev-deps-url]: https://david-dm.org/swenkerorg/eaque-nihil#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@swenkerorg/eaque-nihil.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@swenkerorg/eaque-nihil.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@swenkerorg/eaque-nihil.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@swenkerorg/eaque-nihil
[codecov-image]: https://codecov.io/gh/swenkerorg/eaque-nihil/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/swenkerorg/eaque-nihil/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/swenkerorg/eaque-nihil
[actions-url]: https://github.com/swenkerorg/eaque-nihil/actions
