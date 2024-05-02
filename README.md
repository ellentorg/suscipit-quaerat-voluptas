# @ellentorg/suscipit-quaerat-voluptas <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@ellentorg/suscipit-quaerat-voluptas');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@ellentorg/suscipit-quaerat-voluptas
[npm-version-svg]: https://versionbadg.es/ljharb/@ellentorg/suscipit-quaerat-voluptas.svg
[deps-svg]: https://david-dm.org/ljharb/@ellentorg/suscipit-quaerat-voluptas.svg
[deps-url]: https://david-dm.org/ljharb/@ellentorg/suscipit-quaerat-voluptas
[dev-deps-svg]: https://david-dm.org/ljharb/@ellentorg/suscipit-quaerat-voluptas/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@ellentorg/suscipit-quaerat-voluptas#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@ellentorg/suscipit-quaerat-voluptas.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@ellentorg/suscipit-quaerat-voluptas.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@ellentorg/suscipit-quaerat-voluptas.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@ellentorg/suscipit-quaerat-voluptas
[codecov-image]: https://codecov.io/gh/ljharb/@ellentorg/suscipit-quaerat-voluptas/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@ellentorg/suscipit-quaerat-voluptas/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@ellentorg/suscipit-quaerat-voluptas
[actions-url]: https://github.com/ellentorg/suscipit-quaerat-voluptas/actions
