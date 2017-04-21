# npmdoc-gulp-msbuild

#### api documentation for  [gulp-msbuild (v0.4.7)](https://github.com/hoffi/gulp-msbuild#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-msbuild.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-msbuild) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-msbuild.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-msbuild)

#### msbuild plugin for gulp. Inspired by grunt-msbuild.

[![NPM](https://nodei.co/npm/gulp-msbuild.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-msbuild)

- [https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-msbuild/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Hoffmann",
        "url": "https://github.com/hoffi"
    },
    "bugs": {
        "url": "https://github.com/hoffi/gulp-msbuild/issues"
    },
    "dependencies": {
        "didyoumean": "~1.2.1",
        "gulp-util": ">=3.0.0",
        "lodash": "^4.0.0",
        "through2": "^2.0.0"
    },
    "description": "msbuild plugin for gulp. Inspired by grunt-msbuild.",
    "devDependencies": {
        "chai": "^3.4.0",
        "coveralls": "*",
        "istanbul": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "mocha-sinon": "^1.1.6",
        "sinon": ">=1.4.0 <2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6cb14c2e5b4e3b0b1fcc5e84f917eb22beff26de",
        "tarball": "https://registry.npmjs.org/gulp-msbuild/-/gulp-msbuild-0.4.7.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "a549abc15849266756de03e0f144c17e67a60101",
    "homepage": "https://github.com/hoffi/gulp-msbuild#readme",
    "keywords": [
        "gulpplugin",
        "msbuild",
        "xbuild"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "h0ff1"
        }
    ],
    "name": "gulp-msbuild",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hoffi/gulp-msbuild.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "istanbul test ./node_modules/mocha/bin/_mocha --report html -- test/*.js --reporter spec"
    },
    "version": "0.4.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
