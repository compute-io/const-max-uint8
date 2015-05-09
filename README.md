Max Uint8
===
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coverage Status][coveralls-image]][coveralls-url] [![Dependencies][dependencies-image]][dependencies-url]

> Maximum unsigned 8-bit integer.


## Installation

``` bash
$ npm install compute-const-max-uint8
```

For use in the browser, use [browserify](https://github.com/substack/node-browserify).


## Usage

``` javascript
var MAX_UINT8 = require( 'compute-const-max-uint8' );
```

#### MAX_UINT8

Maximum unsigned 8-bit integer.

``` javascript
MAX_UINT8 === Math.pow( 2, 8 ) - 1;
```


## Examples

``` javascript
var MAX_UINT8 = require( 'compute-const-max-uint8' );

console.log( MAX_UINT8 );
// returns 255
```

To run the example code from the top-level application directory,

``` bash
$ node ./examples/index.js
```


## Tests

### Unit

Unit tests use the [Mocha](http://mochajs.org/) test framework with [Chai](http://chaijs.com) assertions. To run the tests, execute the following command in the top-level application directory:

``` bash
$ make test
```

All new feature development should have corresponding unit tests to validate correct functionality.


### Test Coverage

This repository uses [Istanbul](https://github.com/gotwarlost/istanbul) as its code coverage tool. To generate a test coverage report, execute the following command in the top-level application directory:

``` bash
$ make test-cov
```

Istanbul creates a `./reports/coverage` directory. To access an HTML version of the report,

``` bash
$ make view-cov
```


---
## License

[MIT license](http://opensource.org/licenses/MIT). 


## Copyright

Copyright &copy; 2015. Athan Reines.


[npm-image]: http://img.shields.io/npm/v/compute-const-max-uint8.svg
[npm-url]: https://npmjs.org/package/compute-const-max-uint8

[travis-image]: http://img.shields.io/travis/compute-io/const-max-uint8/master.svg
[travis-url]: https://travis-ci.org/compute-io/const-max-uint8

[coveralls-image]: https://img.shields.io/coveralls/compute-io/const-max-uint8/master.svg
[coveralls-url]: https://coveralls.io/r/compute-io/const-max-uint8?branch=master

[dependencies-image]: http://img.shields.io/david/compute-io/const-max-uint8.svg
[dependencies-url]: https://david-dm.org/compute-io/const-max-uint8

[dev-dependencies-image]: http://img.shields.io/david/dev/compute-io/const-max-uint8.svg
[dev-dependencies-url]: https://david-dm.org/dev/compute-io/const-max-uint8

[github-issues-image]: http://img.shields.io/github/issues/compute-io/const-max-uint8.svg
[github-issues-url]: https://github.com/compute-io/const-max-uint8/issues
