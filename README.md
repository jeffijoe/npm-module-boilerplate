# npm-module-boilerplate

[![npm](https://img.shields.io/npm/v/npm-module-boilerplate.svg?maxAge=1000)](https://www.npmjs.com/package/npm-module-boilerplate)
[![dependency Status](https://img.shields.io/david/jeffijoe/npm-module-boilerplate.svg?maxAge=1000)](https://david-dm.org/jeffijoe/npm-module-boilerplate)
[![devDependency Status](https://img.shields.io/david/dev/jeffijoe/npm-module-boilerplate.svg?maxAge=1000)](https://david-dm.org/jeffijoe/npm-module-boilerplate)
[![Build Status](https://img.shields.io/travis/jeffijoe/npm-module-boilerplate.svg?maxAge=1000)](https://travis-ci.org/jeffijoe/npm-module-boilerplate)
[![Coveralls](https://img.shields.io/coveralls/jeffijoe/npm-module-boilerplate.svg?maxAge=1000)](https://coveralls.io/github/jeffijoe/npm-module-boilerplate)
[![Code Climate](https://img.shields.io/codeclimate/github/jeffijoe/npm-module-boilerplate.svg?maxAge=1000)](https://codeclimate.com/github/jeffijoe/npm-module-boilerplate)
[![npm](https://img.shields.io/npm/dt/npm-module-boilerplate.svg?maxAge=1000)](https://www.npmjs.com/package/npm-module-boilerplate)
[![npm](https://img.shields.io/npm/l/npm-module-boilerplate.svg?maxAge=1000)](https://github.com/jeffijoe/npm-module-boilerplate/blob/master/LICENSE.md)
[![node](https://img.shields.io/node/v/npm-module-boilerplate.svg?maxAge=1000)](https://www.npmjs.com/package/npm-module-boilerplate)
[![JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

A boilerplate for authoring npm modules, with tests and linting.

## What's in the package?

Well, let me tell you!

* `ava` and `sinon` for tests
* `nyc` for code coverage
* `eslint-watch` for linting
* `npm run` scripts for the above, so you won't have to install any global packages while authoring your module (I hate global modules, *grr*)
* `.travis.yml` for CI

## `npm run` scripts

* `npm run test`: Runs tests once
* `npm run test:watch`: Runs tests in watch-mode
* `npm run lint`: Lints the code once
* `npm run lint:watch`: Lints the code in watch-mode
* `npm run cover`: Runs code coverage using `nyc` (`istanbul`)
* `npm run coveralls`: Used by coveralls
* `npm run do-publish`: Used when publishing the package.

## Getting started

1. Clone this repo, or download it as a zip
    * If you decide to clone, remove the `.git` folder so you don't get unnecessary git history.
2. Find and replace all occurences of `npm-module-boilerplate` and replace
   it with your module name - filenames, too. You might also want to replace `jeffijoe` with your own Github username... Probably the LICENSE.md as well. :smile:
3. Edit `package.json`, `LICENSE.md` and `README.md` for your own needs.
4. `npm install` and start coding! open 2 terminals, one for linting (`npm run lint-watch`) and one for testing (`npm run test-watch`) - at least that's what I do. ;)
5. Write your code in `lib/npm-module-boilerplate.js` (this is the main file)
6. Write your tests in `test/lib/npm-module-boilerplate.spec.js` (.. or, don't?)
7. Publish!

# Author

Jeff Hansen - [@Jeffijoe](https://twitter.com/Jeffijoe)
