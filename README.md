# npmtest-indicative

#### basic test coverage for  [indicative (v2.2.1)](https://github.com/poppinss/indicative#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-indicative.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-indicative) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-indicative.svg)](https://travis-ci.org/npmtest/node-npmtest-indicative)

#### Intentionally beautiful schema and raw validator for nodejs

[![NPM](https://nodei.co/npm/indicative.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/indicative)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-indicative/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-indicative/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-indicative/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-indicative/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-indicative/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-indicative/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-indicative/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-indicative/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-indicative/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-indicative/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-indicative/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-indicative/build/test-report.html](https://npmtest.github.io/node-npmtest-indicative/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-indicative/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-indicative/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-indicative/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-indicative/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-indicative/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-indicative/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "indicative",
    "version": "2.2.1",
    "description": "Intentionally beautiful schema and raw validator for nodejs",
    "main": "index.js",
    "scripts": {
        "test": "npm run lint && istanbul cover _mocha --report lcovonly -- -R spec test && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "coverage": "npm run lint && istanbul cover _mocha test --bail",
        "lint": "standard"
    },
    "author": "amanvirk",
    "license": "MIT",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "chai": "^3.5.0",
        "co-mocha": "^1.1.2",
        "coveralls": "^2.11.9",
        "cz-conventional-changelog": "^1.1.6",
        "istanbul": "^0.4.3",
        "mocha": "^3.0.2",
        "mocha-lcov-reporter": "^1.2.0",
        "standard": "^8.4.0"
    },
    "dependencies": {
        "inflect": "^0.3.0",
        "lodash": "^4.12.0",
        "moment": "^2.13.0",
        "pope": "^1.0.0",
        "q": "^2.0.3"
    },
    "standard": {
        "global": [
            "it",
            "describe",
            "context",
            "before",
            "after",
            "beforeEach",
            "afterEach"
        ]
    },
    "directories": {
        "doc": "docs",
        "test": "test"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/poppinss/indicative.git"
    },
    "keywords": [
        "node-validator",
        "validator",
        "schema-validator",
        "quick-validations"
    ],
    "bugs": {
        "url": "https://github.com/poppinss/indicative/issues"
    },
    "homepage": "https://github.com/poppinss/indicative#readme",
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
