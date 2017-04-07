# api documentation for  [npm-stats (v1.2.0)](https://github.com/hughsk/npm-stats#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-stats.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-stats) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-stats.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-stats)
#### Convenience module for getting back data from an NPM registry

[![NPM](https://nodei.co/npm/npm-stats.png?downloads=true)](https://www.npmjs.com/package/npm-stats)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-stats/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-npm-stats_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-stats/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-stats/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-stats/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugh Kennedy",
        "email": "hughskennedy@gmail.com",
        "url": "http://hughskennedy.com/"
    },
    "bugs": {
        "url": "https://github.com/hughsk/npm-stats/issues"
    },
    "dependencies": {
        "JSONStream": "~0.6.2",
        "event-stream": "~3.0.12",
        "lodash.merge": "~3.3.2",
        "nano": "^6.2.0",
        "request": "~2.45.0",
        "stream-reduce": "~1.0.3",
        "through": "~2.3.6"
    },
    "description": "Convenience module for getting back data from an NPM registry",
    "devDependencies": {
        "chai": "^3.5.0",
        "tap": "^5.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "e4f5dc78f5c64b8da50e8fcbba70351eb6c2875e",
        "tarball": "https://registry.npmjs.org/npm-stats/-/npm-stats-1.2.0.tgz"
    },
    "gitHead": "5949bd1ec2e01b842af0564682212ee55fef6a07",
    "homepage": "https://github.com/hughsk/npm-stats#readme",
    "keywords": [
        "modules",
        "npm",
        "data",
        "information",
        "analytics",
        "statistics",
        "stats",
        "users",
        "keywords"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bcoe",
            "email": "ben@npmjs.com"
        },
        {
            "name": "dsc",
            "email": "dsc@less.ly"
        },
        {
            "name": "hughsk",
            "email": "hughskennedy@gmail.com"
        },
        {
            "name": "zeke",
            "email": "zeke@sikelianos.com"
        }
    ],
    "name": "npm-stats",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/hughsk/npm-stats.git"
    },
    "scripts": {
        "test": "tap --coverage ./test.js"
    },
    "version": "1.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module npm-stats](#apidoc.module.npm-stats)
1.  [function <span class="apidocSignatureSpan">npm-stats.</span>defaults (defaults)](#apidoc.element.npm-stats.defaults)



# <a name="apidoc.module.npm-stats"></a>[module npm-stats](#apidoc.module.npm-stats)

#### <a name="apidoc.element.npm-stats.defaults"></a>[function <span class="apidocSignatureSpan">npm-stats.</span>defaults (defaults)](#apidoc.element.npm-stats.defaults)
- description and source-code
```javascript
defaults = function (defaults){
  return merge(GLOBAL_DEFAULTS, defaults)
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
