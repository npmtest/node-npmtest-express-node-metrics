# npmtest-express-node-metrics

#### basic test coverage for  [express-node-metrics (v1.4.0)](https://github.com/idanto/node-metrics)  [![npm package](https://img.shields.io/npm/v/npmtest-express-node-metrics.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-node-metrics) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-node-metrics.svg)](https://travis-ci.org/npmtest/node-npmtest-express-node-metrics)

#### metrics for node+express application

[![NPM](https://nodei.co/npm/express-node-metrics.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-node-metrics)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-node-metrics/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-node-metrics/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-node-metrics/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-node-metrics/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-node-metrics/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-node-metrics/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-node-metrics/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-node-metrics/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-node-metrics/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-node-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-node-metrics/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-node-metrics/build/test-report.html](https://npmtest.github.io/node-npmtest-express-node-metrics/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-node-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-node-metrics/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-node-metrics/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-node-metrics/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-node-metrics/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-node-metrics/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-node-metrics/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-node-metrics/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-node-metrics",
    "version": "1.4.0",
    "description": "metrics for node+express application",
    "main": "index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/idanto/express-node-metrics.git"
    },
    "scripts": {
        "test": "./node_modules/.bin/istanbul cover node_modules/.bin/_mocha -- --recursive --reporter mochawesome",
        "test-travis": "./node_modules/.bin/istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --recursive --reporter spec --check-leaks test/",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/.bin/coveralls",
        "doctoc": "npm install -g doctoc && doctoc README.md"
    },
    "bugs": {
        "url": "https://github.com/idanto/node-metrics/issues"
    },
    "homepage": "https://github.com/idanto/node-metrics",
    "keywords": [
        "metrics",
        "node",
        "express",
        "restify"
    ],
    "author": "Idan Tovi",
    "license": "MIT",
    "devDependencies": {
        "chai": "^3.5.0",
        "connect": "^3.5.0",
        "coveralls": "^2.11.13",
        "express": "^4.14.0",
        "fs": "0.0.1-security",
        "istanbul": "^0.4.5",
        "js-yaml": "^3.7.0",
        "mocha": "^3.0.2",
        "mochawesome": "^1.5.2",
        "node-mocks-http": "^1.5.3",
        "request": "^2.79.0",
        "restify": "^4.3.0",
        "rewire": "^2.5.2",
        "sinon": "^1.17.5",
        "sleep": "^4.0.0",
        "swagger-tools": "^0.10.1"
    },
    "dependencies": {
        "event-loop-stats": "^1.0.0",
        "gc-stats": "^1.0.0",
        "measured": "^1.1.0",
        "memwatch-next": "^0.3.0",
        "node-schedule": "^1.1.1",
        "pidusage": "^1.0.7"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
