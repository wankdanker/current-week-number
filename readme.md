# Week number [![NPM version][npmjs-shields]][npmjs-url] [![Build Status][travis-img]][travis-url] [![Dependency Status][depstat-img]][depstat-url] [![Coveralls][coveralls-shields]][coveralls-url]

> Get current week number of the current year or given date string format.

## Install [![Nodei.co stats][npmjs-install]][npmjs-url] 

> Install with [npm](https://npmjs.org)

```
$ npm install current-week-number
```

## Usage
```js
var currentWeekNumber = require('current-week-number');

// june 27, 2014
currentWeekNumber()
//=> 26

currentWeekNumber("March 24, 2015")
//=> 13

currentWeekNumber("03/24/2016")
//=> 12, cuz' year is leap

currentWeekNumber("August 07, 2015")
//=> 32

currentWeekNumber("02/16/2015")
//=> 8
```

## Authors & Contributors
**Charlike Mike Reagent** [![author tips][author-gittip-img]][author-gittip]
+ [gittip/tunnckoCore][author-gittip]
+ [github/tunnckoCore][author-github]
+ [twitter/tunnckoCore][author-twitter]
+ [npmjs/tunnckoCore][author-npmjs]


## License [![MIT license][license-img]][license-url]
Copyright (c) 2014 [Charlike Mike Reagent][author-website], [contributors](https://github.com/tunnckoCore/current-week-number/graphs/contributors).  
Released under the [`MIT`][license-url] license.


[npmjs-url]: http://npm.im/current-week-number
[npmjs-shields]: http://img.shields.io/npm/v/current-week-number.svg
[npmjs-install]: https://nodei.co/npm/current-week-number.svg?mini=true

[coveralls-url]: https://coveralls.io/r/tunnckoCore/current-week-number?branch=master
[coveralls-shields]: https://img.shields.io/coveralls/tunnckoCore/current-week-number.svg

[license-url]: https://github.com/tunnckoCore/current-week-number/blob/master/license.md
[license-img]: http://img.shields.io/badge/license-MIT-blue.svg

[travis-url]: https://travis-ci.org/tunnckoCore/current-week-number
[travis-img]: https://travis-ci.org/tunnckoCore/current-week-number.svg?branch=master

[depstat-url]: https://david-dm.org/tunnckoCore/current-week-number
[depstat-img]: https://david-dm.org/tunnckoCore/current-week-number.svg

[author-gittip-img]: http://img.shields.io/gittip/tunnckoCore.svg
[author-gittip]: https://www.gittip.com/tunnckoCore
[author-github]: https://github.com/tunnckoCore
[author-twitter]: https://twitter.com/tunnckoCore

[author-website]: http://www.whistle-bg.tk
[author-npmjs]: https://npmjs.org/~tunnckocore
