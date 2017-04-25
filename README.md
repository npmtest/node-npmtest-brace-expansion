# npmtest-brace-expansion

#### basic test coverage for  [brace-expansion (v1.1.7)](https://github.com/juliangruber/brace-expansion)  [![npm package](https://img.shields.io/npm/v/npmtest-brace-expansion.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-brace-expansion) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-brace-expansion.svg)](https://travis-ci.org/npmtest/node-npmtest-brace-expansion)

#### Brace expansion as known from sh/bash

[![NPM](https://nodei.co/npm/brace-expansion.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/brace-expansion)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-brace-expansion/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-brace-expansion/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-brace-expansion/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-brace-expansion/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-brace-expansion/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-brace-expansion/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-brace-expansion/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-brace-expansion/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-brace-expansion/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-brace-expansion/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-brace-expansion/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-brace-expansion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-brace-expansion/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-brace-expansion/build/test-report.html](https://npmtest.github.io/node-npmtest-brace-expansion/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-brace-expansion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-brace-expansion/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-brace-expansion/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-brace-expansion/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brace-expansion/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brace-expansion/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-brace-expansion/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-brace-expansion/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Julian Gruber",
        "url": "http://juliangruber.com"
    },
    "bugs": {
        "url": "https://github.com/juliangruber/brace-expansion/issues"
    },
    "dependencies": {
        "balanced-match": "^0.4.1",
        "concat-map": "0.0.1"
    },
    "description": "Brace expansion as known from sh/bash",
    "devDependencies": {
        "matcha": "^0.7.0",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3effc3c50e000531fb720eaff80f0ae8ef23cf59",
        "tarball": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.7.tgz"
    },
    "gitHead": "892512024872ca7680554be90f6e8ce065053372",
    "homepage": "https://github.com/juliangruber/brace-expansion",
    "keywords": [],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "juliangruber"
        },
        {
            "name": "isaacs"
        }
    ],
    "name": "brace-expansion",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/juliangruber/brace-expansion.git"
    },
    "scripts": {
        "bench": "matcha test/perf/bench.js",
        "gentest": "bash test/generate.sh",
        "test": "tape test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": [
            "ie/8..latest",
            "firefox/20..latest",
            "firefox/nightly",
            "chrome/25..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "1.1.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
