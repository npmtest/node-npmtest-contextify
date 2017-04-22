# npmtest-contextify

#### basic test coverage for  [contextify (v0.1.15)](https://github.com/brianmcd/contextify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-contextify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-contextify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-contextify.svg)](https://travis-ci.org/npmtest/node-npmtest-contextify)

#### Turn an object into a persistent execution context.

[![NPM](https://nodei.co/npm/contextify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/contextify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-contextify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-contextify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-contextify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-contextify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-contextify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-contextify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-contextify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-contextify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-contextify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-contextify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-contextify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-contextify/build/test-report.html](https://npmtest.github.io/node-npmtest-contextify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-contextify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-contextify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-contextify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-contextify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-contextify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-contextify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-contextify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-contextify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian McDaniel"
    },
    "bugs": {
        "url": "https://github.com/brianmcd/contextify/issues"
    },
    "contributors": [
        {
            "name": "Assaf Arkin",
            "url": "http://labnotes.org/"
        },
        {
            "name": "Benjamin Byholm",
            "url": "https://research.it.abo.fi/people/bbyholm"
        },
        {
            "name": "Marshall Roch"
        },
        {
            "name": "Nathan Rajlich",
            "url": "http://n8.io"
        },
        {
            "name": "Paul Tan",
            "url": "https://github.com/pyokagan"
        },
        {
            "name": "Jeremy Stashewsky"
        },
        {
            "name": "Rex Morgan",
            "url": "http://www.rexflex.net/"
        },
        {
            "name": "Tom Gallacher",
            "url": "http://tomg.co"
        },
        {
            "name": "Kevin Decker",
            "url": "http://www.incaseofstairs.com"
        },
        {
            "name": "Sergei Ianovich",
            "url": "https://github.com/yanovich"
        },
        {
            "name": "Andrew Paprocki",
            "url": "https://github.com/apaprocki"
        },
        {
            "name": "Trygve Lie",
            "url": "https://github.com/trygve-lie"
        },
        {
            "name": "Ido Ben-Yair",
            "url": "https://github.com/idoby"
        },
        {
            "name": "Rod Vagg",
            "url": "https://r.va.gg/"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.1.0"
    },
    "description": "Turn an object into a persistent execution context.",
    "devDependencies": {
        "nodeunit": ">=0.5.x"
    },
    "directories": {},
    "dist": {
        "shasum": "3d34681d14a5ccbbe609c9ee11eda206b8cf266f",
        "tarball": "https://registry.npmjs.org/contextify/-/contextify-0.1.15.tgz"
    },
    "engines": {
        "node": ">=0.10.11"
    },
    "gitHead": "8929cf6150033bf5e811be5f5c0f385ce960c821",
    "gypfile": true,
    "homepage": "https://github.com/brianmcd/contextify#readme",
    "keywords": [
        "context",
        "vm"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/brianmcd/contextify/blob/master/LICENSE.txt"
        }
    ],
    "main": "./lib/contextify",
    "maintainers": [
        {
            "name": "brianmcd"
        }
    ],
    "name": "contextify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/brianmcd/contextify.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "nodeunit test/"
    },
    "version": "0.1.15",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
