# @omegion1npm/consequatur-corporis-voluptatibus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@omegion1npm/consequatur-corporis-voluptatibus');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/consequatur-corporis-voluptatibus
[npm-version-svg]: https://versionbadg.es/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus.svg
[deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus.svg
[deps-url]: https://david-dm.org/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus
[dev-deps-svg]: https://david-dm.org/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/consequatur-corporis-voluptatibus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/consequatur-corporis-voluptatibus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/consequatur-corporis-voluptatibus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/consequatur-corporis-voluptatibus
[codecov-image]: https://codecov.io/gh/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@omegion1npm/consequatur-corporis-voluptatibus
[actions-url]: https://github.com/omegion1npm/consequatur-corporis-voluptatibus/actions
