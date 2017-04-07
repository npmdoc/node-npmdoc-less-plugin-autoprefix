# api documentation for  [less-plugin-autoprefix (v1.5.1)](http://lesscss.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-less-plugin-autoprefix.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-less-plugin-autoprefix) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-less-plugin-autoprefix.svg)](https://travis-ci.org/npmdoc/node-npmdoc-less-plugin-autoprefix)
#### autoprefixer plugin for less.js

[![NPM](https://nodei.co/npm/less-plugin-autoprefix.png?downloads=true)](https://www.npmjs.com/package/less-plugin-autoprefix)

[![apidoc](https://npmdoc.github.io/node-npmdoc-less-plugin-autoprefix/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-less-plugin-autoprefix_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-less-plugin-autoprefix/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-less-plugin-autoprefix/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-less-plugin-autoprefix/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Luke Page"
    },
    "bugs": {
        "url": "https://github.com/less/less-plugin-autoprefix/issues"
    },
    "contributors": [
        {
            "name": "The Core Less Team"
        }
    ],
    "dependencies": {
        "autoprefixer": "^6.0.0",
        "postcss": "^5.0.0"
    },
    "description": "autoprefixer plugin for less.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "bca4e5b2e48cac6965a1783142e3b32c3c00ce07",
        "tarball": "https://registry.npmjs.org/less-plugin-autoprefix/-/less-plugin-autoprefix-1.5.1.tgz"
    },
    "engines": {
        "node": ">=0.4.2"
    },
    "gitHead": "84979643ebd595af2077db894d4f9462b360f0b1",
    "homepage": "http://lesscss.org",
    "keywords": [
        "less plugins",
        "autoprefixer",
        "less prefixes"
    ],
    "licenses": [
        {
            "type": "Apache v2",
            "url": "https://github.com/less/less-plugin-autoprefix/blob/master/LICENSE"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "agatronic",
            "email": "luke.a.page@gmail.com"
        }
    ],
    "name": "less-plugin-autoprefix",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/less/less-plugin-autoprefix.git"
    },
    "scripts": {},
    "version": "1.5.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module less-plugin-autoprefix](#apidoc.module.less-plugin-autoprefix)
1.  object <span class="apidocSignatureSpan">less-plugin-autoprefix.</span>usage

#### [module less-plugin-autoprefix.usage](#apidoc.module.less-plugin-autoprefix.usage)
1.  [function <span class="apidocSignatureSpan">less-plugin-autoprefix.usage.</span>printUsage ()](#apidoc.element.less-plugin-autoprefix.usage.printUsage)



# <a name="apidoc.module.less-plugin-autoprefix"></a>[module less-plugin-autoprefix](#apidoc.module.less-plugin-autoprefix)



# <a name="apidoc.module.less-plugin-autoprefix.usage"></a>[module less-plugin-autoprefix.usage](#apidoc.module.less-plugin-autoprefix.usage)

#### <a name="apidoc.element.less-plugin-autoprefix.usage.printUsage"></a>[function <span class="apidocSignatureSpan">less-plugin-autoprefix.usage.</span>printUsage ()](#apidoc.element.less-plugin-autoprefix.usage.printUsage)
- description and source-code
```javascript
printUsage = function () {
    console.log("");
    console.log("Autoprefixer Plugin");
    console.log("specify plugin with --autoprefix");
    console.log("The argument is the browser option as specified by autoprefixer e.g.");
    console.log("--autoprefix=\"IE 7,> 1%\"");
    console.log("");
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
