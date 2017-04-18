# npmtest-replay

#### test coverage for  [replay (v2.1.2)](https://github.com/assaf/node-replay#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-replay.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-replay) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-replay.svg)](https://travis-ci.org/npmtest/node-npmtest-replay)

#### When API testing slows you down: record and replay HTTP responses like a boss

[![NPM](https://nodei.co/npm/replay.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/replay)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-replay/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-replay/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-replay/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-replay/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-replay/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-replay/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-replay/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-replay/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-replay/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-replay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-replay/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-replay/build/test-report.html](https://npmtest.github.io/node-npmtest-replay/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-replay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-replay/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-replay/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-replay/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-replay/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-replay/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-replay/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-replay/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Assaf Arkin",
        "url": "http://labnotes.org/"
    },
    "bugs": {
        "url": "https://github.com/assaf/node-replay/issues"
    },
    "config": {
        "tag": "next"
    },
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "debug": "^2.2.0",
        "js-string-escape": "^1.0.1"
    },
    "description": "When API testing slows you down: record and replay HTTP responses like a boss",
    "devDependencies": {
        "async": "^2.0.1",
        "babel": "^6.5.2",
        "babel-eslint": "^6.1.2",
        "babel-preset-es2015-node4": "^2.1.0",
        "babel-preset-stage-2": "^6.13.0",
        "babel-register": "^6.14.0",
        "body-parser": "^1.15.2",
        "del": "^2.2.2",
        "eslint": "^3.5.0",
        "express": "^4.14.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-eslint": "^3.0.1",
        "gulp-exec": "^2.1.2",
        "gulp-notify": "^2.2.0",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-util": "^3.0.7",
        "mocha": "^3.0.2",
        "request": "^2.74.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8fa55e6546f0b29b1b850d60e571844711a2d67c",
        "tarball": "https://registry.npmjs.org/replay/-/replay-2.1.2.tgz"
    },
    "gitHead": "aa5a9f6c9bccb2202461cee06b614667b3685239",
    "homepage": "https://github.com/assaf/node-replay#readme",
    "keywords": [
        "test",
        "testing",
        "mock",
        "stub",
        "http",
        "replay",
        "vcr",
        "api"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/assaf/node-replay/blob/master/MIT-LICENSE"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "assaf"
        },
        {
            "name": "djanowski"
        }
    ],
    "name": "replay",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/assaf/node-replay.git"
    },
    "scripts": {
        "build": "gulp build",
        "postpublish": "gulp tag",
        "prepublish": "gulp build",
        "test": "mocha"
    },
    "version": "2.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
