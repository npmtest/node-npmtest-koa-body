# npmtest-koa-body

#### basic test coverage for  koa-body (v1.6.0)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-body.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-body) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-body.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-body)

#### A koa body parser middleware. Support multipart, urlencoded and json request bodies.

[![NPM](https://nodei.co/npm/koa-body.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-body)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-body/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-body/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-body/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-body/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-body/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-body/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-body/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-body/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-body/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-body/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-body/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-body/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-body/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-body/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-body/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-body/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-body/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-body/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-body/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-body",
    "version": "1.6.0",
    "description": "A koa body parser middleware. Support multipart, urlencoded and json request bodies.",
    "main": "index.js",
    "scripts": {
        "test": "node_modules/.bin/mocha --harmony",
        "examples-multer": "node --harmony examples/multer.js",
        "examples-koa-router": "node --harmony examples/koa-router.js"
    },
    "author": {
        "name": "Daryl Lau",
        "url": "https://github.com/dlau"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/dlau/koa-body.git"
    },
    "keywords": [
        "koa",
        "urlencoded",
        "multipart",
        "json",
        "body",
        "parser",
        "form"
    ],
    "files": [
        ".gitignore",
        ".npmignore",
        ".travis.yml",
        "LICENSE",
        "Makefile",
        "README.md",
        "example.js",
        "index.js",
        "test.js"
    ],
    "dependencies": {
        "co-body": "*",
        "extend": "1.3.0",
        "formidable": "1.0.17"
    },
    "devDependencies": {
        "koa": "*",
        "koa-resource-router": "*",
        "koa-router": "*",
        "lodash": "^3.3.1",
        "mocha": "*",
        "multiline": "*",
        "should": "*",
        "supertest": "2.0.0"
    },
    "contributors": [
        {
            "name": "Daryl Lau",
            "url": "https://github.com/dlau"
        },
        {
            "name": "Charlike Mike Reagent",
            "url": "https://github.com/tunnckoCore"
        }
    ],
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
