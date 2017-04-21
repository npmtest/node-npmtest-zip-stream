# npmtest-zip-stream

#### basic test coverage for  [zip-stream (v1.1.1)](https://github.com/archiverjs/node-zip-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-zip-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zip-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zip-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-zip-stream)

#### a streaming zip archive generator.

[![NPM](https://nodei.co/npm/zip-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zip-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zip-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zip-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zip-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zip-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zip-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zip-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zip-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zip-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zip-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zip-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zip-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zip-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-zip-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zip-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zip-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zip-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zip-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zip-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zip-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zip-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zip-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "zip-stream",
    "version": "1.1.1",
    "description": "a streaming zip archive generator.",
    "homepage": "https://github.com/archiverjs/node-zip-stream",
    "author": {
        "name": "Chris Talkington",
        "url": "http://christalkington.com/"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/archiverjs/node-zip-stream.git"
    },
    "bugs": {
        "url": "https://github.com/archiverjs/node-zip-stream/issues"
    },
    "license": "MIT",
    "main": "index.js",
    "files": [
        "index.js"
    ],
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "mocha --reporter dot",
        "jsdoc": "jsdoc -c jsdoc.json README.md"
    },
    "dependencies": {
        "archiver-utils": "^1.3.0",
        "compress-commons": "^1.1.0",
        "lodash": "^4.8.0",
        "readable-stream": "^2.0.0"
    },
    "devDependencies": {
        "archiver-jsdoc-theme": "^1.0.0",
        "jsdoc": "~3.4.0",
        "chai": "^3.4.0",
        "minami": "^1.1.0",
        "mocha": "^3.2.0",
        "rimraf": "^2.4.3",
        "mkdirp": "^0.5.0"
    },
    "keywords": [
        "archive",
        "stream",
        "zip-stream",
        "zip"
    ],
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
