# npmtest-lodash-cli

#### basic test coverage for  [lodash-cli (v4.17.4)](https://lodash.com/custom-builds)  [![npm package](https://img.shields.io/npm/v/npmtest-lodash-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lodash-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lodash-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-lodash-cli)

#### The Lodash command-line interface.

[![NPM](https://nodei.co/npm/lodash-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lodash-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lodash-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lodash-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lodash-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lodash-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lodash-cli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lodash-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lodash-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lodash-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lodash-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lodash-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lodash-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lodash-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-lodash-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lodash-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lodash-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lodash-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lodash-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lodash-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lodash-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lodash-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lodash-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John-David Dalton",
        "url": "http://allyoucanleet.com/"
    },
    "bin": {
        "lodash": "bin/lodash"
    },
    "bugs": {
        "url": "https://github.com/lodash/lodash-cli/issues"
    },
    "contributors": [
        {
            "name": "John-David Dalton",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {
        "closure-compiler": "0.2.12",
        "glob": "7.1.1",
        "lodash": "4.17.4",
        "semver": "5.3.0",
        "uglify-js": "2.7.5"
    },
    "description": "The Lodash command-line interface.",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-preset-env": "^1.1.4",
        "qunit-extras": "^3.0.0",
        "qunitjs": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "23b727cd0e91e28484fafda1521900a8a811df81",
        "tarball": "https://registry.npmjs.org/lodash-cli/-/lodash-cli-4.17.4.tgz"
    },
    "files": [
        "bin",
        "lib",
        "template",
        "npm-shrinkwrap.json"
    ],
    "greenkeeper": {
        "ignore": [
            "lodash"
        ]
    },
    "homepage": "https://lodash.com/custom-builds",
    "keywords": [
        "builder",
        "compile",
        "customize",
        "lodash"
    ],
    "license": "MIT",
    "main": "bin/lodash",
    "maintainers": [
        {
            "name": "jdalton"
        },
        {
            "name": "mathias"
        }
    ],
    "name": "lodash-cli",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/lodash-cli.git"
    },
    "scripts": {
        "test": "node test"
    },
    "version": "4.17.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
