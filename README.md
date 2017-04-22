# npmdoc-utility2

#### api documentation for  [utility2 (v2017.4.17)](https://github.com/kaizhu256/node-utility2)  [![npm package](https://img.shields.io/npm/v/npmdoc-utility2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-utility2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-utility2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-utility2)

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
    "gitHead": "26185c7f46ead93a1e7e37c3889f019c7a2050eb",
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
        "postinstall": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh postinstall",
        "start": "set -e; export PORT=${PORT:-8080}; if [ -f assets.app.js ]; then node assets.app.js; else npm_config_mode_auto_restart=1 ./lib.utility2.sh shRun shIstanbulCover test.js; fi",
        "test": "PORT=$(./lib.utility2.sh shServerPortRandom) PORT_REPL=$(./lib.utility2.sh shServerPortRandom) npm_config_mode_auto_restart=1 ./lib.utility2.sh test test.js"
    },
    "version": "2017.4.17"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
