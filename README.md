# npmtest-stylus-loader

#### test coverage for  [stylus-loader (v3.0.1)](https://github.com/shama/stylus-loader#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-stylus-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-stylus-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-stylus-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-stylus-loader)

#### Stylus loader for webpack

[![NPM](https://nodei.co/npm/stylus-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/stylus-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-stylus-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylus-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-stylus-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-stylus-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-stylus-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-stylus-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-stylus-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-stylus-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-stylus-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-stylus-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-stylus-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-stylus-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-stylus-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-stylus-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-stylus-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylus-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-stylus-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-stylus-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kyle Robinson Young",
        "url": "http://dontkry.com"
    },
    "bugs": {
        "url": "https://github.com/shama/stylus-loader/issues"
    },
    "dependencies": {
        "loader-utils": "^1.0.2",
        "lodash.clonedeep": "^4.5.0",
        "when": "~3.6.x"
    },
    "description": "Stylus loader for webpack",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "css-loader": "^0.14.0",
        "mocha": "~2.1.0",
        "mocha-loader": "^1.0.0",
        "nib": "^1.0.4",
        "node-libs-browser": "^0.5.2",
        "raw-loader": "~0.5.1",
        "should": "~4.6.1",
        "style-loader": "^0.12.2",
        "stylus": ">=0.52.4",
        "testem": "^0.8.3",
        "webpack": "^2.2.0",
        "webpack-dev-server": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "77f4b34fd030d25b2617bcf5513db5b0730c4089",
        "tarball": "https://registry.npmjs.org/stylus-loader/-/stylus-loader-3.0.1.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "a2725db3827f7f41d350a079ffe215005a71b159",
    "homepage": "https://github.com/shama/stylus-loader#readme",
    "keywords": [
        "webpack",
        "loader",
        "stylus"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "shama"
        },
        {
            "name": "mzgoddard"
        }
    ],
    "name": "stylus-loader",
    "optionalDependencies": {},
    "peerDependencies": {
        "stylus": ">=0.52.4"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/shama/stylus-loader.git"
    },
    "scripts": {
        "test": "testem ci",
        "test-build": "webpack --config test/webpack.config.js --output-path=test/tmp --output-filename=bundle.js",
        "test-dev": "testem -l firefox",
        "test-one": "testem ci -l firefox"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
