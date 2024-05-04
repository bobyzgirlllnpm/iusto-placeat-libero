# @bobyzgirlllnpm/iusto-placeat-libero <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A robust, ES3 compatible, "has own property" predicate.

## Example

```js
const assert = require('assert');
const hasOwn = require('@bobyzgirlllnpm/iusto-placeat-libero');

assert.equal(hasOwn({}, 'toString'), false);
assert.equal(hasOwn([], 'length'), true);
assert.equal(hasOwn({ a: 42 }, 'a'), true);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/iusto-placeat-libero
[npm-version-svg]: https://versionbadg.es/inspect-js/@bobyzgirlllnpm/iusto-placeat-libero.svg
[deps-svg]: https://david-dm.org/bobyzgirlllnpm/iusto-placeat-libero.svg
[deps-url]: https://david-dm.org/bobyzgirlllnpm/iusto-placeat-libero
[dev-deps-svg]: https://david-dm.org/bobyzgirlllnpm/iusto-placeat-libero/dev-status.svg
[dev-deps-url]: https://david-dm.org/bobyzgirlllnpm/iusto-placeat-libero#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/iusto-placeat-libero.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/iusto-placeat-libero.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/iusto-placeat-libero.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/iusto-placeat-libero
[codecov-image]: https://codecov.io/gh/bobyzgirlllnpm/iusto-placeat-libero/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/bobyzgirlllnpm/iusto-placeat-libero/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/bobyzgirlllnpm/iusto-placeat-libero
[actions-url]: https://github.com/bobyzgirlllnpm/iusto-placeat-libero/actions
