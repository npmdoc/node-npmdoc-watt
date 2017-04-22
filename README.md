# npmdoc-watt

#### api documentation for  watt (v3.3.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-watt.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-watt) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-watt.svg)](https://travis-ci.org/npmdoc/node-npmdoc-watt)

#### Powerful generator control flow

[![NPM](https://nodei.co/npm/watt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/watt)

- [https://npmdoc.github.io/node-npmdoc-watt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-watt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-watt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-watt/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-watt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-watt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Bell"
    },
    "dependencies": {
        "setimmediate": "^1.0.4"
    },
    "description": "Powerful generator control flow",
    "devDependencies": {
        "standard": "^7.0.0",
        "tap": "^5.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "c8463c408d1b4878702a53d21b84676aaa6c0136",
        "tarball": "https://registry.npmjs.org/watt/-/watt-3.3.0.tgz"
    },
    "gitHead": "5b783130b9e5d41b41713b3357ecc6f582f3ed0a",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mappum"
        }
    ],
    "name": "watt",
    "optionalDependencies": {},
    "scripts": {
        "test": "standard && tap test.js --cov",
        "test-lcov": "mkdir -p coverage && tap test/*.js -Rsilent --coverage-report=text-lcov > coverage/lcov.info",
        "test-tap": "tap test/*.js -Rtap"
    },
    "version": "3.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
