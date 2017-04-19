# npmtest-cssstats

#### basic test coverage for  [cssstats (v3.0.0)](https://github.com/cssstats/cssstats-core#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cssstats.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cssstats) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cssstats.svg)](https://travis-ci.org/npmtest/node-npmtest-cssstats)

#### High-level stats for stylesheets

[![NPM](https://nodei.co/npm/cssstats.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cssstats)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cssstats/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssstats/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cssstats/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cssstats/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cssstats/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cssstats/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cssstats/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cssstats/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cssstats/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cssstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cssstats/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cssstats/build/test-report.html](https://npmtest.github.io/node-npmtest-cssstats/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cssstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cssstats/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cssstats/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cssstats/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cssstats/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cssstats/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cssstats/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cssstats/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brent Jackson"
    },
    "bugs": {
        "url": "https://github.com/cssstats/cssstats-core/issues"
    },
    "dependencies": {
        "bytes": "^2.4.0",
        "css-selector-tokenizer": "^0.7.0",
        "css-shorthand-expand": "^1.1.0",
        "gzip-size": "^3.0.0",
        "has-class-selector": "1.0.0",
        "has-element-selector": "^1.0.0",
        "has-id-selector": "1.0.0",
        "has-pseudo-class": "1.0.1",
        "has-pseudo-element": "1.0.0",
        "is-blank": "^1.1.0",
        "is-css-shorthand": "^1.0.1",
        "is-present": "^1.0.0",
        "is-vendor-prefixed": "0.0.1",
        "lodash": "^4.16.6",
        "postcss": "^5.2.5",
        "postcss-safe-parser": "^2.0.0",
        "specificity": "^0.3.0"
    },
    "description": "High-level stats for stylesheets",
    "devDependencies": {
        "get-css": "1.2.1",
        "mocha": "^3.1.2",
        "standard": "^8.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3be9fce31d07960da34649c0c151bb48e9c1e31e",
        "tarball": "https://registry.npmjs.org/cssstats/-/cssstats-3.0.0.tgz"
    },
    "gitHead": "72370f57b3431d67974e5a2406f97b29a536e86a",
    "homepage": "https://github.com/cssstats/cssstats-core#readme",
    "keywords": [
        "CSS",
        "Performance",
        "Stats",
        "cssstats"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jxnblk"
        },
        {
            "name": "johno"
        }
    ],
    "name": "cssstats",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cssstats/cssstats-core.git"
    },
    "scripts": {
        "lint": "standard",
        "test": "npm run lint && rm -rf test/results && mkdir test/results && mocha test"
    },
    "standard": {
        "global": [
            "before",
            "describe",
            "it"
        ]
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
