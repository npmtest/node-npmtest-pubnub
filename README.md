# npmtest-pubnub

#### basic test coverage for  [pubnub (v4.8.0)](https://github.com/pubnub/javascript#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pubnub.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pubnub) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pubnub.svg)](https://travis-ci.org/npmtest/node-npmtest-pubnub)

#### Publish & Subscribe Real-time Messaging with PubNub

[![NPM](https://nodei.co/npm/pubnub.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pubnub)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pubnub/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pubnub/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pubnub/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pubnub/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pubnub/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pubnub/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pubnub/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pubnub/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pubnub/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pubnub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pubnub/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pubnub/build/test-report.html](https://npmtest.github.io/node-npmtest-pubnub/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pubnub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pubnub/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pubnub/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pubnub/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pubnub/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pubnub/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pubnub/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pubnub/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "PubNub"
    },
    "bin": {},
    "browser": "./dist/web/pubnub.min.js",
    "bugs": {
        "url": "https://github.com/pubnub/javascript/issues"
    },
    "bundleDependencies": [],
    "dependencies": {
        "agentkeepalive": "^3.1.0",
        "superagent": "^2.3.0",
        "superagent-proxy": "^1.0.2",
        "uuid": "^3.0.1"
    },
    "description": "Publish & Subscribe Real-time Messaging with PubNub",
    "devDependencies": {
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-class-properties": "^6.22.0",
        "babel-plugin-transform-flow-strip-types": "^6.22.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-register": "^6.22.0",
        "eslint-config-airbnb": "^14.0.0",
        "eslint-plugin-flowtype": "^2.30.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-mocha": "^4.8.0",
        "eslint-plugin-react": "^6.9.0",
        "flow-bin": "^0.39.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-clean": "^0.3.2",
        "gulp-eslint": "^3.0.1",
        "gulp-exec": "^2.1.3",
        "gulp-flowtype": "^1.0.0",
        "gulp-gzip": "^1.4.0",
        "gulp-istanbul": "^1.1.1",
        "gulp-mocha": "^3.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^2.4.0",
        "gulp-uglify": "^2.0.1",
        "gulp-unzip": "^0.2.0",
        "imports-loader": "^0.7.0",
        "isparta": "^4.0.0",
        "js-yaml": "^3.7.0",
        "json-loader": "^0.5.4",
        "karma": "^1.4.0",
        "karma-babel-preprocessor": "^6.0.1",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sinon-chai": "^1.2.4",
        "karma-spec-reporter": "^0.0.26",
        "mocha": "^3.2.0",
        "nock": "^9.0.2",
        "phantomjs-prebuilt": "^2.1.14",
        "run-sequence": "^1.2.2",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0",
        "stats-webpack-plugin": "^0.4.3",
        "uglify-js": "^2.7.5",
        "underscore": "^1.8.3",
        "webpack": "^1.14.0",
        "webpack-dev-server": "^1.16.2",
        "webpack-stream": "^3.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "033c7202faba1f765233b036ecafa3084ec36f23",
        "tarball": "https://registry.npmjs.org/pubnub/-/pubnub-4.8.0.tgz"
    },
    "engine": {
        "node": ">=0.8"
    },
    "gitHead": "455dddc285663d1f488f948104c80179a00e6789",
    "homepage": "https://github.com/pubnub/javascript#readme",
    "keywords": [
        "cloud",
        "publish",
        "subscribe",
        "websockets",
        "comet",
        "bosh",
        "xmpp",
        "real-time",
        "messaging"
    ],
    "license": "MIT",
    "main": "./lib/node/index.js",
    "maintainers": [
        {
            "name": "maxpresman"
        },
        {
            "name": "pubnub"
        },
        {
            "name": "pubnub1"
        },
        {
            "name": "stephenlb"
        }
    ],
    "name": "pubnub",
    "noAnalyze": false,
    "optionalDependencies": {},
    "react-native": "./lib/react_native/index.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/pubnub/javascript.git"
    },
    "scripts": {
        "codecov": "cat coverage/lcov.info | codecov"
    },
    "version": "4.8.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
