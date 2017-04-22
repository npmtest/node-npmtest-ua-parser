# npmtest-ua-parser

#### basic test coverage for  [ua-parser (v0.3.5)](https://github.com/tobie/ua-parser)  [![npm package](https://img.shields.io/npm/v/npmtest-ua-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ua-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ua-parser.svg)](https://travis-ci.org/npmtest/node-npmtest-ua-parser)

#### A port of Browserscope's user agent parser.

[![NPM](https://nodei.co/npm/ua-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ua-parser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ua-parser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ua-parser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ua-parser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ua-parser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ua-parser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ua-parser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ua-parser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ua-parser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ua-parser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ua-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ua-parser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ua-parser/build/test-report.html](https://npmtest.github.io/node-npmtest-ua-parser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ua-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ua-parser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ua-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ua-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ua-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ua-parser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ua-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ua-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/tobie/ua-parser/issues"
    },
    "contributors": [
        {
            "name": "Tobie Langel",
            "url": "http://tobielangel.com"
        },
        {
            "name": "Lindsey Simon",
            "url": "http://www.idreamofuni.com"
        },
        {
            "name": "Philip Tellis",
            "url": "http://bluesmoon.info"
        },
        {
            "name": "Dave Olsen",
            "url": "http://dmolsen.com"
        }
    ],
    "dependencies": {
        "yamlparser": ">=0.0.2"
    },
    "description": "A port of Browserscope's user agent parser.",
    "devDependencies": {
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "2ff4f9c9e6e2d64d711461f17beb2c9c697f2f1a",
        "tarball": "https://registry.npmjs.org/ua-parser/-/ua-parser-0.3.5.tgz"
    },
    "gitHead": "7ad65f22f29a9fad784b6c5af47fd04298a6d81b",
    "homepage": "https://github.com/tobie/ua-parser",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/tobie/ua-parser/master/js/LICENSE"
        },
        {
            "type": "Apache-2.0",
            "url": "https://raw.github.com/tobie/ua-parser/master/js/LICENSE"
        }
    ],
    "main": "./js/index",
    "maintainers": [
        {
            "name": "tobie"
        }
    ],
    "name": "ua-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/tobie/ua-parser.git"
    },
    "scripts": {
        "test": "mocha -u tdd -R dot ./js/test/*.js"
    },
    "version": "0.3.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
