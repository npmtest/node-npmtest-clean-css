# npmtest-clean-css

#### basic test coverage for  [clean-css (v4.0.12)](https://github.com/jakubpawlowicz/clean-css)  [![npm package](https://img.shields.io/npm/v/npmtest-clean-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clean-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clean-css.svg)](https://travis-ci.org/npmtest/node-npmtest-clean-css)

#### A well-tested CSS minifier

[![NPM](https://nodei.co/npm/clean-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clean-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clean-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clean-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clean-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-clean-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clean-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clean-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clean-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jakub Pawlowicz",
        "url": "http://twitter.com/jakubpawlowicz"
    },
    "bugs": {
        "url": "https://github.com/jakubpawlowicz/clean-css/issues"
    },
    "dependencies": {
        "source-map": "0.5.x"
    },
    "description": "A well-tested CSS minifier",
    "devDependencies": {
        "browserify": "13.x",
        "http-proxy": "1.x",
        "jshint": "2.x",
        "nock": "9.x",
        "server-destroy": "1.x",
        "uglify-js": ">=2.6.1",
        "vows": "0.8.x"
    },
    "directories": {},
    "dist": {
        "shasum": "a02e61707f1840bd3338f54dbc9acbda4e772fa3",
        "tarball": "https://registry.npmjs.org/clean-css/-/clean-css-4.0.12.tgz"
    },
    "engines": {
        "node": ">= 4.0"
    },
    "files": [
        "lib",
        "History.md",
        "index.js",
        "LICENSE"
    ],
    "gitHead": "72a00b7b1f42822e1b843b9f6fc1029bdb02d3e3",
    "homepage": "https://github.com/jakubpawlowicz/clean-css",
    "keywords": [
        "css",
        "minifier"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "goalsmashers"
        },
        {
            "name": "jakub.pawlowicz"
        }
    ],
    "name": "clean-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jakubpawlowicz/clean-css.git"
    },
    "scripts": {
        "bench": "node ./test/bench.js",
        "browserify": "browserify --standalone CleanCSS index.js | uglifyjs --compress --mangle -o cleancss-browser.js",
        "check": "jshint .",
        "prepublish": "npm run check",
        "test": "vows"
    },
    "version": "4.0.12"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
