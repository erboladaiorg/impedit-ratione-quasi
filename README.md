# @erboladaiorg/impedit-ratione-quasi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@erboladaiorg/impedit-ratione-quasi');

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

[package-url]: https://npmjs.org/package/@erboladaiorg/impedit-ratione-quasi
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiorg/impedit-ratione-quasi.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/impedit-ratione-quasi.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiorg/impedit-ratione-quasi
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/impedit-ratione-quasi/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiorg/impedit-ratione-quasi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/impedit-ratione-quasi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/impedit-ratione-quasi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/impedit-ratione-quasi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/impedit-ratione-quasi
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiorg/impedit-ratione-quasi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiorg/impedit-ratione-quasi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiorg/impedit-ratione-quasi
[actions-url]: https://github.com/erboladaiorg/impedit-ratione-quasi/actions
