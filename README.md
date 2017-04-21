# npmtest-jscodeshift

#### basic test coverage for  [jscodeshift (v0.3.30)](https://github.com/facebook/jscodeshift#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jscodeshift.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jscodeshift) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jscodeshift.svg)](https://travis-ci.org/npmtest/node-npmtest-jscodeshift)

#### A toolkit for JavaScript codemods

[![NPM](https://nodei.co/npm/jscodeshift.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jscodeshift)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jscodeshift/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscodeshift/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jscodeshift/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jscodeshift/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jscodeshift/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jscodeshift/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jscodeshift/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jscodeshift/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jscodeshift/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscodeshift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jscodeshift/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jscodeshift/build/test-report.html](https://npmtest.github.io/node-npmtest-jscodeshift/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jscodeshift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jscodeshift/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jscodeshift/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jscodeshift/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jscodeshift/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jscodeshift/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jscodeshift/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jscodeshift/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Kling"
    },
    "bin": {
        "jscodeshift": "./bin/jscodeshift.sh"
    },
    "bugs": {
        "url": "https://github.com/facebook/jscodeshift/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "babel-core": "^5",
        "babel-plugin-transform-flow-strip-types": "^6.8.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-register": "^6.9.0",
        "babylon": "^6.8.1",
        "colors": "^1.1.2",
        "es6-promise": "^3.0.0",
        "flow-parser": "^0.*",
        "lodash": "^4.13.1",
        "micromatch": "^2.3.7",
        "node-dir": "0.1.8",
        "nomnom": "^1.8.1",
        "recast": "^0.11.11",
        "temp": "^0.8.1",
        "write-file-atomic": "^1.2.0"
    },
    "description": "A toolkit for JavaScript codemods",
    "devDependencies": {
        "babel-eslint": "^6.1.2",
        "eslint": "^3.1.1",
        "jest": "^15.1.1",
        "jsdoc": "^3.4.0",
        "mkdirp": "^0.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "73f459d8fc3b3a80841991aeb7d24809cef6dfc5",
        "tarball": "https://registry.npmjs.org/jscodeshift/-/jscodeshift-0.3.30.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "eb9a30ba2e39d6324a9af698862677ce182e848a",
    "homepage": "https://github.com/facebook/jscodeshift#readme",
    "jest": {
        "testPathDirs": [
            "src",
            "bin",
            "sample"
        ]
    },
    "keywords": [
        "codemod",
        "recast"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fkling"
        }
    ],
    "name": "jscodeshift",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/jscodeshift.git"
    },
    "scripts": {
        "build": "cp -R src/ dist/",
        "docs": "rm -rf docs && jsdoc -d docs -R README.md src/collections/* src/core.js src/Collection.js",
        "prepublish": "npm run build && npm run test",
        "test": "jest --bail"
    },
    "version": "0.3.30"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
