# npmtest-gulp-htmlincluder

#### test coverage for  [gulp-htmlincluder (v0.1.0)](https://github.com/internetErik/gulp-htmlincluder)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-htmlincluder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-htmlincluder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-htmlincluder.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-htmlincluder)

#### Gulp plugin for building HTML files into each other.  Made for a workflow involving responsive unit testing.

[![NPM](https://nodei.co/npm/gulp-htmlincluder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-htmlincluder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-htmlincluder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-htmlincluder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-htmlincluder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-htmlincluder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-htmlincluder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-htmlincluder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-htmlincluder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Erik Christianson",
        "url": "https://github.com/internetErik"
    },
    "bugs": {
        "url": "https://github.com/internetErik/gulp-htmlincluder/issues"
    },
    "dependencies": {
        "gulp-util": "~2.2.0",
        "through2": "*"
    },
    "description": "Gulp plugin for building HTML files into each other.  Made for a workflow involving responsive unit testing.",
    "devDependencies": {
        "coveralls": "*",
        "event-stream": "*",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "should": "~2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "71c0893985c8c84111e6f39b5dc6e03d63fe4909",
        "tarball": "https://registry.npmjs.org/gulp-htmlincluder/-/gulp-htmlincluder-0.1.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "d81d2fd854f6a297e433663cf9c8ffbeb963cd1e",
    "homepage": "https://github.com/internetErik/gulp-htmlincluder",
    "keywords": [
        "gulpplugin"
    ],
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "main": "./index.js",
    "maintainers": [
        {
            "name": "interneterik"
        }
    ],
    "name": "gulp-htmlincluder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/internetErik/gulp-htmlincluder.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test _mocha --report html -- test/*.js --reporter spec"
    },
    "version": "0.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
