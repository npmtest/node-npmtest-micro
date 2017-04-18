# npmtest-micro

#### test coverage for  [micro (v7.3.2)](https://github.com/zeit/micro#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-micro.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-micro) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-micro.svg)](https://travis-ci.org/npmtest/node-npmtest-micro)

#### Asynchronous HTTP microservices

[![NPM](https://nodei.co/npm/micro.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/micro)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-micro/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-micro/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-micro/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-micro/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-micro/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-micro/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-micro/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-micro/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-micro/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-micro/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-micro/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-micro/build/test-report.html](https://npmtest.github.io/node-npmtest-micro/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-micro/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-micro/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-micro/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-micro/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-micro/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-micro/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-micro/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-micro/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zeit, Inc."
    },
    "bin": {
        "micro": "./bin/micro.js"
    },
    "bugs": {
        "url": "https://github.com/zeit/micro/issues"
    },
    "dependencies": {
        "args": "2.6.0",
        "async-to-gen": "1.3.2",
        "bluebird": "3.5.0",
        "boxen": "1.0.0",
        "chalk": "1.1.3",
        "clipboardy": "1.1.0",
        "get-port": "3.1.0",
        "ip": "1.1.5",
        "is-async-supported": "1.2.0",
        "isstream": "0.1.2",
        "media-typer": "0.3.0",
        "node-version": "1.0.0",
        "raw-body": "2.2.0",
        "update-notifier": "2.1.0"
    },
    "description": "Asynchronous HTTP microservices",
    "devDependencies": {
        "ava": "0.19.1",
        "coveralls": "2.13.0",
        "eslint-config-prettier": "1.6.0",
        "husky": "0.13.3",
        "lint-staged": "3.4.0",
        "nyc": "10.2.0",
        "prettier": "0.22.0",
        "request": "2.81.0",
        "request-promise": "4.2.0",
        "resumer": "0.0.0",
        "test-listen": "1.0.2",
        "then-sleep": "1.0.1",
        "xo": "0.18.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c6ff82fad6b045cfe04cbc673834ef1fc3dc13aa",
        "tarball": "https://registry.npmjs.org/micro/-/micro-7.3.2.tgz"
    },
    "files": [
        "bin",
        "lib"
    ],
    "gitHead": "cdd49c8725c0a06ff1870c51d526af6f3826bbc0",
    "homepage": "https://github.com/zeit/micro#readme",
    "keywords": [
        "micro",
        "service",
        "microservice",
        "serverless",
        "API"
    ],
    "license": "MIT",
    "lint-staged": {
        "*.js": [
            "npm run lint",
            "prettier --single-quote --write",
            "git add"
        ]
    },
    "main": "./lib/server.js",
    "maintainers": [
        {
            "name": "leo"
        },
        {
            "name": "rauchg"
        }
    ],
    "name": "micro",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeit/micro.git"
    },
    "scripts": {
        "lint": "xo",
        "precommit": "lint-staged",
        "test": "npm run lint && NODE_ENV=test nyc ava"
    },
    "version": "7.3.2",
    "xo": {
        "ignores": [
            "examples/**/*"
        ],
        "extends": "prettier"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
