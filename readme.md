## [![npm][npmjs-img]][npmjs-url] [![mit license][license-img]][license-url] [![build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![deps status][daviddm-img]][daviddm-url]

> Get current week number of the current year or given date string format.

## Install
```bash
npm install current-week-number
npm test
```


## API
> For more use-cases see the [tests](./test.js)

### [currentWeekNumber](./index.js#L40)
> Get week number of the current date/year or given valid `Date` string format

- `[date]` **{String}** every valid Date-ish string format
- `return` **{Number}**

**Example:**

```js
var currentWeekNumber = require('current-week-number');

// june 27, 2014
currentWeekNumber()
//=> 26

currentWeekNumber('March 24, 2015')
//=> 13

currentWeekNumber('03/24/2016')
//=> 12, cuz' year is leap

currentWeekNumber('August 07, 2015')
//=> 32

currentWeekNumber('02/16/2015')
//=> 8
```


## Author
**Charlike Mike Reagent**
+ [gratipay/tunnckoCore][author-gratipay]
+ [twitter/tunnckoCore][author-twitter]
+ [github/tunnckoCore][author-github]
+ [npmjs/tunnckoCore][author-npmjs]
+ [more ...][contrib-more]


## License [![MIT license][license-img]][license-url]
Copyright (c) 2014-2015 [Charlike Mike Reagent][contrib-more], [contributors][contrib-graf].  
Released under the [`MIT`][license-url] license.


[npmjs-url]: http://npm.im/current-week-number
[npmjs-img]: https://img.shields.io/npm/v/current-week-number.svg?style=flat&label=current-week-number

[coveralls-url]: https://coveralls.io/r/datetime/current-week-number?branch=master
[coveralls-img]: https://img.shields.io/coveralls/datetime/current-week-number.svg?style=flat

[license-url]: https://github.com/datetime/current-week-number/blob/master/license.md
[license-img]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat

[travis-url]: https://travis-ci.org/datetime/current-week-number
[travis-img]: https://img.shields.io/travis/datetime/current-week-number.svg?style=flat

[daviddm-url]: https://david-dm.org/datetime/current-week-number
[daviddm-img]: https://img.shields.io/david/datetime/current-week-number.svg?style=flat

[author-gratipay]: https://gratipay.com/tunnckoCore
[author-twitter]: https://twitter.com/tunnckoCore
[author-github]: https://github.com/tunnckoCore
[author-npmjs]: https://npmjs.org/~tunnckocore

[contrib-more]: http://j.mp/1stW47C
[contrib-graf]: https://github.com/datetime/current-week-number/graphs/contributors

***

_Powered and automated by [kdf](https://github.com/tunnckoCore), January 26, 2015_