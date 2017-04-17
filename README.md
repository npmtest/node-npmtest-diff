# test coverage for  [diff (v3.2.0)](https://github.com/kpdecker/jsdiff#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-diff.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-diff) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-diff.svg)](https://travis-ci.org/npmtest/node-npmtest-diff)
#### A javascript text diff implementation.

[![NPM](https://nodei.co/npm/diff.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/diff)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-diff/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-diff/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-diff/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-diff/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-diff/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-diff/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-diff/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-diff/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-diff/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-diff/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-diff/build/test-report.html](https://npmtest.github.io/node-npmtest-diff/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-diff/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-diff/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-diff/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-diff/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-diff/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-diff/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-diff/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "babel": {
        "sourceMaps": "inline",
        "presets": [
            "es3",
            "es2015-mod"
        ],
        "auxiliaryCommentBefore": "istanbul ignore start",
        "auxiliaryCommentAfter": "istanbul ignore end"
    },
    "bugs": {
        "url": "http://github.com/kpdecker/jsdiff/issues"
    },
    "dependencies": {},
    "description": "A javascript text diff implementation.",
    "devDependencies": {
        "async": "^1.4.2",
        "babel-core": "^6.0.0",
        "babel-loader": "^6.0.0",
        "babel-preset-es2015-mod": "^6.3.13",
        "babel-preset-es3": "^1.0.1",
        "chai": "^3.3.0",
        "colors": "^1.1.2",
        "eslint": "^1.6.0",
        "grunt": "^0.4.5",
        "grunt-babel": "^6.0.0",
        "grunt-clean": "^0.4.0",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-eslint": "^17.3.1",
        "grunt-karma": "^0.12.1",
        "grunt-mocha-istanbul": "^3.0.1",
        "grunt-mocha-test": "^0.12.7",
        "grunt-webpack": "^1.0.11",
        "istanbul": "github:kpdecker/istanbul",
        "karma": "^0.13.11",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^2.0.0",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-sauce-launcher": "^0.3.0",
        "karma-sourcemap-loader": "^0.3.6",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.3.3",
        "phantomjs-prebuilt": "^2.1.5",
        "semver": "^5.0.3",
        "webpack": "^1.12.2",
        "webpack-dev-server": "^1.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c9ce393a4b7cbd0b058a725c93df299027868ff9",
        "tarball": "https://registry.npmjs.org/diff/-/diff-3.2.0.tgz"
    },
    "engines": {
        "node": ">=0.3.1"
    },
    "gitHead": "becde77e9f7aa31944480cf2a335815cd44d2d12",
    "homepage": "https://github.com/kpdecker/jsdiff#readme",
    "keywords": [
        "diff",
        "javascript"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib",
    "maintainers": [
        {
            "name": "kpdecker"
        }
    ],
    "name": "diff",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kpdecker/jsdiff.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
