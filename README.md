# npmdoc-svg2png

#### api documentation for  [svg2png (v4.1.1)](https://github.com/domenic/svg2png#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-svg2png.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-svg2png) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-svg2png.svg)](https://travis-ci.org/npmdoc/node-npmdoc-svg2png)

#### Converts SVGs to PNGs, using PhantomJS

[![NPM](https://nodei.co/npm/svg2png.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg2png)

- [https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg2png/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg2png/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-svg2png/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-svg2png/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Domenic Denicola",
        "url": "https://domenic.me"
    },
    "bin": {
        "svg2png": "bin/svg2png-cli.js"
    },
    "bugs": {
        "url": "https://github.com/domenic/svg2png/issues"
    },
    "dependencies": {
        "file-url": "^2.0.0",
        "phantomjs-prebuilt": "^2.1.14",
        "pn": "^1.0.0",
        "yargs": "^6.5.0"
    },
    "description": "Converts SVGs to PNGs, using PhantomJS",
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "eslint": "^3.12.2",
        "mkdirp": "^0.5.1",
        "mocha": "^3.2.0",
        "rimraf": "^2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "6b9e0398aa418778b6436e127a2fb7f00d499c28",
        "tarball": "https://registry.npmjs.org/svg2png/-/svg2png-4.1.1.tgz"
    },
    "files": [
        "lib/",
        "bin/"
    ],
    "gitHead": "5997ae9452796f480c13506c32cb04d1dc38369e",
    "homepage": "https://github.com/domenic/svg2png#readme",
    "license": "WTFPL",
    "main": "lib/svg2png.js",
    "maintainers": [
        {
            "name": "domenic"
        }
    ],
    "name": "svg2png",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/domenic/svg2png.git"
    },
    "scripts": {
        "lint": "eslint lib test",
        "rebaseline": "node test/success-tests/rebaseline.js",
        "test": "mocha"
    },
    "version": "4.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
