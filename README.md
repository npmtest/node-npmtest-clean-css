# test coverage for  [clean-css (v4.0.11)](https://github.com/jakubpawlowicz/clean-css)  [![npm package](https://img.shields.io/npm/v/npmtest-clean-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-clean-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-clean-css.svg)](https://travis-ci.org/npmtest/node-npmtest-clean-css)
#### A well-tested CSS minifier

[![NPM](https://nodei.co/npm/clean-css.png?downloads=true)](https://www.npmjs.com/package/clean-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-clean-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-clean-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-clean-css/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-clean-css/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-clean-css%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-clean-css/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clean-css/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-clean-css%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clean-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-clean-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jakub Pawlowicz",
        "email": "contact@jakubpawlowicz.com",
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
        "shasum": "a6d88bffb399420b24298db49d99a1ed067534a8",
        "tarball": "https://registry.npmjs.org/clean-css/-/clean-css-4.0.11.tgz"
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
    "gitHead": "9a912c899aeb10169ccad486bfa1b1441b1e084d",
    "homepage": "https://github.com/jakubpawlowicz/clean-css",
    "keywords": [
        "css",
        "minifier"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "goalsmashers",
            "email": "jakub@goalsmashers.com"
        },
        {
            "name": "jakub.pawlowicz",
            "email": "contact@jakubpawlowicz.com"
        }
    ],
    "name": "clean-css",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "4.0.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
