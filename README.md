# test coverage for  [backbone (v1.3.3)](https://github.com/jashkenas/backbone#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-backbone.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-backbone) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-backbone.svg)](https://travis-ci.org/npmtest/node-npmtest-backbone)
#### Give your JS App some Backbone with Models, Views, Collections, and Events.

[![NPM](https://nodei.co/npm/backbone.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/backbone)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-backbone/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-backbone/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-backbone/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-backbone/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-backbone/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-backbone/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-backbone/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-backbone/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-backbone/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-backbone/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-backbone/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-backbone/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeremy Ashkenas"
    },
    "bugs": {
        "url": "https://github.com/jashkenas/backbone/issues"
    },
    "dependencies": {
        "underscore": ">=1.8.3"
    },
    "description": "Give your JS App some Backbone with Models, Views, Collections, and Events.",
    "devDependencies": {
        "coffee-script": "1.7.1",
        "docco": "0.7.0",
        "eslint": "1.10.x",
        "karma": "^0.13.13",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-qunit": "^0.1.5",
        "qunitjs": "^1.18.0",
        "uglify-js": "^2.4.17"
    },
    "directories": {},
    "dist": {
        "shasum": "4cc80ea7cb1631ac474889ce40f2f8bc683b2999",
        "tarball": "https://registry.npmjs.org/backbone/-/backbone-1.3.3.tgz"
    },
    "files": [
        "backbone.js",
        "backbone-min.js",
        "backbone-min.map",
        "LICENSE"
    ],
    "gitHead": "8ec88604732944f197b352a6be22c8216ea9d3a1",
    "homepage": "https://github.com/jashkenas/backbone#readme",
    "keywords": [
        "model",
        "view",
        "controller",
        "router",
        "server",
        "client",
        "browser"
    ],
    "license": "MIT",
    "main": "backbone.js",
    "maintainers": [
        {
            "name": "braddunbar"
        },
        {
            "name": "jashkenas"
        },
        {
            "name": "jridgewell"
        }
    ],
    "name": "backbone",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jashkenas/backbone.git"
    },
    "scripts": {
        "build": "uglifyjs backbone.js --mangle --source-map backbone-min.map -o backbone-min.js",
        "doc": "docco backbone.js && docco examples/todos/todos.js examples/backbone.localStorage.js",
        "lint": "eslint backbone.js test/*.js",
        "test": "karma start && coffee test/model.coffee && npm run lint"
    },
    "url": "http://backbonejs.org",
    "version": "1.3.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
