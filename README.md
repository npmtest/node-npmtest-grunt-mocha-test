# npmtest-grunt-mocha-test

#### basic test coverage for  [grunt-mocha-test (v0.13.2)](https://github.com/pghalliday/grunt-mocha-test)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-mocha-test.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-mocha-test) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-mocha-test.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-mocha-test)

#### A grunt task for running server side mocha tests

[![NPM](https://nodei.co/npm/grunt-mocha-test.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-mocha-test)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-mocha-test/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-mocha-test/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-mocha-test/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-mocha-test/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-mocha-test/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Peter Halliday",
        "url": "http://pghalliday.github.io/"
    },
    "bugs": {
        "url": "https://github.com/pghalliday/grunt-mocha-test/issues"
    },
    "config": {
        "travis-cov": {
            "threshold": 100
        }
    },
    "dependencies": {
        "hooker": "^0.2.3",
        "mkdirp": "^0.5.0"
    },
    "description": "A grunt task for running server side mocha tests",
    "devDependencies": {
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-continue": "^0.1.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-coveralls": "^1.0.1",
        "grunt-env": "^0.4.4",
        "grunt-istanbul": "^0.7.1",
        "grunt-istanbul-coverage": "^0.1.4",
        "mocha": "^3.0.2",
        "rimraf": "^2.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0f3abcc6ab543647b1effc5ab44ebd3702f0ab8c",
        "tarball": "https://registry.npmjs.org/grunt-mocha-test/-/grunt-mocha-test-0.13.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.4"
    },
    "files": [
        "tasks",
        "LICENSE-MIT"
    ],
    "gitHead": "19af1b447f9883bd59e92ce4ad308f3668d85740",
    "homepage": "https://github.com/pghalliday/grunt-mocha-test",
    "keywords": [
        "gruntplugin",
        "mocha",
        "test"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "pghalliday"
        }
    ],
    "name": "grunt-mocha-test",
    "optionalDependencies": {},
    "peerDependencies": {
        "mocha": ">=1.20.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/pghalliday/grunt-mocha-test.git"
    },
    "scripts": {
        "ci": "grunt ci",
        "test": "grunt"
    },
    "version": "0.13.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
