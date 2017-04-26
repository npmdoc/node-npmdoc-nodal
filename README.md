# npmdoc-nodal

#### basic api documentation for  [nodal (v0.13.4)](https://github.com/keithwhor/nodal)  [![npm package](https://img.shields.io/npm/v/npmdoc-nodal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nodal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nodal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nodal)

#### An API Server and Framework for node.js

[![NPM](https://nodei.co/npm/nodal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodal)

- [https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nodal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nodal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Keith Horwood"
    },
    "bin": {
        "nodal": "cli/bin.js"
    },
    "bugs": {
        "url": "https://github.com/keithwhor/nodal/issues"
    },
    "dependencies": {
        "api-res": "~0.0.4",
        "async": "~1.5.2",
        "cmnd": "~0.1.0",
        "colors": "~1.1.0",
        "cross-spawn-async": "~2.1.6",
        "deep-equal": "~1.0.1",
        "dot": "~1.0.3",
        "dotenv": "^2.0.0",
        "fs-extra": "~0.26.4",
        "fxn": "~0.0.5",
        "i": "~0.3.4",
        "inquirer": "~0.11.3",
        "mime-types": "~2.1.9",
        "pg": "~4.5.5"
    },
    "description": "An API Server and Framework for node.js",
    "devDependencies": {
        "chai": "~3.5.0",
        "mocha": "~2.4.5"
    },
    "directories": {},
    "dist": {
        "shasum": "94275f4bbffa5d97a3509962d4366d4b530525a8",
        "tarball": "https://registry.npmjs.org/nodal/-/nodal-0.13.4.tgz"
    },
    "gitHead": "386fe2b89acd817cfc54b4de19cba9f2a9273184",
    "homepage": "https://github.com/keithwhor/nodal",
    "keywords": [
        "framework",
        "api",
        "application",
        "branding",
        "server",
        "modular",
        "nodal"
    ],
    "license": "MIT",
    "main": "core/module.js",
    "maintainers": [
        {
            "name": "keithwhor"
        }
    ],
    "name": "nodal",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/keithwhor/nodal.git"
    },
    "scripts": {
        "docs": "documentation build core/module.js -o docs -f html",
        "test": "mocha ./test/runner.js"
    },
    "version": "0.13.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
