# npmtest-sails-mongo

#### basic test coverage for  [sails-mongo (v0.12.2)](https://github.com/balderdashy/sails-mongo#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-mongo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-mongo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-mongo.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-mongo)

#### Mongo DB adapter for Sails.js

[![NPM](https://nodei.co/npm/sails-mongo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-mongo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-mongo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-mongo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-mongo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-mongo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-mongo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sails-mongo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sails-mongo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-mongo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-mongo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-mongo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-mongo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-mongo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-mongo/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-mongo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-mongo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-mongo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-mongo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-mongo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-mongo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-mongo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-mongo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/balderdashy/sails-mongo/issues"
    },
    "contributors": [
        {
            "name": "Cody Stoltman"
        },
        {
            "name": "Zolmeister"
        },
        {
            "name": "Robin Persson"
        },
        {
            "name": "Ted Kulp"
        },
        {
            "name": "Andy Pham"
        }
    ],
    "dependencies": {
        "@sailshq/lodash": "3.10.2",
        "async": "2.0.1",
        "mongodb": "2.1.20",
        "validator": "4.5.1",
        "waterline-cursor": "0.0.7",
        "waterline-errors": "0.10.1"
    },
    "description": "Mongo DB adapter for Sails.js",
    "devDependencies": {
        "captains-log": "^1.0.2",
        "mocha": "3.0.2",
        "waterline-adapter-tests": "~0.12.1"
    },
    "directories": {},
    "dist": {
        "shasum": "475b9e508d380f8787a0e6b1dfebbd607f4f66e3",
        "tarball": "https://registry.npmjs.org/sails-mongo/-/sails-mongo-0.12.2.tgz"
    },
    "gitHead": "feb4760daa65d238765bfa39f6be3cd8b1e6805d",
    "homepage": "https://github.com/balderdashy/sails-mongo#readme",
    "keywords": [
        "mongo",
        "mongodb",
        "orm",
        "waterline",
        "sails"
    ],
    "license": "MIT",
    "main": "./lib/adapter.js",
    "maintainers": [
        {
            "name": "balderdashy"
        },
        {
            "name": "mikermcneil"
        },
        {
            "name": "particlebanana"
        },
        {
            "name": "sgress454"
        },
        {
            "name": "tedkulp"
        }
    ],
    "name": "sails-mongo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/sails-mongo.git"
    },
    "scripts": {
        "docker": "docker-compose run adapter bash",
        "test": "make test"
    },
    "version": "0.12.2",
    "waterlineAdapter": {
        "waterlineVersion": "~0.10.0",
        "interfaces": [
            "semantic",
            "queryable",
            "associations"
        ],
        "features": [
            "cross-adapter"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
