# npmtest-text-miner

#### basic test coverage for  [text-miner (v1.0.5)](https://github.com/Planeshifter/text-miner#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-text-miner.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-text-miner) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-text-miner.svg)](https://travis-ci.org/npmtest/node-npmtest-text-miner)

#### text mining utilities

[![NPM](https://nodei.co/npm/text-miner.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/text-miner)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-text-miner/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-text-miner/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-text-miner/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-text-miner/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-text-miner/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-text-miner/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-text-miner/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-text-miner/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-text-miner/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-text-miner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-text-miner/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-text-miner/build/test-report.html](https://npmtest.github.io/node-npmtest-text-miner/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-text-miner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-text-miner/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-text-miner/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-text-miner/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-text-miner/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-text-miner/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-text-miner/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-text-miner/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Philipp Burckhardt"
    },
    "bugs": {
        "url": "https://github.com/Planeshifter/text-miner/issues"
    },
    "dependencies": {
        "natural": "~0.2.1",
        "underscore": "~1.8.2",
        "underscore.string": "^3.2.2"
    },
    "description": "text mining utilities",
    "devDependencies": {
        "chai": "3.x.x",
        "chai-as-promised": "^5.0.0",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.8",
        "jshint": "^2.6.3",
        "jshint-stylish": "2.x.x",
        "mocha": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "079e08973b24225368dd016eac69562c74617c5c",
        "tarball": "https://registry.npmjs.org/text-miner/-/text-miner-1.0.5.tgz"
    },
    "gitHead": "7db9d93a1faaa01edb267fc7c611f47d1e0e053a",
    "homepage": "https://github.com/Planeshifter/text-miner#readme",
    "keywords": [
        "text-mining",
        "text-analytics",
        "document-term-matrix",
        "dtm",
        "text-analysis"
    ],
    "license": "MIT",
    "main": "src/text-miner.js",
    "maintainers": [
        {
            "name": "planeshifter"
        }
    ],
    "name": "text-miner",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Planeshifter/text-miner.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/.bin/_mocha --dir ./reports/coveralls/coverage --report lcovonly -- -R spec && cat ./reports/coveralls/coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./reports/coveralls",
        "test": "mocha",
        "test-cov": "istanbul cover ./node_modules/.bin/_mocha --dir ./reports/coverage -- -R spec"
    },
    "version": "1.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
