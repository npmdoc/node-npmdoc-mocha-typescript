# npmdoc-mocha-typescript

#### api documentation for  mocha-typescript (v1.0.23)  [![npm package](https://img.shields.io/npm/v/npmdoc-mocha-typescript.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mocha-typescript) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mocha-typescript.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mocha-typescript)

#### TypeScript decorators based wrapper over mocha's interface

[![NPM](https://nodei.co/npm/mocha-typescript.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha-typescript)

- [https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mocha-typescript/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mocha-typescript",
    "version": "1.0.23",
    "description": "TypeScript decorators based wrapper over mocha's interface",
    "main": "index.js",
    "typings": "index.d.ts",
    "repository": {
        "type": "git",
        "url": "https://github.com/PanayotCankov/mocha-typescript"
    },
    "bin": {
        "mocha-typescript-watch": "./bin/watch.js"
    },
    "scripts": {
        "pretest": "tsc",
        "test": "mocha test.js --opts mocha.opts",
        "prepublish": "tsc"
    },
    "author": "Panayot Cankov",
    "license": "Apache-2.0",
    "dependencies": {
        "chalk": "^1.1.3",
        "yargs": "^6.5.0"
    },
    "devDependencies": {
        "@types/mocha": "^2.2.39",
        "@types/node": "^7.0.5",
        "assert": "^1.3.0",
        "better-assert": "^1.0.2",
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "typescript": "^2.2.1"
    },
    "files": [
        "index.js",
        "index.d.ts",
        "bin/watch.js"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
