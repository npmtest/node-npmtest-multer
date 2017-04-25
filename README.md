# npmtest-multer

#### basic test coverage for  [multer (v1.3.0)](https://github.com/expressjs/multer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-multer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-multer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-multer.svg)](https://travis-ci.org/npmtest/node-npmtest-multer)

#### Middleware for handling `multipart/form-data`.

[![NPM](https://nodei.co/npm/multer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/multer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-multer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-multer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-multer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-multer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-multer/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-multer/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-multer/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-multer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-multer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-multer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-multer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-multer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-multer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-multer/build/test-report.html](https://npmtest.github.io/node-npmtest-multer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-multer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-multer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-multer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-multer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-multer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-multer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-multer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-multer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/multer/issues"
    },
    "contributors": [
        {
            "name": "Hage Yaapa",
            "url": "http://www.hacksparrow.com"
        },
        {
            "name": "Jaret Pfluger"
        },
        {
            "name": "Linus Unnebäck"
        }
    ],
    "dependencies": {
        "append-field": "^0.1.0",
        "busboy": "^0.2.11",
        "concat-stream": "^1.5.0",
        "mkdirp": "^0.5.1",
        "object-assign": "^3.0.0",
        "on-finished": "^2.3.0",
        "type-is": "^1.6.4",
        "xtend": "^4.0.0"
    },
    "description": "Middleware for handling 'multipart/form-data'.",
    "devDependencies": {
        "express": "^4.13.1",
        "form-data": "^1.0.0-rc1",
        "fs-temp": "^0.1.2",
        "mocha": "^2.2.5",
        "rimraf": "^2.4.1",
        "standard": "^8.2.0",
        "testdata-w3c-json-form": "^0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "092b2670f6846fa4914965efc8cf94c20fec6cd2",
        "tarball": "https://registry.npmjs.org/multer/-/multer-1.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "LICENSE",
        "index.js",
        "storage/",
        "lib/"
    ],
    "gitHead": "7ef2e81215e9b773204df44fb4aee29e58340061",
    "homepage": "https://github.com/expressjs/multer#readme",
    "keywords": [
        "form",
        "post",
        "multipart",
        "form-data",
        "formdata",
        "express",
        "middleware"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "hacksparrow"
        },
        {
            "name": "linusu"
        },
        {
            "name": "jpfluger"
        }
    ],
    "name": "multer",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/multer.git"
    },
    "scripts": {
        "test": "standard && mocha"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
