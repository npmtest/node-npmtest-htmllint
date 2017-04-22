# npmtest-htmllint

#### basic test coverage for  [htmllint (v0.6.0)](https://github.com/htmllint/htmllint#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-htmllint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-htmllint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-htmllint.svg)](https://travis-ci.org/npmtest/node-npmtest-htmllint)

#### An unofficial html5 linter.

[![NPM](https://nodei.co/npm/htmllint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/htmllint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-htmllint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-htmllint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-htmllint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-htmllint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-htmllint/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-htmllint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-htmllint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-htmllint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-htmllint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-htmllint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-htmllint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-htmllint/build/test-report.html](https://npmtest.github.io/node-npmtest-htmllint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-htmllint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-htmllint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-htmllint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-htmllint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-htmllint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-htmllint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-htmllint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-htmllint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browserify": {
        "transform": [
            "bulkify"
        ]
    },
    "bugs": {
        "url": "https://github.com/htmllint/htmllint/issues"
    },
    "contributors": [
        {
            "name": "Michael Coleman",
            "url": "http://github.com/coalman"
        },
        {
            "name": "Andrew Messier",
            "url": "http://github.com/messman"
        },
        {
            "name": "Marshall Lochbaum",
            "url": "http://github.com/mlochbaum"
        },
        {
            "name": "Roman Myers",
            "url": "http://github.com/romnempire"
        }
    ],
    "dependencies": {
        "bulk-require": "^1.0.0",
        "htmlparser2": "^3.7.3",
        "lodash": "^4.3.0",
        "promise": "^7.1.1"
    },
    "description": "An unofficial html5 linter.",
    "devDependencies": {
        "bulkify": "^1.0.2",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "gulp": "^3.9.1",
        "gulp-coveralls": "^0.1.3",
        "gulp-eslint": "^3.0.1",
        "gulp-gh-pages": "^0.5.4",
        "gulp-istanbul": "^1.0.0",
        "gulp-jscs": "^4.0.0",
        "gulp-jsdoc": "^0.1.4",
        "gulp-jshint": "^2.0.0",
        "gulp-mocha": "^3.0.1",
        "jshint": "^2.9.1",
        "jshint-stylish": "^2.1.0",
        "mocha": "^3.2.0",
        "plato": "^1.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dbb006676dd66d767cb1b6bb875f08840b91998d",
        "tarball": "https://registry.npmjs.org/htmllint/-/htmllint-0.6.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "aa5583c5c4c26ac24bed17193a5d92309b49cab6",
    "homepage": "https://github.com/htmllint/htmllint#readme",
    "keywords": [
        "html",
        "lint",
        "hint",
        "htmllint"
    ],
    "license": "ISC",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "coalman"
        },
        {
            "name": "mlochbaum"
        }
    ],
    "name": "htmllint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/htmllint/htmllint.git"
    },
    "scripts": {
        "test": "./node_modules/gulp/bin/gulp.js travis",
        "testlocal": "gulp test"
    },
    "version": "0.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
