# @lambrioanpm/non-aut-corporis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@lambrioanpm/non-aut-corporis');
const Eval = require('@lambrioanpm/non-aut-corporis/eval');
const Range = require('@lambrioanpm/non-aut-corporis/range');
const Ref = require('@lambrioanpm/non-aut-corporis/ref');
const Syntax = require('@lambrioanpm/non-aut-corporis/syntax');
const Type = require('@lambrioanpm/non-aut-corporis/type');
const URI = require('@lambrioanpm/non-aut-corporis/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@lambrioanpm/non-aut-corporis
[npm-version-svg]: https://versionbadg.es/ljharb/@lambrioanpm/non-aut-corporis.svg
[deps-svg]: https://david-dm.org/ljharb/@lambrioanpm/non-aut-corporis.svg
[deps-url]: https://david-dm.org/ljharb/@lambrioanpm/non-aut-corporis
[dev-deps-svg]: https://david-dm.org/ljharb/@lambrioanpm/non-aut-corporis/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@lambrioanpm/non-aut-corporis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@lambrioanpm/non-aut-corporis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@lambrioanpm/non-aut-corporis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@lambrioanpm/non-aut-corporis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@lambrioanpm/non-aut-corporis
[codecov-image]: https://codecov.io/gh/ljharb/@lambrioanpm/non-aut-corporis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@lambrioanpm/non-aut-corporis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@lambrioanpm/non-aut-corporis
[actions-url]: https://github.com/lambrioanpm/non-aut-corporis/actions
