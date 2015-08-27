# split-string [![NPM version](https://badge.fury.io/js/split-string.svg)](http://badge.fury.io/js/split-string)

> Split a string on a character except when the character is escaped.

## Install

Install with [npm](https://www.npmjs.com/)

```sh
$ npm i split-string --save
```

## Usage

```js
var split = require('split-string');

split('a.b.c');
//=> ['a', 'b', 'c']
```

**respects escaped characters**

```js
split('a.b.c\\.d');
//=> ['a', 'b', 'c.d']
```

## Related projects

* [deromanize](https://www.npmjs.com/package/deromanize): Convert roman numerals to arabic numbers (useful for books, outlines, documentation, slide decks, etc) | [homepage](https://github.com/jonschlinkert/deromanize)
* [randomatic](https://www.npmjs.com/package/randomatic): Generate randomized strings of a specified length, fast. Only the length is necessary, but you… [more](https://www.npmjs.com/package/randomatic) | [homepage](https://github.com/jonschlinkert/randomatic)
* [repeat-string](https://www.npmjs.com/package/repeat-string): Repeat the given string n times. Fastest implementation for repeating a string. | [homepage](https://github.com/jonschlinkert/repeat-string)
* [romanize](https://www.npmjs.com/package/romanize): Convert numbers to roman numerals (useful for books, outlines, documentation, slide decks, etc) | [homepage](https://github.com/jonschlinkert/romanize)

## Running tests

Install dev dependencies:

```sh
$ npm i -d && npm test
```

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/split-string/issues/new).

## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License

Copyright © 2015 Jon Schlinkert
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on August 27, 2015._
