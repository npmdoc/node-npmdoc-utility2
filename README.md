# api documentation for  [utility2 (v2017.4.16)](https://github.com/kaizhu256/node-utility2)  [![npm package](https://img.shields.io/npm/v/npmdoc-utility2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-utility2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-utility2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-utility2)
#### the zero-dependency, swiss-army-knife utility for building, testing, and deploying webapps

[![NPM](https://nodei.co/npm/utility2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/utility2)

- [https://npmdoc.github.io/node-npmdoc-utility2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-utility2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-utility2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-utility2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-utility2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-utility2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "kai zhu"
    },
    "bin": {
        "utility2": "lib.utility2.sh",
        "utility2-apidoc": "lib.apidoc.js",
        "utility2-github-crud": "lib.github_crud.js",
        "utility2-istanbul": "lib.istanbul.js",
        "utility2-jslint": "lib.jslint.js",
        "utility2-uglifyjs": "lib.uglifyjs.js"
    },
    "bugs": {
        "url": "https://github.com/kaizhu256/node-utility2/issues"
    },
    "dependencies": {},
    "description": "the zero-dependency, swiss-army-knife utility for building, testing, and deploying webapps",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "78997891c1e7bf707e8bc53fd040aeb4ad3650a7",
    "homepage": "https://github.com/kaizhu256/node-utility2",
    "keywords": [
        "build",
        "ci",
        "code-coverage",
        "continuous-integration",
        "deploy",
        "devops",
        "electron",
        "headless-browser",
        "istanbul",
        "jscoverage",
        "phantomjs",
        "slimerjs",
        "test",
        "test-coverage",
        "travis",
        "travis-ci"
    ],
    "license": "MIT",
    "main": "lib.utility2.js",
    "name": "utility2",
    "nameAlias": "utility2",
    "nameAliasPublish": "npmtest-lite npmtest4 test-lite",
    "nameOriginal": "utility2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "readmeFilename": "README.md",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kaizhu256/node-utility2.git"
    },
    "scripts": {
        "build-ci": "./lib.utility2.sh shReadmeTest build_ci.sh",
        "env": "env",
        "heroku-postbuild": "./lib.utility2.sh shDeployHeroku",
        "postinstall": "if [ -f npm_scripts.sh ]; then ./npm_scripts.sh postinstall; fi",
        "start": "(set -e; export PORT=${PORT:-8080}; if [ -f assets.app.js ]; then node assets.app.js; exit; fi; export npm_config_mode_auto_restart=1; ./lib.utility2.sh shRun shIstanbulCover test.js)",
        "test": "(set -e; export PORT=$(./lib.utility2.sh shServerPortRandom); export PORT_REPL=$(./lib.utility2.sh shServerPortRandom); export npm_config_mode_auto_restart=1; ./lib.utility2.sh test test.js)"
    },
    "version": "2017.4.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
