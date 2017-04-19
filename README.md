# npmdoc-node-expat

#### api documentation for  [node-expat (v2.3.15)](http://github.com/astro/node-expat)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-expat.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-expat) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-expat.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-expat)

#### NodeJS binding for fast XML parsing.

[![NPM](https://nodei.co/npm/node-expat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-expat)

- [https://npmdoc.github.io/node-npmdoc-node-expat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-expat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-expat/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Astro",
        "url": "http://spaceboyz.net/~astro/"
    },
    "bugs": {
        "url": "https://github.com/astro/node-expat/issues"
    },
    "contributors": [
        {
            "name": "Stephan Maka"
        },
        {
            "name": "Derek Hammer"
        },
        {
            "name": "Iein Valdez"
        },
        {
            "name": "Peter Körner"
        },
        {
            "name": "Camilo Aguilar"
        },
        {
            "name": "Michael Weibel"
        },
        {
            "name": "Alexey Zhuchkov"
        },
        {
            "name": "Satyam Shekhar"
        },
        {
            "name": "Dhruv Matani"
        },
        {
            "name": "Andreas Botsikas"
        },
        {
            "name": "Tom Hughes-Croucher"
        },
        {
            "name": "Nathan Rajlich"
        },
        {
            "name": "Julien Genestoux"
        },
        {
            "name": "Sonny Piers"
        },
        {
            "name": "Lloyd Watkin"
        },
        {
            "name": "AJ ONeal"
        },
        {
            "name": "Rod Vagg"
        },
        {
            "name": "Christoph Hartmann"
        },
        {
            "name": "Corbin Uselton"
        },
        {
            "name": "Julian Duque"
        },
        {
            "name": "Lovell Fuller"
        },
        {
            "name": "Antonio Bustos"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.5"
    },
    "description": "NodeJS binding for fast XML parsing.",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "debug": "^2.2.0",
        "iconv": "^2.2.0",
        "libxmljs": "^0.18.0",
        "ltx": "^2.3.0",
        "node-xml": "^1.0.2",
        "sax": "^1.2.1",
        "standard": "^7.1.2",
        "vows": "^0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "96a53a0bc00649daf78f4fc074a23e644c223b4c",
        "tarball": "https://registry.npmjs.org/node-expat/-/node-expat-2.3.15.tgz"
    },
    "gitHead": "b062e57b79ffbcf4d8c0f9b1606eb39dc991123d",
    "gypfile": true,
    "homepage": "http://github.com/astro/node-expat",
    "keywords": [
        "xml",
        "sax",
        "expat",
        "libexpat",
        "parse",
        "parsing"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT"
        }
    ],
    "main": "./lib/node-expat",
    "maintainers": [
        {
            "name": "astro"
        },
        {
            "name": "lloydwatkin"
        },
        {
            "name": "chris-rock"
        },
        {
            "name": "sonny"
        }
    ],
    "name": "node-expat",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/astro/node-expat.git"
    },
    "scripts": {
        "benchmark": "node ./benchmark.js",
        "install": "node-gyp rebuild",
        "lint": "standard",
        "preversion": "npm test",
        "test": "npm run unit && npm run lint",
        "unit": "vows --spec ./test/**/*.js"
    },
    "version": "2.3.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
