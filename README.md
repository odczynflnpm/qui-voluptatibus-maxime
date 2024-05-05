# @odczynflnpm/qui-voluptatibus-maxime <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@odczynflnpm/qui-voluptatibus-maxime');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@odczynflnpm/qui-voluptatibus-maxime
[npm-version-svg]: https://versionbadg.es/inspect-js/@odczynflnpm/qui-voluptatibus-maxime.svg
[deps-svg]: https://david-dm.org/inspect-js/@odczynflnpm/qui-voluptatibus-maxime.svg
[deps-url]: https://david-dm.org/inspect-js/@odczynflnpm/qui-voluptatibus-maxime
[dev-deps-svg]: https://david-dm.org/inspect-js/@odczynflnpm/qui-voluptatibus-maxime/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@odczynflnpm/qui-voluptatibus-maxime#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@odczynflnpm/qui-voluptatibus-maxime.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@odczynflnpm/qui-voluptatibus-maxime.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@odczynflnpm/qui-voluptatibus-maxime.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@odczynflnpm/qui-voluptatibus-maxime
[codecov-image]: https://codecov.io/gh/inspect-js/@odczynflnpm/qui-voluptatibus-maxime/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@odczynflnpm/qui-voluptatibus-maxime/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@odczynflnpm/qui-voluptatibus-maxime
[actions-url]: https://github.com/odczynflnpm/qui-voluptatibus-maxime/actions
