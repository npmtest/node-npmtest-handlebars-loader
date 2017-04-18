# npmtest-handlebars-loader

#### test coverage for  [handlebars-loader (v1.4.0)](https://github.com/pcardune/handlebars-loader)  [![npm package](https://img.shields.io/npm/v/npmtest-handlebars-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-handlebars-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-handlebars-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-handlebars-loader)

#### handlebars loader module for webpack

[![NPM](https://nodei.co/npm/handlebars-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/handlebars-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-handlebars-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-handlebars-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-handlebars-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-handlebars-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-handlebars-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-handlebars-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-handlebars-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-handlebars-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-handlebars-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-handlebars-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-handlebars-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-handlebars-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-handlebars-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-handlebars-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-handlebars-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-handlebars-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-handlebars-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-handlebars-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-handlebars-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-handlebars-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-handlebars-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/pcardune/handlebars-loader/issues"
    },
    "contributors": [
        {
            "name": "Alan @altano"
        },
        {
            "name": "Tobias Koppers @sokra"
        },
        {
            "name": "Jason Anderson @diurnalist"
        }
    ],
    "dependencies": {
        "async": "~0.2.10",
        "fastparse": "^1.0.0",
        "loader-utils": "0.2.x",
        "object-assign": "^4.1.0"
    },
    "description": "handlebars loader module for webpack",
    "devDependencies": {
        "coveralls": "^2.11.8",
        "eslint": "^2.8.0",
        "html-loader": "^0.3.0",
        "istanbul": "^0.4.2",
        "mocha": "^1.21.4",
        "npm-release": "^1.0.0",
        "sinon": "^1.10.3"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "142b2c29bcb8e407554fbc8846feef9f90da3317",
        "tarball": "https://registry.npmjs.org/handlebars-loader/-/handlebars-loader-1.4.0.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "5c867860a7abd8adb178813c7effbbc50edfb82b",
    "homepage": "https://github.com/pcardune/handlebars-loader",
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "altano"
        },
        {
            "name": "diurnalist"
        },
        {
            "name": "pcardune"
        }
    ],
    "name": "handlebars-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "handlebars": ">= 1.3.0 < 5"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/pcardune/handlebars-loader.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "lint": "eslint lib/ test/ index.js",
        "test": "mocha"
    },
    "version": "1.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
