# api documentation for  [node-expat (v2.3.15)](http://github.com/astro/node-expat)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-expat.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-expat) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-expat.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-expat)
#### NodeJS binding for fast XML parsing.

[![NPM](https://nodei.co/npm/node-expat.png?downloads=true)](https://www.npmjs.com/package/node-expat)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-expat_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-expat/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-expat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Astro",
        "email": "astro@spaceboyz.net",
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
            "name": "astro",
            "email": "astro@spaceboyz.net"
        },
        {
            "name": "lloydwatkin",
            "email": "lloyd@evilprofessor.co.uk"
        },
        {
            "name": "chris-rock",
            "email": "chris@lollyrock.com"
        },
        {
            "name": "sonny",
            "email": "sonny@fastmail.net"
        }
    ],
    "name": "node-expat",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-expat](#apidoc.module.node-expat)
1.  [function <span class="apidocSignatureSpan">node-expat.</span>Parser (encoding)](#apidoc.element.node-expat.Parser)
1.  [function <span class="apidocSignatureSpan">node-expat.</span>createParser (cb)](#apidoc.element.node-expat.createParser)
1.  object <span class="apidocSignatureSpan">node-expat.</span>Parser.prototype

#### [module node-expat.Parser](#apidoc.module.node-expat.Parser)
1.  [function <span class="apidocSignatureSpan">node-expat.</span>Parser (encoding)](#apidoc.element.node-expat.Parser.Parser)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.</span>super_ ()](#apidoc.element.node-expat.Parser.super_)

#### [module node-expat.Parser.prototype](#apidoc.module.node-expat.Parser.prototype)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>_getNewParser ()](#apidoc.element.node-expat.Parser.prototype._getNewParser)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>destroy ()](#apidoc.element.node-expat.Parser.prototype.destroy)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>destroySoon ()](#apidoc.element.node-expat.Parser.prototype.destroySoon)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>end (data)](#apidoc.element.node-expat.Parser.prototype.end)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentByteIndex ()](#apidoc.element.node-expat.Parser.prototype.getCurrentByteIndex)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentColumnNumber ()](#apidoc.element.node-expat.Parser.prototype.getCurrentColumnNumber)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentLineNumber ()](#apidoc.element.node-expat.Parser.prototype.getCurrentLineNumber)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getError ()](#apidoc.element.node-expat.Parser.prototype.getError)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>parse (buf, isFinal)](#apidoc.element.node-expat.Parser.prototype.parse)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>pause ()](#apidoc.element.node-expat.Parser.prototype.pause)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>reset ()](#apidoc.element.node-expat.Parser.prototype.reset)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>resume ()](#apidoc.element.node-expat.Parser.prototype.resume)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>setEncoding (encoding)](#apidoc.element.node-expat.Parser.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>setUnknownEncoding (map, convert)](#apidoc.element.node-expat.Parser.prototype.setUnknownEncoding)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>stop ()](#apidoc.element.node-expat.Parser.prototype.stop)
1.  [function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>write (data)](#apidoc.element.node-expat.Parser.prototype.write)



# <a name="apidoc.module.node-expat"></a>[module node-expat](#apidoc.module.node-expat)

#### <a name="apidoc.element.node-expat.Parser"></a>[function <span class="apidocSignatureSpan">node-expat.</span>Parser (encoding)](#apidoc.element.node-expat.Parser)
- description and source-code
```javascript
Parser = function (encoding) {
  this.encoding = encoding
  this._getNewParser()
  this.parser.emit = this.emit.bind(this)

  // Stream API
  this.writable = true
  this.readable = true
}
```
- example usage
```shell
...
Important events emitted by a parser:

'''javascript
(function () {
"use strict";

var expat = require('node-expat')
var parser = new expat.Parser('UTF-8')

parser.on('startElement', function (name, attrs) {
  console.log(name, attrs)
})

parser.on('endElement', function (name) {
  console.log(name)
...
```

#### <a name="apidoc.element.node-expat.createParser"></a>[function <span class="apidocSignatureSpan">node-expat.</span>createParser (cb)](#apidoc.element.node-expat.createParser)
- description and source-code
```javascript
createParser = function (cb) {
  var parser = new Parser()
  if (cb) {
    parser.on('startElement', cb)
  }
  return parser
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-expat.Parser"></a>[module node-expat.Parser](#apidoc.module.node-expat.Parser)

#### <a name="apidoc.element.node-expat.Parser.Parser"></a>[function <span class="apidocSignatureSpan">node-expat.</span>Parser (encoding)](#apidoc.element.node-expat.Parser.Parser)
- description and source-code
```javascript
Parser = function (encoding) {
  this.encoding = encoding
  this._getNewParser()
  this.parser.emit = this.emit.bind(this)

  // Stream API
  this.writable = true
  this.readable = true
}
```
- example usage
```shell
...
Important events emitted by a parser:

'''javascript
(function () {
"use strict";

var expat = require('node-expat')
var parser = new expat.Parser('UTF-8')

parser.on('startElement', function (name, attrs) {
  console.log(name, attrs)
})

parser.on('endElement', function (name) {
  console.log(name)
...
```

#### <a name="apidoc.element.node-expat.Parser.super_"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.</span>super_ ()](#apidoc.element.node-expat.Parser.super_)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-expat.Parser.prototype"></a>[module node-expat.Parser.prototype](#apidoc.module.node-expat.Parser.prototype)

#### <a name="apidoc.element.node-expat.Parser.prototype._getNewParser"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>_getNewParser ()](#apidoc.element.node-expat.Parser.prototype._getNewParser)
- description and source-code
```javascript
_getNewParser = function () {
  this.parser = new expat.Parser(this.encoding)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.destroy"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>destroy ()](#apidoc.element.node-expat.Parser.prototype.destroy)
- description and source-code
```javascript
destroy = function () {
  this.parser.stop()
  this.end()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.destroySoon"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>destroySoon ()](#apidoc.element.node-expat.Parser.prototype.destroySoon)
- description and source-code
```javascript
destroySoon = function () {
  this.destroy()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.end"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>end (data)](#apidoc.element.node-expat.Parser.prototype.end)
- description and source-code
```javascript
end = function (data) {
  var error, result
  try {
    result = this.parse(data || '', true)
    if (!result) {
      error = this.getError()
    }
  } catch (e) {
    error = e
  }

  if (!error) {
    this.emit('end')
  } else {
    this.emit('error', error)
  }
  this.emit('close')
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.getCurrentByteIndex"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentByteIndex ()](#apidoc.element.node-expat.Parser.prototype.getCurrentByteIndex)
- description and source-code
```javascript
getCurrentByteIndex = function () {
  return this.parser.getCurrentByteIndex()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.getCurrentColumnNumber"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentColumnNumber ()](#apidoc.element.node-expat.Parser.prototype.getCurrentColumnNumber)
- description and source-code
```javascript
getCurrentColumnNumber = function () {
  return this.parser.getCurrentColumnNumber()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.getCurrentLineNumber"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getCurrentLineNumber ()](#apidoc.element.node-expat.Parser.prototype.getCurrentLineNumber)
- description and source-code
```javascript
getCurrentLineNumber = function () {
  return this.parser.getCurrentLineNumber()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.getError"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>getError ()](#apidoc.element.node-expat.Parser.prototype.getError)
- description and source-code
```javascript
getError = function () {
  return this.parser.getError()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.parse"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>parse (buf, isFinal)](#apidoc.element.node-expat.Parser.prototype.parse)
- description and source-code
```javascript
parse = function (buf, isFinal) {
  return this.parser.parse(buf, isFinal)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.pause"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>pause ()](#apidoc.element.node-expat.Parser.prototype.pause)
- description and source-code
```javascript
pause = function () {
  return this.stop()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.reset"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>reset ()](#apidoc.element.node-expat.Parser.prototype.reset)
- description and source-code
```javascript
reset = function () {
  return this.parser.reset()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.resume"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>resume ()](#apidoc.element.node-expat.Parser.prototype.resume)
- description and source-code
```javascript
resume = function () {
  return this.parser.resume()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>setEncoding (encoding)](#apidoc.element.node-expat.Parser.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function (encoding) {
  this.encoding = encoding
  return this.parser.setEncoding(this.encoding)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.setUnknownEncoding"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>setUnknownEncoding (map, convert)](#apidoc.element.node-expat.Parser.prototype.setUnknownEncoding)
- description and source-code
```javascript
setUnknownEncoding = function (map, convert) {
  return this.parser.setUnknownEncoding(map, convert)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.stop"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>stop ()](#apidoc.element.node-expat.Parser.prototype.stop)
- description and source-code
```javascript
stop = function () {
  return this.parser.stop()
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-expat.Parser.prototype.write"></a>[function <span class="apidocSignatureSpan">node-expat.Parser.prototype.</span>write (data)](#apidoc.element.node-expat.Parser.prototype.write)
- description and source-code
```javascript
write = function (data) {
  var error, result
  try {
    result = this.parse(data)
    if (!result) {
      error = this.getError()
    }
  } catch (e) {
    error = e
  }
  if (error) {
    this.emit('error', error)
    this.emit('close')
  }
  return result
}
```
- example usage
```shell
...
    console.log(text)
  })

  parser.on('error', function (error) {
    console.error(error)
  })

  parser.write('<html><head><title>Hello World</title></head><body><p>Foobar</p></body></html>')

}())

'''

## API
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
