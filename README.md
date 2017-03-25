# api documentation for  [utility2 (v2017.3.22)](https://github.com/kaizhu256/node-utility2)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-utility2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-utility2)
#### the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps

[![NPM](https://nodei.co/npm/utility2.png?downloads=true)](https://www.npmjs.com/package/utility2)

[![apidoc](https://npmdoc.github.io/node-npmdoc-utility2/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-utility2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-utility2/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-utility2/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "kai zhu",
        "email": "kaizhu256@gmail.com"
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
    "description": "the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "8e163e40289f10711d7ccf0d5758e02fc7fa5776",
    "homepage": "https://github.com/kaizhu256/node-utility2",
    "keywords": [
        "browser",
        "build",
        "busybox",
        "ci",
        "code-coverage",
        "continuous-integration",
        "deploy",
        "docker",
        "electron",
        "headless-browser",
        "istanbul",
        "jscover",
        "jscoverage",
        "phantomjs",
        "slimerjs",
        "swiss-army-knife",
        "test",
        "test-coverage",
        "travis",
        "travis-ci",
        "utility2",
        "webapp"
    ],
    "license": "MIT",
    "main": "lib.utility2.js",
    "name": "utility2",
    "nameAlias": "utility2",
    "nameAliasPublish": "busybox npmtest-lite test-lite",
    "nameOriginal": "utility2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "readme": "# utility2\nthe zero-dependency swiss-army-knife tool for building, testing, and deploying webapps\n\n[![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-utility2.svg)](https://travis-ci.org/kaizhu256/node-utility2) [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build/coverage.html/index.html)\n\n[![NPM](https://nodei.co/npm/utility2.png?downloads=true)](https://www.npmjs.com/package/utility2)\n\n[![package-listing](https://kaizhu256.github.io/node-utility2/build/screen-capture.npmPackageListing.svg)](https://github.com/kaizhu256/node-utility2)\n\n\n\n# cdn download\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/assets.utility2.rollup.js](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/assets.utility2.rollup.js)\n\n\n\n# live demo\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html)\n\n[![github.com test-server](https://kaizhu256.github.io/node-utility2/build/screen-capture.deployGithub.browser._2Fnode-utility2_2Fbuild_2Fapp_2Findex.html.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html)\n\n\n\n# documentation\n#### apidoc\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html)\n\n[![apidoc](https://kaizhu256.github.io/node-utility2/build/screen-capture.buildApidoc.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html)\n\n#### todo\n- npm publish 2017.3.22\n- add function to remotely update .travis.yml\n- query failed travis-ci builds\n- rename sub-package db-lite -> nedb-lite\n- rename sub-package istanbul-lite -> istanbul-classic\n- rename sub-package jslint-lite -> jslint-classic\n- use optional remote-credentials during travis-ci build\n- allow server-side stdout to be streamed to webapps\n- add utility2.middlewareLimit\n- add server stress test using electron\n- analytics\n- none\n\n#### changes for v2017.3.22\n- add shell-function shGitRemotePromote to auto-promote branches alpha -> beta -> master\n- deprecate ssh-key in favor of github oauth - https://stackoverflow.com/questions/18027115/committing-via-travis-ci-failing\n- enable shNpmdocRepoListCreate in travis-ci\n- enhance shell-function shNpmPackageListingCreate to add total package-size to package-listing\n- fix apidoc bug 'Function.prototype.toString is not generic'\n- fix shell-function shInit bug - export: npm_package_react-native: bad variable name\n- none\n\n#### this package requires\n- darwin or linux os\n\n\n\n# build status [![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-utility2.svg)](https://travis-ci.org/kaizhu256/node-utility2)\n[![build commit status](https://kaizhu256.github.io/node-utility2/build/build.badge.svg)](https://travis-ci.org/kaizhu256/node-utility2)\n\n| git-branch : | [master](https://github.com/kaizhu256/node-utility2/tree/master) | [beta](https://github.com/kaizhu256/node-utility2/tree/beta) | [alpha](https://github.com/kaizhu256/node-utility2/tree/alpha)|\n|--:|:--|:--|:--|\n| test-server-github : | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/app/index.html) | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html) | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/app/index.html)|\n| test-server-heroku : | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-master.herokuapp.com) | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-beta.herokuapp.com) | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-alpha.herokuapp.com)|\n| test-report : | [![test-report](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/test-report.html)|\n| coverage : | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/coverage.html/index.html) | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/coverage.html/index.html) | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/coverage.html/index.html)|\n| build-artifacts : | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..master..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..beta..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..alpha..travis-ci.org)|\n\n#### master branch\n- stable branch\n- HEAD should be tagged, npm-published package\n\n#### beta branch\n- semi-stable branch\n- HEAD should be latest, npm-published package\n\n#### alpha branch\n- unstable branch\n- HEAD is arbitrary\n- commit history may be rewritten\n\n\n\n# quickstart interactive example\n#### to run this example, follow the instruction in the script below\n- [example.sh](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/example.sh)\n'''shell\n# example.sh\n\n# this shell script will serve a webpage that will interactively run browser-tests with coverage\n\n# instruction\n    # 1. copy and paste this entire shell script into a console and press enter\n    # 2. play with the browser-demo on http://127.0.0.1:8081\n\nshExampleSh() {(set -e\n    # npm install utility2\n    npm install \"kaizhu256/node-utility2#alpha\"\n    # serve a webpage that will interactively run browser-tests with coverage\n    cd node_modules/utility2 && export PORT=8081 && npm start\n)}\nshExampleSh\n'''\n\n#### output from browser\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleSh.browser..png)\n\n#### output from shell\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleSh.svg)\n\n\n\n# quickstart automated example\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Ftest-report.html.png)\n\n#### to run this example, follow the instruction in the script below\n- [example.js](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/example.js)\n'''javascript\n/*\nexample.js\n\nthis script will demo automated browser-tests with coverage (via electron and istanbul)\n\ninstruction\n    1. save this script as example.js\n    2. run the shell command:\n        $ npm install electron-lite \"kaizhu256/node-utility2#alpha\" && \\\n            PATH=\"$(pwd)/node_modules/.bin:$PATH\" \\\n            PORT=8081 \\\n            npm_config_mode_coverage=utility2 \\\n            node_modules/.bin/utility2 test example.js\n    3. view test-report in ./tmp/build/test-report.html\n    4. view coverage in ./tmp/build/coverage.html/index.html\n*/\n\n\n\n/* istanbul instrument in package utility2 */\n/*jslint\n    bitwise: true,\n    browser: true,\n    maxerr: 8,\n    maxlen: 96,\n    node: true,\n    nomen: true,\n    regexp: true,\n    stupid: true\n*/\n(function () {\n    'use strict';\n    var local;\n\n\n\n    // run shared js-env code - pre-init\n    (function () {\n        // init local\n        local = {};\n        // init modeJs\n        local.modeJs = (function () {\n            try {\n                return typeof navigator.userAgent === 'string' &&\n                    typeof document.querySelector('body') === 'object' &&\n                    typeof XMLHttpRequest.prototype.open === 'function' &&\n                    'browser';\n            } catch (errorCaughtBrowser) {\n                return module.exports &&\n                    typeof process.versions.node === 'string' &&\n                    typeof require('http').createServer === 'function' &&\n                    'node';\n            }\n        }());\n        // init global\n        local.global = local.modeJs === 'browser'\n            ? window\n            : global;\n        // init utility2_rollup\n        local = local.global.utility2_rollup || (local.modeJs === 'browser'\n            ? window.utility2\n            : require('utility2'));\n        // export local\n        local.global.local = local;\n        // run test-server\n        local.testRunServer(local);\n        // init assets\n        local.assetsDict['/assets.hello'] = 'hello';\n    }());\n    switch (local.modeJs) {\n\n\n\n    // run browser js-env code - function\n    case 'browser':\n        local.testCase_ajax_200 = function (options, onError) {\n        /*\n         * this function will test ajax's \"200 ok\" handling-behavior\n         */\n            options = {};\n            // test ajax-path 'assets.hello'\n            local.ajax({ url: 'assets.hello' }, function (error, xhr) {\n                local.tryCatchOnError(function () {\n                    // validate no error occurred\n                    local.assert(!error, error);\n                    // validate data\n                    options.data = xhr.responseText;\n                    local.assert(options.data === 'hello', options.data);\n                    onError();\n                }, onError);\n            });\n        };\n        local.testCase_ajax_404 = function (options, onError) {\n        /*\n         * this function will test ajax's \"404 not found\" handling-behavior\n         */\n            options = {};\n            // test ajax-path '/undefined'\n            local.ajax({ url: '/undefined' }, function (error) {\n                local.tryCatchOnError(function () {\n                    // validate error occurred\n                    local.assert(error, error);\n                    options.statusCode = error.statusCode;\n                    // validate 404 http statusCode\n                    local.assert(options.statusCode === 404, options.statusCode);\n                    onError();\n                }, onError);\n            });\n        };\n        break;\n\n\n\n    // run node js-env code - function\n    case 'node':\n        local.testCase_webpage_default = function (options, onError) {\n        /*\n         * this function will test webpage's default handling-behavior\n         */\n            options = { modeCoverageMerge: true, url: local.serverLocalHost + '?modeTest=1' };\n            local.browserTest(options, onError);\n        };\n        break;\n    }\n    switch (local.modeJs) {\n\n\n\n    // post-init\n    // run browser js-env code - post-init\n    /* istanbul ignore next */\n    case 'browser':\n        local.testRunBrowser = function (event) {\n            if (!event || (event &&\n                    event.currentTarget &&\n                    event.currentTarget.className &&\n                    event.currentTarget.className.includes &&\n                    event.currentTarget.className.includes('onreset'))) {\n                // reset output\n                Array.from(\n                    document.querySelectorAll('body > .resettable')\n                ).forEach(function (element) {\n                    switch (element.tagName) {\n                    case 'INPUT':\n                    case 'TEXTAREA':\n                        element.value = '';\n                        break;\n                    default:\n                        element.textContent = '';\n                    }\n                });\n            }\n            switch (event && event.currentTarget && event.currentTarget.id) {\n            case 'testRunButton1':\n                // show tests\n                if (document.querySelector('#testReportDiv1').style.display === 'none') {\n                    document.querySelector('#testReportDiv1').style.display = 'block';\n                    document.querySelector('#testRunButton1').textContent =\n                        'hide internal test';\n                    local.modeTest = true;\n                    local.testRunDefault(local);\n                // hide tests\n                } else {\n                    document.querySelector('#testReportDiv1').style.display = 'none';\n                    document.querySelector('#testRunButton1').textContent = 'run internal test';\n                }\n                break;\n            // custom-case\n            case 'testRunButton2':\n                // run tests\n                local.modeTest = true;\n                local.testRunDefault(local);\n                break;\n            default:\n                if (location.href.indexOf(\"modeTest=\") >= 0) {\n                    return;\n                }\n                // try to JSON.stringify #inputTextareaEval1\n                try {\n                    document.querySelector('#outputPreJsonStringify1').textContent = '';\n                    document.querySelector('#outputPreJsonStringify1').textContent =\n                        local.jsonStringifyOrdered(\n                            JSON.parse(document.querySelector('#inputTextareaEval1').value),\n                            null,\n                            4\n                        );\n                } catch (ignore) {\n                }\n                // jslint #inputTextareaEval1\n                local.jslint.errorText = '';\n                if (document.querySelector('#inputTextareaEval1').value\n                        .indexOf('/*jslint') >= 0) {\n                    local.jslint.jslintAndPrint(\n                        document.querySelector('#inputTextareaEval1').value,\n                        'inputTextareaEval1.js'\n                    );\n                }\n                document.querySelector('#outputPreJslint1').textContent =\n                    local.jslint.errorText\n                    .replace((/\\u001b\\[\\d+m/g), '')\n                    .trim();\n                // try to cleanup __coverage__\n                try {\n                    delete local.global.__coverage__['/inputTextareaEval1.js'];\n                } catch (ignore) {\n                }\n                // try to cover and eval input-code\n                try {\n                    /*jslint evil: true*/\n                    document.querySelector('#outputTextarea1').value =\n                        local.istanbul.instrumentSync(\n                            document.querySelector('#inputTextareaEval1').value,\n                            '/inputTextareaEval1.js'\n                        );\n                    eval(document.querySelector('#outputTextarea1').value);\n                    document.querySelector('#coverageReportDiv1').innerHTML =\n                        local.istanbul.coverageReportCreate({\n                            coverage: window.__coverage__\n                        });\n                } catch (errorCaught) {\n                    console.error(errorCaught.stack);\n                }\n            }\n            if (document.querySelector('#inputTextareaEval1') && (!event || (event &&\n                    event.currentTarget &&\n                    event.currentTarget.className &&\n                    event.currentTarget.className.includes &&\n                    event.currentTarget.className.includes('oneval')))) {\n                // try to eval input-code\n                try {\n                    /*jslint evil: true*/\n                    eval(document.querySelector('#inputTextareaEval1').value);\n                } catch (errorCaught) {\n                    console.error(errorCaught.stack);\n                }\n            }\n        };\n        // log stderr and stdout to #outputTextareaStdout1\n        ['error', 'log'].forEach(function (key) {\n            console[key + '_original'] = console[key];\n            console[key] = function () {\n                var element;\n                console[key + '_original'].apply(console, arguments);\n                element = document.querySelector('#outputTextareaStdout1');\n                if (!element) {\n                    return;\n                }\n                // append text to #outputTextareaStdout1\n                element.value += Array.from(arguments).map(function (arg) {\n                    return typeof arg === 'string'\n                        ? arg\n                        : JSON.stringify(arg, null, 4);\n                }).join(' ') + '\\n';\n                // scroll textarea to bottom\n                element.scrollTop = element.scrollHeight;\n            };\n        });\n        // init event-handling\n        ['change', 'click', 'keyup'].forEach(function (event) {\n            Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {\n                element.addEventListener(event, local.testRunBrowser);\n            });\n        });\n        // run tests\n        local.testRunBrowser();\n        break;\n\n\n\n    // run node js-env code - post-init\n    /* istanbul ignore next */\n    case 'node':\n        // export local\n        module.exports = local;\n        // require modules\n        local.fs = require('fs');\n        local.http = require('http');\n        local.url = require('url');\n        // init assets\n        local.assetsDict = local.assetsDict || {};\n        /* jslint-ignore-begin */\n        local.assetsDict['/assets.index.template.html'] = '\\\n<!doctype html>\\n\\\n<html lang=\"en\">\\n\\\n<head>\\n\\\n<meta charset=\"UTF-8\">\\n\\\n<meta name=\"viewport\" content=\"width=device-width, initial-scale=1\">\\n\\\n<title>{{env.npm_package_name}} (v{{env.npm_package_version}})</title>\\n\\\n<style>\\n\\\n/*csslint\\n\\\n    box-sizing: false,\\n\\\n    universal-selector: false\\n\\\n*/\\n\\\n* {\\n\\\n    box-sizing: border-box;\\n\\\n}\\n\\\nbody {\\n\\\n    background: #dde;\\n\\\n    font-family: Arial, Helvetica, sans-serif;\\n\\\n    margin: 2rem;\\n\\\n}\\n\\\nbody > * {\\n\\\n    margin-bottom: 1rem;\\n\\\n}\\n\\\n.utility2FooterDiv {\\n\\\n    margin-top: 20px;\\n\\\n    text-align: center;\\n\\\n}\\n\\\n</style>\\n\\\n<style>\\n\\\n/*csslint\\n\\\n    ids: false,\\n\\\n*/\\n\\\n#outputPreJslint1 {\\n\\\n    color: #d00;\\n\\\n}\\n\\\ntextarea {\\n\\\n    font-family: monospace;\\n\\\n    height: 10rem;\\n\\\n    width: 100%;\\n\\\n}\\n\\\ntextarea[readonly] {\\n\\\n    background: #ddd;\\n\\\n}\\n\\\n</style>\\n\\\n</head>\\n\\\n<body>\\n\\\n<!-- utility2-comment\\n\\\n<div id=\"ajaxProgressDiv1\" style=\"background: #d00; height: 2px; left: 0; margin: 0; padding: 0; position: fixed; top: 0; transition: background 0.5s, width 1.5s; width: 25%;\"></div>\\n\\\nutility2-comment -->\\n\\\n<h1>\\n\\\n<!-- utility2-comment\\n\\\n    <a\\n\\\n        {{#if env.npm_package_homepage}}\\n\\\n        href=\"{{env.npm_package_homepage}}\"\\n\\\n        {{/if env.npm_package_homepage}}\\n\\\n        target=\"_blank\"\\n\\\n    >\\n\\\nutility2-comment -->\\n\\\n        {{env.npm_package_name}} (v{{env.npm_package_version}})\\n\\\n<!-- utility2-comment\\n\\\n    </a>\\n\\\nutility2-comment -->\\n\\\n</h1>\\n\\\n<h3>{{env.npm_package_description}}</h3>\\n\\\n<!-- utility2-comment\\n\\\n<h4><a download href=\"assets.app.js\">download standalone app</a></h4>\\n\\\nutility2-comment -->\\n\\\n\\n\\\n\\n\\\n\\n\\\n<label>edit or paste script below to cover and test</label>\\n\\\n<textarea class=\"oneval onkeyup onreset\" id=\"inputTextareaEval1\">\\n\\\n// remove comment below to disable jslint\\n\\\n/*jslint\\n\\\n    browser: true,\\n\\\n    es6: true\\n\\\n*/\\n\\\n/*global window*/\\n\\\n(function () {\\n\\\n    \"use strict\";\\n\\\n    var testCaseDict;\\n\\\n    testCaseDict = {};\\n\\\n    testCaseDict.modeTest = true;\\n\\\n\\n\\\n    // comment this testCase to disable the failed assertion demo\\n\\\n    testCaseDict.testCase_failed_assertion_demo = function (\\n\\\n        options,\\n\\\n        onError\\n\\\n    ) {\\n\\\n    /*\\n\\\n     * this function will demo a failed assertion test\\n\\\n     */\\n\\\n        // jslint-hack\\n\\\n        window.utility2.nop(options);\\n\\\n        window.utility2.assert(false, \"this is a failed assertion demo\");\\n\\\n        onError();\\n\\\n    };\\n\\\n\\n\\\n    testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\\n\\\n    /*\\n\\\n     * this function will demo a passed ajax test\\n\\\n     */\\n\\\n        var data;\\n\\\n        options = {url: \"/\"};\\n\\\n        // test ajax request for main-page \"/\"\\n\\\n        window.utility2.ajax(options, function (error, xhr) {\\n\\\n            try {\\n\\\n                // validate no error occurred\\n\\\n                window.utility2.assert(!error, error);\\n\\\n                // validate \"200 ok\" status\\n\\\n                window.utility2.assert(xhr.statusCode === 200, xhr.statusCode);\\n\\\n                // validate non-empty data\\n\\\n                data = xhr.responseText;\\n\\\n                window.utility2.assert(data && data.length > 0, data);\\n\\\n                onError();\\n\\\n            } catch (errorCaught) {\\n\\\n                onError(errorCaught);\\n\\\n            }\\n\\\n        });\\n\\\n    };\\n\\\n\\n\\\n    window.utility2.testRunDefault(testCaseDict);\\n\\\n}());\\n\\\n</textarea>\\n\\\n<pre id=\"outputPreJsonStringify1\"></pre>\\n\\\n<pre id=\"outputPreJslint1\"></pre>\\n\\\n<label>instrumented-code</label>\\n\\\n<textarea class=\"resettable\" id=\"outputTextarea1\" readonly></textarea>\\n\\\n<label>stderr and stdout</label>\\n\\\n<textarea class=\"resettable\" id=\"outputTextareaStdout1\" readonly></textarea>\\n\\\n<button class=\"onclick onreset\" id=\"testRunButton2\">run internal test</button><br>\\n\\\n<div class=\"resettable\" id=\"testReportDiv1\" style=\"display: none;\"></div>\\n\\\n<div id=\"coverageReportDiv1\" class=\"resettable\"></div>\\n\\\n<!-- utility2-comment\\n\\\n{{#if isRollup}}\\n\\\n<script src=\"assets.app.js\"></script>\\n\\\n{{#unless isRollup}}\\n\\\nutility2-comment -->\\n\\\n<script src=\"assets.utility2.lib.istanbul.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.jslint.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.db.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.sjcl.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.uglifyjs.js\"></script>\\n\\\n<script src=\"assets.utility2.js\"></script>\\n\\\n<script src=\"jsonp.utility2._stateInit?callback=window.utility2._stateInit\"></script>\\n\\\n<script>window.utility2.onResetBefore.counter += 1;</script>\\n\\\n<script src=\"assets.example.js\"></script>\\n\\\n<script src=\"assets.test.js\"></script>\\n\\\n<script>window.utility2.onResetBefore();</script>\\n\\\n<!-- utility2-comment\\n\\\n{{/if isRollup}}\\n\\\nutility2-comment -->\\n\\\n<div class=\"utility2FooterDiv\">\\n\\\n    [ this app was created with\\n\\\n    <a href=\"https://github.com/kaizhu256/node-utility2\" target=\"_blank\">utility2</a>\\n\\\n    ]\\n\\\n</div>\\n\\\n</body>\\n\\\n</html>\\n\\\n';\n        /* jslint-ignore-end */\n        if (local.templateRender) {\n            local.assetsDict['/'] = local.templateRender(\n                local.assetsDict['/assets.index.template.html'],\n                {\n                    env: local.objectSetDefault(local.env, {\n                        npm_package_description: 'example module',\n                        npm_package_name: 'example',\n                        npm_package_nameAlias: 'example',\n                        npm_package_version: '0.0.1'\n                    })\n                }\n            );\n        } else {\n            local.assetsDict['/'] = local.assetsDict['/assets.index.template.html']\n                .replace((/\\{\\{env\\.(\\w+?)\\}\\}/g), function (match0, match1) {\n                    // jslint-hack\n                    String(match0);\n                    switch (match1) {\n                    case 'npm_package_description':\n                        return 'example module';\n                    case 'npm_package_name':\n                        return 'example';\n                    case 'npm_package_nameAlias':\n                        return 'example';\n                    case 'npm_package_version':\n                        return '0.0.1';\n                    }\n                });\n        }\n        // run the cli\n        if (local.global.utility2_rollup || module !== require.main) {\n            break;\n        }\n        local.assetsDict['/assets.example.js'] =\n            local.assetsDict['/assets.example.js'] ||\n            local.fs.readFileSync(__filename, 'utf8');\n        local.assetsDict['/assets.utility2.rollup.js'] =\n            local.assetsDict['/assets.utility2.rollup.js'] ||\n            local.fs.readFileSync(\n                // npmdoc-hack\n                local.utility2.__dirname +\n                    '/lib.utility2.js',\n                'utf8'\n            ).replace((/^#!/), '//');\n        local.assetsDict['/favicon.ico'] = local.assetsDict['/favicon.ico'] || '';\n        // if $npm_config_timeout_exit exists,\n        // then exit this process after $npm_config_timeout_exit ms\n        if (Number(process.env.npm_config_timeout_exit)) {\n            setTimeout(process.exit, Number(process.env.npm_config_timeout_exit));\n        }\n        // start server\n        if (local.global.utility2_serverHttp1) {\n            break;\n        }\n        process.env.PORT = process.env.PORT || '8081';\n        console.log('server starting on port ' + process.env.PORT);\n        local.http.createServer(function (request, response) {\n            request.urlParsed = local.url.parse(request.url);\n            if (local.assetsDict[request.urlParsed.pathname] !== undefined) {\n                response.end(local.assetsDict[request.urlParsed.pathname]);\n                return;\n            }\n            response.statusCode = 404;\n            response.end();\n        }).listen(process.env.PORT);\n        break;\n    }\n}());\n'''\n\n#### output from utility2\n![screen-capture](https://kaizhu256.github.io/screen-capture.testExampleJs.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Ftest-report.html.png)\n\n#### output from istanbul\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.browser._2Ftmp_2Fapp_2Ftmp_2Fbuild_2Fcoverage.html_2Fapp_2Fexample.js.html.png)\n\n#### output from shell\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.svg)\n\n\n\n# package.json\n'''json\n{\n    \"author\": \"kai zhu <kaizhu256@gmail.com>\",\n    \"bin\": {\n        \"utility2\": \"lib.utility2.sh\",\n        \"utility2-apidoc\": \"lib.apidoc.js\",\n        \"utility2-github-crud\": \"lib.github_crud.js\",\n        \"utility2-istanbul\": \"lib.istanbul.js\",\n        \"utility2-jslint\": \"lib.jslint.js\",\n        \"utility2-uglifyjs\": \"lib.uglifyjs.js\"\n    },\n    \"description\": \"the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps\",\n    \"devDependencies\": {\n        \"electron-lite\": \"kaizhu256/node-electron-lite#alpha\"\n    },\n    \"engines\": {\n        \"node\": \">=4.0\"\n    },\n    \"homepage\": \"https://github.com/kaizhu256/node-utility2\",\n    \"keywords\": [\n        \"browser\",\n        \"build\",\n        \"busybox\",\n        \"ci\",\n        \"code-coverage\",\n        \"continuous-integration\",\n        \"deploy\",\n        \"docker\",\n        \"electron\",\n        \"headless-browser\",\n        \"istanbul\",\n        \"jscover\",\n        \"jscoverage\",\n        \"phantomjs\",\n        \"slimerjs\",\n        \"swiss-army-knife\",\n        \"test\",\n        \"test-coverage\",\n        \"travis\",\n        \"travis-ci\",\n        \"utility2\",\n        \"webapp\"\n    ],\n    \"license\": \"MIT\",\n    \"main\": \"lib.utility2.js\",\n    \"name\": \"utility2\",\n    \"nameAlias\": \"utility2\",\n    \"nameAliasPublish\": \"busybox npmtest-lite test-lite\",\n    \"nameOriginal\": \"utility2\",\n    \"os\": [\n        \"darwin\",\n        \"linux\"\n    ],\n    \"readmeParse\": \"1\",\n    \"repository\": {\n        \"type\": \"git\",\n        \"url\": \"https://github.com/kaizhu256/node-utility2.git\"\n    },\n    \"scripts\": {\n        \"build-ci\": \"./lib.utility2.sh shReadmeTest build_ci.sh\",\n        \"env\": \"env\",\n        \"heroku-postbuild\": \"./lib.utility2.sh shDeployHeroku\",\n        \"postinstall\": \"if [ -f npm_scripts.sh ]; then ./npm_scripts.sh postinstall; fi\",\n        \"start\": \"(set -e; export PORT=${PORT:-8080}; if [ -f assets.app.js ]; then node assets.app.js; exit; fi; export npm_config_mode_auto_restart=1; ./lib.utility2.sh shRun shIstanbulCover test.js)\",\n        \"test\": \"(set -e; export PORT=$(./lib.utility2.sh shServerPortRandom); export PORT_REPL=$(./lib.utility2.sh shServerPortRandom); export npm_config_mode_auto_restart=1; ./lib.utility2.sh test test.js)\"\n    },\n    \"version\": \"2017.3.22\"\n}\n'''\n\n\n\n# changelog of last 50 commits\n[![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.gitLog.svg)](https://github.com/kaizhu256/node-utility2/commits)\n\n\n\n# internal build-script\n- Dockerfile.base\n'''shell\n# Dockerfile.base\n# docker build -f tmp/README.Dockerfile.base -t kaizhu256/node-utility2:base .\n# docker build -f \"tmp/README.Dockerfile.$DOCKER_TAG\" -t \"$GITHUB_REPO:$DOCKER_TAG\" .\n# https://hub.docker.com/_/node/\nFROM debian:stable-slim\nMAINTAINER kai zhu <kaizhu256@gmail.com>\nVOLUME [ \\\n  \"/mnt\", \\\n  \"/root\", \\\n  \"/tmp\", \\\n  \"/usr/share/doc\", \\\n  \"/usr/share/man\", \\\n  \"/var/cache\", \\\n  \"/var/lib/apt\", \\\n  \"/var/log\", \\\n  \"/var/tmp\" \\\n]\nWORKDIR /tmp\n# install nodejs\n# https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        apt-utils \\\n        busybox \\\n        ca-certificates \\\n        curl && \\\n    (busybox --list | xargs -n1 /bin/sh -c 'ln -s /bin/busybox /bin/$0 2>/dev/null' || true) \\\n        && \\\n    curl -sL https://deb.nodesource.com/setup_6.x | /bin/bash - && \\\n    apt-get install -y nodejs\n# install electron-lite\nVOLUME [ \\\n  \"/usr/lib/chromium\" \\\n]\n# COPY electron-*.zip /tmp\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        chromium \\\n        gconf2 \\\n        git \\\n        xvfb && \\\n    npm install \"kaizhu256/node-electron-lite#alpha\" && \\\n    cd node_modules/electron-lite && \\\n    npm install && \\\n    export DISPLAY=:99.0 && \\\n    (Xvfb \"$DISPLAY\" &) && \\\n    npm test && \\\n    cp /tmp/electron-*.zip /\n# install extras\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        nginx-extras \\\n        transmission-daemon \\\n        ssh \\\n        vim\n'''\n\n- Dockerfile.elasticsearch\n'''shell\n# Dockerfile.elasticsearch\nFROM kaizhu256/node-utility2:latest\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# install swagger-ui\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    rm -fr /swagger-ui && \\\n    git clone --branch=v2.1.5 --single-branch \\\n        https://github.com/swagger-api/swagger-ui.git && \\\n    mv swagger-ui/dist /swagger-ui\n'''\n\n- Dockerfile.emscripten\n'''shell\n# Dockerfile.emscripten\n# docker build -f tmp/README.Dockerfile.emscripten -t emscripten .\nFROM kaizhu256/node-utility2:latest\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# https://kripken.github.io/emscripten-site/docs\n# /building_from_source/building_emscripten_from_source_using_the_sdk.html\n# build emscripten v1.36.0\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    mkdir -p /usr/share/man/man1 && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        cmake && \\\n    cd / && \\\n    git clone https://github.com/juj/emsdk.git --branch=master --single-branch && \\\n    cd /emsdk && \\\n    ./emsdk install -j2 --shallow sdk-master-64bit && \\\n    ./emsdk activate && \\\n    find . -name \".git\" -print0 | xargs -0 rm -fr && \\\n    find . -name \"src\" -print0 | xargs -0 rm -fr\n'''\n\n- Dockerfile.latest\n'''shell\n# Dockerfile.latest\nFROM kaizhu256/node-utility2:base\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# install elasticsearch and kibana\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    mkdir -p /usr/share/man/man1 && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        default-jre && \\\n    curl -#Lo elasticsearch.tar.gz \\\n        https://download.elastic.co/elasticsearch/elasticsearch/elasticsearch-1.7.6.tar.gz && \\\n    rm -fr /elasticsearch && \\\n    mkdir -p /elasticsearch && \\\n    tar -xzf elasticsearch.tar.gz --strip-components=1 -C /elasticsearch && \\\n    curl -#Lo kibana.tar.gz https://download.elastic.co/kibana/kibana/kibana-3.1.3.tar.gz && \\\n    rm -fr /kibana && \\\n    mkdir -p /kibana && \\\n    tar -xzf kibana.tar.gz --strip-components=1 -C /kibana\n'''\n\n- build_ci.sh\n'''shell\n# build_ci.sh\n\n# this shell script will run the build for this package\n\nshBuildCiInternalPost() {(set -e\n    #// coverage-hack\n    shDeployGithub\n    shDeployHeroku\n    shReadmeBuildLinkVerify\n)}\n\nshBuildCiInternalPre() {(set -e\n    shReadmeTest example.js\n    # save screen-capture\n    (export MODE_BUILD=testExampleJs\n        export modeBrowserTest=screenCapture\n        export url=\"/tmp/app/tmp/build/coverage.html/app/example.js.html\"\n        shBrowserTest\n        export url=\"$npm_config_dir_build/test-report.html\"\n        shBrowserTest)\n    shReadmeTest example.sh\n    shNpmTestPublished\n)}\n\n# run shBuildCi\n. ./lib.utility2.sh\nshBuildCi\n'''\n\n\n\n# misc\n- this package was created with [utility2](https://github.com/kaizhu256/node-utility2)\n",
    "readmeFilename": "README.md",
    "readmeParse": "1",
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
    "version": "2017.3.22"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module utility2](#apidoc.module.utility2)
1.  [function <span class="apidocSignatureSpan">utility2.</span>Blob (array, options)](#apidoc.element.utility2.Blob)
1.  [function <span class="apidocSignatureSpan">utility2.</span>FormData ()](#apidoc.element.utility2.FormData)
1.  [function <span class="apidocSignatureSpan">utility2.</span>Module (id, parent)](#apidoc.element.utility2.Module)
1.  [function <span class="apidocSignatureSpan">utility2.</span>__require (path)](#apidoc.element.utility2.__require)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_http.IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_http.ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_http.XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_middleware (request, response, nextMiddleware)](#apidoc.element.utility2._middleware)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_middlewareError (error, request, response)](#apidoc.element.utility2._middlewareError)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_middlewareJsonpStateInit (request, response, nextMiddleware)](#apidoc.element.utility2._middlewareJsonpStateInit)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_serverLocalUrlTest ()](#apidoc.element.utility2._serverLocalUrlTest)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_stateInit (options)](#apidoc.element.utility2._stateInit)
1.  [function <span class="apidocSignatureSpan">utility2.</span>_testRunBefore ()](#apidoc.element.utility2._testRunBefore)
1.  [function <span class="apidocSignatureSpan">utility2.</span>ajax (options, onError)](#apidoc.element.utility2.ajax)
1.  [function <span class="apidocSignatureSpan">utility2.</span>ajaxProgressUpdate ()](#apidoc.element.utility2.ajaxProgressUpdate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>apidocCreate (options)](#apidoc.element.utility2.apidocCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>assert (passed, message)](#apidoc.element.utility2.assert)
1.  [function <span class="apidocSignatureSpan">utility2.</span>assertJsonEqual (aa, bb)](#apidoc.element.utility2.assertJsonEqual)
1.  [function <span class="apidocSignatureSpan">utility2.</span>assertJsonNotEqual (aa, bb)](#apidoc.element.utility2.assertJsonNotEqual)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64FromBuffer (bff)](#apidoc.element.utility2.base64FromBuffer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64FromHex (text)](#apidoc.element.utility2.base64FromHex)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64FromString (text)](#apidoc.element.utility2.base64FromString)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64ToBuffer (text)](#apidoc.element.utility2.base64ToBuffer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64ToHex (text)](#apidoc.element.utility2.base64ToHex)
1.  [function <span class="apidocSignatureSpan">utility2.</span>base64ToString (text)](#apidoc.element.utility2.base64ToString)
1.  [function <span class="apidocSignatureSpan">utility2.</span>blobRead (blob, encoding, onError)](#apidoc.element.utility2.blobRead)
1.  [function <span class="apidocSignatureSpan">utility2.</span>browserTest (options, onError)](#apidoc.element.utility2.browserTest)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferConcat (bufferList)](#apidoc.element.utility2.bufferConcat)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferCreate (text)](#apidoc.element.utility2.bufferCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferCreateIfNotBuffer (text)](#apidoc.element.utility2.bufferCreateIfNotBuffer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferIndexOfSubBuffer (bff, subBff, fromIndex)](#apidoc.element.utility2.bufferIndexOfSubBuffer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferRandomBytes (length)](#apidoc.element.utility2.bufferRandomBytes)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferToNodeBuffer (bff)](#apidoc.element.utility2.bufferToNodeBuffer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>bufferToString (bff)](#apidoc.element.utility2.bufferToString)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildApidoc (options, onError)](#apidoc.element.utility2.buildApidoc)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildApp (optionsList, onError)](#apidoc.element.utility2.buildApp)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildLib (options, onError)](#apidoc.element.utility2.buildLib)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildNpmdoc (options, onError)](#apidoc.element.utility2.buildNpmdoc)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildReadme (options, onError)](#apidoc.element.utility2.buildReadme)
1.  [function <span class="apidocSignatureSpan">utility2.</span>buildTest (options, onError)](#apidoc.element.utility2.buildTest)
1.  [function <span class="apidocSignatureSpan">utility2.</span>cookieDict ()](#apidoc.element.utility2.cookieDict)
1.  [function <span class="apidocSignatureSpan">utility2.</span>cookieRemove (name)](#apidoc.element.utility2.cookieRemove)
1.  [function <span class="apidocSignatureSpan">utility2.</span>cookieRemoveAll ()](#apidoc.element.utility2.cookieRemoveAll)
1.  [function <span class="apidocSignatureSpan">utility2.</span>cookieSet (name, value, expiresOffset)](#apidoc.element.utility2.cookieSet)
1.  [function <span class="apidocSignatureSpan">utility2.</span>db._DbTable (options)](#apidoc.element.utility2.db._DbTable)
1.  [function <span class="apidocSignatureSpan">utility2.</span>domFragmentRender (template, dict)](#apidoc.element.utility2.domFragmentRender)
1.  [function <span class="apidocSignatureSpan">utility2.</span>echo (arg)](#apidoc.element.utility2.echo)
1.  [function <span class="apidocSignatureSpan">utility2.</span>errorMessagePrepend (error, message)](#apidoc.element.utility2.errorMessagePrepend)
1.  [function <span class="apidocSignatureSpan">utility2.</span>exit (exitCode)](#apidoc.element.utility2.exit)
1.  [function <span class="apidocSignatureSpan">utility2.</span>fsRmrSync (dir)](#apidoc.element.utility2.fsRmrSync)
1.  [function <span class="apidocSignatureSpan">utility2.</span>fsWriteFileWithMkdirpSync (file, data)](#apidoc.element.utility2.fsWriteFileWithMkdirpSync)
1.  [function <span class="apidocSignatureSpan">utility2.</span>httpRequest (options, onError)](#apidoc.element.utility2.httpRequest)
1.  [function <span class="apidocSignatureSpan">utility2.</span>isNullOrUndefined (arg)](#apidoc.element.utility2.isNullOrUndefined)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbul.HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbul.Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbul.TextReport (e)](#apidoc.element.utility2.istanbul.TextReport)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbul.require (path)](#apidoc.element.utility2.istanbul.require)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbulCoverageMerge (coverage1, coverage2)](#apidoc.element.utility2.istanbulCoverageMerge)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbulCoverageReportCreate ()](#apidoc.element.utility2.istanbulCoverageReportCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbulInstrumentInPackage (code, file)](#apidoc.element.utility2.istanbulInstrumentInPackage)
1.  [function <span class="apidocSignatureSpan">utility2.</span>istanbulInstrumentSync (code, file)](#apidoc.element.utility2.istanbulInstrumentSync)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jslint.JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jslintAndPrint (script, file)](#apidoc.element.utility2.jslintAndPrint)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jslintAndPrintConditional (script, file, mode)](#apidoc.element.utility2.jslintAndPrintConditional)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jsonCopy (arg)](#apidoc.element.utility2.jsonCopy)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jsonStringifyOrdered (element, replacer, space)](#apidoc.element.utility2.jsonStringifyOrdered)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtA256GcmDecrypt (token, key)](#apidoc.element.utility2.jwtA256GcmDecrypt)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtA256GcmEncrypt (data, key)](#apidoc.element.utility2.jwtA256GcmEncrypt)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtAes256KeyCreate ()](#apidoc.element.utility2.jwtAes256KeyCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtAes256KeyInit (key)](#apidoc.element.utility2.jwtAes256KeyInit)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtBase64UrlNormalize (text)](#apidoc.element.utility2.jwtBase64UrlNormalize)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtHs256Decode (token, key)](#apidoc.element.utility2.jwtHs256Decode)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtHs256Encode (data, key)](#apidoc.element.utility2.jwtHs256Encode)
1.  [function <span class="apidocSignatureSpan">utility2.</span>jwtNormalize (data)](#apidoc.element.utility2.jwtNormalize)
1.  [function <span class="apidocSignatureSpan">utility2.</span>listGetElementRandom (list)](#apidoc.element.utility2.listGetElementRandom)
1.  [function <span class="apidocSignatureSpan">utility2.</span>listShuffle (list)](#apidoc.element.utility2.listShuffle)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareAssetsCached (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareAssetsCached)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareBodyRead (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareBodyRead)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareCacheControlLastModified ( request, response, nextMiddleware )](#apidoc.element.utility2.middlewareCacheControlLastModified)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareFileServer (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareFileServer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareForwardProxy (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareForwardProxy)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareGroupCreate (middlewareList)](#apidoc.element.utility2.middlewareGroupCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>middlewareInit (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareInit)
1.  [function <span class="apidocSignatureSpan">utility2.</span>moduleDirname (module, modulePathList)](#apidoc.element.utility2.moduleDirname)
1.  [function <span class="apidocSignatureSpan">utility2.</span>nop ()](#apidoc.element.utility2.nop)
1.  [function <span class="apidocSignatureSpan">utility2.</span>normalizeDict (dict)](#apidoc.element.utility2.normalizeDict)
1.  [function <span class="apidocSignatureSpan">utility2.</span>normalizeList (list)](#apidoc.element.utility2.normalizeList)
1.  [function <span class="apidocSignatureSpan">utility2.</span>normalizeText (text)](#apidoc.element.utility2.normalizeText)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectGetElementFirst (arg)](#apidoc.element.utility2.objectGetElementFirst)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectKeysTypeof (arg)](#apidoc.element.utility2.objectKeysTypeof)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectLiteralize (arg)](#apidoc.element.utility2.objectLiteralize)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectSetDefault (arg, defaults, depth)](#apidoc.element.utility2.objectSetDefault)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectSetOverride (arg, overrides, depth, env)](#apidoc.element.utility2.objectSetOverride)
1.  [function <span class="apidocSignatureSpan">utility2.</span>objectTraverse (arg, onSelf, circularList)](#apidoc.element.utility2.objectTraverse)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onErrorDefault (error)](#apidoc.element.utility2.onErrorDefault)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onErrorThrow (error)](#apidoc.element.utility2.onErrorThrow)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onErrorWithStack (onError)](#apidoc.element.utility2.onErrorWithStack)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onFileModifiedRestart (file)](#apidoc.element.utility2.onFileModifiedRestart)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onNext (options, onError)](#apidoc.element.utility2.onNext)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.onParallel)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onReadyAfter (onError)](#apidoc.element.utility2.onReadyAfter)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onReadyBefore (error)](#apidoc.element.utility2.onReadyBefore)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onResetAfter (onError)](#apidoc.element.utility2.onResetAfter)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onResetBefore (error)](#apidoc.element.utility2.onResetBefore)
1.  [function <span class="apidocSignatureSpan">utility2.</span>onTimeout (onError, timeout, message)](#apidoc.element.utility2.onTimeout)
1.  [function <span class="apidocSignatureSpan">utility2.</span>processSpawnWithTimeout ()](#apidoc.element.utility2.processSpawnWithTimeout)
1.  [function <span class="apidocSignatureSpan">utility2.</span>profile (fnc, onError)](#apidoc.element.utility2.profile)
1.  [function <span class="apidocSignatureSpan">utility2.</span>profileSync (fnc)](#apidoc.element.utility2.profileSync)
1.  [function <span class="apidocSignatureSpan">utility2.</span>replStart ()](#apidoc.element.utility2.replStart)
1.  [function <span class="apidocSignatureSpan">utility2.</span>requireExampleJsFromReadme ()](#apidoc.element.utility2.requireExampleJsFromReadme)
1.  [function <span class="apidocSignatureSpan">utility2.</span>serverLocalRequestHandler (request, response)](#apidoc.element.utility2.serverLocalRequestHandler)
1.  [function <span class="apidocSignatureSpan">utility2.</span>serverRespondDefault (request, response, statusCode, error)](#apidoc.element.utility2.serverRespondDefault)
1.  [function <span class="apidocSignatureSpan">utility2.</span>serverRespondEcho (request, response)](#apidoc.element.utility2.serverRespondEcho)
1.  [function <span class="apidocSignatureSpan">utility2.</span>serverRespondHeadSet (request, response, statusCode, headers)](#apidoc.element.utility2.serverRespondHeadSet)
1.  [function <span class="apidocSignatureSpan">utility2.</span>serverRespondTimeoutDefault (request, response, timeout)](#apidoc.element.utility2.serverRespondTimeoutDefault)
1.  [function <span class="apidocSignatureSpan">utility2.</span>sjcl.prng (e)](#apidoc.element.utility2.sjcl.prng)
1.  [function <span class="apidocSignatureSpan">utility2.</span>sjclHashScryptCreate (password, options)](#apidoc.element.utility2.sjclHashScryptCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>sjclHashScryptValidate (password, hash)](#apidoc.element.utility2.sjclHashScryptValidate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>sjclHashSha256Create (data)](#apidoc.element.utility2.sjclHashSha256Create)
1.  [function <span class="apidocSignatureSpan">utility2.</span>sjclHmacSha256Create (key, data)](#apidoc.element.utility2.sjclHmacSha256Create)
1.  [function <span class="apidocSignatureSpan">utility2.</span>streamListCleanup (streamList)](#apidoc.element.utility2.streamListCleanup)
1.  [function <span class="apidocSignatureSpan">utility2.</span>streamReadAll (stream, onError)](#apidoc.element.utility2.streamReadAll)
1.  [function <span class="apidocSignatureSpan">utility2.</span>stringHtmlSafe (text)](#apidoc.element.utility2.stringHtmlSafe)
1.  [function <span class="apidocSignatureSpan">utility2.</span>taskCreate (options, onTask, onError)](#apidoc.element.utility2.taskCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>taskCreateCached (options, onTask, onError)](#apidoc.element.utility2.taskCreateCached)
1.  [function <span class="apidocSignatureSpan">utility2.</span>templateRender (template, dict)](#apidoc.element.utility2.templateRender)
1.  [function <span class="apidocSignatureSpan">utility2.</span>templateRenderJslintLite (template, options)](#apidoc.element.utility2.templateRenderJslintLite)
1.  [function <span class="apidocSignatureSpan">utility2.</span>testMock (mockList, onTestCase, onError)](#apidoc.element.utility2.testMock)
1.  [function <span class="apidocSignatureSpan">utility2.</span>testReportCreate (testReport)](#apidoc.element.utility2.testReportCreate)
1.  [function <span class="apidocSignatureSpan">utility2.</span>testReportMerge (testReport1, testReport2)](#apidoc.element.utility2.testReportMerge)
1.  [function <span class="apidocSignatureSpan">utility2.</span>testRunDefault (options)](#apidoc.element.utility2.testRunDefault)
1.  [function <span class="apidocSignatureSpan">utility2.</span>testRunServer (options)](#apidoc.element.utility2.testRunServer)
1.  [function <span class="apidocSignatureSpan">utility2.</span>timeElapsedStart (options)](#apidoc.element.utility2.timeElapsedStart)
1.  [function <span class="apidocSignatureSpan">utility2.</span>timeElapsedStop (options)](#apidoc.element.utility2.timeElapsedStop)
1.  [function <span class="apidocSignatureSpan">utility2.</span>tryCatchOnError (fnc, onError)](#apidoc.element.utility2.tryCatchOnError)
1.  [function <span class="apidocSignatureSpan">utility2.</span>tryCatchReadFile (file, options)](#apidoc.element.utility2.tryCatchReadFile)
1.  [function <span class="apidocSignatureSpan">utility2.</span>uglify (code, file)](#apidoc.element.utility2.uglify)
1.  [function <span class="apidocSignatureSpan">utility2.</span>uglifyjs.MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP)
1.  [function <span class="apidocSignatureSpan">utility2.</span>urlParse (url)](#apidoc.element.utility2.urlParse)
1.  [function <span class="apidocSignatureSpan">utility2.</span>uuid4Create ()](#apidoc.element.utility2.uuid4Create)
1.  number <span class="apidocSignatureSpan">utility2.</span>ajaxProgressCounter
1.  number <span class="apidocSignatureSpan">utility2.</span>ajaxProgressState
1.  number <span class="apidocSignatureSpan">utility2.</span>timeExit
1.  number <span class="apidocSignatureSpan">utility2.</span>timeoutDefault
1.  object <span class="apidocSignatureSpan"></span>utility2
1.  object <span class="apidocSignatureSpan">utility2.</span>FormData.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>__require.extensions
1.  object <span class="apidocSignatureSpan">utility2.</span>_debugTryCatchErrorCaught
1.  object <span class="apidocSignatureSpan">utility2.</span>_http
1.  object <span class="apidocSignatureSpan">utility2.</span>_http.IncomingMessage.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>_http.ServerResponse.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>_http.XMLHttpRequest.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>_http.XMLHttpRequest.prototype.upload
1.  object <span class="apidocSignatureSpan">utility2.</span>apidoc
1.  object <span class="apidocSignatureSpan">utility2.</span>assetsDict
1.  object <span class="apidocSignatureSpan">utility2.</span>cacheDict
1.  object <span class="apidocSignatureSpan">utility2.</span>contentTypeDict
1.  object <span class="apidocSignatureSpan">utility2.</span>db
1.  object <span class="apidocSignatureSpan">utility2.</span>db._DbTable.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>env
1.  object <span class="apidocSignatureSpan">utility2.</span>errorDefault
1.  object <span class="apidocSignatureSpan">utility2.</span>github_crud
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.HtmlReport.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.Instrumenter.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.TextReport.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.collector
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.coverageUtils
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.escodegen
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.esprima
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.estraverse
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.estraverse.Controller.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.fs
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.handlebars
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.util
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul.writer
1.  object <span class="apidocSignatureSpan">utility2.</span>jslint
1.  object <span class="apidocSignatureSpan">utility2.</span>jslint.CSSLint
1.  object <span class="apidocSignatureSpan">utility2.</span>jslint.CSSLint._Reporter.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>local
1.  object <span class="apidocSignatureSpan">utility2.</span>module
1.  object <span class="apidocSignatureSpan">utility2.</span>packageJsonNpmdocDefault
1.  object <span class="apidocSignatureSpan">utility2.</span>regexpEmailValidate
1.  object <span class="apidocSignatureSpan">utility2.</span>regexpPhoneValidate
1.  object <span class="apidocSignatureSpan">utility2.</span>regexpUriComponentCharset
1.  object <span class="apidocSignatureSpan">utility2.</span>regexpUuidValidate
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.bitArray
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.cipher
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.cipher.aes.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.exception
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.hash
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.hash.sha256.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.json
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.misc
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.misc.hmac.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>sjcl.prng.prototype
1.  object <span class="apidocSignatureSpan">utility2.</span>taskOnTaskDict
1.  object <span class="apidocSignatureSpan">utility2.</span>testReport
1.  object <span class="apidocSignatureSpan">utility2.</span>uglifyjs
1.  string <span class="apidocSignatureSpan">utility2.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.</span>modeJs
1.  string <span class="apidocSignatureSpan">utility2.</span>modeTest
1.  string <span class="apidocSignatureSpan">utility2.</span>modeTestCase
1.  string <span class="apidocSignatureSpan">utility2.</span>serverLocalHost
1.  string <span class="apidocSignatureSpan">utility2.</span>stringAsciiCharset
1.  string <span class="apidocSignatureSpan">utility2.</span>stringUriComponentCharset

#### [module utility2.FormData](#apidoc.module.utility2.FormData)
1.  [function <span class="apidocSignatureSpan">utility2.</span>FormData ()](#apidoc.element.utility2.FormData.FormData)

#### [module utility2.FormData.prototype](#apidoc.module.utility2.FormData.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.FormData.prototype.</span>append (name, value, filename)](#apidoc.element.utility2.FormData.prototype.append)
1.  [function <span class="apidocSignatureSpan">utility2.FormData.prototype.</span>read (onError)](#apidoc.element.utility2.FormData.prototype.read)

#### [module utility2.__require](#apidoc.module.utility2.__require)
1.  [function <span class="apidocSignatureSpan">utility2.</span>__require (path)](#apidoc.element.utility2.__require.__require)
1.  [function <span class="apidocSignatureSpan">utility2.__require.</span>resolve (request)](#apidoc.element.utility2.__require.resolve)
1.  object <span class="apidocSignatureSpan">utility2.__require.</span>cache
1.  object <span class="apidocSignatureSpan">utility2.__require.</span>extensions
1.  object <span class="apidocSignatureSpan">utility2.__require.</span>main

#### [module utility2.__require.extensions](#apidoc.module.utility2.__require.extensions)

#### [module utility2._http](#apidoc.module.utility2._http)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>createServer ()](#apidoc.element.utility2._http.createServer)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>request (xhr, onResponse)](#apidoc.element.utility2._http.request)
1.  object <span class="apidocSignatureSpan">utility2._http.</span>STATUS_CODES

#### [module utility2._http.IncomingMessage](#apidoc.module.utility2._http.IncomingMessage)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage.IncomingMessage)

#### [module utility2._http.IncomingMessage.prototype](#apidoc.module.utility2._http.IncomingMessage.prototype)
1.  [function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>addListener (event, onEvent)](#apidoc.element.utility2._http.IncomingMessage.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>emit (event, data)](#apidoc.element.utility2._http.IncomingMessage.prototype.emit)
1.  [function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>on (event, onEvent)](#apidoc.element.utility2._http.IncomingMessage.prototype.on)
1.  [function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>pipe (writable)](#apidoc.element.utility2._http.IncomingMessage.prototype.pipe)

#### [module utility2._http.ServerResponse](#apidoc.module.utility2._http.ServerResponse)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse.ServerResponse)

#### [module utility2._http.ServerResponse.prototype](#apidoc.module.utility2._http.ServerResponse.prototype)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>addListener (event, onEvent)](#apidoc.element.utility2._http.ServerResponse.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>emit (event, data)](#apidoc.element.utility2._http.ServerResponse.prototype.emit)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>end (data)](#apidoc.element.utility2._http.ServerResponse.prototype.end)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>on (event, onEvent)](#apidoc.element.utility2._http.ServerResponse.prototype.on)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>setHeader (key, value)](#apidoc.element.utility2._http.ServerResponse.prototype.setHeader)
1.  [function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>write (data)](#apidoc.element.utility2._http.ServerResponse.prototype.write)

#### [module utility2._http.XMLHttpRequest](#apidoc.module.utility2._http.XMLHttpRequest)
1.  [function <span class="apidocSignatureSpan">utility2._http.</span>XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest.XMLHttpRequest)

#### [module utility2._http.XMLHttpRequest.prototype](#apidoc.module.utility2._http.XMLHttpRequest.prototype)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>abort ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.abort)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>addEventListener (event, onError)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>getAllResponseHeaders ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.getAllResponseHeaders)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>getResponseHeader (key)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.getResponseHeader)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onError (error, data)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onError)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onResponse (responseStream)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onResponse)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onreadystatechange ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onreadystatechange)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>open (method, url)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.open)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>overrideMimeType ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.overrideMimeType)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>send (data)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.send)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>setRequestHeader (key, value)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.setRequestHeader)
1.  object <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>upload

#### [module utility2._http.XMLHttpRequest.prototype.upload](#apidoc.module.utility2._http.XMLHttpRequest.prototype.upload)
1.  [function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.upload.</span>addEventListener ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.upload.addEventListener)

#### [module utility2.apidoc](#apidoc.module.utility2.apidoc)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>apidocCreate (options)](#apidoc.element.utility2.apidoc.apidocCreate)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>apidocModuleDictAdd (options, moduleDict)](#apidoc.element.utility2.apidoc.apidocModuleDictAdd)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>assert (passed, message)](#apidoc.element.utility2.apidoc.assert)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>moduleDirname (module, modulePathList)](#apidoc.element.utility2.apidoc.moduleDirname)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>nop ()](#apidoc.element.utility2.apidoc.nop)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>objectSetDefault (arg, defaults, depth)](#apidoc.element.utility2.apidoc.objectSetDefault)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>stringHtmlSafe (text)](#apidoc.element.utility2.apidoc.stringHtmlSafe)
1.  [function <span class="apidocSignatureSpan">utility2.apidoc.</span>templateRender (template, dict)](#apidoc.element.utility2.apidoc.templateRender)
1.  object <span class="apidocSignatureSpan">utility2.</span>apidoc
1.  object <span class="apidocSignatureSpan">utility2.apidoc.</span>local
1.  object <span class="apidocSignatureSpan">utility2.apidoc.</span>module
1.  string <span class="apidocSignatureSpan">utility2.apidoc.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.apidoc.</span>modeJs
1.  string <span class="apidocSignatureSpan">utility2.apidoc.</span>templateApidocHtml
1.  string <span class="apidocSignatureSpan">utility2.apidoc.</span>templateApidocMd

#### [module utility2.db](#apidoc.module.utility2.db)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>_DbTable (options)](#apidoc.element.utility2.db._DbTable)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbCrudRemoveAll (onError)](#apidoc.element.utility2.db.dbCrudRemoveAll)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbDrop (onError)](#apidoc.element.utility2.db.dbDrop)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbExport (onError)](#apidoc.element.utility2.db.dbExport)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbImport (text, onError)](#apidoc.element.utility2.db.dbImport)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbLoad (onError)](#apidoc.element.utility2.db.dbLoad)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbRowGetItem (dbRow, key)](#apidoc.element.utility2.db.dbRowGetItem)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbRowListGetManyByOperator (dbRowList, fieldName, operator, bb)](#apidoc.element.utility2.db.dbRowListGetManyByOperator)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbRowListGetManyByQuery (dbRowList, query, fieldName)](#apidoc.element.utility2.db.dbRowListGetManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbRowProject (dbRow, projection)](#apidoc.element.utility2.db.dbRowProject)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbRowSetId (dbRow, idIndex)](#apidoc.element.utility2.db.dbRowSetId)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbSave (onError)](#apidoc.element.utility2.db.dbSave)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbTableCreateMany (optionsList, onError)](#apidoc.element.utility2.db.dbTableCreateMany)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>dbTableCreateOne (options, onError)](#apidoc.element.utility2.db.dbTableCreateOne)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>jsonCopy (arg)](#apidoc.element.utility2.db.jsonCopy)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>jsonStringifyOrdered (element, replacer, space)](#apidoc.element.utility2.db.jsonStringifyOrdered)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>nop ()](#apidoc.element.utility2.db.nop)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>normalizeDict (dict)](#apidoc.element.utility2.db.normalizeDict)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>normalizeList (list)](#apidoc.element.utility2.db.normalizeList)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>objectSetOverride (arg, overrides, depth, env)](#apidoc.element.utility2.db.objectSetOverride)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>onErrorDefault (error)](#apidoc.element.utility2.db.onErrorDefault)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>onErrorWithStack (onError)](#apidoc.element.utility2.db.onErrorWithStack)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.db.onParallel)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>setTimeoutOnError (onError, error, data)](#apidoc.element.utility2.db.setTimeoutOnError)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>sortCompare (aa, bb)](#apidoc.element.utility2.db.sortCompare)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageClear (onError)](#apidoc.element.utility2.db.storageClear)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageDefer (options, onError)](#apidoc.element.utility2.db.storageDefer)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageGetItem (key, onError)](#apidoc.element.utility2.db.storageGetItem)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageInit ()](#apidoc.element.utility2.db.storageInit)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageKeys (onError)](#apidoc.element.utility2.db.storageKeys)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageLength (onError)](#apidoc.element.utility2.db.storageLength)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageRemoveItem (key, onError)](#apidoc.element.utility2.db.storageRemoveItem)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>storageSetItem (key, value, onError)](#apidoc.element.utility2.db.storageSetItem)
1.  object <span class="apidocSignatureSpan">utility2.</span>db
1.  object <span class="apidocSignatureSpan">utility2.db.</span>dbTableDict
1.  object <span class="apidocSignatureSpan">utility2.db.</span>local
1.  object <span class="apidocSignatureSpan">utility2.db.</span>module
1.  object <span class="apidocSignatureSpan">utility2.db.</span>storageDeferList
1.  string <span class="apidocSignatureSpan">utility2.db.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.db.</span>modeJs
1.  string <span class="apidocSignatureSpan">utility2.db.</span>storageDir

#### [module utility2.db._DbTable](#apidoc.module.utility2.db._DbTable)
1.  [function <span class="apidocSignatureSpan">utility2.db.</span>_DbTable (options)](#apidoc.element.utility2.db._DbTable._DbTable)

#### [module utility2.db._DbTable.prototype](#apidoc.module.utility2.db._DbTable.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_cleanup ()](#apidoc.element.utility2.db._DbTable.prototype._cleanup)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudGetManyByQuery (query)](#apidoc.element.utility2.db._DbTable.prototype._crudGetManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudGetOneById (idDict)](#apidoc.element.utility2.db._DbTable.prototype._crudGetOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudRemoveOneById (idDict, circularList)](#apidoc.element.utility2.db._DbTable.prototype._crudRemoveOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudSetOneById (dbRow)](#apidoc.element.utility2.db._DbTable.prototype._crudSetOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudUpdateOneById (dbRow)](#apidoc.element.utility2.db._DbTable.prototype._crudUpdateOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_persist ()](#apidoc.element.utility2.db._DbTable.prototype._persist)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_save (onError)](#apidoc.element.utility2.db._DbTable.prototype._save)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudCountAll (onError)](#apidoc.element.utility2.db._DbTable.prototype.crudCountAll)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudCountManyByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudCountManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetManyById (idDictList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetManyById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetManyByQuery (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetOneById (idDict, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetOneByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetOneByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveAll (onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveAll)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveManyById (idDictList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveManyByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveOneById (idDict, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudSetManyById (dbRowList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudSetManyById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudSetOneById (dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudSetOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateManyById (dbRowList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateManyByQuery (query, dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyByQuery)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateOneById (dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateOneById)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>drop (onError)](#apidoc.element.utility2.db._DbTable.prototype.drop)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>export (onError)](#apidoc.element.utility2.db._DbTable.prototype.export)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>idIndexCreate (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.idIndexCreate)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>idIndexRemove (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.idIndexRemove)
1.  [function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>ttlSet (ttl, onError)](#apidoc.element.utility2.db._DbTable.prototype.ttlSet)

#### [module utility2.github_crud](#apidoc.module.utility2.github_crud)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentDelete (options, onError)](#apidoc.element.utility2.github_crud.contentDelete)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentGet (options, onError)](#apidoc.element.utility2.github_crud.contentGet)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentPut (options, onError)](#apidoc.element.utility2.github_crud.contentPut)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentPutFile (options, onError)](#apidoc.element.utility2.github_crud.contentPutFile)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentRequest (options, onError)](#apidoc.element.utility2.github_crud.contentRequest)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentTouch (options, onError)](#apidoc.element.utility2.github_crud.contentTouch)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>httpRequest (options, onError)](#apidoc.element.utility2.github_crud.httpRequest)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>nop ()](#apidoc.element.utility2.github_crud.nop)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>onErrorWithStack (onError)](#apidoc.element.utility2.github_crud.onErrorWithStack)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>onNext (options, onError)](#apidoc.element.utility2.github_crud.onNext)
1.  [function <span class="apidocSignatureSpan">utility2.github_crud.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.github_crud.onParallel)
1.  object <span class="apidocSignatureSpan">utility2.</span>github_crud
1.  object <span class="apidocSignatureSpan">utility2.github_crud.</span>local
1.  object <span class="apidocSignatureSpan">utility2.github_crud.</span>module
1.  string <span class="apidocSignatureSpan">utility2.github_crud.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.github_crud.</span>modeJs

#### [module utility2.istanbul](#apidoc.module.utility2.istanbul)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>TextReport (e)](#apidoc.element.utility2.istanbul.TextReport)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>cliRunIstanbul (options)](#apidoc.element.utility2.istanbul.cliRunIstanbul)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>coverageMerge (coverage1, coverage2)](#apidoc.element.utility2.istanbul.coverageMerge)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>coverageReportCreate ()](#apidoc.element.utility2.istanbul.coverageReportCreate)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>fsWriteFileWithMkdirpSync (file, data)](#apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>fsWriteFileWithMkdirpSync2 (file, data)](#apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync2)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>instrumentInPackage (code, file)](#apidoc.element.utility2.istanbul.instrumentInPackage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>instrumentSync (code, file)](#apidoc.element.utility2.istanbul.instrumentSync)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>nop ()](#apidoc.element.utility2.istanbul.nop)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>require (path)](#apidoc.element.utility2.istanbul.require)
1.  object <span class="apidocSignatureSpan">utility2.</span>istanbul
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>_fs
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>collector
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>coverageUtils
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>escodegen
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>esprima
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>estraverse
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>esutils
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>fs
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>handlebars
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>local
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>util
1.  object <span class="apidocSignatureSpan">utility2.istanbul.</span>writer
1.  string <span class="apidocSignatureSpan">utility2.istanbul.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.istanbul.</span>foot.txt
1.  string <span class="apidocSignatureSpan">utility2.istanbul.</span>head.txt
1.  string <span class="apidocSignatureSpan">utility2.istanbul.</span>modeJs
1.  string <span class="apidocSignatureSpan">utility2.istanbul.</span>templateCoverageBadgeSvg

#### [module utility2.istanbul.HtmlReport](#apidoc.module.utility2.istanbul.HtmlReport)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport.HtmlReport)
1.  string <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.</span>TYPE

#### [module utility2.istanbul.HtmlReport.prototype](#apidoc.module.utility2.istanbul.HtmlReport.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>fillTemplate (e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.fillTemplate)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>getPathHtml (e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.getPathHtml)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>standardLinkMapper ()](#apidoc.element.utility2.istanbul.HtmlReport.prototype.standardLinkMapper)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeDetailPage (e, t, n)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeDetailPage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeFiles ( e, t, n, r)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeFiles)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeIndexPage ( e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeIndexPage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeReport ( e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeReport)

#### [module utility2.istanbul.Instrumenter](#apidoc.module.utility2.istanbul.Instrumenter)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter.Instrumenter)

#### [module utility2.istanbul.Instrumenter.prototype](#apidoc.module.utility2.istanbul.Instrumenter.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>arrowBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.arrowBlockConverter)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchIncrementExprAst (e, t , n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchIncrementExprAst)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchLocationFor (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchLocationFor)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchName (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchName)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>conditionalBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.conditionalBranchInjector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>convertToBlock (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.convertToBlock)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>coverFunction (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.coverFunction)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>coverStatement (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.coverStatement)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>endIgnore ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.endIgnore)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>extractCurrentHint (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.extractCurrentHint)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>filterHints (e )](#apidoc.element.utility2.istanbul.Instrumenter.prototype.filterHints)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>findLeaves ( e, n, r, i)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.findLeaves)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>fixColumnPositions (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.fixColumnPositions)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>functionName (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.functionName)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>getPreamble (e, t )](#apidoc.element.utility2.istanbul.Instrumenter.prototype.getPreamble)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>ifBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBlockConverter)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>ifBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBranchInjector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrument (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrument)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrumentASTSync (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentASTSync)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrumentSync (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentSync)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>isUseStrictExpression (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.isUseStrictExpression)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>lastFileCoverage ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.lastFileCoverage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>lastSourceMap ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.lastSourceMap)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>locationsForNodes (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.locationsForNodes)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>logicalExpressionBranchInjector (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>loopBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.loopBlockConverter)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeAddSkip (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddSkip)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeAddType (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddType)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeSkipNode (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeSkipNode)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>paranoidHandlerCheck (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.paranoidHandlerCheck)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>skipInit (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.skipInit)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>skipLeft (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.skipLeft)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>splice (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.splice)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>startIgnore ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.startIgnore)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>statementName (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.statementName)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>switchBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.switchBranchInjector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>switchCaseInjector (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.switchCaseInjector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>withBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.withBlockConverter)

#### [module utility2.istanbul.TextReport](#apidoc.module.utility2.istanbul.TextReport)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>TextReport (e)](#apidoc.element.utility2.istanbul.TextReport.TextReport)
1.  string <span class="apidocSignatureSpan">utility2.istanbul.TextReport.</span>TYPE

#### [module utility2.istanbul.TextReport.prototype](#apidoc.module.utility2.istanbul.TextReport.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.TextReport.prototype.</span>writeReport (e)](#apidoc.element.utility2.istanbul.TextReport.prototype.writeReport)

#### [module utility2.istanbul.collector](#apidoc.module.utility2.istanbul.collector)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.collector.</span>fileCoverageFor (file)](#apidoc.element.utility2.istanbul.collector.fileCoverageFor)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.collector.</span>files ()](#apidoc.element.utility2.istanbul.collector.files)

#### [module utility2.istanbul.coverageUtils](#apidoc.module.utility2.istanbul.coverageUtils)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>addDerivedInfo (e)](#apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfo)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>addDerivedInfoForFile (e)](#apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfoForFile)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>blankSummary ()](#apidoc.element.utility2.istanbul.coverageUtils.blankSummary)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>mergeFileCoverage (e, t)](#apidoc.element.utility2.istanbul.coverageUtils.mergeFileCoverage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>mergeSummaryObjects ()](#apidoc.element.utility2.istanbul.coverageUtils.mergeSummaryObjects)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>removeDerivedInfo (e)](#apidoc.element.utility2.istanbul.coverageUtils.removeDerivedInfo)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>summarizeCoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.summarizeCoverage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>summarizeFileCoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.summarizeFileCoverage)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>toYUICoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.toYUICoverage)

#### [module utility2.istanbul.escodegen](#apidoc.module.utility2.istanbul.escodegen)
1.  boolean <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>browser
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>attachComments (e, t, n)](#apidoc.element.utility2.istanbul.escodegen.attachComments)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>generate (e, t)](#apidoc.element.utility2.istanbul.escodegen.generate)
1.  object <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>FORMAT_DEFAULTS
1.  object <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>FORMAT_MINIFY
1.  object <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>Precedence

#### [module utility2.istanbul.esprima](#apidoc.module.utility2.istanbul.esprima)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>parse (e, t)](#apidoc.element.utility2.istanbul.esprima.parse)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>tokenize (e, n)](#apidoc.element.utility2.istanbul.esprima.tokenize)
1.  object <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>Syntax
1.  string <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>version

#### [module utility2.istanbul.estraverse](#apidoc.module.utility2.istanbul.estraverse)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>Controller ()](#apidoc.element.utility2.istanbul.estraverse.Controller)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>attachComments (e, t, n)](#apidoc.element.utility2.istanbul.estraverse.attachComments)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>cloneEnvironment ()](#apidoc.element.utility2.istanbul.estraverse.cloneEnvironment)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>replace (e, t)](#apidoc.element.utility2.istanbul.estraverse.replace)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>traverse (e, t)](#apidoc.element.utility2.istanbul.estraverse.traverse)
1.  object <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>Syntax
1.  object <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>VisitorKeys
1.  object <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>VisitorOption
1.  string <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>version

#### [module utility2.istanbul.estraverse.Controller.prototype](#apidoc.module.utility2.istanbul.estraverse.Controller.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>__execute (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__execute)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>__initialize (e, t)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__initialize)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>break ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.break)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>current ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.current)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>notify (t)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.notify)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>parents ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.parents)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>path ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.path)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>remove ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.remove)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>replace (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.replace)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>skip ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.skip)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>traverse (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.traverse)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>type ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.type)

#### [module utility2.istanbul.fs](#apidoc.module.utility2.istanbul.fs)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.fs.</span>readFileSync (file)](#apidoc.element.utility2.istanbul.fs.readFileSync)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.fs.</span>readdirSync ()](#apidoc.element.utility2.istanbul.fs.readdirSync)

#### [module utility2.istanbul.handlebars](#apidoc.module.utility2.istanbul.handlebars)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>compile (template)](#apidoc.element.utility2.istanbul.handlebars.compile)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>registerHelper (key, helper)](#apidoc.element.utility2.istanbul.handlebars.registerHelper)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>replace (template, dict, withPrefix)](#apidoc.element.utility2.istanbul.handlebars.replace)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_code ()](#apidoc.element.utility2.istanbul.handlebars.show_code)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_ignores ()](#apidoc.element.utility2.istanbul.handlebars.show_ignores)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_line_execution_counts ()](#apidoc.element.utility2.istanbul.handlebars.show_line_execution_counts)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_lines ()](#apidoc.element.utility2.istanbul.handlebars.show_lines)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_picture ()](#apidoc.element.utility2.istanbul.handlebars.show_picture)

#### [module utility2.istanbul.require](#apidoc.module.utility2.istanbul.require)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.</span>require (path)](#apidoc.element.utility2.istanbul.require.require)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.require.</span>resolve (request)](#apidoc.element.utility2.istanbul.require.resolve)
1.  object <span class="apidocSignatureSpan">utility2.istanbul.require.</span>cache
1.  object <span class="apidocSignatureSpan">utility2.istanbul.require.</span>extensions
1.  object <span class="apidocSignatureSpan">utility2.istanbul.require.</span>main

#### [module utility2.istanbul.util](#apidoc.module.utility2.istanbul.util)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.util.</span>inherits ()](#apidoc.element.utility2.istanbul.util.inherits)

#### [module utility2.istanbul.writer](#apidoc.module.utility2.istanbul.writer)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.writer.</span>write (data)](#apidoc.element.utility2.istanbul.writer.write)
1.  [function <span class="apidocSignatureSpan">utility2.istanbul.writer.</span>writeFile (file, onError)](#apidoc.element.utility2.istanbul.writer.writeFile)

#### [module utility2.jslint](#apidoc.module.utility2.jslint)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.</span>JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.</span>jslintAndPrint (script, file)](#apidoc.element.utility2.jslint.jslintAndPrint)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.</span>jslintEs6 (e, i, s)](#apidoc.element.utility2.jslint.jslintEs6)
1.  number <span class="apidocSignatureSpan">utility2.jslint.</span>errorCounter
1.  object <span class="apidocSignatureSpan">utility2.</span>jslint
1.  object <span class="apidocSignatureSpan">utility2.jslint.</span>CSSLint
1.  object <span class="apidocSignatureSpan">utility2.jslint.</span>local
1.  object <span class="apidocSignatureSpan">utility2.jslint.</span>module
1.  string <span class="apidocSignatureSpan">utility2.jslint.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.jslint.</span>errorText
1.  string <span class="apidocSignatureSpan">utility2.jslint.</span>modeJs

#### [module utility2.jslint.CSSLint](#apidoc.module.utility2.jslint.CSSLint)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>_Reporter (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>addFormatter (e)](#apidoc.element.utility2.jslint.CSSLint.addFormatter)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>addRule (t )](#apidoc.element.utility2.jslint.CSSLint.addRule)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>clearRules ()](#apidoc.element.utility2.jslint.CSSLint.clearRules)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>format (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint.format)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getFormatter (e)](#apidoc.element.utility2.jslint.CSSLint.getFormatter)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getRules ()](#apidoc.element.utility2.jslint.CSSLint.getRules)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getRuleset ()](#apidoc.element.utility2.jslint.CSSLint.getRuleset)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>hasFormat (e)](#apidoc.element.utility2.jslint.CSSLint.hasFormat)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>verify (t, r)](#apidoc.element.utility2.jslint.CSSLint.verify)
1.  object <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>Util
1.  object <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>_listeners
1.  object <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>errors
1.  string <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>version

#### [module utility2.jslint.CSSLint._Reporter.prototype](#apidoc.module.utility2.jslint.CSSLint._Reporter.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>constructor (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>error (e, t, n, r )](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.error)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>info (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.info)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>report (e, t , n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.report)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>rollupError (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupError)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>rollupWarn (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupWarn)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>stat (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.stat)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>warn (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.warn)

#### [module utility2.jslint.JSLINT](#apidoc.module.utility2.jslint.JSLINT)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.</span>JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT.JSLINT)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>color (e)](#apidoc.element.utility2.jslint.JSLINT.color)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>data ( )](#apidoc.element.utility2.jslint.JSLINT.data)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>error_report (e)](#apidoc.element.utility2.jslint.JSLINT.error_report)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>jslint (t, n)](#apidoc.element.utility2.jslint.JSLINT.jslint)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>properties_report (e)](#apidoc.element.utility2.jslint.JSLINT.properties_report)
1.  [function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>report (e)](#apidoc.element.utility2.jslint.JSLINT.report)
1.  object <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>errors
1.  object <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>property
1.  object <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>tree
1.  string <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>edition
1.  string <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>properties

#### [module utility2.sjcl](#apidoc.module.utility2.sjcl)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.</span>decrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.decrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.</span>encrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.encrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.</span>prng (e)](#apidoc.element.utility2.sjcl.prng)
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>bitArray
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>cipher
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>codec
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>exception
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>hash
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>json
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>keyexchange
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>misc
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>mode
1.  object <span class="apidocSignatureSpan">utility2.sjcl.</span>random
1.  string <span class="apidocSignatureSpan">utility2.sjcl.</span>__dirname

#### [module utility2.sjcl.bitArray](#apidoc.module.utility2.sjcl.bitArray)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>P (e, t, n, r)](#apidoc.element.utility2.sjcl.bitArray.P)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>bitLength (e)](#apidoc.element.utility2.sjcl.bitArray.bitLength)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>bitSlice (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.bitSlice)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>byteswapM (e)](#apidoc.element.utility2.sjcl.bitArray.byteswapM)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>clamp (e, t)](#apidoc.element.utility2.sjcl.bitArray.clamp)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>concat (e, t)](#apidoc.element.utility2.sjcl.bitArray.concat)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>equal (e, t)](#apidoc.element.utility2.sjcl.bitArray.equal)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>extract (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.extract)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>getPartial (e)](#apidoc.element.utility2.sjcl.bitArray.getPartial)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>l (e, t)](#apidoc.element.utility2.sjcl.bitArray.l)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>partial (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.partial)

#### [module utility2.sjcl.cipher](#apidoc.module.utility2.sjcl.cipher)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.cipher.</span>aes (e)](#apidoc.element.utility2.sjcl.cipher.aes)

#### [module utility2.sjcl.cipher.aes.prototype](#apidoc.module.utility2.sjcl.cipher.aes.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>D ()](#apidoc.element.utility2.sjcl.cipher.aes.prototype.D)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>decrypt ( e)](#apidoc.element.utility2.sjcl.cipher.aes.prototype.decrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>encrypt (e)](#apidoc.element.utility2.sjcl.cipher.aes.prototype.encrypt)
1.  object <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>k

#### [module utility2.sjcl.exception](#apidoc.module.utility2.sjcl.exception)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>bug (e)](#apidoc.element.utility2.sjcl.exception.bug)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>corrupt (e)](#apidoc.element.utility2.sjcl.exception.corrupt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>invalid (e)](#apidoc.element.utility2.sjcl.exception.invalid)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>notReady (e)](#apidoc.element.utility2.sjcl.exception.notReady)

#### [module utility2.sjcl.hash](#apidoc.module.utility2.sjcl.hash)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.hash.</span>sha256 (e)](#apidoc.element.utility2.sjcl.hash.sha256)

#### [module utility2.sjcl.hash.sha256.prototype](#apidoc.module.utility2.sjcl.hash.sha256.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>D ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.D)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>finalize ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.finalize)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>reset ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.reset)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>update ( e)](#apidoc.element.utility2.sjcl.hash.sha256.prototype.update)
1.  number <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>blockSize
1.  object <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>N
1.  object <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>b

#### [module utility2.sjcl.json](#apidoc.module.utility2.sjcl.json)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>X (e, t, n, r)](#apidoc.element.utility2.sjcl.json.X)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>Y (e, t, n, r)](#apidoc.element.utility2.sjcl.json.Y)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>decode (e)](#apidoc.element.utility2.sjcl.json.decode)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>decrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.json.decrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>e ( e, t, n)](#apidoc.element.utility2.sjcl.json.e)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>ea (e, t)](#apidoc.element.utility2.sjcl.json.ea)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>encode (e)](#apidoc.element.utility2.sjcl.json.encode)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>encrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.json.encrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>fa (e, t)](#apidoc.element.utility2.sjcl.json.fa)
1.  object <span class="apidocSignatureSpan">utility2.sjcl.json.</span>defaults

#### [module utility2.sjcl.misc](#apidoc.module.utility2.sjcl.misc)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>cachedPbkdf2 (e, t)](#apidoc.element.utility2.sjcl.misc.cachedPbkdf2)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>hmac (e, t)](#apidoc.element.utility2.sjcl.misc.hmac)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>pbkdf2 (e, t, n, r, i)](#apidoc.element.utility2.sjcl.misc.pbkdf2)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>scrypt (password, salt, N, r, p, length, Prff)](#apidoc.element.utility2.sjcl.misc.scrypt)
1.  object <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>ca

#### [module utility2.sjcl.misc.hmac.prototype](#apidoc.module.utility2.sjcl.misc.hmac.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>digest ()](#apidoc.element.utility2.sjcl.misc.hmac.prototype.digest)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>encrypt (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.encrypt)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>mac (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.mac)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>reset ()](#apidoc.element.utility2.sjcl.misc.hmac.prototype.reset)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>update (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.update)

#### [module utility2.sjcl.prng](#apidoc.module.utility2.sjcl.prng)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.</span>prng (e)](#apidoc.element.utility2.sjcl.prng.prng)

#### [module utility2.sjcl.prng.prototype](#apidoc.module.utility2.sjcl.prng.prototype)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>U (e)](#apidoc.element.utility2.sjcl.prng.prototype.U)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>aa ()](#apidoc.element.utility2.sjcl.prng.prototype.aa)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>addEntropy (e, t, n)](#apidoc.element.utility2.sjcl.prng.prototype.addEntropy)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>addEventListener (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.addEventListener)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>ba (e)](#apidoc.element.utility2.sjcl.prng.prototype.ba)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>da (e)](#apidoc.element.utility2.sjcl.prng.prototype.da)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>getProgress ( e)](#apidoc.element.utility2.sjcl.prng.prototype.getProgress)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>isReady (e)](#apidoc.element.utility2.sjcl.prng.prototype.isReady)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>randomWords (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.randomWords)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>removeEventListener (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.removeEventListener)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>setDefaultParanoia (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.setDefaultParanoia)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>startCollectors ()](#apidoc.element.utility2.sjcl.prng.prototype.startCollectors)
1.  [function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>stopCollectors ()](#apidoc.element.utility2.sjcl.prng.prototype.stopCollectors)

#### [module utility2.uglifyjs](#apidoc.module.utility2.uglifyjs)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>array_to_hash (e)](#apidoc.element.utility2.uglifyjs.array_to_hash)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_add_scope (e)](#apidoc.element.utility2.uglifyjs.ast_add_scope)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_lift_variables (e)](#apidoc.element.utility2.uglifyjs.ast_lift_variables)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_mangle (e, t)](#apidoc.element.utility2.uglifyjs.ast_mangle)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_squeeze (e, t)](#apidoc.element.utility2.uglifyjs.ast_squeeze)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_walker ()](#apidoc.element.utility2.uglifyjs.ast_walker)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>curry (e)](#apidoc.element.utility2.uglifyjs.curry)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>gen_code (e, t)](#apidoc.element.utility2.uglifyjs.gen_code)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_alphanumeric_char (e)](#apidoc.element.utility2.uglifyjs.is_alphanumeric_char)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_identifier_char (e)](#apidoc.element.utility2.uglifyjs.is_identifier_char)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_identifier_start (e)](#apidoc.element.utility2.uglifyjs.is_identifier_start)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>make_string (e, t)](#apidoc.element.utility2.uglifyjs.make_string)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>member (e, t)](#apidoc.element.utility2.uglifyjs.member)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>parse (e, t, n)](#apidoc.element.utility2.uglifyjs.parse)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>set_logger (e)](#apidoc.element.utility2.uglifyjs.set_logger)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>slice (e, t)](#apidoc.element.utility2.uglifyjs.slice)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>split_lines (e, t)](#apidoc.element.utility2.uglifyjs.split_lines)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>tokenizer (e)](#apidoc.element.utility2.uglifyjs.tokenizer)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>uglify (code, file)](#apidoc.element.utility2.uglifyjs.uglify)
1.  object <span class="apidocSignatureSpan">utility2.</span>uglifyjs
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ATOMIC_START_TOKEN
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>KEYWORDS
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>KEYWORDS_ATOM
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>OPERATORS
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>PRECEDENCE
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>RESERVED_WORDS
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>local
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.</span>module
1.  string <span class="apidocSignatureSpan">utility2.uglifyjs.</span>__dirname
1.  string <span class="apidocSignatureSpan">utility2.uglifyjs.</span>modeJs

#### [module utility2.uglifyjs.MAP](#apidoc.module.utility2.uglifyjs.MAP)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP.MAP)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.MAP.</span>at_top (e)](#apidoc.element.utility2.uglifyjs.MAP.at_top)
1.  [function <span class="apidocSignatureSpan">utility2.uglifyjs.MAP.</span>splice (e)](#apidoc.element.utility2.uglifyjs.MAP.splice)
1.  object <span class="apidocSignatureSpan">utility2.uglifyjs.MAP.</span>skip



# <a name="apidoc.module.utility2"></a>[module utility2](#apidoc.module.utility2)

#### <a name="apidoc.element.utility2.Blob"></a>[function <span class="apidocSignatureSpan">utility2.</span>Blob (array, options)](#apidoc.element.utility2.Blob)
- description and source-code
```javascript
Blob = function (array, options) {
<span class="apidocCodeCommentSpan">  /*
   * this function will create a node-compatible Blob instance
   */
</span>    this.bff = local.bufferConcat(array);
    this.type = options && options.type;
}
```
- example usage
```shell
...
};

local.testCase_FormData_default = function (options, onError) {
/*
 * this function will test FormData's default handling-behavior
 */
    options = {};
    options.blob1 = new local.Blob(['aa', 'bb', '\u1234 ', 0]);
    options.blob2 = new local.Blob(['aa', 'bb', '\u1234 ', 0], {
        type: 'text/plain; charset=utf-8'
    });
    options.data = new local.FormData();
    options.data.append('text1', 'aabb\u1234 0');
    // test file-upload handling-behavior
    options.data.append('file1', options.blob1);
...
```

#### <a name="apidoc.element.utility2.FormData"></a>[function <span class="apidocSignatureSpan">utility2.</span>FormData ()](#apidoc.element.utility2.FormData)
- description and source-code
```javascript
FormData = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will create a serverLocal-compatible FormData instance
 * https://xhr.spec.whatwg.org/#dom-formdata
 * The FormData(form) constructor must run these steps:
 * 1. Let fd be a new FormData object.
 * 2. If form is given, set fd's entries to the result
 *    of constructing the form data set for form. (not implemented)
 * 3. Return fd.
 */
</span>    this.entryList = [];
}
```
- example usage
```shell
...
});
if (options.errorValidate) {
    return;
}
// init options-defaults
local.objectSetDefault(options, {
    inForm: isMultipartFormData
        ? new local.FormData()
        : '',
    inHeader: {},
    inPath: self._path,
    inQuery: '',
    headers: {},
    method: self._method,
    responseType: self.produces &&
...
```

#### <a name="apidoc.element.utility2.Module"></a>[function <span class="apidocSignatureSpan">utility2.</span>Module (id, parent)](#apidoc.element.utility2.Module)
- description and source-code
```javascript
function Module(id, parent) {
  this.id = id;
  this.exports = {};
  this.parent = parent;
  if (parent && parent.children) {
    parent.children.push(this);
  }

  this.filename = null;
  this.loaded = false;
  this.children = [];
}
```
- example usage
```shell
...
// init example.js
tmp = process.cwd() + '/example.js';
// jslint script
local.jslintAndPrintConditional(script, tmp);
// cover script
script = local.istanbulInstrumentInPackage(script, tmp);
// init module
module = require.cache[tmp] = new local.Module(tmp);
// load script into module
module._compile(script, tmp);
// init exports
module.exports.utility2 = local;
module.exports[local.env.npm_package_nameAlias] = global.utility2_moduleExports;
// init assets
local.objectSetOverride(local.assetsDict, module.exports.assetsDict);
...
```

#### <a name="apidoc.element.utility2.__require"></a>[function <span class="apidocSignatureSpan">utility2.</span>__require (path)](#apidoc.element.utility2.__require)
- description and source-code
```javascript
function require(path) {
  try {
    exports.requireDepth += 1;
    return self.require(path);
  } finally {
    exports.requireDepth -= 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2._http.IncomingMessage"></a>[function <span class="apidocSignatureSpan">utility2.</span>_http.IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage)
- description and source-code
```javascript
_http.IncomingMessage = function (xhr) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_http_incomingmessage
 * An IncomingMessage object is created by http.Server or http.ClientRequest
 * and passed as the first argument to the 'request' and 'response' event respectively
 */
</span>    this.headers = {};
    this.httpVersion = '1.1';
    this.method = xhr.method;
    this.onEvent = document.createDocumentFragment();
    this.readable = true;
    this.url = xhr.url;
}
```
- example usage
```shell
...
        self.ended = true;
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse"></a>[function <span class="apidocSignatureSpan">utility2.</span>_http.ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse)
- description and source-code
```javascript
_http.ServerResponse = function (onResponse) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_class_http_serverresponse
 * This object is created internally by a HTTP server--not by the user
 */
</span>    this.chunkList = [];
    this.headers = {};
    this.onEvent = document.createDocumentFragment();
    this.onResponse = onResponse;
    this.statusCode = 200;
}
```
- example usage
```shell
...
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};

local._middlewareError = function (error, request, response) {
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest"></a>[function <span class="apidocSignatureSpan">utility2.</span>_http.XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest)
- description and source-code
```javascript
_http.XMLHttpRequest = function () {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#XMLHttpRequest()
 * The constructor initiates an XMLHttpRequest
 */
</span>    var xhr;
    xhr = this;
    ['onError', 'onResponse'].forEach(function (key) {
        xhr[key] = xhr[key].bind(xhr);
    });
    xhr.headers = {};
    xhr.onLoadList = [];
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState
    xhr.readyState = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/response
    xhr.response = null;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseText
    xhr.responseText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseType
    xhr.responseType = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/status
    xhr.status = xhr.statusCode = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/statusText
    xhr.statusText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/timeout
    xhr.timeout = local.timeoutDefault;
}
```
- example usage
```shell
...
        /*
* this function will send an ajax-request with error-handling and timeout
*/
   var timerTimeout, tmp, xhr;
   onError = local.onErrorWithStack(onError);
   // init modeServerLocal
   if (!local.env.npm_config_mode_backend && local._serverLocalUrlTest(options.url)) {
       xhr = new local._http.XMLHttpRequest();
   }
   // init xhr
   xhr = xhr || (local.modeJs === 'browser'
       ? new local.global.XMLHttpRequest()
       : new local._http.XMLHttpRequest());
   // debug xhr
   local._debugXhr = xhr;
...
```

#### <a name="apidoc.element.utility2._middleware"></a>[function <span class="apidocSignatureSpan">utility2.</span>_middleware (request, response, nextMiddleware)](#apidoc.element.utility2._middleware)
- description and source-code
```javascript
_middleware = function (request, response, nextMiddleware) {
    var options;
    options = {};
    local.onNext(options, function (error) {
        // recurse with next middleware in middlewareList
        if (options.modeNext < self.middlewareList.length) {
            // run the sub-middleware
            self.middlewareList[options.modeNext](
                request,
                response,
                options.onNext
            );
            return;
        }
        // default to nextMiddleware
        nextMiddleware(error);
    });
    options.modeNext = -1;
    options.onNext();
}
```
- example usage
```shell
...
    local.middlewareInit,
    local.middlewareForwardProxy,
    local.middlewareAssetsCached,
    local._middlewareJsonpStateInit
]);
// 1. create server from local._middleware
local.serverLocalRequestHandler = function (request, response) {
    local._middleware(request, response, function (error) {
        local._middlewareError(error, request, response);
    });
};
local.global.utility2_serverHttp1 = local.http.createServer(
    local.serverLocalRequestHandler
);
// 2. start server on local.env.PORT
...
```

#### <a name="apidoc.element.utility2._middlewareError"></a>[function <span class="apidocSignatureSpan">utility2.</span>_middlewareError (error, request, response)](#apidoc.element.utility2._middlewareError)
- description and source-code
```javascript
_middlewareError = function (error, request, response) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will handle errors
 */
</span>    // if error occurred, then respond with '500 Internal Server Error',
    // else respond with '404 Not Found'
    local.serverRespondDefault(request, response, error
        ? (error.statusCode >= 400 && error.statusCode < 600
            ? error.statusCode
            : 500)
        : 404, error);
}
```
- example usage
```shell
...
    local.middlewareForwardProxy,
    local.middlewareAssetsCached,
    local._middlewareJsonpStateInit
]);
// 1. create server from local._middleware
local.serverLocalRequestHandler = function (request, response) {
    local._middleware(request, response, function (error) {
        local._middlewareError(error, request, response);
    });
};
local.global.utility2_serverHttp1 = local.http.createServer(
    local.serverLocalRequestHandler
);
// 2. start server on local.env.PORT
console.log('server listening on http-port ' + local.env.PORT);
...
```

#### <a name="apidoc.element.utility2._middlewareJsonpStateInit"></a>[function <span class="apidocSignatureSpan">utility2.</span>_middlewareJsonpStateInit (request, response, nextMiddleware)](#apidoc.element.utility2._middlewareJsonpStateInit)
- description and source-code
```javascript
_middlewareJsonpStateInit = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will
 * serve the browser-state wrapped in the given jsonp-callback
 */
</span>    var state;
    if (request._stateInit || (request.urlParsed &&
            request.urlParsed.pathname === '/jsonp.utility2._stateInit')) {
        state = { utility2: { assetsDict: {
            '/assets.index.template.html':
                local.assetsDict['/assets.index.template.html']
        } } };
        local.objectSetDefault(state, { utility2: { env: {
            NODE_ENV: local.env.NODE_ENV,
            npm_config_mode_backend: local.env.npm_config_mode_backend,
            npm_package_description: local.env.npm_package_description,
            npm_package_homepage: local.env.npm_package_homepage,
            npm_package_name: local.env.npm_package_name,
            npm_package_nameAlias: local.env.npm_package_nameAlias,
            npm_package_version: local.env.npm_package_version
        } } }, 3);
        if (request._stateInit) {
            return state;
        }
        response.end(
            request.urlParsed.query.callback + '(' + JSON.stringify(state) + ');'
        );
        return;
    }
    nextMiddleware();
}
```
- example usage
```shell
...
*/\n\
';
/* jslint-ignore-end */
case 'local._stateInit':
    script = local.assetsDict['/assets.utility2.rollup.content.js'].replace(
        '/* utility2.rollup.js content */',
        key + '(' + JSON.stringify(
            local._middlewareJsonpStateInit({ _stateInit: true })
        ) + ');'
    );
    break;
case '/assets.lib.js':
    script = local.assetsDict[
        '/assets.' + local.env.npm_package_nameAlias + '.js'
    ];
...
```

#### <a name="apidoc.element.utility2._serverLocalUrlTest"></a>[function <span class="apidocSignatureSpan">utility2.</span>_serverLocalUrlTest ()](#apidoc.element.utility2._serverLocalUrlTest)
- description and source-code
```javascript
_serverLocalUrlTest = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
local.ajax = function (options, onError) {
/*
 * this function will send an ajax-request with error-handling and timeout
 */
    var timerTimeout, tmp, xhr;
    onError = local.onErrorWithStack(onError);
    // init modeServerLocal
    if (!local.env.npm_config_mode_backend && local._serverLocalUrlTest(options.url)) {
        xhr = new local._http.XMLHttpRequest();
    }
    // init xhr
    xhr = xhr || (local.modeJs === 'browser'
        ? new local.global.XMLHttpRequest()
        : new local._http.XMLHttpRequest());
    // debug xhr
...
```

#### <a name="apidoc.element.utility2._stateInit"></a>[function <span class="apidocSignatureSpan">utility2.</span>_stateInit (options)](#apidoc.element.utility2._stateInit)
- description and source-code
```javascript
_stateInit = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will init the state-options
 */
</span>    local.objectSetOverride(local, options, 10);
}
```
- example usage
```shell
...
switch (local.modeJs) {



// run browser js-env code - post-init
case 'browser':
    // init state
    local.utility2._stateInit({});
    break;



// run node js-env code - post-init
case 'node':
    // init assets.lib.rollup.js
...
```

#### <a name="apidoc.element.utility2._testRunBefore"></a>[function <span class="apidocSignatureSpan">utility2.</span>_testRunBefore ()](#apidoc.element.utility2._testRunBefore)
- description and source-code
```javascript
_testRunBefore = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
local.modeTest = local.modeTest || local.env.npm_config_mode_test;
if (!(local.modeTest || options.modeTest)) {
    return;
}
if (!options.testRunBeforeDone) {
    options.testRunBeforeTimer = options.testRunBeforeTimer ||
        setTimeout(function () {
            local._testRunBefore();
            local.onReadyAfter(function () {
                options.testRunBeforeDone = true;
                local.testRunDefault(options);
            });
        });
    return;
}
...
```

#### <a name="apidoc.element.utility2.ajax"></a>[function <span class="apidocSignatureSpan">utility2.</span>ajax (options, onError)](#apidoc.element.utility2.ajax)
- description and source-code
```javascript
ajax = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will send an ajax-request with error-handling and timeout
 */
</span>    var timerTimeout, tmp, xhr;
    onError = local.onErrorWithStack(onError);
    // init modeServerLocal
    if (!local.env.npm_config_mode_backend && local._serverLocalUrlTest(options.url)) {
        xhr = new local._http.XMLHttpRequest();
    }
    // init xhr
    xhr = xhr || (local.modeJs === 'browser'
        ? new local.global.XMLHttpRequest()
        : new local._http.XMLHttpRequest());
    // debug xhr
    local._debugXhr = xhr;
    // init options
    local.objectSetOverride(xhr, options);
    // init headers
    xhr.headers = {};
    Object.keys(options.headers || {}).forEach(function (key) {
        xhr.headers[key.toLowerCase()] = options.headers[key];
    });
    // init method
    xhr.method = xhr.method || 'GET';
    // init timeout
    xhr.timeout = xhr.timeout || local.timeoutDefault;
    // init timerTimeout
    timerTimeout = local.onTimeout(function (error) {
        xhr.error = xhr.error || error;
        xhr.abort();
        // cleanup requestStream and responseStream
        local.streamListCleanup([xhr.requestStream, xhr.responseStream]);
    }, xhr.timeout, 'ajax ' + xhr.method + ' ' + xhr.url);
    // init event handling
    xhr.onEvent = function (event) {
        // init statusCode
        xhr.statusCode = xhr.status;
        switch (event.type) {
        case 'abort':
        case 'error':
        case 'load':
            // do not run more than once
            if (xhr.done) {
                return;
            }
            xhr.done = true;
            // cleanup timerTimeout
            clearTimeout(timerTimeout);
            // cleanup requestStream and responseStream
            setTimeout(function () {
                local.streamListCleanup([xhr.requestStream, xhr.responseStream]);
            });
            // decrement ajaxProgressCounter
            local.ajaxProgressCounter -= 1;
            // handle abort or error event
            if (!xhr.error &&
                    (event.type === 'abort' ||
                    event.type === 'error' ||
                    xhr.statusCode >= 400)) {
                xhr.error = new Error(event.type);
            }
            // handle completed xhr request
            if (xhr.readyState === 4) {
                // debug xhr
                if (xhr.modeDebug) {
                    console.log(new Date().toISOString(
                    ) + ' ajax-response ' + JSON.stringify({
                        statusCode: xhr.statusCode,
                        method: xhr.method,
                        url: xhr.url,
                        responseText: local.tryCatchOnError(function () {
                            return xhr.responseText.slice(0, 256);
                        }, local.nop)
                    }));
                }
                // handle string data
                if (xhr.error) {
                    // debug statusCode
                    xhr.error.statusCode = xhr.statusCode;
                    // debug statusCode / method / url
                    tmp = local.modeJs + ' - ' + xhr.statusCode + ' ' + xhr.method +
                        ' ' + xhr.url + '\n';
                    // try to debug responseText
                    local.tryCatchOnError(function () {
                        tmp += '    ' + JSON.stringify(xhr.responseText.slice(0, 256) +
                            '...') + '\n';
                    }, local.nop);
                    local.errorMessagePrepend(xhr.error, tmp);
                }
            }
            onError(xhr.error, xhr);
            break;
        }
        local.ajaxProgressUpdate();
    };
    // increment ajaxProgressCounter
    local.ajaxProgressCounter += 1;
    xhr.addEventListener('abort', xhr.onEvent);
    xhr.addEventListener('error', xhr.onEvent);
    xhr.addEventListener('load', xhr.onEvent);
    xhr.addEventListener('loadstart', local.ajaxProgressUpdate);
    xhr.addEventListener('progress', local.ajaxProgressUpdate);
    xhr.upload.addEventListener('progress', local.aja ...
```
- example usage
```shell
...
    case 'browser':
local.testCase_ajax_200 = function (options, onError) {
/*
 * this function will test ajax's "200 ok" handling-behavior
 */
    options = {};
    // test ajax-path 'assets.hello'
    local.ajax({ url: 'assets.hello' }, function (error, xhr) {
        local.tryCatchOnError(function () {
            // validate no error occurred
            local.assert(!error, error);
            // validate data
            options.data = xhr.responseText;
            local.assert(options.data === 'hello', options.data);
            onError();
...
```

#### <a name="apidoc.element.utility2.ajaxProgressUpdate"></a>[function <span class="apidocSignatureSpan">utility2.</span>ajaxProgressUpdate ()](#apidoc.element.utility2.ajaxProgressUpdate)
- description and source-code
```javascript
ajaxProgressUpdate = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will update ajaxProgress
 */
</span>    var ajaxProgressDiv1;
    ajaxProgressDiv1 = local.modeJs === 'browser' &&
        document.querySelector('#ajaxProgressDiv1');
    if (!ajaxProgressDiv1) {
        return;
    }
    // init ajaxProgressDiv1StyleBackground
    local.ajaxProgressDiv1StyleBackground = local.ajaxProgressDiv1StyleBackground ||
        ajaxProgressDiv1.style.background;
    // show ajaxProgress
    if (ajaxProgressDiv1.style.background === 'transparent') {
        ajaxProgressDiv1.style.background = local.ajaxProgressDiv1StyleBackground;
    }
    // cleanup timerTimeout
    clearTimeout(local.timerTimeoutAjaxProgressHide);
    // increment ajaxProgress
    if (local.ajaxProgressCounter > 0) {
        // this algorithm will indefinitely increment the ajaxProgressBar
        // with successively smaller increments without ever reaching 100%
        local.ajaxProgressState += 1;
        ajaxProgressDiv1.style.width =
            100 - 75 * Math.exp(-0.125 * local.ajaxProgressState) + '%';
        return;
    }
    // finish ajaxProgress
    ajaxProgressDiv1.style.width = '100%';
    // hide ajaxProgress
    local.timerTimeoutAjaxProgressHide = setTimeout(function () {
        ajaxProgressDiv1.style.background = 'transparent';
        // reset ajaxProgress
        setTimeout(function () {
            local.ajaxProgressCounter = 0;
            local.ajaxProgressState = 0;
            ajaxProgressDiv1.style.width = '25%';
        }, 500);
    }, 1500);
}
```
- example usage
```shell
...
                }, local.nop);
                local.errorMessagePrepend(xhr.error, tmp);
            }
        }
        onError(xhr.error, xhr);
        break;
    }
    local.ajaxProgressUpdate();
};
// increment ajaxProgressCounter
local.ajaxProgressCounter += 1;
xhr.addEventListener('abort', xhr.onEvent);
xhr.addEventListener('error', xhr.onEvent);
xhr.addEventListener('load', xhr.onEvent);
xhr.addEventListener('loadstart', local.ajaxProgressUpdate);
...
```

#### <a name="apidoc.element.utility2.apidocCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>apidocCreate (options)](#apidoc.element.utility2.apidocCreate)
- description and source-code
```javascript
apidocCreate = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will create the apidoc from options.dir
 */
</span>    var elementCreate, module, moduleMain, readExample, tmp, trimLeft;
    elementCreate = function (module, prefix, key) {
    /*
     * this function will create the apidoc-element in the given module
     */
        var element;
        element = {};
        element.moduleName = prefix.split('.');
        // handle case where module is a function
        if (element.moduleName.slice(-1)[0] === key) {
            element.moduleName.pop();
        }
        element.moduleName = element.moduleName.join('.');
        element.id = encodeURIComponent('apidoc.element.' + prefix + '.' + key);
        element.typeof = typeof module[key];
        element.name = (element.typeof + ' <span class="apidocSignatureSpan">' +
            element.moduleName + '.</span>' + key)
            // handle case where module is a function
            .replace('>.<', '><');
        if (element.typeof !== 'function') {
            return element;
        }
        // init source
        element.source = 'n/a';
        // bug-workaround - catch and ignore error
        // "Function.prototype.toString is not generic"
        try {
            element.source = trimLeft(module[key].toString());
        } catch (ignore) {
        }
        if (element.source.length > 4096) {
            element.source = element.source.slice(0, 4096).trimRight() + ' ...';
        }
        element.source = (options.template === local.templateApidocHtml
            ? local.stringHtmlSafe(element.source)
            : element.source)
            .replace((/\([\S\s]*?\)/), function (match0) {
                // init signature
                element.signature = match0
                    .replace((/ *?\/\*[\S\s]*?\*\/ */g), '')
                    .replace((/,/g), ', ')
                    .replace((/\s+/g), ' ');
                return element.signature;
            })
            .replace(
                (/( *?\/\*[\S\s]*?\*\/\n)/),
                '<span class="apidocCodeCommentSpan">$1</span>'
            )
            .replace((/^function \(/), key + ' = function (');
        // init example
        options.exampleList.some(function (example) {
            example.replace(
                new RegExp('((?:\n.*?){8}\\.)(' + key + ')(\\((?:.*?\n){8})'),
                function (match0, match1, match2, match3) {
                    element.example = '...' + trimLeft(
                        options.template === local.templateApidocHtml
                            ?  local.stringHtmlSafe(match1) +
                                '<span class="apidocCodeKeywordSpan">' +
                                local.stringHtmlSafe(match2) +
                                '</span>' +
                                local.stringHtmlSafe(match3)
                            : match0
                    ).trimRight() + '\n...';
                }
            );
            return element.example;
        });
        element.example = element.example || 'n/a';
        return element;
    };
    readExample = function (file) {
    /*
     * this function will read the example from the given file
     */
        try {
            return ('\n\n\n\n\n\n\n\n' +
                local.fs.readFileSync(local.path.resolve(options.dir, file), 'utf8') +
                '\n\n\n\n\n\n\n\n').replace((/\r\n*/g), '\n');
        } catch (errorCaught) {
            return '';
        }
    };
    trimLeft = function (text) {
    /*
     * this function will normalize the whitespace around the text
     */
        var whitespace;
        whitespace = '';
        text.trim().replace((/^ */gm), function (match0) {
            if (!whitespace || match0.length < whitespace.length) {
                whitespace = match0;
            }
        });
        text = text.replace(new RegExp('^' + whitespace, 'gm'), '');
        // enforce 128 character column limit
        text = text.replace((/^.{128}[^\\\n]+/gm), function (match0) {
            return match0.replace((/(.{128}(?:\b|\w+))/g), '$1\n').trimRight();
        });
        r ...
```
- example usage
```shell
...
local.fs = require('fs');
local.path = require('path');
// run the cli
if (module !== require.main || local.global.utility2_rollup) {
    break;
}
// jslint files
process.stdout.write(local.apidocCreate({
    dir: process.argv[2],
    modulePathList: module.paths,
    template: process.argv[3] === '--markdown'
        ? local.templateApidocMd
        : local.templateApidocHtml
}));
break;
...
```

#### <a name="apidoc.element.utility2.assert"></a>[function <span class="apidocSignatureSpan">utility2.</span>assert (passed, message)](#apidoc.element.utility2.assert)
- description and source-code
```javascript
assert = function (passed, message) {
<span class="apidocCodeCommentSpan">/*
 * this function will throw the error message if passed is falsey
 */
</span>    var error;
    if (passed) {
        return;
    }
    error = message && message.message
        // if message is an error-object, then leave it as is
        ? message
        : new Error(typeof message === 'string'
            // if message is a string, then leave it as is
            ? message
            // else JSON.stringify message
            : JSON.stringify(message));
    throw error;
}
```
- example usage
```shell
...
 * this function will test ajax's "200 ok" handling-behavior
 */
    options = {};
    // test ajax-path 'assets.hello'
    local.ajax({ url: 'assets.hello' }, function (error, xhr) {
        local.tryCatchOnError(function () {
            // validate no error occurred
            local.assert(!error, error);
            // validate data
            options.data = xhr.responseText;
            local.assert(options.data === 'hello', options.data);
            onError();
        }, onError);
    });
};
...
```

#### <a name="apidoc.element.utility2.assertJsonEqual"></a>[function <span class="apidocSignatureSpan">utility2.</span>assertJsonEqual (aa, bb)](#apidoc.element.utility2.assertJsonEqual)
- description and source-code
```javascript
assertJsonEqual = function (aa, bb) {
<span class="apidocCodeCommentSpan">/*
 * this function will assert
 * utility2.jsonStringifyOrdered(aa) === JSON.stringify(bb)
 */
</span>    aa = local.jsonStringifyOrdered(aa);
    bb = JSON.stringify(bb);
    local.assert(aa === bb, [aa, bb]);
}
```
- example usage
```shell
...
 * this function will test ajax's assets handling-behavior
 */
    options = { url: 'package.json' };
    local.ajax(options, function (error, xhr) {
        // validate no error occurred
        local.assert(!error, error);
        // validate statusCode
        local.assertJsonEqual(xhr.statusCode, 200);
        // validate responseText
        local.assert((/"name": "utility2"/).test(xhr.responseText), xhr.responseText);
        onError();
    });
};

local.testCase_ajax_error = function (options, onError) {
...
```

#### <a name="apidoc.element.utility2.assertJsonNotEqual"></a>[function <span class="apidocSignatureSpan">utility2.</span>assertJsonNotEqual (aa, bb)](#apidoc.element.utility2.assertJsonNotEqual)
- description and source-code
```javascript
assertJsonNotEqual = function (aa, bb) {
<span class="apidocCodeCommentSpan">/*
 * this function will assert
 * utility2.jsonStringifyOrdered(aa) !== JSON.stringify(bb)
 */
</span>    aa = local.jsonStringifyOrdered(aa);
    bb = JSON.stringify(bb);
    local.assert(aa !== bb, [aa, bb]);
}
```
- example usage
```shell
...
    options.list.forEach(function (aa, ii) {
        options.list.forEach(function (bb, jj) {
            if (ii === jj) {
                // test assertJsonEqual's handling-behavior
                local.assertJsonEqual(aa, bb);
            } else {
                // test assertJsonNotEqual's handling-behavior
                local.assertJsonNotEqual(aa, bb);
            }
        });
    });
    onError();
};

local.testCase_base64Xxx_default = function (options, onError) {
...
```

#### <a name="apidoc.element.utility2.base64FromBuffer"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64FromBuffer (bff)](#apidoc.element.utility2.base64FromBuffer)
- description and source-code
```javascript
base64FromBuffer = function (bff) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/Add-ons/Code_snippets/StringView#The_code
 * this function will convert the Uint8Array-bff to base64-encoded-text
 */
</span>    var ii, mod3, text, uint24, uint6ToB64;
    text = '';
    uint24 = 0;
    uint6ToB64 = function (uint6) {
        return uint6 < 26
            ? uint6 + 65
            : uint6 < 52
            ? uint6 + 71
            : uint6 < 62
            ? uint6 - 4
            : uint6 === 62
            ? 43
            : 47;
    };
    for (ii = 0; ii < bff.length; ii += 1) {
        mod3 = ii % 3;
        uint24 |= bff[ii] << (16 >>> mod3 & 24);
        if (mod3 === 2 || bff.length - ii === 1) {
            text += String.fromCharCode(
                uint6ToB64(uint24 >>> 18 & 63),
                uint6ToB64(uint24 >>> 12 & 63),
                uint6ToB64(uint24 >>> 6 & 63),
                uint6ToB64(uint24 & 63)
            );
            uint24 = 0;
        }
    }
    return text.replace(/A(?=A$|$)/g, '=');
}
```
- example usage
```shell
...
.filter(function (key) {
    return typeof request.swgg.bodyMeta[key].filename === 'string';
})
.map(function (key) {
    tmp = local.jsonCopy(request.swgg.paramDict);
    local.objectSetOverride(tmp, {
        fileBlob:
            local.base64FromBuffer(request.swgg.bodyParsed[key]),
        fileContentType: request.swgg.bodyMeta[key].contentType,
        fileFilename: request.swgg.bodyMeta[key].filename,
        fileInputName: request.swgg.bodyMeta[key].name,
        fileSize: request.swgg.bodyParsed[key].length,
        fileUrl: local.swaggerJson.basePath +
            '/' + request.swgg.pathObject._tags0 +
            '/fileGetOneById/' + tmp.id
...
```

#### <a name="apidoc.element.utility2.base64FromHex"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64FromHex (text)](#apidoc.element.utility2.base64FromHex)
- description and source-code
```javascript
base64FromHex = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the hex-text to base64-encoded-text
 */
</span>    var bff, ii;
    bff = [];
    for (ii = 0; ii < text.length; ii += 2) {
        bff.push(parseInt(text[ii] + text[ii + 1], 16));
    }
    return local.base64FromBuffer(bff);
}
```
- example usage
```shell
...
options = {};
options.base64 = local.base64FromString(local.stringAsciiCharset + '\u1234');
local.assertJsonEqual(
    local.base64FromBuffer(local.base64ToBuffer(options.base64)),
    options.base64
);
local.assertJsonEqual(
    local.base64FromHex(local.base64ToHex(options.base64)),
    options.base64
);
local.assertJsonEqual(
    local.base64FromString(local.base64ToString(options.base64)),
    options.base64
);
onError();
...
```

#### <a name="apidoc.element.utility2.base64FromString"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64FromString (text)](#apidoc.element.utility2.base64FromString)
- description and source-code
```javascript
base64FromString = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the utf8-text to base64-encoded-text
 */
</span>    return local.base64FromBuffer(local.bufferCreate(text));
}
```
- example usage
```shell
...
    break;
case 'string':
    tmp = options.modeNotRandom
        ? 'abcd1234'
        : ((1 + Math.random()) * 0x10000000000000).toString(36).slice(1);
    switch (propDef.format) {
    case 'byte':
        tmp = local.base64FromString(tmp);
        break;
    case 'date':
    case 'date-time':
        tmp = new Date().toISOString();
        break;
    case 'email':
        tmp = tmp + '@random.com';
...
```

#### <a name="apidoc.element.utility2.base64ToBuffer"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64ToBuffer (text)](#apidoc.element.utility2.base64ToBuffer)
- description and source-code
```javascript
base64ToBuffer = function (text) {
<span class="apidocCodeCommentSpan">/*
 * https://gist.github.com/wang-bin/7332335
 * this function will convert the base64-encoded text to Uint8Array
 */
</span>    var de = new Uint8Array(text.length); //3/4
    var u = 0, q = '', x = '', c;
    var map64 = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/";
    for (var r=0; c=text[x++]; ~c&&(u=q%4?u*64+c:c,q++%4)?de[r++]=(255&u>>(-2*q&6)):0)
        c = map64.indexOf(c);
    return de.subarray(0, r);
}
```
- example usage
```shell
...
    if (!data) {
        local.serverRespondDefault(request, response, 404);
        return;
    }
    local.serverRespondHeadSet(request, response, null, {
        'Content-Type': data.fileContentType
    });
    response.end(local.base64ToBuffer(data.fileBlob));
    break;
case 'userLogout':
    options.onNext();
    break;
default:
    options.onNext(null, data, meta);
}
...
```

#### <a name="apidoc.element.utility2.base64ToHex"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64ToHex (text)](#apidoc.element.utility2.base64ToHex)
- description and source-code
```javascript
base64ToHex = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the base64-encoded-text to hex-text
 */
</span>    var bff, ii;
    bff = local.base64ToBuffer(text);
    text = '';
    for (ii = 0; ii < bff.length; ii += 1) {
        text += (0x100 + bff[ii]).toString(16).slice(-2);
    }
    return text;
}
```
- example usage
```shell
...
options = {};
options.base64 = local.base64FromString(local.stringAsciiCharset + '\u1234');
local.assertJsonEqual(
    local.base64FromBuffer(local.base64ToBuffer(options.base64)),
    options.base64
);
local.assertJsonEqual(
    local.base64FromHex(local.base64ToHex(options.base64)),
    options.base64
);
local.assertJsonEqual(
    local.base64FromString(local.base64ToString(options.base64)),
    options.base64
);
onError();
...
```

#### <a name="apidoc.element.utility2.base64ToString"></a>[function <span class="apidocSignatureSpan">utility2.</span>base64ToString (text)](#apidoc.element.utility2.base64ToString)
- description and source-code
```javascript
base64ToString = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the base64-encoded text to utf8-text
 */
</span>    return local.bufferToString(local.base64ToBuffer(text));
}
```
- example usage
```shell
...
        // validate signature
        local.assert(local.sjcl.codec.base64url.fromBits(
            new local.sjcl.misc.hmac(local.sjcl.codec.base64url.toBits(
                local.jwtAes256KeyInit(key)
            )).encrypt(token[0] + '.' + token[1])
        ) === token[2]);
        // return decoded data
        token = JSON.parse(local.base64ToString(token[1]));
        // https://tools.ietf.org/html/rfc7519#section-4.1
        // validate jwt-registered-headers
        local.assert(!token.exp || token.exp >= timeNow);
        local.assert(!token.nbf || token.nbf <= timeNow);
        return token;
    }, local.nop) || {};
};
...
```

#### <a name="apidoc.element.utility2.blobRead"></a>[function <span class="apidocSignatureSpan">utility2.</span>blobRead (blob, encoding, onError)](#apidoc.element.utility2.blobRead)
- description and source-code
```javascript
blobRead = function (blob, encoding, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will read from the blob with the given encoding
 * possible encodings are:
 * - Uint8Array (default)
 * - dataURL
 * - text
 */
</span>    var data, done, reader;
    if (local.modeJs === 'node') {
        switch (encoding) {
        // readAsDataURL
        case 'dataURL':
            data = 'data:' + (blob.type || '') + ';base64,' +
                local.base64FromBuffer(blob.bff);
            break;
        // readAsText
        case 'text':
            data = local.bufferToString(blob.bff);
            break;
        // readAsArrayBuffer
        default:
            data = local.bufferCreate(blob.bff);
        }
        onError(null, data);
        return;
    }
    reader = new local.global.FileReader();
    reader.onabort = reader.onerror = reader.onload = function (event) {
        if (done) {
            return;
        }
        done = true;
        switch (event.type) {
        case 'abort':
        case 'error':
            onError(new Error('blobRead - ' + event.type));
            break;
        case 'load':
            onError(null, reader.result instanceof local.global.ArrayBuffer
                // convert ArrayBuffer to Uint8Array
                ? local.bufferCreate(reader.result)
                : reader.result);
            break;
        }
    };
    switch (encoding) {
    // readAsDataURL
    case 'dataURL':
        reader.readAsDataURL(blob);
        break;
    // readAsText
    case 'text':
        reader.readAsText(blob);
        break;
    // readAsArrayBuffer
    default:
        reader.readAsArrayBuffer(blob);
    }
}
```
- example usage
```shell
...
if (!(value instanceof local.Blob)) {
    result[ii] = [boundary + '\r\nContent-Disposition: form-data; name="' +
        element.name + '"\r\n\r\n', value, '\r\n'];
    return;
}
// read from blob in parallel
onParallel.counter += 1;
local.blobRead(value, 'binary', function (error, data) {
    result[ii] = !error && [boundary +
        '\r\nContent-Disposition: form-data; name="' + element.name + '"' +
        // read param filename
        (value && value.name
            ? '; filename="' + value.name + '"'
            : '') +
        '\r\n' +
...
```

#### <a name="apidoc.element.utility2.browserTest"></a>[function <span class="apidocSignatureSpan">utility2.</span>browserTest (options, onError)](#apidoc.element.utility2.browserTest)
- description and source-code
```javascript
browserTest = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will spawn an electron process to test options.url
 */
</span>    var done, modeNext, onNext, onParallel, timerTimeout;
    if (local.modeJs === 'node') {
        local.objectSetDefault(options, local.env);
        options.timeoutDefault = options.timeoutDefault || local.timeoutDefault;
    }
    modeNext = Number(options.modeNext || 0);
    onNext = function (error, data) {
        modeNext = error instanceof Error
            ? Infinity
            : modeNext + 1;
        switch (modeNext) {
        // run node code
        case 1:
            // init options
            options.testName = local.env.MODE_BUILD + '.browser.' +
                encodeURIComponent(local.urlParse(options.url).pathname
                    .replace(
                        '/build..' + local.env.CI_BRANCH + '..' + local.env.CI_HOST,
                        '/build'
                    ));
            local.objectSetDefault(options, {
                fileCoverage: local.env.npm_config_dir_tmp +
                    '/coverage.' + options.testName + '.json',
                fileScreenCapture: (local.env.npm_config_dir_build +
                    '/screen-capture.' + options.testName + '.png')
                    .replace((/%/g), '_')
                    .replace((/_2F\.png$/), '.png'),
                fileTestReport: local.env.npm_config_dir_tmp +
                    '/test-report.' + options.testName + '.json',
                modeBrowserTest: 'test',
                timeExit: Date.now() + options.timeoutDefault
            }, 1);
            // init timerTimeout
            timerTimeout = local.onTimeout(
                onNext,
                options.timeoutDefault,
                options.testName
            );
            // init file urlBrowser
            options.modeNext = 20;
            options.urlBrowser = local.env.npm_config_dir_tmp + '/electron.' +
                Date.now().toString(16) + Math.random().toString(16) + '.html';
            local.fsWriteFileWithMkdirpSync(options.urlBrowser, '<style>body {' +
                    'border: 1px solid black;' +
                    'margin: 0;' +
                    'padding: 0;' +
                '}</style>' +
                '<webview id=webview1 src="' +
                options.url.replace('{{timeExit}}', options.timeExit) +
                '" style="' +
                    'border: none;' +
                    'height: 100%;' +
                    'margin: 0;' +
                    'padding: 0;' +
                    'width: 100%;' +
                '"></webview>' +
                '<script>window.local = {}; (' + local.browserTest
                    .toString()
                    .replace((/<\//g), '<\\/')
                    // coverage-hack - un-instrument
                    .replace((/\b__cov_.*?\+\+/g), '0') +
                '(' + JSON.stringify(options) + '))</script>');
            console.log('\nbrowserTest - created electron entry-page ' +
                options.urlBrowser + '\n');
            // spawn an electron process to test a url
            options.modeNext = 10;
            local.processSpawnWithTimeout('electron', [
                __filename,
                'browserTest',
                '--disable-overlay-scrollbar',
                '--enable-logging'
            ], {
                env: local.jsonCopy(options),
                stdio: options.modeSilent
                    ? 'ignore'
                    : ['ignore', 1, 2]
            }).once('exit', onNext);
            break;
        case 2:
            console.log('\nbrowserTest - exit-code ' + error + ' - ' + options.url +
                '\n');
            // merge browser coverage
            if (options.modeCoverageMerge) {
                // try to JSON.parse the string
                local.tryCatchOnError(function () {
                    data = JSON.parse(
                        local.fs.readFileSync(options.fileCoverage, 'utf8')
                    );
                }, local.nop);
                if (!local._debugTryCatchErrorCaught) { ...
```
- example usage
```shell
...
// run node js-env code - function
case 'node':
    local.testCase_webpage_default = function (options, onError) {
    /*
     * this function will test webpage's default handling-behavior
     */
        options = { modeCoverageMerge: true, url: local.serverLocalHost + '?modeTest=1' };
        local.browserTest(options, onError);
    };
    break;
}
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.bufferConcat"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferConcat (bufferList)](#apidoc.element.utility2.bufferConcat)
- description and source-code
```javascript
bufferConcat = function (bufferList) {
<span class="apidocCodeCommentSpan">/*
 * this function will emulate node's Buffer.concat for Uint8Array in the browser
 */
</span>    var ii, jj, length, result;
    length = 0;
    bufferList = bufferList
        .filter(function (element) {
            return element || element === 0;
        })
        .map(function (element) {
            // convert number to string
            if (typeof element === 'number') {
                element = String(element);
            }
            // convert non-Uint8Array to Uint8Array
            element = local.bufferCreateIfNotBuffer(element);
            length += element.length;
            return element;
        });
    result = local.bufferCreate(length);
    ii = 0;
    bufferList.forEach(function (element) {
        for (jj = 0; jj < element.length; ii += 1, jj += 1) {
            result[ii] = element[jj];
        }
    });
    return result;
}
```
- example usage
```shell
...
options.crlf = local.bufferCreate([0x0d, 0x0a]);
// init boundary
ii = 0;
jj = local.bufferIndexOfSubBuffer(request.bodyRaw, options.crlf, ii);
if (jj <= 0) {
    break;
}
options.boundary = local.bufferConcat([
    options.crlf,
    request.bodyRaw.slice(ii, jj)
]);
ii = jj + 2;
while (true) {
    jj = local.bufferIndexOfSubBuffer(
        request.bodyRaw,
...
```

#### <a name="apidoc.element.utility2.bufferCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferCreate (text)](#apidoc.element.utility2.bufferCreate)
- description and source-code
```javascript
bufferCreate = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a Uint8Array from the text,
 * with either 'utf8' (default) or 'base64' encoding
 */
</span>    if (typeof text === 'string') {
        if (local.modeJs === 'node') {
            return new Buffer(text);
        }
        if (local.global.TextEncoder) {
            return new local.global.TextEncoder('utf-8').encode(text);
        }
// bug-workaround - TextEncoder.encode polyfill
/* jslint-ignore-begin */
// utility2-uglifyjs https://github.com/feross/buffer/blob/v4.9.1/index.js#L1670
/* istanbul ignore next */
function utf8ToBytes(e,t){t=t||Infinity;var n,r=e.length,i=null,s=[];for(var o=0
;o<r;++o){n=e.charCodeAt(o);if(n>55295&&n<57344){if(!i){if(n>56319){(t-=3)>-1&&s
.push(239,191,189);continue}if(o+1===r){(t-=3)>-1&&s.push(239,191,189);continue}
i=n;continue}if(n<56320){(t-=3)>-1&&s.push(239,191,189),i=n;continue}n=(i-55296<<10|
n-56320)+65536}else i&&(t-=3)>-1&&s.push(239,191,189);i=null;if(n<128){if((t-=1)<0
)break;s.push(n)}else if(n<2048){if((t-=2)<0)break;s.push(n>>6|192,n&63|128)}else if(
n<65536){if((t-=3)<0)break;s.push(n>>12|224,n>>6&63|128,n&63|128)}else{if(!(n<1114112
))throw new Error("Invalid code point");if((t-=4)<0)break;s.push(n>>18|240,n>>12&63|128
,n>>6&63|128,n&63|128)}}return s}
return new local.global.Uint8Array(utf8ToBytes(text));
/* jslint-ignore-end */
    }
    return new local.global.Uint8Array(text);
}
```
- example usage
```shell
...
 * --Boundary--\r\n
 */
case 'multipart/form-data':
    request.swgg.isMultipartFormData = true;
    request.swgg.bodyParsed = {};
    request.swgg.bodyMeta = {};
    options = {};
    options.crlf = local.bufferCreate([0x0d, 0x0a]);
    // init boundary
    ii = 0;
    jj = local.bufferIndexOfSubBuffer(request.bodyRaw, options.crlf, ii);
    if (jj <= 0) {
        break;
    }
    options.boundary = local.bufferConcat([
...
```

#### <a name="apidoc.element.utility2.bufferCreateIfNotBuffer"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferCreateIfNotBuffer (text)](#apidoc.element.utility2.bufferCreateIfNotBuffer)
- description and source-code
```javascript
bufferCreateIfNotBuffer = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a Uint8Array from the text with the given encoding,
 * if it is not already a Uint8Array
 */
</span>    return text instanceof local.global.Uint8Array
        ? text
        : local.bufferCreate(text);
}
```
- example usage
```shell
...
    })
    .map(function (element) {
        // convert number to string
        if (typeof element === 'number') {
            element = String(element);
        }
        // convert non-Uint8Array to Uint8Array
        element = local.bufferCreateIfNotBuffer(element);
        length += element.length;
        return element;
    });
result = local.bufferCreate(length);
ii = 0;
bufferList.forEach(function (element) {
    for (jj = 0; jj < element.length; ii += 1, jj += 1) {
...
```

#### <a name="apidoc.element.utility2.bufferIndexOfSubBuffer"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferIndexOfSubBuffer (bff, subBff, fromIndex)](#apidoc.element.utility2.bufferIndexOfSubBuffer)
- description and source-code
```javascript
bufferIndexOfSubBuffer = function (bff, subBff, fromIndex) {
<span class="apidocCodeCommentSpan">/*
 * this function will search bff for the indexOf-like position of the subBff
 */
</span>    var ii, jj, kk;
    for (ii = fromIndex || 0; ii < bff.length; ii += 1) {
        for (jj = 0, kk = ii; jj < subBff.length; jj += 1, kk += 1) {
            if (subBff[jj] !== bff[kk]) {
                break;
            }
        }
        if (jj === subBff.length) {
            return kk - jj;
        }
    }
    return subBff.length && -1;
}
```
- example usage
```shell
...
request.swgg.isMultipartFormData = true;
request.swgg.bodyParsed = {};
request.swgg.bodyMeta = {};
options = {};
options.crlf = local.bufferCreate([0x0d, 0x0a]);
// init boundary
ii = 0;
jj = local.bufferIndexOfSubBuffer(request.bodyRaw, options.crlf, ii);
if (jj <= 0) {
    break;
}
options.boundary = local.bufferConcat([
    options.crlf,
    request.bodyRaw.slice(ii, jj)
]);
...
```

#### <a name="apidoc.element.utility2.bufferRandomBytes"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferRandomBytes (length)](#apidoc.element.utility2.bufferRandomBytes)
- description and source-code
```javascript
bufferRandomBytes = function (length) {
<span class="apidocCodeCommentSpan">/*
 * this function will create create a Uint8Array with the given length,
 * filled with random bytes
 */
</span>    var bff, ii;
    bff = new local.global.Uint8Array(length);
    for (ii = 0; ii < bff.length; ii += 1) {
        bff[ii] = Math.random() * 0x100;
    }
    return bff;
}
```
- example usage
```shell
...
};

local.jwtAes256KeyCreate = function () {
/*
 * this function will create a random, aes-256-base64url-jwt-key
 */
    return local.jwtBase64UrlNormalize(
        local.base64FromBuffer(local.bufferRandomBytes(32))
    );
};

local.jwtAes256KeyInit = function (key) {
/*
 * https://jwt.io/
 * this function will init the aes-256-base64url-jwt-key
...
```

#### <a name="apidoc.element.utility2.bufferToNodeBuffer"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferToNodeBuffer (bff)](#apidoc.element.utility2.bufferToNodeBuffer)
- description and source-code
```javascript
bufferToNodeBuffer = function (bff) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the Uint8Array instance to a node Buffer instance
 */
</span>    if (local.modeJs === 'node' &&
            bff instanceof local.global.Uint8Array && (!Buffer.isBuffer(bff))) {
        Object.setPrototypeOf(bff, Buffer.prototype);
    }
    return bff;
}
```
- example usage
```shell
...
        xhr.data.read(function (error, data) {
            if (error) {
                xhr.error = xhr.error || error;
                xhr.onEvent({ type: 'error' });
                return;
            }
            // send data
            xhr.send(local.bufferToNodeBuffer(data));
        });
    } else {
        // send data
        xhr.send(local.bufferToNodeBuffer(xhr.data));
    }
    return xhr;
};
...
```

#### <a name="apidoc.element.utility2.bufferToString"></a>[function <span class="apidocSignatureSpan">utility2.</span>bufferToString (bff)](#apidoc.element.utility2.bufferToString)
- description and source-code
```javascript
bufferToString = function (bff) {
<span class="apidocCodeCommentSpan">/*
 * this function will convert the Uint8Array bff to a utf8 string
 */
</span>    bff = bff || '';
    if (typeof bff === 'string') {
        return bff;
    }
    bff = local.bufferCreateIfNotBuffer(bff);
    if (local.modeJs === 'node') {
        return new Buffer(bff).toString();
    }
    if (local.global.TextDecoder) {
        return new local.global.TextDecoder('utf-8').decode(bff);
    }
// bug-workaround - TextDecoder.decode polyfill
/* jslint-ignore-begin */
// http://stackoverflow.com/questions/17191945/conversion-between-utf-8-arraybuffer-and-string
function Utf8ArrayToStr(e){var t,n,r,i,s,o;t="",r=e.length,n=0;while(n<r){i=e[n++
];switch(i>>4){case 0:case 1:case 2:case 3:case 4:case 5:case 6:case 7:t+=String
.fromCharCode(i);break;case 12:case 13:s=e[n++],t+=String.fromCharCode((i&31)<<6|
s&63);break;case 14:s=e[n++],o=e[n++],t+=String.fromCharCode((i&15)<<12|(s&63)<<6|
(o&63)<<0)}}return t}
return Utf8ArrayToStr(bff);
/* jslint-ignore-end */
}
```
- example usage
```shell
...
    nextMiddleware();
    return;
}
switch (String(request.headers['content-type']).split(';')[0]) {
// parse application/x-www-form-urlencoded, e.g.
// aa=hello%20world&bb=bye%20world
case 'application/x-www-form-urlencoded':
    request.swgg.bodyParsed = local.bufferToString(request.bodyRaw);
    request.swgg.bodyParsed =
        local.urlParse('?' + request.swgg.bodyParsed, true).query;
    break;
/*
 * https://tools.ietf.org/html/rfc7578
 * parse multipart/form-data, e.g.
 * --Boundary\r\n
...
```

#### <a name="apidoc.element.utility2.buildApidoc"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildApidoc (options, onError)](#apidoc.element.utility2.buildApidoc)
- description and source-code
```javascript
buildApidoc = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the apidoc
 */
</span>    // optimization - do not run if $npm_config_mode_coverage = all
    if (local.env.npm_config_mode_coverage === 'all') {
        onError();
        return;
    }
    local.objectSetDefault(options, { blacklistDict: local });
    // create apidoc.html
    local.fsWriteFileWithMkdirpSync(
        local.env.npm_config_dir_build + '/apidoc.html',
        local.apidocCreate(options)
    );
    console.log('created apidoc file://' + local.env.npm_config_dir_build +
        '/apidoc.html\n');
    local.browserTest({
        modeBrowserTest: 'screenCapture',
        url: 'file://' + local.env.npm_config_dir_build + '/apidoc.html'
    }, onError);
}
```
- example usage
```shell
...
 * this function will test buildApidoc\'s default handling-behavior-behavior\n\
 */\n\
    options = { modulePathList: module.paths };\n\
    if (local.env.npm_package_buildNpmdoc) {\n\
        local.buildNpmdoc(options, onError);\n\
        return;\n\
    }\n\
    local.buildApidoc(options, onError);\n\
};\n\
\n\
local.testCase_buildApp_default = local.testCase_buildApp_default || function (\n\
    options,\n\
    onError\n\
) {\n\
/*\n\
...
```

#### <a name="apidoc.element.utility2.buildApp"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildApp (optionsList, onError)](#apidoc.element.utility2.buildApp)
- description and source-code
```javascript
buildApp = function (optionsList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the app
 */
</span>    var onParallel;
    local.fsRmrSync(local.env.npm_config_dir_build + '/app');
    onParallel = local.onParallel(function (error) {
        /* istanbul ignore next */
        if (!local.global.__coverage__) {
            local.fs.writeFileSync(
                'assets.' + local.env.npm_package_nameAlias + '.rollup.js',
                local.assetsDict['/assets.' + local.env.npm_package_nameAlias +
                    '.rollup.js'] ||
                    local.assetsDict['/assets.' + local.env.npm_package_nameAlias +
                        '.js']
            );
        }
        onError(error);
    });
    onParallel.counter += 1;
    optionsList = optionsList.concat({
        file: '/assets.' + local.env.npm_package_nameAlias + '.js',
        url: '/assets.' + local.env.npm_package_nameAlias + '.js'
    }, {
        file: '/assets.' + local.env.npm_package_nameAlias + '.rollup.js',
        url: '/assets.' + local.env.npm_package_nameAlias + '.rollup.js'
    }, {
        file: '/assets.app.js',
        url: '/assets.app.js'
    }, {
        file: '/assets.example.js',
        url: '/assets.example.js'
    }, {
        file: '/assets.test.js',
        url: '/assets.test.js'
    }, {
        file: '/assets.utility2.rollup.js',
        url: '/assets.utility2.rollup.js'
    }, {
        file: '/index.html',
        url: '/index.html'
    }, {
        file: '/jsonp.utility2._stateInit',
        url: '/jsonp.utility2._stateInit?callback=window.utility2._stateInit'
    });
    optionsList.forEach(function (options) {
        onParallel.counter += 1;
        local.ajax(options, function (error, xhr) {
            // validate no error occurred
            local.assert(!error, error);
            // jslint file
            local.jslintAndPrintConditional(xhr.responseText, options.file);
            // validate no error occurred
            local.assert(!local.jslint.errorText, local.jslint.errorText);
            local.fsWriteFileWithMkdirpSync(
                local.env.npm_config_dir_build + '/app' + options.file,
                new Buffer(xhr.response)
            );
            onParallel();
        });
    });
    // test standalone assets.app.js
    onParallel.counter += 1;
    local.fs.writeFileSync('tmp/assets.app.js', local.assetsDict['/assets.app.js']);
    local.processSpawnWithTimeout(process.argv[0], ['assets.app.js'], {
        cwd: 'tmp',
        env: {
            PORT: (Math.random() * 0x10000) | 0x8000,
            npm_config_timeout_exit: 5000
        },
        stdio: ['ignore', 1, 2]
    })
        .once('error', onParallel)
        .once('exit', function (exitCode) {
            // validate exitCode
            local.assert(!exitCode, exitCode);
            onParallel();
        });
    onParallel();
}
```
- example usage
```shell
...
/*\n\
 * this function will test buildApp\'s default handling-behavior-behavior\n\
 */\n\
    local.testCase_buildReadme_default(options, local.onErrorThrow);\n\
    local.testCase_buildLib_default(options, local.onErrorThrow);\n\
    local.testCase_buildTest_default(options, local.onErrorThrow);\n\
    options = [];\n\
    local.buildApp(options, onError);\n\
};\n\
\n\
local.testCase_buildLib_default = local.testCase_buildLib_default || function (\n\
    options,\n\
    onError\n\
) {\n\
/*\n\
...
```

#### <a name="apidoc.element.utility2.buildLib"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildLib (options, onError)](#apidoc.element.utility2.buildLib)
- description and source-code
```javascript
buildLib = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the lib
 */
</span>    local.objectSetDefault(options, {
        customize: local.nop,
        dataFrom: local.tryCatchReadFile(
            'lib.' + local.env.npm_package_nameAlias + '.js',
            'utf8'
        ),
        dataTo: local.templateRenderJslintLite(
            local.assetsDict['/assets.lib.template.js'],
            {}
        )
    });
    // search-and-replace - customize dataTo
    [
        // customize body before istanbul
        (/[\S\s]*?^\/\* istanbul instrument in package /m),
        // customize body after init exports
        (/\n {12}module.exports.module = module;\n[\S\s]*?$/)
    ].forEach(function (rgx) {
        // handle large string-replace
        options.dataFrom.replace(rgx, function (match0) {
            options.dataTo.replace(rgx, function (match1) {
                options.dataTo = options.dataTo.split(match1);
                options.dataTo[0] += match0;
                options.dataTo[0] += options.dataTo.splice(1, 1)[0];
                options.dataTo = options.dataTo.join(match1);
            });
        });
    });
    options.customize();
    // save lib.xxx.js
    local.fs.writeFileSync(
        'lib.' + local.env.npm_package_nameAlias + '.js',
        options.dataTo
    );
    onError();
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will test buildLib\'s default handling-behavior\n\
 */\n\
    options = {};\n\
    local.buildLib(options, onError);\n\
};\n\
\n\
local.testCase_buildReadme_default = local.testCase_buildReadme_default || function (\n\
    options,\n\
    onError\n\
) {\n\
/*\n\
...
```

#### <a name="apidoc.element.utility2.buildNpmdoc"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildNpmdoc (options, onError)](#apidoc.element.utility2.buildNpmdoc)
- description and source-code
```javascript
buildNpmdoc = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the npmdoc
 */
</span>    var onParallel, packageJson;
    onParallel = local.utility2.onParallel(onError);
    onParallel.counter += 1;
    // build package.json
    packageJson = JSON.parse(local.fs.readFileSync('package.json', 'utf8'));
    local.objectSetDefault(packageJson, local.objectLiteralize({
        devDependencies: {
            '$[]': [local.env.npm_package_buildNpmdoc, '*']
        },
        repository: {
            type: 'git',
            url: 'https://github.com/npmdoc/node-npmdoc-' +
                local.env.npm_package_buildNpmdoc + '.git'
        }
    }), 2);
    local.objectSetOverride(packageJson, local.objectLiteralize({
        keywords: ['documentation', local.env.npm_package_buildNpmdoc]
    }), 2);
    onParallel.counter += 1;
    local.buildReadme({
        dataFrom: '\n# package.json\n'''json\n' +
            JSON.stringify(packageJson) + '\n'''\n'
    }, onParallel);
    packageJson = JSON.parse(local.fs.readFileSync('package.json', 'utf8'));
    // build apidoc.html
    onParallel.counter += 1;
    local.buildApidoc({
        dir: local.env.npm_package_buildNpmdoc,
        modulePathList: options.modulePathList
    }, onParallel);
    // build README.md
    options = { modulePathList: options.modulePathList };
    options.readme = local.apidocCreate({
        dir: local.env.npm_package_buildNpmdoc,
/* jslint-ignore-begin */
header: '\
# api documentation for \
 \
utility2 (v2017.3.22) \
 \
[![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-utility2.svg)](https://travis-ci.org
/npmdoc/node-npmdoc-utility2)\
\n\
#### the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps \
\n\
\n\
[![NPM](https://nodei.co/npm/utility2.png?downloads=true)](https://www.npmjs.com/package/utility2)\
\n\
\n\
[![apidoc](https://npmdoc.github.io/node-npmdoc-utility2/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode
-npmdoc-utility2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node
-npmdoc-utility2/build..beta..travis-ci.org/apidoc.html)\
\n\
\n\
![package-listing](https://npmdoc.github.io/node-npmdoc-utility2/build/screen-capture.npmPackageListing.svg) \
\n\
\n\
\n\
\n\
# package.json \
\n\
\n\
'''json \
\n\
\n\
{
    "author": {
        "name": "kai zhu",
        "email": "kaizhu256@gmail.com"
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
    "description": "the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "8e163e40289f10711d7ccf0d5758e02fc7fa5776",
    "homepage": "https://github.com/kaizhu256/node-utility2",
    "keywords": [
        "browser",
        "build",
        "busybox",
        "ci",
        "code-coverage",
        "continuous-integration",
        "deploy",
        "docker",
        "electron",
        "headless-browser",
        "istanbul",
        "jscover",
        "jscoverage",
        "phantomjs",
        "slimerjs",
        "swiss-army-knife",
        "test",
        "test-coverage",
        "travis",
        "travis-ci",
        "utility2",
        "webapp"
    ],
    "license": "MIT",
    "main": "lib.utility2.js",
    "name": "utility2",
    "nameAlias": "utility2",
    "nameAliasPublish": "busybox npmtest-lite test-lite",
    "nameOriginal": "utility2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "readme": "# utility2\nthe zero-dependency swiss-army-knife tool for building, testing, and deploying webapps\n\n[![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-utility2.svg)](https://travis-ci.org/kaizhu256/node-utility2) [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build/coverage.html/index.html)\n\n[![NPM](https://nodei.co/npm/utility2.png?downloads=true)](https://www.npmjs.com/package/utility2)\n\n[![package-listing](https://kaizhu256.github.io/node-utility2/build/screen-capture.npmPackageListing.svg)](https://github.com/kaizhu256/node-utility2)\n\n\n\n# cdn download\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/assets.utility2.rollup.js](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/assets.utility2.rollup.js)\n\n\n\n# live demo\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html)\n\n[![github.com test-server](https://kaizhu256.github.io/node-utility2/build/screen-capture.deployGithub.browser._2Fnode-utility2_2Fbuild_2Fapp_2Findex.html.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html)\n\n\n\n# documentation\n#### apidoc\n- [https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html)\n\n[![apidoc](https://kaizhu256.github.io/node-utility2/build/screen-capture.buildApidoc.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/apidoc.html)\n\n#### todo\n- npm publish 2017.3.22\n- add function to remotely update .travis.yml\n- query failed travis-ci builds\n- rename sub-package db-lite -> nedb-lite\n- rename sub-package istanbul-lite -> istanbul-classic\n- rename sub-package jslint-lite -> jslint-classic\n- use optional remote-credentials during travis-ci build\n- allow server-side stdout to be streamed to webapps\n- add utility2.middlewareLimit\n- add server stress test using electron\n- analytics\n- none\n\n#### changes for v2017.3.22\n- add shell-function shGitRemotePromote to auto-promote branches alpha -> beta -> master\n- deprecate ssh-key in favor of github oauth - https://stackoverflow.com/questions/18027115/committing-via-travis-ci-failing\n- enable shNpmdocRepoListCreate in travis-ci\n- enhance shell-function shNpmPackageListingCreate to add total package-size to package-listing\n- fix apidoc bug 'Function.prototype.toString is not generic'\n- fix shell-function shInit bug - export: npm_package_react-native: bad variable name\n- none\n\n#### this package requires\n- darwin or linux os\n\n\n\n# build status [![travis-ci.org build-status](https://api.travis-ci.org/kaizhu256/node-utility2.svg)](https://travis-ci.org/kaizhu256/node-utility2)\n[![build commit status](https://kaizhu256.github.io/node-utility2/build/build.badge.svg)](https://travis-ci.org/kaizhu256/node-utility2)\n\n| git-branch : | [master](https://github.com/kaizhu256/node-utility2/tree/master) | [beta](https://github.com/kaizhu256/node-utility2/tree/beta) | [alpha](https://github.com/kaizhu256/node-utility2/tree/alpha)|\n|--:|:--|:--|:--|\n| test-server-github : | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/app/index.html) | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/app/index.html) | [![github.com test-server](https://kaizhu256.github.io/node-utility2/GitHub-Mark-32px.png)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/app/index.html)|\n| test-server-heroku : | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-master.herokuapp.com) | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-beta.herokuapp.com) | [![heroku.com test-server](https://kaizhu256.github.io/node-utility2/heroku-logo.75x25.png)](https://h1-utility2-alpha.herokuapp.com)|\n| test-report : | [![test-report](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/test-report.html) | [![test-report](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/test-report.badge.svg)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/test-report.html)|\n| coverage : | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..master..travis-ci.org/coverage.html/index.html) | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/coverage.html/index.html) | [![istanbul-coverage](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/coverage.badge.svg)](https://kaizhu256.github.io/node-utility2/build..alpha..travis-ci.org/coverage.html/index.html)|\n| build-artifacts : | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..master..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..beta..travis-ci.org) | [![build-artifacts](https://kaizhu256.github.io/node-utility2/glyphicons_144_folder_open.png)](https://github.com/kaizhu256/node-utility2/tree/gh-pages/build..alpha..travis-ci.org)|\n\n#### master branch\n- stable branch\n- HEAD should be tagged, npm-published package\n\n#### beta branch\n- semi-stable branch\n- HEAD should be latest, npm-published package\n\n#### alpha branch\n- unstable branch\n- HEAD is arbitrary\n- commit history may be rewritten\n\n\n\n# quickstart interactive example\n#### to run this example, follow the instruction in the script below\n- [example.sh](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/example.sh)\n'''shell\n# example.sh\n\n# this shell script will serve a webpage that will interactively run browser-tests with coverage\n\n# instruction\n    # 1. copy and paste this entire shell script into a console and press enter\n    # 2. play with the browser-demo on http://127.0.0.1:8081\n\nshExampleSh() {(set -e\n    # npm install utility2\n    npm install \"kaizhu256/node-utility2#alpha\"\n    # serve a webpage that will interactively run browser-tests with coverage\n    cd node_modules/utility2 && export PORT=8081 && npm start\n)}\nshExampleSh\n'''\n\n#### output from browser\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleSh.browser..png)\n\n#### output from shell\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleSh.svg)\n\n\n\n# quickstart automated example\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Ftest-report.html.png)\n\n#### to run this example, follow the instruction in the script below\n- [example.js](https://kaizhu256.github.io/node-utility2/build..beta..travis-ci.org/example.js)\n'''javascript\n/*\nexample.js\n\nthis script will demo automated browser-tests with coverage (via electron and istanbul)\n\ninstruction\n    1. save this script as example.js\n    2. run the shell command:\n        $ npm install electron-lite \"kaizhu256/node-utility2#alpha\" && \\\n            PATH=\"$(pwd)/node_modules/.bin:$PATH\" \\\n            PORT=8081 \\\n            npm_config_mode_coverage=utility2 \\\n            node_modules/.bin/utility2 test example.js\n    3. view test-report in ./tmp/build/test-report.html\n    4. view coverage in ./tmp/build/coverage.html/index.html\n*/\n\n\n\n/* istanbul instrument in package utility2 */\n/*jslint\n    bitwise: true,\n    browser: true,\n    maxerr: 8,\n    maxlen: 96,\n    node: true,\n    nomen: true,\n    regexp: true,\n    stupid: true\n*/\n(function () {\n    'use strict';\n    var local;\n\n\n\n    // run shared js-env code - pre-init\n    (function () {\n        // init local\n        local = {};\n        // init modeJs\n        local.modeJs = (function () {\n            try {\n                return typeof navigator.userAgent === 'string' &&\n                    typeof document.querySelector('body') === 'object' &&\n                    typeof XMLHttpRequest.prototype.open === 'function' &&\n                    'browser';\n            } catch (errorCaughtBrowser) {\n                return module.exports &&\n                    typeof process.versions.node === 'string' &&\n                    typeof require('http').createServer === 'function' &&\n                    'node';\n            }\n        }());\n        // init global\n        local.global = local.modeJs === 'browser'\n            ? window\n            : global;\n        // init utility2_rollup\n        local = local.global.utility2_rollup || (local.modeJs === 'browser'\n            ? window.utility2\n            : require('utility2'));\n        // export local\n        local.global.local = local;\n        // run test-server\n        local.testRunServer(local);\n        // init assets\n        local.assetsDict['/assets.hello'] = 'hello';\n    }());\n    switch (local.modeJs) {\n\n\n\n    // run browser js-env code - function\n    case 'browser':\n        local.testCase_ajax_200 = function (options, onError) {\n        /*\n         * this function will test ajax's \"200 ok\" handling-behavior\n         */\n            options = {};\n            // test ajax-path 'assets.hello'\n            local.ajax({ url: 'assets.hello' }, function (error, xhr) {\n                local.tryCatchOnError(function () {\n                    // validate no error occurred\n                    local.assert(!error, error);\n                    // validate data\n                    options.data = xhr.responseText;\n                    local.assert(options.data === 'hello', options.data);\n                    onError();\n                }, onError);\n            });\n        };\n        local.testCase_ajax_404 = function (options, onError) {\n        /*\n         * this function will test ajax's \"404 not found\" handling-behavior\n         */\n            options = {};\n            // test ajax-path '/undefined'\n            local.ajax({ url: '/undefined' }, function (error) {\n                local.tryCatchOnError(function () {\n                    // validate error occurred\n                    local.assert(error, error);\n                    options.statusCode = error.statusCode;\n                    // validate 404 http statusCode\n                    local.assert(options.statusCode === 404, options.statusCode);\n                    onError();\n                }, onError);\n            });\n        };\n        break;\n\n\n\n    // run node js-env code - function\n    case 'node':\n        local.testCase_webpage_default = function (options, onError) {\n        /*\n         * this function will test webpage's default handling-behavior\n         */\n            options = { modeCoverageMerge: true, url: local.serverLocalHost + '?modeTest=1' };\n            local.browserTest(options, onError);\n        };\n        break;\n    }\n    switch (local.modeJs) {\n\n\n\n    // post-init\n    // run browser js-env code - post-init\n    /* istanbul ignore next */\n    case 'browser':\n        local.testRunBrowser = function (event) {\n            if (!event || (event &&\n                    event.currentTarget &&\n                    event.currentTarget.className &&\n                    event.currentTarget.className.includes &&\n                    event.currentTarget.className.includes('onreset'))) {\n                // reset output\n                Array.from(\n                    document.querySelectorAll('body > .resettable')\n                ).forEach(function (element) {\n                    switch (element.tagName) {\n                    case 'INPUT':\n                    case 'TEXTAREA':\n                        element.value = '';\n                        break;\n                    default:\n                        element.textContent = '';\n                    }\n                });\n            }\n            switch (event && event.currentTarget && event.currentTarget.id) {\n            case 'testRunButton1':\n                // show tests\n                if (document.querySelector('#testReportDiv1').style.display === 'none') {\n                    document.querySelector('#testReportDiv1').style.display = 'block';\n                    document.querySelector('#testRunButton1').textContent =\n                        'hide internal test';\n                    local.modeTest = true;\n                    local.testRunDefault(local);\n                // hide tests\n                } else {\n                    document.querySelector('#testReportDiv1').style.display = 'none';\n                    document.querySelector('#testRunButton1').textContent = 'run internal test';\n                }\n                break;\n            // custom-case\n            case 'testRunButton2':\n                // run tests\n                local.modeTest = true;\n                local.testRunDefault(local);\n                break;\n            default:\n                if (location.href.indexOf(\"modeTest=\") >= 0) {\n                    return;\n                }\n                // try to JSON.stringify #inputTextareaEval1\n                try {\n                    document.querySelector('#outputPreJsonStringify1').textContent = '';\n                    document.querySelector('#outputPreJsonStringify1').textContent =\n                        local.jsonStringifyOrdered(\n                            JSON.parse(document.querySelector('#inputTextareaEval1').value),\n                            null,\n                            4\n                        );\n                } catch (ignore) {\n                }\n                // jslint #inputTextareaEval1\n                local.jslint.errorText = '';\n                if (document.querySelector('#inputTextareaEval1').value\n                        .indexOf('/*jslint') >= 0) {\n                    local.jslint.jslintAndPrint(\n                        document.querySelector('#inputTextareaEval1').value,\n                        'inputTextareaEval1.js'\n                    );\n                }\n                document.querySelector('#outputPreJslint1').textContent =\n                    local.jslint.errorText\n                    .replace((/\\u001b\\[\\d+m/g), '')\n                    .trim();\n                // try to cleanup __coverage__\n                try {\n                    delete local.global.__coverage__['/inputTextareaEval1.js'];\n                } catch (ignore) {\n                }\n                // try to cover and eval input-code\n                try {\n                    /*jslint evil: true*/\n                    document.querySelector('#outputTextarea1').value =\n                        local.istanbul.instrumentSync(\n                            document.querySelector('#inputTextareaEval1').value,\n                            '/inputTextareaEval1.js'\n                        );\n                    eval(document.querySelector('#outputTextarea1').value);\n                    document.querySelector('#coverageReportDiv1').innerHTML =\n                        local.istanbul.coverageReportCreate({\n                            coverage: window.__coverage__\n                        });\n                } catch (errorCaught) {\n                    console.error(errorCaught.stack);\n                }\n            }\n            if (document.querySelector('#inputTextareaEval1') && (!event || (event &&\n                    event.currentTarget &&\n                    event.currentTarget.className &&\n                    event.currentTarget.className.includes &&\n                    event.currentTarget.className.includes('oneval')))) {\n                // try to eval input-code\n                try {\n                    /*jslint evil: true*/\n                    eval(document.querySelector('#inputTextareaEval1').value);\n                } catch (errorCaught) {\n                    console.error(errorCaught.stack);\n                }\n            }\n        };\n        // log stderr and stdout to #outputTextareaStdout1\n        ['error', 'log'].forEach(function (key) {\n            console[key + '_original'] = console[key];\n            console[key] = function () {\n                var element;\n                console[key + '_original'].apply(console, arguments);\n                element = document.querySelector('#outputTextareaStdout1');\n                if (!element) {\n                    return;\n                }\n                // append text to #outputTextareaStdout1\n                element.value += Array.from(arguments).map(function (arg) {\n                    return typeof arg === 'string'\n                        ? arg\n                        : JSON.stringify(arg, null, 4);\n                }).join(' ') + '\\n';\n                // scroll textarea to bottom\n                element.scrollTop = element.scrollHeight;\n            };\n        });\n        // init event-handling\n        ['change', 'click', 'keyup'].forEach(function (event) {\n            Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {\n                element.addEventListener(event, local.testRunBrowser);\n            });\n        });\n        // run tests\n        local.testRunBrowser();\n        break;\n\n\n\n    // run node js-env code - post-init\n    /* istanbul ignore next */\n    case 'node':\n        // export local\n        module.exports = local;\n        // require modules\n        local.fs = require('fs');\n        local.http = require('http');\n        local.url = require('url');\n        // init assets\n        local.assetsDict = local.assetsDict || {};\n        /* jslint-ignore-begin */\n        local.assetsDict['/assets.index.template.html'] = '\\\n<!doctype html>\\n\\\n<html lang=\"en\">\\n\\\n<head>\\n\\\n<meta charset=\"UTF-8\">\\n\\\n<meta name=\"viewport\" content=\"width=device-width, initial-scale=1\">\\n\\\n<title>{{env.npm_package_name}} (v{{env.npm_package_version}})</title>\\n\\\n<style>\\n\\\n/*csslint\\n\\\n    box-sizing: false,\\n\\\n    universal-selector: false\\n\\\n*/\\n\\\n* {\\n\\\n    box-sizing: border-box;\\n\\\n}\\n\\\nbody {\\n\\\n    background: #dde;\\n\\\n    font-family: Arial, Helvetica, sans-serif;\\n\\\n    margin: 2rem;\\n\\\n}\\n\\\nbody > * {\\n\\\n    margin-bottom: 1rem;\\n\\\n}\\n\\\n.utility2FooterDiv {\\n\\\n    margin-top: 20px;\\n\\\n    text-align: center;\\n\\\n}\\n\\\n</style>\\n\\\n<style>\\n\\\n/*csslint\\n\\\n    ids: false,\\n\\\n*/\\n\\\n#outputPreJslint1 {\\n\\\n    color: #d00;\\n\\\n}\\n\\\ntextarea {\\n\\\n    font-family: monospace;\\n\\\n    height: 10rem;\\n\\\n    width: 100%;\\n\\\n}\\n\\\ntextarea[readonly] {\\n\\\n    background: #ddd;\\n\\\n}\\n\\\n</style>\\n\\\n</head>\\n\\\n<body>\\n\\\n<!-- utility2-comment\\n\\\n<div id=\"ajaxProgressDiv1\" style=\"background: #d00; height: 2px; left: 0; margin: 0; padding: 0; position: fixed; top: 0; transition: background 0.5s, width 1.5s; width: 25%;\"></div>\\n\\\nutility2-comment -->\\n\\\n<h1>\\n\\\n<!-- utility2-comment\\n\\\n    <a\\n\\\n        {{#if env.npm_package_homepage}}\\n\\\n        href=\"{{env.npm_package_homepage}}\"\\n\\\n        {{/if env.npm_package_homepage}}\\n\\\n        target=\"_blank\"\\n\\\n    >\\n\\\nutility2-comment -->\\n\\\n        {{env.npm_package_name}} (v{{env.npm_package_version}})\\n\\\n<!-- utility2-comment\\n\\\n    </a>\\n\\\nutility2-comment -->\\n\\\n</h1>\\n\\\n<h3>{{env.npm_package_description}}</h3>\\n\\\n<!-- utility2-comment\\n\\\n<h4><a download href=\"assets.app.js\">download standalone app</a></h4>\\n\\\nutility2-comment -->\\n\\\n\\n\\\n\\n\\\n\\n\\\n<label>edit or paste script below to cover and test</label>\\n\\\n<textarea class=\"oneval onkeyup onreset\" id=\"inputTextareaEval1\">\\n\\\n// remove comment below to disable jslint\\n\\\n/*jslint\\n\\\n    browser: true,\\n\\\n    es6: true\\n\\\n*/\\n\\\n/*global window*/\\n\\\n(function () {\\n\\\n    \"use strict\";\\n\\\n    var testCaseDict;\\n\\\n    testCaseDict = {};\\n\\\n    testCaseDict.modeTest = true;\\n\\\n\\n\\\n    // comment this testCase to disable the failed assertion demo\\n\\\n    testCaseDict.testCase_failed_assertion_demo = function (\\n\\\n        options,\\n\\\n        onError\\n\\\n    ) {\\n\\\n    /*\\n\\\n     * this function will demo a failed assertion test\\n\\\n     */\\n\\\n        // jslint-hack\\n\\\n        window.utility2.nop(options);\\n\\\n        window.utility2.assert(false, \"this is a failed assertion demo\");\\n\\\n        onError();\\n\\\n    };\\n\\\n\\n\\\n    testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\\n\\\n    /*\\n\\\n     * this function will demo a passed ajax test\\n\\\n     */\\n\\\n        var data;\\n\\\n        options = {url: \"/\"};\\n\\\n        // test ajax request for main-page \"/\"\\n\\\n        window.utility2.ajax(options, function (error, xhr) {\\n\\\n            try {\\n\\\n                // validate no error occurred\\n\\\n                window.utility2.assert(!error, error);\\n\\\n                // validate \"200 ok\" status\\n\\\n                window.utility2.assert(xhr.statusCode === 200, xhr.statusCode);\\n\\\n                // validate non-empty data\\n\\\n                data = xhr.responseText;\\n\\\n                window.utility2.assert(data && data.length > 0, data);\\n\\\n                onError();\\n\\\n            } catch (errorCaught) {\\n\\\n                onError(errorCaught);\\n\\\n            }\\n\\\n        });\\n\\\n    };\\n\\\n\\n\\\n    window.utility2.testRunDefault(testCaseDict);\\n\\\n}());\\n\\\n</textarea>\\n\\\n<pre id=\"outputPreJsonStringify1\"></pre>\\n\\\n<pre id=\"outputPreJslint1\"></pre>\\n\\\n<label>instrumented-code</label>\\n\\\n<textarea class=\"resettable\" id=\"outputTextarea1\" readonly></textarea>\\n\\\n<label>stderr and stdout</label>\\n\\\n<textarea class=\"resettable\" id=\"outputTextareaStdout1\" readonly></textarea>\\n\\\n<button class=\"onclick onreset\" id=\"testRunButton2\">run internal test</button><br>\\n\\\n<div class=\"resettable\" id=\"testReportDiv1\" style=\"display: none;\"></div>\\n\\\n<div id=\"coverageReportDiv1\" class=\"resettable\"></div>\\n\\\n<!-- utility2-comment\\n\\\n{{#if isRollup}}\\n\\\n<script src=\"assets.app.js\"></script>\\n\\\n{{#unless isRollup}}\\n\\\nutility2-comment -->\\n\\\n<script src=\"assets.utility2.lib.istanbul.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.jslint.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.db.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.sjcl.js\"></script>\\n\\\n<script src=\"assets.utility2.lib.uglifyjs.js\"></script>\\n\\\n<script src=\"assets.utility2.js\"></script>\\n\\\n<script src=\"jsonp.utility2._stateInit?callback=window.utility2._stateInit\"></script>\\n\\\n<script>window.utility2.onResetBefore.counter += 1;</script>\\n\\\n<script src=\"assets.example.js\"></script>\\n\\\n<script src=\"assets.test.js\"></script>\\n\\\n<script>window.utility2.onResetBefore();</script>\\n\\\n<!-- utility2-comment\\n\\\n{{/if isRollup}}\\n\\\nutility2-comment -->\\n\\\n<div class=\"utility2FooterDiv\">\\n\\\n    [ this app was created with\\n\\\n    <a href=\"https://github.com/kaizhu256/node-utility2\" target=\"_blank\">utility2</a>\\n\\\n    ]\\n\\\n</div>\\n\\\n</body>\\n\\\n</html>\\n\\\n';\n        /* jslint-ignore-end */\n        if (local.templateRender) {\n            local.assetsDict['/'] = local.templateRender(\n                local.assetsDict['/assets.index.template.html'],\n                {\n                    env: local.objectSetDefault(local.env, {\n                        npm_package_description: 'example module',\n                        npm_package_name: 'example',\n                        npm_package_nameAlias: 'example',\n                        npm_package_version: '0.0.1'\n                    })\n                }\n            );\n        } else {\n            local.assetsDict['/'] = local.assetsDict['/assets.index.template.html']\n                .replace((/\\{\\{env\\.(\\w+?)\\}\\}/g), function (match0, match1) {\n                    // jslint-hack\n                    String(match0);\n                    switch (match1) {\n                    case 'npm_package_description':\n                        return 'example module';\n                    case 'npm_package_name':\n                        return 'example';\n                    case 'npm_package_nameAlias':\n                        return 'example';\n                    case 'npm_package_version':\n                        return '0.0.1';\n                    }\n                });\n        }\n        // run the cli\n        if (local.global.utility2_rollup || module !== require.main) {\n            break;\n        }\n        local.assetsDict['/assets.example.js'] =\n            local.assetsDict['/assets.example.js'] ||\n            local.fs.readFileSync(__filename, 'utf8');\n        local.assetsDict['/assets.utility2.rollup.js'] =\n            local.assetsDict['/assets.utility2.rollup.js'] ||\n            local.fs.readFileSync(\n                // npmdoc-hack\n                local.utility2.__dirname +\n                    '/lib.utility2.js',\n                'utf8'\n            ).replace((/^#!/), '//');\n        local.assetsDict['/favicon.ico'] = local.assetsDict['/favicon.ico'] || '';\n        // if $npm_config_timeout_exit exists,\n        // then exit this process after $npm_config_timeout_exit ms\n        if (Number(process.env.npm_config_timeout_exit)) {\n            setTimeout(process.exit, Number(process.env.npm_config_timeout_exit));\n        }\n        // start server\n        if (local.global.utility2_serverHttp1) {\n            break;\n        }\n        process.env.PORT = process.env.PORT || '8081';\n        console.log('server starting on port ' + process.env.PORT);\n        local.http.createServer(function (request, response) {\n            request.urlParsed = local.url.parse(request.url);\n            if (local.assetsDict[request.urlParsed.pathname] !== undefined) {\n                response.end(local.assetsDict[request.urlParsed.pathname]);\n                return;\n            }\n            response.statusCode = 404;\n            response.end();\n        }).listen(process.env.PORT);\n        break;\n    }\n}());\n'''\n\n#### output from utility2\n![screen-capture](https://kaizhu256.github.io/screen-capture.testExampleJs.browser._2Fhome_2Ftravis_2Fbuild_2Fkaizhu256_2Fnode-utility2_2Ftmp_2Fbuild_2Ftest-report.html.png)\n\n#### output from istanbul\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.browser._2Ftmp_2Fapp_2Ftmp_2Fbuild_2Fcoverage.html_2Fapp_2Fexample.js.html.png)\n\n#### output from shell\n![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.testExampleJs.svg)\n\n\n\n# package.json\n'''json\n{\n    \"author\": \"kai zhu <kaizhu256@gmail.com>\",\n    \"bin\": {\n        \"utility2\": \"lib.utility2.sh\",\n        \"utility2-apidoc\": \"lib.apidoc.js\",\n        \"utility2-github-crud\": \"lib.github_crud.js\",\n        \"utility2-istanbul\": \"lib.istanbul.js\",\n        \"utility2-jslint\": \"lib.jslint.js\",\n        \"utility2-uglifyjs\": \"lib.uglifyjs.js\"\n    },\n    \"description\": \"the zero-dependency swiss-army-knife tool for building, testing, and deploying webapps\",\n    \"devDependencies\": {\n        \"electron-lite\": \"kaizhu256/node-electron-lite#alpha\"\n    },\n    \"engines\": {\n        \"node\": \">=4.0\"\n    },\n    \"homepage\": \"https://github.com/kaizhu256/node-utility2\",\n    \"keywords\": [\n        \"browser\",\n        \"build\",\n        \"busybox\",\n        \"ci\",\n        \"code-coverage\",\n        \"continuous-integration\",\n        \"deploy\",\n        \"docker\",\n        \"electron\",\n        \"headless-browser\",\n        \"istanbul\",\n        \"jscover\",\n        \"jscoverage\",\n        \"phantomjs\",\n        \"slimerjs\",\n        \"swiss-army-knife\",\n        \"test\",\n        \"test-coverage\",\n        \"travis\",\n        \"travis-ci\",\n        \"utility2\",\n        \"webapp\"\n    ],\n    \"license\": \"MIT\",\n    \"main\": \"lib.utility2.js\",\n    \"name\": \"utility2\",\n    \"nameAlias\": \"utility2\",\n    \"nameAliasPublish\": \"busybox npmtest-lite test-lite\",\n    \"nameOriginal\": \"utility2\",\n    \"os\": [\n        \"darwin\",\n        \"linux\"\n    ],\n    \"readmeParse\": \"1\",\n    \"repository\": {\n        \"type\": \"git\",\n        \"url\": \"https://github.com/kaizhu256/node-utility2.git\"\n    },\n    \"scripts\": {\n        \"build-ci\": \"./lib.utility2.sh shReadmeTest build_ci.sh\",\n        \"env\": \"env\",\n        \"heroku-postbuild\": \"./lib.utility2.sh shDeployHeroku\",\n        \"postinstall\": \"if [ -f npm_scripts.sh ]; then ./npm_scripts.sh postinstall; fi\",\n        \"start\": \"(set -e; export PORT=${PORT:-8080}; if [ -f assets.app.js ]; then node assets.app.js; exit; fi; export npm_config_mode_auto_restart=1; ./lib.utility2.sh shRun shIstanbulCover test.js)\",\n        \"test\": \"(set -e; export PORT=$(./lib.utility2.sh shServerPortRandom); export PORT_REPL=$(./lib.utility2.sh shServerPortRandom); export npm_config_mode_auto_restart=1; ./lib.utility2.sh test test.js)\"\n    },\n    \"version\": \"2017.3.22\"\n}\n'''\n\n\n\n# changelog of last 50 commits\n[![screen-capture](https://kaizhu256.github.io/node-utility2/build/screen-capture.gitLog.svg)](https://github.com/kaizhu256/node-utility2/commits)\n\n\n\n# internal build-script\n- Dockerfile.base\n'''shell\n# Dockerfile.base\n# docker build -f tmp/README.Dockerfile.base -t kaizhu256/node-utility2:base .\n# docker build -f \"tmp/README.Dockerfile.$DOCKER_TAG\" -t \"$GITHUB_REPO:$DOCKER_TAG\" .\n# https://hub.docker.com/_/node/\nFROM debian:stable-slim\nMAINTAINER kai zhu <kaizhu256@gmail.com>\nVOLUME [ \\\n  \"/mnt\", \\\n  \"/root\", \\\n  \"/tmp\", \\\n  \"/usr/share/doc\", \\\n  \"/usr/share/man\", \\\n  \"/var/cache\", \\\n  \"/var/lib/apt\", \\\n  \"/var/log\", \\\n  \"/var/tmp\" \\\n]\nWORKDIR /tmp\n# install nodejs\n# https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        apt-utils \\\n        busybox \\\n        ca-certificates \\\n        curl && \\\n    (busybox --list | xargs -n1 /bin/sh -c 'ln -s /bin/busybox /bin/$0 2>/dev/null' || true) \\\n        && \\\n    curl -sL https://deb.nodesource.com/setup_6.x | /bin/bash - && \\\n    apt-get install -y nodejs\n# install electron-lite\nVOLUME [ \\\n  \"/usr/lib/chromium\" \\\n]\n# COPY electron-*.zip /tmp\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        chromium \\\n        gconf2 \\\n        git \\\n        xvfb && \\\n    npm install \"kaizhu256/node-electron-lite#alpha\" && \\\n    cd node_modules/electron-lite && \\\n    npm install && \\\n    export DISPLAY=:99.0 && \\\n    (Xvfb \"$DISPLAY\" &) && \\\n    npm test && \\\n    cp /tmp/electron-*.zip /\n# install extras\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        nginx-extras \\\n        transmission-daemon \\\n        ssh \\\n        vim\n'''\n\n- Dockerfile.elasticsearch\n'''shell\n# Dockerfile.elasticsearch\nFROM kaizhu256/node-utility2:latest\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# install swagger-ui\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    rm -fr /swagger-ui && \\\n    git clone --branch=v2.1.5 --single-branch \\\n        https://github.com/swagger-api/swagger-ui.git && \\\n    mv swagger-ui/dist /swagger-ui\n'''\n\n- Dockerfile.emscripten\n'''shell\n# Dockerfile.emscripten\n# docker build -f tmp/README.Dockerfile.emscripten -t emscripten .\nFROM kaizhu256/node-utility2:latest\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# https://kripken.github.io/emscripten-site/docs\n# /building_from_source/building_emscripten_from_source_using_the_sdk.html\n# build emscripten v1.36.0\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    mkdir -p /usr/share/man/man1 && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        cmake && \\\n    cd / && \\\n    git clone https://github.com/juj/emsdk.git --branch=master --single-branch && \\\n    cd /emsdk && \\\n    ./emsdk install -j2 --shallow sdk-master-64bit && \\\n    ./emsdk activate && \\\n    find . -name \".git\" -print0 | xargs -0 rm -fr && \\\n    find . -name \"src\" -print0 | xargs -0 rm -fr\n'''\n\n- Dockerfile.latest\n'''shell\n# Dockerfile.latest\nFROM kaizhu256/node-utility2:base\nMAINTAINER kai zhu <kaizhu256@gmail.com>\n# install elasticsearch and kibana\nRUN export DEBIAN_FRONTEND=noninteractive && \\\n    mkdir -p /usr/share/man/man1 && \\\n    apt-get update && \\\n    apt-get install --no-install-recommends -y \\\n        default-jre && \\\n    curl -#Lo elasticsearch.tar.gz \\\n        https://download.elastic.co/elasticsearch/elasticsearch/elasticsearch-1.7.6.tar.gz && \\\n    rm -fr /elasticsearch && \\\n    mkdir -p /elasticsearch && \\\n    tar -xzf elasticsearch.tar.gz --strip-components=1 -C /elasticsearch && \\\n    curl -#Lo kibana.tar.gz https://download.elastic.co/kibana/kibana/kibana-3.1.3.tar.gz && \\\n    rm -fr /kibana && \\\n    mkdir -p /kibana && \\\n    tar -xzf kibana.tar.gz --strip-components=1 -C /kibana\n'''\n\n- build_ci.sh\n'''shell\n# build_ci.sh\n\n# this shell script will run the build for this package\n\nshBuildCiInternalPost() {(set -e\n    #// coverage-hack\n    shDeployGithub\n    shDeployHeroku\n    shReadmeBuildLinkVerify\n)}\n\nshBuildCiInternalPre() {(set -e\n    shReadmeTest example.js\n    # save screen-capture\n    (export MODE_BUILD=testExampleJs\n        export modeBrowserTest=screenCapture\n        export url=\"/tmp/app/tmp/build/coverage.html/app/example.js.html\"\n        shBrowserTest\n        export url=\"$npm_config_dir_build/test-report.html\"\n        shBrowserTest)\n    shReadmeTest example.sh\n    shNpmTestPublished\n)}\n\n# run shBuildCi\n. ./lib.utility2.sh\nshBuildCi\n'''\n\n\n\n# misc\n- this package was created with [utility2](https://github.com/kaizhu256/node-utility2)\n",
    "readmeFilename": "README.md",
    "readmeParse": "1",
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
    "version": "2017.3.22"
} \
\n\
''' \
\n\
',
/* jslint-ignore-end */
        modulePathList: options.modulePathList,
        template: local.apidoc.templateApidocMd
    });
    local.fs.writeFileSync('README.md', options.readme);
    // re-build package.json
    packageJson.description = (/\w.*/).exec(options.readme)[0]
        .replace((/ {2,}/g), ' ')
        .trim();
    local.fs.writeFileSync(
        'package.json',
        local.jsonStringifyOrdered(packageJson, null, 4) + '\n'
    );
    onParallel();
}
```
- example usage
```shell
...
    onError\n\
) {\n\
/*\n\
 * this function will test buildApidoc\'s default handling-behavior-behavior\n\
 */\n\
    options = { modulePathList: module.paths };\n\
    if (local.env.npm_package_buildNpmdoc) {\n\
        local.buildNpmdoc(options, onError);\n\
        return;\n\
    }\n\
    local.buildApidoc(options, onError);\n\
};\n\
\n\
local.testCase_buildApp_default = local.testCase_buildApp_default || function (\n\
    options,\n\
...
```

#### <a name="apidoc.element.utility2.buildReadme"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildReadme (options, onError)](#apidoc.element.utility2.buildReadme)
- description and source-code
```javascript
buildReadme = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the readme in jslint-lite style
 */
</span>    local.objectSetDefault(options, {
        customize: local.nop,
        dataFrom: local.tryCatchReadFile('README.md', 'utf8')
    });
    // init package.json
    options.rgx = (/\n# package.json\n'''json\n([\S\s]*?)\n'''\n/);
    options.dataFrom.replace(options.rgx, function (match0, match1) {
        options.packageJson = JSON.parse(match1);
        options.packageJson.description = options.dataFrom.split('\n')[1];
        local.objectSetDefault(options.packageJson, {
            nameAlias: options.packageJson.name.replace((/\W/g), '_'),
            nameOriginal: options.packageJson.name
        });
        local.objectSetDefault(
            options.packageJson,
            JSON.parse(local.templateRenderJslintLite(
                options.rgx.exec(local.assetsDict['/assets.readme.template.md'])[1],
                options
            )),
            2
        );
        // avoid npm-installing self
        delete options.packageJson.devDependencies[options.packageJson.name];
        // save package.json
        local.fs.writeFileSync(
            'package.json',
            local.jsonStringifyOrdered(options.packageJson, null, 4) + '\n'
        );
        // update dataTo
        options.dataTo = local.templateRenderJslintLite(
            local.assetsDict['/assets.readme.template.md'],
            options
        );
        options.dataTo = options.dataTo.replace(
            options.rgx,
            match0.replace(
                match1,
                local.jsonStringifyOrdered(options.packageJson, null, 4)
            )
        );
    });
    // search-and-replace - customize dataTo
    [
        // customize header
        (/.*?\n.*?\n/),
        // customize todo
        (/\n#### todo\n[\S\s]*?\n\n\n\n/),
        // customize quickstart-header
        (/\n'''javascript\n\/\*\nexample\.js\n\n[^']*?\n/),
        (/\n {8}\$ npm install [^']*? &&/),
        (/\n {12}: global;\n[^']*?\n {8}local\.global\.local = local;\n/),
        (/\n {8}local\.global\.local = local;\n[^']*?\n {4}\/\/ post-init\n/),
        new RegExp('\\n {8}local\\.testRunBrowser = function \\(event\\) \\{\\n' +
            '[^']*?^ {12}if \\(!event \\|\\| \\(event &&\\n', 'm'),
        (/\n {12}\/\/ custom-case\n[^']*?\n {12}\}\n/),
        // customize quickstart-html-style
        (/\n<\/style>\\n\\\n<style>\\n\\\n[^']*?\\n\\\n<\/style>\\n\\\n/),
        // customize quickstart-html-body
        (/\nutility2-comment -->(?:\\n\\\n){4}[^']*?^<!-- utility2-comment\\n\\\n/m),
        // customize build-script
        (/\n# internal build-script\n[\S\s]*?^- build_ci\.sh\n/m),
        (/\nshBuildCiInternalPost\(\) \{\(set -e\n[^']*?\n\)\}\n/),
        (/\nshBuildCiInternalPre\(\) \{\(set -e\n[^']*?\n\)\}\n/),
        (/\nshBuildCiPost\(\) \{\(set -e\n[^']*?\n\)\}\n/),
        (/\nshBuildCiPre\(\) \{\(set -e\n[^']*?\n\)\}\n/)
    ].forEach(function (rgx) {
        // handle large string-replace
        options.dataFrom.replace(rgx, function (match0) {
            options.dataTo.replace(rgx, function (match1) {
                options.dataTo = options.dataTo.split(match1);
                options.dataTo[0] += match0;
                options.dataTo[0] += options.dataTo.splice(1, 1)[0];
                options.dataTo = options.dataTo.join(match1);
            });
        });
    });
    // customize comment
    options.dataFrom.replace(
        (/^( *?)(?:#!! |#\/\/ |\/\/!!)(.*?)$/gm),
        function (match0, match1, match2) {
            options.dataTo = options.dataTo.replace(match1 + match2, match0);
        }
    );
    options.customize();
    // save README.md
    local.fs.writeFileSync('README.md', options.dataTo);
    onError();
}
```
- example usage
```shell
...
 * this function will test buildReadme\'s default handling-behavior-behavior\n\
 */\n\
    if (local.env.npm_package_buildNpmdoc) {\n\
        onError();\n\
        return;\n\
    }\n\
    options = {};\n\
    local.buildReadme(options, onError);\n\
};\n\
\n\
local.testCase_buildTest_default = local.testCase_buildTest_default || function (\n\
    options,\n\
    onError\n\
) {\n\
/*\n\
...
```

#### <a name="apidoc.element.utility2.buildTest"></a>[function <span class="apidocSignatureSpan">utility2.</span>buildTest (options, onError)](#apidoc.element.utility2.buildTest)
- description and source-code
```javascript
buildTest = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will build the test
 */
</span>    local.objectSetDefault(options, {
        customize: local.nop,
        dataFrom: local.tryCatchReadFile('test.js', 'utf8'),
        dataTo: local.templateRenderJslintLite(
            local.assetsDict['/assets.test.template.js'],
            {}
        )
    });
    // search-and-replace - customize dataTo
    [
        // customize js\-env code
        new RegExp('\\n {4}\\/\\/ run shared js\\-env code - pre-init\\n[\\S\\s]*?' +
            '^ {4}\\(function \\(\\) \\{\\n', 'm'),
        (/\n {8}local.global.local = local;\n[\S\s]*?^ {4}\}\(\)\);\n/m),
        (/\n {4}\/\/ run shared js\-env code - function\n[\S\s]*?\n {4}\}\(\)\);\n/),
        (/\n {4}\/\/ run browser js\-env code - function\n[\S\s]*?\n {8}break;\n/),
        (/\n {4}\/\/ run node js\-env code - function\n[\S\s]*?\n {8}break;\n/),
        new RegExp('\\n {4}\\/\\/ run browser js\\-env code - post-init\\n[\\S\\s]*?' +
            '^ {4}case \'browser\':\n', 'm'),
        (/\n {4}\/\/ run shared js\-env code - post-init\n[\S\s]*?\n {4}\}\(\)\);\n/)
    ].forEach(function (rgx) {
        // handle large string-replace
        options.dataFrom.replace(rgx, function (match0) {
            options.dataTo.replace(rgx, function (match1) {
                options.dataTo = options.dataTo.split(match1);
                options.dataTo[0] += match0;
                options.dataTo[0] += options.dataTo.splice(1, 1)[0];
                options.dataTo = options.dataTo.join(match1);
            });
        });
    });
    options.customize();
    // save test.js
    local.fs.writeFileSync('test.js', options.dataTo);
    onError();
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will test buildTest\'s default handling-behavior\n\
 */\n\
    options = {};\n\
    local.buildTest(options, onError);\n\
};\n\
\n\
local.testCase_webpage_default = local.testCase_webpage_default || function (\n\
    options,\n\
    onError\n\
) {\n\
/*\n\
...
```

#### <a name="apidoc.element.utility2.cookieDict"></a>[function <span class="apidocSignatureSpan">utility2.</span>cookieDict ()](#apidoc.element.utility2.cookieDict)
- description and source-code
```javascript
cookieDict = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will return a dict of all cookies
 */
</span>    var result;
    result = {};
    document.cookie.replace((/(\w+)=([^;]*)/g), function (match0, match1, match2) {
        // jslint-hack
        local.nop(match0);
        result[match1] = match2;
    });
    return result;
}
```
- example usage
```shell
...
        /*
* this function will test cookieXxx's default handling-behavior
*/
   options = {};
   // test cookieRemoveAll handling-behavior
   local.cookieRemoveAll();
   // validate data
   options.data = local.cookieDict().aa;
   local.assertJsonEqual(options.data, undefined);
   // test cookieSet handling-behavior
   local.cookieSet('aa', 'bb', 1000);
   // validate data
   options.data = local.cookieDict().aa;
   local.assertJsonEqual(options.data, 'bb');
   // test cookieRemove handling-behavior
...
```

#### <a name="apidoc.element.utility2.cookieRemove"></a>[function <span class="apidocSignatureSpan">utility2.</span>cookieRemove (name)](#apidoc.element.utility2.cookieRemove)
- description and source-code
```javascript
cookieRemove = function (name) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the cookie with the given name
 */
</span>    document.cookie = name + '=; expires=Thu, 01 Jan 1970 00:00:00 GMT';
}
```
- example usage
```shell
...
local.assertJsonEqual(options.data, undefined);
// test cookieSet handling-behavior
local.cookieSet('aa', 'bb', 1000);
// validate data
options.data = local.cookieDict().aa;
local.assertJsonEqual(options.data, 'bb');
// test cookieRemove handling-behavior
local.cookieRemove('aa');
// validate data
options.data = local.cookieDict().aa;
local.assertJsonEqual(options.data, undefined);
// test cookieSet handling-behavior
local.cookieSet('aa', 'bb', 1000);
// test cookieRemoveAll handling-behavior
local.cookieRemoveAll();
...
```

#### <a name="apidoc.element.utility2.cookieRemoveAll"></a>[function <span class="apidocSignatureSpan">utility2.</span>cookieRemoveAll ()](#apidoc.element.utility2.cookieRemoveAll)
- description and source-code
```javascript
cookieRemoveAll = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will remove all cookies
 */
</span>    document.cookie.replace((/(\w+)=/g), function (match0, match1) {
        // jslint-hack
        local.nop(match0);
        document.cookie = match1 + '=; expires=Thu, 01 Jan 1970 00:00:00 GMT';
    });
}
```
- example usage
```shell
...

local.testCase_cookieXxx_default = function (options, onError) {
/*
 * this function will test cookieXxx's default handling-behavior
 */
    options = {};
    // test cookieRemoveAll handling-behavior
    local.cookieRemoveAll();
    // validate data
    options.data = local.cookieDict().aa;
    local.assertJsonEqual(options.data, undefined);
    // test cookieSet handling-behavior
    local.cookieSet('aa', 'bb', 1000);
    // validate data
    options.data = local.cookieDict().aa;
...
```

#### <a name="apidoc.element.utility2.cookieSet"></a>[function <span class="apidocSignatureSpan">utility2.</span>cookieSet (name, value, expiresOffset)](#apidoc.element.utility2.cookieSet)
- description and source-code
```javascript
cookieSet = function (name, value, expiresOffset) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the cookie with the given name, value,
 * and expiresOffset (in ms)
 */
</span>    var tmp;
    tmp = name + '=' + value + '; expires=' +
        new Date(Date.now() + expiresOffset).toUTCString();
    document.cookie = tmp;
    return tmp;
}
```
- example usage
```shell
...
options = {};
// test cookieRemoveAll handling-behavior
local.cookieRemoveAll();
// validate data
options.data = local.cookieDict().aa;
local.assertJsonEqual(options.data, undefined);
// test cookieSet handling-behavior
local.cookieSet('aa', 'bb', 1000);
// validate data
options.data = local.cookieDict().aa;
local.assertJsonEqual(options.data, 'bb');
// test cookieRemove handling-behavior
local.cookieRemove('aa');
// validate data
options.data = local.cookieDict().aa;
...
```

#### <a name="apidoc.element.utility2.db._DbTable"></a>[function <span class="apidocSignatureSpan">utility2.</span>db._DbTable (options)](#apidoc.element.utility2.db._DbTable)
- description and source-code
```javascript
db._DbTable = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a dbTable
 */
</span>    options = local.normalizeDict(options);
    this.name = String(options.name);
    // register dbTable in dbTableDict
    local.dbTableDict[this.name] = this;
    this.dbRowList = [];
    this.isDirty = null;
    this.idIndexList = [{ name: '_id', dict: {} }];
    this.ttl = 0;
    this.ttlLast = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.domFragmentRender"></a>[function <span class="apidocSignatureSpan">utility2.</span>domFragmentRender (template, dict)](#apidoc.element.utility2.domFragmentRender)
- description and source-code
```javascript
domFragmentRender = function (template, dict) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a dom-fragment rendered from the givent template and dict
 */
</span>    var tmp;
    tmp = document.createElement('template');
    tmp.innerHTML = local.templateRender(template, dict);
    return tmp.content;
}
```
- example usage
```shell
...
var resource, self;
// reset state
local.idDomElementDict = {};
self = local.uiState = local.jsonCopy(local.swaggerJson);
// init url
self.url = document.querySelector('.swggUiContainer > .header > .td2').value;
// templateRender main
self.uiFragment = local.domFragmentRender(local.templateUiMain, self);
local.objectSetDefault(self, {
    resourceDict: {},
    operationDict: {},
    tagDict: {}
});
// init tagDict
self.tags.forEach(function (tag) {
...
```

#### <a name="apidoc.element.utility2.echo"></a>[function <span class="apidocSignatureSpan">utility2.</span>echo (arg)](#apidoc.element.utility2.echo)
- description and source-code
```javascript
echo = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will return the arg
 */
</span>    return arg;
}
```
- example usage
```shell
...
};

local.testCase_echo_default = function (options, onError) {
/*
 * this function will test echo's default handling-behavior
 */
    options = {};
    options.data = local.echo('aa');
    local.assertJsonEqual(options.data, 'aa');
    onError();
};

local.testCase_exit_default = function (options, onError) {
/*
 * this function will exit's default handling-behavior
...
```

#### <a name="apidoc.element.utility2.errorMessagePrepend"></a>[function <span class="apidocSignatureSpan">utility2.</span>errorMessagePrepend (error, message)](#apidoc.element.utility2.errorMessagePrepend)
- description and source-code
```javascript
errorMessagePrepend = function (error, message) {
<span class="apidocCodeCommentSpan">/*
 * this function will prepend the message to error.message and error.stack
 */
</span>    error.message = message + error.message;
    error.stack = message + error.stack;
    return error;
}
```
- example usage
```shell
...
         */
local.onErrorJsonapi(function (error, data) {
    local.serverRespondHeadSet(request, response, error && error.statusCode, {
        'Content-Type': 'application/json; charset=UTF-8'
    });
    if (error) {
        // debug statusCode / method / url
        local.errorMessagePrepend(error, response.statusCode + ' ' +
            request.method + ' ' + request.url + '\n');
        // print error.stack to stderr
        local.onErrorDefault(error);
    }
    data = error || data;
    data.meta.statusCode = response.statusCode =
        data.meta.statusCode || response.statusCode;
...
```

#### <a name="apidoc.element.utility2.exit"></a>[function <span class="apidocSignatureSpan">utility2.</span>exit (exitCode)](#apidoc.element.utility2.exit)
- description and source-code
```javascript
exit = function (exitCode) {
<span class="apidocCodeCommentSpan">/*
 * this function will exit the current process with the given exitCode
 */
</span>    exitCode = !exitCode || Number(exitCode) === 0
        ? 0
        : Number(exitCode) || 1;
    switch (local.modeJs) {
    case 'browser':
        console.log(JSON.stringify({
            global_test_results: local.global.global_test_results
        }));
        break;
    case 'node':
        process.exit(exitCode);
        break;
    }
    // reset modeTest
    local.modeTest = null;
}
```
- example usage
```shell
...
                local.jslintAndPrint(
                    local.fs.readFileSync(local.path.resolve(arg), 'utf8'),
                    arg
                );
            }
        });
        // if error occurred, then exit with non-zero code
        process.exit(local.errorCounter);
        break;
    }
}());
...
```

#### <a name="apidoc.element.utility2.fsRmrSync"></a>[function <span class="apidocSignatureSpan">utility2.</span>fsRmrSync (dir)](#apidoc.element.utility2.fsRmrSync)
- description and source-code
```javascript
fsRmrSync = function (dir) {
<span class="apidocCodeCommentSpan">/*
 * this function will synchronously 'rm -fr' the dir
 */
</span>    local.child_process.spawnSync(
        'rm',
        ['-fr', local.path.resolve(process.cwd(), dir)],
        { stdio: ['ignore', 1, 2] }
    );
}
```
- example usage
```shell
...
};

local.buildApp = function (optionsList, onError) {
/*
 * this function will build the app
 */
    var onParallel;
    local.fsRmrSync(local.env.npm_config_dir_build + '/app');
    onParallel = local.onParallel(function (error) {
        /* istanbul ignore next */
        if (!local.global.__coverage__) {
            local.fs.writeFileSync(
                'assets.' + local.env.npm_package_nameAlias + '.rollup.js',
                local.assetsDict['/assets.' + local.env.npm_package_nameAlias +
                    '.rollup.js'] ||
...
```

#### <a name="apidoc.element.utility2.fsWriteFileWithMkdirpSync"></a>[function <span class="apidocSignatureSpan">utility2.</span>fsWriteFileWithMkdirpSync (file, data)](#apidoc.element.utility2.fsWriteFileWithMkdirpSync)
- description and source-code
```javascript
fsWriteFileWithMkdirpSync = function (file, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will synchronously 'mkdir -p' and write the data to file
 */
</span>    // try to write to file
    try {
        require('fs').writeFileSync(file, data);
    } catch (errorCaught) {
        // mkdir -p
        require('child_process').spawnSync(
            'mkdir',
            ['-p', require('path').dirname(file)],
            { stdio: ['ignore', 1, 2] }
        );
        // re-write to file
        require('fs').writeFileSync(file, data);
    }
}
```
- example usage
```shell
...
    options.timeoutDefault,
    options.testName
);
// init file urlBrowser
options.modeNext = 20;
options.urlBrowser = local.env.npm_config_dir_tmp + '/electron.' +
    Date.now().toString(16) + Math.random().toString(16) + '.html';
local.fsWriteFileWithMkdirpSync(options.urlBrowser, '<style>body {' +
        'border: 1px solid black;' +
        'margin: 0;' +
        'padding: 0;' +
    '}</style>' +
    '<webview id=webview1 src="' +
    options.url.replace('{{timeExit}}', options.timeExit) +
    '" style="' +
...
```

#### <a name="apidoc.element.utility2.httpRequest"></a>[function <span class="apidocSignatureSpan">utility2.</span>httpRequest (options, onError)](#apidoc.element.utility2.httpRequest)
- description and source-code
```javascript
httpRequest = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will request the data from options.url
 */
</span>    var chunkList, onError2, timerTimeout, done, request, response, urlParsed;
    // init onError2
    onError2 = function (error) {
        if (done) {
            return;
        }
        done = true;
        // cleanup timerTimeout
        clearTimeout(timerTimeout);
        // cleanup request and response
        [request, response].forEach(function (stream) {
            // try to end the stream
            try {
                stream.end();
            // else try to destroy the stream
            } catch (errorCaught) {
                try {
                    stream.destroy();
                } catch (ignore) {
                }
            }
        });
        // debug response
        console.error(new Date().toISOString() + ' http-response ' + JSON.stringify({
            method: options.method,
            url: options.url,
            statusCode: (response && response.statusCode) || 0
        }));
        onError(error, response);
    };
    // init timerTimeout
    timerTimeout = setTimeout(function () {
        onError2(new Error('http-request timeout'));
    }, options.timeout || 30000);
    urlParsed = require('url').parse(options.url);
    urlParsed.headers = options.headers;
    urlParsed.method = options.method;
    // debug request
    console.error();
    console.error(new Date().toISOString() + ' http-request ' + JSON.stringify({
        method: options.method,
        url: options.url
    }));
    request = require(
        urlParsed.protocol.slice(0, -1)
    ).request(urlParsed, function (_response) {
        response = _response;
        if (response.statusCode < 200 || response.statusCode > 299) {
            onError2(new Error(response.statusCode));
            return;
        }
        chunkList = [];
        response
            .on('data', function (chunk) {
                chunkList.push(chunk);
            })
            .on('end', function () {
                response.data = Buffer.concat(chunkList);
                onError2();
            })
            .on('error', onError2);
    }).on('error', onError2);
    request.end(options.data);
}
```
- example usage
```shell
...
         */
options = { file: options.file, message: options.message, url: options.url };
local.onNext(options, function (error, data) {
    switch (options.modeNext) {
    case 1:
        // get file from url
        if ((/^(?:http|https):\/\//).test(options.file)) {
            local.httpRequest({
                method: 'GET',
                url: options.file
            }, function (error, response) {
                options.onNext(error, response && response.data);
            });
            return;
        }
...
```

#### <a name="apidoc.element.utility2.isNullOrUndefined"></a>[function <span class="apidocSignatureSpan">utility2.</span>isNullOrUndefined (arg)](#apidoc.element.utility2.isNullOrUndefined)
- description and source-code
```javascript
isNullOrUndefined = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will test if the arg is null or undefined
 */
</span>    return arg === null || arg === undefined;
}
```
- example usage
```shell
...
        /*
* this function will run the middleware that will parse request.bodyRaw
*/
   var ii, jj, options;
   // jslint-hack
   local.nop(response);
   // if request is already parsed, then goto nextMiddleware
   if (!local.isNullOrUndefined(request.swgg.bodyParsed)) {
       nextMiddleware();
       return;
   }
   switch (String(request.headers['content-type']).split(';')[0]) {
   // parse application/x-www-form-urlencoded, e.g.
   // aa=hello%20world&bb=bye%20world
   case 'application/x-www-form-urlencoded':
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbul.HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport)
- description and source-code
```javascript
function HtmlReport(e){Report.call(this),this.opts=e||{},this.opts.dir=this.opts.dir||path.resolve(
process.cwd(),"html-report"),this.opts.sourceStore=this.opts.sourceStore||Store.
create("fslookup"),this.opts.linkMapper=this.opts.linkMapper||this.standardLinkMapper
(),this.opts.writer=this.opts.writer||null,this.opts.templateData={datetime:Date
()},this.opts.watermarks=this.opts.watermarks||defaults.watermarks()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbul.Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter)
- description and source-code
```javascript
function g(e){this.opts=e||{debug:!1,walkDebug:!1,coverageVariable:"__coverage__"
,codeGenerationOptions:undefined,noAutoWrap:!1,noCompact:!1,embedSource:!1,preserveComments
:!1},this.walker=new v({ArrowFunctionExpression:[this.arrowBlockConverter],ExpressionStatement
:this.coverStatement,BreakStatement:this.coverStatement,ContinueStatement:this.coverStatement
,DebuggerStatement:this.coverStatement,ReturnStatement:this.coverStatement,ThrowStatement
:this.coverStatement,TryStatement:[this.paranoidHandlerCheck,this.coverStatement
],VariableDeclaration:this.coverStatement,IfStatement:[this.ifBlockConverter,this
.coverStatement,this.ifBranchInjector],ForStatement:[this.skipInit,this.loopBlockConverter
,this.coverStatement],ForInStatement:[this.skipLeft,this.loopBlockConverter,this
.coverStatement],ForOfStatement:[this.skipLeft,this.loopBlockConverter,this.coverStatement
],WhileStatement:[this.loopBlockConverter,this.coverStatement],DoWhileStatement:
[this.loopBlockConverter,this.coverStatement],SwitchStatement:[this.coverStatement
,this.switchBranchInjector],SwitchCase:[this.switchCaseInjector],WithStatement:[
this.withBlockConverter,this.coverStatement],FunctionDeclaration:[this.coverFunction
,this.coverStatement],FunctionExpression:this.coverFunction,LabeledStatement:this
.coverStatement,ConditionalExpression:this.conditionalBranchInjector,LogicalExpression
:this.logicalExpressionBranchInjector,ObjectExpression:this.maybeAddType},this.extractCurrentHint
,this,this.opts.walkDebug),this.opts.backdoor&&this.opts.backdoor.omitTrackerSuffix&&
(this.omitTrackerSuffix=!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.TextReport"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbul.TextReport (e)](#apidoc.element.utility2.istanbul.TextReport)
- description and source-code
```javascript
function TextReport(e){Report.call(this),e=e||{},this.dir=e.dir||process.cwd(),this
.file=e.file,this.summary=e.summary,this.maxCols=e.maxCols||0,this.watermarks=e.
watermarks||defaults.watermarks()}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.require"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbul.require (path)](#apidoc.element.utility2.istanbul.require)
- description and source-code
```javascript
function require(path) {
  try {
    exports.requireDepth += 1;
    return self.require(path);
  } finally {
    exports.requireDepth -= 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbulCoverageMerge"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbulCoverageMerge (coverage1, coverage2)](#apidoc.element.utility2.istanbulCoverageMerge)
- description and source-code
```javascript
istanbulCoverageMerge = function (coverage1, coverage2) {
<span class="apidocCodeCommentSpan">/*
 * this function will merge coverage2 into coverage1
 */
</span>    var dict1, dict2;
    coverage1 = coverage1 || {};
    coverage2 = coverage2 || {};
    Object.keys(coverage2).forEach(function (file) {
        if (!coverage2[file]) {
            return;
        }
        // if file is undefined in coverage1, then add it
        if (!coverage1[file]) {
            coverage1[file] = coverage2[file];
            return;
        }
        // merge file from coverage2 into coverage1
        ['b', 'f', 's'].forEach(function (key) {
            dict1 = coverage1[file][key];
            dict2 = coverage2[file][key];
            switch (key) {
            // increment coverage for branch lines
            case 'b':
                Object.keys(dict2).forEach(function (key) {
                    dict2[key].forEach(function (count, ii) {
                        dict1[key][ii] += count;
                    });
                });
                break;
            // increment coverage for function and statement lines
            case 'f':
            case 's':
                Object.keys(dict2).forEach(function (key) {
                    dict1[key] += dict2[key];
                });
                break;
            }
        });
    });
    return coverage1;
}
```
- example usage
```shell
...
    // try to JSON.parse the string
    local.tryCatchOnError(function () {
        data = JSON.parse(
            local.fs.readFileSync(options.fileCoverage, 'utf8')
        );
    }, local.nop);
    if (!local._debugTryCatchErrorCaught) {
        local.istanbulCoverageMerge(local.global.__coverage__, data);
        console.log('\nbrowserTest - merged coverage from ' +
            options.fileCoverage + '\n');
    }
}
if (options.modeBrowserTest !== 'test') {
    modeNext = Infinity;
    onNext();
...
```

#### <a name="apidoc.element.utility2.istanbulCoverageReportCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbulCoverageReportCreate ()](#apidoc.element.utility2.istanbulCoverageReportCreate)
- description and source-code
```javascript
istanbulCoverageReportCreate = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. print coverage in text-format to stdout
 * 2. write coverage in html-format to filesystem
 * 3. return coverage in html-format as single document
 */
</span>    var options;
    /* istanbul ignore next */
    if (!local.global.__coverage__) {
        return '';
    }
    options = {};
    options.dir = process.cwd() + '/tmp/build/coverage.html';
    // merge previous coverage
    if (local.modeJs === 'node' && process.env.npm_config_mode_coverage_merge) {
        console.log('merging file://' + options.dir + '/coverage.json to coverage');
        try {
            local.coverageMerge(
                local.global.__coverage__,
                JSON.parse(
                    local._fs.readFileSync(options.dir + '/coverage.json', 'utf8')
                )
            );
        } catch (ignore) {
        }
        try {
            options.coverageCodeDict = JSON.parse(local._fs.readFileSync(
                options.dir + '/coverage.code-dict.json',
                'utf8'
            ));
            Object.keys(options.coverageCodeDict).forEach(function (key) {
                local.global.__coverageCodeDict__[key] =
                    local.global.__coverageCodeDict__[key] ||
                    options.coverageCodeDict[key];
            });
        } catch (ignore) {
        }
    }
    // init writer
    local.coverageReportHtml = '';
    local.coverageReportHtml += '<div class="coverageReportDiv">\n' +
        '<h1>coverage-report</h1>\n' +
        '<div ' +
        'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
    local.writerData = '';
    options.sourceStore = {};
    options.writer = local.writer;
    // 1. print coverage in text-format to stdout
    new local.TextReport(options).writeReport(local.collector);
    // 2. write coverage in html-format to filesystem
    new local.HtmlReport(options).writeReport(local.collector);
    local.writer.writeFile('', local.nop);
    // write coverage.json
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.json',
        JSON.stringify(local.global.__coverage__)
    );
    // write coverage.code-dict.json
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.code-dict.json',
        JSON.stringify(local.global.__coverageCodeDict__)
    );
    // write coverage.badge.svg
    options.pct = local.coverageReportSummary.root.metrics.lines.pct;
    local.fsWriteFileWithMkdirpSync2(
        local.path.dirname(options.dir) + '/coverage.badge.svg',
        local.templateCoverageBadgeSvg
            // edit coverage badge percent
            .replace((/100.0/g), options.pct)
            // edit coverage badge color
            .replace(
                (/0d0/g),
                ('0' + Math.round((100 - options.pct) * 2.21).toString(16)).slice(-2) +
                    ('0' + Math.round(options.pct * 2.21).toString(16)).slice(-2) + '00'
            )
    );
    console.log('created coverage file://' + options.dir + '/index.html');
    // 3. return coverage in html-format as a single document
    local.coverageReportHtml += '</div>\n</div>\n';
    // write coverage.rollup.html
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.rollup.html',
        local.coverageReportHtml
    );
    return local.coverageReportHtml;
}
```
- example usage
```shell
...
        JSON.stringify(testReport)
    );
    break;
}
setTimeout(function () {
    if (local.modeJs === 'browser') {
        // update coverageReport
        local.istanbulCoverageReportCreate({
            coverage: local.global.__coverage__
        });
        if (document.querySelector('#coverageReportDiv1')) {
            document.querySelector('#coverageReportDiv1').innerHTML =
                local.istanbul.coverageReportCreate({
                    coverage: window.__coverage__
                });
...
```

#### <a name="apidoc.element.utility2.istanbulInstrumentInPackage"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbulInstrumentInPackage (code, file)](#apidoc.element.utility2.istanbulInstrumentInPackage)
- description and source-code
```javascript
istanbulInstrumentInPackage = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will instrument the code
 * only if the macro /\* istanbul instrument in package $npm_package_nameAlias *\/
 * exists in the code
 */
</span>    return process.env.npm_config_mode_coverage &&
        code.indexOf('/* istanbul ignore all */\n') < 0 && (
            process.env.npm_config_mode_coverage === 'all' ||
            code.indexOf('/* istanbul instrument in package ' +
                    process.env.npm_package_nameAlias + ' */\n') >= 0 ||
            code.indexOf('/* istanbul instrument in package ' +
                    process.env.npm_config_mode_coverage + ' */\n') >= 0
        )
        ? local.instrumentSync(code, file)
        : code;
}
```
- example usage
```shell
...
    local[local.env.npm_package_nameAlias] = local;
    return local;
}
// init file $npm_package_main
tmp = process.cwd() + '/' + local.env.npm_package_main;
global.utility2_moduleExports = require(tmp);
local.assetsDict['/assets.' + local.env.npm_package_nameAlias + '.js'] =
    local.istanbulInstrumentInPackage(
        local.fs.readFileSync(tmp, 'utf8').replace((/^#!/), '//'),
        tmp
    );
global.utility2_moduleExports.global = global;
// read script from README.md
script = local.templateRenderJslintLite(
    local.assetsDict['/assets.example.template.js'],
...
```

#### <a name="apidoc.element.utility2.istanbulInstrumentSync"></a>[function <span class="apidocSignatureSpan">utility2.</span>istanbulInstrumentSync (code, file)](#apidoc.element.utility2.istanbulInstrumentSync)
- description and source-code
```javascript
istanbulInstrumentSync = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. normalize the file
 * 2. save code to __coverageCodeDict__[file] for future html-report
 * 3. return instrumented code
 */
</span>    // 1. normalize the file
    file = local.path.resolve('/', file);
    // 2. save code to __coverageCodeDict__[file] for future html-report
    local.global.__coverageCodeDict__[file] = code;
    // 3. return instrumented code
    return new local.Instrumenter({
        embedSource: true,
        noAutoWrap: true
    }).instrumentSync(code, file).trimLeft();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT"></a>[function <span class="apidocSignatureSpan">utility2.</span>jslint.JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT)
- description and source-code
```javascript
jslint.JSLINT = function (t, n){var r,o,u;S.errors=[],S.tree="",S.properties="",i=P=X=O=Object
.create(W["(begin)"]),V=[],_=Object.create(null),st(U),H=Object.create(null);if(
n){M=Object.create(n),o=M.predef;if(o)if(Array.isArray(o))for(r=0;r<o.length;r+=1
)_[o[r]]=!0;else typeof o=="object"&&st(o)}else M=Object.create(null);M.indent=+
M.indent||4,M.maxerr=+M.maxerr||50,b=q=Object.create(null),y=m={scope:q,loopage:0
,level:0},g=[m],s=[],f=[],l=!1,w=!1,E=null,x=!1,C=[],L=!1,D=!0,z=!1,$=null,J=0,T
.init(t),ot();try{dt();if(O.id==="(number)")O.stop("unexpected_a");else switch(O
.id){case"{":case"[":l=!0,x=!0,ln();break;default:bt(1),O.id===";"&&!L&&(O.edge=!0
,dt(";")),u=tn(),i.first=u,S.tree=i,u.disrupt&&P.warn("weird_program")}E=null,dt
("(end)"),S.property=H}catch(a){a&&S.errors.push({reason:a.message,line:a.line||
O.line,character:a.character||O.from},null)}return S.errors.length===0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslintAndPrint"></a>[function <span class="apidocSignatureSpan">utility2.</span>jslintAndPrint (script, file)](#apidoc.element.utility2.jslintAndPrint)
- description and source-code
```javascript
jslintAndPrint = function (script, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will jslint / csslint the script and print any errors to stderr
 */
</span>    var ignoreDict, lineno, scriptParsed;
    // cleanup errors
    local.errorCounter = 0;
    local.errorText = '';
    // do nothing for empty script
    if (!script.length) {
        return script;
    }
    // init ignoreDict
    ignoreDict = {};
    // init lineno
    lineno = 0;
    // parse script
    scriptParsed = script
        // indent text-block
        // /* jslint-indent-begin */ ... /* jslint-indent-end */
        .replace(
/* jslint-indent-begin 20 */
(function () {
    /*jslint maxlen: 256*/
    return (/^ *?\/\* jslint-indent-begin (\d+?) \*\/$[\S\s]+?^ *?\/\* jslint-indent-end \*\/$/gm);
}()),
/* jslint-indent-end */
            function (match0, match1) {
                return match0.replace(
                    (/(^ *\S)/gm),
                    new Array(Number(match1) + 1).join(' ') + '$1'
                );
            }
        )
        // ignore text-block
        // /* jslint-ignore-begin */ ... /* jslint-ignore-end */
        .replace(
/* jslint-ignore-begin */
(/^ *?\/\* jslint-ignore-begin \*\/$[\S\s]+?^ *?\/\* jslint-ignore-end \*\/$/gm),
/* jslint-ignore-end */
            function (match0) {
                return match0.replace((/.*/g), '');
            }
        )
        // ignore next-line
        // /* jslint-ignore-next-line */
        .replace(
/* jslint-ignore-next-line */
(/^ *?\/\* jslint-ignore-next-line \*\/\n.*/gm),
            function (match0) {
                return match0.replace((/.*/g), '');
            }
        );
    // csslint script
    if (file.slice(-4) === '.css') {
        scriptParsed = scriptParsed.replace(new RegExp([
            // handle flexbox
            ' display: flex;',
            ' flex: .+?;',
            ' flex-.+?: .+?;'
        ].join('|'), 'g'), function () {
            return ' background: url(' + Math.random() + ');';
        });
        local.CSSLint.errors = local.CSSLint.verify(scriptParsed).messages
            .filter(function (error) {
                return !ignoreDict[error.rule.id];
            });
        // if error occurred, then print colorized error messages
        if (!local.CSSLint.errors.length) {
            return script;
        }
        local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
        local.CSSLint.errors
            .filter(function (error) {
                return error;
            })
            .forEach(function (error) {
                local.errorCounter += 1;
                lineno += 1;
                local.errorText +=
                    (' #' + String(lineno) + ' ').slice(-4) +
                    '\u001b[33m' + error.type + ' - ' + error.rule.id +
                    ' - ' + error.message + '\n    ' + error.rule.desc +
                    '\u001b[39m\n    ' + String(error.evidence).trim() +
                    '\u001b[90m \/\/ line ' + error.line +
                    ', col ' + error.col + '\u001b[39m\n';
            });
    // jslint es6-script
    } else if ((/^\/\*jslint\b[\s\w,:]*?\bes6: true\b/m)
            .test(scriptParsed.slice(0, 0x1000))) {
        // comment shebang
        scriptParsed = scriptParsed.replace((/^#!/), '//');
        local.jslintEs6.errors = local.jslintEs6(scriptParsed).warnings;
        if (!local.jslintEs6.errors.length) {
            return script;
        }
        // if error occurred, then print colorized error messages
        local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
        local.jslintEs6.errors
            .filter(function (error) {
                return error;
            })
            .forEach(function (error) {
                local.errorCounter += 1;
                lineno += 1;
                local.errorText +=
                    (' #' + String(lineno) + ' ').slice(-4) +
                    '\u001b[33m' + error.message +
                    '\u001b[39m\n    ' + String(error.a).trim() +
                    '\u001b[90m \/\/ Line ' + (error.line + 1) +
                    ', Pos ' + (error.column + 1) + '\u001 ...
```
- example usage
```shell
...
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
local.jslint.errorText = '';
if (document.querySelector('#inputTextareaEval1').value
        .indexOf('/*jslint') >= 0) {
    local.jslint.jslintAndPrint(
        document.querySelector('#inputTextareaEval1').value,
        'inputTextareaEval1.js'
    );
}
document.querySelector('#outputPreJslint1').textContent =
    local.jslint.errorText
    .replace((/\u001b\[\d+m/g), '')
...
```

#### <a name="apidoc.element.utility2.jslintAndPrintConditional"></a>[function <span class="apidocSignatureSpan">utility2.</span>jslintAndPrintConditional (script, file, mode)](#apidoc.element.utility2.jslintAndPrintConditional)
- description and source-code
```javascript
jslintAndPrintConditional = function (script, file, mode) {
<span class="apidocCodeCommentSpan">/*
 * this function will jslint / csslint the script and print any errors to stderr,
 * conditionally
 */
</span>    var extname;
    // cleanup errors
    local.jslint.errorCounter = 0;
    local.jslint.errorText = '';
    // optimization - ignore uglified/rollup files
    if ((/\bmin\b|\brollup\b/).test(file)) {
        return script;
    }
    extname = (/\.\w+$/).exec(file);
    extname = extname && extname[0];
    switch (extname) {
    case '.css':
        if (script.indexOf('/*csslint') >= 0 || mode === 'force') {
            local.jslintAndPrint(script, file);
        }
        break;
    case '.html':
        // csslint <style> tag
        script.replace(
            (/<style>([\S\s]+?)<\/style>/g),
            function (match0, match1, ii, text) {
                // jslint-hack
                local.nop(match0);
                // preserve lineno
                match1 = text.slice(0, ii).replace((/.+/g), '') + match1;
                local.jslintAndPrintConditional(match1, file + '.css', mode);
            }
        );
        // jslint <script> tag
        script.replace(
            (/<script>([\S\s]+?)<\/script>/g),
            function (match0, match1, ii, text) {
                // jslint-hack
                local.nop(match0);
                // preserve lineno
                match1 = text.slice(0, ii).replace((/.+/g), '') + match1;
                local.jslintAndPrintConditional(match1, file + '.js', mode);
            }
        );
        break;
    case '.js':
        if ((script.indexOf('/*jslint') >= 0 &&
                !local.global.__coverage__) || mode === 'force') {
            local.jslintAndPrint(script, file);
        }
        break;
    }
    return script;
}
```
- example usage
```shell
...
});
optionsList.forEach(function (options) {
    onParallel.counter += 1;
    local.ajax(options, function (error, xhr) {
        // validate no error occurred
        local.assert(!error, error);
        // jslint file
        local.jslintAndPrintConditional(xhr.responseText, options.file);
        // validate no error occurred
        local.assert(!local.jslint.errorText, local.jslint.errorText);
        local.fsWriteFileWithMkdirpSync(
            local.env.npm_config_dir_build + '/app' + options.file,
            new Buffer(xhr.response)
        );
        onParallel();
...
```

#### <a name="apidoc.element.utility2.jsonCopy"></a>[function <span class="apidocSignatureSpan">utility2.</span>jsonCopy (arg)](#apidoc.element.utility2.jsonCopy)
- description and source-code
```javascript
jsonCopy = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a deep-copy of the JSON-arg
 */
</span>    return arg === undefined
        ? undefined
        : JSON.parse(JSON.stringify(arg));
}
```
- example usage
```shell
...
                return;
            }
            // recurse
            normalize(dbRow[key]);
        });
    }
};
dbRow = local.jsonCopy(dbRow && typeof dbRow === 'object'
    ? dbRow
    : {});
// update timestamp
timeNow = new Date().toISOString();
dbRow._timeCreated = dbRow._timeCreated || timeNow;
dbRow._timeUpdated = timeNow;
// normalize
...
```

#### <a name="apidoc.element.utility2.jsonStringifyOrdered"></a>[function <span class="apidocSignatureSpan">utility2.</span>jsonStringifyOrdered (element, replacer, space)](#apidoc.element.utility2.jsonStringifyOrdered)
- description and source-code
```javascript
jsonStringifyOrdered = function (element, replacer, space) {
<span class="apidocCodeCommentSpan">/*
 * this function will JSON.stringify the element,
 * with object-keys sorted and circular-references removed
 */
</span>    var circularList, stringify, tmp;
    stringify = function (element) {
    /*
     * this function will recursively JSON.stringify the element,
     * with object-keys sorted and circular-references removed
     */
        // if element is an object, then recurse its items with object-keys sorted
        if (element &&
                typeof element === 'object' &&
                typeof element.toJSON !== 'function') {
            // ignore circular-reference
            if (circularList.indexOf(element) >= 0) {
                return;
            }
            circularList.push(element);
            // if element is an array, then recurse its elements
            if (Array.isArray(element)) {
                return '[' + element.map(function (element) {
                    // recurse
                    tmp = stringify(element);
                    return typeof tmp === 'string'
                        ? tmp
                        : 'null';
                }).join(',') + ']';
            }
            return '{' + Object.keys(element)
                // sort object-keys
                .sort()
                .map(function (key) {
                    // recurse
                    tmp = stringify(element[key]);
                    if (typeof tmp === 'string') {
                        return JSON.stringify(key) + ':' + tmp;
                    }
                })
                .filter(function (element) {
                    return typeof element === 'string';
                })
                .join(',') + '}';
        }
        // else JSON.stringify as normal
        return JSON.stringify(element);
    };
    circularList = [];
    return JSON.stringify(element && typeof element === 'object'
        // recurse
        ? JSON.parse(stringify(element))
        : element, replacer, space);
}
```
- example usage
```shell
...
if (location.href.indexOf("modeTest=") >= 0) {
    return;
}
// try to JSON.stringify #inputTextareaEval1
try {
    document.querySelector('#outputPreJsonStringify1').textContent = '';
    document.querySelector('#outputPreJsonStringify1').textContent =
        local.jsonStringifyOrdered(
            JSON.parse(document.querySelector('#inputTextareaEval1').value),
            null,
            4
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
...
```

#### <a name="apidoc.element.utility2.jwtA256GcmDecrypt"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtA256GcmDecrypt (token, key)](#apidoc.element.utility2.jwtA256GcmDecrypt)
- description and source-code
```javascript
jwtA256GcmDecrypt = function (token, key) {
<span class="apidocCodeCommentSpan">/*
 * https://tools.ietf.org/html/rfc7516
 * this function will use json-web-encryption to
 * aes-256-gcm-decrypt the token with the given base64url-encoded key
 */
</span>    return local.tryCatchOnError(function () {
        token = token
            .replace((/-/g), '+')
            .replace((/_/g), '/')
            .split('.');
        token = local.sjcl.decrypt(local.sjcl.codec.base64url.toBits(
            local.jwtAes256KeyInit(key)
        ), JSON.stringify({
            adata: token[4],
            ct: token[3],
            iv: token[2],
            ks: 256,
            mode: 'gcm'
        }));
        return local.jwtHs256Decode(token, key);
    }, local.nop) || {};
}
```
- example usage
```shell
...
switch (options.modeNext) {
case 1:
    local.dbTableUser = local.db.dbTableCreateOne({ name: 'User' });
    crud = request.swgg.crud;
    user = request.swgg.user = {};
    user.jwtEncrypted = request.headers.authorization &&
        request.headers.authorization.replace('Bearer ', '');
    user.jwtDecrypted = local.jwtA256GcmDecrypt(user.jwtEncrypted);
    switch (crud.operationId.split('.')[0]) {
    // coverage-hack - test error handling-behavior
    case 'crudErrorLogin':
        options.onNext(local.errorDefault);
        return;
    case 'userLoginByPassword':
        user.password = request.urlParsed.query.password;
...
```

#### <a name="apidoc.element.utility2.jwtA256GcmEncrypt"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtA256GcmEncrypt (data, key)](#apidoc.element.utility2.jwtA256GcmEncrypt)
- description and source-code
```javascript
jwtA256GcmEncrypt = function (data, key) {
<span class="apidocCodeCommentSpan">/*
 * https://tools.ietf.org/html/rfc7516
 * this function will use json-web-encryption to
 * aes-256-gcm-encrypt the data with the given base64url-encoded key
 */
</span>    var adata;
    adata = local.jwtAes256KeyCreate();
    data = local.jwtHs256Encode(data, key);
    data = JSON.parse(local.sjcl.encrypt(
        local.sjcl.codec.base64url.toBits(local.jwtAes256KeyInit(key)),
        data,
        { adata: local.sjcl.codec.base64url.toBits(adata), ks: 256, mode: 'gcm' }
    ));
    return local.jwtBase64UrlNormalize('eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4R0NNIn0..' +
        data.iv + '.' + data.ct + '.' + adata);
}
```
- example usage
```shell
...
// init isAuthenticated
user.isAuthenticated = true;
// https://tools.ietf.org/html/rfc7519
// create JSON Web Token (JWT)
user.jwtDecrypted = {};
user.jwtDecrypted.sub = user.data.username;
// update jwtEncrypted in client
user.jwtEncrypted = local.jwtA256GcmEncrypt(user.jwtDecrypted);
local.serverRespondHeadSet(request, response, null, {
    'swgg-jwt-encrypted': user.jwtEncrypted
});
// update jwtEncrypted in dbTableUser
local.dbTableUser.crudUpdateOneById({
    jwtEncrypted: user.jwtEncrypted,
    username: user.jwtDecrypted.sub
...
```

#### <a name="apidoc.element.utility2.jwtAes256KeyCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtAes256KeyCreate ()](#apidoc.element.utility2.jwtAes256KeyCreate)
- description and source-code
```javascript
jwtAes256KeyCreate = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will create a random, aes-256-base64url-jwt-key
 */
</span>    return local.jwtBase64UrlNormalize(
        local.base64FromBuffer(local.bufferRandomBytes(32))
    );
}
```
- example usage
```shell
...
local.jwtA256GcmEncrypt = function (data, key) {
/*
 * https://tools.ietf.org/html/rfc7516
 * this function will use json-web-encryption to
 * aes-256-gcm-encrypt the data with the given base64url-encoded key
 */
    var adata;
    adata = local.jwtAes256KeyCreate();
    data = local.jwtHs256Encode(data, key);
    data = JSON.parse(local.sjcl.encrypt(
        local.sjcl.codec.base64url.toBits(local.jwtAes256KeyInit(key)),
        data,
        { adata: local.sjcl.codec.base64url.toBits(adata), ks: 256, mode: 'gcm' }
    ));
    return local.jwtBase64UrlNormalize('eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4R0NNIn0..' +
...
```

#### <a name="apidoc.element.utility2.jwtAes256KeyInit"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtAes256KeyInit (key)](#apidoc.element.utility2.jwtAes256KeyInit)
- description and source-code
```javascript
jwtAes256KeyInit = function (key) {
<span class="apidocCodeCommentSpan">/*
 * https://jwt.io/
 * this function will init the aes-256-base64url-jwt-key
 */
</span>    // init npm_config_jwtAes256Key
    local.env.npm_config_jwtAes256Key = local.env.npm_config_jwtAes256Key ||
        'AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA';
    return key || local.env.npm_config_jwtAes256Key;
}
```
- example usage
```shell
...
         */
return local.tryCatchOnError(function () {
    token = token
        .replace((/-/g), '+')
        .replace((/_/g), '/')
        .split('.');
    token = local.sjcl.decrypt(local.sjcl.codec.base64url.toBits(
        local.jwtAes256KeyInit(key)
    ), JSON.stringify({
        adata: token[4],
        ct: token[3],
        iv: token[2],
        ks: 256,
        mode: 'gcm'
    }));
...
```

#### <a name="apidoc.element.utility2.jwtBase64UrlNormalize"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtBase64UrlNormalize (text)](#apidoc.element.utility2.jwtBase64UrlNormalize)
- description and source-code
```javascript
jwtBase64UrlNormalize = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will normlize the text to base64url format
 */
</span>    return text
        .replace((/\=/g), '')
        .replace((/\+/g), '-')
        .replace((/\//g), '_');
}
```
- example usage
```shell
...
    adata = local.jwtAes256KeyCreate();
    data = local.jwtHs256Encode(data, key);
    data = JSON.parse(local.sjcl.encrypt(
        local.sjcl.codec.base64url.toBits(local.jwtAes256KeyInit(key)),
        data,
        { adata: local.sjcl.codec.base64url.toBits(adata), ks: 256, mode: 'gcm' }
    ));
    return local.jwtBase64UrlNormalize('eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4R0NNIn0..' +
        data.iv + '.' + data.ct + '.' + adata);
};

local.jwtAes256KeyCreate = function () {
/*
 * this function will create a random, aes-256-base64url-jwt-key
 */
...
```

#### <a name="apidoc.element.utility2.jwtHs256Decode"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtHs256Decode (token, key)](#apidoc.element.utility2.jwtHs256Decode)
- description and source-code
```javascript
jwtHs256Decode = function (token, key) {
<span class="apidocCodeCommentSpan">/*
 * https://jwt.io/
 * this function will decode the json-web-token with the given base64-encode key
 */
</span>    var timeNow;
    timeNow = Date.now() / 1000;
    // try to decode the token
    return local.tryCatchOnError(function () {
        token = token.split('.');
        // validate header
        local.assert(token[0] === 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9', token);
        // validate signature
        local.assert(local.sjcl.codec.base64url.fromBits(
            new local.sjcl.misc.hmac(local.sjcl.codec.base64url.toBits(
                local.jwtAes256KeyInit(key)
            )).encrypt(token[0] + '.' + token[1])
        ) === token[2]);
        // return decoded data
        token = JSON.parse(local.base64ToString(token[1]));
        // https://tools.ietf.org/html/rfc7519#section-4.1
        // validate jwt-registered-headers
        local.assert(!token.exp || token.exp >= timeNow);
        local.assert(!token.nbf || token.nbf <= timeNow);
        return token;
    }, local.nop) || {};
}
```
- example usage
```shell
...
        ), JSON.stringify({
            adata: token[4],
            ct: token[3],
            iv: token[2],
            ks: 256,
            mode: 'gcm'
        }));
        return local.jwtHs256Decode(token, key);
    }, local.nop) || {};
};

local.jwtA256GcmEncrypt = function (data, key) {
/*
 * https://tools.ietf.org/html/rfc7516
 * this function will use json-web-encryption to
...
```

#### <a name="apidoc.element.utility2.jwtHs256Encode"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtHs256Encode (data, key)](#apidoc.element.utility2.jwtHs256Encode)
- description and source-code
```javascript
jwtHs256Encode = function (data, key) {
<span class="apidocCodeCommentSpan">/*
 * https://jwt.io/
 * this function will encode the data into a json-web-token
 * with the given base64-encode key
 */
</span>    data = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.' +
        local.jwtBase64UrlNormalize(local.base64FromString(JSON.stringify(data)));
    return data + '.' + local.sjcl.codec.base64url.fromBits(
        new local.sjcl.misc.hmac(local.sjcl.codec.base64url.toBits(
            local.jwtAes256KeyInit(key)
        )).encrypt(data)
    );
}
```
- example usage
```shell
...
        /*
* https://tools.ietf.org/html/rfc7516
* this function will use json-web-encryption to
* aes-256-gcm-encrypt the data with the given base64url-encoded key
*/
   var adata;
   adata = local.jwtAes256KeyCreate();
   data = local.jwtHs256Encode(data, key);
   data = JSON.parse(local.sjcl.encrypt(
       local.sjcl.codec.base64url.toBits(local.jwtAes256KeyInit(key)),
       data,
       { adata: local.sjcl.codec.base64url.toBits(adata), ks: 256, mode: 'gcm' }
   ));
   return local.jwtBase64UrlNormalize('eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4R0NNIn0..' +
       data.iv + '.' + data.ct + '.' + adata);
...
```

#### <a name="apidoc.element.utility2.jwtNormalize"></a>[function <span class="apidocSignatureSpan">utility2.</span>jwtNormalize (data)](#apidoc.element.utility2.jwtNormalize)
- description and source-code
```javascript
jwtNormalize = function (data) {
<span class="apidocCodeCommentSpan">/*
 * https://tools.ietf.org/html/rfc7519#section-4.1
 * this function will normalize the jwt-data with registered-headers
 */
</span>    var timeNow;
    timeNow = Date.now() / 1000;
    return local.objectSetDefault(data, {
        exp: timeNow + 5 * 60,
        iat: timeNow,
        jti: Math.random().toString(16).slice(2),
        nbf: timeNow
    });
}
```
- example usage
```shell
...
        /*
* this function will test jwtA256GcmXxx's default handling-behavior
*/
   options = {};
   options.key = local.jwtAes256KeyCreate();
   // use canonical example at https://jwt.io/
   options.data = { sub: '1234567890', name: 'John Doe', admin: true };
   options.data = local.jwtNormalize(options.data);
   options.data = JSON.parse(local.jsonStringifyOrdered(options.data));
   // encrypt token
   options.token = local.jwtA256GcmEncrypt(options.data, options.key);
   // validate encrypted-token
   local.assertJsonEqual(
       local.jwtA256GcmDecrypt(options.token, options.key),
       options.data
...
```

#### <a name="apidoc.element.utility2.listGetElementRandom"></a>[function <span class="apidocSignatureSpan">utility2.</span>listGetElementRandom (list)](#apidoc.element.utility2.listGetElementRandom)
- description and source-code
```javascript
listGetElementRandom = function (list) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a random element from the list
 */
</span>    return list[Math.floor(list.length * Math.random())];
}
```
- example usage
```shell
...
propDef = options.propDef;
if (propDef.readOnly) {
    return;
}
if (propDef.enum) {
    tmp = options.modeNotRandom
        ? propDef.enum[0]
        : local.listGetElementRandom(propDef.enum);
    return propDef.type === 'array'
        ? [tmp]
        : tmp;
}
// http://json-schema.org/latest/json-schema-validation.html#anchor13
// 5.1.  Validation keywords for numeric instances (number and integer)
max = isFinite(propDef.maximum)
...
```

#### <a name="apidoc.element.utility2.listShuffle"></a>[function <span class="apidocSignatureSpan">utility2.</span>listShuffle (list)](#apidoc.element.utility2.listShuffle)
- description and source-code
```javascript
listShuffle = function (list) {
<span class="apidocCodeCommentSpan">/*
 * https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle
 * this function will inplace shuffle the list, via fisher-yates algorithm
 */
</span>    var ii, random, swap;
    for (ii = list.length - 1; ii > 0; ii -= 1) {
        // coerce to finite integer
        random = (Math.random() * (ii + 1)) | 0;
        swap = list[ii];
        list[ii] = list[random];
        list[random] = swap;
    }
    return list;
}
```
- example usage
```shell
...
         */
options = {};
// init list
options.list = '[0,1]';
// shuffle list 100 times
for (options.ii = 0; options.ii < 100; options.ii += 1) {
    options.listShuffled =
        JSON.stringify(local.listShuffle(JSON.parse(options.list)));
    // validate shuffled list
    local.assertJsonEqual(options.listShuffled.length, options.list.length);
    options.changed = options.changed || options.listShuffled !== options.list;
}
// validate list changed at least once during the shuffle
local.assert(options.changed, options);
onError();
...
```

#### <a name="apidoc.element.utility2.middlewareAssetsCached"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareAssetsCached (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareAssetsCached)
- description and source-code
```javascript
middlewareAssetsCached = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will serve cached-assets
 */
</span>    var options;
    options = {};
    local.onNext(options, function (error, data) {
        options.result = options.result || local.assetsDict[request.urlParsed.pathname];
        if (options.result === undefined) {
            nextMiddleware(error);
            return;
        }
        switch (options.modeNext) {
        case 1:
            // skip gzip
            if (response.headersSent ||
                    !(/\bgzip\b/).test(request.headers['accept-encoding'])) {
                options.modeNext += 1;
                options.onNext();
                return;
            }
            // gzip and cache result
            local.taskCreateCached({
                cacheDict: 'middlewareAssetsCachedGzip',
                key: request.urlParsed.pathname
            }, function (onError) {
                local.zlib.gzip(options.result, function (error, data) {
                    onError(error, !error && data.toString('base64'));
                });
            }, options.onNext);
            break;
        case 2:
            // set gzip header
            options.result = local.base64ToBuffer(data);
            response.setHeader('Content-Encoding', 'gzip');
            response.setHeader('Content-Length', options.result.length);
            options.onNext();
            break;
        case 3:
            local.middlewareCacheControlLastModified(request, response, options.onNext);
            break;
        case 4:
            response.end(options.result);
            break;
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.middlewareBodyRead"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareBodyRead (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareBodyRead)
- description and source-code
```javascript
middlewareBodyRead = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will
 * read and save the request-body to request.bodyRaw
 */
</span>    // jslint-hack
    local.nop(response);
    // if request is already read, then goto nextMiddleware
    if (!request.readable) {
        nextMiddleware();
        return;
    }
    local.streamReadAll(request, function (error, data) {
        request.bodyRaw = request.bodyRaw || data;
        nextMiddleware(error);
    });
}
```
- example usage
```shell
...
        'X-Response-Header-Test': 'bb'
    });
    local.serverRespondEcho(request, response);
    break;
// test http POST handling-behavior
case '/test.body':
    // test request-body-read handling-behavior
    local.middlewareBodyRead(request, response, function () {
        // test multiple request-body-read handling-behavior
        local.middlewareBodyRead(request, response, function () {
            response.write(request.bodyRaw);
            response.end();
        });
    });
    break;
...
```

#### <a name="apidoc.element.utility2.middlewareCacheControlLastModified"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareCacheControlLastModified ( request, response, nextMiddleware )](#apidoc.element.utility2.middlewareCacheControlLastModified)
- description and source-code
```javascript
middlewareCacheControlLastModified = function ( request, response, nextMiddleware ) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will update the Last-Modified header
 */
</span>    // do not cache if headers already sent or url has '?' search indicator
    if (!(response.headersSent || request.url.indexOf('?') >= 0)) {
        // init serverResponseHeaderLastModified
        local.serverResponseHeaderLastModified =
            local.serverResponseHeaderLastModified ||
            // resolve to 1000 ms
            new Date(new Date(Math.floor(Date.now() / 1000) * 1000).toGMTString());
        // respond with 304 If-Modified-Since serverResponseHeaderLastModified
        if (new Date(request.headers['if-modified-since']) >=
                local.serverResponseHeaderLastModified) {
            response.statusCode = 304;
            response.end();
            return;
        }
        response.setHeader('Cache-Control', 'no-cache');
        response.setHeader(
            'Last-Modified',
            local.serverResponseHeaderLastModified.toGMTString()
        );
    }
    nextMiddleware();
}
```
- example usage
```shell
...
        // set gzip header
        options.result = local.base64ToBuffer(data);
        response.setHeader('Content-Encoding', 'gzip');
        response.setHeader('Content-Length', options.result.length);
        options.onNext();
        break;
    case 3:
        local.middlewareCacheControlLastModified(request, response, options.onNext);
        break;
    case 4:
        response.end(options.result);
        break;
    }
});
options.modeNext = 0;
...
```

#### <a name="apidoc.element.utility2.middlewareFileServer"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareFileServer (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareFileServer)
- description and source-code
```javascript
middlewareFileServer = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will serve files
 */
</span>    if (request.method !== 'GET' || local.modeJs === 'browser') {
        nextMiddleware();
        return;
    }
    request.urlFile = (process.cwd() + request.urlParsed.pathname
        // security - disable parent directory lookup
        .replace((/.*\/\.\.\//g), '/'))
        // replace trailing '/' with '/index.html'
        .replace((/\/$/), '/index.html');
    // serve file from cache
    local.taskCreateCached({
        cacheDict: 'middlewareFileServer',
        key: request.urlFile
    // run background-task to re-cache file
    }, function (onError) {
        local.fs.readFile(request.urlFile, function (error, data) {
            onError(error, data && local.base64FromBuffer(data));
        });
    }, function (error, data) {
        // default to nextMiddleware
        if (error) {
            nextMiddleware();
            return;
        }
        // init response-header content-type
        request.urlParsed.contentType = (/\.[^\.]*$/).exec(request.urlParsed.pathname);
        request.urlParsed.contentType = local.contentTypeDict[
            request.urlParsed.contentType && request.urlParsed.contentType[0]
        ];
        local.serverRespondHeadSet(request, response, null, {
            'Content-Type': request.urlParsed.contentType
        });
        // serve file from cache
        response.end(local.base64ToBuffer(data));
    });
}
```
- example usage
```shell
...
        case '/test.timeout':
            setTimeout(function () {
                response.end();
            }, 2000);
            break;
        // serve file
        default:
            local.middlewareFileServer(request, response, nextMiddleware);
        }
    });
}());
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.middlewareForwardProxy"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareForwardProxy (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareForwardProxy)
- description and source-code
```javascript
middlewareForwardProxy = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will forward-proxy the request
 * to its destination-host
 */
</span>    var onError, options, timerTimeout;
    // handle preflight-cors
    if ((request.headers['access-control-request-headers'] || '')
            .indexOf('forward-proxy-url') >= 0) {
        // enable cors
        // http://en.wikipedia.org/wiki/Cross-origin_resource_sharing
        local.serverRespondHeadSet(request, response, null, {
            'Access-Control-Allow-Headers': 'forward-proxy-headers,forward-proxy-url',
            'Access-Control-Allow-Methods': 'DELETE,GET,HEAD,OPTIONS,PATCH,POST,PUT',
            'Access-Control-Allow-Origin': '*'
        });
        response.end();
        return;
    }
    if (!request.headers['forward-proxy-url']) {
        nextMiddleware();
        return;
    }
    // enable cors
    // http://en.wikipedia.org/wiki/Cross-origin_resource_sharing
    local.serverRespondHeadSet(request, response, null, {
        'Access-Control-Allow-Headers': 'forward-proxy-headers,forward-proxy-url',
        'Access-Control-Allow-Methods': 'DELETE,GET,HEAD,OPTIONS,PATCH,POST,PUT',
        'Access-Control-Allow-Origin': '*'
    });
    // init onError
    onError = function (error) {
        clearTimeout(timerTimeout);
        if (!error || options.done) {
            return;
        }
        options.done = true;
        // cleanup client
        local.streamListCleanup([options.clientRequest, options.clientResponse]);
        nextMiddleware(error);
    };
    // init options
    options = local.urlParse(request.headers['forward-proxy-url']);
    options.method = request.method;
    options.url = request.headers['forward-proxy-url'];
    // init timerTimeout
    timerTimeout = local.onTimeout(
        onError,
        local.timeoutDefault,
        'forward-proxy ' + options.method + ' ' + options.url
    );
    // parse headers
    options.headers = {};
    local.tryCatchOnError(function () {
        options.headers = JSON.parse(request.headers['forward-proxy-headers']);
    }, local.nop);
    // debug options
    local._debugForwardProxy = options;
    console.log(new Date().toISOString() + ' middlewareForwardProxy ' + JSON.stringify({
        method: options.method,
        url: options.url,
        headers: options.headers
    }));
    options.clientRequest = (options.protocol === 'https:'
        ? local.https
        : local.http).request(options, function (clientResponse) {
        options.clientResponse = clientResponse.on('error', onError);
        // pipe clientResponse to serverResponse
        options.clientResponse.pipe(response);
    }).on('error', onError);
    // init event-handling
    request.on('error', onError);
    response.on('finish', onError).on('error', onError);
    // pipe serverRequest to clientRequest
    request.pipe(options.clientRequest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.middlewareGroupCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareGroupCreate (middlewareList)](#apidoc.element.utility2.middlewareGroupCreate)
- description and source-code
```javascript
middlewareGroupCreate = function (middlewareList) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a middleware that will
 * sequentially run the sub-middlewares in middlewareList
 */
</span>    var self;
    self = function (request, response, nextMiddleware) {
        var options;
        options = {};
        local.onNext(options, function (error) {
            // recurse with next middleware in middlewareList
            if (options.modeNext < self.middlewareList.length) {
                // run the sub-middleware
                self.middlewareList[options.modeNext](
                    request,
                    response,
                    options.onNext
                );
                return;
            }
            // default to nextMiddleware
            nextMiddleware(error);
        });
        options.modeNext = -1;
        options.onNext();
    };
    self.middlewareList = middlewareList;
    return self;
}
```
- example usage
```shell
...
* 2. start server on local.env.PORT
* 3. run tests
*/
   if (local.global.utility2_serverHttp1) {
       return;
   }
   local.onReadyBefore.counter += 1;
   local._middleware = local._middleware || local.middlewareGroupCreate([
       local.middlewareInit,
       local.middlewareForwardProxy,
       local.middlewareAssetsCached,
       local._middlewareJsonpStateInit
   ]);
   // 1. create server from local._middleware
   local.serverLocalRequestHandler = function (request, response) {
...
```

#### <a name="apidoc.element.utility2.middlewareInit"></a>[function <span class="apidocSignatureSpan">utility2.</span>middlewareInit (request, response, nextMiddleware)](#apidoc.element.utility2.middlewareInit)
- description and source-code
```javascript
middlewareInit = function (request, response, nextMiddleware) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the middleware that will init the request and response
 */
</span>    // debug server-request
    local._debugServerRequest = request;
    // debug server-response
    local._debugServerResponse = response;
    // init timerTimeout
    local.serverRespondTimeoutDefault(request, response, local.timeoutDefault);
    // init request.urlParsed
    request.urlParsed = local.urlParse(request.url);
    // init response-header content-type
    request.urlParsed.contentType = (/\.[^\.]*$/).exec(request.urlParsed.pathname);
    request.urlParsed.contentType = local.contentTypeDict[
        request.urlParsed.contentType && request.urlParsed.contentType[0]
    ];
    local.serverRespondHeadSet(request, response, null, {
        'Content-Type': request.urlParsed.contentType
    });
    // set main-page content-type to text/html
    if (request.urlParsed.pathname === '/') {
        local.serverRespondHeadSet(request, response, null, {
            'Content-Type': 'text/html; charset=UTF-8'
        });
    }
    // init response.end and response.write to accept Uint8Array instance
    ['end', 'write'].forEach(function (key) {
        response['_' + key] = response['_' + key] || response[key];
        response[key] = function () {
            var args;
            args = Array.from(arguments);
            args[0] = local.bufferToNodeBuffer(args[0]);
            response['_' + key].apply(response, args);
        };
    });
    // default to nextMiddleware
    nextMiddleware();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.moduleDirname"></a>[function <span class="apidocSignatureSpan">utility2.</span>moduleDirname (module, modulePathList)](#apidoc.element.utility2.moduleDirname)
- description and source-code
```javascript
moduleDirname = function (module, modulePathList) {
<span class="apidocCodeCommentSpan">/*
 * this function will search modulePathList for the module's __dirname
 */
</span>    var result, tmp;
    // search process.cwd()
    if (!module || module === '.' || module.indexOf('/') >= 0) {
        return require('path').resolve(process.cwd(), module || '');
    }
    // search builtin
    if (Object.keys(process.binding('natives')).indexOf(module) >= 0) {
        return module;
    }
    // search modulePathList
    [
        modulePathList,
        require('module').globalPaths
    ].some(function (modulePathList) {
        modulePathList.some(function (modulePath) {
            try {
                tmp = require('path').resolve(
                    process.cwd(),
                    modulePath + '/' + module
                );
                result = require('fs').statSync(tmp).isDirectory() && tmp;
                return result;
            } catch (ignore) {
            }
        });
        return result;
    });
    return result || '';
}
```
- example usage
```shell
...
    // enforce 128 character column limit
    text = text.replace((/^.{128}[^\\\n]+/gm), function (match0) {
        return match0.replace((/(.{128}(?:\b|\w+))/g), '$1\n').trimRight();
    });
    return text;
};
// init options
options.dir = local.moduleDirname(
    options.dir,
    options.modulePathList || local.module.paths
);
local.objectSetDefault(options, {
    env: {},
    packageJson: JSON.parse(readExample('package.json'))
});
...
```

#### <a name="apidoc.element.utility2.nop"></a>[function <span class="apidocSignatureSpan">utility2.</span>nop ()](#apidoc.element.utility2.nop)
- description and source-code
```javascript
nop = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will demo a failed assertion test\n\
 */\n\
    // jslint-hack\n\
    window.utility2.nop(options);\n\
    window.utility2.assert(false, "this is a failed assertion demo");\n\
    onError();\n\
};\n\
\n\
testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\n\
/*\n\
 * this function will demo a passed ajax test\n\
...
```

#### <a name="apidoc.element.utility2.normalizeDict"></a>[function <span class="apidocSignatureSpan">utility2.</span>normalizeDict (dict)](#apidoc.element.utility2.normalizeDict)
- description and source-code
```javascript
normalizeDict = function (dict) {
<span class="apidocCodeCommentSpan">/*
 * this function will normalize the dict
 */
</span>    return dict && typeof dict === 'object' && !Array.isArray(dict)
        ? dict
        : {};
}
```
- example usage
```shell
...

// run shared js-env code - lib.dbTable.js
(function () {
    local._DbTable = function (options) {
    /*
     * this function will create a dbTable
     */
        options = local.normalizeDict(options);
        this.name = String(options.name);
        // register dbTable in dbTableDict
        local.dbTableDict[this.name] = this;
        this.dbRowList = [];
        this.isDirty = null;
        this.idIndexList = [{ name: '_id', dict: {} }];
        this.ttl = 0;
...
```

#### <a name="apidoc.element.utility2.normalizeList"></a>[function <span class="apidocSignatureSpan">utility2.</span>normalizeList (list)](#apidoc.element.utility2.normalizeList)
- description and source-code
```javascript
normalizeList = function (list) {
<span class="apidocCodeCommentSpan">/*
 * this function will normalize the list
 */
</span>    return Array.isArray(list)
        ? list
        : [];
}
```
- example usage
```shell
...
/*
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
    var self;
    this._cleanup();
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (idDict) {
            return self._crudGetOneById(idDict);
        })
    ));
};

local._DbTable.prototype.crudGetManyByQuery = function (options, onError) {
/*
...
```

#### <a name="apidoc.element.utility2.normalizeText"></a>[function <span class="apidocSignatureSpan">utility2.</span>normalizeText (text)](#apidoc.element.utility2.normalizeText)
- description and source-code
```javascript
normalizeText = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will normalize the text
 */
</span>    return typeof text === 'string'
        ? text
        : '';
}
```
- example usage
```shell
...
    options.data = local.normalizeList([1]);
    local.assertJsonEqual(options.data, [1]);
    options.data = local.normalizeList(null);
    local.assertJsonEqual(options.data, []);
    options.data = local.normalizeList({});
    local.assertJsonEqual(options.data, []);
    // test normalizeText handling-behavior
    options.data = local.normalizeText('aa');
    local.assertJsonEqual(options.data, 'aa');
    options.data = local.normalizeText(null);
    local.assertJsonEqual(options.data, '');
    options.data = local.normalizeText({});
    local.assertJsonEqual(options.data, '');
    onError();
};
...
```

#### <a name="apidoc.element.utility2.objectGetElementFirst"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectGetElementFirst (arg)](#apidoc.element.utility2.objectGetElementFirst)
- description and source-code
```javascript
objectGetElementFirst = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the first element of the arg
 */
</span>    var item;
    item = {};
    item.key = Object.keys(arg)[0];
    item.value = arg[item.key];
    return item;
}
```
- example usage
```shell
...

local.testCase_objectGetElementFirst_default = function (options, onError) {
/*
 * this function will test objectGetElementFirst's default handling-behavior
 */
    options = { aa: 1, bb: 2 };
    local.assertJsonEqual(
        local.objectGetElementFirst(options),
        { key: 'aa', value: 1 }
    );
    onError();
};

local.testCase_objectKeysTypeOf_default = function (options, onError) {
/*
...
```

#### <a name="apidoc.element.utility2.objectKeysTypeof"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectKeysTypeof (arg)](#apidoc.element.utility2.objectKeysTypeof)
- description and source-code
```javascript
objectKeysTypeof = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a list of the arg's keys, sorted by item-type
 */
</span>    return Object.keys(arg).map(function (key) {
        return typeof arg[key] + ' ' + key;
    }).sort().join('\n');
}
```
- example usage
```shell
...
        aa: true,
        bb: local.nop,
        cc: 0,
        dd: null,
        ee: '',
        ff: undefined
    };
    options = local.objectKeysTypeof(options);
    local.assertJsonEqual(
        options,
        'boolean aa\nfunction bb\nnumber cc\nobject dd\nstring ee\nundefined ff'
    );
    onError();
};
...
```

#### <a name="apidoc.element.utility2.objectLiteralize"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectLiteralize (arg)](#apidoc.element.utility2.objectLiteralize)
- description and source-code
```javascript
objectLiteralize = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will traverse arg, and replace every encounter of the magical key '$[]'
 * with its object literal [key, value]
 */
</span>    local.objectTraverse(arg, function (element) {
        if (element && typeof element === 'object' && !Array.isArray(element)) {
            Object.keys(element).forEach(function (key) {
                if (key.indexOf('$[]') === 0) {
                    element[element[key][0]] = element[key][1];
                    delete element[key];
                }
            });
        }
    });
    return arg;
}
```
- example usage
```shell
...
    "swagger": "2.0",
    "tags": []
};
// save tags
tmp = {};
[local.swaggerJson.tags, options.tags || []].forEach(function (tagList) {
    tagList.forEach(function (tag) {
        local.objectSetOverride(tmp, local.objectLiteralize({
            '$[]': [tag.name, tag]
        }));
    }, 2);
});
tmp = Object.keys(tmp).sort().map(function (key) {
    return tmp[key];
});
...
```

#### <a name="apidoc.element.utility2.objectSetDefault"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectSetDefault (arg, defaults, depth)](#apidoc.element.utility2.objectSetDefault)
- description and source-code
```javascript
objectSetDefault = function (arg, defaults, depth) {
<span class="apidocCodeCommentSpan">/*
 * this function will recursively set defaults for undefined-items in the arg
 */
</span>    arg = arg || {};
    defaults = defaults || {};
    Object.keys(defaults).forEach(function (key) {
        var arg2, defaults2;
        arg2 = arg[key];
        // handle misbehaving getter
        try {
            defaults2 = defaults[key];
        } catch (ignore) {
        }
        if (defaults2 === undefined) {
            return;
        }
        // init arg[key] to default value defaults[key]
        if (!arg2) {
            arg[key] = defaults2;
            return;
        }
        // if arg2 and defaults2 are both non-null and non-array objects,
        // then recurse with arg2 and defaults2
        if (depth > 1 &&
                // arg2 is a non-null and non-array object
                arg2 &&
                typeof arg2 === 'object' &&
                !Array.isArray(arg2) &&
                // defaults2 is a non-null and non-array object
                defaults2 &&
                typeof defaults2 === 'object' &&
                !Array.isArray(defaults2)) {
            // recurse
            local.objectSetDefault(arg2, defaults2, depth - 1);
        }
    });
    return arg;
}
```
- example usage
```shell
...
</html>\n\
';
/* jslint-ignore-end */
if (local.templateRender) {
    local.assetsDict['/'] = local.templateRender(
        local.assetsDict['/assets.index.template.html'],
        {
            env: local.objectSetDefault(local.env, {
                npm_package_description: 'example module',
                npm_package_name: 'example',
                npm_package_nameAlias: 'example',
                npm_package_version: '0.0.1'
            })
        }
    );
...
```

#### <a name="apidoc.element.utility2.objectSetOverride"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectSetOverride (arg, overrides, depth, env)](#apidoc.element.utility2.objectSetOverride)
- description and source-code
```javascript
objectSetOverride = function (arg, overrides, depth, env) {
<span class="apidocCodeCommentSpan">/*
 * this function will recursively set overrides for items in the arg
 */
</span>    arg = arg || {};
    env = env || (typeof process === 'object' && process.env) || {};
    overrides = overrides || {};
    Object.keys(overrides).forEach(function (key) {
        var arg2, overrides2;
        arg2 = arg[key];
        overrides2 = overrides[key];
        if (overrides2 === undefined) {
            return;
        }
        // if both arg2 and overrides2 are non-null and non-array objects,
        // then recurse with arg2 and overrides2
        if (depth > 1 &&
                // arg2 is a non-null and non-array object
                (arg2 &&
                typeof arg2 === 'object' &&
                !Array.isArray(arg2)) &&
                // overrides2 is a non-null and non-array object
                (overrides2 &&
                typeof overrides2 === 'object' &&
                !Array.isArray(overrides2))) {
            local.objectSetOverride(arg2, overrides2, depth - 1, env);
            return;
        }
        // else set arg[key] with overrides[key]
        arg[key] = arg === env
            // if arg is env, then overrides falsey value with empty string
            ? overrides2 || ''
            : overrides2;
    });
    return arg;
}
```
- example usage
```shell
...
        (arg2 &&
        typeof arg2 === 'object' &&
        !Array.isArray(arg2)) &&
        // overrides2 is a non-null and non-array object
        (overrides2 &&
        typeof overrides2 === 'object' &&
        !Array.isArray(overrides2))) {
    local.objectSetOverride(arg2, overrides2, depth - 1, env);
    return;
}
// else set arg[key] with overrides[key]
arg[key] = arg === env
    // if arg is env, then overrides falsey value with empty string
    ? overrides2 || ''
    : overrides2;
...
```

#### <a name="apidoc.element.utility2.objectTraverse"></a>[function <span class="apidocSignatureSpan">utility2.</span>objectTraverse (arg, onSelf, circularList)](#apidoc.element.utility2.objectTraverse)
- description and source-code
```javascript
objectTraverse = function (arg, onSelf, circularList) {
<span class="apidocCodeCommentSpan">/*
 * this function will recursively traverse the arg,
 * and run onSelf with the arg's properties
 */
</span>    onSelf(arg);
    circularList = circularList || [];
    if (arg &&
            typeof arg === 'object' &&
            circularList.indexOf(arg) < 0) {
        circularList.push(arg);
        Object.keys(arg).forEach(function (key) {
            // recurse with arg[key]
            local.objectTraverse(arg[key], onSelf, circularList);
        });
    }
    return arg;
}
```
- example usage
```shell
...
};

local.objectLiteralize = function (arg) {
/*
 * this function will traverse arg, and replace every encounter of the magical key '$[]'
 * with its object literal [key, value]
 */
    local.objectTraverse(arg, function (element) {
        if (element && typeof element === 'object' && !Array.isArray(element)) {
            Object.keys(element).forEach(function (key) {
                if (key.indexOf('$[]') === 0) {
                    element[element[key][0]] = element[key][1];
                    delete element[key];
                }
            });
...
```

#### <a name="apidoc.element.utility2.onErrorDefault"></a>[function <span class="apidocSignatureSpan">utility2.</span>onErrorDefault (error)](#apidoc.element.utility2.onErrorDefault)
- description and source-code
```javascript
onErrorDefault = function (error) {
<span class="apidocCodeCommentSpan">/*
 * this function will if error exists, then print error.stack to stderr
 */
</span>    if (error && !local.global.__coverage__) {
        console.error(error.stack);
    }
}
```
- example usage
```shell
...
            dbTable.idIndexCreate(JSON.parse(match3));
            break;
        case 'ttlSet':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.ttlSet(JSON.parse(match3));
            break;
        default:
            local.onErrorDefault(new Error('dbImport - invalid operation - ' + match0));
        }
    });
    return local.setTimeoutOnError(onError);
};

local.dbLoad = function (onError) {
/*
...
```

#### <a name="apidoc.element.utility2.onErrorThrow"></a>[function <span class="apidocSignatureSpan">utility2.</span>onErrorThrow (error)](#apidoc.element.utility2.onErrorThrow)
- description and source-code
```javascript
onErrorThrow = function (error) {
<span class="apidocCodeCommentSpan">/*
 * this function will assert no error occurred
 */
</span>    if (error) {
        throw error;
    }
}
```
- example usage
```shell
...
local.testCase_onErrorThrow_error = function (options, onError) {
/*
 * this function will test onErrorThrow's error handling-behavior
 */
    local.tryCatchOnError(function () {
        options = {};
        options.error = new Error();
        local.onErrorThrow(options.error);
    }, function (error) {
        // validate error occurred
        local.assert(error, error);
        onError();
    });
};
...
```

#### <a name="apidoc.element.utility2.onErrorWithStack"></a>[function <span class="apidocSignatureSpan">utility2.</span>onErrorWithStack (onError)](#apidoc.element.utility2.onErrorWithStack)
- description and source-code
```javascript
onErrorWithStack = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a new callback that will call onError,
 * and append the current stack to any error
 */
</span>    var stack;
    stack = new Error().stack.replace((/(.*?)\n.*?$/m), '$1');
    return function (error, data, meta) {
        if (error &&
                error !== local.errorDefault &&
                String(error.stack).indexOf(stack.split('\n')[2]) < 0) {
            // append the current stack to error.stack
            error.stack += '\n' + stack;
        }
        onError(error, data, meta);
    };
}
```
- example usage
```shell
...
local.onParallel = function (onError, onDebug) {
/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
...
```

#### <a name="apidoc.element.utility2.onFileModifiedRestart"></a>[function <span class="apidocSignatureSpan">utility2.</span>onFileModifiedRestart (file)](#apidoc.element.utility2.onFileModifiedRestart)
- description and source-code
```javascript
onFileModifiedRestart = function (file) {
<span class="apidocCodeCommentSpan">/*
 * this function will watch the file, and if modified, then restart the process
 */
</span>    if (local.env.npm_config_mode_auto_restart &&
            local.fs.existsSync(file) &&
            local.fs.statSync(file).isFile()) {
        local.fs.watchFile(file, {
            interval: 1000,
            persistent: false
        }, function (stat2, stat1) {
            if (stat2.mtime > stat1.mtime) {
                console.log('file modified - ' + file);
                local.exit(77);
            }
        });
    }
}
```
- example usage
```shell
...
            [__dirname, process.cwd()].forEach(function (dir) {
local.fs.readdirSync(dir).forEach(function (file) {
    if ((/\brollup\b/).test(file)) {
        return;
    }
    file = dir + '/' + file;
    // if the file is modified, then restart the process
    local.onFileModifiedRestart(file);
    switch (local.path.extname(file)) {
    case '.css':
    case '.html':
    case '.js':
    case '.json':
        // jslint file
        local.jslintAndPrintConditional(
...
```

#### <a name="apidoc.element.utility2.onNext"></a>[function <span class="apidocSignatureSpan">utility2.</span>onNext (options, onError)](#apidoc.element.utility2.onNext)
- description and source-code
```javascript
onNext = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will wrap onError inside the recursive function options.onNext,
 * and append the current stack to any error
 */
</span>    options.onNext = local.onErrorWithStack(function (error, data, meta) {
        try {
            options.modeNext = error && !options.modeErrorIgnore
                ? Infinity
                : options.modeNext + 1;
            onError(error, data, meta);
        } catch (errorCaught) {
            // throw errorCaught to break infinite recursion-loop
            if (options.errorCaught) {
                throw options.errorCaught;
            }
            options.errorCaught = errorCaught;
            options.onNext(errorCaught, data, meta);
        }
    });
    return options;
}
```
- example usage
```shell
...
            onError(error, data, meta);
        } catch (errorCaught) {
            // throw errorCaught to break infinite recursion-loop
            if (options.errorCaught) {
                throw options.errorCaught;
            }
            options.errorCaught = errorCaught;
            options.onNext(errorCaught, data, meta);
        }
    });
    return options;
};

local.onParallel = function (onError, onDebug) {
/*
...
```

#### <a name="apidoc.element.utility2.onParallel"></a>[function <span class="apidocSignatureSpan">utility2.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.onParallel)
- description and source-code
```javascript
onParallel = function (onError, onDebug) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
</span>    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
        // handle error
        if (error) {
            self.error = error;
            // ensure counter will decrement to 0
            self.counter = 1;
        }
        // decrement counter
        self.counter -= 1;
        // if counter === 0, then call onError with error
        if (self.counter === 0) {
            onError(error);
        }
    };
    // init counter
    self.counter = 0;
    // return callback
    return self;
}
```
- example usage
```shell
...
};

local.dbCrudRemoveAll = function (onError) {
/*
 * this function will remove all dbRow's from the db
 */
    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].crudRemoveAll(onParallel);
    });
...
```

#### <a name="apidoc.element.utility2.onReadyAfter"></a>[function <span class="apidocSignatureSpan">utility2.</span>onReadyAfter (onError)](#apidoc.element.utility2.onReadyAfter)
- description and source-code
```javascript
onReadyAfter = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will call onError when onReadyBefore.counter === 0
 */
</span>    local.onReadyBefore.counter += 1;
    local.taskCreate({ key: 'utility2.onReadyAfter' }, null, onError);
    local.onResetAfter(local.onReadyBefore);
    return onError;
}
```
- example usage
```shell
...
if (!(local.modeTest || options.modeTest)) {
    return;
}
if (!options.testRunBeforeDone) {
    options.testRunBeforeTimer = options.testRunBeforeTimer ||
        setTimeout(function () {
            local._testRunBefore();
            local.onReadyAfter(function () {
                options.testRunBeforeDone = true;
                local.testRunDefault(options);
            });
        });
    return;
}
// reset _testRunBefore
...
```

#### <a name="apidoc.element.utility2.onReadyBefore"></a>[function <span class="apidocSignatureSpan">utility2.</span>onReadyBefore (error)](#apidoc.element.utility2.onReadyBefore)
- description and source-code
```javascript
onReadyBefore = function (error) {
    onDebug(error, self);
    // if previously counter === 0 or error occurred, then return
    if (self.counter === 0 || self.error) {
        return;
    }
    // handle error
    if (error) {
        self.error = error;
        // ensure counter will decrement to 0
        self.counter = 1;
    }
    // decrement counter
    self.counter -= 1;
    // if counter === 0, then call onError with error
    if (self.counter === 0) {
        onError(error);
    }
}
```
- example usage
```shell
...
    );
    // 2. start server on local.env.PORT
    console.log('server listening on http-port ' + local.env.PORT);
    local.onReadyBefore.counter += 1;
    local.global.utility2_serverHttp1.listen(local.env.PORT, local.onReadyBefore);
    // 3. run tests
    local.testRunDefault(options);
    local.onReadyBefore();
};

local.timeElapsedStart = function (options) {
/*
 * this function will start options.timeElapsed
 */
    options = options || {};
...
```

#### <a name="apidoc.element.utility2.onResetAfter"></a>[function <span class="apidocSignatureSpan">utility2.</span>onResetAfter (onError)](#apidoc.element.utility2.onResetAfter)
- description and source-code
```javascript
onResetAfter = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will call onError when onResetBefore.counter === 0
 */
</span>    local.onResetBefore.counter += 1;
    // visual notification - onResetAfter
    local.ajaxProgressUpdate();
    local.taskCreate({ key: 'utility2.onResetAfter' }, null, onError);
    setTimeout(local.onResetBefore);
    return onError;
}
```
- example usage
```shell
...

local.onReadyAfter = function (onError) {
/*
 * this function will call onError when onReadyBefore.counter === 0
 */
    local.onReadyBefore.counter += 1;
    local.taskCreate({ key: 'utility2.onReadyAfter' }, null, onError);
    local.onResetAfter(local.onReadyBefore);
    return onError;
};

local.onReadyBefore = local.onParallel(function (error) {
/*
 * this function will keep track of onReadyBefore.counter
 */
...
```

#### <a name="apidoc.element.utility2.onResetBefore"></a>[function <span class="apidocSignatureSpan">utility2.</span>onResetBefore (error)](#apidoc.element.utility2.onResetBefore)
- description and source-code
```javascript
onResetBefore = function (error) {
    onDebug(error, self);
    // if previously counter === 0 or error occurred, then return
    if (self.counter === 0 || self.error) {
        return;
    }
    // handle error
    if (error) {
        self.error = error;
        // ensure counter will decrement to 0
        self.counter = 1;
    }
    // decrement counter
    self.counter -= 1;
    // if counter === 0, then call onError with error
    if (self.counter === 0) {
        onError(error);
    }
}
```
- example usage
```shell
...
<script src="assets.utility2.lib.sjcl.js"></script>\n\
<script src="assets.utility2.lib.uglifyjs.js"></script>\n\
<script src="assets.utility2.js"></script>\n\
<script src="jsonp.utility2._stateInit?callback=window.utility2._stateInit"></script>\n\
<script>window.utility2.onResetBefore.counter += 1;</script>\n\
<script src="assets.example.js"></script>\n\
<script src="assets.test.js"></script>\n\
<script>window.utility2.onResetBefore();</script>\n\
<!-- utility2-comment\n\
{{/if isRollup}}\n\
utility2-comment -->\n\
<div class="utility2FooterDiv">\n\
[ this app was created with\n\
<a href="https://github.com/kaizhu256/node-utility2" target="_blank">utility2</a>\n\
]\n\
...
```

#### <a name="apidoc.element.utility2.onTimeout"></a>[function <span class="apidocSignatureSpan">utility2.</span>onTimeout (onError, timeout, message)](#apidoc.element.utility2.onTimeout)
- description and source-code
```javascript
onTimeout = function (onError, timeout, message) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a timeout-error-handler,
 * that will append the current stack to any error encountered
 */
</span>    onError = local.onErrorWithStack(onError);
    // create timeout timer
    return setTimeout(function () {
        onError(new Error('onTimeout - timeout-error - ' +
            timeout + ' ms - ' + (typeof message === 'function'
            ? message()
            : message)));
    // coerce to finite integer
    }, timeout | 0);
}
```
- example usage
```shell
...
    xhr.headers[key.toLowerCase()] = options.headers[key];
});
// init method
xhr.method = xhr.method || 'GET';
// init timeout
xhr.timeout = xhr.timeout || local.timeoutDefault;
// init timerTimeout
timerTimeout = local.onTimeout(function (error) {
    xhr.error = xhr.error || error;
    xhr.abort();
    // cleanup requestStream and responseStream
    local.streamListCleanup([xhr.requestStream, xhr.responseStream]);
}, xhr.timeout, 'ajax ' + xhr.method + ' ' + xhr.url);
// init event handling
xhr.onEvent = function (event) {
...
```

#### <a name="apidoc.element.utility2.processSpawnWithTimeout"></a>[function <span class="apidocSignatureSpan">utility2.</span>processSpawnWithTimeout ()](#apidoc.element.utility2.processSpawnWithTimeout)
- description and source-code
```javascript
processSpawnWithTimeout = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will run like child_process.spawn,
 * but with auto-timeout after timeoutDefault milliseconds
 */
</span>    var childProcess;
    // spawn childProcess
    childProcess = local.child_process.spawn.apply(local.child_process, arguments)
        .on('exit', function () {
            // try to kill timerTimeout childProcess
            local.tryCatchOnError(function () {
                process.kill(childProcess.timerTimeout.pid);
            }, local.nop);
        });
    // init failsafe timerTimeout
    childProcess.timerTimeout = local.child_process.spawn('/bin/sh', ['-c', 'sleep ' +
        // coerce to finite integer
        (((0.001 * local.timeoutDefault) | 0) +
        // add 2 second delay to failsafe timerTimeout
        2) + '; kill -9 ' + childProcess.pid + ' 2>/dev/null'], { stdio: 'ignore' });
    return childProcess;
}
```
- example usage
```shell
...
        // coverage-hack - un-instrument
        .replace((/\b__cov_.*?\+\+/g), '0') +
    '(' + JSON.stringify(options) + '))</script>');
console.log('\nbrowserTest - created electron entry-page ' +
    options.urlBrowser + '\n');
// spawn an electron process to test a url
options.modeNext = 10;
local.processSpawnWithTimeout('electron', [
    __filename,
    'browserTest',
    '--disable-overlay-scrollbar',
    '--enable-logging'
], {
    env: local.jsonCopy(options),
    stdio: options.modeSilent
...
```

#### <a name="apidoc.element.utility2.profile"></a>[function <span class="apidocSignatureSpan">utility2.</span>profile (fnc, onError)](#apidoc.element.utility2.profile)
- description and source-code
```javascript
profile = function (fnc, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will profile the async fnc in milliseconds with the callback onError
 */
</span>    var timeStart;
    timeStart = Date.now();
    // run async fnc
    fnc(function (error) {
        // call onError with difference in milliseconds between Date.now() and timeStart
        onError(error, Date.now() - timeStart);
    });
}
```
- example usage
```shell
...
});
// validate timeElapsed
local.assert(
    0 <= options.timeElapsed && options.timeElapsed < 1000,
    options.timeElapsed
);
// test profile's async handling-behavior
local.profile(function (onError) {
    setTimeout(onError);
}, function (error, timeElapsed) {
    // validate no error occurred
    local.assert(!error, error);
    options.timeElapsed = timeElapsed;
    // validate timeElapsed
    local.assert(0 <= options.timeElapsed &&
...
```

#### <a name="apidoc.element.utility2.profileSync"></a>[function <span class="apidocSignatureSpan">utility2.</span>profileSync (fnc)](#apidoc.element.utility2.profileSync)
- description and source-code
```javascript
profileSync = function (fnc) {
<span class="apidocCodeCommentSpan">/*
 * this function will profile the sync fnc in milliseconds
 */
</span>    var timeStart;
    timeStart = Date.now();
    // run sync fnc
    fnc();
    // return difference in milliseconds between Date.now() and timeStart
    return Date.now() - timeStart;
}
```
- example usage
```shell
...

local.testCase_profileXxx_default = function (options, onError) {
/*
 * this function will test profileXxx's default handling-behavior
 */
    options = {};
    // test profileSync's handling-behavior
    options.timeElapsed = local.profileSync(function () {
        return;
    });
    // validate timeElapsed
    local.assert(
        0 <= options.timeElapsed && options.timeElapsed < 1000,
        options.timeElapsed
    );
...
```

#### <a name="apidoc.element.utility2.replStart"></a>[function <span class="apidocSignatureSpan">utility2.</span>replStart ()](#apidoc.element.utility2.replStart)
- description and source-code
```javascript
replStart = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will start the repl-debugger
 */
</span>    /*jslint evil: true*/
    var self;
    if (global.utility2_serverRepl1) {
        return;
    }
    // start replServer
    self = global.utility2_serverRepl1 = require('repl').start({ useGlobal: true });
    self.nop = function () {
    /*
     * this function will do nothing
     */
        return;
    };
    self.onError = function (error) {
    /*
     * this function will debug any repl-error
     */
        // debug error
        global.utility2_debugReplError = error;
        console.error(error.stack);
    };
    // save repl eval function
    self.evalDefault = self.eval;
    // hook custom repl eval function
    self.eval = function (script, context, file, onError) {
        var match, onError2;
        match = (/^(\S+)(.*?)\n/).exec(script);
        onError2 = function (error, data) {
            // debug error
            global.utility2_debugReplError = error || global.utility2_debugReplError;
            onError(error, data);
        };
        switch (match && match[1]) {
        // syntax sugar to run async shell command
        case '$':
            switch (match[2]) {
            // syntax sugar to run git diff
            case ' git diff':
                match[2] = ' git diff --color | cat';
                break;
            // syntax sugar to run git log
            case ' git log':
                match[2] = ' git log -n 4 | cat';
                break;
            }
            // run async shell command
            require('child_process').spawn(
                '/bin/sh',
                ['-c', match[2]],
                { stdio: ['ignore', 1, 2] }
            )
                // on shell exit, print return prompt
                .on('exit', function (exitCode) {
                    console.log('exit-code ' + exitCode);
                    self.evalDefault(
                        '\n',
                        context,
                        file,
                        onError2
                    );
                });
            script = '\n';
            break;
        // syntax sugar to grep current dir
        case 'grep':
            // run async shell command
            require('child_process').spawn(
                '/bin/sh',
                ['-c', 'find . -type f | grep -v ' +
/* jslint-ignore-begin */
'"\
/\\.\\|.*\\(\\b\\|_\\)\\(\\.\\d\\|\
archive\\|artifact\\|\
bower_component\\|build\\|\
coverage\\|\
doc\\|\
external\\|\
fixture\\|\
git_module\\|\
jquery\\|\
log\\|\
min\\|mock\\|\
node_module\\|\
rollup\\|\
swp\\|\
tmp\\|\
vendor\\)\\(\\b\\|[_s]\\)\
" ' +
/* jslint-ignore-end */
                    '| tr "\\n" "\\000" | xargs -0 grep -in "' +
                    match[2].trim() + '"'],
                { stdio: ['ignore', 1, 2] }
            )
                // on shell exit, print return prompt
                .on('exit', function (exitCode) {
                    console.log('exit-code ' + exitCode);
                    self.evalDefault(
                        '\n',
                        context,
                        file,
                        onError2
                    );
                });
            script = '\n';
            break;
        // syntax sugar to list object's keys, sorted by item-type
        case 'keys':
            script = 'console.log(Object.keys(' + match[2] + ').map(function (key) {' +
                'return typeof ' + match[2] + '[key] + " " + key + "\\n";' +
                '}).sort().join("") + Object.keys(' + match[2] + ').length)\n';
            break;
        // syntax sugar to print stringified arg
        case 'print':
            script = 'console.log(String(' + match[2] + '))\n';
            break;
        }
        // eval the script
        self.evalDefault(script, context, file, onError2);
    };
    self.socket = { end: self.nop, on: self.nop, write: self.nop };
    // init process.stdout
    process.stdout._writeDefault = process.stdout._writeDefault ||
        process.stdout._write;
    process.stdout._write = function (chunk, encoding, callback) { ...
```
- example usage
```shell
...
                'assets.swgg.petstore.json',
                local.env.SWAGGER_JSON_URL
            );
    }
    // run the cli
    switch (process.argv[2]) {
    case 'swagger-ui':
        local.replStart();
        local.global.local = local;
        local.assetsDict['/'] = local.assetsDict['/assets.swgg.html'];
        local.testRunServer({});
        break;
    }
    break;
}
...
```

#### <a name="apidoc.element.utility2.requireExampleJsFromReadme"></a>[function <span class="apidocSignatureSpan">utility2.</span>requireExampleJsFromReadme ()](#apidoc.element.utility2.requireExampleJsFromReadme)
- description and source-code
```javascript
requireExampleJsFromReadme = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will require and export example.js embedded in README.md
 */
</span>    var module, script, tmp;
    // start the repl-debugger
    local.replStart();
    // debug dir
    [__dirname, process.cwd()].forEach(function (dir) {
        local.fs.readdirSync(dir).forEach(function (file) {
            if ((/\brollup\b/).test(file)) {
                return;
            }
            file = dir + '/' + file;
            // if the file is modified, then restart the process
            local.onFileModifiedRestart(file);
            switch (local.path.extname(file)) {
            case '.css':
            case '.html':
            case '.js':
            case '.json':
                // jslint file
                local.jslintAndPrintConditional(
                    local.tryCatchReadFile(file, 'utf8'),
                    file
                );
                break;
            }
        });
    });
    if (local.global.utility2_rollup || local.env.npm_config_mode_start) {
        // init assets
        local.assetsDict['/'] = local.assetsDict['/index.html'] = local.templateRender(
            // uncomment utility2-comment
            local.assetsDict['/assets.index.template.html'].replace(
                (/<!-- utility2-comment\b([\S\s]+?)\butility2-comment -->/g),
                '$1'
            ),
            { env: local.env, isRollup: true }
        );
        local.assetsDict['/assets.example.js'] =
            local.assetsDict['/assets.example.template.js'];
        local.assetsDict['/assets.app.js'] =
            local.fs.readFileSync(__filename, 'utf8').replace((/^#!/), '//');
        // coverage-hack
        local.nop(local.env.npm_config_mode_start && (function () {
            local.assetsDict['/assets.app.js'] =
                local.assetsDict['/assets.utility2.rollup.begin.js'];
            local.assetsDict['/assets.app.js'] += '\n\n\n' +
                local.fs.readFileSync(__filename, 'utf8').replace((/^#!/), '//');
            local.assetsDict['/assets.app.js'] += '\n\n\n' +
                local.assetsDict['/assets.example.js'];
            local.assetsDict['/assets.app.js'] += '\n\n\n' +
                local.assetsDict['/assets.test.js'];
            local.global.local = local;
        }()));
        local[local.env.npm_package_nameAlias] = local;
        return local;
    }
    // init file $npm_package_main
    tmp = process.cwd() + '/' + local.env.npm_package_main;
    global.utility2_moduleExports = require(tmp);
    local.assetsDict['/assets.' + local.env.npm_package_nameAlias + '.js'] =
        local.istanbulInstrumentInPackage(
            local.fs.readFileSync(tmp, 'utf8').replace((/^#!/), '//'),
            tmp
        );
    global.utility2_moduleExports.global = global;
    // read script from README.md
    script = local.templateRenderJslintLite(
        local.assetsDict['/assets.example.template.js'],
        {}
    );
    // coverage-hack
    local.nop(local.env.npm_package_readmeParse && (function () {
        local.fs.readFileSync('README.md', 'utf8').replace(
            (/'''\w*?(\n[\W\s]*?example\.js[\n\"][\S\s]+?)\n'''/),
            function (match0, match1, ii, text) {
                // jslint-hack
                local.nop(match0);
                // preserve lineno
                script = text.slice(0, ii).replace((/.+/g), '') + match1;
            }
        );
    }()));
    script = script
        // alias require($npm_package_name) to utility2_moduleExports;
        .replace(
            "require('" + local.env.npm_package_name + "')",
            'global.utility2_moduleExports'
        )
        .replace(
            "require('" + local.env.npm_package_nameOriginal + "')",
            'global.utility2_moduleExports'
        );
    // init example.js
    tmp = process.cwd() + '/example.js';
    // jslint script
    local.jslintAndPrintConditional(script, tmp);
    // cover script
    script = local.istanbulInstrumentInPackage(script, tmp);
    // init module
    module = require.cache[tmp] = new local.Module(tmp);
    // load script into module
    mo ...
```
- example usage
```shell
...
                local.global.utility2_rollup || local.global.local,\n\
                local.global.utility2\n\
            );\n\
            break;\n\
        // re-init local from example.js\n\
        case \'node\':\n\
            local = (local.global.utility2_rollup || require(\'utility2\'))\n\
                .requireExampleJsFromReadme();\n\
            break;\n\
        }\n\
        // export local\n\
        local.global.local = local;\n\
    }());\n\
\n\
\n\
...
```

#### <a name="apidoc.element.utility2.serverLocalRequestHandler"></a>[function <span class="apidocSignatureSpan">utility2.</span>serverLocalRequestHandler (request, response)](#apidoc.element.utility2.serverLocalRequestHandler)
- description and source-code
```javascript
serverLocalRequestHandler = function (request, response) {
    local._middleware(request, response, function (error) {
        local._middlewareError(error, request, response);
    });
}
```
- example usage
```shell
...
self.end = function (data) {
    // do not run more than once
    if (self.ended) {
        return;
    }
    self.ended = true;
    self.serverRequest.data = data;
    local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
};
self.on = function () {
    return self;
};
self.serverRequest = new local._http.IncomingMessage(xhr);
self.serverResponse = new local._http.ServerResponse(onResponse);
self.setHeader = function (key, value) {
...
```

#### <a name="apidoc.element.utility2.serverRespondDefault"></a>[function <span class="apidocSignatureSpan">utility2.</span>serverRespondDefault (request, response, statusCode, error)](#apidoc.element.utility2.serverRespondDefault)
- description and source-code
```javascript
serverRespondDefault = function (request, response, statusCode, error) {
<span class="apidocCodeCommentSpan">/*
 * this function will respond with a default message,
 * or error.stack for the given statusCode
 */
</span>    // init statusCode and contentType
    local.serverRespondHeadSet(
        request,
        response,
        statusCode,
        { 'Content-Type': 'text/plain; charset=utf-8' }
    );
    if (error) {
        // debug statusCode / method / url
        local.errorMessagePrepend(
            error,
            response.statusCode + ' ' + request.method + ' ' + request.url + '\n'
        );
        // print error.stack to stderr
        local.onErrorDefault(error);
        // end response with error.stack
        response.end(error.stack);
        return;
    }
    // end response with default statusCode message
    response.end(
        statusCode + ' ' + local.http.STATUS_CODES[statusCode]
    );
}
```
- example usage
```shell
...
        options.onNext(null, data, meta);
    }
    break;
case 3:
    switch (crud.operationId.split('.')[0]) {
    case 'fileGetOneById':
        if (!data) {
            local.serverRespondDefault(request, response, 404);
            return;
        }
        local.serverRespondHeadSet(request, response, null, {
            'Content-Type': data.fileContentType
        });
        response.end(local.base64ToBuffer(data.fileBlob));
        break;
...
```

#### <a name="apidoc.element.utility2.serverRespondEcho"></a>[function <span class="apidocSignatureSpan">utility2.</span>serverRespondEcho (request, response)](#apidoc.element.utility2.serverRespondEcho)
- description and source-code
```javascript
serverRespondEcho = function (request, response) {
<span class="apidocCodeCommentSpan">/*
 * this function will respond with debug info
 */
</span>    response.write(request.method + ' ' + request.url +
        ' HTTP/' + request.httpVersion + '\r\n' +
        Object.keys(request.headers).map(function (key) {
            return key + ': ' + request.headers[key] + '\r\n';
        }).join('') + '\r\n');
    request.pipe(response);
}
```
- example usage
```shell
...
switch (request.urlParsed.pathname) {
// test http POST handling-behavior
case '/test.echo':
    // test response header handling-behavior
    local.serverRespondHeadSet(request, response, null, {
        'X-Response-Header-Test': 'bb'
    });
    local.serverRespondEcho(request, response);
    break;
// test http POST handling-behavior
case '/test.body':
    // test request-body-read handling-behavior
    local.middlewareBodyRead(request, response, function () {
        // test multiple request-body-read handling-behavior
        local.middlewareBodyRead(request, response, function () {
...
```

#### <a name="apidoc.element.utility2.serverRespondHeadSet"></a>[function <span class="apidocSignatureSpan">utility2.</span>serverRespondHeadSet (request, response, statusCode, headers)](#apidoc.element.utility2.serverRespondHeadSet)
- description and source-code
```javascript
serverRespondHeadSet = function (request, response, statusCode, headers) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the response object's statusCode / headers
 */
</span>    // jslint-hack
    local.nop(request);
    if (response.headersSent) {
        return;
    }
    // init response.statusCode
    if (Number(statusCode)) {
        response.statusCode = Number(statusCode);
    }
    Object.keys(headers).forEach(function (key) {
        if (headers[key]) {
            response.setHeader(key, headers[key]);
        }
    });
    return true;
}
```
- example usage
```shell
...
        });
    local.dbTableFile.crudSetManyById(crud.body, options.onNext);
    break;
case 'userLoginByPassword':
case 'userLogout':
    // respond with 401 Unauthorized
    if (!user.isAuthenticated) {
        local.serverRespondHeadSet(request, response, 401, {});
        request.swgg.crud.endArgList = [request, response];
        options.modeNext = Infinity;
        options.onNext();
        return;
    }
    options.onNext();
    break;
...
```

#### <a name="apidoc.element.utility2.serverRespondTimeoutDefault"></a>[function <span class="apidocSignatureSpan">utility2.</span>serverRespondTimeoutDefault (request, response, timeout)](#apidoc.element.utility2.serverRespondTimeoutDefault)
- description and source-code
```javascript
serverRespondTimeoutDefault = function (request, response, timeout) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a timeout-error-handler for the server-request
 */
</span>    request.onTimeout = request.onTimeout || function (error) {
        local.serverRespondDefault(request, response, 500, error);
        setTimeout(function () {
            // cleanup request and response
            local.streamListCleanup([request, response]);
        }, 1000);
    };
    request.timerTimeout = local.onTimeout(
        request.onTimeout,
        timeout || local.timeoutDefault,
        'server ' + request.method + ' ' + request.url
    );
    response.on('finish', function () {
        // cleanup timerTimeout
        clearTimeout(request.timerTimeout);
    });
}
```
- example usage
```shell
...
* this function will run the middleware that will init the request and response
*/
   // debug server-request
   local._debugServerRequest = request;
   // debug server-response
   local._debugServerResponse = response;
   // init timerTimeout
   local.serverRespondTimeoutDefault(request, response, local.timeoutDefault);
   // init request.urlParsed
   request.urlParsed = local.urlParse(request.url);
   // init response-header content-type
   request.urlParsed.contentType = (/\.[^\.]*$/).exec(request.urlParsed.pathname);
   request.urlParsed.contentType = local.contentTypeDict[
       request.urlParsed.contentType && request.urlParsed.contentType[0]
   ];
...
```

#### <a name="apidoc.element.utility2.sjcl.prng"></a>[function <span class="apidocSignatureSpan">utility2.</span>sjcl.prng (e)](#apidoc.element.utility2.sjcl.prng)
- description and source-code
```javascript
sjcl.prng = function (e){this.c=[new sjcl.hash.sha256
],this.i=[0],this.F=0,this.s={},this.C=0,this.K={},this.O=this.d=this.j=this.W=0
,this.b=[0,0,0,0,0,0,0,0],this.f=[0,0,0,0],this.A=s,this.B=e,this.q=u,this.w={progress
:{},seeded:{}},this.m=this.V=0,this.t=1,this.u=2,this.S=65536,this.I=[0,48,64,96
,128,192,256,384,512,768,1024],this.T=3e4,this.R=80}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjclHashScryptCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>sjclHashScryptCreate (password, options)](#apidoc.element.utility2.sjclHashScryptCreate)
- description and source-code
```javascript
sjclHashScryptCreate = function (password, options) {
<span class="apidocCodeCommentSpan">/*
 * https://github.com/wg/scrypt
 * this function will create a scrypt-hash of the password
 * with the given options (default = $s0$10801)
 * e.g. $s0$e0801$epIxT/h6HbbwHaehFnh/bw==$7H0vsXlY8UxxyW/BWx/9GuY7jEvGjT71GFd6O4SZND0=
 */
</span>    // init options
    options = (options || '$s0$10801').split('$');
    // init salt
    if (!options[3]) {
        options[3] = local.sjcl.codec.base64.fromBits(
            local.sjcl.random.randomWords(4, 0)
        );
    }
    // init hash
    options[4] = local.sjcl.codec.base64.fromBits(
        local.sjcl.misc.scrypt(
            password || '',
            local.sjcl.codec.base64.toBits(options[3]),
            Math.pow(2, parseInt(options[2].slice(0, 1), 16)),
            parseInt(options[2].slice(1, 2), 16),
            parseInt(options[2].slice(3, 4), 16)
        )
    );
    return options.slice(0, 5).join('$');
}
```
- example usage
```shell
...
};

local.sjclHashScryptValidate = function (password, hash) {
/*
 * https://github.com/wg/scrypt
 * this function will validate the password against the scrypt-hash
 */
    return local.sjclHashScryptCreate(password, hash) === hash;
};

local.sjclHashSha256Create = function (data) {
/*
 * this function will create a base64-encoded sha-256 hash of the string data
 */
    return local.sjcl.codec.base64.fromBits(local.sjcl.hash.sha256.hash(data));
...
```

#### <a name="apidoc.element.utility2.sjclHashScryptValidate"></a>[function <span class="apidocSignatureSpan">utility2.</span>sjclHashScryptValidate (password, hash)](#apidoc.element.utility2.sjclHashScryptValidate)
- description and source-code
```javascript
sjclHashScryptValidate = function (password, hash) {
<span class="apidocCodeCommentSpan">/*
 * https://github.com/wg/scrypt
 * this function will validate the password against the scrypt-hash
 */
</span>    return local.sjclHashScryptCreate(password, hash) === hash;
}
```
- example usage
```shell
...
    options.modeNext = Infinity;
    options.onNext();
    break;
case 2:
    switch (crud.operationId.split('.')[0]) {
    case 'userLoginByPassword':
        user.data = data;
        if (!local.sjclHashScryptValidate(
                user.password,
                user.data && user.data.password
            )) {
            options.modeNext = Infinity;
            options.onNext();
            return;
        }
...
```

#### <a name="apidoc.element.utility2.sjclHashSha256Create"></a>[function <span class="apidocSignatureSpan">utility2.</span>sjclHashSha256Create (data)](#apidoc.element.utility2.sjclHashSha256Create)
- description and source-code
```javascript
sjclHashSha256Create = function (data) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a base64-encoded sha-256 hash of the string data
 */
</span>    return local.sjcl.codec.base64.fromBits(local.sjcl.hash.sha256.hash(data));
}
```
- example usage
```shell
...
};

local.testCase_sjclHashSha256Create_default = function (options, onError) {
/*
 * this function will test sjclHashSha256Create's default handling-behavior
 */
    options = {};
    options.data = local.sjclHashSha256Create('aa');
    local.assertJsonEqual(options.data, 'lhtt0+3jy47LqsvWjeBAzXjrLtWIkTDM60xJJo6k1QY=');
    onError();
};

local.testCase_sjclHmacSha256Create_default = function (options, onError) {
/*
 * this function will test sjclHmacSha256Create's default handling-behavior
...
```

#### <a name="apidoc.element.utility2.sjclHmacSha256Create"></a>[function <span class="apidocSignatureSpan">utility2.</span>sjclHmacSha256Create (key, data)](#apidoc.element.utility2.sjclHmacSha256Create)
- description and source-code
```javascript
sjclHmacSha256Create = function (key, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a base64-encoded sha-256 hmac
 * from the base64-encoded key and string data
 */
</span>    return local.sjcl.codec.base64.fromBits(
        (new local.sjcl.misc.hmac(
            local.sjcl.codec.base64.toBits(key),
            local.sjcl.hash.sha256
        )).mac(local.sjcl.codec.utf8String.toBits(data))
    );
}
```
- example usage
```shell
...
};

local.testCase_sjclHmacSha256Create_default = function (options, onError) {
/*
 * this function will test sjclHmacSha256Create's default handling-behavior
 */
    options = {};
    options.data = local.sjclHmacSha256Create('aa', 'bb');
    local.assertJsonEqual(options.data, 'cgAzwbGmYMrEqU9B05ADLwtflGJxqijX5BWd2hAlcfM=');
    onError();
};

local.testCase_stringHtmlSafe_default = function (options, onError) {
/*
 * this function will test stringHtmlSafe's default handling-behavior
...
```

#### <a name="apidoc.element.utility2.streamListCleanup"></a>[function <span class="apidocSignatureSpan">utility2.</span>streamListCleanup (streamList)](#apidoc.element.utility2.streamListCleanup)
- description and source-code
```javascript
streamListCleanup = function (streamList) {
<span class="apidocCodeCommentSpan">/*
 * this function will end or destroy the streams in streamList
 */
</span>    streamList.forEach(function (stream) {
        // try to end the stream
        local.tryCatchOnError(function () {
            stream.end();
        }, function () {
            // if error, then try to destroy the stream
            local.tryCatchOnError(function () {
                stream.destroy();
            }, local.nop);
        });
    });
}
```
- example usage
```shell
...
// init timeout
xhr.timeout = xhr.timeout || local.timeoutDefault;
// init timerTimeout
timerTimeout = local.onTimeout(function (error) {
    xhr.error = xhr.error || error;
    xhr.abort();
    // cleanup requestStream and responseStream
    local.streamListCleanup([xhr.requestStream, xhr.responseStream]);
}, xhr.timeout, 'ajax ' + xhr.method + ' ' + xhr.url);
// init event handling
xhr.onEvent = function (event) {
    // init statusCode
    xhr.statusCode = xhr.status;
    switch (event.type) {
    case 'abort':
...
```

#### <a name="apidoc.element.utility2.streamReadAll"></a>[function <span class="apidocSignatureSpan">utility2.</span>streamReadAll (stream, onError)](#apidoc.element.utility2.streamReadAll)
- description and source-code
```javascript
streamReadAll = function (stream, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will concat data from the stream,
 * and pass it to onError when done reading
 */
</span>    var chunkList;
    chunkList = [];
    // read data from the stream
    stream
        // on data event, push the buffer chunk to chunkList
        .on('data', function (chunk) {
            chunkList.push(chunk);
        })
        // on end event, pass concatenated read buffer to onError
        .on('end', function () {
            onError(null, local.modeJs === 'browser'
                ? chunkList[0]
                : local.bufferConcat(chunkList));
        })
        // on error event, pass error to onError
        .on('error', onError);
}
```
- example usage
```shell
...
    this.onreadystatechange();
    this.readyState = 3;
    this.onreadystatechange();
    if (this.responseType === 'stream') {
        this.onError(null, this.responseStream);
        return;
    }
    local.streamReadAll(this.responseStream, this.onError);
};

// https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/onreadystatechange
local._http.XMLHttpRequest.prototype.onreadystatechange = local.nop;

local._http.XMLHttpRequest.prototype.open = function (method, url) {
/*
...
```

#### <a name="apidoc.element.utility2.stringHtmlSafe"></a>[function <span class="apidocSignatureSpan">utility2.</span>stringHtmlSafe (text)](#apidoc.element.utility2.stringHtmlSafe)
- description and source-code
```javascript
stringHtmlSafe = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will make the text html-safe
 */
</span>    // new RegExp('[' + '"&\'<>'.split('').sort().join('') + ']', 'g')
    return text.replace((/["&'<>]/g), function (match0) {
        return '&#x' + match0.charCodeAt(0).toString(16) + ';';
    });
}
```
- example usage
```shell
...
    element.source = trimLeft(module[key].toString());
} catch (ignore) {
}
if (element.source.length > 4096) {
    element.source = element.source.slice(0, 4096).trimRight() + ' ...';
}
element.source = (options.template === local.templateApidocHtml
    ? local.stringHtmlSafe(element.source)
    : element.source)
    .replace((/\([\S\s]*?\)/), function (match0) {
        // init signature
        element.signature = match0
            .replace((/ *?\/\*[\S\s]*?\*\/ */g), '')
            .replace((/,/g), ', ')
            .replace((/\s+/g), ' ');
...
```

#### <a name="apidoc.element.utility2.taskCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>taskCreate (options, onTask, onError)](#apidoc.element.utility2.taskCreate)
- description and source-code
```javascript
taskCreate = function (options, onTask, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create the task onTask named options.key, if it does not exist,
 * and push onError to its onErrorList
 */
</span>    var task;
    // init task
    task = local.taskOnTaskDict[options.key] = local.taskOnTaskDict[options.key] ||
        { onErrorList: [] };
    // push callback onError to the task
    if (onError) {
        onError = local.onErrorWithStack(onError);
        task.onErrorList.push(onError);
    }
    // if task exists, then return it
    if (!onTask || task.onTask) {
        return task;
    }
    task.onDone = function () {
        // if already done, then do nothing
        if (task.done) {
            return;
        }
        task.done = true;
        // cleanup timerTimeout
        clearTimeout(task.timerTimeout);
        // cleanup task
        delete local.taskOnTaskDict[options.key];
        // preserve error.message and error.stack
        task.result = JSON.stringify(Array.from(arguments)
            .map(function (element) {
                if (element && element.stack) {
                    element = local.objectSetDefault(local.jsonCopy(element), {
                        message: element.message,
                        name: element.name,
                        stack: element.stack
                    });
                }
                return element;
            }));
        // pass result to callbacks in onErrorList
        task.onErrorList.forEach(function (onError) {
            onError.apply(null, JSON.parse(task.result));
        });
    };
    // init timerTimeout
    task.timerTimeout = local.onTimeout(
        task.onDone,
        options.timeout || local.timeoutDefault,
        'taskCreate ' + options.key
    );
    task.onTask = onTask;
    // run onTask
    task.onTask(task.onDone);
    return task;
}
```
- example usage
```shell
...
};

local.onReadyAfter = function (onError) {
/*
 * this function will call onError when onReadyBefore.counter === 0
 */
    local.onReadyBefore.counter += 1;
    local.taskCreate({ key: 'utility2.onReadyAfter' }, null, onError);
    local.onResetAfter(local.onReadyBefore);
    return onError;
};

local.onReadyBefore = local.onParallel(function (error) {
/*
 * this function will keep track of onReadyBefore.counter
...
```

#### <a name="apidoc.element.utility2.taskCreateCached"></a>[function <span class="apidocSignatureSpan">utility2.</span>taskCreateCached (options, onTask, onError)](#apidoc.element.utility2.taskCreateCached)
- description and source-code
```javascript
taskCreateCached = function (options, onTask, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. if cache-hit, then call onError with cacheValue
 * 2. run onTask in background
 * 3. save onTask's result to cache
 * 4. if cache-miss, then call onError with onTask's result
 */
</span>    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        //  1. if cache-hit, then call onError with cacheValue
        case 1:
            // read cacheValue from memory-cache
            local.cacheDict[options.cacheDict] = local.cacheDict[options.cacheDict] ||
                {};
            options.cacheValue = local.cacheDict[options.cacheDict][options.key];
            if (options.cacheValue) {
                // call onError with cacheValue
                options.modeCacheHit = true;
                onError(null, JSON.parse(options.cacheValue));
                if (!options.modeCacheUpdate) {
                    break;
                }
            }
            // run background-task with lower priority for cache-hit
            setTimeout(options.onNext, options.modeCacheHit && options.cacheTtl);
            break;
        // 2. run onTask in background
        case 2:
            local.taskCreate(options, onTask, options.onNext);
            break;
        default:
            // 3. save onTask's result to cache
            // JSON.stringify data to prevent side-effects on cache
            options.cacheValue = JSON.stringify(data);
            if (!error && options.cacheValue) {
                local.cacheDict[options.cacheDict][options.key] = options.cacheValue;
            }
            // 4. if cache-miss, then call onError with onTask's result
            if (!options.modeCacheHit) {
                onError(error, options.cacheValue && JSON.parse(options.cacheValue));
            }
            (options.onCacheWrite || local.nop)();
            break;
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
if (response.headersSent ||
        !(/\bgzip\b/).test(request.headers['accept-encoding'])) {
    options.modeNext += 1;
    options.onNext();
    return;
}
// gzip and cache result
local.taskCreateCached({
    cacheDict: 'middlewareAssetsCachedGzip',
    key: request.urlParsed.pathname
}, function (onError) {
    local.zlib.gzip(options.result, function (error, data) {
        onError(error, !error && data.toString('base64'));
    });
}, options.onNext);
...
```

#### <a name="apidoc.element.utility2.templateRender"></a>[function <span class="apidocSignatureSpan">utility2.</span>templateRender (template, dict)](#apidoc.element.utility2.templateRender)
- description and source-code
```javascript
templateRender = function (template, dict) {
<span class="apidocCodeCommentSpan">/*
 * this function will render the template with the given dict
 */
</span>    var argList, getValue, match, renderPartial, rgx, value;
    dict = dict || {};
    getValue = function (key) {
        argList = key.split(' ');
        value = dict;
        // iteratively lookup nested values in the dict
        argList[0].split('.').forEach(function (key) {
            value = value && value[key];
        });
        return value;
    };
    renderPartial = function (match0, helper, key, partial) {
        switch (helper) {
        case 'each':
            value = getValue(key);
            return Array.isArray(value)
                ? value.map(function (dict) {
                    // recurse with partial
                    return local.templateRender(partial, dict);
                }).join('')
                : '';
        case 'if':
            partial = partial.split('{{#unless ' + key + '}}');
            partial = getValue(key)
                ? partial[0]
                // handle 'unless' case
                : partial.slice(1).join('{{#unless ' + key + '}}');
            // recurse with partial
            return local.templateRender(partial, dict);
        case 'unless':
            return getValue(key)
                ? ''
                // recurse with partial
                : local.templateRender(partial, dict);
        default:
            // recurse with partial
            return match0[0] + local.templateRender(match0.slice(1), dict);
        }
    };
    // render partials
    rgx = (/\{\{#(\w+) ([^}]+?)\}\}/g);
    template = template || '';
    for (match = rgx.exec(template); match; match = rgx.exec(template)) {
        rgx.lastIndex += 1 - match[0].length;
        template = template.replace(
            new RegExp('\\{\\{#(' + match[1] + ') (' + match[2] +
                ')\\}\\}([\\S\\s]*?)\\{\\{/' + match[1] + ' ' + match[2] +
                '\\}\\}'),
            renderPartial
        );
    }
    // search for keys in the template
    return template.replace((/\{\{[^}]+?\}\}/g), function (match0) {
        getValue(match0.slice(2, -2));
        if (value === undefined) {
            return match0;
        }
        argList.slice(1).forEach(function (arg) {
            switch (arg) {
            case 'alphanumeric':
                value = value.replace((/\W/g), '_');
                break;
            case 'decodeURIComponent':
                value = decodeURIComponent(value);
                break;
            case 'encodeURIComponent':
                value = encodeURIComponent(value);
                break;
            case 'htmlSafe':
                value = value.replace((/["&'<>]/g), function (match0) {
                    return '&#x' + match0.charCodeAt(0).toString(16) + ';';
                });
                break;
            case 'jsonStringify':
                value = JSON.stringify(value);
                break;
            case 'jsonStringify4':
                value = JSON.stringify(value, null, 4);
                break;
            case 'markdownCodeSafe':
                value = value.replace((/'/g), '\'');
                break;
            default:
                value = value[arg]();
                break;
            }
        });
        return String(value);
    });
}
```
- example usage
```shell
...
    ]\n\
</div>\n\
</body>\n\
</html>\n\
';
/* jslint-ignore-end */
if (local.templateRender) {
    local.assetsDict['/'] = local.templateRender(
        local.assetsDict['/assets.index.template.html'],
        {
            env: local.objectSetDefault(local.env, {
                npm_package_description: 'example module',
                npm_package_name: 'example',
                npm_package_nameAlias: 'example',
                npm_package_version: '0.0.1'
...
```

#### <a name="apidoc.element.utility2.templateRenderJslintLite"></a>[function <span class="apidocSignatureSpan">utility2.</span>templateRenderJslintLite (template, options)](#apidoc.element.utility2.templateRenderJslintLite)
- description and source-code
```javascript
templateRenderJslintLite = function (template, options) {
<span class="apidocCodeCommentSpan">/*
 * this function will render the jslint-lite template with the given options.packageJson
 */
</span>    options.packageJson = options.packageJson ||
        JSON.parse(local.fs.readFileSync('package.json', 'utf8'));
    local.objectSetDefault(options.packageJson, {
        nameAlias: options.packageJson.name.replace((/\W/g), '_'),
        repository: { url: 'https://github.com/kaizhu256/node-jslint-lite.git' }
    }, 2);
    options.githubRepo = options.packageJson.repository.url.split('/').slice(-2);
    options.githubRepo[1] = options.githubRepo[1].replace((/\.git$/), '');
    template = template.replace(
        (/https:\/\/kaizhu256\.github\.io\/node-jslint-lite/g),
        'https://' +  options.githubRepo[0] + '.github.io/' +  options.githubRepo[1]
    );
    template = template.replace(
        (/kaizhu256\/node-jslint-lite/g),
        options.githubRepo.join('/')
    );
    template = template.replace(
        (/kaizhu256_2Fnode-jslint-lite/g),
        options.githubRepo.join('_2F')
    );
    template = template.replace(
        (/node-jslint-lite/g),
        options.githubRepo[1]
    );
    template = template.replace((/^#!/), '//');
    template = template.replace((/jslint-lite/g), options.packageJson.name);
    template = template.replace(
        '/* istanbul instrument in package jslint */',
        '/* istanbul instrument in package ' + options.packageJson.nameAlias + ' */'
    );
    template = template.replace(
        (/\b(assets\.|lib\.|local\.|utility2_)jslint\b/g),
        '$1' + options.packageJson.nameAlias
    );
    template = template.replace(
        (/\bh1-jslint\b/g),
        'h1-' + options.packageJson.nameAlias.replace((/_/g), '-')
    );
    return template;
}
```
- example usage
```shell
...
         */
local.objectSetDefault(options, {
    customize: local.nop,
    dataFrom: local.tryCatchReadFile(
        'lib.' + local.env.npm_package_nameAlias + '.js',
        'utf8'
    ),
    dataTo: local.templateRenderJslintLite(
        local.assetsDict['/assets.lib.template.js'],
        {}
    )
});
// search-and-replace - customize dataTo
[
    // customize body before istanbul
...
```

#### <a name="apidoc.element.utility2.testMock"></a>[function <span class="apidocSignatureSpan">utility2.</span>testMock (mockList, onTestCase, onError)](#apidoc.element.utility2.testMock)
- description and source-code
```javascript
testMock = function (mockList, onTestCase, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will mock the objects in mockList while running the onTestCase
 */
</span>    var onError2;
    onError2 = function (error) {
        // restore mock[0] from mock[2]
        mockList.reverse().forEach(function (mock) {
            local.objectSetOverride(mock[0], mock[2]);
        });
        onError(error);
    };
    // try to call onError with mock-objects
    local.tryCatchOnError(function () {
        // mock-objects
        mockList.forEach(function (mock) {
            mock[2] = {};
            // backup mock[0] into mock[2]
            Object.keys(mock[1]).forEach(function (key) {
                mock[2][key] = mock[0][key];
            });
            // override mock[0] with mock[1]
            local.objectSetOverride(mock[0], mock[1]);
        });
        // run onTestCase
        onTestCase(onError2);
    }, onError2);
}
```
- example usage
```shell
...
    });
};

local.testCase_FormData_error = function (options, onError) {
/*
 * this function will test FormData's error handling-behavior
 */
    local.testMock([
        [local.FormData.prototype, { read: function (onError) {
            onError(local.errorDefault);
        } }]
    ], function (onError) {
        options = {};
        options.data = new local.FormData();
        options.method = 'POST';
...
```

#### <a name="apidoc.element.utility2.testReportCreate"></a>[function <span class="apidocSignatureSpan">utility2.</span>testReportCreate (testReport)](#apidoc.element.utility2.testReportCreate)
- description and source-code
```javascript
testReportCreate = function (testReport) {
<span class="apidocCodeCommentSpan">/*
 * this function will create test-report artifacts
 */
</span>    // print test-report summary
    console.log('\n' + new Array(56).join('-') + '\n' + testReport.testPlatformList
        .filter(function (testPlatform) {
            // if testPlatform has no tests, then filter it out
            return testPlatform.testCaseList.length;
        })
        .map(function (testPlatform) {
            return '| test-report - ' + testPlatform.name + '\n|' +
                ('        ' + testPlatform.timeElapsed + ' ms     ')
                .slice(-16) +
                ('        ' + testPlatform.testsFailed + ' failed ')
                .slice(-16) +
                ('        ' + testPlatform.testsPassed + ' passed ')
                .slice(-16) + '     |\n' + new Array(56).join('-');
        })
        .join('\n') + '\n');
    // create test-report.html
    local.fs.writeFileSync(
        local.env.npm_config_dir_build + '/test-report.html',
        local.testReportMerge(testReport, {})
    );
    // create build.badge.svg
    local.fs.writeFileSync(local.env.npm_config_dir_build +
        '/build.badge.svg', local.assetsDict['/assets.buildBadge.template.svg']
        // edit branch name
        .replace((/0000-00-00 00:00:00/g),
            new Date().toISOString().slice(0, 19).replace('T', ' '))
        // edit branch name
        .replace((/- master -/g), '| ' + local.env.CI_BRANCH + ' |')
        // edit commit id
        .replace(
            (/aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa/g),
            local.env.CI_COMMIT_ID
        ));
    // create test-report.badge.svg
    local.fs.writeFileSync(
        local.env.npm_config_dir_build + '/test-report.badge.svg',
        local.assetsDict['/assets.testReportBadge.template.svg']
            // edit number of tests failed
            .replace((/999/g), testReport.testsFailed)
            // edit badge color
            .replace(
                (/d00/g),
                // coverage-hack - cover both fail and pass cases
                '0d00'.slice(!!testReport.testsFailed).slice(0, 3)
            )
    );
    console.log('created test-report file://' + local.env.npm_config_dir_build +
        '/test-report.html\n');
    // if any test failed, then exit with non-zero exit-code
    console.log('\n' + local.env.MODE_BUILD +
        ' - ' + testReport.testsFailed + ' failed tests\n');
    // exit with number of tests failed
    local.exit(testReport.testsFailed);
}
```
- example usage
```shell
...
    options = [
        // suppress console.log
        [console, { log: local.nop }],
        [local, { exit: local.nop }]
    ];
    local.testMock(options, function (onError) {
        // test exit handling-behavior
        local.testReportCreate(local.testReport);
        onError();
    }, onError);
};

local.testCase_webpage_error = function (options, onError) {
/*
 * this function will test webpage's error handling-behavior
...
```

#### <a name="apidoc.element.utility2.testReportMerge"></a>[function <span class="apidocSignatureSpan">utility2.</span>testReportMerge (testReport1, testReport2)](#apidoc.element.utility2.testReportMerge)
- description and source-code
```javascript
testReportMerge = function (testReport1, testReport2) {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. merge testReport2 into testReport1
 * 2. return testReport1 in html-format
 */
</span>    var errorStackList, testCaseNumber, testReport;
    // 1. merge testReport2 into testReport1
    [testReport1, testReport2].forEach(function (testReport, ii) {
        ii += 1;
        local.objectSetDefault(testReport, {
            date: new Date().toISOString(),
            errorStackList: [],
            testPlatformList: [],
            timeElapsed: 0
        }, 8);
        // security - handle malformed testReport
        local.assert(
            testReport && typeof testReport === 'object',
            ii + ' invalid testReport ' + typeof testReport
        );
        // validate timeElapsed
        local.assert(
            typeof testReport.timeElapsed === 'number',
            ii + ' invalid testReport.timeElapsed ' + typeof testReport.timeElapsed
        );
        // security - handle malformed testReport.testPlatformList
        testReport.testPlatformList.forEach(function (testPlatform) {
            local.objectSetDefault(testPlatform, {
                name: 'undefined',
                testCaseList: [],
                timeElapsed: 0
            }, 8);
            local.assert(
                typeof testPlatform.name === 'string',
                ii + ' invalid testPlatform.name ' + typeof testPlatform.name
            );
            // insert $MODE_BUILD into testPlatform.name
            if (local.env.MODE_BUILD) {
                testPlatform.name = testPlatform.name.replace(
                    (/^(browser|node)\b/),
                    local.env.MODE_BUILD + ' - $1'
                );
            }
            // validate timeElapsed
            local.assert(
                typeof testPlatform.timeElapsed === 'number',
                ii + ' invalid testPlatform.timeElapsed ' +
                    typeof testPlatform.timeElapsed
            );
            // security - handle malformed testPlatform.testCaseList
            testPlatform.testCaseList.forEach(function (testCase) {
                local.objectSetDefault(testCase, {
                    errorStack: '',
                    name: 'undefined',
                    timeElapsed: 0
                }, 8);
                local.assert(
                    typeof testCase.errorStack === 'string',
                    ii + ' invalid testCase.errorStack ' + typeof testCase.errorStack
                );
                local.assert(
                    typeof testCase.name === 'string',
                    ii + ' invalid testCase.name ' + typeof testCase.name
                );
                // validate timeElapsed
                local.assert(
                    typeof testCase.timeElapsed === 'number',
                    ii + ' invalid testCase.timeElapsed ' + typeof testCase.timeElapsed
                );
            });
        });
    });
    // merge testReport2.testPlatformList into testReport1.testPlatformList
    testReport2.testPlatformList.forEach(function (testPlatform2) {
        // add testPlatform2 to testReport1.testPlatformList
        testReport1.testPlatformList.push(testPlatform2);
    });
    // update testReport1.timeElapsed
    testReport1.timeElapsed += testReport2.timeElapsed;
    testReport = testReport1;
    testReport.testsFailed = 0;
    testReport.testsPassed = 0;
    testReport.testsPending = 0;
    testReport.testPlatformList.forEach(function (testPlatform) {
        testPlatform.testsFailed = 0;
        testPlatform.testsPassed = 0;
        testPlatform.testsPending = 0;
        testPlatform.testCaseList.forEach(function (testCase) {
            switch (testCase.status) {
            // update failed tests
            case 'failed':
                testPlatform.testsFailed += 1;
                testReport.testsFailed += 1;
                break;
            // update passed tests
            case 'passed':
                testPlatform.testsPassed += 1;
                testReport.testsPassed += 1;
                break;
            // update pending tests ...
```
- example usage
```shell
...
if (local._debugTryCatchErrorCaught) {
    onNext(local._debugTryCatchErrorCaught);
    return;
}
console.log('\nbrowserTest - merging test-report from ' +
    options.fileTestReport + '\n');
if (!options.modeTestIgnore) {
    local.testReportMerge(local.testReport, data);
}
// create test-report.json
local.fs.writeFileSync(
    local.env.npm_config_dir_build + '/test-report.json',
    JSON.stringify(local.testReport)
);
onNext(data && data.testsFailed && new Error(data.testsFailed));
...
```

#### <a name="apidoc.element.utility2.testRunDefault"></a>[function <span class="apidocSignatureSpan">utility2.</span>testRunDefault (options)](#apidoc.element.utility2.testRunDefault)
- description and source-code
```javascript
testRunDefault = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will run all tests in testPlatform.testCaseList
 */
</span>    var exit, onParallel, testPlatform, testReport, testReportDiv1, timerInterval;
    // init modeTest
    local.modeTest = local.modeTest || local.env.npm_config_mode_test;
    if (!(local.modeTest || options.modeTest)) {
        return;
    }
    if (!options.testRunBeforeDone) {
        options.testRunBeforeTimer = options.testRunBeforeTimer ||
            setTimeout(function () {
                local._testRunBefore();
                local.onReadyAfter(function () {
                    options.testRunBeforeDone = true;
                    local.testRunDefault(options);
                });
            });
        return;
    }
    // reset _testRunBefore
    options.testRunBeforeDone = options.testRunBeforeTimer = null;
    // visual notification - testRun
    local.ajaxProgressUpdate();
    // init onParallel
    onParallel = local.onParallel(function () {
    /*
     * this function will create the test-report after all tests are done
     */
        local.ajaxProgressUpdate();
        // stop testPlatform timer
        local.timeElapsedStop(testPlatform);
        // finalize testReport
        local.testReportMerge(testReport, {});
        switch (local.modeJs) {
        case 'browser':
            // notify saucelabs of test results
            // https://docs.saucelabs.com/reference/rest-api/
            // #js-unit-testing
            local.global.global_test_results = {
                coverage: local.global.__coverage__,
                failed: testReport.testsFailed,
                testReport: testReport
            };
            break;
        case 'node':
            // create test-report.json
            local.fs.writeFileSync(
                local.env.npm_config_dir_build + '/test-report.json',
                JSON.stringify(testReport)
            );
            break;
        }
        setTimeout(function () {
            if (local.modeJs === 'browser') {
                // update coverageReport
                local.istanbulCoverageReportCreate({
                    coverage: local.global.__coverage__
                });
                if (document.querySelector('#coverageReportDiv1')) {
                    document.querySelector('#coverageReportDiv1').innerHTML =
                        local.istanbul.coverageReportCreate({
                            coverage: window.__coverage__
                        });
                }
            }
            // restore exit
            local.tryCatchOnError(function () {
                process.exit = exit;
            }, local.nop);
            // exit with number of tests failed
            local.exit(testReport.testsFailed);
        // coverage-hack - wait 1000 ms for timerInterval
        }, 1000);
    });
    onParallel.counter += 1;
    // mock exit
    switch (local.modeJs) {
    case 'node':
        exit = process.exit;
        process.exit = local.nop;
        break;
    }
    // init modeTestCase
    local.modeTestCase = local.modeTestCase || local.env.npm_config_mode_test_case;
    // init testReport
    testReport = local.testReport;
    // init testReport timer
    local.timeElapsedStart(testReport);
    // init testPlatform
    testPlatform = local.testReport.testPlatformList[0];
    // init testPlatform timer
    local.timeElapsedStart(testPlatform);
    // reset testPlatform.testCaseList
    testPlatform.testCaseList.length = 0;
    // add tests into testPlatform.testCaseList
    Object.keys(options).forEach(function (key) {
        // add testCase options[key] to testPlatform.testCaseList
        if ((local.modeTestCase && local.modeTestCase.split(',').indexOf(key) >= 0) ||
                (!local.modeTestCase && key.indexOf('testCase_') === 0)) {
            testPlatform.testCaseList.push({
                name: key,
                status: 'pending',
                onTestCase: options[key]
            });
        }
    });
    // visual notification - update test-progress until done
    // init testReportDiv1 element
    if (local.modeJs === ...
```
- example usage
```shell
...
case 'testRunButton1':
    // show tests
    if (document.querySelector('#testReportDiv1').style.display === 'none') {
        document.querySelector('#testReportDiv1').style.display = 'block';
        document.querySelector('#testRunButton1').textContent =
            'hide internal test';
        local.modeTest = true;
        local.testRunDefault(local);
    // hide tests
    } else {
        document.querySelector('#testReportDiv1').style.display = 'none';
        document.querySelector('#testRunButton1').textContent = 'run internal test';
    }
    break;
// custom-case
...
```

#### <a name="apidoc.element.utility2.testRunServer"></a>[function <span class="apidocSignatureSpan">utility2.</span>testRunServer (options)](#apidoc.element.utility2.testRunServer)
- description and source-code
```javascript
testRunServer = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. create server from local._middleware
 * 2. start server on local.env.PORT
 * 3. run tests
 */
</span>    if (local.global.utility2_serverHttp1) {
        return;
    }
    local.onReadyBefore.counter += 1;
    local._middleware = local._middleware || local.middlewareGroupCreate([
        local.middlewareInit,
        local.middlewareForwardProxy,
        local.middlewareAssetsCached,
        local._middlewareJsonpStateInit
    ]);
    // 1. create server from local._middleware
    local.serverLocalRequestHandler = function (request, response) {
        local._middleware(request, response, function (error) {
            local._middlewareError(error, request, response);
        });
    };
    local.global.utility2_serverHttp1 = local.http.createServer(
        local.serverLocalRequestHandler
    );
    // 2. start server on local.env.PORT
    console.log('server listening on http-port ' + local.env.PORT);
    local.onReadyBefore.counter += 1;
    local.global.utility2_serverHttp1.listen(local.env.PORT, local.onReadyBefore);
    // 3. run tests
    local.testRunDefault(options);
    local.onReadyBefore();
}
```
- example usage
```shell
...
    // init utility2_rollup
    local = local.global.utility2_rollup || (local.modeJs === 'browser'
        ? window.utility2
        : require('utility2'));
    // export local
    local.global.local = local;
    // run test-server
    local.testRunServer(local);
    // init assets
    local.assetsDict['/assets.hello'] = 'hello';
}());
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.timeElapsedStart"></a>[function <span class="apidocSignatureSpan">utility2.</span>timeElapsedStart (options)](#apidoc.element.utility2.timeElapsedStart)
- description and source-code
```javascript
timeElapsedStart = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will start options.timeElapsed
 */
</span>    options = options || {};
    options.timeStart = options.timeStart || Date.now();
    return options;
}
```
- example usage
```shell
...
    break;
}
// init modeTestCase
local.modeTestCase = local.modeTestCase || local.env.npm_config_mode_test_case;
// init testReport
testReport = local.testReport;
// init testReport timer
local.timeElapsedStart(testReport);
// init testPlatform
testPlatform = local.testReport.testPlatformList[0];
// init testPlatform timer
local.timeElapsedStart(testPlatform);
// reset testPlatform.testCaseList
testPlatform.testCaseList.length = 0;
// add tests into testPlatform.testCaseList
...
```

#### <a name="apidoc.element.utility2.timeElapsedStop"></a>[function <span class="apidocSignatureSpan">utility2.</span>timeElapsedStop (options)](#apidoc.element.utility2.timeElapsedStop)
- description and source-code
```javascript
timeElapsedStop = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will stop options.timeElapsed
 */
</span>    options = local.timeElapsedStart(options);
    options.timeElapsed = Date.now() - options.timeStart;
    return options;
}
```
- example usage
```shell
...
    return arg1.status.replace('passed', 'z') + arg1.name >
        arg2.status.replace('passed', 'z') + arg2.name
        ? 1
        : -1;
});
// stop testReport timer
if (testReport.testsPending === 0) {
    local.timeElapsedStop(testReport);
}
// 2. return testReport1 in html-format
// json-copy testReport that will be modified for html templating
testReport = local.jsonCopy(testReport1);
// update timeElapsed
local.timeElapsedStop(testReport);
testReport.testPlatformList.forEach(function (testPlatform) {
...
```

#### <a name="apidoc.element.utility2.tryCatchOnError"></a>[function <span class="apidocSignatureSpan">utility2.</span>tryCatchOnError (fnc, onError)](#apidoc.element.utility2.tryCatchOnError)
- description and source-code
```javascript
tryCatchOnError = function (fnc, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will try to run the fnc in a try-catch block,
 * else call onError with the errorCaught
 */
</span>    // validate onError
    local.assert(typeof onError === 'function', typeof onError);
    try {
        // reset errorCaught
        local._debugTryCatchErrorCaught = null;
        return fnc();
    } catch (errorCaught) {
        // debug errorCaught
        local._debugTryCatchErrorCaught = errorCaught;
        return onError(errorCaught);
    }
}
```
- example usage
```shell
...
local.testCase_ajax_200 = function (options, onError) {
/*
 * this function will test ajax's "200 ok" handling-behavior
 */
    options = {};
    // test ajax-path 'assets.hello'
    local.ajax({ url: 'assets.hello' }, function (error, xhr) {
        local.tryCatchOnError(function () {
            // validate no error occurred
            local.assert(!error, error);
            // validate data
            options.data = xhr.responseText;
            local.assert(options.data === 'hello', options.data);
            onError();
        }, onError);
...
```

#### <a name="apidoc.element.utility2.tryCatchReadFile"></a>[function <span class="apidocSignatureSpan">utility2.</span>tryCatchReadFile (file, options)](#apidoc.element.utility2.tryCatchReadFile)
- description and source-code
```javascript
tryCatchReadFile = function (file, options) {
<span class="apidocCodeCommentSpan">/*
 * this function will try to read the file or return an empty string
 */
</span>    var data;
    data = '';
    try {
        data = local.fs.readFileSync(file, options);
    } catch (ignore) {
    }
    return data;
}
```
- example usage
```shell
...

local.buildLib = function (options, onError) {
/*
 * this function will build the lib
 */
    local.objectSetDefault(options, {
        customize: local.nop,
        dataFrom: local.tryCatchReadFile(
            'lib.' + local.env.npm_package_nameAlias + '.js',
            'utf8'
        ),
        dataTo: local.templateRenderJslintLite(
            local.assetsDict['/assets.lib.template.js'],
            {}
        )
...
```

#### <a name="apidoc.element.utility2.uglify"></a>[function <span class="apidocSignatureSpan">utility2.</span>uglify (code, file)](#apidoc.element.utility2.uglify)
- description and source-code
```javascript
uglify = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will uglify the js-code
 */
</span>    var ast;
    // uglify css
    if ((file || '').slice(-4) === '.css') {
        return code
            // remove comment /**/
            .replace((/\/\*[\S\s]*?\*\//g), '')
            // remove comment //
            .replace((/\/\/.*/g), '')
            // remove whitespace
            .replace((/\t/g), ' ')
            .replace((/ {2,}/g), ' ')
            .replace((/ *?([\n,:;{}]) */g), '$1')
            .replace((/\n\n+/g), '\n')
            .trim();
    }
    // parse code and get the initial AST
    ast = local.parse(code
        .trim()
        // comment shebang
        .replace((/^#!/), '//'));
    // get a new AST with mangled names
    ast = local.ast_mangle(ast);
    // get an AST with compression optimizations
    ast = local.ast_squeeze(ast);
    // compressed code here
    return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
}
```
- example usage
```shell
...
), function (response) {
    local.chunkList = [];
    response
        .on('data', function (chunk) {
            local.chunkList.push(chunk);
        })
        .on('end', function () {
            console.log(local.uglify(
                Buffer.concat(local.chunkList).toString(),
                local.url.parse(process.argv[2]).pathname
            ));
        });
})
    .end();
break;
...
```

#### <a name="apidoc.element.utility2.uglifyjs.MAP"></a>[function <span class="apidocSignatureSpan">utility2.</span>uglifyjs.MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP)
- description and source-code
```javascript
uglifyjs.MAP = function (r, i, s){function f(){var f=i.call(s,r[a],a);f instanceof t?(f=f.v,f instanceof n?u.
push.apply(u,f.v):u.push(f)):f!=e&&(f instanceof n?o.push.apply(o,f.v):o.push(f)
)}var o=[],u=[],a;if(r instanceof Array)for(a=0;a<r.length;++a)f();else for(a in
r)HOP(r,a)&&f();return u.concat(o)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.urlParse"></a>[function <span class="apidocSignatureSpan">utility2.</span>urlParse (url)](#apidoc.element.utility2.urlParse)
- description and source-code
```javascript
urlParse = function (url) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/URL
 * this function will parse the url according to the above spec, plus a query param
 */
</span>    var urlParsed;
    urlParsed = {};
    // try to parse the url
    local.tryCatchOnError(function () {
        // resolve host-less url
        switch (local.modeJs) {
        case 'browser':
            local.serverLocalHost = local.serverLocalHost ||
                location.protocol + '//' + location.host;
            // resolve absolute path
            if (url[0] === '/') {
                url = local.serverLocalHost + url;
            // resolve relative path
            } else if (!(/^\w+?:\/\//).test(url)) {
                url = local.serverLocalHost +
                    location.pathname.replace((/\/[^\/]*?$/), '') + '/' + url;
            }
            urlParsed = new local.global.URL(url);
            urlParsed.path = '/' + urlParsed.href
                .split('/')
                .slice(3)
                .join('/')
                .split('#')[0];
            break;
        case 'node':
            local.env.PORT = local.env.PORT || '8081';
            local.serverLocalHost = local.serverLocalHost ||
                ('http://127.0.0.1:' + local.env.PORT);
            // resolve absolute path
            if (url[0] === '/') {
                url = local.serverLocalHost + url;
            // resolve relative path
            } else if (!(/^\w+?:\/\//).test(url)) {
                url = local.serverLocalHost + '/' + url;
            }
            urlParsed = local.url.parse(url);
            break;
        }
        // init query
        urlParsed.query = {};
        urlParsed.search.slice(1).replace((/[^&]+/g), function (item) {
            item = item.split('=');
            item[0] = decodeURIComponent(item[0]);
            item[1] = decodeURIComponent(item.slice(1).join('='));
            // parse repeating query-param as an array
            if (urlParsed.query[item[0]]) {
                if (!Array.isArray(urlParsed.query[item[0]])) {
                    urlParsed.query[item[0]] = [urlParsed.query[item[0]]];
                }
                urlParsed.query[item[0]].push(item[1]);
            } else {
                urlParsed.query[item[0]] = item[1];
            }
        });
    }, local.nop);
    // https://developer.mozilla.org/en/docs/Web/API/URL#Properties
    return {
        hash: urlParsed.hash || '',
        host: urlParsed.host || '',
        hostname: urlParsed.hostname || '',
        href: urlParsed.href || '',
        path: urlParsed.path || '',
        pathname: urlParsed.pathname || '',
        port: urlParsed.port || '',
        protocol: urlParsed.protocol || '',
        query: urlParsed.query || {},
        search: urlParsed.search || ''
    };
}
```
- example usage
```shell
...
}
switch (String(request.headers['content-type']).split(';')[0]) {
// parse application/x-www-form-urlencoded, e.g.
// aa=hello%20world&bb=bye%20world
case 'application/x-www-form-urlencoded':
    request.swgg.bodyParsed = local.bufferToString(request.bodyRaw);
    request.swgg.bodyParsed =
        local.urlParse('?' + request.swgg.bodyParsed, true).query;
    break;
/*
 * https://tools.ietf.org/html/rfc7578
 * parse multipart/form-data, e.g.
 * --Boundary\r\n
 * Content-Disposition: form-data; name="key"\r\n
 * \r\n
...
```

#### <a name="apidoc.element.utility2.uuid4Create"></a>[function <span class="apidocSignatureSpan">utility2.</span>uuid4Create ()](#apidoc.element.utility2.uuid4Create)
- description and source-code
```javascript
uuid4Create = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will create a random uuid,
 * with format 'xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'
 */
</span>    // code derived from http://jsperf.com/uuid4
    var id, ii;
    id = '';
    for (ii = 0; ii < 32; ii += 1) {
        switch (ii) {
        case 8:
        case 20:
            id += '-';
            // coerce to finite integer
            id += (Math.random() * 16 | 0).toString(16);
            break;
        case 12:
            id += '-';
            id += '4';
            break;
        case 16:
            id += '-';
            id += (Math.random() * 4 | 8).toString(16);
            break;
        default:
            // coerce to finite integer
            id += (Math.random() * 16 | 0).toString(16);
        }
    }
    return id;
}
```
- example usage
```shell
...

    local.testCase_uuid4Create_default = function (options, onError) {
    /*
     * this function will test uuid4Create's default handling-behavior
     */
        options = {};
        // test uuid4 handling-behavior
        options.data = local.uuid4Create();
        // validate data
        local.assert(local.regexpUuidValidate.test(options.data), options.data);
        onError();
    };
}());
switch (local.modeJs) {
...
```



# <a name="apidoc.module.utility2.FormData"></a>[module utility2.FormData](#apidoc.module.utility2.FormData)

#### <a name="apidoc.element.utility2.FormData.FormData"></a>[function <span class="apidocSignatureSpan">utility2.</span>FormData ()](#apidoc.element.utility2.FormData.FormData)
- description and source-code
```javascript
FormData = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will create a serverLocal-compatible FormData instance
 * https://xhr.spec.whatwg.org/#dom-formdata
 * The FormData(form) constructor must run these steps:
 * 1. Let fd be a new FormData object.
 * 2. If form is given, set fd's entries to the result
 *    of constructing the form data set for form. (not implemented)
 * 3. Return fd.
 */
</span>    this.entryList = [];
}
```
- example usage
```shell
...
});
if (options.errorValidate) {
    return;
}
// init options-defaults
local.objectSetDefault(options, {
    inForm: isMultipartFormData
        ? new local.FormData()
        : '',
    inHeader: {},
    inPath: self._path,
    inQuery: '',
    headers: {},
    method: self._method,
    responseType: self.produces &&
...
```



# <a name="apidoc.module.utility2.FormData.prototype"></a>[module utility2.FormData.prototype](#apidoc.module.utility2.FormData.prototype)

#### <a name="apidoc.element.utility2.FormData.prototype.append"></a>[function <span class="apidocSignatureSpan">utility2.FormData.prototype.</span>append (name, value, filename)](#apidoc.element.utility2.FormData.prototype.append)
- description and source-code
```javascript
append = function (name, value, filename) {
<span class="apidocCodeCommentSpan">/*
 * https://xhr.spec.whatwg.org/#dom-formdata-append
 * The append(name, value, filename) method, when invoked, must run these steps:
 * 1. If the filename argument is given, set value to a new File object
 *    whose contents are value and name is filename.
 * 2. Append a new entry whose name is name, and value is value,
 *    to context object's list of entries.
 */
</span>    if (filename) {
        // bug-workaround - chromium cannot assign name to Blob instance
        local.tryCatchOnError(function () {
            value.name = filename;
        }, local.nop);
    }
    this.entryList.push({ name: name, value: value });
}
```
- example usage
```shell
...
}
switch (paramDef.in) {
case 'body':
    options.inBody = tmp;
    break;
case 'formData':
    if (isMultipartFormData) {
        options.inForm.append(paramDef.name, tmp, tmp && tmp.name);
        break;
    }
    options.inForm += '&' + encodeURIComponent(paramDef.name) + '=' +
        encodeURIComponent(tmp);
    break;
case 'header':
    options.inHeader[encodeURIComponent(paramDef.name.toLowerCase())] = tmp;
...
```

#### <a name="apidoc.element.utility2.FormData.prototype.read"></a>[function <span class="apidocSignatureSpan">utility2.FormData.prototype.</span>read (onError)](#apidoc.element.utility2.FormData.prototype.read)
- description and source-code
```javascript
read = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * https://tools.ietf.org/html/rfc7578
 * this function will read from formData as a buffer, e.g.
 * --Boundary\r\n
 * Content-Disposition: form-data; name="key"\r\n
 * \r\n
 * value\r\n
 * --Boundary\r\n
 * Content-Disposition: form-data; name="input1"; filename="file1.png"\r\n
 * Content-Type: image/jpeg\r\n
 * \r\n
 * <data1>\r\n
 * --Boundary\r\n
 * Content-Disposition: form-data; name="input2"; filename="file2.png"\r\n
 * Content-Type: image/jpeg\r\n
 * \r\n
 * <data2>\r\n
 * --Boundary--\r\n
 */
</span>    var boundary, onParallel, result;
    // handle null-case
    if (this.entryList.length === 0) {
        onError(null, local.bufferCreate());
        return;
    }
    // init boundary
    boundary = '--' + Date.now().toString(16) + Math.random().toString(16);
    // init result
    result = [];
    onParallel = local.onParallel(function (error) {
        // add closing boundary
        result.push([boundary + '--\r\n']);
        // concatenate result
        onError(
            error,
            // flatten result
            !error && local.bufferConcat(Array.prototype.concat.apply([], result))
        );
    });
    onParallel.counter += 1;
    this.entryList.forEach(function (element, ii) {
        var value;
        value = element.value;
        if (!(value instanceof local.Blob)) {
            result[ii] = [boundary + '\r\nContent-Disposition: form-data; name="' +
                element.name + '"\r\n\r\n', value, '\r\n'];
            return;
        }
        // read from blob in parallel
        onParallel.counter += 1;
        local.blobRead(value, 'binary', function (error, data) {
            result[ii] = !error && [boundary +
                '\r\nContent-Disposition: form-data; name="' + element.name + '"' +
                // read param filename
                (value && value.name
                    ? '; filename="' + value.name + '"'
                    : '') +
                '\r\n' +
                // read param Content-Type
                (value && value.type
                    ? 'Content-Type: ' + value.type + '\r\n'
                    : '') +
                '\r\n', data, '\r\n'];
            onParallel(error);
        });
    });
    onParallel();
}
```
- example usage
```shell
...
._input.length&&(t=this._input.charAt(this._cursor+e-1)),t},read:function(){var e=
null;return this._cursor<this._input.length&&(this._input.charAt(this._cursor)=="\n"?
(this._line++,this._col=1):this._col++,e=this._input.charAt(this._cursor++)),e},
mark:function(){this._bookmark={cursor:this._cursor,line:this._line,col:this._col
}},reset:function(){this._bookmark&&(this._cursor=this._bookmark.cursor,this._line=
this._bookmark.line,this._col=this._bookmark.col,delete this._bookmark)},readTo:
function(e){var t="",n;while(t.length<e.length||t.lastIndexOf(e)!=t.length-e.length
){n=this.read();if(!n)throw new Error('Expected "'+e+'" at line '+this._line+", col "+
this._col+".");t+=n}return t},readWhile:function(e){var t="",n=this.read();while(
n!==null&&e(n))t+=n,n=this.read();return t},readMatch:function(e){var t=this._input
.substring(this._cursor),n=null;return typeof e=="string"?t.indexOf(e)===0&&(n=this
.readCount(e.length)):e instanceof RegExp&&e.test(t)&&(n=this.readCount(RegExp.lastMatch
.length)),n},readCount:function(e){var t="";while(e--)t+=this.read();return t}},
n.prototype=new Error,r.fromToken=function(e){return new r(e.value,e.startLine,e
.startCol)},r.prototype={constructor:r,valueOf:function(){return this.toString()
...
```



# <a name="apidoc.module.utility2.__require"></a>[module utility2.__require](#apidoc.module.utility2.__require)

#### <a name="apidoc.element.utility2.__require.__require"></a>[function <span class="apidocSignatureSpan">utility2.</span>__require (path)](#apidoc.element.utility2.__require.__require)
- description and source-code
```javascript
function require(path) {
  try {
    exports.requireDepth += 1;
    return self.require(path);
  } finally {
    exports.requireDepth -= 1;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.__require.resolve"></a>[function <span class="apidocSignatureSpan">utility2.__require.</span>resolve (request)](#apidoc.element.utility2.__require.resolve)
- description and source-code
```javascript
function resolve(request) {
  return Module._resolveFilename(request, self);
}
```
- example usage
```shell
...
local.moduleDirname = function (module, modulePathList) {
/*
 * this function will search modulePathList for the module's __dirname
 */
    var result, tmp;
    // search process.cwd()
    if (!module || module === '.' || module.indexOf('/') >= 0) {
        return require('path').resolve(process.cwd(), module || '');
    }
    // search builtin
    if (Object.keys(process.binding('natives')).indexOf(module) >= 0) {
        return module;
    }
    // search modulePathList
    [
...
```



# <a name="apidoc.module.utility2.__require.extensions"></a>[module utility2.__require.extensions](#apidoc.module.utility2.__require.extensions)



# <a name="apidoc.module.utility2._http"></a>[module utility2._http](#apidoc.module.utility2._http)

#### <a name="apidoc.element.utility2._http.IncomingMessage"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage)
- description and source-code
```javascript
IncomingMessage = function (xhr) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_http_incomingmessage
 * An IncomingMessage object is created by http.Server or http.ClientRequest
 * and passed as the first argument to the 'request' and 'response' event respectively
 */
</span>    this.headers = {};
    this.httpVersion = '1.1';
    this.method = xhr.method;
    this.onEvent = document.createDocumentFragment();
    this.readable = true;
    this.url = xhr.url;
}
```
- example usage
```shell
...
        self.ended = true;
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse)
- description and source-code
```javascript
ServerResponse = function (onResponse) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_class_http_serverresponse
 * This object is created internally by a HTTP server--not by the user
 */
</span>    this.chunkList = [];
    this.headers = {};
    this.onEvent = document.createDocumentFragment();
    this.onResponse = onResponse;
    this.statusCode = 200;
}
```
- example usage
```shell
...
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};

local._middlewareError = function (error, request, response) {
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest)
- description and source-code
```javascript
XMLHttpRequest = function () {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#XMLHttpRequest()
 * The constructor initiates an XMLHttpRequest
 */
</span>    var xhr;
    xhr = this;
    ['onError', 'onResponse'].forEach(function (key) {
        xhr[key] = xhr[key].bind(xhr);
    });
    xhr.headers = {};
    xhr.onLoadList = [];
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState
    xhr.readyState = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/response
    xhr.response = null;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseText
    xhr.responseText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseType
    xhr.responseType = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/status
    xhr.status = xhr.statusCode = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/statusText
    xhr.statusText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/timeout
    xhr.timeout = local.timeoutDefault;
}
```
- example usage
```shell
...
        /*
* this function will send an ajax-request with error-handling and timeout
*/
   var timerTimeout, tmp, xhr;
   onError = local.onErrorWithStack(onError);
   // init modeServerLocal
   if (!local.env.npm_config_mode_backend && local._serverLocalUrlTest(options.url)) {
       xhr = new local._http.XMLHttpRequest();
   }
   // init xhr
   xhr = xhr || (local.modeJs === 'browser'
       ? new local.global.XMLHttpRequest()
       : new local._http.XMLHttpRequest());
   // debug xhr
   local._debugXhr = xhr;
...
```

#### <a name="apidoc.element.utility2._http.createServer"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>createServer ()](#apidoc.element.utility2._http.createServer)
- description and source-code
```javascript
createServer = function () {
<span class="apidocCodeCommentSpan">    /*
     * https://nodejs.org/api/all.html#all_http_createserver_requestlistener
     * Returns a new instance of http.Server
     */
</span>    return { listen: function (port, onError) {
    /*
     * https://nodejs.org/api/all.html#all_server_listen_handle_callback
     * This will cause the server to accept connections on the specified handle,
     * but it is presumed that the file descriptor or handle has already been bound
     * to a port or domain socket
     */
        // jslint-hack
        local.nop(port);
        onError();
    } };
}
```
- example usage
```shell
...
}
// start server
if (local.global.utility2_serverHttp1) {
    break;
}
process.env.PORT = process.env.PORT || '8081';
console.log('server starting on port ' + process.env.PORT);
local.http.createServer(function (request, response) {
    request.urlParsed = local.url.parse(request.url);
    if (local.assetsDict[request.urlParsed.pathname] !== undefined) {
        response.end(local.assetsDict[request.urlParsed.pathname]);
        return;
    }
    response.statusCode = 404;
    response.end();
...
```

#### <a name="apidoc.element.utility2._http.request"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>request (xhr, onResponse)](#apidoc.element.utility2._http.request)
- description and source-code
```javascript
request = function (xhr, onResponse) {
    var self;
    self = {};
    self.end = function (data) {
        // do not run more than once
        if (self.ended) {
            return;
        }
        self.ended = true;
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
}
```
- example usage
```shell
...
console.error();
console.error(new Date().toISOString() + ' http-request ' + JSON.stringify({
    method: options.method,
    url: options.url
}));
request = require(
    urlParsed.protocol.slice(0, -1)
).request(urlParsed, function (_response) {
    response = _response;
    chunkList = [];
    response
        .on('data', function (chunk) {
            chunkList.push(chunk);
        })
        .on('end', function () {
...
```



# <a name="apidoc.module.utility2._http.IncomingMessage"></a>[module utility2._http.IncomingMessage](#apidoc.module.utility2._http.IncomingMessage)

#### <a name="apidoc.element.utility2._http.IncomingMessage.IncomingMessage"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>IncomingMessage (xhr)](#apidoc.element.utility2._http.IncomingMessage.IncomingMessage)
- description and source-code
```javascript
IncomingMessage = function (xhr) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_http_incomingmessage
 * An IncomingMessage object is created by http.Server or http.ClientRequest
 * and passed as the first argument to the 'request' and 'response' event respectively
 */
</span>    this.headers = {};
    this.httpVersion = '1.1';
    this.method = xhr.method;
    this.onEvent = document.createDocumentFragment();
    this.readable = true;
    this.url = xhr.url;
}
```
- example usage
```shell
...
        self.ended = true;
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};
...
```



# <a name="apidoc.module.utility2._http.IncomingMessage.prototype"></a>[module utility2._http.IncomingMessage.prototype](#apidoc.module.utility2._http.IncomingMessage.prototype)

#### <a name="apidoc.element.utility2._http.IncomingMessage.prototype.addListener"></a>[function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>addListener (event, onEvent)](#apidoc.element.utility2._http.IncomingMessage.prototype.addListener)
- description and source-code
```javascript
addListener = function (event, onEvent) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_addlistener_event_listener
 * Adds a listener to the end of the listeners array for the specified event
 */
</span>    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
}
```
- example usage
```shell
...
:function(e,t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})},
stat:function(e,t){this.stats[e]=t}},CSSLint._Reporter=Reporter,CSSLint.Util={mix
:function(e,t){var n;for(n in t)t.hasOwnProperty(n)&&(e[n]=t[n]);return n},indexOf
:function(e,t){if(e.indexOf)return e.indexOf(t);for(var n=0,r=e.length;n<r;n++)if(
e[n]===t)return n;return-1},forEach:function(e,t){if(e.forEach)return e.forEach(
t);for(var n=0,r=e.length;n<r;n++)t(e[n],n,e)}},CSSLint.addRule({id:"adjoining-classes"
,name:"Disallow adjoining classes",desc:"Don't use adjoining classes.",browsers:"IE6"
,init:function(e,t){var n=this;e.addListener("startrule",function(r){var i=r.selectors
,s,o,u,a,f,l,c;for(f=0;f<i.length;f++){s=i[f];for(l=0;l<s.parts.length;l++){o=s.
parts[l];if(o.type==e.SELECTOR_PART_TYPE){a=0;for(c=0;c<o.modifiers.length;c++)u=
o.modifiers[c],u.type=="class"&&a++,a>1&&t.report("Don't use adjoining classes."
,o.line,o.col,n)}}}})}}),CSSLint.addRule({id:"box-model",name:"Beware of broken box size"
,desc:"Don't use width or height when using padding or border.",browsers:"All",init
:function(e,t){function u(){s={},o=!1}function a(){var e,u;if(!o){if(s.height)for(
e in i)i.hasOwnProperty(e)&&s[e]&&(u=s[e].value,(e!="padding"||u.parts.length!==2||
...
```

#### <a name="apidoc.element.utility2._http.IncomingMessage.prototype.emit"></a>[function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>emit (event, data)](#apidoc.element.utility2._http.IncomingMessage.prototype.emit)
- description and source-code
```javascript
emit = function (event, data) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_emit_event_arg1_arg2
 * Calls each of the listeners in order with the supplied arguments
 */
</span>    event = new local.global.Event(event);
    event.data = data;
    this.onEvent.dispatchEvent(event);
}
```
- example usage
```shell
...
 * Adds a listener to the end of the listeners array for the specified event
 */
    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
};

local._http.IncomingMessage.prototype.emit = function (event, data) {
/*
...
```

#### <a name="apidoc.element.utility2._http.IncomingMessage.prototype.on"></a>[function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>on (event, onEvent)](#apidoc.element.utility2._http.IncomingMessage.prototype.on)
- description and source-code
```javascript
on = function (event, onEvent) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_addlistener_event_listener
 * Adds a listener to the end of the listeners array for the specified event
 */
</span>    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
}
```
- example usage
```shell
...
}));
request = require(
    urlParsed.protocol.slice(0, -1)
).request(urlParsed, function (_response) {
    response = _response;
    chunkList = [];
    response
        .on('data', function (chunk) {
            chunkList.push(chunk);
        })
        .on('end', function () {
            response.data = Buffer.concat(chunkList);
            onError2();
        })
        .on('error', onError2);
...
```

#### <a name="apidoc.element.utility2._http.IncomingMessage.prototype.pipe"></a>[function <span class="apidocSignatureSpan">utility2._http.IncomingMessage.prototype.</span>pipe (writable)](#apidoc.element.utility2._http.IncomingMessage.prototype.pipe)
- description and source-code
```javascript
pipe = function (writable) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_readable_pipe_destination_options
 * This method pulls all the data out of a readable stream, and writes it to the
 * supplied destination, automatically managing the flow so that the destination is not
 * overwhelmed by a fast readable stream
 */
</span>    this.on('data', function (chunk) {
        writable.write(chunk);
    });
    this.on('end', function () {
        writable.end();
    });
    return writable;
}
```
- example usage
```shell
...
        headers: options.headers
    }));
    options.clientRequest = (options.protocol === 'https:'
        ? local.https
        : local.http).request(options, function (clientResponse) {
        options.clientResponse = clientResponse.on('error', onError);
        // pipe clientResponse to serverResponse
        options.clientResponse.pipe(response);
    }).on('error', onError);
    // init event-handling
    request.on('error', onError);
    response.on('finish', onError).on('error', onError);
    // pipe serverRequest to clientRequest
    request.pipe(options.clientRequest);
};
...
```



# <a name="apidoc.module.utility2._http.ServerResponse"></a>[module utility2._http.ServerResponse](#apidoc.module.utility2._http.ServerResponse)

#### <a name="apidoc.element.utility2._http.ServerResponse.ServerResponse"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>ServerResponse (onResponse)](#apidoc.element.utility2._http.ServerResponse.ServerResponse)
- description and source-code
```javascript
ServerResponse = function (onResponse) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_class_http_serverresponse
 * This object is created internally by a HTTP server--not by the user
 */
</span>    this.chunkList = [];
    this.headers = {};
    this.onEvent = document.createDocumentFragment();
    this.onResponse = onResponse;
    this.statusCode = 200;
}
```
- example usage
```shell
...
        self.serverRequest.data = data;
        local.serverLocalRequestHandler(self.serverRequest, self.serverResponse);
    };
    self.on = function () {
        return self;
    };
    self.serverRequest = new local._http.IncomingMessage(xhr);
    self.serverResponse = new local._http.ServerResponse(onResponse);
    self.setHeader = function (key, value) {
        self.serverRequest.headers[key.toLowerCase()] = value;
    };
    return self;
};

local._middlewareError = function (error, request, response) {
...
```



# <a name="apidoc.module.utility2._http.ServerResponse.prototype"></a>[module utility2._http.ServerResponse.prototype](#apidoc.module.utility2._http.ServerResponse.prototype)

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.addListener"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>addListener (event, onEvent)](#apidoc.element.utility2._http.ServerResponse.prototype.addListener)
- description and source-code
```javascript
addListener = function (event, onEvent) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_addlistener_event_listener
 * Adds a listener to the end of the listeners array for the specified event
 */
</span>    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
}
```
- example usage
```shell
...
:function(e,t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})},
stat:function(e,t){this.stats[e]=t}},CSSLint._Reporter=Reporter,CSSLint.Util={mix
:function(e,t){var n;for(n in t)t.hasOwnProperty(n)&&(e[n]=t[n]);return n},indexOf
:function(e,t){if(e.indexOf)return e.indexOf(t);for(var n=0,r=e.length;n<r;n++)if(
e[n]===t)return n;return-1},forEach:function(e,t){if(e.forEach)return e.forEach(
t);for(var n=0,r=e.length;n<r;n++)t(e[n],n,e)}},CSSLint.addRule({id:"adjoining-classes"
,name:"Disallow adjoining classes",desc:"Don't use adjoining classes.",browsers:"IE6"
,init:function(e,t){var n=this;e.addListener("startrule",function(r){var i=r.selectors
,s,o,u,a,f,l,c;for(f=0;f<i.length;f++){s=i[f];for(l=0;l<s.parts.length;l++){o=s.
parts[l];if(o.type==e.SELECTOR_PART_TYPE){a=0;for(c=0;c<o.modifiers.length;c++)u=
o.modifiers[c],u.type=="class"&&a++,a>1&&t.report("Don't use adjoining classes."
,o.line,o.col,n)}}}})}}),CSSLint.addRule({id:"box-model",name:"Beware of broken box size"
,desc:"Don't use width or height when using padding or border.",browsers:"All",init
:function(e,t){function u(){s={},o=!1}function a(){var e,u;if(!o){if(s.height)for(
e in i)i.hasOwnProperty(e)&&s[e]&&(u=s[e].value,(e!="padding"||u.parts.length!==2||
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.emit"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>emit (event, data)](#apidoc.element.utility2._http.ServerResponse.prototype.emit)
- description and source-code
```javascript
emit = function (event, data) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_emit_event_arg1_arg2
 * Calls each of the listeners in order with the supplied arguments
 */
</span>    event = new local.global.Event(event);
    event.data = data;
    this.onEvent.dispatchEvent(event);
}
```
- example usage
```shell
...
 * Adds a listener to the end of the listeners array for the specified event
 */
    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
};

local._http.IncomingMessage.prototype.emit = function (event, data) {
/*
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.end"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>end (data)](#apidoc.element.utility2._http.ServerResponse.prototype.end)
- description and source-code
```javascript
end = function (data) {
<span class="apidocCodeCommentSpan">/* https://nodejs.org/api/all.html#all_response_end_data_encoding_callback
 * This method signals to the server that all of the response headers
 * and body have been sent
 */
</span>    // emit writable events
    this.chunkList.push(data || '');
    this.emit('finish');
    // emit readable events
    this.onResponse(this);
    this.emit('data', local.bufferConcat(this.chunkList));
    this.emit('end');
}
```
- example usage
```shell
...
        break;
    }
    process.env.PORT = process.env.PORT || '8081';
    console.log('server starting on port ' + process.env.PORT);
    local.http.createServer(function (request, response) {
        request.urlParsed = local.url.parse(request.url);
        if (local.assetsDict[request.urlParsed.pathname] !== undefined) {
            response.end(local.assetsDict[request.urlParsed.pathname]);
            return;
        }
        response.statusCode = 404;
        response.end();
    }).listen(process.env.PORT);
    break;
}
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.on"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>on (event, onEvent)](#apidoc.element.utility2._http.ServerResponse.prototype.on)
- description and source-code
```javascript
on = function (event, onEvent) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_emitter_addlistener_event_listener
 * Adds a listener to the end of the listeners array for the specified event
 */
</span>    this.onEvent.addEventListener(event, function (event) {
        onEvent(event.data);
    });
    if (this.readable && event === 'end') {
        this.readable = null;
        this.emit('data', this.data);
        this.emit('end');
    }
    return this;
}
```
- example usage
```shell
...
}));
request = require(
    urlParsed.protocol.slice(0, -1)
).request(urlParsed, function (_response) {
    response = _response;
    chunkList = [];
    response
        .on('data', function (chunk) {
            chunkList.push(chunk);
        })
        .on('end', function () {
            response.data = Buffer.concat(chunkList);
            onError2();
        })
        .on('error', onError2);
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.setHeader"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>setHeader (key, value)](#apidoc.element.utility2._http.ServerResponse.prototype.setHeader)
- description and source-code
```javascript
setHeader = function (key, value) {
    this.headers[key.toLowerCase()] = value;
}
```
- example usage
```shell
...
local._http.XMLHttpRequest.prototype.setRequestHeader = function (key, value) {
/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#setRequestHeader()
 * Sets the value of an HTTP request header
 */
    key = key.toLowerCase();
    this.headers[key] = value;
    this.requestStream.setHeader(key, value);
};

// https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/upload
local._http.XMLHttpRequest.prototype.upload = { addEventListener: local.nop };

local._http.createServer = function () {
    /*
...
```

#### <a name="apidoc.element.utility2._http.ServerResponse.prototype.write"></a>[function <span class="apidocSignatureSpan">utility2._http.ServerResponse.prototype.</span>write (data)](#apidoc.element.utility2._http.ServerResponse.prototype.write)
- description and source-code
```javascript
write = function (data) {
<span class="apidocCodeCommentSpan">/*
 * https://nodejs.org/api/all.html#all_response_write_chunk_encoding_callback
 * This sends a chunk of the response body
 */
</span>    this.chunkList.push(data);
}
```
- example usage
```shell
...
local.fs = require('fs');
local.path = require('path');
// run the cli
if (module !== require.main || local.global.utility2_rollup) {
    break;
}
// jslint files
process.stdout.write(local.apidocCreate({
    dir: process.argv[2],
    modulePathList: module.paths,
    template: process.argv[3] === '--markdown'
        ? local.templateApidocMd
        : local.templateApidocHtml
}));
break;
...
```



# <a name="apidoc.module.utility2._http.XMLHttpRequest"></a>[module utility2._http.XMLHttpRequest](#apidoc.module.utility2._http.XMLHttpRequest)

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.XMLHttpRequest"></a>[function <span class="apidocSignatureSpan">utility2._http.</span>XMLHttpRequest ()](#apidoc.element.utility2._http.XMLHttpRequest.XMLHttpRequest)
- description and source-code
```javascript
XMLHttpRequest = function () {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#XMLHttpRequest()
 * The constructor initiates an XMLHttpRequest
 */
</span>    var xhr;
    xhr = this;
    ['onError', 'onResponse'].forEach(function (key) {
        xhr[key] = xhr[key].bind(xhr);
    });
    xhr.headers = {};
    xhr.onLoadList = [];
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/readyState
    xhr.readyState = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/response
    xhr.response = null;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseText
    xhr.responseText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/responseType
    xhr.responseType = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/status
    xhr.status = xhr.statusCode = 0;
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/statusText
    xhr.statusText = '';
    // https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/timeout
    xhr.timeout = local.timeoutDefault;
}
```
- example usage
```shell
...
        /*
* this function will send an ajax-request with error-handling and timeout
*/
   var timerTimeout, tmp, xhr;
   onError = local.onErrorWithStack(onError);
   // init modeServerLocal
   if (!local.env.npm_config_mode_backend && local._serverLocalUrlTest(options.url)) {
       xhr = new local._http.XMLHttpRequest();
   }
   // init xhr
   xhr = xhr || (local.modeJs === 'browser'
       ? new local.global.XMLHttpRequest()
       : new local._http.XMLHttpRequest());
   // debug xhr
   local._debugXhr = xhr;
...
```



# <a name="apidoc.module.utility2._http.XMLHttpRequest.prototype"></a>[module utility2._http.XMLHttpRequest.prototype](#apidoc.module.utility2._http.XMLHttpRequest.prototype)

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.abort"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>abort ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.abort)
- description and source-code
```javascript
abort = function () {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#abort()
 * Aborts the request if it has already been sent
 */
</span>    this.onError(new Error('abort'));
}
```
- example usage
```shell
...
// init method
xhr.method = xhr.method || 'GET';
// init timeout
xhr.timeout = xhr.timeout || local.timeoutDefault;
// init timerTimeout
timerTimeout = local.onTimeout(function (error) {
    xhr.error = xhr.error || error;
    xhr.abort();
    // cleanup requestStream and responseStream
    local.streamListCleanup([xhr.requestStream, xhr.responseStream]);
}, xhr.timeout, 'ajax ' + xhr.method + ' ' + xhr.url);
// init event handling
xhr.onEvent = function (event) {
    // init statusCode
    xhr.statusCode = xhr.status;
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>addEventListener (event, onError)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.addEventListener)
- description and source-code
```javascript
addEventListener = function (event, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will add event listeners to the xhr-connection
 */
</span>    switch (event) {
    case 'abort':
    case 'error':
    case 'load':
        this.onLoadList.push(onError);
        break;
    }
}
```
- example usage
```shell
...
        // scroll textarea to bottom
        element.scrollTop = element.scrollHeight;
    };
});
// init event-handling
['change', 'click', 'keyup'].forEach(function (event) {
    Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {
        element.addEventListener(event, local.testRunBrowser);
    });
});
// run tests
local.testRunBrowser();
break;
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.getAllResponseHeaders"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>getAllResponseHeaders ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.getAllResponseHeaders)
- description and source-code
```javascript
getAllResponseHeaders = function () {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest
 * #getAllResponseHeaders()
 * Returns all the response headers, separated by CRLF, as a string,
 * or null if no response has been received
 */
</span>    var xhr;
    xhr = this;
    return Object.keys((xhr.responseStream &&
        xhr.responseStream.headers) || {}).map(function (key) {
        return key + ': ' + xhr.responseStream.headers[key] + '\r\n';
    }).join('') + '\r\n';
}
```
- example usage
```shell
...
        responseText: error.message,
        statusCode: 400
    };
}
// init responseHeaders
data.responseHeaders = {};
(
    (data.getAllResponseHeaders && data.getAllResponseHeaders()) || ''
).replace(
    (/.+/g),
    function (item) {
        item = item.split(':');
        data.responseHeaders[item[0].trim().toLowerCase()] =
            item.slice(1).join(':').trim();
    }
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.getResponseHeader"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>getResponseHeader (key)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.getResponseHeader)
- description and source-code
```javascript
getResponseHeader = function (key) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#getResponseHeader()
 * Returns the string containing the text of the specified header,
 * or null if either the response has not yet been received
 * or the header doesn't exist in the response
 */
</span>    return (this.responseStream &&
        this.responseStream.headers &&
        this.responseStream.headers[key]) || null;
}
```
- example usage
```shell
...
    // send ajax-request
    return local.ajax(options, function (error, xhr) {
        // try to init responseJson
        local.tryCatchOnError(function () {
            xhr.responseJson = JSON.parse(xhr.responseText);
        }, local.nop);
        // init userJwtEncrypted
        if (xhr.getResponseHeader('swgg-jwt-encrypted')) {
            local.userJwtEncrypted = xhr.getResponseHeader('swgg-jwt-encrypted');
        }
        onError(error, xhr);
    });
};

local.apiDictUpdate = function (options) {
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.onError"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onError (error, data)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onError)
- description and source-code
```javascript
onError = function (error, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will handle the error and data passed back to the xhr-connection
 */
</span>    if (this.done) {
        return;
    }
    this.error = error;
    this.response = data;
    // init responseText
    if (!this.responseType || this.responseType === 'text') {
        this.responseText = local.bufferToString(data);
    }
    // update xhr
    this.readyState = 4;
    this.onreadystatechange();
    // handle data
    this.onLoadList.forEach(function (onError) {
        onError({ type: error
            ? 'error'
            : 'load' });
    });
}
```
- example usage
```shell
...
};

local._http.XMLHttpRequest.prototype.abort = function () {
/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#abort()
 * Aborts the request if it has already been sent
 */
    this.onError(new Error('abort'));
};

local._http.XMLHttpRequest.prototype.addEventListener = function (event, onError) {
/*
 * this function will add event listeners to the xhr-connection
 */
    switch (event) {
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.onResponse"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onResponse (responseStream)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onResponse)
- description and source-code
```javascript
onResponse = function (responseStream) {
<span class="apidocCodeCommentSpan">/*
 * this function will handle the responseStream from the xhr-connection
 */
</span>    this.responseStream = responseStream;
    // update xhr
    this.status = this.statusCode = this.responseStream.statusCode;
    this.statusText = local.http.STATUS_CODES[this.responseStream.statusCode] || '';
    this.readyState = 1;
    this.onreadystatechange();
    this.readyState = 2;
    this.onreadystatechange();
    this.readyState = 3;
    this.onreadystatechange();
    if (this.responseType === 'stream') {
        this.onError(null, this.responseStream);
        return;
    }
    local.streamReadAll(this.responseStream, this.onError);
}
```
- example usage
```shell
...
 * This method signals to the server that all of the response headers
 * and body have been sent
 */
    // emit writable events
    this.chunkList.push(data || '');
    this.emit('finish');
    // emit readable events
    this.onResponse(this);
    this.emit('data', local.bufferConcat(this.chunkList));
    this.emit('end');
};

// https://nodejs.org/api/all.html#all_emitter_on_event_listener
local._http.ServerResponse.prototype.on =
    local._http.IncomingMessage.prototype.addListener;
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.onreadystatechange"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>onreadystatechange ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.onreadystatechange)
- description and source-code
```javascript
onreadystatechange = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    this.response = data;
    // init responseText
    if (!this.responseType || this.responseType === 'text') {
        this.responseText = local.bufferToString(data);
    }
    // update xhr
    this.readyState = 4;
    this.onreadystatechange();
    // handle data
    this.onLoadList.forEach(function (onError) {
        onError({ type: error
            ? 'error'
            : 'load' });
    });
};
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.open"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>open (method, url)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.open)
- description and source-code
```javascript
open = function (method, url) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#open()
 * Initializes a request
 */
</span>    this.method = method;
    this.url = url;
    // parse url
    this.urlParsed = local.urlParse(String(this.url));
    this.hostname = this.urlParsed.hostname;
    this.path = this.urlParsed.pathname + this.urlParsed.search;
    this.port = this.urlParsed.port;
    // init requestStream
    this.requestStream = (this.urlParsed.protocol === 'https:'
        ? local.https
        : local.http).request(this, this.onResponse)
        // handle request-error
        .on('error', this.onError);
}
```
- example usage
```shell
...
    onError();
    return;
}
switch (modeJs) {
case 'browser':
    // init indexedDB
    try {
        request = window.indexedDB.open(storageDir);
        // debug request
        local._debugStorageRequestIndexedDB = request;
        request.onerror = onError;
        request.onsuccess = function () {
            window[storageDir] = request.result;
            onError();
        };
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.overrideMimeType"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>overrideMimeType ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.overrideMimeType)
- description and source-code
```javascript
overrideMimeType = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.send"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>send (data)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.send)
- description and source-code
```javascript
send = function (data) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#send()
 * Sends the request
 */
</span>    var self;
    self = this;
    self.data = data;
    // asynchronously send data
    setTimeout(function () {
        self.requestStream.end(self.data);
    });
}
```
- example usage
```shell
...
        xhr.data.read(function (error, data) {
            if (error) {
                xhr.error = xhr.error || error;
                xhr.onEvent({ type: 'error' });
                return;
            }
            // send data
            xhr.send(local.bufferToNodeBuffer(data));
        });
    } else {
        // send data
        xhr.send(local.bufferToNodeBuffer(xhr.data));
    }
    return xhr;
};
...
```

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.setRequestHeader"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.</span>setRequestHeader (key, value)](#apidoc.element.utility2._http.XMLHttpRequest.prototype.setRequestHeader)
- description and source-code
```javascript
setRequestHeader = function (key, value) {
<span class="apidocCodeCommentSpan">/*
 * https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest#setRequestHeader()
 * Sets the value of an HTTP request header
 */
</span>    key = key.toLowerCase();
    this.headers[key] = value;
    this.requestStream.setHeader(key, value);
}
```
- example usage
```shell
...
xhr.addEventListener('loadstart', local.ajaxProgressUpdate);
xhr.addEventListener('progress', local.ajaxProgressUpdate);
xhr.upload.addEventListener('progress', local.ajaxProgressUpdate);
// open url
xhr.open(xhr.method, xhr.url);
// set request-headers
Object.keys(xhr.headers).forEach(function (key) {
    xhr.setRequestHeader(key, xhr.headers[key]);
});
// debug xhr
if (xhr.modeDebug) {
    console.log(new Date().toISOString() + ' ajax-request ' + JSON.stringify({
        method: xhr.method,
        url: xhr.url,
        headers: xhr.headers,
...
```



# <a name="apidoc.module.utility2._http.XMLHttpRequest.prototype.upload"></a>[module utility2._http.XMLHttpRequest.prototype.upload](#apidoc.module.utility2._http.XMLHttpRequest.prototype.upload)

#### <a name="apidoc.element.utility2._http.XMLHttpRequest.prototype.upload.addEventListener"></a>[function <span class="apidocSignatureSpan">utility2._http.XMLHttpRequest.prototype.upload.</span>addEventListener ()](#apidoc.element.utility2._http.XMLHttpRequest.prototype.upload.addEventListener)
- description and source-code
```javascript
addEventListener = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
        // scroll textarea to bottom
        element.scrollTop = element.scrollHeight;
    };
});
// init event-handling
['change', 'click', 'keyup'].forEach(function (event) {
    Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {
        element.addEventListener(event, local.testRunBrowser);
    });
});
// run tests
local.testRunBrowser();
break;
...
```



# <a name="apidoc.module.utility2.apidoc"></a>[module utility2.apidoc](#apidoc.module.utility2.apidoc)

#### <a name="apidoc.element.utility2.apidoc.apidocCreate"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>apidocCreate (options)](#apidoc.element.utility2.apidoc.apidocCreate)
- description and source-code
```javascript
apidocCreate = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will create the apidoc from options.dir
 */
</span>    var elementCreate, module, moduleMain, readExample, tmp, trimLeft;
    elementCreate = function (module, prefix, key) {
    /*
     * this function will create the apidoc-element in the given module
     */
        var element;
        element = {};
        element.moduleName = prefix.split('.');
        // handle case where module is a function
        if (element.moduleName.slice(-1)[0] === key) {
            element.moduleName.pop();
        }
        element.moduleName = element.moduleName.join('.');
        element.id = encodeURIComponent('apidoc.element.' + prefix + '.' + key);
        element.typeof = typeof module[key];
        element.name = (element.typeof + ' <span class="apidocSignatureSpan">' +
            element.moduleName + '.</span>' + key)
            // handle case where module is a function
            .replace('>.<', '><');
        if (element.typeof !== 'function') {
            return element;
        }
        // init source
        element.source = 'n/a';
        // bug-workaround - catch and ignore error
        // "Function.prototype.toString is not generic"
        try {
            element.source = trimLeft(module[key].toString());
        } catch (ignore) {
        }
        if (element.source.length > 4096) {
            element.source = element.source.slice(0, 4096).trimRight() + ' ...';
        }
        element.source = (options.template === local.templateApidocHtml
            ? local.stringHtmlSafe(element.source)
            : element.source)
            .replace((/\([\S\s]*?\)/), function (match0) {
                // init signature
                element.signature = match0
                    .replace((/ *?\/\*[\S\s]*?\*\/ */g), '')
                    .replace((/,/g), ', ')
                    .replace((/\s+/g), ' ');
                return element.signature;
            })
            .replace(
                (/( *?\/\*[\S\s]*?\*\/\n)/),
                '<span class="apidocCodeCommentSpan">$1</span>'
            )
            .replace((/^function \(/), key + ' = function (');
        // init example
        options.exampleList.some(function (example) {
            example.replace(
                new RegExp('((?:\n.*?){8}\\.)(' + key + ')(\\((?:.*?\n){8})'),
                function (match0, match1, match2, match3) {
                    element.example = '...' + trimLeft(
                        options.template === local.templateApidocHtml
                            ?  local.stringHtmlSafe(match1) +
                                '<span class="apidocCodeKeywordSpan">' +
                                local.stringHtmlSafe(match2) +
                                '</span>' +
                                local.stringHtmlSafe(match3)
                            : match0
                    ).trimRight() + '\n...';
                }
            );
            return element.example;
        });
        element.example = element.example || 'n/a';
        return element;
    };
    readExample = function (file) {
    /*
     * this function will read the example from the given file
     */
        try {
            return ('\n\n\n\n\n\n\n\n' +
                local.fs.readFileSync(local.path.resolve(options.dir, file), 'utf8') +
                '\n\n\n\n\n\n\n\n').replace((/\r\n*/g), '\n');
        } catch (errorCaught) {
            return '';
        }
    };
    trimLeft = function (text) {
    /*
     * this function will normalize the whitespace around the text
     */
        var whitespace;
        whitespace = '';
        text.trim().replace((/^ */gm), function (match0) {
            if (!whitespace || match0.length < whitespace.length) {
                whitespace = match0;
            }
        });
        text = text.replace(new RegExp('^' + whitespace, 'gm'), '');
        // enforce 128 character column limit
        text = text.replace((/^.{128}[^\\\n]+/gm), function (match0) {
            return match0.replace((/(.{128}(?:\b|\w+))/g), '$1\n').trimRight();
        });
        r ...
```
- example usage
```shell
...
local.fs = require('fs');
local.path = require('path');
// run the cli
if (module !== require.main || local.global.utility2_rollup) {
    break;
}
// jslint files
process.stdout.write(local.apidocCreate({
    dir: process.argv[2],
    modulePathList: module.paths,
    template: process.argv[3] === '--markdown'
        ? local.templateApidocMd
        : local.templateApidocHtml
}));
break;
...
```

#### <a name="apidoc.element.utility2.apidoc.apidocModuleDictAdd"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>apidocModuleDictAdd (options, moduleDict)](#apidoc.element.utility2.apidoc.apidocModuleDictAdd)
- description and source-code
```javascript
apidocModuleDictAdd = function (options, moduleDict) {
<span class="apidocCodeCommentSpan">/*
 * this function will add the modules in moduleDict to options.moduleDict
 */
</span>    var isModule, tmp;
    ['child', 'prototype', 'grandchild', 'prototype'].forEach(function (element) {
        Object.keys(moduleDict).sort().forEach(function (prefix) {
            if (!(/^\w[\w\-.]*?$/).test(prefix)) {
                return;
            }
            Object.keys(moduleDict[prefix]).forEach(function (key) {
                if (!(/^\w[\w\-.]*?$/).test(key)) {
                    return;
                }
                // bug-workaround - buggy electron accessors
                try {
                    tmp = element === 'prototype'
                        ? {
                            module: moduleDict[prefix][key].prototype,
                            name: prefix + '.' + key + '.prototype'
                        }
                        : {
                            module: moduleDict[prefix][key],
                            name: prefix + '.' + key
                        };
                    if (!tmp.module ||
                            !(typeof tmp.module === 'function' ||
                            typeof tmp.module === 'object') ||
                            options.moduleDict[tmp.name] ||
                            options.circularList.indexOf(tmp.module) >= 0) {
                        return;
                    }
                    isModule = [
                        tmp.module,
                        tmp.module.prototype
                    ].some(function (dict) {
                        return Object.keys(dict || {}).some(function (key) {
                            try {
                                return typeof dict[key] === 'function';
                            } catch (ignore) {
                            }
                        });
                    });
                    if (!isModule) {
                        return;
                    }
                    options.circularList.push(tmp.module);
                    options.moduleDict[tmp.name] = tmp.module;
                } catch (ignore) {
                }
            });
        });
    });
}
```
- example usage
```shell
...
options.circularList = [];
tmp.forEach(function (element) {
    if (options.circularList.indexOf(element) < 0) {
        options.circularList.push(element);
    }
});
// init moduleDict child
local.apidocModuleDictAdd(options, options.moduleDict);
// init moduleDict lib
(function () {
    // optimization - isolate try-catch block
    try {
        options.libFileList = options.libFileList ||
            local.fs.readdirSync(options.dir + '/lib')
            .sort()
...
```

#### <a name="apidoc.element.utility2.apidoc.assert"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>assert (passed, message)](#apidoc.element.utility2.apidoc.assert)
- description and source-code
```javascript
assert = function (passed, message) {
<span class="apidocCodeCommentSpan">/*
 * this function will throw the error message if passed is falsey
 */
</span>    var error;
    if (passed) {
        return;
    }
    error = message && message.message
        // if message is an error-object, then leave it as is
        ? message
        : new Error(typeof message === 'string'
            // if message is a string, then leave it as is
            ? message
            // else JSON.stringify message
            : JSON.stringify(message));
    throw error;
}
```
- example usage
```shell
...
 * this function will test ajax's "200 ok" handling-behavior
 */
    options = {};
    // test ajax-path 'assets.hello'
    local.ajax({ url: 'assets.hello' }, function (error, xhr) {
        local.tryCatchOnError(function () {
            // validate no error occurred
            local.assert(!error, error);
            // validate data
            options.data = xhr.responseText;
            local.assert(options.data === 'hello', options.data);
            onError();
        }, onError);
    });
};
...
```

#### <a name="apidoc.element.utility2.apidoc.moduleDirname"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>moduleDirname (module, modulePathList)](#apidoc.element.utility2.apidoc.moduleDirname)
- description and source-code
```javascript
moduleDirname = function (module, modulePathList) {
<span class="apidocCodeCommentSpan">/*
 * this function will search modulePathList for the module's __dirname
 */
</span>    var result, tmp;
    // search process.cwd()
    if (!module || module === '.' || module.indexOf('/') >= 0) {
        return require('path').resolve(process.cwd(), module || '');
    }
    // search builtin
    if (Object.keys(process.binding('natives')).indexOf(module) >= 0) {
        return module;
    }
    // search modulePathList
    [
        modulePathList,
        require('module').globalPaths
    ].some(function (modulePathList) {
        modulePathList.some(function (modulePath) {
            try {
                tmp = require('path').resolve(
                    process.cwd(),
                    modulePath + '/' + module
                );
                result = require('fs').statSync(tmp).isDirectory() && tmp;
                return result;
            } catch (ignore) {
            }
        });
        return result;
    });
    return result || '';
}
```
- example usage
```shell
...
    // enforce 128 character column limit
    text = text.replace((/^.{128}[^\\\n]+/gm), function (match0) {
        return match0.replace((/(.{128}(?:\b|\w+))/g), '$1\n').trimRight();
    });
    return text;
};
// init options
options.dir = local.moduleDirname(
    options.dir,
    options.modulePathList || local.module.paths
);
local.objectSetDefault(options, {
    env: {},
    packageJson: JSON.parse(readExample('package.json'))
});
...
```

#### <a name="apidoc.element.utility2.apidoc.nop"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>nop ()](#apidoc.element.utility2.apidoc.nop)
- description and source-code
```javascript
nop = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will demo a failed assertion test\n\
 */\n\
    // jslint-hack\n\
    window.utility2.nop(options);\n\
    window.utility2.assert(false, "this is a failed assertion demo");\n\
    onError();\n\
};\n\
\n\
testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\n\
/*\n\
 * this function will demo a passed ajax test\n\
...
```

#### <a name="apidoc.element.utility2.apidoc.objectSetDefault"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>objectSetDefault (arg, defaults, depth)](#apidoc.element.utility2.apidoc.objectSetDefault)
- description and source-code
```javascript
objectSetDefault = function (arg, defaults, depth) {
<span class="apidocCodeCommentSpan">/*
 * this function will recursively set defaults for undefined-items in the arg
 */
</span>    arg = arg || {};
    defaults = defaults || {};
    Object.keys(defaults).forEach(function (key) {
        var arg2, defaults2;
        arg2 = arg[key];
        // handle misbehaving getter
        try {
            defaults2 = defaults[key];
        } catch (ignore) {
        }
        if (defaults2 === undefined) {
            return;
        }
        // init arg[key] to default value defaults[key]
        if (!arg2) {
            arg[key] = defaults2;
            return;
        }
        // if arg2 and defaults2 are both non-null and non-array objects,
        // then recurse with arg2 and defaults2
        if (depth > 1 &&
                // arg2 is a non-null and non-array object
                arg2 &&
                typeof arg2 === 'object' &&
                !Array.isArray(arg2) &&
                // defaults2 is a non-null and non-array object
                defaults2 &&
                typeof defaults2 === 'object' &&
                !Array.isArray(defaults2)) {
            // recurse
            local.objectSetDefault(arg2, defaults2, depth - 1);
        }
    });
    return arg;
}
```
- example usage
```shell
...
</html>\n\
';
/* jslint-ignore-end */
if (local.templateRender) {
    local.assetsDict['/'] = local.templateRender(
        local.assetsDict['/assets.index.template.html'],
        {
            env: local.objectSetDefault(local.env, {
                npm_package_description: 'example module',
                npm_package_name: 'example',
                npm_package_nameAlias: 'example',
                npm_package_version: '0.0.1'
            })
        }
    );
...
```

#### <a name="apidoc.element.utility2.apidoc.stringHtmlSafe"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>stringHtmlSafe (text)](#apidoc.element.utility2.apidoc.stringHtmlSafe)
- description and source-code
```javascript
stringHtmlSafe = function (text) {
<span class="apidocCodeCommentSpan">/*
 * this function will make the text html-safe
 */
</span>    // new RegExp('[' + '"&\'<>'.split('').sort().join('') + ']', 'g')
    return text.replace((/["&'<>]/g), function (match0) {
        return '&#x' + match0.charCodeAt(0).toString(16) + ';';
    });
}
```
- example usage
```shell
...
    element.source = trimLeft(module[key].toString());
} catch (ignore) {
}
if (element.source.length > 4096) {
    element.source = element.source.slice(0, 4096).trimRight() + ' ...';
}
element.source = (options.template === local.templateApidocHtml
    ? local.stringHtmlSafe(element.source)
    : element.source)
    .replace((/\([\S\s]*?\)/), function (match0) {
        // init signature
        element.signature = match0
            .replace((/ *?\/\*[\S\s]*?\*\/ */g), '')
            .replace((/,/g), ', ')
            .replace((/\s+/g), ' ');
...
```

#### <a name="apidoc.element.utility2.apidoc.templateRender"></a>[function <span class="apidocSignatureSpan">utility2.apidoc.</span>templateRender (template, dict)](#apidoc.element.utility2.apidoc.templateRender)
- description and source-code
```javascript
templateRender = function (template, dict) {
<span class="apidocCodeCommentSpan">/*
 * this function will render the template with the given dict
 */
</span>    var argList, getValue, match, renderPartial, rgx, value;
    dict = dict || {};
    getValue = function (key) {
        argList = key.split(' ');
        value = dict;
        // iteratively lookup nested values in the dict
        argList[0].split('.').forEach(function (key) {
            value = value && value[key];
        });
        return value;
    };
    renderPartial = function (match0, helper, key, partial) {
        switch (helper) {
        case 'each':
            value = getValue(key);
            return Array.isArray(value)
                ? value.map(function (dict) {
                    // recurse with partial
                    return local.templateRender(partial, dict);
                }).join('')
                : '';
        case 'if':
            partial = partial.split('{{#unless ' + key + '}}');
            partial = getValue(key)
                ? partial[0]
                // handle 'unless' case
                : partial.slice(1).join('{{#unless ' + key + '}}');
            // recurse with partial
            return local.templateRender(partial, dict);
        case 'unless':
            return getValue(key)
                ? ''
                // recurse with partial
                : local.templateRender(partial, dict);
        default:
            // recurse with partial
            return match0[0] + local.templateRender(match0.slice(1), dict);
        }
    };
    // render partials
    rgx = (/\{\{#(\w+) ([^}]+?)\}\}/g);
    template = template || '';
    for (match = rgx.exec(template); match; match = rgx.exec(template)) {
        rgx.lastIndex += 1 - match[0].length;
        template = template.replace(
            new RegExp('\\{\\{#(' + match[1] + ') (' + match[2] +
                ')\\}\\}([\\S\\s]*?)\\{\\{/' + match[1] + ' ' + match[2] +
                '\\}\\}'),
            renderPartial
        );
    }
    // search for keys in the template
    return template.replace((/\{\{[^}]+?\}\}/g), function (match0) {
        getValue(match0.slice(2, -2));
        if (value === undefined) {
            return match0;
        }
        argList.slice(1).forEach(function (arg) {
            switch (arg) {
            case 'alphanumeric':
                value = value.replace((/\W/g), '_');
                break;
            case 'decodeURIComponent':
                value = decodeURIComponent(value);
                break;
            case 'encodeURIComponent':
                value = encodeURIComponent(value);
                break;
            case 'htmlSafe':
                value = value.replace((/["&'<>]/g), function (match0) {
                    return '&#x' + match0.charCodeAt(0).toString(16) + ';';
                });
                break;
            case 'jsonStringify':
                value = JSON.stringify(value);
                break;
            case 'jsonStringify4':
                value = JSON.stringify(value, null, 4);
                break;
            case 'markdownCodeSafe':
                value = value.replace((/'/g), '\'');
                break;
            default:
                value = value[arg]();
                break;
            }
        });
        return String(value);
    });
}
```
- example usage
```shell
...
    ]\n\
</div>\n\
</body>\n\
</html>\n\
';
/* jslint-ignore-end */
if (local.templateRender) {
    local.assetsDict['/'] = local.templateRender(
        local.assetsDict['/assets.index.template.html'],
        {
            env: local.objectSetDefault(local.env, {
                npm_package_description: 'example module',
                npm_package_name: 'example',
                npm_package_nameAlias: 'example',
                npm_package_version: '0.0.1'
...
```



# <a name="apidoc.module.utility2.db"></a>[module utility2.db](#apidoc.module.utility2.db)

#### <a name="apidoc.element.utility2.db._DbTable"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>_DbTable (options)](#apidoc.element.utility2.db._DbTable)
- description and source-code
```javascript
_DbTable = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a dbTable
 */
</span>    options = local.normalizeDict(options);
    this.name = String(options.name);
    // register dbTable in dbTableDict
    local.dbTableDict[this.name] = this;
    this.dbRowList = [];
    this.isDirty = null;
    this.idIndexList = [{ name: '_id', dict: {} }];
    this.ttl = 0;
    this.ttlLast = 0;
}
```
- example usage
```shell
...
        /*
* this function will create a dbTable with the given options
*/
   var self;
   options = local.normalizeDict(options);
   // register dbTable
   self = local.dbTableDict[options.name] =
       local.dbTableDict[options.name] || new local._DbTable(options);
   // remove idIndex
   local.normalizeList(options.idIndexRemoveList).forEach(function (index) {
       self.idIndexRemove(index);
   });
   // create idIndex
   local.normalizeList(options.idIndexCreateList).forEach(function (index) {
       self.idIndexCreate(index);
...
```

#### <a name="apidoc.element.utility2.db.dbCrudRemoveAll"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbCrudRemoveAll (onError)](#apidoc.element.utility2.db.dbCrudRemoveAll)
- description and source-code
```javascript
dbCrudRemoveAll = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove all dbRow's from the db
 */
</span>    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].crudRemoveAll(onParallel);
    });
    onParallel();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbDrop"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbDrop (onError)](#apidoc.element.utility2.db.dbDrop)
- description and source-code
```javascript
dbDrop = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will drop the db
 */
</span>    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    local.storageClear(onParallel);
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].drop(onParallel);
    });
    onParallel();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbExport"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbExport (onError)](#apidoc.element.utility2.db.dbExport)
- description and source-code
```javascript
dbExport = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will export the db as serialized text
 */
</span>    var result;
    result = '';
    Object.keys(local.dbTableDict).forEach(function (key) {
        result += local.dbTableDict[key].export();
        result += '\n\n';
    });
    return local.setTimeoutOnError(onError, null, result.trim());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbImport"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbImport (text, onError)](#apidoc.element.utility2.db.dbImport)
- description and source-code
```javascript
dbImport = function (text, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will import the serialized text into the db
 */
</span>    var dbTable;
    text.replace((/^(\w\S*?) (\S+?) (\S+?)$/gm), function (
        match0,
        match1,
        match2,
        match3
    ) {
        // jslint-hack
        local.nop(match0);
        switch (match2) {
        case 'dbRowSet':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.crudSetOneById(JSON.parse(match3));
            break;
        case 'idIndexCreate':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.idIndexCreate(JSON.parse(match3));
            break;
        case 'ttlSet':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.ttlSet(JSON.parse(match3));
            break;
        default:
            local.onErrorDefault(new Error('dbImport - invalid operation - ' + match0));
        }
    });
    return local.setTimeoutOnError(onError);
}
```
- example usage
```shell
...
                return key.indexOf('dbTable.') === 0;
            })
            .forEach(function (key) {
                onParallel.counter += 1;
                local.storageGetItem(key, function (error, data) {
                    onParallel.counter += 1;
                    onParallel(error);
                    local.dbImport(data, onParallel);
                });
            });
        onParallel();
    });
};

local.dbRowGetItem = function (dbRow, key) {
...
```

#### <a name="apidoc.element.utility2.db.dbLoad"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbLoad (onError)](#apidoc.element.utility2.db.dbLoad)
- description and source-code
```javascript
dbLoad = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will load the db from storage
 */
</span>    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    local.storageKeys(function (error, data) {
        onParallel.counter += 1;
        onParallel.counter += 1;
        onParallel(error);
        local.normalizeList(data)
            .filter(function (key) {
                return key.indexOf('dbTable.') === 0;
            })
            .forEach(function (key) {
                onParallel.counter += 1;
                local.storageGetItem(key, function (error, data) {
                    onParallel.counter += 1;
                    onParallel(error);
                    local.dbImport(data, onParallel);
                });
            });
        onParallel();
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbRowGetItem"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbRowGetItem (dbRow, key)](#apidoc.element.utility2.db.dbRowGetItem)
- description and source-code
```javascript
dbRowGetItem = function (dbRow, key) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the item with the given key from dbRow
 */
</span>    var ii, value;
    value = dbRow;
    key = String(key).split('.');
    // optimization - for-loop
    for (ii = 0; ii < key.length && value && typeof value === 'object'; ii += 1) {
        value = value[key[ii]];
    }
    return value === undefined
        ? null
        : value;
}
```
- example usage
```shell
...
// get dbRow's with the given options.query
result = this._crudGetManyByQuery(options.query);
// sort dbRow's with the given options.sort
local.normalizeList(options.sort).forEach(function (element) {
    if (element.isDescending) {
        result.sort(function (aa, bb) {
            return -local.sortCompare(
                local.dbRowGetItem(aa, element.fieldName),
                local.dbRowGetItem(bb, element.fieldName)
            );
        });
    } else {
        result.sort(function (aa, bb) {
            return local.sortCompare(
                local.dbRowGetItem(aa, element.fieldName),
...
```

#### <a name="apidoc.element.utility2.db.dbRowListGetManyByOperator"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbRowListGetManyByOperator (dbRowList, fieldName, operator, bb)](#apidoc.element.utility2.db.dbRowListGetManyByOperator)
- description and source-code
```javascript
dbRowListGetManyByOperator = function (dbRowList, fieldName, operator, bb) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow's in dbRowList with the given operator
 */
</span>    var ii, jj, result, fieldValue, test, typeof2;
    result = [];
    typeof2 = typeof bb;
    if (bb && typeof2 === 'object') {
        switch (operator) {
        case '$in':
        case '$nin':
        case '$regex':
            break;
        default:
            return result;
        }
    }
    switch (operator) {
    case '$eq':
        test = function (aa, bb) {
            return aa === bb;
        };
        break;
    case '$exists':
        bb = !bb;
        test = function (aa, bb) {
            return !((aa === null) ^ bb);
        };
        break;
    case '$gt':
        test = function (aa, bb, typeof1, typeof2) {
            return typeof1 === typeof2 && aa > bb;
        };
        break;
    case '$gte':
        test = function (aa, bb, typeof1, typeof2) {
            return typeof1 === typeof2 && aa >= bb;
        };
        break;
    case '$in':
        if (bb && typeof bb.indexOf === 'function') {
            if (typeof2 === 'string') {
                test = function (aa, bb, typeof1, typeof2) {
                    return typeof1 === typeof2 && bb.indexOf(aa) >= 0;
                };
            } else {
                test = function (aa, bb) {
                    return bb.indexOf(aa) >= 0;
                };
            }
        }
        break;
    case '$lt':
        test = function (aa, bb, typeof1, typeof2) {
            return typeof1 === typeof2 && aa < bb;
        };
        break;
    case '$lte':
        test = function (aa, bb, typeof1, typeof2) {
            return typeof1 === typeof2 && aa <= bb;
        };
        break;
    case '$ne':
        test = function (aa, bb) {
            return aa !== bb;
        };
        break;
    case '$nin':
        if (bb && typeof bb.indexOf === 'function') {
            if (typeof2 === 'string') {
                test = function (aa, bb, typeof1, typeof2) {
                    return typeof1 === typeof2 && bb.indexOf(aa) < 0;
                };
            } else {
                test = function (aa, bb) {
                    return bb.indexOf(aa) < 0;
                };
            }
        }
        break;
    case '$regex':
        if (bb && typeof bb.test === 'function') {
            test = function (aa, bb) {
                return bb.test(aa);
            };
        }
        break;
    case '$typeof':
        test = function (aa, bb, typeof1) {
            // jslint-hack
            local.nop(aa);
            return typeof1 === bb;
        };
        break;
    }
    if (!test) {
        return result;
    }
    // optimization - for-loop
    for (ii = dbRowList.length - 1; ii >= 0; ii -= 1) {
        fieldValue = local.dbRowGetItem(dbRowList[ii], fieldName);
        // normalize to list
        if (!Array.isArray(fieldValue)) {
            fieldValue = [fieldValue];
        }
        // optimization - for-loop
        for (jj = fieldValue.length - 1; jj >= 0; jj -= 1) {
            if (test(fieldValue[jj], bb, typeof fieldValue[jj], typeof2)) {
                result.push(dbRowList[ii]);
                break;
            }
        }
    }
    return result;
}
```
- example usage
```shell
...
         */
var bb, dbRowDict, result;
result = dbRowList;
if (!result.length) {
    return result;
}
if (!(query && typeof query === 'object')) {
    result = local.dbRowListGetManyByOperator(result, fieldName, '$eq', query);
    return result;
}
Object.keys(query).some(function (key) {
    bb = query[key];
    if (key === '$or' && Array.isArray(bb)) {
        dbRowDict = {};
        bb.forEach(function (query) {
...
```

#### <a name="apidoc.element.utility2.db.dbRowListGetManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbRowListGetManyByQuery (dbRowList, query, fieldName)](#apidoc.element.utility2.db.dbRowListGetManyByQuery)
- description and source-code
```javascript
dbRowListGetManyByQuery = function (dbRowList, query, fieldName) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow's in dbRowList with the given query
 */
</span>    var bb, dbRowDict, result;
    result = dbRowList;
    if (!result.length) {
        return result;
    }
    if (!(query && typeof query === 'object')) {
        result = local.dbRowListGetManyByOperator(result, fieldName, '$eq', query);
        return result;
    }
    Object.keys(query).some(function (key) {
        bb = query[key];
        if (key === '$or' && Array.isArray(bb)) {
            dbRowDict = {};
            bb.forEach(function (query) {
                // recurse
                local.dbRowListGetManyByQuery(result, query).forEach(function (dbRow) {
                    dbRowDict[dbRow._id] = dbRow;
                });
            });
            result = Object.keys(dbRowDict).map(function (id) {
                return dbRowDict[id];
            });
            return !result.length;
        }
        if (key[0] === '$') {
            result = local.dbRowListGetManyByOperator(result, fieldName, key, bb);
            return !result.length;
        }
        // recurse
        result = local.dbRowListGetManyByQuery(result, bb, key);
        return !result.length;
    });
    return result;
}
```
- example usage
```shell
...
    }
};

local._DbTable.prototype._crudGetManyByQuery = function (query) {
/*
 * this function will get the dbRow's in the dbTable with the given query
 */
    return local.dbRowListGetManyByQuery(this.dbRowList, local.normalizeDict(query));
};

local._DbTable.prototype._crudGetOneById = function (idDict) {
/*
 * this function will get the dbRow in the dbTable with the given idDict
 */
    var id, result;
...
```

#### <a name="apidoc.element.utility2.db.dbRowProject"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbRowProject (dbRow, projection)](#apidoc.element.utility2.db.dbRowProject)
- description and source-code
```javascript
dbRowProject = function (dbRow, projection) {
<span class="apidocCodeCommentSpan">/*
 * this function will project and deepcopy the dbRow
 */
</span>    var result;
    if (!dbRow) {
        return null;
    }
    // handle list-case
    if (Array.isArray(dbRow)) {
        return dbRow.map(function (dbRow) {
            // recurse
            return local.dbRowProject(dbRow, projection);
        });
    }
    // normalize to list
    if (!(Array.isArray(projection) && projection.length)) {
        projection = Object.keys(dbRow);
    }
    result = {};
    projection.forEach(function (key) {
        if (key[0] !== '$') {
            result[key] = dbRow[key];
        }
    });
    return local.jsonCopy(result);
}
```
- example usage
```shell
...
local._DbTable.prototype.crudGetManyById = function (idDictList, onError) {
/*
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
    var self;
    this._cleanup();
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (idDict) {
            return self._crudGetOneById(idDict);
        })
    ));
};

local._DbTable.prototype.crudGetManyByQuery = function (options, onError) {
...
```

#### <a name="apidoc.element.utility2.db.dbRowSetId"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbRowSetId (dbRow, idIndex)](#apidoc.element.utility2.db.dbRowSetId)
- description and source-code
```javascript
dbRowSetId = function (dbRow, idIndex) {
<span class="apidocCodeCommentSpan">/*
 * this function will set a random and unique id into dbRow for the given idIndex,
 * if it does not exist
 */
</span>    var id;
    id = dbRow[idIndex.name];
    if (typeof id !== 'number' && typeof id !== 'string') {
        do {
            id = idIndex.isInteger
                ? (1 + Math.random()) * 0x10000000000000
                : 'a' + ((1 + Math.random()) * 0x10000000000000).toString(36).slice(1);
        // optimization - hasOwnProperty
        } while (idIndex.dict.hasOwnProperty(id));
        dbRow[idIndex.name] = id;
    }
    return id;
}
```
- example usage
```shell
...
dbRow = local.jsonCopy(dbRow);
// remove existing dbRow
existing = this._crudRemoveOneById(dbRow) || dbRow;
// init meta
dbRow.$meta = { isRemoved: null, ttl: this.ttl + Date.now() };
this.idIndexList.forEach(function (idIndex) {
    // auto-set id
    id = local.dbRowSetId(existing, idIndex);
    // copy id from existing to dbRow
    dbRow[idIndex.name] = id;
    // set dbRow
    idIndex.dict[id] = dbRow;
});
// update dbRowList
this.dbRowList.push(dbRow);
...
```

#### <a name="apidoc.element.utility2.db.dbSave"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbSave (onError)](#apidoc.element.utility2.db.dbSave)
- description and source-code
```javascript
dbSave = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will save the db to storage
 */
</span>    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key]._save(onParallel);
    });
    onParallel();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbTableCreateMany"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbTableCreateMany (optionsList, onError)](#apidoc.element.utility2.db.dbTableCreateMany)
- description and source-code
```javascript
dbTableCreateMany = function (optionsList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the optionsList into the db
 */
</span>    var onParallel, result;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error, result);
    });
    onParallel.counter += 1;
    result = local.normalizeList(optionsList).map(function (options) {
        onParallel.counter += 1;
        return local.dbTableCreateOne(options, onParallel);
    });
    return local.setTimeoutOnError(onParallel, null, result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.dbTableCreateOne"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>dbTableCreateOne (options, onError)](#apidoc.element.utility2.db.dbTableCreateOne)
- description and source-code
```javascript
dbTableCreateOne = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a dbTable with the given options
 */
</span>    var self;
    options = local.normalizeDict(options);
    // register dbTable
    self = local.dbTableDict[options.name] =
        local.dbTableDict[options.name] || new local._DbTable(options);
    // remove idIndex
    local.normalizeList(options.idIndexRemoveList).forEach(function (index) {
        self.idIndexRemove(index);
    });
    // create idIndex
    local.normalizeList(options.idIndexCreateList).forEach(function (index) {
        self.idIndexCreate(index);
    });
    // upsert dbRow
    self.crudSetManyById(options.dbRowList);
    self.isLoaded = self.isLoaded || options.isLoaded;
    if (!self.isLoaded) {
        local.storageGetItem('dbTable.' + self.name, function (error, data) {
            // validate no error occurred
            console.assert(!error, error);
            if (!self.isLoaded) {
                local.dbImport(data);
            }
            self.isLoaded = true;
            local.setTimeoutOnError(onError, null, self);
        });
        return self;
    }
    return local.setTimeoutOnError(onError, null, self);
}
```
- example usage
```shell
...
*
* this zero-dependency package will provide a persistent, in-browser database
*
* browser example:
*     <script src="assets.db-lite.js"></script>
*     <script>
*     var dbTable1;
*     dbTable1 = window.dbTable1 = window.utility2_db.dbTableCreateOne({ name: "dbTable1" });
*     dbTable1.idIndexCreate({ name: "field1" });
*     dbTable1.crudSetOneById({ field1: "hello", field2: "world" });
*     console.log(dbTable1.crudGetManyByQuery({
*         limit: Infinity,
*         query: { field1: "hello" },
*         skip: 0,
*         sort: [{ fieldName: 'field1', isDescending: false }]
...
```

#### <a name="apidoc.element.utility2.db.jsonCopy"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>jsonCopy (arg)](#apidoc.element.utility2.db.jsonCopy)
- description and source-code
```javascript
jsonCopy = function (arg) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a deep-copy of the JSON-arg
 */
</span>    return arg === undefined
        ? undefined
        : JSON.parse(JSON.stringify(arg));
}
```
- example usage
```shell
...
                return;
            }
            // recurse
            normalize(dbRow[key]);
        });
    }
};
dbRow = local.jsonCopy(dbRow && typeof dbRow === 'object'
    ? dbRow
    : {});
// update timestamp
timeNow = new Date().toISOString();
dbRow._timeCreated = dbRow._timeCreated || timeNow;
dbRow._timeUpdated = timeNow;
// normalize
...
```

#### <a name="apidoc.element.utility2.db.jsonStringifyOrdered"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>jsonStringifyOrdered (element, replacer, space)](#apidoc.element.utility2.db.jsonStringifyOrdered)
- description and source-code
```javascript
jsonStringifyOrdered = function (element, replacer, space) {
<span class="apidocCodeCommentSpan">/*
 * this function will JSON.stringify the element,
 * with object-keys sorted and circular-references removed
 */
</span>    var circularList, stringify, tmp;
    stringify = function (element) {
    /*
     * this function will recursively JSON.stringify the element,
     * with object-keys sorted and circular-references removed
     */
        // if element is an object, then recurse its items with object-keys sorted
        if (element &&
                typeof element === 'object' &&
                typeof element.toJSON !== 'function') {
            // ignore circular-reference
            if (circularList.indexOf(element) >= 0) {
                return;
            }
            circularList.push(element);
            // if element is an array, then recurse its elements
            if (Array.isArray(element)) {
                return '[' + element.map(function (element) {
                    // recurse
                    tmp = stringify(element);
                    return typeof tmp === 'string'
                        ? tmp
                        : 'null';
                }).join(',') + ']';
            }
            return '{' + Object.keys(element)
                // sort object-keys
                .sort()
                .map(function (key) {
                    // recurse
                    tmp = stringify(element[key]);
                    if (typeof tmp === 'string') {
                        return JSON.stringify(key) + ':' + tmp;
                    }
                })
                .filter(function (element) {
                    return typeof element === 'string';
                })
                .join(',') + '}';
        }
        // else JSON.stringify as normal
        return JSON.stringify(element);
    };
    circularList = [];
    return JSON.stringify(element && typeof element === 'object'
        // recurse
        ? JSON.parse(stringify(element))
        : element, replacer, space);
}
```
- example usage
```shell
...
if (location.href.indexOf("modeTest=") >= 0) {
    return;
}
// try to JSON.stringify #inputTextareaEval1
try {
    document.querySelector('#outputPreJsonStringify1').textContent = '';
    document.querySelector('#outputPreJsonStringify1').textContent =
        local.jsonStringifyOrdered(
            JSON.parse(document.querySelector('#inputTextareaEval1').value),
            null,
            4
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
...
```

#### <a name="apidoc.element.utility2.db.nop"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>nop ()](#apidoc.element.utility2.db.nop)
- description and source-code
```javascript
nop = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will demo a failed assertion test\n\
 */\n\
    // jslint-hack\n\
    window.utility2.nop(options);\n\
    window.utility2.assert(false, "this is a failed assertion demo");\n\
    onError();\n\
};\n\
\n\
testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\n\
/*\n\
 * this function will demo a passed ajax test\n\
...
```

#### <a name="apidoc.element.utility2.db.normalizeDict"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>normalizeDict (dict)](#apidoc.element.utility2.db.normalizeDict)
- description and source-code
```javascript
normalizeDict = function (dict) {
<span class="apidocCodeCommentSpan">/*
 * this function will normalize the dict
 */
</span>    return dict && typeof dict === 'object' && !Array.isArray(dict)
        ? dict
        : {};
}
```
- example usage
```shell
...

// run shared js-env code - lib.dbTable.js
(function () {
    local._DbTable = function (options) {
    /*
     * this function will create a dbTable
     */
        options = local.normalizeDict(options);
        this.name = String(options.name);
        // register dbTable in dbTableDict
        local.dbTableDict[this.name] = this;
        this.dbRowList = [];
        this.isDirty = null;
        this.idIndexList = [{ name: '_id', dict: {} }];
        this.ttl = 0;
...
```

#### <a name="apidoc.element.utility2.db.normalizeList"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>normalizeList (list)](#apidoc.element.utility2.db.normalizeList)
- description and source-code
```javascript
normalizeList = function (list) {
<span class="apidocCodeCommentSpan">/*
 * this function will normalize the list
 */
</span>    return Array.isArray(list)
        ? list
        : [];
}
```
- example usage
```shell
...
/*
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
    var self;
    this._cleanup();
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (idDict) {
            return self._crudGetOneById(idDict);
        })
    ));
};

local._DbTable.prototype.crudGetManyByQuery = function (options, onError) {
/*
...
```

#### <a name="apidoc.element.utility2.db.objectSetOverride"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>objectSetOverride (arg, overrides, depth, env)](#apidoc.element.utility2.db.objectSetOverride)
- description and source-code
```javascript
objectSetOverride = function (arg, overrides, depth, env) {
<span class="apidocCodeCommentSpan">/*
 * this function will recursively set overrides for items in the arg
 */
</span>    arg = arg || {};
    env = env || (typeof process === 'object' && process.env) || {};
    overrides = overrides || {};
    Object.keys(overrides).forEach(function (key) {
        var arg2, overrides2;
        arg2 = arg[key];
        overrides2 = overrides[key];
        if (overrides2 === undefined) {
            return;
        }
        // if both arg2 and overrides2 are non-null and non-array objects,
        // then recurse with arg2 and overrides2
        if (depth > 1 &&
                // arg2 is a non-null and non-array object
                (arg2 &&
                typeof arg2 === 'object' &&
                !Array.isArray(arg2)) &&
                // overrides2 is a non-null and non-array object
                (overrides2 &&
                typeof overrides2 === 'object' &&
                !Array.isArray(overrides2))) {
            local.objectSetOverride(arg2, overrides2, depth - 1, env);
            return;
        }
        // else set arg[key] with overrides[key]
        arg[key] = arg === env
            // if arg is env, then overrides falsey value with empty string
            ? overrides2 || ''
            : overrides2;
    });
    return arg;
}
```
- example usage
```shell
...
        (arg2 &&
        typeof arg2 === 'object' &&
        !Array.isArray(arg2)) &&
        // overrides2 is a non-null and non-array object
        (overrides2 &&
        typeof overrides2 === 'object' &&
        !Array.isArray(overrides2))) {
    local.objectSetOverride(arg2, overrides2, depth - 1, env);
    return;
}
// else set arg[key] with overrides[key]
arg[key] = arg === env
    // if arg is env, then overrides falsey value with empty string
    ? overrides2 || ''
    : overrides2;
...
```

#### <a name="apidoc.element.utility2.db.onErrorDefault"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>onErrorDefault (error)](#apidoc.element.utility2.db.onErrorDefault)
- description and source-code
```javascript
onErrorDefault = function (error) {
<span class="apidocCodeCommentSpan">/*
 * this function will if error exists, then print error.stack to stderr
 */
</span>    if (error && !local.global.__coverage__) {
        console.error(error.stack);
    }
}
```
- example usage
```shell
...
            dbTable.idIndexCreate(JSON.parse(match3));
            break;
        case 'ttlSet':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.ttlSet(JSON.parse(match3));
            break;
        default:
            local.onErrorDefault(new Error('dbImport - invalid operation - ' + match0));
        }
    });
    return local.setTimeoutOnError(onError);
};

local.dbLoad = function (onError) {
/*
...
```

#### <a name="apidoc.element.utility2.db.onErrorWithStack"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>onErrorWithStack (onError)](#apidoc.element.utility2.db.onErrorWithStack)
- description and source-code
```javascript
onErrorWithStack = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a new callback that will call onError,
 * and append the current stack to any error
 */
</span>    var stack;
    stack = new Error().stack.replace((/(.*?)\n.*?$/m), '$1');
    return function (error, data, meta) {
        if (error &&
                error !== local.errorDefault &&
                String(error.stack).indexOf(stack.split('\n')[2]) < 0) {
            // append the current stack to error.stack
            error.stack += '\n' + stack;
        }
        onError(error, data, meta);
    };
}
```
- example usage
```shell
...
local.onParallel = function (onError, onDebug) {
/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
...
```

#### <a name="apidoc.element.utility2.db.onParallel"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.db.onParallel)
- description and source-code
```javascript
onParallel = function (onError, onDebug) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
</span>    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
        // handle error
        if (error) {
            self.error = error;
            // ensure counter will decrement to 0
            self.counter = 1;
        }
        // decrement counter
        self.counter -= 1;
        // if counter === 0, then call onError with error
        if (self.counter === 0) {
            onError(error);
        }
    };
    // init counter
    self.counter = 0;
    // return callback
    return self;
}
```
- example usage
```shell
...
};

local.dbCrudRemoveAll = function (onError) {
/*
 * this function will remove all dbRow's from the db
 */
    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].crudRemoveAll(onParallel);
    });
...
```

#### <a name="apidoc.element.utility2.db.setTimeoutOnError"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>setTimeoutOnError (onError, error, data)](#apidoc.element.utility2.db.setTimeoutOnError)
- description and source-code
```javascript
setTimeoutOnError = function (onError, error, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will asynchronously call onError
 */
</span>    if (typeof onError === 'function') {
        setTimeout(function () {
            onError(error, data);
        });
    }
    return data;
}
```
- example usage
```shell
...
};

local._DbTable.prototype.crudCountAll = function (onError) {
/*
 * this function will count all of dbRow's in the dbTable
 */
    this._cleanup();
    return local.setTimeoutOnError(onError, null, this.dbRowList.length);
};

local._DbTable.prototype.crudCountManyByQuery = function (query, onError) {
/*
 * this function will count the number of dbRow's in the dbTable with the given query
 */
    this._cleanup();
...
```

#### <a name="apidoc.element.utility2.db.sortCompare"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>sortCompare (aa, bb)](#apidoc.element.utility2.db.sortCompare)
- description and source-code
```javascript
sortCompare = function (aa, bb) {
<span class="apidocCodeCommentSpan">/*
 * this function will compare aa vs bb and return:
 * -1 if aa < bb
 *  0 if aa === bb
 *  1 if aa > bb
 * the priority for comparing different typeof's is:
 * null < boolean < number < string < object < undefined
 */
</span>    var typeof1, typeof2;
    if (aa === bb) {
        return 0;
    }
    if (aa === null) {
        return -1;
    }
    if (bb === null) {
        return 1;
    }
    typeof1 = typeof aa;
    typeof2 = typeof bb;
    if (typeof1 === typeof2) {
        return typeof1 === 'object'
            ? 0
            : aa > bb
            ? 1
            : -1;
    }
    if (typeof1 === 'boolean') {
        return -1;
    }
    if (typeof2 === 'boolean') {
        return 1;
    }
    if (typeof1 === 'number') {
        return -1;
    }
    if (typeof2 === 'number') {
        return 1;
    }
    if (typeof1 === 'string') {
        return -1;
    }
    if (typeof2 === 'string') {
        return 1;
    }
    return 0;
}
```
- example usage
```shell
...
options = local.normalizeDict(options);
// get dbRow's with the given options.query
result = this._crudGetManyByQuery(options.query);
// sort dbRow's with the given options.sort
local.normalizeList(options.sort).forEach(function (element) {
    if (element.isDescending) {
        result.sort(function (aa, bb) {
            return -local.sortCompare(
                local.dbRowGetItem(aa, element.fieldName),
                local.dbRowGetItem(bb, element.fieldName)
            );
        });
    } else {
        result.sort(function (aa, bb) {
            return local.sortCompare(
...
```

#### <a name="apidoc.element.utility2.db.storageClear"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageClear (onError)](#apidoc.element.utility2.db.storageClear)
- description and source-code
```javascript
storageClear = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will clear storage
 */
</span>    defer({ action: 'clear' }, onError);
}
```
- example usage
```shell
...
 * this function will drop the db
 */
    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    local.storageClear(onParallel);
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].drop(onParallel);
    });
    onParallel();
};
...
```

#### <a name="apidoc.element.utility2.db.storageDefer"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageDefer (options, onError)](#apidoc.element.utility2.db.storageDefer)
- description and source-code
```javascript
storageDefer = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will defer options.action until storage is ready
 */
</span>    var data, done, objectStore, onError2, request, tmp;
    onError = onError || function (error) {
        // validate no error occurred
        console.assert(!error, error);
    };
    if (!storage) {
        deferList.push(function () {
            defer(options, onError);
        });
        init();
        return;
    }
    switch (modeJs) {
    case 'browser':
        onError2 = function () {
            /* istanbul ignore next */
            if (done) {
                return;
            }
            done = true;
            onError(
                request && (request.error || request.transaction.error),
                data || request.result || ''
            );
        };
        switch (options.action) {
        case 'clear':
        case 'removeItem':
        case 'setItem':
            objectStore = storage
                .transaction(storageDir, 'readwrite')
                .objectStore(storageDir);
            break;
        default:
            objectStore = storage
                .transaction(storageDir, 'readonly')
                .objectStore(storageDir);
        }
        switch (options.action) {
        case 'clear':
            request = objectStore.clear();
            break;
        case 'getItem':
            request = objectStore.get(String(options.key));
            break;
        case 'keys':
            data = [];
            request = objectStore.openCursor();
            request.onsuccess = function () {
                if (!request.result) {
                    onError2();
                    return;
                }
                data.push(request.result.key);
                request.result.continue();
            };
            break;
        case 'length':
            request = objectStore.count();
            break;
        case 'removeItem':
            request = objectStore.delete(String(options.key));
            break;
        case 'setItem':
            request = objectStore.put(options.value, String(options.key));
            break;
        }
        ['onabort', 'onerror', 'onsuccess'].forEach(function (handler) {
            request[handler] = request[handler] || onError2;
        });
        // debug request
        local._debugStorageRequest = request;
        break;
    case 'node':
        switch (options.action) {
        case 'clear':
            child_process.spawnSync(
                'sh',
                ['-c', 'rm -f ' + storage + '/*'],
                { stdio: ['ignore', 1, 2] }
            );
            setTimeout(onError);
            break;
        case 'getItem':
            fs.readFile(
                storage + '/' + encodeURIComponent(String(options.key)),
                'utf8',
                // ignore error
                function (error, data) {
                    onError(error && null, data || '');
                }
            );
            break;
        case 'keys':
            fs.readdir(storage, function (error, data) {
                onError(error, data && data.map(decodeURIComponent));
            });
            break;
        case 'length':
            fs.readdir(storage, function (error, data) {
                onError(error, data && data.length);
            });
            break;
        case 'removeItem':
            fs.unlink(
                storage + '/' + encodeURIComponent(String(options.key)),
                // ignore error
                function () {
                    onError();
                }
            );
            break;
        case 'setItem':
            tmp = os.tmpdir() + '/' + Date.now() + Math.random();
            // save to tmp
            fs.writeFile(tmp, options.value, function (error) {
                // validate no error occurred
                console.assert(!error, error);
                // rename tmp to key
                fs.rename(
                    tmp,
                    storage + '/' + encodeURIComponent(String(options.key)),
                    onError
                ); ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.storageGetItem"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageGetItem (key, onError)](#apidoc.element.utility2.db.storageGetItem)
- description and source-code
```javascript
storageGetItem = function (key, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the item with the given key from storage
 */
</span>    defer({ action: 'getItem', key: key }, onError);
}
```
- example usage
```shell
...
    onParallel(error);
    local.normalizeList(data)
        .filter(function (key) {
            return key.indexOf('dbTable.') === 0;
        })
        .forEach(function (key) {
            onParallel.counter += 1;
            local.storageGetItem(key, function (error, data) {
                onParallel.counter += 1;
                onParallel(error);
                local.dbImport(data, onParallel);
            });
        });
    onParallel();
});
...
```

#### <a name="apidoc.element.utility2.db.storageInit"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageInit ()](#apidoc.element.utility2.db.storageInit)
- description and source-code
```javascript
storageInit = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will init storage
 */
</span>    var onError, request;
    onError = function (error) {
        // validate no error occurred
        console.assert(!error, error);
        if (modeJs === 'browser') {
            storage = window[storageDir];
        }
        while (deferList.length) {
            deferList.shift()();
        }
    };
    if (modeJs === 'browser') {
        storage = window[storageDir];
    }
    if (storage) {
        onError();
        return;
    }
    switch (modeJs) {
    case 'browser':
        // init indexedDB
        try {
            request = window.indexedDB.open(storageDir);
            // debug request
            local._debugStorageRequestIndexedDB = request;
            request.onerror = onError;
            request.onsuccess = function () {
                window[storageDir] = request.result;
                onError();
            };
            request.onupgradeneeded = function () {
                if (!request.result.objectStoreNames.contains(storageDir)) {
                    request.result.createObjectStore(storageDir);
                }
            };
        } catch (ignore) {
        }
        break;
    case 'node':
        // mkdirp storage
        storage = storageDir;
        child_process.spawnSync(
            'mkdir',
            ['-p', storage],
            { stdio: ['ignore', 1, 2] }
        );
        onError();
        break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.storageKeys"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageKeys (onError)](#apidoc.element.utility2.db.storageKeys)
- description and source-code
```javascript
storageKeys = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get all the keys in storage
 */
</span>    defer({ action: 'keys' }, onError);
}
```
- example usage
```shell
...
        /*
* this function will load the db from storage
*/
   var onParallel;
   onParallel = local.onParallel(function (error) {
       local.setTimeoutOnError(onError, error);
   });
   local.storageKeys(function (error, data) {
       onParallel.counter += 1;
       onParallel.counter += 1;
       onParallel(error);
       local.normalizeList(data)
           .filter(function (key) {
               return key.indexOf('dbTable.') === 0;
           })
...
```

#### <a name="apidoc.element.utility2.db.storageLength"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageLength (onError)](#apidoc.element.utility2.db.storageLength)
- description and source-code
```javascript
storageLength = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the number of items in storage
 */
</span>    defer({ action: 'length' }, onError);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db.storageRemoveItem"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageRemoveItem (key, onError)](#apidoc.element.utility2.db.storageRemoveItem)
- description and source-code
```javascript
storageRemoveItem = function (key, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the item with the given key from storage
 */
</span>    defer({ action: 'removeItem', key: key }, onError);
}
```
- example usage
```shell
...
 */
    console.error('dropping dbTable ' + this.name + ' ...');
    // reset dbTable
    local._DbTable.call(this, this);
    // cancel pending persist
    this.timerPersist = null;
    // clear persistence
    local.storageRemoveItem('dbTable.' + this.name, onError);
};

local._DbTable.prototype.export = function (onError) {
/*
 * this function will export the db
 */
    var ii, result, self;
...
```

#### <a name="apidoc.element.utility2.db.storageSetItem"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>storageSetItem (key, value, onError)](#apidoc.element.utility2.db.storageSetItem)
- description and source-code
```javascript
storageSetItem = function (key, value, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the item with the given key and value to storage
 */
</span>    defer({ action: 'setItem', key: key, value: value }, onError);
}
```
- example usage
```shell
...
    }, 1000);
};

local._DbTable.prototype._save = function (onError) {
/*
 * this function will save the dbTable to storage
 */
    local.storageSetItem('dbTable.' + this.name, this.export(), onError);
};

local._DbTable.prototype.crudCountAll = function (onError) {
/*
 * this function will count all of dbRow's in the dbTable
 */
    this._cleanup();
...
```



# <a name="apidoc.module.utility2.db._DbTable"></a>[module utility2.db._DbTable](#apidoc.module.utility2.db._DbTable)

#### <a name="apidoc.element.utility2.db._DbTable._DbTable"></a>[function <span class="apidocSignatureSpan">utility2.db.</span>_DbTable (options)](#apidoc.element.utility2.db._DbTable._DbTable)
- description and source-code
```javascript
_DbTable = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a dbTable
 */
</span>    options = local.normalizeDict(options);
    this.name = String(options.name);
    // register dbTable in dbTableDict
    local.dbTableDict[this.name] = this;
    this.dbRowList = [];
    this.isDirty = null;
    this.idIndexList = [{ name: '_id', dict: {} }];
    this.ttl = 0;
    this.ttlLast = 0;
}
```
- example usage
```shell
...
        /*
* this function will create a dbTable with the given options
*/
   var self;
   options = local.normalizeDict(options);
   // register dbTable
   self = local.dbTableDict[options.name] =
       local.dbTableDict[options.name] || new local._DbTable(options);
   // remove idIndex
   local.normalizeList(options.idIndexRemoveList).forEach(function (index) {
       self.idIndexRemove(index);
   });
   // create idIndex
   local.normalizeList(options.idIndexCreateList).forEach(function (index) {
       self.idIndexCreate(index);
...
```



# <a name="apidoc.module.utility2.db._DbTable.prototype"></a>[module utility2.db._DbTable.prototype](#apidoc.module.utility2.db._DbTable.prototype)

#### <a name="apidoc.element.utility2.db._DbTable.prototype._cleanup"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_cleanup ()](#apidoc.element.utility2.db._DbTable.prototype._cleanup)
- description and source-code
```javascript
_cleanup = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will cleanup soft-deleted records from the dbTable
 */
</span>    var dbRow, ii, list, ttl;
    ttl = Date.now();
    if (!(this.isDirty ||
          // cleanup ttl every minute
          (this.ttl && this.ttlLast + this.ttl < ttl))) {
        return;
    }
    this.isDirty = null;
    this.ttlLast = ttl;
    // cleanup dbRowList
    list = this.dbRowList;
    this.dbRowList = [];
    // optimization - for-loop
    for (ii = 0; ii < list.length; ii += 1) {
        dbRow = list[ii];
        // cleanup ttl
        if (this.ttl && dbRow.$meta.ttl < ttl) {
            this._crudRemoveOneById(dbRow);
        // cleanup isRemoved
        } else if (!dbRow.$meta.isRemoved) {
            this.dbRowList.push(dbRow);
        }
    }
}
```
- example usage
```shell
...
    local.storageSetItem('dbTable.' + this.name, this.export(), onError);
};

local._DbTable.prototype.crudCountAll = function (onError) {
/*
 * this function will count all of dbRow's in the dbTable
 */
    this._cleanup();
    return local.setTimeoutOnError(onError, null, this.dbRowList.length);
};

local._DbTable.prototype.crudCountManyByQuery = function (query, onError) {
/*
 * this function will count the number of dbRow's in the dbTable with the given query
 */
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._crudGetManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudGetManyByQuery (query)](#apidoc.element.utility2.db._DbTable.prototype._crudGetManyByQuery)
- description and source-code
```javascript
_crudGetManyByQuery = function (query) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow's in the dbTable with the given query
 */
</span>    return local.dbRowListGetManyByQuery(this.dbRowList, local.normalizeDict(query));
}
```
- example usage
```shell
...
/*
 * this function will count the number of dbRow's in the dbTable with the given query
 */
    this._cleanup();
    return local.setTimeoutOnError(
        onError,
        null,
        this._crudGetManyByQuery(query).length
    );
};

local._DbTable.prototype.crudGetManyById = function (idDictList, onError) {
/*
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._crudGetOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudGetOneById (idDict)](#apidoc.element.utility2.db._DbTable.prototype._crudGetOneById)
- description and source-code
```javascript
_crudGetOneById = function (idDict) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow in the dbTable with the given idDict
 */
</span>    var id, result;
    idDict = local.normalizeDict(idDict);
    result = null;
    this.idIndexList.some(function (idIndex) {
        id = idDict[idIndex.name];
        // optimization - hasOwnProperty
        if (idIndex.dict.hasOwnProperty(id)) {
            result = idIndex.dict[id];
            return result;
        }
    });
    return result;
}
```
- example usage
```shell
...
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
    var self;
    this._cleanup();
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (idDict) {
            return self._crudGetOneById(idDict);
        })
    ));
};

local._DbTable.prototype.crudGetManyByQuery = function (options, onError) {
/*
 * this function will get the dbRow's in the dbTable with the given options.query
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._crudRemoveOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudRemoveOneById (idDict, circularList)](#apidoc.element.utility2.db._DbTable.prototype._crudRemoveOneById)
- description and source-code
```javascript
_crudRemoveOneById = function (idDict, circularList) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the dbRow from the dbTable with the given idDict
 */
</span>    var id, result, self;
    if (!idDict) {
        return null;
    }
    self = this;
    circularList = circularList || [idDict];
    result = null;
    self.idIndexList.forEach(function (idIndex) {
        id = idDict[idIndex.name];
        // optimization - hasOwnProperty
        if (!idIndex.dict.hasOwnProperty(id)) {
            return;
        }
        result = idIndex.dict[id];
        delete idIndex.dict[id];
        // optimization - soft-delete
        result.$meta.isRemoved = true;
        self.isDirty = true;
        if (circularList.indexOf(result) >= 0) {
            return;
        }
        circularList.push(result);
        // recurse
        self._crudRemoveOneById(result, circularList);
    });
    // persist
    this._persist();
    return result;
}
```
- example usage
```shell
...
    list = this.dbRowList;
    this.dbRowList = [];
    // optimization - for-loop
    for (ii = 0; ii < list.length; ii += 1) {
        dbRow = list[ii];
        // cleanup ttl
        if (this.ttl && dbRow.$meta.ttl < ttl) {
            this._crudRemoveOneById(dbRow);
        // cleanup isRemoved
        } else if (!dbRow.$meta.isRemoved) {
            this.dbRowList.push(dbRow);
        }
    }
};
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._crudSetOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudSetOneById (dbRow)](#apidoc.element.utility2.db._DbTable.prototype._crudSetOneById)
- description and source-code
```javascript
_crudSetOneById = function (dbRow) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the dbRow into the dbTable with the given dbRow._id
 * WARNING - existing dbRow with conflicting dbRow._id will be removed
 */
</span>    var existing, id, normalize, timeNow;
    normalize = function (dbRow) {
    /*
     * this function will recursively normalize dbRow
     */
        if (dbRow && typeof dbRow === 'object') {
            Object.keys(dbRow).forEach(function (key) {
                // remove invalid property
                if (key[0] === '$' || key.indexOf('.') >= 0 || dbRow[key] === null) {
                    // optimization - soft-delete
                    dbRow[key] = undefined;
                    return;
                }
                // recurse
                normalize(dbRow[key]);
            });
        }
    };
    dbRow = local.jsonCopy(dbRow && typeof dbRow === 'object'
        ? dbRow
        : {});
    // update timestamp
    timeNow = new Date().toISOString();
    dbRow._timeCreated = dbRow._timeCreated || timeNow;
    dbRow._timeUpdated = timeNow;
    // normalize
    normalize(dbRow);
    dbRow = local.jsonCopy(dbRow);
    // remove existing dbRow
    existing = this._crudRemoveOneById(dbRow) || dbRow;
    // init meta
    dbRow.$meta = { isRemoved: null, ttl: this.ttl + Date.now() };
    this.idIndexList.forEach(function (idIndex) {
        // auto-set id
        id = local.dbRowSetId(existing, idIndex);
        // copy id from existing to dbRow
        dbRow[idIndex.name] = id;
        // set dbRow
        idIndex.dict[id] = dbRow;
    });
    // update dbRowList
    this.dbRowList.push(dbRow);
    // persist
    this._persist();
    return dbRow;
}
```
- example usage
```shell
...
    }
    // remove existing dbRow
    this._crudRemoveOneById(result);
    // update dbRow
    dbRow._timeCreated = undefined;
    local.objectSetOverride(result, dbRow, Infinity);
    // replace dbRow
    result = this._crudSetOneById(result);
    return result;
};

local._DbTable.prototype._persist = function () {
/*
 * this function will persist the dbTable to storage
 */
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._crudUpdateOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_crudUpdateOneById (dbRow)](#apidoc.element.utility2.db._DbTable.prototype._crudUpdateOneById)
- description and source-code
```javascript
_crudUpdateOneById = function (dbRow) {
<span class="apidocCodeCommentSpan">/*
 * this function will update the dbRow in the dbTable,
 * if it exists with the given dbRow._id
 * WARNING
 * existing dbRow's with conflicting unique-keys (besides the one being updated)
 * will be removed
 */
</span>    var id, result;
    dbRow = local.jsonCopy(local.normalizeDict(dbRow));
    result = null;
    this.idIndexList.some(function (idIndex) {
        id = dbRow[idIndex.name];
        // optimization - hasOwnProperty
        if (idIndex.dict.hasOwnProperty(id)) {
            result = idIndex.dict[id];
            return true;
        }
    });
    if (!result) {
        return result;
    }
    // remove existing dbRow
    this._crudRemoveOneById(result);
    // update dbRow
    dbRow._timeCreated = undefined;
    local.objectSetOverride(result, dbRow, Infinity);
    // replace dbRow
    result = this._crudSetOneById(result);
    return result;
}
```
- example usage
```shell
...
 * this function will update the dbRowList in the dbTable,
 * if they exist with the given dbRow._id's
 */
    var self;
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(dbRowList).map(function (dbRow) {
            return self._crudUpdateOneById(dbRow);
        })
    ));
};

local._DbTable.prototype.crudUpdateManyByQuery = function (query, dbRow, onError) {
/*
 * this function will update the dbRow's in the dbTable with the given query
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._persist"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_persist ()](#apidoc.element.utility2.db._DbTable.prototype._persist)
- description and source-code
```javascript
_persist = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will persist the dbTable to storage
 */
</span>    var self;
    self = this;
    // throttle storage-writes to once every 1000 ms
    if (self.timerPersist) {
        return;
    }
    self.timerPersist = setTimeout(function () {
        if (self.timerPersist) {
            self.timerPersist = null;
            self._save();
        }
    }, 1000);
}
```
- example usage
```shell
...
            return;
        }
        circularList.push(result);
        // recurse
        self._crudRemoveOneById(result, circularList);
    });
    // persist
    this._persist();
    return result;
};

local._DbTable.prototype._crudSetOneById = function (dbRow) {
/*
 * this function will set the dbRow into the dbTable with the given dbRow._id
 * WARNING - existing dbRow with conflicting dbRow._id will be removed
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype._save"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>_save (onError)](#apidoc.element.utility2.db._DbTable.prototype._save)
- description and source-code
```javascript
_save = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will save the dbTable to storage
 */
</span>    local.storageSetItem('dbTable.' + this.name, this.export(), onError);
}
```
- example usage
```shell
...
    // throttle storage-writes to once every 1000 ms
    if (self.timerPersist) {
        return;
    }
    self.timerPersist = setTimeout(function () {
        if (self.timerPersist) {
            self.timerPersist = null;
            self._save();
        }
    }, 1000);
};

local._DbTable.prototype._save = function (onError) {
/*
 * this function will save the dbTable to storage
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudCountAll"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudCountAll (onError)](#apidoc.element.utility2.db._DbTable.prototype.crudCountAll)
- description and source-code
```javascript
crudCountAll = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will count all of dbRow's in the dbTable
 */
</span>    this._cleanup();
    return local.setTimeoutOnError(onError, null, this.dbRowList.length);
}
```
- example usage
```shell
...
        skip: crud.querySkip,
        sort: crud.querySort
    }, function (error, data) {
        crud.queryData = data;
        onParallel(error);
    });
    onParallel.counter += 1;
    crud.dbTable.crudCountAll(function (error, data) {
        crud.paginationCountTotal = data;
        onParallel(error);
    });
    break;
case 'crudGetOneById':
    crud.dbTable.crudGetOneById(crud.queryById, options.onNext);
    break;
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudCountManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudCountManyByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudCountManyByQuery)
- description and source-code
```javascript
crudCountManyByQuery = function (query, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will count the number of dbRow's in the dbTable with the given query
 */
</span>    this._cleanup();
    return local.setTimeoutOnError(
        onError,
        null,
        this._crudGetManyByQuery(query).length
    );
}
```
- example usage
```shell
...
            local.onNext(options, function (error, data, meta) {
switch (options.modeNext) {
case 1:
    crud = request.swgg.crud;
    user = request.swgg.user;
    switch (crud.operationId.split('.')[0]) {
    case 'crudCountManyByQuery':
        crud.dbTable.crudCountManyByQuery(crud.queryWhere, options.onNext);
        break;
    case 'crudSetManyById':
        crud.dbTable.crudSetManyById(crud.body, options.onNext);
        break;
    case 'crudSetOneById':
        // replace idField with idAlias in body
        delete crud.body.id;
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudGetManyById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetManyById (idDictList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetManyById)
- description and source-code
```javascript
crudGetManyById = function (idDictList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow's in the dbTable with the given idDictList
 */
</span>    var self;
    this._cleanup();
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (idDict) {
            return self._crudGetOneById(idDict);
        })
    ));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudGetManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetManyByQuery (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetManyByQuery)
- description and source-code
```javascript
crudGetManyByQuery = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow's in the dbTable with the given options.query
 */
</span>    var result;
    this._cleanup();
    options = local.normalizeDict(options);
    // get dbRow's with the given options.query
    result = this._crudGetManyByQuery(options.query);
    // sort dbRow's with the given options.sort
    local.normalizeList(options.sort).forEach(function (element) {
        if (element.isDescending) {
            result.sort(function (aa, bb) {
                return -local.sortCompare(
                    local.dbRowGetItem(aa, element.fieldName),
                    local.dbRowGetItem(bb, element.fieldName)
                );
            });
        } else {
            result.sort(function (aa, bb) {
                return local.sortCompare(
                    local.dbRowGetItem(aa, element.fieldName),
                    local.dbRowGetItem(bb, element.fieldName)
                );
            });
        }
    });
    // skip and limit dbRow's with the given options.skip and options.limit
    result = result.slice(
        options.skip || 0,
        (options.skip || 0) + (options.limit || Infinity)
    );
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        result,
        options.projection
    ));
}
```
- example usage
```shell
...
* browser example:
*     <script src="assets.db-lite.js"></script>
*     <script>
*     var dbTable1;
*     dbTable1 = window.dbTable1 = window.utility2_db.dbTableCreateOne({ name: "dbTable1" });
*     dbTable1.idIndexCreate({ name: "field1" });
*     dbTable1.crudSetOneById({ field1: "hello", field2: "world" });
*     console.log(dbTable1.crudGetManyByQuery({
*         limit: Infinity,
*         query: { field1: "hello" },
*         skip: 0,
*         sort: [{ fieldName: 'field1', isDescending: false }]
*     }));
*     </script>
*
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudGetOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetOneById (idDict, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetOneById)
- description and source-code
```javascript
crudGetOneById = function (idDict, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow in the dbTable with the given idDict
 */
</span>    this._cleanup();
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        this._crudGetOneById(idDict)
    ));
}
```
- example usage
```shell
...
    onParallel.counter += 1;
    crud.dbTable.crudCountAll(function (error, data) {
        crud.paginationCountTotal = data;
        onParallel(error);
    });
    break;
case 'crudGetOneById':
    crud.dbTable.crudGetOneById(crud.queryById, options.onNext);
    break;
case 'crudGetOneByQuery':
    crud.dbTable.crudGetOneByQuery({
        query: crud.queryWhere
    }, options.onNext);
    break;
case 'crudNullDelete':
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudGetOneByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudGetOneByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudGetOneByQuery)
- description and source-code
```javascript
crudGetOneByQuery = function (query, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the dbRow in the dbTable with the given query
 */
</span>    var ii, result;
    this._cleanup();
    // optimization - for-loop
    for (ii = 0; ii < this.dbRowList.length; ii += 1) {
        result = local.dbRowListGetManyByQuery([this.dbRowList[ii]], query)[0];
        if (result) {
            break;
        }
    }
    return local.setTimeoutOnError(onError, null, local.dbRowProject(result));
}
```
- example usage
```shell
...
        onParallel(error);
    });
    break;
case 'crudGetOneById':
    crud.dbTable.crudGetOneById(crud.queryById, options.onNext);
    break;
case 'crudGetOneByQuery':
    crud.dbTable.crudGetOneByQuery({
        query: crud.queryWhere
    }, options.onNext);
    break;
case 'crudNullDelete':
case 'crudNullGet':
case 'crudNullHead':
case 'crudNullOptions':
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudRemoveAll"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveAll (onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveAll)
- description and source-code
```javascript
crudRemoveAll = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove all of the dbRow's from the dbTable
 */
</span>    var idIndexList;
    // save idIndexList
    idIndexList = this.idIndexList;
    // reset dbTable
    local._DbTable.call(this, this);
    // restore idIndexList
    local.dbTableCreateOne({
        name: this.name,
        idIndexCreateList: idIndexList
    }, onError);
}
```
- example usage
```shell
...
    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].crudRemoveAll(onParallel);
    });
    onParallel();
};

local.dbDrop = function (onError) {
/*
 * this function will drop the db
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveManyById (idDictList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyById)
- description and source-code
```javascript
crudRemoveManyById = function (idDictList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the dbRow's from the dbTable with the given idDictList
 */
</span>    var self;
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(idDictList).map(function (dbRow) {
            return self._crudRemoveOneById(dbRow);
        })
    ));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveManyByQuery (query, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveManyByQuery)
- description and source-code
```javascript
crudRemoveManyByQuery = function (query, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the dbRow's from the dbTable with the given query
 */
</span>    var self;
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        self._crudGetManyByQuery(query).map(function (dbRow) {
            return self._crudRemoveOneById(dbRow);
        })
    ));
}
```
- example usage
```shell
...
case 'crudNullOptions':
case 'crudNullPatch':
case 'crudNullPost':
case 'crudNullPut':
    options.onNext();
    break;
case 'crudRemoveManyByQuery':
    crud.dbTable.crudRemoveManyByQuery(crud.queryWhere, options.onNext);
    break;
case 'crudRemoveOneById':
    crud.dbTable.crudRemoveOneById(crud.queryById, options.onNext);
    break;
case 'fileGetOneById':
    local.dbTableFile = local.db.dbTableCreateOne({ name: 'File' });
    crud.dbTable.crudGetOneById(crud.queryById, options.onNext);
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudRemoveOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudRemoveOneById (idDict, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudRemoveOneById)
- description and source-code
```javascript
crudRemoveOneById = function (idDict, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the dbRow from the dbTable with the given idDict
 */
</span>    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        this._crudRemoveOneById(idDict)
    ));
}
```
- example usage
```shell
...
case 'crudNullPut':
    options.onNext();
    break;
case 'crudRemoveManyByQuery':
    crud.dbTable.crudRemoveManyByQuery(crud.queryWhere, options.onNext);
    break;
case 'crudRemoveOneById':
    crud.dbTable.crudRemoveOneById(crud.queryById, options.onNext);
    break;
case 'fileGetOneById':
    local.dbTableFile = local.db.dbTableCreateOne({ name: 'File' });
    crud.dbTable.crudGetOneById(crud.queryById, options.onNext);
    break;
case 'fileUploadManyByForm':
    local.dbTableFile = local.db.dbTableCreateOne({ name: 'File' });
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudSetManyById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudSetManyById (dbRowList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudSetManyById)
- description and source-code
```javascript
crudSetManyById = function (dbRowList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the dbRowList into the dbTable
 */
</span>    var self;
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(dbRowList).map(function (dbRow) {
            return self._crudSetOneById(dbRow);
        })
    ));
}
```
- example usage
```shell
...
    self.idIndexRemove(index);
});
// create idIndex
local.normalizeList(options.idIndexCreateList).forEach(function (index) {
    self.idIndexCreate(index);
});
// upsert dbRow
self.crudSetManyById(options.dbRowList);
self.isLoaded = self.isLoaded || options.isLoaded;
if (!self.isLoaded) {
    local.storageGetItem('dbTable.' + self.name, function (error, data) {
        // validate no error occurred
        console.assert(!error, error);
        if (!self.isLoaded) {
            local.dbImport(data);
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudSetOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudSetOneById (dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudSetOneById)
- description and source-code
```javascript
crudSetOneById = function (dbRow, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the dbRow into the dbTable with the given dbRow._id
 */
</span>    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        this._crudSetOneById(dbRow)
    ));
}
```
- example usage
```shell
...
*
* browser example:
*     <script src="assets.db-lite.js"></script>
*     <script>
*     var dbTable1;
*     dbTable1 = window.dbTable1 = window.utility2_db.dbTableCreateOne({ name: "dbTable1" });
*     dbTable1.idIndexCreate({ name: "field1" });
*     dbTable1.crudSetOneById({ field1: "hello", field2: "world" });
*     console.log(dbTable1.crudGetManyByQuery({
*         limit: Infinity,
*         query: { field1: "hello" },
*         skip: 0,
*         sort: [{ fieldName: 'field1', isDescending: false }]
*     }));
*     </script>
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateManyById (dbRowList, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyById)
- description and source-code
```javascript
crudUpdateManyById = function (dbRowList, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will update the dbRowList in the dbTable,
 * if they exist with the given dbRow._id's
 */
</span>    var self;
    self = this;
    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        local.normalizeList(dbRowList).map(function (dbRow) {
            return self._crudUpdateOneById(dbRow);
        })
    ));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyByQuery"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateManyByQuery (query, dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateManyByQuery)
- description and source-code
```javascript
crudUpdateManyByQuery = function (query, dbRow, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will update the dbRow's in the dbTable with the given query
 */
</span>    var result, self, tmp;
    self = this;
    tmp = local.jsonCopy(local.normalizeDict(dbRow));
    result = self._crudGetManyByQuery(query).map(function (dbRow) {
        tmp._id = dbRow._id;
        return self._crudUpdateOneById(tmp);
    });
    return local.setTimeoutOnError(onError, null, result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.crudUpdateOneById"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>crudUpdateOneById (dbRow, onError)](#apidoc.element.utility2.db._DbTable.prototype.crudUpdateOneById)
- description and source-code
```javascript
crudUpdateOneById = function (dbRow, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will update the dbRow in the dbTable,
 * if it exists with the given dbRow._id
 */
</span>    return local.setTimeoutOnError(onError, null, local.dbRowProject(
        this._crudUpdateOneById(dbRow)
    ));
}
```
- example usage
```shell
...
    crud.dbTable.crudSetOneById(crud.body, options.onNext);
    break;
case 'crudUpdateOneById':
    // replace idField with idAlias in body
    delete crud.body.id;
    delete crud.body[crud.idField];
    crud.body[crud.idAlias] = crud.data[crud.idField];
    crud.dbTable.crudUpdateOneById(crud.body, options.onNext);
    break;
// coverage-hack - test error handling-behavior
case 'crudErrorDelete':
case 'crudErrorGet':
case 'crudErrorHead':
case 'crudErrorOptions':
case 'crudErrorPatch':
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.drop"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>drop (onError)](#apidoc.element.utility2.db._DbTable.prototype.drop)
- description and source-code
```javascript
drop = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will drop the dbTable
 */
</span>    console.error('dropping dbTable ' + this.name + ' ...');
    // reset dbTable
    local._DbTable.call(this, this);
    // cancel pending persist
    this.timerPersist = null;
    // clear persistence
    local.storageRemoveItem('dbTable.' + this.name, onError);
}
```
- example usage
```shell
...
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    local.storageClear(onParallel);
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].drop(onParallel);
    });
    onParallel();
};

local.dbExport = function (onError) {
/*
 * this function will export the db as serialized text
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.export"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>export (onError)](#apidoc.element.utility2.db._DbTable.prototype.export)
- description and source-code
```javascript
export = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will export the db
 */
</span>    var ii, result, self;
    this._cleanup();
    self = this;
    result = '';
    result += self.name + ' ttlSet ' + self.ttl + '\n';
    self.idIndexList.forEach(function (idIndex) {
        result += self.name + ' idIndexCreate ' + JSON.stringify({
            isInteger: idIndex.isInteger,
            name: idIndex.name
        }) + '\n';
    });
    // optimization - for-loop
    for (ii = 0; ii < self.dbRowList.length; ii += 1) {
        result += self.name + ' dbRowSet ' +
            JSON.stringify(local.dbRowProject(self.dbRowList[ii])) + '\n';
    }
    return local.setTimeoutOnError(onError, null, result.trim());
}
```
- example usage
```shell
...
    }, 1000);
};

local._DbTable.prototype._save = function (onError) {
/*
 * this function will save the dbTable to storage
 */
    local.storageSetItem('dbTable.' + this.name, this.export(), onError);
};

local._DbTable.prototype.crudCountAll = function (onError) {
/*
 * this function will count all of dbRow's in the dbTable
 */
    this._cleanup();
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.idIndexCreate"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>idIndexCreate (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.idIndexCreate)
- description and source-code
```javascript
idIndexCreate = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create an idIndex with the given options.name
 */
</span>    var dbRow, idIndex, ii, name;
    options = local.normalizeDict(options);
    name = String(options.name);
    // disallow idIndex with dot-name
    if (name.indexOf('.') >= 0 || name === '_id') {
        return local.setTimeoutOnError(onError);
    }
    // remove existing idIndex
    this.idIndexRemove(options);
    // init idIndex
    idIndex = {
        dict: {},
        isInteger: options.isInteger,
        name: options.name
    };
    this.idIndexList.push(idIndex);
    // populate idIndex with dbRowList
    // optimization - for-loop
    for (ii = 0; ii < this.dbRowList.length; ii += 1) {
        dbRow = this.dbRowList[ii];
        // auto-set id
        if (!dbRow.$meta.isRemoved) {
            idIndex.dict[local.dbRowSetId(dbRow, idIndex)] = dbRow;
        }
    }
    // persist
    this._persist();
    return local.setTimeoutOnError(onError);
}
```
- example usage
```shell
...
* this zero-dependency package will provide a persistent, in-browser database
*
* browser example:
*     <script src="assets.db-lite.js"></script>
*     <script>
*     var dbTable1;
*     dbTable1 = window.dbTable1 = window.utility2_db.dbTableCreateOne({ name: "dbTable1" });
*     dbTable1.idIndexCreate({ name: "field1" });
*     dbTable1.crudSetOneById({ field1: "hello", field2: "world" });
*     console.log(dbTable1.crudGetManyByQuery({
*         limit: Infinity,
*         query: { field1: "hello" },
*         skip: 0,
*         sort: [{ fieldName: 'field1', isDescending: false }]
*     }));
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.idIndexRemove"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>idIndexRemove (options, onError)](#apidoc.element.utility2.db._DbTable.prototype.idIndexRemove)
- description and source-code
```javascript
idIndexRemove = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will remove the idIndex with the given options.name
 */
</span>    var name;
    options = local.normalizeDict(options);
    name = String(options.name);
    this.idIndexList = this.idIndexList.filter(function (idIndex) {
        return idIndex.name !== name || idIndex.name === '_id';
    });
    // persist
    this._persist();
    return local.setTimeoutOnError(onError);
}
```
- example usage
```shell
...
options = local.normalizeDict(options);
name = String(options.name);
// disallow idIndex with dot-name
if (name.indexOf('.') >= 0 || name === '_id') {
    return local.setTimeoutOnError(onError);
}
// remove existing idIndex
this.idIndexRemove(options);
// init idIndex
idIndex = {
    dict: {},
    isInteger: options.isInteger,
    name: options.name
};
this.idIndexList.push(idIndex);
...
```

#### <a name="apidoc.element.utility2.db._DbTable.prototype.ttlSet"></a>[function <span class="apidocSignatureSpan">utility2.db._DbTable.prototype.</span>ttlSet (ttl, onError)](#apidoc.element.utility2.db._DbTable.prototype.ttlSet)
- description and source-code
```javascript
ttlSet = function (ttl, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will set the ttl in milliseconds
 */
</span>    var ii;
    // set ttl in milliseconds
    this.ttl = ttl;
    // update dbRowList
    ttl += Date.now();
    // optimization - for-loop
    for (ii = 0; ii < this.dbRowList.length; ii += 1) {
        this.dbRowList[ii].$meta.ttl = ttl;
    }
    // persist
    this._persist();
    return local.setTimeoutOnError(onError);
}
```
- example usage
```shell
...
            break;
        case 'idIndexCreate':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.idIndexCreate(JSON.parse(match3));
            break;
        case 'ttlSet':
            dbTable = local.dbTableCreateOne({ isLoaded: true, name: match1 });
            dbTable.ttlSet(JSON.parse(match3));
            break;
        default:
            local.onErrorDefault(new Error('dbImport - invalid operation - ' + match0));
        }
    });
    return local.setTimeoutOnError(onError);
};
...
```



# <a name="apidoc.module.utility2.github_crud"></a>[module utility2.github_crud](#apidoc.module.utility2.github_crud)

#### <a name="apidoc.element.utility2.github_crud.contentDelete"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentDelete (options, onError)](#apidoc.element.utility2.github_crud.contentDelete)
- description and source-code
```javascript
contentDelete = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will delete the github file
 * https://developer.github.com/v3/repos/contents/#delete-a-file
 */
</span>    var onParallel;
    options = { message: options.message, url: options.url };
    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        case 1:
            // get sha
            local.contentRequest({ method: 'GET', url: options.url }, options.onNext);
            break;
        case 2:
            // delete file with sha
            if (!error && data.sha) {
                local.contentRequest({
                    message: options.message,
                    method: 'DELETE',
                    sha: data.sha,
                    url: options.url
                }, options.onNext);
                return;
            }
            // delete tree
            onParallel = local.onParallel(options.onNext);
            onParallel.counter += 1;
            data.forEach(function (element) {
                onParallel.counter += 1;
                // recurse
                local.contentDelete({
                    message: options.message,
                    url: element.url
                }, onParallel);
            });
            onParallel();
            break;
        default:
            onError();
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
    }
    // delete tree
    onParallel = local.onParallel(options.onNext);
    onParallel.counter += 1;
    data.forEach(function (element) {
        onParallel.counter += 1;
        // recurse
        local.contentDelete({
            message: options.message,
            url: element.url
        }, onParallel);
    });
    onParallel();
    break;
default:
...
```

#### <a name="apidoc.element.utility2.github_crud.contentGet"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentGet (options, onError)](#apidoc.element.utility2.github_crud.contentGet)
- description and source-code
```javascript
contentGet = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will get the github file
 * https://developer.github.com/v3/repos/contents/#get-contents
 */
</span>    options = { url: options.url };
    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        case 1:
            local.contentRequest({ method: 'GET', url: options.url }, options.onNext);
            break;
        case 2:
            options.onNext(null, new Buffer(data.content, 'base64'));
            break;
        default:
            onError(error, !error && data);
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
    }, function (error) {
        // validate no error occurred
        console.assert(!error, error);
    });
    break;
// get file
case 'get':
    local.contentGet({ url: process.argv[3] }, function (error, data) {
        // validate no error occurred
        console.assert(!error, error);
        try {
            process.stdout.write(data);
        } catch (ignore) {
        }
    });
...
```

#### <a name="apidoc.element.utility2.github_crud.contentPut"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentPut (options, onError)](#apidoc.element.utility2.github_crud.contentPut)
- description and source-code
```javascript
contentPut = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will put options.content into the github file
 * https://developer.github.com/v3/repos/contents/#update-a-file
 */
</span>    options = {
        content: options.content,
        message: options.message,
        modeErrorIgnore: true,
        url: options.url
    };
    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        case 1:
            // get sha
            local.contentRequest({ method: 'GET', url: options.url }, options.onNext);
            break;
        case 2:
            // put file with sha
            local.contentRequest({
                content: options.content,
                message: options.message,
                method: 'PUT',
                sha: data.sha,
                url: options.url
            }, options.onNext);
            break;
        default:
            onError(error);
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
    // get file
    local.fs.readFile(
        local.path.resolve(process.cwd(), options.file),
        options.onNext
    );
    break;
case 2:
    local.contentPut({
        content: data,
        message: options.message,
        // resolve file in url
        url: (/\/$/).test(options.url)
            ? options.url + local.path.basename(options.file)
            : options.url
    }, options.onNext);
...
```

#### <a name="apidoc.element.utility2.github_crud.contentPutFile"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentPutFile (options, onError)](#apidoc.element.utility2.github_crud.contentPutFile)
- description and source-code
```javascript
contentPutFile = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will put options.file into the github file
 * https://developer.github.com/v3/repos/contents/#update-a-file
 */
</span>    options = { file: options.file, message: options.message, url: options.url };
    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        case 1:
            // get file from url
            if ((/^(?:http|https):\/\//).test(options.file)) {
                local.httpRequest({
                    method: 'GET',
                    url: options.file
                }, function (error, response) {
                    options.onNext(error, response && response.data);
                });
                return;
            }
            // get file
            local.fs.readFile(
                local.path.resolve(process.cwd(), options.file),
                options.onNext
            );
            break;
        case 2:
            local.contentPut({
                content: data,
                message: options.message,
                // resolve file in url
                url: (/\/$/).test(options.url)
                    ? options.url + local.path.basename(options.file)
                    : options.url
            }, options.onNext);
            break;
        default:
            onError(error);
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
            process.stdout.write(data);
        } catch (ignore) {
        }
    });
    break;
// put file
case 'put':
    local.contentPutFile({
        message: process.argv[5],
        url: process.argv[3],
        file: process.argv[4]
    }, function (error) {
        // validate no error occurred
        console.assert(!error, error);
    });
...
```

#### <a name="apidoc.element.utility2.github_crud.contentRequest"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentRequest (options, onError)](#apidoc.element.utility2.github_crud.contentRequest)
- description and source-code
```javascript
contentRequest = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will request the content from github
 */
</span>    // init options
    options = {
        chunkList: [],
        content: options.content,
        headers: {
            // github oauth authentication
            Authorization: 'token ' + process.env.GITHUB_TOKEN,
            // bug-workaround - github api requires user-agent header
            'User-Agent': 'undefined'
        },
        message: options.message,
        method: options.method,
        responseJson: {},
        sha: options.sha,
        url: options.url
    };
    options.url = options.url
/* jslint-ignore-begin */
// parse https://github.com/:owner/:repo/blob/:branch/:path
.replace(
    (/^https:\/\/github.com\/([^\/]+?\/[^\/]+?)\/blob\/([^\/]+?)\/(.+)/),
    'https://api.github.com/repos/$1/contents/$3?branch=$2'
)
// parse https://github.com/:owner/:repo/tree/:branch/:path
.replace(
    (/^https:\/\/github.com\/([^\/]+?\/[^\/]+?)\/tree\/([^\/]+?)\/(.+)/),
    'https://api.github.com/repos/$1/contents/$3?branch=$2'
)
// parse https://raw.githubusercontent.com/:owner/:repo/:branch/:path
.replace(
(/^https:\/\/raw.githubusercontent.com\/([^\/]+?\/[^\/]+?)\/([^\/]+?)\/(.+)/),
    'https://api.github.com/repos/$1/contents/$3?branch=$2'
)
// parse https://:owner.github.io/:repo/:path
.replace(
    (/^https:\/\/([^\.]+?)\.github\.io\/([^\/]+?)\/(.+)/),
    'https://api.github.com/repos/$1/$2/contents/$3?branch=gh-pages'
)
/* jslint-ignore-end */
        .replace((/\?branch=(.*)/), function (match0, match1) {
            options.branch = match1;
            if (options.method === 'GET') {
                match0 = match0.replace('branch', 'ref');
            }
            return match0;
        });
    if (options.url.indexOf('https://api.github.com/repos/') !== 0) {
        options.onError2(new Error('invalid url ' + options.url));
        return;
    }
    if (options.method !== 'GET') {
        options.message = options.message ||
            '[ci skip] ' + options.method + ' file ' + options.url
            .replace((/\?.*/), '');
        options.url += '&message=' + encodeURIComponent(options.message);
        if (options.sha) {
            options.url += '&sha=' + options.sha;
        }
        options.data = JSON.stringify({
            branch: options.branch,
            content: new Buffer(options.content || '').toString('base64'),
            message: options.message,
            sha: options.sha
        });
    }
    local.httpRequest(options, function (error, response) {
        try {
            options.responseJson = JSON.parse(response.data.toString());
        } catch (ignore) {
        }
        onError(error, options.responseJson);
    });
}
```
- example usage
```shell
...
         */
var onParallel;
options = { message: options.message, url: options.url };
local.onNext(options, function (error, data) {
    switch (options.modeNext) {
    case 1:
        // get sha
        local.contentRequest({ method: 'GET', url: options.url }, options.onNext);
        break;
    case 2:
        // delete file with sha
        if (!error && data.sha) {
            local.contentRequest({
                message: options.message,
                method: 'DELETE',
...
```

#### <a name="apidoc.element.utility2.github_crud.contentTouch"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>contentTouch (options, onError)](#apidoc.element.utility2.github_crud.contentTouch)
- description and source-code
```javascript
contentTouch = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will touch options.url
 * https://developer.github.com/v3/repos/contents/#update-a-file
 */
</span>    options = {
        message: options.message,
        modeErrorIgnore: true,
        url: options.url
    };
    local.onNext(options, function (error, data) {
        switch (options.modeNext) {
        case 1:
            // get sha
            local.contentRequest({ method: 'GET', url: options.url }, options.onNext);
            break;
        case 2:
            // put file with sha
            local.contentRequest({
                content: new Buffer(data.content || '', 'base64'),
                message: options.message,
                method: 'PUT',
                sha: data.sha,
                url: options.url
            }, options.onNext);
            break;
        default:
            onError(error);
        }
    });
    options.modeNext = 0;
    options.onNext();
}
```
- example usage
```shell
...
    }, function (error) {
        // validate no error occurred
        console.assert(!error, error);
    });
    break;
// touch
case 'touch':
    local.contentTouch({
        message: process.argv[4],
        url: process.argv[3]
    }, function (error) {
        // validate no error occurred
        console.assert(!error, error);
    });
    break;
...
```

#### <a name="apidoc.element.utility2.github_crud.httpRequest"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>httpRequest (options, onError)](#apidoc.element.utility2.github_crud.httpRequest)
- description and source-code
```javascript
httpRequest = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will request the data from options.url
 */
</span>    var chunkList, onError2, timerTimeout, done, request, response, urlParsed;
    // init onError2
    onError2 = function (error) {
        if (done) {
            return;
        }
        done = true;
        // cleanup timerTimeout
        clearTimeout(timerTimeout);
        // cleanup request and response
        [request, response].forEach(function (stream) {
            // try to end the stream
            try {
                stream.end();
            // else try to destroy the stream
            } catch (errorCaught) {
                try {
                    stream.destroy();
                } catch (ignore) {
                }
            }
        });
        if (response && (response.statusCode < 200 || response.statusCode >= 300)) {
            error = error || new Error(response.statusCode);
            console.error(String(response.data));
        }
        // debug response
        console.error(new Date().toISOString() + ' http-response ' + JSON.stringify({
            statusCode: (response && response.statusCode) || 0,
            method: options.method,
            url: options.url
        }));
        onError(error, response);
    };
    // init timerTimeout
    timerTimeout = setTimeout(function () {
        onError2(new Error('http-request timeout'));
    }, options.timeout || 30000);
    urlParsed = require('url').parse(options.url);
    urlParsed.headers = options.headers;
    urlParsed.method = options.method;
    // debug request
    console.error();
    console.error(new Date().toISOString() + ' http-request ' + JSON.stringify({
        method: options.method,
        url: options.url
    }));
    request = require(
        urlParsed.protocol.slice(0, -1)
    ).request(urlParsed, function (_response) {
        response = _response;
        chunkList = [];
        response
            .on('data', function (chunk) {
                chunkList.push(chunk);
            })
            .on('end', function () {
                response.data = Buffer.concat(chunkList);
                onError2();
            })
            .on('error', onError2);
    }).on('error', onError2);
    request.end(options.data);
}
```
- example usage
```shell
...
         */
options = { file: options.file, message: options.message, url: options.url };
local.onNext(options, function (error, data) {
    switch (options.modeNext) {
    case 1:
        // get file from url
        if ((/^(?:http|https):\/\//).test(options.file)) {
            local.httpRequest({
                method: 'GET',
                url: options.file
            }, function (error, response) {
                options.onNext(error, response && response.data);
            });
            return;
        }
...
```

#### <a name="apidoc.element.utility2.github_crud.nop"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>nop ()](#apidoc.element.utility2.github_crud.nop)
- description and source-code
```javascript
nop = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will demo a failed assertion test\n\
 */\n\
    // jslint-hack\n\
    window.utility2.nop(options);\n\
    window.utility2.assert(false, "this is a failed assertion demo");\n\
    onError();\n\
};\n\
\n\
testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\n\
/*\n\
 * this function will demo a passed ajax test\n\
...
```

#### <a name="apidoc.element.utility2.github_crud.onErrorWithStack"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>onErrorWithStack (onError)](#apidoc.element.utility2.github_crud.onErrorWithStack)
- description and source-code
```javascript
onErrorWithStack = function (onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a new callback that will call onError,
 * and append the current stack to any error
 */
</span>    var stack;
    stack = new Error().stack.replace((/(.*?)\n.*?$/m), '$1');
    return function (error, data, meta) {
        if (error &&
                error !== local.errorDefault &&
                String(error.stack).indexOf(stack.split('\n')[2]) < 0) {
            // append the current stack to error.stack
            error.stack += '\n' + stack;
        }
        onError(error, data, meta);
    };
}
```
- example usage
```shell
...
local.onParallel = function (onError, onDebug) {
/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
...
```

#### <a name="apidoc.element.utility2.github_crud.onNext"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>onNext (options, onError)](#apidoc.element.utility2.github_crud.onNext)
- description and source-code
```javascript
onNext = function (options, onError) {
<span class="apidocCodeCommentSpan">/*
 * this function will wrap onError inside the recursive function options.onNext,
 * and append the current stack to any error
 */
</span>    options.onNext = local.onErrorWithStack(function (error, data, meta) {
        try {
            options.modeNext = error && !options.modeErrorIgnore
                ? Infinity
                : options.modeNext + 1;
            onError(error, data, meta);
        } catch (errorCaught) {
            // throw errorCaught to break infinite recursion-loop
            if (options.errorCaught) {
                throw options.errorCaught;
            }
            options.errorCaught = errorCaught;
            options.onNext(errorCaught, data, meta);
        }
    });
    return options;
}
```
- example usage
```shell
...
            onError(error, data, meta);
        } catch (errorCaught) {
            // throw errorCaught to break infinite recursion-loop
            if (options.errorCaught) {
                throw options.errorCaught;
            }
            options.errorCaught = errorCaught;
            options.onNext(errorCaught, data, meta);
        }
    });
    return options;
};

local.onParallel = function (onError, onDebug) {
/*
...
```

#### <a name="apidoc.element.utility2.github_crud.onParallel"></a>[function <span class="apidocSignatureSpan">utility2.github_crud.</span>onParallel (onError, onDebug)](#apidoc.element.utility2.github_crud.onParallel)
- description and source-code
```javascript
onParallel = function (onError, onDebug) {
<span class="apidocCodeCommentSpan">/*
 * this function will create a function that will
 * 1. run async tasks in parallel
 * 2. if counter === 0 or error occurred, then call onError with error
 */
</span>    var self;
    onError = local.onErrorWithStack(onError);
    onDebug = onDebug || local.nop;
    self = function (error) {
        onDebug(error, self);
        // if previously counter === 0 or error occurred, then return
        if (self.counter === 0 || self.error) {
            return;
        }
        // handle error
        if (error) {
            self.error = error;
            // ensure counter will decrement to 0
            self.counter = 1;
        }
        // decrement counter
        self.counter -= 1;
        // if counter === 0, then call onError with error
        if (self.counter === 0) {
            onError(error);
        }
    };
    // init counter
    self.counter = 0;
    // return callback
    return self;
}
```
- example usage
```shell
...
};

local.dbCrudRemoveAll = function (onError) {
/*
 * this function will remove all dbRow's from the db
 */
    var onParallel;
    onParallel = local.onParallel(function (error) {
        local.setTimeoutOnError(onError, error);
    });
    onParallel.counter += 1;
    Object.keys(local.dbTableDict).forEach(function (key) {
        onParallel.counter += 1;
        local.dbTableDict[key].crudRemoveAll(onParallel);
    });
...
```



# <a name="apidoc.module.utility2.istanbul"></a>[module utility2.istanbul](#apidoc.module.utility2.istanbul)

#### <a name="apidoc.element.utility2.istanbul.HtmlReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport)
- description and source-code
```javascript
function HtmlReport(e){Report.call(this),this.opts=e||{},this.opts.dir=this.opts.dir||path.resolve(
process.cwd(),"html-report"),this.opts.sourceStore=this.opts.sourceStore||Store.
create("fslookup"),this.opts.linkMapper=this.opts.linkMapper||this.standardLinkMapper
(),this.opts.writer=this.opts.writer||null,this.opts.templateData={datetime:Date
()},this.opts.watermarks=this.opts.watermarks||defaults.watermarks()}
```
- example usage
```shell
...
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
);
// write coverage.code-dict.json
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter)
- description and source-code
```javascript
function g(e){this.opts=e||{debug:!1,walkDebug:!1,coverageVariable:"__coverage__"
,codeGenerationOptions:undefined,noAutoWrap:!1,noCompact:!1,embedSource:!1,preserveComments
:!1},this.walker=new v({ArrowFunctionExpression:[this.arrowBlockConverter],ExpressionStatement
:this.coverStatement,BreakStatement:this.coverStatement,ContinueStatement:this.coverStatement
,DebuggerStatement:this.coverStatement,ReturnStatement:this.coverStatement,ThrowStatement
:this.coverStatement,TryStatement:[this.paranoidHandlerCheck,this.coverStatement
],VariableDeclaration:this.coverStatement,IfStatement:[this.ifBlockConverter,this
.coverStatement,this.ifBranchInjector],ForStatement:[this.skipInit,this.loopBlockConverter
,this.coverStatement],ForInStatement:[this.skipLeft,this.loopBlockConverter,this
.coverStatement],ForOfStatement:[this.skipLeft,this.loopBlockConverter,this.coverStatement
],WhileStatement:[this.loopBlockConverter,this.coverStatement],DoWhileStatement:
[this.loopBlockConverter,this.coverStatement],SwitchStatement:[this.coverStatement
,this.switchBranchInjector],SwitchCase:[this.switchCaseInjector],WithStatement:[
this.withBlockConverter,this.coverStatement],FunctionDeclaration:[this.coverFunction
,this.coverStatement],FunctionExpression:this.coverFunction,LabeledStatement:this
.coverStatement,ConditionalExpression:this.conditionalBranchInjector,LogicalExpression
:this.logicalExpressionBranchInjector,ObjectExpression:this.maybeAddType},this.extractCurrentHint
,this,this.opts.walkDebug),this.opts.backdoor&&this.opts.backdoor.omitTrackerSuffix&&
(this.omitTrackerSuffix=!0)}
```
- example usage
```shell
...
     * 3. return instrumented code
     */
        // 1. normalize the file
        file = local.path.resolve('/', file);
        // 2. save code to __coverageCodeDict__[file] for future html-report
        local.global.__coverageCodeDict__[file] = code;
        // 3. return instrumented code
        return new local.Instrumenter({
            embedSource: true,
            noAutoWrap: true
        }).instrumentSync(code, file).trimLeft();
    };
    local.util = { inherits: local.nop };
}());
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.istanbul.TextReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>TextReport (e)](#apidoc.element.utility2.istanbul.TextReport)
- description and source-code
```javascript
function TextReport(e){Report.call(this),e=e||{},this.dir=e.dir||process.cwd(),this
.file=e.file,this.summary=e.summary,this.maxCols=e.maxCols||0,this.watermarks=e.
watermarks||defaults.watermarks()}
```
- example usage
```shell
...
    '<h1>coverage-report</h1>\n' +
    '<div ' +
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
...
```

#### <a name="apidoc.element.utility2.istanbul.cliRunIstanbul"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>cliRunIstanbul (options)](#apidoc.element.utility2.istanbul.cliRunIstanbul)
- description and source-code
```javascript
cliRunIstanbul = function (options) {
<span class="apidocCodeCommentSpan">/*
 * this function will run the cli
 */
</span>    var tmp;
    if ((module !== local.require.main || local.global.utility2_rollup) &&
            !(options && options.runMain)) {
        return;
    }
    switch (process.argv[2]) {
    // transparently adds coverage information to a node command
    case 'cover':
        try {
            tmp = JSON.parse(local._fs.readFileSync('package.json', 'utf8'));
            process.env.npm_package_nameAlias = process.env.npm_package_nameAlias ||
                tmp.nameAlias ||
                tmp.name.replace((/-/g), '_');
        } catch (ignore) {
        }
        process.env.npm_config_mode_coverage = process.env.npm_config_mode_coverage ||
            process.env.npm_package_nameAlias ||
            'all';
        // add coverage hook to require
        local._moduleExtensionsJs = local.module._extensions['.js'];
        local.module._extensions['.js'] = function (module, file) {
            if (typeof file === 'string' &&
                    file.indexOf(process.cwd()) === 0 &&
                    file.indexOf(process.cwd() + '/node_modules/') !== 0) {
                module._compile(local.instrumentInPackage(
                    local._fs.readFileSync(file, 'utf8'),
                    file
                ), file);
                return;
            }
            local._moduleExtensionsJs(module, file);
        };
        // init process.argv
        process.argv.splice(1, 2);
        process.argv[1] = local.path.resolve(process.cwd(), process.argv[1]);
        console.log('\ncovering $ ' + process.argv.join(' '));
        // create coverage on exit
        process.on('exit', function () {
            local.coverageReportCreate({ coverage: local.global.__coverage__ });
        });
        // re-run cli
        local.module.runMain();
        break;
    // instrument a file and print result to stdout
    case 'instrument':
        process.argv[3] = local.path.resolve(process.cwd(), process.argv[3]);
        process.stdout.write(local.instrumentSync(
            local._fs.readFileSync(process.argv[3], 'utf8'),
            process.argv[3]
        ));
        break;
    // cover a node command only when npm_config_mode_coverage is set
    case 'test':
        if (process.env.npm_config_mode_coverage) {
            process.argv[2] = 'cover';
            // re-run cli
            local.cliRunIstanbul(options);
            return;
        }
        // init process.argv
        process.argv.splice(1, 2);
        process.argv[1] = local.path.resolve(process.cwd(), process.argv[1]);
        // re-run cli
        local.module.runMain();
        break;
    }
}
```
- example usage
```shell
...
    ));
    break;
// cover a node command only when npm_config_mode_coverage is set
case 'test':
    if (process.env.npm_config_mode_coverage) {
        process.argv[2] = 'cover';
        // re-run cli
        local.cliRunIstanbul(options);
        return;
    }
    // init process.argv
    process.argv.splice(1, 2);
    process.argv[1] = local.path.resolve(process.cwd(), process.argv[1]);
    // re-run cli
    local.module.runMain();
...
```

#### <a name="apidoc.element.utility2.istanbul.coverageMerge"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>coverageMerge (coverage1, coverage2)](#apidoc.element.utility2.istanbul.coverageMerge)
- description and source-code
```javascript
coverageMerge = function (coverage1, coverage2) {
<span class="apidocCodeCommentSpan">/*
 * this function will merge coverage2 into coverage1
 */
</span>    var dict1, dict2;
    coverage1 = coverage1 || {};
    coverage2 = coverage2 || {};
    Object.keys(coverage2).forEach(function (file) {
        if (!coverage2[file]) {
            return;
        }
        // if file is undefined in coverage1, then add it
        if (!coverage1[file]) {
            coverage1[file] = coverage2[file];
            return;
        }
        // merge file from coverage2 into coverage1
        ['b', 'f', 's'].forEach(function (key) {
            dict1 = coverage1[file][key];
            dict2 = coverage2[file][key];
            switch (key) {
            // increment coverage for branch lines
            case 'b':
                Object.keys(dict2).forEach(function (key) {
                    dict2[key].forEach(function (count, ii) {
                        dict1[key][ii] += count;
                    });
                });
                break;
            // increment coverage for function and statement lines
            case 'f':
            case 's':
                Object.keys(dict2).forEach(function (key) {
                    dict1[key] += dict2[key];
                });
                break;
            }
        });
    });
    return coverage1;
}
```
- example usage
```shell
...
}
options = {};
options.dir = process.cwd() + '/tmp/build/coverage.html';
// merge previous coverage
if (local.modeJs === 'node' && process.env.npm_config_mode_coverage_merge) {
    console.log('merging file://' + options.dir + '/coverage.json to coverage');
    try {
        local.coverageMerge(
            local.global.__coverage__,
            JSON.parse(
                local._fs.readFileSync(options.dir + '/coverage.json', 'utf8')
            )
        );
    } catch (ignore) {
    }
...
```

#### <a name="apidoc.element.utility2.istanbul.coverageReportCreate"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>coverageReportCreate ()](#apidoc.element.utility2.istanbul.coverageReportCreate)
- description and source-code
```javascript
coverageReportCreate = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. print coverage in text-format to stdout
 * 2. write coverage in html-format to filesystem
 * 3. return coverage in html-format as single document
 */
</span>    var options;
    /* istanbul ignore next */
    if (!local.global.__coverage__) {
        return '';
    }
    options = {};
    options.dir = process.cwd() + '/tmp/build/coverage.html';
    // merge previous coverage
    if (local.modeJs === 'node' && process.env.npm_config_mode_coverage_merge) {
        console.log('merging file://' + options.dir + '/coverage.json to coverage');
        try {
            local.coverageMerge(
                local.global.__coverage__,
                JSON.parse(
                    local._fs.readFileSync(options.dir + '/coverage.json', 'utf8')
                )
            );
        } catch (ignore) {
        }
        try {
            options.coverageCodeDict = JSON.parse(local._fs.readFileSync(
                options.dir + '/coverage.code-dict.json',
                'utf8'
            ));
            Object.keys(options.coverageCodeDict).forEach(function (key) {
                local.global.__coverageCodeDict__[key] =
                    local.global.__coverageCodeDict__[key] ||
                    options.coverageCodeDict[key];
            });
        } catch (ignore) {
        }
    }
    // init writer
    local.coverageReportHtml = '';
    local.coverageReportHtml += '<div class="coverageReportDiv">\n' +
        '<h1>coverage-report</h1>\n' +
        '<div ' +
        'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
    local.writerData = '';
    options.sourceStore = {};
    options.writer = local.writer;
    // 1. print coverage in text-format to stdout
    new local.TextReport(options).writeReport(local.collector);
    // 2. write coverage in html-format to filesystem
    new local.HtmlReport(options).writeReport(local.collector);
    local.writer.writeFile('', local.nop);
    // write coverage.json
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.json',
        JSON.stringify(local.global.__coverage__)
    );
    // write coverage.code-dict.json
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.code-dict.json',
        JSON.stringify(local.global.__coverageCodeDict__)
    );
    // write coverage.badge.svg
    options.pct = local.coverageReportSummary.root.metrics.lines.pct;
    local.fsWriteFileWithMkdirpSync2(
        local.path.dirname(options.dir) + '/coverage.badge.svg',
        local.templateCoverageBadgeSvg
            // edit coverage badge percent
            .replace((/100.0/g), options.pct)
            // edit coverage badge color
            .replace(
                (/0d0/g),
                ('0' + Math.round((100 - options.pct) * 2.21).toString(16)).slice(-2) +
                    ('0' + Math.round(options.pct * 2.21).toString(16)).slice(-2) + '00'
            )
    );
    console.log('created coverage file://' + options.dir + '/index.html');
    // 3. return coverage in html-format as a single document
    local.coverageReportHtml += '</div>\n</div>\n';
    // write coverage.rollup.html
    local.fsWriteFileWithMkdirpSync2(
        options.dir + '/coverage.rollup.html',
        local.coverageReportHtml
    );
    return local.coverageReportHtml;
}
```
- example usage
```shell
...
        document.querySelector('#outputTextarea1').value =
            local.istanbul.instrumentSync(
                document.querySelector('#inputTextareaEval1').value,
                '/inputTextareaEval1.js'
            );
        eval(document.querySelector('#outputTextarea1').value);
        document.querySelector('#coverageReportDiv1').innerHTML =
            local.istanbul.coverageReportCreate({
                coverage: window.__coverage__
            });
    } catch (errorCaught) {
        console.error(errorCaught.stack);
    }
}
if (document.querySelector('#inputTextareaEval1') && (!event || (event &&
...
```

#### <a name="apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>fsWriteFileWithMkdirpSync (file, data)](#apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync)
- description and source-code
```javascript
fsWriteFileWithMkdirpSync = function (file, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will synchronously 'mkdir -p' and write the data to file
 */
</span>    // try to write to file
    try {
        require('fs').writeFileSync(file, data);
    } catch (errorCaught) {
        // mkdir -p
        require('child_process').spawnSync(
            'mkdir',
            ['-p', require('path').dirname(file)],
            { stdio: ['ignore', 1, 2] }
        );
        // re-write to file
        require('fs').writeFileSync(file, data);
    }
}
```
- example usage
```shell
...
    options.timeoutDefault,
    options.testName
);
// init file urlBrowser
options.modeNext = 20;
options.urlBrowser = local.env.npm_config_dir_tmp + '/electron.' +
    Date.now().toString(16) + Math.random().toString(16) + '.html';
local.fsWriteFileWithMkdirpSync(options.urlBrowser, '<style>body {' +
        'border: 1px solid black;' +
        'margin: 0;' +
        'padding: 0;' +
    '}</style>' +
    '<webview id=webview1 src="' +
    options.url.replace('{{timeExit}}', options.timeExit) +
    '" style="' +
...
```

#### <a name="apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync2"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>fsWriteFileWithMkdirpSync2 (file, data)](#apidoc.element.utility2.istanbul.fsWriteFileWithMkdirpSync2)
- description and source-code
```javascript
fsWriteFileWithMkdirpSync2 = function (file, data) {
<span class="apidocCodeCommentSpan">/*
 * this function will synchronously 'mkdir -p' and write the data to file
 */
</span>    // try to write to file
    try {
        require('fs').writeFileSync(file, data);
    } catch (errorCaught) {
        // mkdir -p
        require('child_process').spawnSync(
            'mkdir',
            ['-p', require('path').dirname(file)],
            { stdio: ['ignore', 1, 2] }
        );
        // re-write to file
        require('fs').writeFileSync(file, data);
    }
}
```
- example usage
```shell
...
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
);
// write coverage.code-dict.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.code-dict.json',
    JSON.stringify(local.global.__coverageCodeDict__)
...
```

#### <a name="apidoc.element.utility2.istanbul.instrumentInPackage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>instrumentInPackage (code, file)](#apidoc.element.utility2.istanbul.instrumentInPackage)
- description and source-code
```javascript
instrumentInPackage = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will instrument the code
 * only if the macro /\* istanbul instrument in package $npm_package_nameAlias *\/
 * exists in the code
 */
</span>    return process.env.npm_config_mode_coverage &&
        code.indexOf('/* istanbul ignore all */\n') < 0 && (
            process.env.npm_config_mode_coverage === 'all' ||
            code.indexOf('/* istanbul instrument in package ' +
                    process.env.npm_package_nameAlias + ' */\n') >= 0 ||
            code.indexOf('/* istanbul instrument in package ' +
                    process.env.npm_config_mode_coverage + ' */\n') >= 0
        )
        ? local.instrumentSync(code, file)
        : code;
}
```
- example usage
```shell
...
    'all';
// add coverage hook to require
local._moduleExtensionsJs = local.module._extensions['.js'];
local.module._extensions['.js'] = function (module, file) {
    if (typeof file === 'string' &&
            file.indexOf(process.cwd()) === 0 &&
            file.indexOf(process.cwd() + '/node_modules/') !== 0) {
        module._compile(local.instrumentInPackage(
            local._fs.readFileSync(file, 'utf8'),
            file
        ), file);
        return;
    }
    local._moduleExtensionsJs(module, file);
};
...
```

#### <a name="apidoc.element.utility2.istanbul.instrumentSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>instrumentSync (code, file)](#apidoc.element.utility2.istanbul.instrumentSync)
- description and source-code
```javascript
instrumentSync = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will
 * 1. normalize the file
 * 2. save code to __coverageCodeDict__[file] for future html-report
 * 3. return instrumented code
 */
</span>    // 1. normalize the file
    file = local.path.resolve('/', file);
    // 2. save code to __coverageCodeDict__[file] for future html-report
    local.global.__coverageCodeDict__[file] = code;
    // 3. return instrumented code
    return new local.Instrumenter({
        embedSource: true,
        noAutoWrap: true
    }).instrumentSync(code, file).trimLeft();
}
```
- example usage
```shell
...
    delete local.global.__coverage__['/inputTextareaEval1.js'];
} catch (ignore) {
}
// try to cover and eval input-code
try {
    /*jslint evil: true*/
    document.querySelector('#outputTextarea1').value =
        local.istanbul.instrumentSync(
            document.querySelector('#inputTextareaEval1').value,
            '/inputTextareaEval1.js'
        );
    eval(document.querySelector('#outputTextarea1').value);
    document.querySelector('#coverageReportDiv1').innerHTML =
        local.istanbul.coverageReportCreate({
            coverage: window.__coverage__
...
```

#### <a name="apidoc.element.utility2.istanbul.nop"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>nop ()](#apidoc.element.utility2.istanbul.nop)
- description and source-code
```javascript
nop = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
    options,\n\
    onError\n\
) {\n\
/*\n\
 * this function will demo a failed assertion test\n\
 */\n\
    // jslint-hack\n\
    window.utility2.nop(options);\n\
    window.utility2.assert(false, "this is a failed assertion demo");\n\
    onError();\n\
};\n\
\n\
testCaseDict.testCase_passed_ajax_demo = function (options, onError) {\n\
/*\n\
 * this function will demo a passed ajax test\n\
...
```

#### <a name="apidoc.element.utility2.istanbul.require"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>require (path)](#apidoc.element.utility2.istanbul.require)
- description and source-code
```javascript
function require(path) {
  try {
    exports.requireDepth += 1;
    return self.require(path);
  } finally {
    exports.requireDepth -= 1;
  }
}
```
- example usage
```shell
...
                return '';
            },
            stdout: {}
        }
        : local.process;
    require = function (key) {
        try {
            return local[key] || local.require(key);
        } catch (ignore) {
        }
    };
}());
...
```



# <a name="apidoc.module.utility2.istanbul.HtmlReport"></a>[module utility2.istanbul.HtmlReport](#apidoc.module.utility2.istanbul.HtmlReport)

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.HtmlReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>HtmlReport (e)](#apidoc.element.utility2.istanbul.HtmlReport.HtmlReport)
- description and source-code
```javascript
function HtmlReport(e){Report.call(this),this.opts=e||{},this.opts.dir=this.opts.dir||path.resolve(
process.cwd(),"html-report"),this.opts.sourceStore=this.opts.sourceStore||Store.
create("fslookup"),this.opts.linkMapper=this.opts.linkMapper||this.standardLinkMapper
(),this.opts.writer=this.opts.writer||null,this.opts.templateData={datetime:Date
()},this.opts.watermarks=this.opts.watermarks||defaults.watermarks()}
```
- example usage
```shell
...
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
);
// write coverage.code-dict.json
...
```



# <a name="apidoc.module.utility2.istanbul.HtmlReport.prototype"></a>[module utility2.istanbul.HtmlReport.prototype](#apidoc.module.utility2.istanbul.HtmlReport.prototype)

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.fillTemplate"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>fillTemplate (e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.fillTemplate)
- description and source-code
```javascript
fillTemplate = function (e, t){var n=this.opts
,r=n.linkMapper;t.entity=e.name||"All files",t.metrics=e.metrics,t.reportClass=getReportClass
(e.metrics.statements,n.watermarks.statements),t.pathHtml=pathTemplate({html:this
.getPathHtml(e,r)}),t.prettify={js:r.asset(e,"prettify.js"),css:r.asset(e,"prettify.css"
)}}
```
- example usage
```shell
...
(e,!0)}}),l;f.unshift({line:0,covered:null,text:new InsertionText("")}),this.fillTemplate
(t,s),e.write(headerTemplate(s)),e.write('<pre><table class="coverage">\n'),annotateLines
(n,f),annotateBranches(n,f),annotateFunctions(n,f),annotateStatements(n,f),f.shift
(),l={structured:f,maxLines:f.length,fileCoverage:n},e.write(detailTemplate(l)),
e.write("</table></pre>\n"),e.write(footerTemplate(s))},writeIndexPage:function(
e,t){var n=this.opts.linkMapper,r=this.opts.templateData,i=Array.prototype.slice
.apply(t.children),s=this.opts.watermarks;i.sort(function(e,t){return e.name<t.name?-1
:1}),this.fillTemplate(t,r),e.write(headerTemplate(r)),e.write(summaryTableHeader
),i.forEach(function(t){var r=t.metrics,i={statements:getReportClass(r.statements
,s.statements),lines:getReportClass(r.lines,s.lines),functions:getReportClass(r.
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))},writeFiles:function(
e,t,n,r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.getPathHtml"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>getPathHtml (e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.getPathHtml)
- description and source-code
```javascript
getPathHtml = function (e, t){var n=e.parent,r=[],i=[],s;while(n)r.
push(n),n=n.parent;for(s=0;s<r.length;s+=1)i.push('<a href="'+t.ancestor(e,s+1)+'">'+
(r[s].relativeName||"All files")+"</a>");return i.reverse(),i.length>0?i.join(" &#187; "
)+" &#187; "+e.displayShortName():""}
```
- example usage
```shell
...
)}),t.join("\n")}),HtmlReport.TYPE="html",util.inherits(HtmlReport,Report),Report
.mix(HtmlReport,{getPathHtml:function(e,t){var n=e.parent,r=[],i=[],s;while(n)r.
push(n),n=n.parent;for(s=0;s<r.length;s+=1)i.push('<a href="'+t.ancestor(e,s+1)+'">'+
(r[s].relativeName||"All files")+"</a>");return i.reverse(),i.length>0?i.join(" &#187; "
)+" &#187; "+e.displayShortName():""},fillTemplate:function(e,t){var n=this.opts
,r=n.linkMapper;t.entity=e.name||"All files",t.metrics=e.metrics,t.reportClass=getReportClass
(e.metrics.statements,n.watermarks.statements),t.pathHtml=pathTemplate({html:this
.getPathHtml(e,r)}),t.prettify={js:r.asset(e,"prettify.js"),css:r.asset(e,"prettify.css"
)}},writeDetailPage:function(e,t,n){var r=this.opts,i=r.sourceStore,s=r.templateData
,o=n.code&&Array.isArray(n.code)?n.code.join("\n")+"\n":i.get(n.path),u=o.split(/(?:\r?\n)|\r/
),a=0,f=u.map(function(e){return a+=1,{line:a,covered:null,text:new InsertionText
(e,!0)}}),l;f.unshift({line:0,covered:null,text:new InsertionText("")}),this.fillTemplate
(t,s),e.write(headerTemplate(s)),e.write('<pre><table class="coverage">\n'),annotateLines
(n,f),annotateBranches(n,f),annotateFunctions(n,f),annotateStatements(n,f),f.shift
(),l={structured:f,maxLines:f.length,fileCoverage:n},e.write(detailTemplate(l)),
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.standardLinkMapper"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>standardLinkMapper ()](#apidoc.element.utility2.istanbul.HtmlReport.prototype.standardLinkMapper)
- description and source-code
```javascript
standardLinkMapper = function (){return{fromParent:function(e){var t=0,n=
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
r.length-1;for(o=0;o<i;o+=1)n+="../";e=e.parent}return n},ancestor:function(e,t)
{return this.ancestorHref(e,t)+"index.html"},asset:function(e,t){var n=0,r=e.parent
;while(r)n+=1,r=r.parent;return this.ancestorHref(e,n)+t}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.writeDetailPage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeDetailPage (e, t, n)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeDetailPage)
- description and source-code
```javascript
writeDetailPage = function (e, t, n){var r=this.opts,i=r.sourceStore,s=r.templateData
,o=n.code&&Array.isArray(n.code)?n.code.join("\n")+"\n":i.get(n.path),u=o.split(/(?:\r?\n)|\r/
),a=0,f=u.map(function(e){return a+=1,{line:a,covered:null,text:new InsertionText
(e,!0)}}),l;f.unshift({line:0,covered:null,text:new InsertionText("")}),this.fillTemplate
(t,s),e.write(headerTemplate(s)),e.write('<pre><table class="coverage">\n'),annotateLines
(n,f),annotateBranches(n,f),annotateFunctions(n,f),annotateStatements(n,f),f.shift
(),l={structured:f,maxLines:f.length,fileCoverage:n},e.write(detailTemplate(l)),
e.write("</table></pre>\n"),e.write(footerTemplate(s))}
```
- example usage
```shell
...
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))},writeFiles:function(
e,t,n,r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
.forEach(function(t){t.kind==="dir"?i.writeFiles(e,t,path.resolve(n,t.relativeName
),r):(o=path.resolve(n,t.relativeName+".html"),i.opts.verbose&&console.error("Writing "+
o),e.writeFile(o,function(e){i.writeDetailPage(e,t,r.fileCoverageFor(t.fullPath(
)))}))})},standardLinkMapper:function(){return{fromParent:function(e){var t=0,n=
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
r.length-1;for(o=0;o<i;o+=1)n+="../";e=e.parent}return n},ancestor:function(e,t)
{return this.ancestorHref(e,t)+"index.html"},asset:function(e,t){var n=0,r=e.parent
;while(r)n+=1,r=r.parent;return this.ancestorHref(e,n)+t}}},writeReport:function(
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.writeFiles"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeFiles ( e, t, n, r)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeFiles)
- description and source-code
```javascript
writeFiles = function ( e, t, n, r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
.forEach(function(t){t.kind==="dir"?i.writeFiles(e,t,path.resolve(n,t.relativeName
),r):(o=path.resolve(n,t.relativeName+".html"),i.opts.verbose&&console.error("Writing "+
o),e.writeFile(o,function(e){i.writeDetailPage(e,t,r.fileCoverageFor(t.fullPath(
)))}))})}
```
- example usage
```shell
...
),i.forEach(function(t){var r=t.metrics,i={statements:getReportClass(r.statements
,s.statements),lines:getReportClass(r.lines,s.lines),functions:getReportClass(r.
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))},writeFiles:function(
e,t,n,r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
.forEach(function(t){t.kind==="dir"?i.writeFiles(e,t,path.resolve(n,t.relativeName
),r):(o=path.resolve(n,t.relativeName+".html"),i.opts.verbose&&console.error("Writing "+
o),e.writeFile(o,function(e){i.writeDetailPage(e,t,r.fileCoverageFor(t.fullPath(
)))}))})},standardLinkMapper:function(){return{fromParent:function(e){var t=0,n=
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
r.length-1;for(o=0;o<i;o+=1)n+="../";e=e.parent}return n},ancestor:function(e,t)
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.writeIndexPage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeIndexPage ( e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeIndexPage)
- description and source-code
```javascript
writeIndexPage = function ( e, t){var n=this.opts.linkMapper,r=this.opts.templateData,i=Array.prototype.slice
.apply(t.children),s=this.opts.watermarks;i.sort(function(e,t){return e.name<t.name?-1
:1}),this.fillTemplate(t,r),e.write(headerTemplate(r)),e.write(summaryTableHeader
),i.forEach(function(t){var r=t.metrics,i={statements:getReportClass(r.statements
,s.statements),lines:getReportClass(r.lines,s.lines),functions:getReportClass(r.
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))}
```
- example usage
```shell
...
:1}),this.fillTemplate(t,r),e.write(headerTemplate(r)),e.write(summaryTableHeader
),i.forEach(function(t){var r=t.metrics,i={statements:getReportClass(r.statements
,s.statements),lines:getReportClass(r.lines,s.lines),functions:getReportClass(r.
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))},writeFiles:function(
e,t,n,r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
.forEach(function(t){t.kind==="dir"?i.writeFiles(e,t,path.resolve(n,t.relativeName
),r):(o=path.resolve(n,t.relativeName+".html"),i.opts.verbose&&console.error("Writing "+
o),e.writeFile(o,function(e){i.writeDetailPage(e,t,r.fileCoverageFor(t.fullPath(
)))}))})},standardLinkMapper:function(){return{fromParent:function(e){var t=0,n=
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
...
```

#### <a name="apidoc.element.utility2.istanbul.HtmlReport.prototype.writeReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.HtmlReport.prototype.</span>writeReport ( e, t)](#apidoc.element.utility2.istanbul.HtmlReport.prototype.writeReport)
- description and source-code
```javascript
writeReport = function ( e, t){var n=this.opts,r=n.dir,i=new TreeSummarizer,s=n.writer||new FileWriter(t),
o;e.files().forEach(function(t){i.addFileCoverageSummary(t,utils.summarizeFileCoverage
(e.fileCoverageFor(t)))}),o=i.getTreeSummary(),fs.readdirSync(path.resolve(__dirname
,"..","vendor")).forEach(function(e){var t=path.resolve(__dirname,"..","vendor",
e),i=path.resolve(r,e),o=fs.statSync(t);o.isFile()&&(n.verbose&&console.log("Write asset: "+
i),s.copyFile(t,i))}),this.writeFiles(s,o.root,r,e)}
```
- example usage
```shell
...
    '<h1>coverage-report</h1>\n' +
    '<div ' +
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
...
```



# <a name="apidoc.module.utility2.istanbul.Instrumenter"></a>[module utility2.istanbul.Instrumenter](#apidoc.module.utility2.istanbul.Instrumenter)

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.Instrumenter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>Instrumenter (e)](#apidoc.element.utility2.istanbul.Instrumenter.Instrumenter)
- description and source-code
```javascript
function g(e){this.opts=e||{debug:!1,walkDebug:!1,coverageVariable:"__coverage__"
,codeGenerationOptions:undefined,noAutoWrap:!1,noCompact:!1,embedSource:!1,preserveComments
:!1},this.walker=new v({ArrowFunctionExpression:[this.arrowBlockConverter],ExpressionStatement
:this.coverStatement,BreakStatement:this.coverStatement,ContinueStatement:this.coverStatement
,DebuggerStatement:this.coverStatement,ReturnStatement:this.coverStatement,ThrowStatement
:this.coverStatement,TryStatement:[this.paranoidHandlerCheck,this.coverStatement
],VariableDeclaration:this.coverStatement,IfStatement:[this.ifBlockConverter,this
.coverStatement,this.ifBranchInjector],ForStatement:[this.skipInit,this.loopBlockConverter
,this.coverStatement],ForInStatement:[this.skipLeft,this.loopBlockConverter,this
.coverStatement],ForOfStatement:[this.skipLeft,this.loopBlockConverter,this.coverStatement
],WhileStatement:[this.loopBlockConverter,this.coverStatement],DoWhileStatement:
[this.loopBlockConverter,this.coverStatement],SwitchStatement:[this.coverStatement
,this.switchBranchInjector],SwitchCase:[this.switchCaseInjector],WithStatement:[
this.withBlockConverter,this.coverStatement],FunctionDeclaration:[this.coverFunction
,this.coverStatement],FunctionExpression:this.coverFunction,LabeledStatement:this
.coverStatement,ConditionalExpression:this.conditionalBranchInjector,LogicalExpression
:this.logicalExpressionBranchInjector,ObjectExpression:this.maybeAddType},this.extractCurrentHint
,this,this.opts.walkDebug),this.opts.backdoor&&this.opts.backdoor.omitTrackerSuffix&&
(this.omitTrackerSuffix=!0)}
```
- example usage
```shell
...
     * 3. return instrumented code
     */
        // 1. normalize the file
        file = local.path.resolve('/', file);
        // 2. save code to __coverageCodeDict__[file] for future html-report
        local.global.__coverageCodeDict__[file] = code;
        // 3. return instrumented code
        return new local.Instrumenter({
            embedSource: true,
            noAutoWrap: true
        }).instrumentSync(code, file).trimLeft();
    };
    local.util = { inherits: local.nop };
}());
switch (local.modeJs) {
...
```



# <a name="apidoc.module.utility2.istanbul.Instrumenter.prototype"></a>[module utility2.istanbul.Instrumenter.prototype](#apidoc.module.utility2.istanbul.Instrumenter.prototype)

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.arrowBlockConverter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>arrowBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.arrowBlockConverter)
- description and source-code
```javascript
arrowBlockConverter = function (e){var t;e.expression&&(t=f.returnStatement(e.body),t.loc=e.body.loc,e
.body=this.convertToBlock(t),e.expression=!1)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.branchIncrementExprAst"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchIncrementExprAst (e, t , n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchIncrementExprAst)
- description and source-code
```javascript
branchIncrementExprAst = function (e, t , n){var r=f.postIncrement(f.subscript(f.subscript(f.dot(f.variable(this.currentState
.trackerVar),f.variable("b")),f.stringLiteral(e)),f.numericLiteral(t)),n);return r
}
```
- example usage
```shell
...
.trackerVar),f.variable("b")),f.stringLiteral(e)),f.numericLiteral(t)),n);return r
},locationsForNodes:function(e){var t=[],n;for(n=0;n<e.length;n+=1)t.push(e[n].loc
);return t},ifBranchInjector:function(e,t){var n=!!this.currentState.ignoring,r=
this.currentState.currentHint,i=!n&&r&&r.type==="if",s=!n&&r&&r.type==="else",o=
e.loc.start.line,u=e.loc.start.column,a=function(){return{line:o,column:u}},l=this
.branchName("if",t.startLineForNode(e),[{start:a(),end:a(),skip:i||undefined},{start
:a(),end:a(),skip:s||undefined}]),c=e.consequent.body,h=e.alternate.body,p;c.unshift
(f.statement(this.branchIncrementExprAst(l,0))),h.unshift(f.statement(this.branchIncrementExprAst
(l,1))),i&&(p=e.consequent,p.preprocessor=this.startIgnore,p.postprocessor=this.
endIgnore),s&&(p=e.alternate,p.preprocessor=this.startIgnore,p.postprocessor=this
.endIgnore)},branchLocationFor:function(e,t){return this.coverState.branchMap[e]
.locations[t]},switchBranchInjector:function(e,t){var n=e.cases,r,i;if(!(n&&n.length>0
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
(n));for(i=0;i<n.length;i+=1)n[i].branchLocation=this.branchLocationFor(r,i),n[i
].consequent.unshift(f.statement(this.branchIncrementExprAst(r,i)))},switchCaseInjector
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.branchLocationFor"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchLocationFor (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchLocationFor)
- description and source-code
```javascript
branchLocationFor = function (e, t){return this.coverState.branchMap[e]
.locations[t]}
```
- example usage
```shell
...
:a(),end:a(),skip:s||undefined}]),c=e.consequent.body,h=e.alternate.body,p;c.unshift
(f.statement(this.branchIncrementExprAst(l,0))),h.unshift(f.statement(this.branchIncrementExprAst
(l,1))),i&&(p=e.consequent,p.preprocessor=this.startIgnore,p.postprocessor=this.
endIgnore),s&&(p=e.alternate,p.preprocessor=this.startIgnore,p.postprocessor=this
.endIgnore)},branchLocationFor:function(e,t){return this.coverState.branchMap[e]
.locations[t]},switchBranchInjector:function(e,t){var n=e.cases,r,i;if(!(n&&n.length>0
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
(n));for(i=0;i<n.length;i+=1)n[i].branchLocation=this.branchLocationFor(r,i),n[i
].consequent.unshift(f.statement(this.branchIncrementExprAst(r,i)))},switchCaseInjector
:function(e){var t=e.branchLocation;delete e.branchLocation,this.maybeSkipNode(e
,"next")&&(t.skip=!0)},conditionalBranchInjector:function(e,t){var n=this.branchName
("cond-expr",t.startLineForNode(e),this.locationsForNodes([e.consequent,e.alternate
])),r=this.branchIncrementExprAst(n,0),i=this.branchIncrementExprAst(n,1);e.consequent
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.branchName"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>branchName (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.branchName)
- description and source-code
```javascript
branchName = function (e, t, n){var r,i=[],s=[],o,u=!!this.currentState.ignoring;this.currentState
.branch+=1,r=this.currentState.branch;for(o=0;o<n.length;o+=1)n[o].skip=n[o].skip||
u||undefined,s.push(n[o]),i.push(0);return this.coverState.b[r]=i,this.coverState
.branchMap[r]={line:t,type:e,locations:s},r}
```
- example usage
```shell
...
.branchMap[r]={line:t,type:e,locations:s},r},branchIncrementExprAst:function(e,t
,n){var r=f.postIncrement(f.subscript(f.subscript(f.dot(f.variable(this.currentState
.trackerVar),f.variable("b")),f.stringLiteral(e)),f.numericLiteral(t)),n);return r
},locationsForNodes:function(e){var t=[],n;for(n=0;n<e.length;n+=1)t.push(e[n].loc
);return t},ifBranchInjector:function(e,t){var n=!!this.currentState.ignoring,r=
this.currentState.currentHint,i=!n&&r&&r.type==="if",s=!n&&r&&r.type==="else",o=
e.loc.start.line,u=e.loc.start.column,a=function(){return{line:o,column:u}},l=this
.branchName("if",t.startLineForNode(e),[{start:a(),end:a(),skip:i||undefined},{start
:a(),end:a(),skip:s||undefined}]),c=e.consequent.body,h=e.alternate.body,p;c.unshift
(f.statement(this.branchIncrementExprAst(l,0))),h.unshift(f.statement(this.branchIncrementExprAst
(l,1))),i&&(p=e.consequent,p.preprocessor=this.startIgnore,p.postprocessor=this.
endIgnore),s&&(p=e.alternate,p.preprocessor=this.startIgnore,p.postprocessor=this
.endIgnore)},branchLocationFor:function(e,t){return this.coverState.branchMap[e]
.locations[t]},switchBranchInjector:function(e,t){var n=e.cases,r,i;if(!(n&&n.length>0
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.conditionalBranchInjector"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>conditionalBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.conditionalBranchInjector)
- description and source-code
```javascript
conditionalBranchInjector = function (e, t){var n=this.branchName
("cond-expr",t.startLineForNode(e),this.locationsForNodes([e.consequent,e.alternate
])),r=this.branchIncrementExprAst(n,0),i=this.branchIncrementExprAst(n,1);e.consequent
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
),e.alternate=f.sequence(i,e.alternate)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.convertToBlock"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>convertToBlock (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.convertToBlock)
- description and source-code
```javascript
convertToBlock = function (e){return e?e.type==="BlockStatement"?
e:{type:"BlockStatement",body:[e]}:{type:"BlockStatement",body:[]}}
```
- example usage
```shell
...
,"%VAR% = %VAR%.%GLOBAL%;","if (!(%VAR%['%FILE%'])) {","   %VAR%['%FILE%'] = %OBJECT%;"
,"}","%VAR% = %VAR%['%FILE%'];"].join("\n").replace(/%STRICT%/g,u(o)).replace(/%VAR%/g
,u(i)).replace(/%GLOBAL%/g,u(n)).replace(/%FILE%/g,u(r)).replace(/%OBJECT%/g,u(s
)),a},startIgnore:function(){this.currentState.ignoring+=1},endIgnore:function()
{this.currentState.ignoring-=1},convertToBlock:function(e){return e?e.type==="BlockStatement"?
e:{type:"BlockStatement",body:[e]}:{type:"BlockStatement",body:[]}},arrowBlockConverter
:function(e){var t;e.expression&&(t=f.returnStatement(e.body),t.loc=e.body.loc,e
.body=this.convertToBlock(t),e.expression=!1)},paranoidHandlerCheck:function(e){!
e.handler&&e.handlers&&(e.handler=e.handlers[0])},ifBlockConverter:function(e){e
.consequent=this.convertToBlock(e.consequent),e.alternate=this.convertToBlock(e.
alternate)},loopBlockConverter:function(e){e.body=this.convertToBlock(e.body)},withBlockConverter
:function(e){e.body=this.convertToBlock(e.body)},statementName:function(e,t){var n
,r=!!this.currentState.ignoring;return e.skip=r||undefined,t=t||0,this.currentState
.statement+=1,n=this.currentState.statement,this.coverState.statementMap[n]=e,this
.coverState.s[n]=t,n},skipInit:function(e){e.init&&(e.init.skipWalk=!0)},skipLeft
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.coverFunction"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>coverFunction (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.coverFunction)
- description and source-code
```javascript
coverFunction = function (e, t){var n,r=e.body,i=r.body,s;this.maybeSkipNode(e,"next"),n=this.functionName
(e,t.startLineForNode(e),{start:e.loc.start,end:{line:e.body.loc.start.line,column
:e.body.loc.start.column}}),i.length>0&&this.isUseStrictExpression(i[0])&&(s=i.shift
()),i.unshift(f.statement(f.postIncrement(f.subscript(f.dot(f.variable(this.currentState
.trackerVar),f.variable("f")),f.stringLiteral(n))))),s&&i.unshift(s)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.coverStatement"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>coverStatement (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.coverStatement)
- description and source-code
```javascript
coverStatement = function (e, n){var r,i,s
;this.maybeSkipNode(e,"next");if(this.isUseStrictExpression(e)){s=n.ancestor(2);
if(s&&(s.node.type===t.FunctionExpression.name||s.node.type===t.FunctionDeclaration
.name)&&n.parent().node.body[0]===e)return}e.type===t.FunctionDeclaration.name?r=
this.statementName(e.loc,1):(r=this.statementName(e.loc),i=f.statement(f.postIncrement
(f.subscript(f.dot(f.variable(this.currentState.trackerVar),f.variable("s")),f.stringLiteral
(r)))),this.splice(i,e,n))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.endIgnore"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>endIgnore ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.endIgnore)
- description and source-code
```javascript
endIgnore = function ()
{this.currentState.ignoring-=1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.extractCurrentHint"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>extractCurrentHint (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.extractCurrentHint)
- description and source-code
```javascript
extractCurrentHint = function (e){if(!e.range)return;
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
this.currentState.currentHint=i,this.currentState.lastHintPosition=t,t+=1}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.filterHints"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>filterHints (e )](#apidoc.element.utility2.istanbul.Instrumenter.prototype.filterHints)
- description and source-code
```javascript
filterHints = function (e ){var t=[],n,r,i;if(!e||!h(e))return t;for(n=0;n<e.length;n+=1)r=e[n],r&&r.value&&
r.range&&h(r.range)&&(i=String(r.value).match(a),i&&t.push({type:i[1],start:r.range
[0],end:r.range[1]}));return t}
```
- example usage
```shell
...
[0],end:r.range[1]}));return t},extractCurrentHint:function(e){if(!e.range)return;
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
this.currentState.currentHint=i,this.currentState.lastHintPosition=t,t+=1}},instrumentASTSync
:function(e,t,n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
.sourceMap=null,this.coverState={path:t,s:{},b:{},f:{},fnMap:{},statementMap:{},
branchMap:{}},this.currentState={trackerVar:p(t,this.omitTrackerSuffix),func:0,branch
:0,variable:0,statement:0,hints:this.filterHints(e.comments),currentHint:null,lastHintPosition
:-1,ignoring:0},e.body&&e.body.length>0&&this.isUseStrictExpression(e.body[0])&&
(e.body.shift(),r=!0),this.walker.startWalk(e),s=this.opts.codeGenerationOptions||
{format:{compact:!this.opts.noCompact}},s.comment=this.opts.preserveComments,o=i
.generate(e,s),u=this.getPreamble(n||"",r);if(o.map&&o.code){a=u.split(/\r\n|\r|\n/
).length;for(f=0;f<o.map._mappings._array.length;f+=1)o.map._mappings._array[f].
generatedLine+=a;this.sourceMap=o.map,o=o.code}return u+"\n"+o+"\n"},instrument:
function(e,t,n){!n&&typeof t=="function"&&(n=t,t=null);try{n(null,this.instrumentSync
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.findLeaves"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>findLeaves ( e, n, r, i)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.findLeaves)
- description and source-code
```javascript
findLeaves = function ( e, n, r, i){e.type===t.LogicalExpression.name?(this.findLeaves(e.left,n,e,"left"),this
.findLeaves(e.right,n,e,"right")):n.push({node:e,parent:r,property:i})}
```
- example usage
```shell
...
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
),e.alternate=f.sequence(i,e.alternate)},maybeAddSkip:function(e){return function(
t){var n=!!this.currentState.ignoring,r=this.currentState.currentHint,i=!n&&r&&r
.type==="next";i&&(this.startIgnore(),t.postprocessor=this.endIgnore);if(i||n)e.
skip=!0}},logicalExpressionBranchInjector:function(e,n){var r=n.parent(),i=[],s,
o,u;this.maybeSkipNode(e,"next");if(r&&r.node.type===t.LogicalExpression.name)return;
this.findLeaves(e,i),s=this.branchName("binary-expr",n.startLineForNode(e),this.
locationsForNodes(i.map(function(e){return e.node})));for(u=0;u<i.length;u+=1)o=
i[u],o.parent[o.property]=f.sequence(this.branchIncrementExprAst(s,u),o.node),o.
node.preprocessor=this.maybeAddSkip(this.branchLocationFor(s,u))},findLeaves:function(
e,n,r,i){e.type===t.LogicalExpression.name?(this.findLeaves(e.left,n,e,"left"),this
.findLeaves(e.right,n,e,"right")):n.push({node:e,parent:r,property:i})},maybeAddType
:function(e){var n=e.properties,r,i;for(r=0;r<n.length;r+=1)i=n[r],i.type||(i.type=
t.Property.name)}},e?module.exports=g:window.Instrumenter=g})(typeof module!="undefined"&&typeof
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.fixColumnPositions"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>fixColumnPositions (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.fixColumnPositions)
- description and source-code
```javascript
fixColumnPositions = function (e){var t=o.length
,n=function(e){e.start.line===1&&(e.start.column-=t),e.end.line===1&&(e.end.column-=
t)},r,i,s,u;i=e.statementMap;for(r in i)i.hasOwnProperty(r)&&n(i[r]);i=e.fnMap;for(
r in i)i.hasOwnProperty(r)&&n(i[r].loc);i=e.branchMap;for(r in i)if(i.hasOwnProperty
(r)){u=i[r].locations;for(s=0;s<u.length;s+=1)n(u[s])}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.functionName"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>functionName (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.functionName)
- description and source-code
```javascript
functionName = function (e, t, n){this
.currentState.func+=1;var r=this.currentState.func,i=!!this.currentState.ignoring
,s=e.id?e.id.name:"(anonymous_"+r+")",o=function(e){var t=n[e]||{};return{line:t
.line,column:t.column}};return this.coverState.fnMap[r]={name:s,line:t,loc:{start
:o("start"),end:o("end")},skip:i||undefined},this.coverState.f[r]=0,r}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.getPreamble"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>getPreamble (e, t )](#apidoc.element.utility2.istanbul.Instrumenter.prototype.getPreamble)
- description and source-code
```javascript
getPreamble = function (e, t ){var n=this.opts.coverageVariable||"__coverage__",r=this.coverState.path.replace
(/\\/g,"\\\\"),i=this.currentState.trackerVar,s,o=t?'"use strict";':"",u=function(
e){return function(){return e}},a;return this.opts.noAutoWrap||this.fixColumnPositions
(this.coverState),this.opts.embedSource&&(this.coverState.code=e.split(/(?:\r?\n)|\r/
)),s=this.opts.debug?JSON.stringify(this.coverState,undefined,4):JSON.stringify(
this.coverState),a=["%STRICT%","var %VAR% = (Function('return this'))();","if (!%VAR%.%GLOBAL%) { %VAR%.%GLOBAL% = {}; }"
,"%VAR% = %VAR%.%GLOBAL%;","if (!(%VAR%['%FILE%'])) {","   %VAR%['%FILE%'] = %OBJECT%;"
,"}","%VAR% = %VAR%['%FILE%'];"].join("\n").replace(/%STRICT%/g,u(o)).replace(/%VAR%/g
,u(i)).replace(/%GLOBAL%/g,u(n)).replace(/%FILE%/g,u(r)).replace(/%OBJECT%/g,u(s
)),a}
```
- example usage
```shell
...
:function(e,t,n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
.sourceMap=null,this.coverState={path:t,s:{},b:{},f:{},fnMap:{},statementMap:{},
branchMap:{}},this.currentState={trackerVar:p(t,this.omitTrackerSuffix),func:0,branch
:0,variable:0,statement:0,hints:this.filterHints(e.comments),currentHint:null,lastHintPosition
:-1,ignoring:0},e.body&&e.body.length>0&&this.isUseStrictExpression(e.body[0])&&
(e.body.shift(),r=!0),this.walker.startWalk(e),s=this.opts.codeGenerationOptions||
{format:{compact:!this.opts.noCompact}},s.comment=this.opts.preserveComments,o=i
.generate(e,s),u=this.getPreamble(n||"",r);if(o.map&&o.code){a=u.split(/\r\n|\r|\n/
).length;for(f=0;f<o.map._mappings._array.length;f+=1)o.map._mappings._array[f].
generatedLine+=a;this.sourceMap=o.map,o=o.code}return u+"\n"+o+"\n"},instrument:
function(e,t,n){!n&&typeof t=="function"&&(n=t,t=null);try{n(null,this.instrumentSync
(e,t))}catch(r){n(r)}},lastFileCoverage:function(){return this.coverState},lastSourceMap
:function(){return this.sourceMap},fixColumnPositions:function(e){var t=o.length
,n=function(e){e.start.line===1&&(e.start.column-=t),e.end.line===1&&(e.end.column-=
t)},r,i,s,u;i=e.statementMap;for(r in i)i.hasOwnProperty(r)&&n(i[r]);i=e.fnMap;for(
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBlockConverter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>ifBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBlockConverter)
- description and source-code
```javascript
ifBlockConverter = function (e){e
.consequent=this.convertToBlock(e.consequent),e.alternate=this.convertToBlock(e.
alternate)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBranchInjector"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>ifBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.ifBranchInjector)
- description and source-code
```javascript
ifBranchInjector = function (e, t){var n=!!this.currentState.ignoring,r=
this.currentState.currentHint,i=!n&&r&&r.type==="if",s=!n&&r&&r.type==="else",o=
e.loc.start.line,u=e.loc.start.column,a=function(){return{line:o,column:u}},l=this
.branchName("if",t.startLineForNode(e),[{start:a(),end:a(),skip:i||undefined},{start
:a(),end:a(),skip:s||undefined}]),c=e.consequent.body,h=e.alternate.body,p;c.unshift
(f.statement(this.branchIncrementExprAst(l,0))),h.unshift(f.statement(this.branchIncrementExprAst
(l,1))),i&&(p=e.consequent,p.preprocessor=this.startIgnore,p.postprocessor=this.
endIgnore),s&&(p=e.alternate,p.preprocessor=this.startIgnore,p.postprocessor=this
.endIgnore)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.instrument"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrument (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrument)
- description and source-code
```javascript
instrument = function (e, t, n){!n&&typeof t=="function"&&(n=t,t=null);try{n(null,this.instrumentSync
(e,t))}catch(r){n(r)}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentASTSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrumentASTSync (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentASTSync)
- description and source-code
```javascript
instrumentASTSync = function (e, t, n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
.sourceMap=null,this.coverState={path:t,s:{},b:{},f:{},fnMap:{},statementMap:{},
branchMap:{}},this.currentState={trackerVar:p(t,this.omitTrackerSuffix),func:0,branch
:0,variable:0,statement:0,hints:this.filterHints(e.comments),currentHint:null,lastHintPosition
:-1,ignoring:0},e.body&&e.body.length>0&&this.isUseStrictExpression(e.body[0])&&
(e.body.shift(),r=!0),this.walker.startWalk(e),s=this.opts.codeGenerationOptions||
{format:{compact:!this.opts.noCompact}},s.comment=this.opts.preserveComments,o=i
.generate(e,s),u=this.getPreamble(n||"",r);if(o.map&&o.code){a=u.split(/\r\n|\r|\n/
).length;for(f=0;f<o.map._mappings._array.length;f+=1)o.map._mappings._array[f].
generatedLine+=a;this.sourceMap=o.map,o=o.code}return u+"\n"+o+"\n"}
```
- example usage
```shell
...
[this.path.length-e]:null},parent:function(){return this.ancestor(1)},isLabeled:
function(){var e=this.parent();return e&&e.node.type===t.LabeledStatement.name}}
,g.prototype={instrumentSync:function(e,n){var s;if(typeof e!="string")throw new
Error("Code must be string");return e.charAt(0)==="#"&&(e="//"+e),this.opts.noAutoWrap||
(e=o+e+u),s=r.parse(e,{loc:!0,range:!0,tokens:this.opts.preserveComments,comment
:!0}),this.opts.preserveComments&&(s=i.attachComments(s,s.comments,s.tokens)),this
.opts.noAutoWrap||(s={type:t.Program.name,body:s.body[0].expression.callee.body.
body,comments:s.comments}),this.instrumentASTSync(s,n,e)},filterHints:function(e
){var t=[],n,r,i;if(!e||!h(e))return t;for(n=0;n<e.length;n+=1)r=e[n],r&&r.value&&
r.range&&h(r.range)&&(i=String(r.value).match(a),i&&t.push({type:i[1],start:r.range
[0],end:r.range[1]}));return t},extractCurrentHint:function(e){if(!e.range)return;
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
this.currentState.currentHint=i,this.currentState.lastHintPosition=t,t+=1}},instrumentASTSync
:function(e,t,n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>instrumentSync (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.instrumentSync)
- description and source-code
```javascript
instrumentSync = function (e, n){var s;if(typeof e!="string")throw new
Error("Code must be string");return e.charAt(0)==="#"&&(e="//"+e),this.opts.noAutoWrap||
(e=o+e+u),s=r.parse(e,{loc:!0,range:!0,tokens:this.opts.preserveComments,comment
:!0}),this.opts.preserveComments&&(s=i.attachComments(s,s.comments,s.tokens)),this
.opts.noAutoWrap||(s={type:t.Program.name,body:s.body[0].expression.callee.body.
body,comments:s.comments}),this.instrumentASTSync(s,n,e)}
```
- example usage
```shell
...
    delete local.global.__coverage__['/inputTextareaEval1.js'];
} catch (ignore) {
}
// try to cover and eval input-code
try {
    /*jslint evil: true*/
    document.querySelector('#outputTextarea1').value =
        local.istanbul.instrumentSync(
            document.querySelector('#inputTextareaEval1').value,
            '/inputTextareaEval1.js'
        );
    eval(document.querySelector('#outputTextarea1').value);
    document.querySelector('#coverageReportDiv1').innerHTML =
        local.istanbul.coverageReportCreate({
            coverage: window.__coverage__
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.isUseStrictExpression"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>isUseStrictExpression (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.isUseStrictExpression)
- description and source-code
```javascript
isUseStrictExpression = function (e){return e&&e.type===
t.ExpressionStatement.name&&e.expression&&e.expression.type===t.Literal.name&&e.
expression.value==="use strict"}
```
- example usage
```shell
...
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
this.currentState.currentHint=i,this.currentState.lastHintPosition=t,t+=1}},instrumentASTSync
:function(e,t,n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
.sourceMap=null,this.coverState={path:t,s:{},b:{},f:{},fnMap:{},statementMap:{},
branchMap:{}},this.currentState={trackerVar:p(t,this.omitTrackerSuffix),func:0,branch
:0,variable:0,statement:0,hints:this.filterHints(e.comments),currentHint:null,lastHintPosition
:-1,ignoring:0},e.body&&e.body.length>0&&this.isUseStrictExpression(e.body[0])&&
(e.body.shift(),r=!0),this.walker.startWalk(e),s=this.opts.codeGenerationOptions||
{format:{compact:!this.opts.noCompact}},s.comment=this.opts.preserveComments,o=i
.generate(e,s),u=this.getPreamble(n||"",r);if(o.map&&o.code){a=u.split(/\r\n|\r|\n/
).length;for(f=0;f<o.map._mappings._array.length;f+=1)o.map._mappings._array[f].
generatedLine+=a;this.sourceMap=o.map,o=o.code}return u+"\n"+o+"\n"},instrument:
function(e,t,n){!n&&typeof t=="function"&&(n=t,t=null);try{n(null,this.instrumentSync
(e,t))}catch(r){n(r)}},lastFileCoverage:function(){return this.coverState},lastSourceMap
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.lastFileCoverage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>lastFileCoverage ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.lastFileCoverage)
- description and source-code
```javascript
lastFileCoverage = function (){return this.coverState}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.lastSourceMap"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>lastSourceMap ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.lastSourceMap)
- description and source-code
```javascript
lastSourceMap = function (){return this.sourceMap}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.locationsForNodes"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>locationsForNodes (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.locationsForNodes)
- description and source-code
```javascript
locationsForNodes = function (e){var t=[],n;for(n=0;n<e.length;n+=1)t.push(e[n].loc
);return t}
```
- example usage
```shell
...
.endIgnore)},branchLocationFor:function(e,t){return this.coverState.branchMap[e]
.locations[t]},switchBranchInjector:function(e,t){var n=e.cases,r,i;if(!(n&&n.length>0
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
(n));for(i=0;i<n.length;i+=1)n[i].branchLocation=this.branchLocationFor(r,i),n[i
].consequent.unshift(f.statement(this.branchIncrementExprAst(r,i)))},switchCaseInjector
:function(e){var t=e.branchLocation;delete e.branchLocation,this.maybeSkipNode(e
,"next")&&(t.skip=!0)},conditionalBranchInjector:function(e,t){var n=this.branchName
("cond-expr",t.startLineForNode(e),this.locationsForNodes([e.consequent,e.alternate
])),r=this.branchIncrementExprAst(n,0),i=this.branchIncrementExprAst(n,1);e.consequent
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
),e.alternate=f.sequence(i,e.alternate)},maybeAddSkip:function(e){return function(
t){var n=!!this.currentState.ignoring,r=this.currentState.currentHint,i=!n&&r&&r
.type==="next";i&&(this.startIgnore(),t.postprocessor=this.endIgnore);if(i||n)e.
skip=!0}},logicalExpressionBranchInjector:function(e,n){var r=n.parent(),i=[],s,
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>logicalExpressionBranchInjector (e, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector)
- description and source-code
```javascript
logicalExpressionBranchInjector = function (e, n){var r=n.parent(),i=[],s,
o,u;this.maybeSkipNode(e,"next");if(r&&r.node.type===t.LogicalExpression.name)return;
this.findLeaves(e,i),s=this.branchName("binary-expr",n.startLineForNode(e),this.
locationsForNodes(i.map(function(e){return e.node})));for(u=0;u<i.length;u+=1)o=
i[u],o.parent[o.property]=f.sequence(this.branchIncrementExprAst(s,u),o.node),o.
node.preprocessor=this.maybeAddSkip(this.branchLocationFor(s,u))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.loopBlockConverter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>loopBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.loopBlockConverter)
- description and source-code
```javascript
loopBlockConverter = function (e){e.body=this.convertToBlock(e.body)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddSkip"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeAddSkip (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddSkip)
- description and source-code
```javascript
maybeAddSkip = function (e){return function(
t){var n=!!this.currentState.ignoring,r=this.currentState.currentHint,i=!n&&r&&r
.type==="next";i&&(this.startIgnore(),t.postprocessor=this.endIgnore);if(i||n)e.
skip=!0}}
```
- example usage
```shell
...
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
(n));for(i=0;i<n.length;i+=1)n[i].branchLocation=this.branchLocationFor(r,i),n[i
].consequent.unshift(f.statement(this.branchIncrementExprAst(r,i)))},switchCaseInjector
:function(e){var t=e.branchLocation;delete e.branchLocation,this.maybeSkipNode(e
,"next")&&(t.skip=!0)},conditionalBranchInjector:function(e,t){var n=this.branchName
("cond-expr",t.startLineForNode(e),this.locationsForNodes([e.consequent,e.alternate
])),r=this.branchIncrementExprAst(n,0),i=this.branchIncrementExprAst(n,1);e.consequent
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
),e.alternate=f.sequence(i,e.alternate)},maybeAddSkip:function(e){return function(
t){var n=!!this.currentState.ignoring,r=this.currentState.currentHint,i=!n&&r&&r
.type==="next";i&&(this.startIgnore(),t.postprocessor=this.endIgnore);if(i||n)e.
skip=!0}},logicalExpressionBranchInjector:function(e,n){var r=n.parent(),i=[],s,
o,u;this.maybeSkipNode(e,"next");if(r&&r.node.type===t.LogicalExpression.name)return;
this.findLeaves(e,i),s=this.branchName("binary-expr",n.startLineForNode(e),this.
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddType"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeAddType (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeAddType)
- description and source-code
```javascript
maybeAddType = function (e){var n=e.properties,r,i;for(r=0;r<n.length;r+=1)i=n[r],i.type||(i.type=
t.Property.name)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeSkipNode"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>maybeSkipNode (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.maybeSkipNode)
- description and source-code
```javascript
maybeSkipNode = function (e, t){var n=!!this.currentState
.ignoring,r=this.currentState.currentHint,i=!n&&r&&r.type===t;return i?(this.startIgnore
(),e.postprocessor=this.endIgnore,!0):!1}
```
- example usage
```shell
...
.statement+=1,n=this.currentState.statement,this.coverState.statementMap[n]=e,this
.coverState.s[n]=t,n},skipInit:function(e){e.init&&(e.init.skipWalk=!0)},skipLeft
:function(e){e.left.skipWalk=!0},isUseStrictExpression:function(e){return e&&e.type===
t.ExpressionStatement.name&&e.expression&&e.expression.type===t.Literal.name&&e.
expression.value==="use strict"},maybeSkipNode:function(e,t){var n=!!this.currentState
.ignoring,r=this.currentState.currentHint,i=!n&&r&&r.type===t;return i?(this.startIgnore
(),e.postprocessor=this.endIgnore,!0):!1},coverStatement:function(e,n){var r,i,s
;this.maybeSkipNode(e,"next");if(this.isUseStrictExpression(e)){s=n.ancestor(2);
if(s&&(s.node.type===t.FunctionExpression.name||s.node.type===t.FunctionDeclaration
.name)&&n.parent().node.body[0]===e)return}e.type===t.FunctionDeclaration.name?r=
this.statementName(e.loc,1):(r=this.statementName(e.loc),i=f.statement(f.postIncrement
(f.subscript(f.dot(f.variable(this.currentState.trackerVar),f.variable("s")),f.stringLiteral
(r)))),this.splice(i,e,n))},splice:function(e,t,n){var r=n.isLabeled()?n.parent(
).node:t;r.prepend=r.prepend||[],d(r.prepend,e)},functionName:function(e,t,n){this
.currentState.func+=1;var r=this.currentState.func,i=!!this.currentState.ignoring
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.paranoidHandlerCheck"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>paranoidHandlerCheck (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.paranoidHandlerCheck)
- description and source-code
```javascript
paranoidHandlerCheck = function (e){!
e.handler&&e.handlers&&(e.handler=e.handlers[0])}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.skipInit"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>skipInit (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.skipInit)
- description and source-code
```javascript
skipInit = function (e){e.init&&(e.init.skipWalk=!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.skipLeft"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>skipLeft (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.skipLeft)
- description and source-code
```javascript
skipLeft = function (e){e.left.skipWalk=!0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.splice"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>splice (e, t, n)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.splice)
- description and source-code
```javascript
splice = function (e, t, n){var r=n.isLabeled()?n.parent(
).node:t;r.prepend=r.prepend||[],d(r.prepend,e)}
```
- example usage
```shell
...
,InvalidModuleSpecifier:"Unexpected token",IllegalImportDeclaration:"Unexpected token"
,IllegalExportDeclaration:"Unexpected token",DuplicateBinding:"Duplicate binding %0"
},u={NonAsciiIdentifierStart:/[\xAA\xB5\xBA\xC0-\xD6\xD8-\xF6\xF8-\u02C1\u02C6-\u02D1\u02E0-\u02E4\u02EC\u02EE\u0370-\u0374\u0376\u0377\u037A-\u037D\u037F\u0386\u0388-\u038A\u038C\u038E-\u03A1\u03A3-\u03F5\u03F7-\u0481\u048A-\u052F\u0531-\u0556\u0559\u0561-\u0587\u05D0-\u05EA\u05F0-\u05F2\u0620-\u064A\u066E\u066F\u0671-\u06D3\u06D5\u06E5\u06E6\u06EE\u06EF\u06FA-\u06FC\u06FF\u0710\u0712-\u072F\u074D-\u07A5\u07B1\u07CA-\u07EA\u07F4\u07F5\u07FA\u0800-\u0815\u081A\u0824\u0828\u0840-\u0858\u08A0-\u08B2\u0904-\u0939\u093D\u0950\u0958-\u0961\u0971-\u0980\u0985-\u098C\u098F\u0990\u0993-\u09A8\u09AA-\u09B0\u09B2\u09B6-\u09B9\u09BD\u09CE\u09DC\u09DD\u09DF-\u09E1\u09F0\u09F1\u0A05-\u0A0A\u0A0F\u0A10\u0A13-\u0A28\u0A2A-\u0A30\u0A32\u0A33\u0A35\u0A36\u0A38\u0A39\u0A59-\u0A5C\u0A5E\u0A72-\u0A74\u0A85-\u0A8D\u0A8F-\u0A91\u0A93-\u0AA8\u0AAA-\u0AB0\u0AB2\u0AB3\u0AB5-\u0AB9\u0ABD\u0AD0\u0AE0\u0AE1\u0B05-\u0B0C\u0B0F\u0B10\u0B13-\u0B28\u0B2A-\u0B30\u0B32\u0B33\u0B35-\u0B39\u0B3D\u0B5C\u0B5D\u0B5F-\u0B61\u0B71\u0B83\u0B85-\u0B8A\u0B8E-\u0B90\u0B92-\u0B95\u0B99\u0B9A\u0B9C\u0B9E\u0B9F\u0BA3\u0BA4\u0BA8-\u0BAA\u0BAE-\u0BB9\u0BD0\u0C05-\u0C0C\u0C0E-\u0C10\u0C12-\u0C28\u0C2A-\u0C39\u0C3D\u0C58\u0C59\u0C60\u0C61\u0C85-\u0C8C\u0C8E-\u0C90\u0C92-\u0CA8\u0CAA-\u0CB3\u0CB5-\u0CB9\u0CBD\u0CDE\u0CE0\u0CE1\u0CF1\u0CF2\u0D05-\u0D0C\u0D0E-\u0D10\u0D12-\u0D3A\u0D3D\u0D4E\u0D60\u0D61\u0D7A-\u0D7F\u0D85-\u0D96\u0D9A-\u0DB1\u0DB3-\u0DBB\u0DBD\u0DC0-\u0DC6\u0E01-\u0E30\u0E32\u0E33\u0E40-\u0E46\u0E81\u0E82\u0E84\u0E87\u0E88\u0E8A\u0E8D\u0E94-\u0E97\u0E99-\u0E9F\u0EA1-\u0EA3\u0EA5\u0EA7\u0EAA\u0EAB\u0EAD-\u0EB0\u0EB2\u0EB3\u0EBD\u0EC0-\u0EC4\u0EC6\u0EDC-\u0EDF\u0F00\u0F40-\u0F47\u0F49-\u0F6C\u0F88-\u0F8C\u1000-\u102A\u103F\u1050-\u1055\u105A-\u105D\u1061\u1065\u1066\u106E-\u1070\u1075-\u1081\u108E\u10A0-\u10C5\u10C7\u10CD\u10D0-\u10FA\u10FC-\u1248\u124A-\u124D\u1250-\u1256\u1258\u125A-\u125D\u1260-\u1288\u128A-\u128D\u1290-\u12B0\u12B2-\u12B5\u12B8-\u12BE\u12C0\u12C2-\u12C5\u12C8-\u12D6\u12D8-\u1310\u1312-\u1315\u1318-\u135A\u1380-\u138F\u13A0-\u13F4\u1401-\u166C\u166F-\u167F\u1681-\u169A\u16A0-\u16EA\u16EE-\u16F8\u1700-\u170C\u170E-\u1711\u1720-\u1731\u1740-\u1751\u1760-\u176C\u176E-\u1770\u1780-\u17B3\u17D7\u17DC\u1820-\u1877\u1880-\u18A8\u18AA\u18B0-\u18F5\u1900-\u191E\u1950-\u196D\u1970-\u1974\u1980-\u19AB\u19C1-\u19C7\u1A00-\u1A16\u1A20-\u1A54\u1AA7\u1B05-\u1B33\u1B45-\u1B4B\u1B83-\u1BA0\u1BAE\u1BAF\u1BBA-\u1BE5\u1C00-\u1C23\u1C4D-\u1C4F\u1C5A-\u1C7D\u1CE9-\u1CEC\u1CEE-\u1CF1\u1CF5\u1CF6\u1D00-\u1DBF\u1E00-\u1F15\u1F18-\u1F1D\u1F20-\u1F45\u1F48-\u1F4D\u1F50-\u1F57\u1F59\u1F5B\u1F5D\u1F5F-\u1F7D\u1F80-\u1FB4\u1FB6-\u1FBC\u1FBE\u1FC2-\u1FC4\u1FC6-\u1FCC\u1FD0-\u1FD3\u1FD6-\u1FDB\u1FE0-\u1FEC\u1FF2-\u1FF4\u1FF6-\u1FFC\u2071\u207F\u2090-\u209C\u2102\u2107\u210A-\u2113\u2115\u2118-\u211D\u2124\u2126\u2128\u212A-\u2139\u213C-\u213F\u2145-\u2149\u214E\u2160-\u2188\u2C00-\u2C2E\u2C30-\u2C5E\u2C60-\u2CE4\u2CEB-\u2CEE\u2CF2\u2CF3\u2D00-\u2D25\u2D27\u2D2D\u2D30-\u2D67\u2D6F\u2D80-\u2D96\u2DA0-\u2DA6\u2DA8-\u2DAE\u2DB0-\u2DB6\u2DB8-\u2DBE\u2DC0-\u2DC6\u2DC8-\u2DCE\u2DD0-\u2DD6\u2DD8-\u2DDE\u3005-\u3007\u3021-\u3029\u3031-\u3035\u3038-\u303C\u3041-\u3096\u309B-\u309F\u30A1-\u30FA\u30FC-\u30FF\u3105-\u312D\u3131-\u318E\u31A0-\u31BA\u31F0-\u31FF\u3400-\u4DB5\u4E00-\u9FCC\uA000-\uA48C\uA4D0-\uA4FD\uA500-\uA60C\uA610-\uA61F\uA62A\uA62B\uA640-\uA66E\uA67F-\uA69D\uA6A0-\uA6EF\uA717-\uA71F\uA722-\uA788\uA78B-\uA78E\uA790-\uA7AD\uA7B0\uA7B1\uA7F7-\uA801\uA803-\uA805\uA807-\uA80A\uA80C-\uA822\uA840-\uA873\uA882-\uA8B3\uA8F2-\uA8F7\uA8FB\uA90A-\uA925\uA930-\uA946\uA960-\uA97C\uA984-\uA9B2\uA9CF\uA9E0-\uA9E4\uA9E6-\uA9EF\uA9FA-\uA9FE\uAA00-\uAA28\uAA40-\uAA42\uAA44-\uAA4B\uAA60-\uAA76\uAA7A\uAA7E-\uAAAF\uAAB1\uAAB5\uAAB6\uAAB9-\uAABD\uAAC0\uAAC2\uAADB-\uAADD\uAAE0-\uAAEA\uAAF2-\uAAF4\uAB01-\uAB06\uAB09-\uAB0E\uAB11-\uAB16\uAB20-\uAB26\uAB28-\uAB2E\uAB30-\uAB5A\uAB5C-\uAB5F\uAB64\uAB65\uABC0-\uABE2\uAC00-\uD7A3\uD7B0-\uD7C6\uD7CB-\uD7FB\uF900-\uFA6D\uFA70-\uFAD9\uFB00-\uFB06\uFB13-\uFB17\uFB1D\uFB1F-\uFB28\uFB2A-\uFB36\uFB38-\uFB3C\uFB3E\uFB40\uFB41\uFB43\uFB44\uFB46-\uFBB1\uFBD3-\uFD3D\uFD50-\uFD8F\uFD92-\uFDC7\uFDF0-\uFDFB\uFE70-\uFE74\uFE76-\uFEFC\uFF21-\uFF3A\uFF41-\uFF5A\uFF66-\uFFBE\uFFC2-\uFFC7\uFFCA-\uFFCF\uFFD2-\uFFD7\uFFDA-\uFFDC]|\uD800[\uDC00-\uDC0B\uDC0D-\uDC26\uDC28-\uDC3A\uDC3C\uDC3D\uDC3F-\uDC4D\uDC50-\uDC5D\uDC80-\uDCFA\uDD40-\uDD74\uDE80-\uDE9C\uDEA0-\uDED0\uDF00-\uDF1F\uDF30-\uDF4A\uDF50-\uDF75\uDF80-\uDF9D\uDFA0-\uDFC3\uDFC8-\uDFCF\uDFD1-\uDFD5]|\uD801[\uDC00-\uDC9D\uDD00-\uDD27\uDD30-\uDD63\uDE00-\uDF36\uDF40-\uDF55\uDF60-\uDF67]|\uD802[\uDC00-\uDC05\uDC08\uDC0A-\uDC35\uDC37\uDC38\uDC3C\uDC3F-\uDC55\uDC60-\uDC76\uDC80-\uDC9E\uDD00-\uDD15\uDD20-\uDD39\uDD80-\uDDB7\uDDBE\uDDBF\uDE00\uDE10-\uDE13\uDE15-\uDE17\uDE19-\uDE33\uDE60-\uDE7C\uDE80-\uDE9C\uDEC0-\uDEC7\uDEC9-\uDEE4\uDF00-\uDF35\uDF40-\uDF55\uDF60-\uDF72\uDF80-\uDF91]|\uD803[\uDC00-\uDC48]|\uD804[\uDC03-\uDC37\uDC83-\uDCAF\uDCD0-\uDCE8\uDD03-\uDD26\uDD50-\uDD72\uDD76\uDD83-\uDDB2\uDDC1-\uDDC4\uDDDA\uDE00-\uDE11\uDE13-\uDE2B\uDEB0-\uDEDE\uDF05-\uDF0C\uDF0F\uDF10\uDF13-\uDF28\uDF2A-\uDF30\uDF32\uDF33\uDF35-\uDF39\uDF3D\uDF5D-\uDF61]|\uD805[\uDC80-\uDCAF\uDCC4\uDCC5\uDCC7\uDD80-\uDDAE\uDE00-\uDE2F\uDE44\uDE80-\uDEAA]|\uD806[\uDCA0-\uDCDF\uDCFF\uDEC0-\uDEF8]|\uD808[\uDC00-\uDF98]|\uD809[\uDC00-\uDC6E]|[\uD80C\uD840-\uD868\uD86A-\uD86C][\uDC00-\uDFFF]|\uD80D[\uDC00-\uDC2E]|\uD81A[\uDC00-\uDE38\uDE40-\uDE5E\uDED0-\uDEED\uDF00-\uDF2F\uDF40-\uDF43\uDF63-\uDF77\uDF7D-\uDF8F]|\uD81B[\uDF00-\uDF44\uDF50\uDF93-\uDF9F]|\uD82C[\uDC00\uDC01]|\uD82F[\uDC00-\uDC6A\uDC70-\uDC7C\uDC80-\uDC88\uDC90-\uDC99]|\uD835[\uDC00-\uDC54\uDC56-\uDC9C\uDC9E\uDC9F\uDCA2\uDCA5\uDCA6\uDCA9-\uDCAC\uDCAE-\uDCB9\uDCBB\uDCBD-\uDCC3\uDCC5-\uDD05\uDD07-\uDD0A\uDD0D-\uDD14\uDD16-\uDD1C\uDD1E-\uDD39\uDD3B-\uDD3E\uDD40-\uDD44\uDD46\uDD4A-\uDD50\uDD52-\uDEA5\uDEA8-\uDEC0\uDEC2-\uDEDA\uDEDC-\uDEFA\uDEFC-\uDF14\uDF16-\uDF34\uDF36-\uDF4E\uDF50-\uDF6E\uDF70-\uDF88\uDF8A-\uDFA8\uDFAA-\uDFC2\uDFC4-\uDFCB]|\uD83A[\uDC00-\uDCC4]|\uD83B[\uDE00-\uDE03\uDE05-\uDE1F\uDE21\uDE22\uDE24\uDE27\uDE29-\uDE32\uDE34-\uDE37\uDE39\uDE3B\uDE42\uDE47\uDE49\uDE4B\uDE4D-\uDE4F\uDE51\uDE52\uDE54\uDE57\uDE59\uDE5B\uDE5D\uDE5F\uDE61\uDE62\uDE64\uDE67-\uDE6A\uDE6C-\uDE72\uDE74-\uDE77\uDE79-\uDE7C\uDE7E\uDE80-\uDE89\uDE8B-\uDE9B\uDEA1-\uDEA3\uDEA5-\uDEA9\uDEAB-\uDEBB]|\uD869[\uDC00-\uDED6\uDF00-\uDFFF]|\uD86D[\uDC00-\uDF34\uDF40-\uDFFF]|\uD86E[\uDC00-\uDC1D]|\uD87E[\uDC00-\uDE1D]/
,NonAsciiIdentifierPart:/[\xAA\xB5\xB7\xBA\xC0-\xD6\xD8-\xF6\xF8-\u02C1\u02C6-\u02D1\u02E0-\u02E4\u02EC\u02EE\u0300-\u0374\u0376\u0377\u037A-\u037D\u037F\u0386-\u038A\u038C\u038E-\u03A1\u03A3-\u03F5\u03F7-\u0481\u0483-\u0487\u048A-\u052F\u0531-\u0556\u0559\u0561-\u0587\u0591-\u05BD\u05BF\u05C1\u05C2\u05C4\u05C5\u05C7\u05D0-\u05EA\u05F0-\u05F2\u0610-\u061A\u0620-\u0669\u066E-\u06D3\u06D5-\u06DC\u06DF-\u06E8\u06EA-\u06FC\u06FF\u0710-\u074A\u074D-\u07B1\u07C0-\u07F5\u07FA\u0800-\u082D\u0840-\u085B\u08A0-\u08B2\u08E4-\u0963\u0966-\u096F\u0971-\u0983\u0985-\u098C\u098F\u0990\u0993-\u09A8\u09AA-\u09B0\u09B2\u09B6-\u09B9\u09BC-\u09C4\u09C7\u09C8\u09CB-\u09CE\u09D7\u09DC\u09DD\u09DF-\u09E3\u09E6-\u09F1\u0A01-\u0A03\u0A05-\u0A0A\u0A0F\u0A10\u0A13-\u0A28\u0A2A-\u0A30\u0A32\u0A33\u0A35\u0A36\u0A38\u0A39\u0A3C\u0A3E-\u0A42\u0A47\u0A48\u0A4B-\u0A4D\u0A51\u0A59-\u0A5C\u0A5E\u0A66-\u0A75\u0A81-\u0A83\u0A85-\u0A8D\u0A8F-\u0A91\u0A93-\u0AA8\u0AAA-\u0AB0\u0AB2\u0AB3\u0AB5-\u0AB9\u0ABC-\u0AC5\u0AC7-\u0AC9\u0ACB-\u0ACD\u0AD0\u0AE0-\u0AE3\u0AE6-\u0AEF\u0B01-\u0B03\u0B05-\u0B0C\u0B0F\u0B10\u0B13-\u0B28\u0B2A-\u0B30\u0B32\u0B33\u0B35-\u0B39\u0B3C-\u0B44\u0B47\u0B48\u0B4B-\u0B4D\u0B56\u0B57\u0B5C\u0B5D\u0B5F-\u0B63\u0B66-\u0B6F\u0B71\u0B82\u0B83\u0B85-\u0B8A\u0B8E-\u0B90\u0B92-\u0B95\u0B99\u0B9A\u0B9C\u0B9E\u0B9F\u0BA3\u0BA4\u0BA8-\u0BAA\u0BAE-\u0BB9\u0BBE-\u0BC2\u0BC6-\u0BC8\u0BCA-\u0BCD\u0BD0\u0BD7\u0BE6-\u0BEF\u0C00-\u0C03\u0C05-\u0C0C\u0C0E-\u0C10\u0C12-\u0C28\u0C2A-\u0C39\u0C3D-\u0C44\u0C46-\u0C48\u0C4A-\u0C4D\u0C55\u0C56\u0C58\u0C59\u0C60-\u0C63\u0C66-\u0C6F\u0C81-\u0C83\u0C85-\u0C8C\u0C8E-\u0C90\u0C92-\u0CA8\u0CAA-\u0CB3\u0CB5-\u0CB9\u0CBC-\u0CC4\u0CC6-\u0CC8\u0CCA-\u0CCD\u0CD5\u0CD6\u0CDE\u0CE0-\u0CE3\u0CE6-\u0CEF\u0CF1\u0CF2\u0D01-\u0D03\u0D05-\u0D0C\u0D0E-\u0D10\u0D12-\u0D3A\u0D3D-\u0D44\u0D46-\u0D48\u0D4A-\u0D4E\u0D57\u0D60-\u0D63\u0D66-\u0D6F\u0D7A-\u0D7F\u0D82\u0D83\u0D85-\u0D96\u0D9A-\u0DB1\u0DB3-\u0DBB\u0DBD\u0DC0-\u0DC6\u0DCA\u0DCF-\u0DD4\u0DD6\u0DD8-\u0DDF\u0DE6-\u0DEF\u0DF2\u0DF3\u0E01-\u0E3A\u0E40-\u0E4E\u0E50-\u0E59\u0E81\u0E82\u0E84\u0E87\u0E88\u0E8A\u0E8D\u0E94-\u0E97\u0E99-\u0E9F\u0EA1-\u0EA3\u0EA5\u0EA7\u0EAA\u0EAB\u0EAD-\u0EB9\u0EBB-\u0EBD\u0EC0-\u0EC4\u0EC6\u0EC8-\u0ECD\u0ED0-\u0ED9\u0EDC-\u0EDF\u0F00\u0F18\u0F19\u0F20-\u0F29\u0F35\u0F37\u0F39\u0F3E-\u0F47\u0F49-\u0F6C\u0F71-\u0F84\u0F86-\u0F97\u0F99-\u0FBC\u0FC6\u1000-\u1049\u1050-\u109D\u10A0-\u10C5\u10C7\u10CD\u10D0-\u10FA\u10FC-\u1248\u124A-\u124D\u1250-\u1256\u1258\u125A-\u125D\u1260-\u1288\u128A-\u128D\u1290-\u12B0\u12B2-\u12B5\u12B8-\u12BE\u12C0\u12C2-\u12C5\u12C8-\u12D6\u12D8-\u1310\u1312-\u1315\u1318-\u135A\u135D-\u135F\u1369-\u1371\u1380-\u138F\u13A0-\u13F4\u1401-\u166C\u166F-\u167F\u1681-\u169A\u16A0-\u16EA\u16EE-\u16F8\u1700-\u170C\u170E-\u1714\u1720-\u1734\u1740-\u1753\u1760-\u176C\u176E-\u1770\u1772\u1773\u1780-\u17D3\u17D7\u17DC\u17DD\u17E0-\u17E9\u180B-\u180D\u1810-\u1819\u1820-\u1877\u1880-\u18AA\u18B0-\u18F5\u1900-\u191E\u1920-\u192B\u1930-\u193B\u1946-\u196D\u1970-\u1974\u1980-\u19AB\u19B0-\u19C9\u19D0-\u19DA\u1A00-\u1A1B\u1A20-\u1A5E\u1A60-\u1A7C\u1A7F-\u1A89\u1A90-\u1A99\u1AA7\u1AB0-\u1ABD\u1B00-\u1B4B\u1B50-\u1B59\u1B6B-\u1B73\u1B80-\u1BF3\u1C00-\u1C37\u1C40-\u1C49\u1C4D-\u1C7D\u1CD0-\u1CD2\u1CD4-\u1CF6\u1CF8\u1CF9\u1D00-\u1DF5\u1DFC-\u1F15\u1F18-\u1F1D\u1F20-\u1F45\u1F48-\u1F4D\u1F50-\u1F57\u1F59\u1F5B\u1F5D\u1F5F-\u1F7D\u1F80-\u1FB4\u1FB6-\u1FBC\u1FBE\u1FC2-\u1FC4\u1FC6-\u1FCC\u1FD0-\u1FD3\u1FD6-\u1FDB\u1FE0-\u1FEC\u1FF2-\u1FF4\u1FF6-\u1FFC\u200C\u200D\u203F\u2040\u2054\u2071\u207F\u2090-\u209C\u20D0-\u20DC\u20E1\u20E5-\u20F0\u2102\u2107\u210A-\u2113\u2115\u2118-\u211D\u2124\u2126\u2128\u212A-\u2139\u213C-\u213F\u2145-\u2149\u214E\u2160-\u2188\u2C00-\u2C2E\u2C30-\u2C5E\u2C60-\u2CE4\u2CEB-\u2CF3\u2D00-\u2D25\u2D27\u2D2D\u2D30-\u2D67\u2D6F\u2D7F-\u2D96\u2DA0-\u2DA6\u2DA8-\u2DAE\u2DB0-\u2DB6\u2DB8-\u2DBE\u2DC0-\u2DC6\u2DC8-\u2DCE\u2DD0-\u2DD6\u2DD8-\u2DDE\u2DE0-\u2DFF\u3005-\u3007\u3021-\u302F\u3031-\u3035\u3038-\u303C\u3041-\u3096\u3099-\u309F\u30A1-\u30FA\u30FC-\u30FF\u3105-\u312D\u3131-\u318E\u31A0-\u31BA\u31F0-\u31FF\u3400-\u4DB5\u4E00-\u9FCC\uA000-\uA48C\uA4D0-\uA4FD\uA500-\uA60C\uA610-\uA62B\uA640-\uA66F\uA674-\uA67D\uA67F-\uA69D\uA69F-\uA6F1\uA717-\uA71F\uA722-\uA788\uA78B-\uA78E\uA790-\uA7AD\uA7B0\uA7B1\uA7F7-\uA827\uA840-\uA873\uA880-\uA8C4\uA8D0-\uA8D9\uA8E0-\uA8F7\uA8FB\uA900-\uA92D\uA930-\uA953\uA960-\uA97C\uA980-\uA9C0\uA9CF-\uA9D9\uA9E0-\uA9FE\uAA00-\uAA36\uAA40-\uAA4D\uAA50-\uAA59\uAA60-\uAA76\uAA7A-\uAAC2\uAADB-\uAADD\uAAE0-\uAAEF\uAAF2-\uAAF6\uAB01-\uAB06\uAB09-\uAB0E\uAB11-\uAB16\uAB20-\uAB26\uAB28-\uAB2E\uAB30-\uAB5A\uAB5C-\uAB5F\uAB64\uAB65\uABC0-\uABEA\uABEC\uABED\uABF0-\uABF9\uAC00-\uD7A3\uD7B0-\uD7C6\uD7CB-\uD7FB\uF900-\uFA6D\uFA70-\uFAD9\uFB00-\uFB06\uFB13-\uFB17\uFB1D-\uFB28\uFB2A-\uFB36\uFB38-\uFB3C\uFB3E\uFB40\uFB41\uFB43\uFB44\uFB46-\uFBB1\uFBD3-\uFD3D\uFD50-\uFD8F\uFD92-\uFDC7\uFDF0-\uFDFB\uFE00-\uFE0F\uFE20-\uFE2D\uFE33\uFE34\uFE4D-\uFE4F\uFE70-\uFE74\uFE76-\uFEFC\uFF10-\uFF19\uFF21-\uFF3A\uFF3F\uFF41-\uFF5A\uFF66-\uFFBE\uFFC2-\uFFC7\uFFCA-\uFFCF\uFFD2-\uFFD7\uFFDA-\uFFDC]|\uD800[\uDC00-\uDC0B\uDC0D-\uDC26\uDC28-\uDC3A\uDC3C\uDC3D\uDC3F-\uDC4D\uDC50-\uDC5D\uDC80-\uDCFA\uDD40-\uDD74\uDDFD\uDE80-\uDE9C\uDEA0-\uDED0\uDEE0\uDF00-\uDF1F\uDF30-\uDF4A\uDF50-\uDF7A\uDF80-\uDF9D\uDFA0-\uDFC3\uDFC8-\uDFCF\uDFD1-\uDFD5]|\uD801[\uDC00-\uDC9D\uDCA0-\uDCA9\uDD00-\uDD27\uDD30-\uDD63\uDE00-\uDF36\uDF40-\uDF55\uDF60-\uDF67]|\uD802[\uDC00-\uDC05\uDC08\uDC0A-\uDC35\uDC37\uDC38\uDC3C\uDC3F-\uDC55\uDC60-\uDC76\uDC80-\uDC9E\uDD00-\uDD15\uDD20-\uDD39\uDD80-\uDDB7\uDDBE\uDDBF\uDE00-\uDE03\uDE05\uDE06\uDE0C-\uDE13\uDE15-\uDE17\uDE19-\uDE33\uDE38-\uDE3A\uDE3F\uDE60-\uDE7C\uDE80-\uDE9C\uDEC0-\uDEC7\uDEC9-\uDEE6\uDF00-\uDF35\uDF40-\uDF55\uDF60-\uDF72\uDF80-\uDF91]|\uD803[\uDC00-\uDC48]|\uD804[\uDC00-\uDC46\uDC66-\uDC6F\uDC7F-\uDCBA\uDCD0-\uDCE8\uDCF0-\uDCF9\uDD00-\uDD34\uDD36-\uDD3F\uDD50-\uDD73\uDD76\uDD80-\uDDC4\uDDD0-\uDDDA\uDE00-\uDE11\uDE13-\uDE37\uDEB0-\uDEEA\uDEF0-\uDEF9\uDF01-\uDF03\uDF05-\uDF0C\uDF0F\uDF10\uDF13-\uDF28\uDF2A-\uDF30\uDF32\uDF33\uDF35-\uDF39\uDF3C-\uDF44\uDF47\uDF48\uDF4B-\uDF4D\uDF57\uDF5D-\uDF63\uDF66-\uDF6C\uDF70-\uDF74]|\uD805[\uDC80-\uDCC5\uDCC7\uDCD0-\uDCD9\uDD80-\uDDB5\uDDB8-\uDDC0\uDE00-\uDE40\uDE44\uDE50-\uDE59\uDE80-\uDEB7\uDEC0-\uDEC9]|\uD806[\uDCA0-\uDCE9\uDCFF\uDEC0-\uDEF8]|\uD808[\uDC00-\uDF98]|\uD809[\uDC00-\uDC6E]|[\uD80C\uD840-\uD868\uD86A-\uD86C][\uDC00-\uDFFF]|\uD80D[\uDC00-\uDC2E]|\uD81A[\uDC00-\uDE38\uDE40-\uDE5E\uDE60-\uDE69\uDED0-\uDEED\uDEF0-\uDEF4\uDF00-\uDF36\uDF40-\uDF43\uDF50-\uDF59\uDF63-\uDF77\uDF7D-\uDF8F]|\uD81B[\uDF00-\uDF44\uDF50-\uDF7E\uDF8F-\uDF9F]|\uD82C[\uDC00\uDC01]|\uD82F[\uDC00-\uDC6A\uDC70-\uDC7C\uDC80-\uDC88\uDC90-\uDC99\uDC9D\uDC9E]|\uD834[\uDD65-\uDD69\uDD6D-\uDD72\uDD7B-\uDD82\uDD85-\uDD8B\uDDAA-\uDDAD\uDE42-\uDE44]|\uD835[\uDC00-\uDC54\uDC56-\uDC9C\uDC9E\uDC9F\uDCA2\uDCA5\uDCA6\uDCA9-\uDCAC\uDCAE-\uDCB9\uDCBB\uDCBD-\uDCC3\uDCC5-\uDD05\uDD07-\uDD0A\uDD0D-\uDD14\uDD16-\uDD1C\uDD1E-\uDD39\uDD3B-\uDD3E\uDD40-\uDD44\uDD46\uDD4A-\uDD50\uDD52-\uDEA5\uDEA8-\uDEC0\uDEC2-\uDEDA\uDEDC-\uDEFA\uDEFC-\uDF14\uDF16-\uDF34\uDF36-\uDF4E\uDF50-\uDF6E\uDF70-\uDF88\uDF8A-\uDFA8\uDFAA-\uDFC2\uDFC4-\uDFCB\uDFCE-\uDFFF]|\uD83A[\uDC00-\uDCC4\uDCD0-\uDCD6]|\uD83B[\uDE00-\uDE03\uDE05-\uDE1F\uDE21\uDE22\uDE24\uDE27\uDE29-\uDE32\uDE34-\uDE37\uDE39\uDE3B\uDE42\uDE47\uDE49\uDE4B\uDE4D-\uDE4F\uDE51\uDE52\uDE54\uDE57\uDE59\uDE5B\uDE5D\uDE5F\uDE61\uDE62\uDE64\uDE67-\uDE6A\uDE6C-\uDE72\uDE74-\uDE77\uDE79-\uDE7C\uDE7E\uDE80-\uDE89\uDE8B-\uDE9B\uDEA1-\uDEA3\uDEA5-\uDEA9\uDEAB-\uDEBB]|\uD869[\uDC00-\uDED6\uDF00-\uDFFF]|\uD86D[\uDC00-\uDF34\uDF40-\uDFFF]|\uD86E[\uDC00-\uDC1D]|\uD87E[\uDC00-\uDE1D]|\uDB40[\uDD00-\uDDEF]/
},St.prototype=Et.prototype={processComment:function(){var e,t,n,r=N.bottomRightStack
,s,o,u=r[r.length-1];if(this.type===i.Program&&this.body.length>0)return;if(N.trailingComments
.length>0){n=[];for(s=N.trailingComments.length-1;s>=0;--s)o=N.trailingComments[
s],o.range[0]>=this.range[1]&&(n.unshift(o),N.trailingComments.splice(s,1));N.trailingComments=
[]}else u&&u.trailingComments&&u.trailingComments[0].range[0]>=this.range[1]&&(n=
u.trailingComments,delete u.trailingComments);while(u&&u.range[0]>=this.range[0]
)e=r.pop(),u=r[r.length-1];if(e){if(e.leadingComments){t=[];for(s=e.leadingComments
.length-1;s>=0;--s)o=e.leadingComments[s],o.range[1]<=this.range[0]&&(t.unshift(
o),e.leadingComments.splice(s,1));e.leadingComments.length||(e.leadingComments=undefined
)}}else if(N.leadingComments.length>0){t=[];for(s=N.leadingComments.length-1;s>=0
;--s)o=N.leadingComments[s],o.range[1]<=this.range[0]&&(t.unshift(o),N.leadingComments
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.startIgnore"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>startIgnore ()](#apidoc.element.utility2.istanbul.Instrumenter.prototype.startIgnore)
- description and source-code
```javascript
startIgnore = function (){this.currentState.ignoring+=1}
```
- example usage
```shell
...
,"next")&&(t.skip=!0)},conditionalBranchInjector:function(e,t){var n=this.branchName
("cond-expr",t.startLineForNode(e),this.locationsForNodes([e.consequent,e.alternate
])),r=this.branchIncrementExprAst(n,0),i=this.branchIncrementExprAst(n,1);e.consequent
.preprocessor=this.maybeAddSkip(this.branchLocationFor(n,0)),e.alternate.preprocessor=
this.maybeAddSkip(this.branchLocationFor(n,1)),e.consequent=f.sequence(r,e.consequent
),e.alternate=f.sequence(i,e.alternate)},maybeAddSkip:function(e){return function(
t){var n=!!this.currentState.ignoring,r=this.currentState.currentHint,i=!n&&r&&r
.type==="next";i&&(this.startIgnore(),t.postprocessor=this.endIgnore);if(i||n)e.
skip=!0}},logicalExpressionBranchInjector:function(e,n){var r=n.parent(),i=[],s,
o,u;this.maybeSkipNode(e,"next");if(r&&r.node.type===t.LogicalExpression.name)return;
this.findLeaves(e,i),s=this.branchName("binary-expr",n.startLineForNode(e),this.
locationsForNodes(i.map(function(e){return e.node})));for(u=0;u<i.length;u+=1)o=
i[u],o.parent[o.property]=f.sequence(this.branchIncrementExprAst(s,u),o.node),o.
node.preprocessor=this.maybeAddSkip(this.branchLocationFor(s,u))},findLeaves:function(
e,n,r,i){e.type===t.LogicalExpression.name?(this.findLeaves(e.left,n,e,"left"),this
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.statementName"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>statementName (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.statementName)
- description and source-code
```javascript
statementName = function (e, t){var n
,r=!!this.currentState.ignoring;return e.skip=r||undefined,t=t||0,this.currentState
.statement+=1,n=this.currentState.statement,this.coverState.statementMap[n]=e,this
.coverState.s[n]=t,n}
```
- example usage
```shell
...
t.ExpressionStatement.name&&e.expression&&e.expression.type===t.Literal.name&&e.
expression.value==="use strict"},maybeSkipNode:function(e,t){var n=!!this.currentState
.ignoring,r=this.currentState.currentHint,i=!n&&r&&r.type===t;return i?(this.startIgnore
(),e.postprocessor=this.endIgnore,!0):!1},coverStatement:function(e,n){var r,i,s
;this.maybeSkipNode(e,"next");if(this.isUseStrictExpression(e)){s=n.ancestor(2);
if(s&&(s.node.type===t.FunctionExpression.name||s.node.type===t.FunctionDeclaration
.name)&&n.parent().node.body[0]===e)return}e.type===t.FunctionDeclaration.name?r=
this.statementName(e.loc,1):(r=this.statementName(e.loc),i=f.statement(f.postIncrement
(f.subscript(f.dot(f.variable(this.currentState.trackerVar),f.variable("s")),f.stringLiteral
(r)))),this.splice(i,e,n))},splice:function(e,t,n){var r=n.isLabeled()?n.parent(
).node:t;r.prepend=r.prepend||[],d(r.prepend,e)},functionName:function(e,t,n){this
.currentState.func+=1;var r=this.currentState.func,i=!!this.currentState.ignoring
,s=e.id?e.id.name:"(anonymous_"+r+")",o=function(e){var t=n[e]||{};return{line:t
.line,column:t.column}};return this.coverState.fnMap[r]={name:s,line:t,loc:{start
:o("start"),end:o("end")},skip:i||undefined},this.coverState.f[r]=0,r},coverFunction
...
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.switchBranchInjector"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>switchBranchInjector (e, t)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.switchBranchInjector)
- description and source-code
```javascript
switchBranchInjector = function (e, t){var n=e.cases,r,i;if(!(n&&n.length>0
))return;r=this.branchName("switch",t.startLineForNode(e),this.locationsForNodes
(n));for(i=0;i<n.length;i+=1)n[i].branchLocation=this.branchLocationFor(r,i),n[i
].consequent.unshift(f.statement(this.branchIncrementExprAst(r,i)))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.switchCaseInjector"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>switchCaseInjector (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.switchCaseInjector)
- description and source-code
```javascript
switchCaseInjector = function (e){var t=e.branchLocation;delete e.branchLocation,this.maybeSkipNode(e
,"next")&&(t.skip=!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.Instrumenter.prototype.withBlockConverter"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.Instrumenter.prototype.</span>withBlockConverter (e)](#apidoc.element.utility2.istanbul.Instrumenter.prototype.withBlockConverter)
- description and source-code
```javascript
withBlockConverter = function (e){e.body=this.convertToBlock(e.body)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.istanbul.TextReport"></a>[module utility2.istanbul.TextReport](#apidoc.module.utility2.istanbul.TextReport)

#### <a name="apidoc.element.utility2.istanbul.TextReport.TextReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>TextReport (e)](#apidoc.element.utility2.istanbul.TextReport.TextReport)
- description and source-code
```javascript
function TextReport(e){Report.call(this),e=e||{},this.dir=e.dir||process.cwd(),this
.file=e.file,this.summary=e.summary,this.maxCols=e.maxCols||0,this.watermarks=e.
watermarks||defaults.watermarks()}
```
- example usage
```shell
...
    '<h1>coverage-report</h1>\n' +
    '<div ' +
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
...
```



# <a name="apidoc.module.utility2.istanbul.TextReport.prototype"></a>[module utility2.istanbul.TextReport.prototype](#apidoc.module.utility2.istanbul.TextReport.prototype)

#### <a name="apidoc.element.utility2.istanbul.TextReport.prototype.writeReport"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.TextReport.prototype.</span>writeReport (e)](#apidoc.element.utility2.istanbul.TextReport.prototype.writeReport)
- description and source-code
```javascript
writeReport = function (e){var t=new TreeSummarizer,n,r,i,s=4*(PCT_COLS+2),o,u=[]
,a;e.files().forEach(function(n){t.addFileCoverageSummary(n,utils.summarizeFileCoverage
(e.fileCoverageFor(n)))}),n=t.getTreeSummary(),r=n.root,i=findNameWidth(r),this.
maxCols>0&&(o=this.maxCols-s-2,i>o&&(i=o)),walk(r,i,u,0,this.watermarks),a=u.join
("\n")+"\n",this.file?(mkdirp.sync(this.dir),fs.writeFileSync(path.join(this.dir
,this.file),a,"utf8")):console.log(a)}
```
- example usage
```shell
...
    '<h1>coverage-report</h1>\n' +
    '<div ' +
    'style="background: #fff; border: 1px solid #000; margin 0; padding: 0;">\n';
local.writerData = '';
options.sourceStore = {};
options.writer = local.writer;
// 1. print coverage in text-format to stdout
new local.TextReport(options).writeReport(local.collector);
// 2. write coverage in html-format to filesystem
new local.HtmlReport(options).writeReport(local.collector);
local.writer.writeFile('', local.nop);
// write coverage.json
local.fsWriteFileWithMkdirpSync2(
    options.dir + '/coverage.json',
    JSON.stringify(local.global.__coverage__)
...
```



# <a name="apidoc.module.utility2.istanbul.collector"></a>[module utility2.istanbul.collector](#apidoc.module.utility2.istanbul.collector)

#### <a name="apidoc.element.utility2.istanbul.collector.fileCoverageFor"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.collector.</span>fileCoverageFor (file)](#apidoc.element.utility2.istanbul.collector.fileCoverageFor)
- description and source-code
```javascript
fileCoverageFor = function (file) {
    return local.global.__coverage__[file];
}
```
- example usage
```shell
...
functions,s.functions),branches:getReportClass(r.branches,s.branches)},o={metrics
:r,reportClasses:i,file:t.displayShortName(),output:n.fromParent(t)};e.write(summaryLineTemplate
(o)+"\n")}),e.write(summaryTableFooter),e.write(footerTemplate(r))},writeFiles:function(
e,t,n,r){var i=this,s=path.resolve(n,"index.html"),o;this.opts.verbose&&console.
error("Writing "+s),e.writeFile(s,function(e){i.writeIndexPage(e,t)}),t.children
.forEach(function(t){t.kind==="dir"?i.writeFiles(e,t,path.resolve(n,t.relativeName
),r):(o=path.resolve(n,t.relativeName+".html"),i.opts.verbose&&console.error("Writing "+
o),e.writeFile(o,function(e){i.writeDetailPage(e,t,r.fileCoverageFor(t.fullPath(
)))}))})},standardLinkMapper:function(){return{fromParent:function(e){var t=0,n=
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
r.length-1;for(o=0;o<i;o+=1)n+="../";e=e.parent}return n},ancestor:function(e,t)
{return this.ancestorHref(e,t)+"index.html"},asset:function(e,t){var n=0,r=e.parent
;while(r)n+=1,r=r.parent;return this.ancestorHref(e,n)+t}}},writeReport:function(
...
```

#### <a name="apidoc.element.utility2.istanbul.collector.files"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.collector.</span>files ()](#apidoc.element.utility2.istanbul.collector.files)
- description and source-code
```javascript
files = function () {
    return Object.keys(local.global.__coverage__).filter(function (key) {
        if (local.global.__coverage__[key] &&
                local.global.__coverageCodeDict__[key]) {
            // reset derived info
            local.global.__coverage__[key].l = null;
            return true;
        }
    });
}
```
- example usage
```shell
...
e.relativeName,r;if(SEP!=="/"){n="";for(t=0;t<e.relativeName.length;t+=1)r=e.relativeName
.charAt(t),r===SEP?n+="/":n+=r}return e.kind==="dir"?n+"index.html":n+".html"},ancestorHref
:function(e,t){var n="",r,i,s,o;for(s=0;s<t;s+=1){r=e.relativeName.split(SEP),i=
r.length-1;for(o=0;o<i;o+=1)n+="../";e=e.parent}return n},ancestor:function(e,t)
{return this.ancestorHref(e,t)+"index.html"},asset:function(e,t){var n=0,r=e.parent
;while(r)n+=1,r=r.parent;return this.ancestorHref(e,n)+t}}},writeReport:function(
e,t){var n=this.opts,r=n.dir,i=new TreeSummarizer,s=n.writer||new FileWriter(t),
o;e.files().forEach(function(t){i.addFileCoverageSummary(t,utils.summarizeFileCoverage
(e.fileCoverageFor(t)))}),o=i.getTreeSummary(),fs.readdirSync(path.resolve(__dirname
,"..","vendor")).forEach(function(e){var t=path.resolve(__dirname,"..","vendor",
e),i=path.resolve(r,e),o=fs.statSync(t);o.isFile()&&(n.verbose&&console.log("Write asset: "+
i),s.copyFile(t,i))}),this.writeFiles(s,o.root,r,e)}}),module.exports=HtmlReport
local.HtmlReport = module.exports; }());
/* jslint-ignore-end */
...
```



# <a name="apidoc.module.utility2.istanbul.coverageUtils"></a>[module utility2.istanbul.coverageUtils](#apidoc.module.utility2.istanbul.coverageUtils)

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfo"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>addDerivedInfo (e)](#apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfo)
- description and source-code
```javascript
function n(e){Object.keys(e).forEach(function(
n){t(e[n])})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfoForFile"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>addDerivedInfoForFile (e)](#apidoc.element.utility2.istanbul.coverageUtils.addDerivedInfoForFile)
- description and source-code
```javascript
function t(e){var t=e.statementMap,n=e.s,r;e.l||(e.l=r={},Object.keys
(n).forEach(function(e){var i=t[e].start.line,s=n[e],o=r[i];s===0&&t[e].skip&&(s=1
);if(typeof o=="undefined"||o<s)r[i]=s}))}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.blankSummary"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>blankSummary ()](#apidoc.element.utility2.istanbul.coverageUtils.blankSummary)
- description and source-code
```javascript
function u(){return{lines:{total:0,covered:0,skipped
:0,pct:"Unknown"},statements:{total:0,covered:0,skipped:0,pct:"Unknown"},functions
:{total:0,covered:0,skipped:0,pct:"Unknown"},branches:{total:0,covered:0,skipped
:0,pct:"Unknown"}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.mergeFileCoverage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>mergeFileCoverage (e, t)](#apidoc.element.utility2.istanbul.coverageUtils.mergeFileCoverage)
- description and source-code
```javascript
function f(e, t){var n=JSON.parse(JSON.stringify(e)),r;return delete n.l,Object.keys(t.s).forEach
(function(e){n.s[e]+=t.s[e]}),Object.keys(t.f).forEach(function(e){n.f[e]+=t.f[e
]}),Object.keys(t.b).forEach(function(e){var i=n.b[e],s=t.b[e];for(r=0;r<i.length
;r+=1)i[r]+=s[r]}),n}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.mergeSummaryObjects"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>mergeSummaryObjects ()](#apidoc.element.utility2.istanbul.coverageUtils.mergeSummaryObjects)
- description and source-code
```javascript
function l(){var e=u(),t=Array.prototype.slice.call(arguments
),n=["lines","statements","branches","functions"],r=function(t){t&&n.forEach(function(
n){e[n].total+=t[n].total,e[n].covered+=t[n].covered,e[n].skipped+=t[n].skipped}
)};return t.forEach(function(e){r(e)}),n.forEach(function(t){e[t].pct=i(e[t].covered
,e[t].total)}),e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.removeDerivedInfo"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>removeDerivedInfo (e)](#apidoc.element.utility2.istanbul.coverageUtils.removeDerivedInfo)
- description and source-code
```javascript
function r(e){Object.keys(e).forEach(function(t){delete e[t].l})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.summarizeCoverage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>summarizeCoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.summarizeCoverage)
- description and source-code
```javascript
function c(e){var t=[];return Object.keys(e).forEach(function(n
){t.push(a(e[n]))}),l.apply(null,t)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.summarizeFileCoverage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>summarizeFileCoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.summarizeFileCoverage)
- description and source-code
```javascript
function a(e){var n=u();return t(e),n.lines=s(e,"l"),n.functions=
s(e,"f","fnMap"),n.statements=s(e,"s","statementMap"),n.branches=o(e),n}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.coverageUtils.toYUICoverage"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.coverageUtils.</span>toYUICoverage (e)](#apidoc.element.utility2.istanbul.coverageUtils.toYUICoverage)
- description and source-code
```javascript
function h(e){var t={};return n(e),Object.keys
(e).forEach(function(n){var r=e[n],i=r.l,s=r.f,o=r.fnMap,u;u=t[n]={lines:{},calledLines
:0,coveredLines:0,functions:{},calledFunctions:0,coveredFunctions:0},Object.keys
(i).forEach(function(e){u.lines[e]=i[e],u.coveredLines+=1,i[e]>0&&(u.calledLines+=1
)}),Object.keys(s).forEach(function(e){var t=o[e].name+":"+o[e].line;u.functions
[t]=s[e],u.coveredFunctions+=1,s[e]>0&&(u.calledFunctions+=1)})}),t}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.istanbul.escodegen"></a>[module utility2.istanbul.escodegen](#apidoc.module.utility2.istanbul.escodegen)

#### <a name="apidoc.element.utility2.istanbul.escodegen.attachComments"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>attachComments (e, t, n)](#apidoc.element.utility2.istanbul.escodegen.attachComments)
- description and source-code
```javascript
function N(e, t, n){var r=
[],s,o,u,a;if(!e.range)throw new Error("attachComments needs range information")
;if(!n.length){if(t.length){for(u=0,o=t.length;u<o;u+=1)s=h(t[u]),s.extendedRange=
[0,e.range[0]],r.push(s);e.leadingComments=r}return e}for(u=0,o=t.length;u<o;u+=1
)r.push(T(h(t[u]),n));return a=0,S(e,{enter:function(e){var t;while(a<r.length){
t=r[a];if(t.extendedRange[1]>e.range[0])break;t.extendedRange[1]===e.range[0]?(e
.leadingComments||(e.leadingComments=[]),e.leadingComments.push(t),r.splice(a,1)
):a+=1}if(a===r.length)return i.Break;if(r[a].extendedRange[0]>e.range[1])return i
.Skip}}),a=0,S(e,{leave:function(e){var t;while(a<r.length){t=r[a];if(e.range[1]<
t.extendedRange[0])break;e.range[1]===t.extendedRange[0]?(e.trailingComments||(e
.trailingComments=[]),e.trailingComments.push(t),r.splice(a,1)):a+=1}if(a===r.length
)return i.Break;if(r[a].extendedRange[0]>e.range[1])return i.Skip}}),e}
```
- example usage
```shell
...
s+"):"+e.type)),r||e},startLineForNode:function(e){return e&&e.loc&&e.loc.start?
e.loc.start.line:null},ancestor:function(e){return this.path.length>e-1?this.path
[this.path.length-e]:null},parent:function(){return this.ancestor(1)},isLabeled:
function(){var e=this.parent();return e&&e.node.type===t.LabeledStatement.name}}
,g.prototype={instrumentSync:function(e,n){var s;if(typeof e!="string")throw new
Error("Code must be string");return e.charAt(0)==="#"&&(e="//"+e),this.opts.noAutoWrap||
(e=o+e+u),s=r.parse(e,{loc:!0,range:!0,tokens:this.opts.preserveComments,comment
:!0}),this.opts.preserveComments&&(s=i.attachComments(s,s.comments,s.tokens)),this
.opts.noAutoWrap||(s={type:t.Program.name,body:s.body[0].expression.callee.body.
body,comments:s.comments}),this.instrumentASTSync(s,n,e)},filterHints:function(e
){var t=[],n,r,i;if(!e||!h(e))return t;for(n=0;n<e.length;n+=1)r=e[n],r&&r.value&&
r.range&&h(r.range)&&(i=String(r.value).match(a),i&&t.push({type:i[1],start:r.range
[0],end:r.range[1]}));return t},extractCurrentHint:function(e){if(!e.range)return;
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
...
```

#### <a name="apidoc.element.utility2.istanbul.escodegen.generate"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.escodegen.</span>generate (e, t)](#apidoc.element.utility2.istanbul.escodegen.generate)
- description and source-code
```javascript
function Nt(e, t){
var n=V(),i,s;return t!=null?(typeof t.indent=="string"&&(n.format.indent.style=
t.indent),typeof t.base=="number"&&(n.format.indent.base=t.base),t=G(n,t),a=t.format
.indent.style,typeof t.base=="string"?u=t.base:u=$(a,t.format.indent.base)):(t=n
,a=t.format.indent.style,u=$(a,t.format.indent.base)),f=t.format.json,l=t.format
.renumber,c=f?!1:t.format.hexadecimal,h=f?"double":t.format.quotes,p=t.format.escapeless
,d=t.format.newline,v=t.format.space,t.format.compact&&(d=v=a=u=""),m=t.format.parentheses
,g=t.format.semicolons,y=t.format.safeConcatenation,b=t.directive,E=f?null:t.parse
,S=t.sourceMap,x=t.sourceCode,T=t.format.preserveBlankLines&&x!==null,w=t,S&&(exports
.browser?r=global.sourceMap.SourceNode:r=require("source-map").SourceNode),i=Tt(
e),S?(s=i.toStringWithSourceMap({file:t.file,sourceRoot:t.sourceMapRoot}),t.sourceContent&&
s.map.setSourceContent(t.sourceMap,t.sourceContent),t.sourceMapWithCode?s:s.map.
toString()):(s={code:i.toString(),map:null},t.sourceMapWithCode?s:s.code)}
```
- example usage
```shell
...
:function(e,t,n){var r=!1,s,o,u,a,f;t=t||String((new Date).getTime())+".js",this
.sourceMap=null,this.coverState={path:t,s:{},b:{},f:{},fnMap:{},statementMap:{},
branchMap:{}},this.currentState={trackerVar:p(t,this.omitTrackerSuffix),func:0,branch
:0,variable:0,statement:0,hints:this.filterHints(e.comments),currentHint:null,lastHintPosition
:-1,ignoring:0},e.body&&e.body.length>0&&this.isUseStrictExpression(e.body[0])&&
(e.body.shift(),r=!0),this.walker.startWalk(e),s=this.opts.codeGenerationOptions||
{format:{compact:!this.opts.noCompact}},s.comment=this.opts.preserveComments,o=i
.generate(e,s),u=this.getPreamble(n||"",r);if(o.map&&o.code){a=u.split(/\r\n|\r|\n/
).length;for(f=0;f<o.map._mappings._array.length;f+=1)o.map._mappings._array[f].
generatedLine+=a;this.sourceMap=o.map,o=o.code}return u+"\n"+o+"\n"},instrument:
function(e,t,n){!n&&typeof t=="function"&&(n=t,t=null);try{n(null,this.instrumentSync
(e,t))}catch(r){n(r)}},lastFileCoverage:function(){return this.coverState},lastSourceMap
:function(){return this.sourceMap},fixColumnPositions:function(e){var t=o.length
,n=function(e){e.start.line===1&&(e.start.column-=t),e.end.line===1&&(e.end.column-=
t)},r,i,s,u;i=e.statementMap;for(r in i)i.hasOwnProperty(r)&&n(i[r]);i=e.fnMap;for(
...
```



# <a name="apidoc.module.utility2.istanbul.esprima"></a>[module utility2.istanbul.esprima](#apidoc.module.utility2.istanbul.esprima)

#### <a name="apidoc.element.utility2.istanbul.esprima.parse"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>parse (e, t)](#apidoc.element.utility2.istanbul.esprima.parse)
- description and source-code
```javascript
function Sr(e, t){var n,r;r=String,typeof e!="string"&&!(e instanceof
String)&&(e=r(e)),a=e,c=0,h=a.length>0?1:0,p=0,y=c,b=h,w=p,S=a.length,x=null,T={
allowIn:!0,allowYield:!0,labelSet:{},inFunctionBody:!1,inIteration:!1,inSwitch:!1
,lastCommentStart:-1,curlyStack:[]},l="script",f=!1,N={},typeof t!="undefined"&&
(N.range=typeof t.range=="boolean"&&t.range,N.loc=typeof t.loc=="boolean"&&t.loc
,N.attachComment=typeof t.attachComment=="boolean"&&t.attachComment,N.loc&&t.source!==
null&&t.source!==undefined&&(N.source=r(t.source)),typeof t.tokens=="boolean"&&t
.tokens&&(N.tokens=[]),typeof t.comment=="boolean"&&t.comment&&(N.comments=[]),typeof
t.tolerant=="boolean"&&t.tolerant&&(N.errors=[]),N.attachComment&&(N.range=!0,N.
comments=[],N.bottomRightStack=[],N.trailingComments=[],N.leadingComments=[]),t.
sourceType==="module"&&(l=t.sourceType,f=!0));try{n=br(),typeof N.comments!="undefined"&&
(n.comments=N.comments),typeof N.tokens!="undefined"&&(wr(),n.tokens=N.tokens),typeof
N.errors!="undefined"&&(n.errors=N.errors)}catch(i){throw i}finally{N={}}return n
}
```
- example usage
```shell
...
    return;
}
// try to JSON.stringify #inputTextareaEval1
try {
    document.querySelector('#outputPreJsonStringify1').textContent = '';
    document.querySelector('#outputPreJsonStringify1').textContent =
        local.jsonStringifyOrdered(
            JSON.parse(document.querySelector('#inputTextareaEval1').value),
            null,
            4
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
local.jslint.errorText = '';
...
```

#### <a name="apidoc.element.utility2.istanbul.esprima.tokenize"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.esprima.</span>tokenize (e, n)](#apidoc.element.utility2.istanbul.esprima.tokenize)
- description and source-code
```javascript
function Er(e, n){var r,i;r=String,typeof e!="string"&&!(e instanceof
String)&&(e=r(e)),a=e,c=0,h=a.length>0?1:0,p=0,y=c,b=h,w=p,S=a.length,x=null,T={
allowIn:!0,allowYield:!0,labelSet:{},inFunctionBody:!1,inIteration:!1,inSwitch:!1
,lastCommentStart:-1,curlyStack:[]},N={},n=n||{},n.tokens=!0,N.tokens=[],N.tokenize=!0
,N.openParenToken=-1,N.openCurlyToken=-1,N.range=typeof n.range=="boolean"&&n.range
,N.loc=typeof n.loc=="boolean"&&n.loc,typeof n.comment=="boolean"&&n.comment&&(N
.comments=[]),typeof n.tolerant=="boolean"&&n.tolerant&&(N.errors=[]);try{gt();if(
x.type===t.EOF)return N.tokens;mt();while(x.type!==t.EOF)try{mt()}catch(s){if(N.
errors){xt(s);break}throw s}wr(),i=N.tokens,typeof N.comments!="undefined"&&(i.comments=
N.comments),typeof N.errors!="undefined"&&(i.errors=N.errors)}catch(o){throw o}finally{
N={}}return i}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.istanbul.estraverse"></a>[module utility2.istanbul.estraverse](#apidoc.module.utility2.istanbul.estraverse)

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>Controller ()](#apidoc.element.utility2.istanbul.estraverse.Controller)
- description and source-code
```javascript
function b(){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.attachComments"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>attachComments (e, t, n)](#apidoc.element.utility2.istanbul.estraverse.attachComments)
- description and source-code
```javascript
function N(e, t, n){var r=
[],s,o,u,a;if(!e.range)throw new Error("attachComments needs range information")
;if(!n.length){if(t.length){for(u=0,o=t.length;u<o;u+=1)s=h(t[u]),s.extendedRange=
[0,e.range[0]],r.push(s);e.leadingComments=r}return e}for(u=0,o=t.length;u<o;u+=1
)r.push(T(h(t[u]),n));return a=0,S(e,{enter:function(e){var t;while(a<r.length){
t=r[a];if(t.extendedRange[1]>e.range[0])break;t.extendedRange[1]===e.range[0]?(e
.leadingComments||(e.leadingComments=[]),e.leadingComments.push(t),r.splice(a,1)
):a+=1}if(a===r.length)return i.Break;if(r[a].extendedRange[0]>e.range[1])return i
.Skip}}),a=0,S(e,{leave:function(e){var t;while(a<r.length){t=r[a];if(e.range[1]<
t.extendedRange[0])break;e.range[1]===t.extendedRange[0]?(e.trailingComments||(e
.trailingComments=[]),e.trailingComments.push(t),r.splice(a,1)):a+=1}if(a===r.length
)return i.Break;if(r[a].extendedRange[0]>e.range[1])return i.Skip}}),e}
```
- example usage
```shell
...
s+"):"+e.type)),r||e},startLineForNode:function(e){return e&&e.loc&&e.loc.start?
e.loc.start.line:null},ancestor:function(e){return this.path.length>e-1?this.path
[this.path.length-e]:null},parent:function(){return this.ancestor(1)},isLabeled:
function(){var e=this.parent();return e&&e.node.type===t.LabeledStatement.name}}
,g.prototype={instrumentSync:function(e,n){var s;if(typeof e!="string")throw new
Error("Code must be string");return e.charAt(0)==="#"&&(e="//"+e),this.opts.noAutoWrap||
(e=o+e+u),s=r.parse(e,{loc:!0,range:!0,tokens:this.opts.preserveComments,comment
:!0}),this.opts.preserveComments&&(s=i.attachComments(s,s.comments,s.tokens)),this
.opts.noAutoWrap||(s={type:t.Program.name,body:s.body[0].expression.callee.body.
body,comments:s.comments}),this.instrumentASTSync(s,n,e)},filterHints:function(e
){var t=[],n,r,i;if(!e||!h(e))return t;for(n=0;n<e.length;n+=1)r=e[n],r&&r.value&&
r.range&&h(r.range)&&(i=String(r.value).match(a),i&&t.push({type:i[1],start:r.range
[0],end:r.range[1]}));return t},extractCurrentHint:function(e){if(!e.range)return;
var t=this.currentState.lastHintPosition+1,n=this.currentState.hints,r=e.range[0
],i;this.currentState.currentHint=null;while(t<n.length){i=n[t];if(!(i.end<r))break;
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.cloneEnvironment"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>cloneEnvironment ()](#apidoc.element.utility2.istanbul.estraverse.cloneEnvironment)
- description and source-code
```javascript
cloneEnvironment = function (){return e({})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.replace"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>replace (e, t)](#apidoc.element.utility2.istanbul.estraverse.replace)
- description and source-code
```javascript
function x(e, t){var n=new b;return n.replace
(e,t)}
```
- example usage
```shell
...
    local.jslint.jslintAndPrint(
        document.querySelector('#inputTextareaEval1').value,
        'inputTextareaEval1.js'
    );
}
document.querySelector('#outputPreJslint1').textContent =
    local.jslint.errorText
    .replace((/\u001b\[\d+m/g), '')
    .trim();
// try to cleanup __coverage__
try {
    delete local.global.__coverage__['/inputTextareaEval1.js'];
} catch (ignore) {
}
// try to cover and eval input-code
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.traverse"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.</span>traverse (e, t)](#apidoc.element.utility2.istanbul.estraverse.traverse)
- description and source-code
```javascript
function S(e, t){var n=new b;return n.traverse(e,t)}
```
- example usage
```shell
...
t){var n,r,i,s;r=e.length,i=0;while(r)n=r>>>1,s=i+n,t(e[s])?r=n:(i=s+1,r-=n+1);return i
}function v(e,t){var n,r,i,s;r=e.length,i=0;while(r)n=r>>>1,s=i+n,t(e[s])?(i=s+1
,r-=n+1):r=n;return i}function m(e,t){var n=u(t),r,i,s;for(i=0,s=n.length;i<s;i+=1
)r=n[i],e[r]=t[r];return e}function g(e,t){this.parent=e,this.key=t}function y(e
,t,n,r){this.node=e,this.path=t,this.wrap=n,this.ref=r}function b(){}function w(
e){return e==null?!1:typeof e=="object"&&typeof e.type=="string"}function E(e,t)
{return(e===n.ObjectExpression||e===n.ObjectPattern)&&"properties"===t}function S
(e,t){var n=new b;return n.traverse(e,t)}function x(e,t){var n=new b;return n.replace
(e,t)}function T(e,t){var n;return n=d(t,function(n){return n.range[0]>e.range[0
]}),e.extendedRange=[e.range[0],e.range[1]],n!==t.length&&(e.extendedRange[1]=t[
n].range[0]),n-=1,n>=0&&(e.extendedRange[0]=t[n].range[1]),e}function N(e,t,n){var r=
[],s,o,u,a;if(!e.range)throw new Error("attachComments needs range information")
;if(!n.length){if(t.length){for(u=0,o=t.length;u<o;u+=1)s=h(t[u]),s.extendedRange=
[0,e.range[0]],r.push(s);e.leadingComments=r}return e}for(u=0,o=t.length;u<o;u+=1
)r.push(T(h(t[u]),n));return a=0,S(e,{enter:function(e){var t;while(a<r.length){
...
```



# <a name="apidoc.module.utility2.istanbul.estraverse.Controller.prototype"></a>[module utility2.istanbul.estraverse.Controller.prototype](#apidoc.module.utility2.istanbul.estraverse.Controller.prototype)

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__execute"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>__execute (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__execute)
- description and source-code
```javascript
__execute = function (t, n){var r,i;return i=
undefined,r=this.__current,this.__current=n,this.__state=null,t&&(i=t.call(this,
n.node,this.__leavelist[this.__leavelist.length-1].node)),this.__current=r,i}
```
- example usage
```shell
...
(f)},b.prototype["break"]=function(){this.notify(a)},b.prototype.remove=function(
){this.notify(l)},b.prototype.__initialize=function(e,t){this.visitor=t,this.root=
e,this.__worklist=[],this.__leavelist=[],this.__current=null,this.__state=null,this
.__fallback=t.fallback==="iteration",this.__keys=s,t.keys&&(this.__keys=m(o(this
.__keys),t.keys))},b.prototype.traverse=function(t,n){var i,s,o,l,c,h,p,d,v,m,g,
b;this.__initialize(t,n),b={},i=this.__worklist,s=this.__leavelist,i.push(new y(
t,null,null,null)),s.push(new y(null,null,null,null));while(i.length){o=i.pop();
if(o===b){o=s.pop(),h=this.__execute(n.leave,o);if(this.__state===a||h===a)return;
continue}if(o.node){h=this.__execute(n.enter,o);if(this.__state===a||h===a)return;
i.push(b),s.push(o);if(this.__state===f||h===f)continue;l=o.node,c=o.wrap||l.type
,m=this.__keys[c];if(!m){if(!this.__fallback)throw new Error("Unknown node type "+
c+".");m=u(l)}d=m.length;while((d-=1)>=0){p=m[d],g=l[p];if(!g)continue;if(r(g)){
v=g.length;while((v-=1)>=0){if(!g[v])continue;if(E(c,m[d]))o=new y(g[v],[p,v],"Property"
,null);else{if(!w(g[v]))continue;o=new y(g[v],[p,v],null,null)}i.push(o)}}else w
(g)&&i.push(new y(g,p,null,null))}}}},b.prototype.replace=function(t,n){function i
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__initialize"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>__initialize (e, t)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.__initialize)
- description and source-code
```javascript
__initialize = function (e, t){this.visitor=t,this.root=
e,this.__worklist=[],this.__leavelist=[],this.__current=null,this.__state=null,this
.__fallback=t.fallback==="iteration",this.__keys=s,t.keys&&(this.__keys=m(o(this
.__keys),t.keys))}
```
- example usage
```shell
...
n.node,this.__leavelist[this.__leavelist.length-1].node)),this.__current=r,i},b.
prototype.notify=function(t){this.__state=t},b.prototype.skip=function(){this.notify
(f)},b.prototype["break"]=function(){this.notify(a)},b.prototype.remove=function(
){this.notify(l)},b.prototype.__initialize=function(e,t){this.visitor=t,this.root=
e,this.__worklist=[],this.__leavelist=[],this.__current=null,this.__state=null,this
.__fallback=t.fallback==="iteration",this.__keys=s,t.keys&&(this.__keys=m(o(this
.__keys),t.keys))},b.prototype.traverse=function(t,n){var i,s,o,l,c,h,p,d,v,m,g,
b;this.__initialize(t,n),b={},i=this.__worklist,s=this.__leavelist,i.push(new y(
t,null,null,null)),s.push(new y(null,null,null,null));while(i.length){o=i.pop();
if(o===b){o=s.pop(),h=this.__execute(n.leave,o);if(this.__state===a||h===a)return;
continue}if(o.node){h=this.__execute(n.enter,o);if(this.__state===a||h===a)return;
i.push(b),s.push(o);if(this.__state===f||h===f)continue;l=o.node,c=o.wrap||l.type
,m=this.__keys[c];if(!m){if(!this.__fallback)throw new Error("Unknown node type "+
c+".");m=u(l)}d=m.length;while((d-=1)>=0){p=m[d],g=l[p];if(!g)continue;if(r(g)){
v=g.length;while((v-=1)>=0){if(!g[v])continue;if(E(c,m[d]))o=new y(g[v],[p,v],"Property"
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.break"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>break ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.break)
- description and source-code
```javascript
break = function (){this.notify(a)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.current"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>current ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.current)
- description and source-code
```javascript
current = function ( ){return this.__current.node}
```
- example usage
```shell
...
:["id","init"],WhileStatement:["test","body"],WithStatement:["object","body"],YieldExpression
:["argument"]},a={},f={},l={},i={Break:a,Skip:f,Remove:l},g.prototype.replace=function(
t){this.parent[this.key]=t},g.prototype.remove=function(){return r(this.parent)?
(this.parent.splice(this.key,1),!0):(this.replace(null),!1)},b.prototype.path=function(
){function a(e,t){if(r(t))for(i=0,s=t.length;i<s;++i)e.push(t[i]);else e.push(t)
}var t,n,i,s,o,u;if(!this.__current.path)return null;o=[];for(t=2,n=this.__leavelist
.length;t<n;++t)u=this.__leavelist[t],a(o,u.path);return a(o,this.__current.path
),o},b.prototype.type=function(){var e=this.current();return e.type||this.__current
.wrap},b.prototype.parents=function(){var t,n,r;r=[];for(t=1,n=this.__leavelist.
length;t<n;++t)r.push(this.__leavelist[t].node);return r},b.prototype.current=function(
){return this.__current.node},b.prototype.__execute=function(t,n){var r,i;return i=
undefined,r=this.__current,this.__current=n,this.__state=null,t&&(i=t.call(this,
n.node,this.__leavelist[this.__leavelist.length-1].node)),this.__current=r,i},b.
prototype.notify=function(t){this.__state=t},b.prototype.skip=function(){this.notify
(f)},b.prototype["break"]=function(){this.notify(a)},b.prototype.remove=function(
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.notify"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>notify (t)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.notify)
- description and source-code
```javascript
notify = function (t){this.__state=t}
```
- example usage
```shell
...
),o},b.prototype.type=function(){var e=this.current();return e.type||this.__current
.wrap},b.prototype.parents=function(){var t,n,r;r=[];for(t=1,n=this.__leavelist.
length;t<n;++t)r.push(this.__leavelist[t].node);return r},b.prototype.current=function(
){return this.__current.node},b.prototype.__execute=function(t,n){var r,i;return i=
undefined,r=this.__current,this.__current=n,this.__state=null,t&&(i=t.call(this,
n.node,this.__leavelist[this.__leavelist.length-1].node)),this.__current=r,i},b.
prototype.notify=function(t){this.__state=t},b.prototype.skip=function(){this.notify
(f)},b.prototype["break"]=function(){this.notify(a)},b.prototype.remove=function(
){this.notify(l)},b.prototype.__initialize=function(e,t){this.visitor=t,this.root=
e,this.__worklist=[],this.__leavelist=[],this.__current=null,this.__state=null,this
.__fallback=t.fallback==="iteration",this.__keys=s,t.keys&&(this.__keys=m(o(this
.__keys),t.keys))},b.prototype.traverse=function(t,n){var i,s,o,l,c,h,p,d,v,m,g,
b;this.__initialize(t,n),b={},i=this.__worklist,s=this.__leavelist,i.push(new y(
t,null,null,null)),s.push(new y(null,null,null,null));while(i.length){o=i.pop();
if(o===b){o=s.pop(),h=this.__execute(n.leave,o);if(this.__state===a||h===a)return;
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.parents"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>parents ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.parents)
- description and source-code
```javascript
parents = function (){var t,n,r;r=[];for(t=1,n=this.__leavelist.
length;t<n;++t)r.push(this.__leavelist[t].node);return r}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.path"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>path ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.path)
- description and source-code
```javascript
path = function ( ){function a(e,t){if(r(t))for(i=0,s=t.length;i<s;++i)e.push(t[i]);else e.push(t)
}var t,n,i,s,o,u;if(!this.__current.path)return null;o=[];for(t=2,n=this.__leavelist
.length;t<n;++t)u=this.__leavelist[t],a(o,u.path);return a(o,this.__current.path
),o}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.remove"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>remove ( )](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.remove)
- description and source-code
```javascript
remove = function ( ){this.notify(l)}
```
- example usage
```shell
...
continue}if(o.node){h=this.__execute(n.enter,o);if(this.__state===a||h===a)return;
i.push(b),s.push(o);if(this.__state===f||h===f)continue;l=o.node,c=o.wrap||l.type
,m=this.__keys[c];if(!m){if(!this.__fallback)throw new Error("Unknown node type "+
c+".");m=u(l)}d=m.length;while((d-=1)>=0){p=m[d],g=l[p];if(!g)continue;if(r(g)){
v=g.length;while((v-=1)>=0){if(!g[v])continue;if(E(c,m[d]))o=new y(g[v],[p,v],"Property"
,null);else{if(!w(g[v]))continue;o=new y(g[v],[p,v],null,null)}i.push(o)}}else w
(g)&&i.push(new y(g,p,null,null))}}}},b.prototype.replace=function(t,n){function i
(e){var t,n,r,i;if(e.ref.remove()){n=e.ref.key,i=e.ref.parent,t=s.length;while(t--
){r=s[t];if(r.ref&&r.ref.parent===i){if(r.ref.key<n)break;--r.ref.key}}}}var s,o
,c,h,p,d,v,m,b,S,x,T,N;this.__initialize(t,n),x={},s=this.__worklist,o=this.__leavelist
,T={root:t},d=new y(t,null,null,new g(T,"root")),s.push(d),o.push(d);while(s.length
){d=s.pop();if(d===x){d=o.pop(),p=this.__execute(n.leave,d),p!==undefined&&p!==a&&
p!==f&&p!==l&&d.ref.replace(p),(this.__state===l||p===l)&&i(d);if(this.__state===
a||p===a)return T.root;continue}p=this.__execute(n.enter,d),p!==undefined&&p!==a&&
p!==f&&p!==l&&(d.ref.replace(p),d.node=p);if(this.__state===l||p===l)i(d),d.node=
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.replace"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>replace (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.replace)
- description and source-code
```javascript
replace = function (t, n){function i
(e){var t,n,r,i;if(e.ref.remove()){n=e.ref.key,i=e.ref.parent,t=s.length;while(t--
){r=s[t];if(r.ref&&r.ref.parent===i){if(r.ref.key<n)break;--r.ref.key}}}}var s,o
,c,h,p,d,v,m,b,S,x,T,N;this.__initialize(t,n),x={},s=this.__worklist,o=this.__leavelist
,T={root:t},d=new y(t,null,null,new g(T,"root")),s.push(d),o.push(d);while(s.length
){d=s.pop();if(d===x){d=o.pop(),p=this.__execute(n.leave,d),p!==undefined&&p!==a&&
p!==f&&p!==l&&d.ref.replace(p),(this.__state===l||p===l)&&i(d);if(this.__state===
a||p===a)return T.root;continue}p=this.__execute(n.enter,d),p!==undefined&&p!==a&&
p!==f&&p!==l&&(d.ref.replace(p),d.node=p);if(this.__state===l||p===l)i(d),d.node=
null;if(this.__state===a||p===a)return T.root;c=d.node;if(!c)continue;s.push(x),
o.push(d);if(this.__state===f||p===f)continue;h=d.wrap||c.type,b=this.__keys[h];
if(!b){if(!this.__fallback)throw new Error("Unknown node type "+h+".");b=u(c)}v=
b.length;while((v-=1)>=0){N=b[v],S=c[N];if(!S)continue;if(r(S)){m=S.length;while(
(m-=1)>=0){if(!S[m])continue;if(E(h,b[v]))d=new y(S[m],[N,m],"Property",new g(S,
m));else{if(!w(S[m]))continue;d=new y(S[m],[N,m],null,new g(S,m))}s.push(d)}}else w
(S)&&s.push(new y(S,N,null,new g(c,N)))}}return T.root}
```
- example usage
```shell
...
    local.jslint.jslintAndPrint(
        document.querySelector('#inputTextareaEval1').value,
        'inputTextareaEval1.js'
    );
}
document.querySelector('#outputPreJslint1').textContent =
    local.jslint.errorText
    .replace((/\u001b\[\d+m/g), '')
    .trim();
// try to cleanup __coverage__
try {
    delete local.global.__coverage__['/inputTextareaEval1.js'];
} catch (ignore) {
}
// try to cover and eval input-code
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.skip"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>skip ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.skip)
- description and source-code
```javascript
skip = function (){this.notify
(f)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.traverse"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>traverse (t, n)](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.traverse)
- description and source-code
```javascript
traverse = function (t, n){var i,s,o,l,c,h,p,d,v,m,g,
b;this.__initialize(t,n),b={},i=this.__worklist,s=this.__leavelist,i.push(new y(
t,null,null,null)),s.push(new y(null,null,null,null));while(i.length){o=i.pop();
if(o===b){o=s.pop(),h=this.__execute(n.leave,o);if(this.__state===a||h===a)return;
continue}if(o.node){h=this.__execute(n.enter,o);if(this.__state===a||h===a)return;
i.push(b),s.push(o);if(this.__state===f||h===f)continue;l=o.node,c=o.wrap||l.type
,m=this.__keys[c];if(!m){if(!this.__fallback)throw new Error("Unknown node type "+
c+".");m=u(l)}d=m.length;while((d-=1)>=0){p=m[d],g=l[p];if(!g)continue;if(r(g)){
v=g.length;while((v-=1)>=0){if(!g[v])continue;if(E(c,m[d]))o=new y(g[v],[p,v],"Property"
,null);else{if(!w(g[v]))continue;o=new y(g[v],[p,v],null,null)}i.push(o)}}else w
(g)&&i.push(new y(g,p,null,null))}}}}
```
- example usage
```shell
...
t){var n,r,i,s;r=e.length,i=0;while(r)n=r>>>1,s=i+n,t(e[s])?r=n:(i=s+1,r-=n+1);return i
}function v(e,t){var n,r,i,s;r=e.length,i=0;while(r)n=r>>>1,s=i+n,t(e[s])?(i=s+1
,r-=n+1):r=n;return i}function m(e,t){var n=u(t),r,i,s;for(i=0,s=n.length;i<s;i+=1
)r=n[i],e[r]=t[r];return e}function g(e,t){this.parent=e,this.key=t}function y(e
,t,n,r){this.node=e,this.path=t,this.wrap=n,this.ref=r}function b(){}function w(
e){return e==null?!1:typeof e=="object"&&typeof e.type=="string"}function E(e,t)
{return(e===n.ObjectExpression||e===n.ObjectPattern)&&"properties"===t}function S
(e,t){var n=new b;return n.traverse(e,t)}function x(e,t){var n=new b;return n.replace
(e,t)}function T(e,t){var n;return n=d(t,function(n){return n.range[0]>e.range[0
]}),e.extendedRange=[e.range[0],e.range[1]],n!==t.length&&(e.extendedRange[1]=t[
n].range[0]),n-=1,n>=0&&(e.extendedRange[0]=t[n].range[1]),e}function N(e,t,n){var r=
[],s,o,u,a;if(!e.range)throw new Error("attachComments needs range information")
;if(!n.length){if(t.length){for(u=0,o=t.length;u<o;u+=1)s=h(t[u]),s.extendedRange=
[0,e.range[0]],r.push(s);e.leadingComments=r}return e}for(u=0,o=t.length;u<o;u+=1
)r.push(T(h(t[u]),n));return a=0,S(e,{enter:function(e){var t;while(a<r.length){
...
```

#### <a name="apidoc.element.utility2.istanbul.estraverse.Controller.prototype.type"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.estraverse.Controller.prototype.</span>type ()](#apidoc.element.utility2.istanbul.estraverse.Controller.prototype.type)
- description and source-code
```javascript
type = function (){var e=this.current();return e.type||this.__current
.wrap}
```
- example usage
```shell
...
n.peek()=="+"){r=this.unicodeRangeToken(t,i,s);break};default:isDigit(t)?r=this.
numberToken(t,i,s):isWhitespace(t)?r=this.whitespaceToken(t,i,s):isIdentStart(t)?
r=this.identOrFunctionToken(t,i,s):r=this.charToken(t,i,s)}break}return!r&&t===null&&
(r=this.createToken(Tokens.EOF,null,i,s)),r},createToken:function(e,t,n,r,i){var s=
this._reader;return i=i||{},{value:t,type:e,channel:i.channel,hide:i.hide||!1,startLine
:n,startCol:r,endLine:s.getLine(),endCol:s.getCol()}},atRuleToken:function(e,t,n
){var r=e,i=this._reader,s=Tokens.CHAR,o=!1,u,a;i.mark(),u=this.readName(),r=e+u
,s=Tokens.type(r.toLowerCase());if(s==Tokens.CHAR||s==Tokens.UNKNOWN)r.length>1?
s=Tokens.UNKNOWN_SYM:(s=Tokens.CHAR,r=e,i.reset());return this.createToken(s,r,t
,n)},charToken:function(e,t,n){var r=Tokens.type(e);return r==-1&&(r=Tokens.CHAR
),this.createToken(r,e,t,n)},commentToken:function(e,t,n){var r=this._reader,i=this
.readComment(e);return this.createToken(Tokens.COMMENT,i,t,n)},comparisonToken:function(
e,t,n){var r=this._reader,i=e+r.read(),s=Tokens.type(i)||Tokens.CHAR;return this
.createToken(s,i,t,n)},hashToken:function(e,t,n){var r=this._reader,i=this.readName
(e);return this.createToken(Tokens.HASH,i,t,n)},htmlCommentStartToken:function(e
...
```



# <a name="apidoc.module.utility2.istanbul.fs"></a>[module utility2.istanbul.fs](#apidoc.module.utility2.istanbul.fs)

#### <a name="apidoc.element.utility2.istanbul.fs.readFileSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.fs.</span>readFileSync (file)](#apidoc.element.utility2.istanbul.fs.readFileSync)
- description and source-code
```javascript
readFileSync = function (file) {
    // return head.txt or foot.txt
    file = local[file.slice(-8)];
    if (local.modeJs === 'browser') {
        file = file
            .replace((/\bhtml\b/g), 'x-istanbul-html')
            .replace((/<style>[\S\s]+?<\/style>/), function (match0) {
                return match0
                    .replace((/\S.*?\{/g), function (match0) {
                        return 'x-istanbul-html ' + match0
                            .replace((/,/g), ', x-istanbul-html ');
                    });
            })
            .replace('position: fixed;', 'position: static;')
            .replace('margin-top: 170px;', 'margin-top: 10px;');
    }
    if (local.modeJs === 'node' && process.env.npm_package_homepage) {
        file = file
            .replace('https://github.com/kaizhu256/node-utility2', process.env.npm_package_homepage)
            .replace('utility2', process.env.npm_package_name)
            .replace('2017.3.22', process.env.npm_package_version);
    } else {
        file = file.replace((/<h1 [\S\s]*<\/h1>/), '<h1>&nbsp;</h1>');
    }
    return file;
}
```
- example usage
```shell
...
}
// run the cli
if (local.global.utility2_rollup || module !== require.main) {
    break;
}
local.assetsDict['/assets.example.js'] =
    local.assetsDict['/assets.example.js'] ||
    local.fs.readFileSync(__filename, 'utf8');
local.assetsDict['/assets.utility2.rollup.js'] =
    local.assetsDict['/assets.utility2.rollup.js'] ||
    local.fs.readFileSync(
        // npmdoc-hack
        local.utility2.__dirname +
            '/lib.utility2.js',
        'utf8'
...
```

#### <a name="apidoc.element.utility2.istanbul.fs.readdirSync"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.fs.</span>readdirSync ()](#apidoc.element.utility2.istanbul.fs.readdirSync)
- description and source-code
```javascript
readdirSync = function () {
    return [];
}
```
- example usage
```shell
...
    html: '',
    moduleDict: {},
    moduleExtraDict: {},
    template: local.templateApidocHtml
});
// init exampleList
options.exampleList = options.exampleList.concat(options.exampleFileList.concat(
    local.fs.readdirSync(options.dir)
        .sort()
        .filter(function (file) {
            return file.indexOf(options.env.npm_package_main) === 0 ||
                (/^(?:readme)\b/i).test(file) ||
                (/^(?:index|lib|test)\b.*\.js$/i).test(file);
        })
).map(readExample));
...
```



# <a name="apidoc.module.utility2.istanbul.handlebars"></a>[module utility2.istanbul.handlebars](#apidoc.module.utility2.istanbul.handlebars)

#### <a name="apidoc.element.utility2.istanbul.handlebars.compile"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>compile (template)](#apidoc.element.utility2.istanbul.handlebars.compile)
- description and source-code
```javascript
compile = function (template) {
<span class="apidocCodeCommentSpan">/*
 * this function will return a function that will render the template with a given dict
 */
</span>    return function (dict) {
        var result;
        result = template;
        // render triple-curly-brace
        result = result.replace((/\{\{\{/g), '{{').replace((/\}\}\}/g), '}}');
        // render with-statement
        result = result.replace(
            (/\{\{#with (.+?)\}\}([\S\s]+?)\{\{\/with\}\}/g),
            function (match0, match1, match2) {
                // jslint-hack
                local.nop(match0);
                return local.handlebars.replace(match2, dict, match1 + '.');
            }
        );
        // render helper
        result = result.replace(
            '{{#show_ignores metrics}}{{/show_ignores}}',
            function () {
                return local.handlebars.show_ignores(dict.metrics);
            }
        );
        result = result.replace('{{#show_line_execution_counts fileCoverage}}' +
            '{{maxLines}}{{/show_line_execution_counts}}', function () {
                return local.handlebars.show_line_execution_counts(
                    dict.fileCoverage,
                    { fn: function () {
                        return dict.maxLines;
                    } }
                );
            });
        result = result.replace(
            '{{#show_lines}}{{maxLines}}{{/show_lines}}',
            function () {
                return local.handlebars.show_lines({ fn: function () {
                    return dict.maxLines;
                } });
            }
        );
        result = result.replace(
            '{{#show_picture}}{{metrics.statements.pct}}{{/show_picture}}',
            function () {
                return local.handlebars.show_picture({ fn: function () {
                    return dict.metrics.statements.pct;
                } });
            }
        );
        result = local.handlebars.replace(result, dict, '');
        // show code last
        result = result.replace(
            '{{#show_code structured}}{{/show_code}}',
            function () {
                return local.handlebars.show_code(dict.structured);
            }
        );
        return result;
    };
}
```
- example usage
```shell
...
create("fslookup"),this.opts.linkMapper=this.opts.linkMapper||this.standardLinkMapper
(),this.opts.writer=this.opts.writer||null,this.opts.templateData={datetime:Date
()},this.opts.watermarks=this.opts.watermarks||defaults.watermarks()}var handlebars=
require("handlebars"),defaults=require("./common/defaults"),path=require("path")
,SEP=path.sep||"/",fs=require("fs"),util=require("util"),FileWriter=require("../util/file-writer"
),Report=require("./index"),Store=require("../store"),InsertionText=require("../util/insertion-text"
),TreeSummarizer=require("../util/tree-summarizer"),utils=require("../object-utils"
),templateFor=function(e){return handlebars.compile(fs.readFileSync(path.resolve
(__dirname,"templates",e+".txt"),"utf8"))},headerTemplate=templateFor("head"),footerTemplate=
templateFor("foot"),pathTemplate=handlebars.compile('<div class="path">{{{html}}}</div>'
),detailTemplate=handlebars.compile(["<tr>",'<td class="line-count">{{#show_lines}}{{maxLines}}{{/show_lines}}</td>'
,'<td class="line-coverage">{{#show_line_execution_counts fileCoverage}}{{maxLines}}{{/show_line_execution_counts}}</td>'
,'<td class="text"><pre class="prettyprint lang-js">{{#show_code structured}}{{/show_code}}</pre></td>'
,"</tr>\n"].join("")),summaryTableHeader=['<div class="coverage-summary">',"<table>"
,"<thead>","<tr>",'   <th data-col="file" data-fmt="html" data-html="true" class="file">File</th>'
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.registerHelper"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>registerHelper (key, helper)](#apidoc.element.utility2.istanbul.handlebars.registerHelper)
- description and source-code
```javascript
registerHelper = function (key, helper) {
<span class="apidocCodeCommentSpan">/*
 * this function will register the helper-function
 */
</span>    local.handlebars[key] = function () {
        try {
            return helper.apply(null, arguments);
        } catch (ignore) {
        }
    };
}
```
- example usage
```shell
...
,'<td data-value="{{metrics.branches.total}}" class="abs {{reportClasses.branches}}">({{metrics.branches.covered}}&nbsp;/&nbsp;{{
metrics.branches.total}})</td>'
,'<td data-value="{{metrics.functions.pct}}" class="pct {{reportClasses.functions}}">{{metrics.functions.pct}}%</td>'
,'<td data-value="{{metrics.functions.total}}" class="abs {{reportClasses.functions}}">({{metrics.functions.covered}}&nbsp;/&nbsp
;{{metrics.functions.total}})</td>'
,'<td data-value="{{metrics.lines.pct}}" class="pct {{reportClasses.lines}}">{{metrics.lines.pct}}%</td>'
,'<td data-value="{{metrics.lines.total}}" class="abs {{reportClasses.lines}}">({{metrics.lines.covered}}&nbsp;/&nbsp;{{metrics.
lines.total}})</td>'
,"</tr>\n"].join("\n	")),summaryTableFooter=["</tbody>","</table>","</div>"].join
("\n"),lt="",gt="",RE_LT=/</g,RE_GT=/>/g,RE_AMP=/&/g,RE_lt=/\u0001/g,RE_gt=/\u0002/g
;handlebars.registerHelper("show_picture",function(e){var t=Number(e.fn(this)),n
,r="";return isFinite(t)?(t===100&&(r=" cover-full"),t=Math.floor(t),n=100-t,'<span class="cover-fill'+
r+'" style="width: '+t+'px;"></span>'+'<span class="cover-empty" style="width:'+
n+'px;"></span>'):""}),handlebars.registerHelper("show_ignores",function(e){var t=
e.statements.skipped,n=e.functions.skipped,r=e.branches.skipped,i;return t===0&&
n===0&&r===0?'<span class="ignore-none">none</span>':(i=[],t>0&&i.push(t===1?"1 statement"
:t+" statements"),n>0&&i.push(n===1?"1 function":n+" functions"),r>0&&i.push(r===1?"1 branch"
:r+" branches"),i.join(", "))}),handlebars.registerHelper("show_lines",function(
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.replace"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>replace (template, dict, withPrefix)](#apidoc.element.utility2.istanbul.handlebars.replace)
- description and source-code
```javascript
replace = function (template, dict, withPrefix) {
<span class="apidocCodeCommentSpan">/*
 * this function will replace the keys in the template with the dict's key / value
 */
</span>    var value;
    // search for keys in the template
    return template.replace((/\{\{.+?\}\}/g), function (match0) {
        value = dict;
        // iteratively lookup nested values in the dict
        (withPrefix + match0.slice(2, -2)).split('.').forEach(function (key) {
            value = value && value[key];
        });
        return value === undefined
            ? match0
            : String(value);
    });
}
```
- example usage
```shell
...
    local.jslint.jslintAndPrint(
        document.querySelector('#inputTextareaEval1').value,
        'inputTextareaEval1.js'
    );
}
document.querySelector('#outputPreJslint1').textContent =
    local.jslint.errorText
    .replace((/\u001b\[\d+m/g), '')
    .trim();
// try to cleanup __coverage__
try {
    delete local.global.__coverage__['/inputTextareaEval1.js'];
} catch (ignore) {
}
// try to cover and eval input-code
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.show_code"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_code ()](#apidoc.element.utility2.istanbul.handlebars.show_code)
- description and source-code
```javascript
show_code = function () {
    try {
        return helper.apply(null, arguments);
    } catch (ignore) {
    }
}
```
- example usage
```shell
...
            }
        );
        result = local.handlebars.replace(result, dict, '');
        // show code last
        result = result.replace(
            '{{#show_code structured}}{{/show_code}}',
            function () {
                return local.handlebars.show_code(dict.structured);
            }
        );
        return result;
    };
};
local.handlebars.registerHelper = function (key, helper) {
/*
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.show_ignores"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_ignores ()](#apidoc.element.utility2.istanbul.handlebars.show_ignores)
- description and source-code
```javascript
show_ignores = function () {
    try {
        return helper.apply(null, arguments);
    } catch (ignore) {
    }
}
```
- example usage
```shell
...
        return local.handlebars.replace(match2, dict, match1 + '.');
    }
);
// render helper
result = result.replace(
    '{{#show_ignores metrics}}{{/show_ignores}}',
    function () {
        return local.handlebars.show_ignores(dict.metrics);
    }
);
result = result.replace('{{#show_line_execution_counts fileCoverage}}' +
    '{{maxLines}}{{/show_line_execution_counts}}', function () {
        return local.handlebars.show_line_execution_counts(
            dict.fileCoverage,
            { fn: function () {
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.show_line_execution_counts"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_line_execution_counts ()](#apidoc.element.utility2.istanbul.handlebars.show_line_execution_counts)
- description and source-code
```javascript
show_line_execution_counts = function () {
    try {
        return helper.apply(null, arguments);
    } catch (ignore) {
    }
}
```
- example usage
```shell
...
    '{{#show_ignores metrics}}{{/show_ignores}}',
    function () {
        return local.handlebars.show_ignores(dict.metrics);
    }
);
result = result.replace('{{#show_line_execution_counts fileCoverage}}' +
    '{{maxLines}}{{/show_line_execution_counts}}', function () {
        return local.handlebars.show_line_execution_counts(
            dict.fileCoverage,
            { fn: function () {
                return dict.maxLines;
            } }
        );
    });
result = result.replace(
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.show_lines"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_lines ()](#apidoc.element.utility2.istanbul.handlebars.show_lines)
- description and source-code
```javascript
show_lines = function () {
    try {
        return helper.apply(null, arguments);
    } catch (ignore) {
    }
}
```
- example usage
```shell
...
                return dict.maxLines;
            } }
        );
    });
result = result.replace(
    '{{#show_lines}}{{maxLines}}{{/show_lines}}',
    function () {
        return local.handlebars.show_lines({ fn: function () {
            return dict.maxLines;
        } });
    }
);
result = result.replace(
    '{{#show_picture}}{{metrics.statements.pct}}{{/show_picture}}',
    function () {
...
```

#### <a name="apidoc.element.utility2.istanbul.handlebars.show_picture"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.handlebars.</span>show_picture ()](#apidoc.element.utility2.istanbul.handlebars.show_picture)
- description and source-code
```javascript
show_picture = function () {
    try {
        return helper.apply(null, arguments);
    } catch (ignore) {
    }
}
```
- example usage
```shell
...
            return dict.maxLines;
        } });
    }
);
result = result.replace(
    '{{#show_picture}}{{metrics.statements.pct}}{{/show_picture}}',
    function () {
        return local.handlebars.show_picture({ fn: function () {
            return dict.metrics.statements.pct;
        } });
    }
);
result = local.handlebars.replace(result, dict, '');
// show code last
result = result.replace(
...
```



# <a name="apidoc.module.utility2.istanbul.require"></a>[module utility2.istanbul.require](#apidoc.module.utility2.istanbul.require)

#### <a name="apidoc.element.utility2.istanbul.require.require"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.</span>require (path)](#apidoc.element.utility2.istanbul.require.require)
- description and source-code
```javascript
function require(path) {
  try {
    exports.requireDepth += 1;
    return self.require(path);
  } finally {
    exports.requireDepth -= 1;
  }
}
```
- example usage
```shell
...
                return '';
            },
            stdout: {}
        }
        : local.process;
    require = function (key) {
        try {
            return local[key] || local.require(key);
        } catch (ignore) {
        }
    };
}());
...
```

#### <a name="apidoc.element.utility2.istanbul.require.resolve"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.require.</span>resolve (request)](#apidoc.element.utility2.istanbul.require.resolve)
- description and source-code
```javascript
function resolve(request) {
  return Module._resolveFilename(request, self);
}
```
- example usage
```shell
...
local.moduleDirname = function (module, modulePathList) {
/*
 * this function will search modulePathList for the module's __dirname
 */
    var result, tmp;
    // search process.cwd()
    if (!module || module === '.' || module.indexOf('/') >= 0) {
        return require('path').resolve(process.cwd(), module || '');
    }
    // search builtin
    if (Object.keys(process.binding('natives')).indexOf(module) >= 0) {
        return module;
    }
    // search modulePathList
    [
...
```



# <a name="apidoc.module.utility2.istanbul.util"></a>[module utility2.istanbul.util](#apidoc.module.utility2.istanbul.util)

#### <a name="apidoc.element.utility2.istanbul.util.inherits"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.util.</span>inherits ()](#apidoc.element.utility2.istanbul.util.inherits)
- description and source-code
```javascript
inherits = function () {
<span class="apidocCodeCommentSpan">/*
 * this function will do nothing
 */
</span>    return;
}
```
- example usage
```shell
...
:r+" branches"),i.join(", "))}),handlebars.registerHelper("show_lines",function(
e){var t=Number(e.fn(this)),n,r=[];for(n=0;n<t;n+=1)r[n]=n+1;return r.join("\n")
}),handlebars.registerHelper("show_line_execution_counts",function(e,t){var n=e.
l,r=Number(t.fn(this)),i,s,o=[],u,a="";for(i=0;i<r;i+=1)s=i+1,a="&nbsp;",u="neutral"
,n.hasOwnProperty(s)&&(n[s]>0?(u="yes",a=n[s]):u="no"),o.push('<span class="cline-any cline-'+
u+'">'+a+"</span>");return o.join("\n")}),handlebars.registerHelper("show_code",
function(e){var t=[];return e.forEach(function(e){t.push(customEscape(e.text)||"&nbsp;"
)}),t.join("\n")}),HtmlReport.TYPE="html",util.inherits(HtmlReport,Report),Report
.mix(HtmlReport,{getPathHtml:function(e,t){var n=e.parent,r=[],i=[],s;while(n)r.
push(n),n=n.parent;for(s=0;s<r.length;s+=1)i.push('<a href="'+t.ancestor(e,s+1)+'">'+
(r[s].relativeName||"All files")+"</a>");return i.reverse(),i.length>0?i.join(" &#187; "
)+" &#187; "+e.displayShortName():""},fillTemplate:function(e,t){var n=this.opts
,r=n.linkMapper;t.entity=e.name||"All files",t.metrics=e.metrics,t.reportClass=getReportClass
(e.metrics.statements,n.watermarks.statements),t.pathHtml=pathTemplate({html:this
.getPathHtml(e,r)}),t.prettify={js:r.asset(e,"prettify.js"),css:r.asset(e,"prettify.css"
...
```



# <a name="apidoc.module.utility2.istanbul.writer"></a>[module utility2.istanbul.writer](#apidoc.module.utility2.istanbul.writer)

#### <a name="apidoc.element.utility2.istanbul.writer.write"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.writer.</span>write (data)](#apidoc.element.utility2.istanbul.writer.write)
- description and source-code
```javascript
write = function (data) {
    local.writerData += data;
}
```
- example usage
```shell
...
local.fs = require('fs');
local.path = require('path');
// run the cli
if (module !== require.main || local.global.utility2_rollup) {
    break;
}
// jslint files
process.stdout.write(local.apidocCreate({
    dir: process.argv[2],
    modulePathList: module.paths,
    template: process.argv[3] === '--markdown'
        ? local.templateApidocMd
        : local.templateApidocHtml
}));
break;
...
```

#### <a name="apidoc.element.utility2.istanbul.writer.writeFile"></a>[function <span class="apidocSignatureSpan">utility2.istanbul.writer.</span>writeFile (file, onError)](#apidoc.element.utility2.istanbul.writer.writeFile)
- description and source-code
```javascript
writeFile = function (file, onError) {
    local.coverageReportHtml += local.writerData + '\n\n';
    if (local.writerFile) {
        local.fsWriteFileWithMkdirpSync2(local.writerFile, local.writerData);
    }
    local.writerData = '';
    local.writerFile = file;
    onError(local.writer);
}
```
- example usage
```shell
...
            onError();
        }
    );
    break;
case 'setItem':
    tmp = os.tmpdir() + '/' + Date.now() + Math.random();
    // save to tmp
    fs.writeFile(tmp, options.value, function (error) {
        // validate no error occurred
        console.assert(!error, error);
        // rename tmp to key
        fs.rename(
            tmp,
            storage + '/' + encodeURIComponent(String(options.key)),
            onError
...
```



# <a name="apidoc.module.utility2.jslint"></a>[module utility2.jslint](#apidoc.module.utility2.jslint)

#### <a name="apidoc.element.utility2.jslint.JSLINT"></a>[function <span class="apidocSignatureSpan">utility2.jslint.</span>JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT)
- description and source-code
```javascript
JSLINT = function (t, n){var r,o,u;S.errors=[],S.tree="",S.properties="",i=P=X=O=Object
.create(W["(begin)"]),V=[],_=Object.create(null),st(U),H=Object.create(null);if(
n){M=Object.create(n),o=M.predef;if(o)if(Array.isArray(o))for(r=0;r<o.length;r+=1
)_[o[r]]=!0;else typeof o=="object"&&st(o)}else M=Object.create(null);M.indent=+
M.indent||4,M.maxerr=+M.maxerr||50,b=q=Object.create(null),y=m={scope:q,loopage:0
,level:0},g=[m],s=[],f=[],l=!1,w=!1,E=null,x=!1,C=[],L=!1,D=!0,z=!1,$=null,J=0,T
.init(t),ot();try{dt();if(O.id==="(number)")O.stop("unexpected_a");else switch(O
.id){case"{":case"[":l=!0,x=!0,ln();break;default:bt(1),O.id===";"&&!L&&(O.edge=!0
,dt(";")),u=tn(),i.first=u,S.tree=i,u.disrupt&&P.warn("weird_program")}E=null,dt
("(end)"),S.property=H}catch(a){a&&S.errors.push({reason:a.message,line:a.line||
O.line,character:a.character||O.from},null)}return S.errors.length===0}
```
- example usage
```shell
...
                '\u001b[90m \/\/ Line ' + (error.line + 1) +
                ', Pos ' + (error.column + 1) + '\u001b[39m\n';
        });
// jslint es5 script
} else {
    // comment shebang
    scriptParsed = scriptParsed.replace((/^#!/), '//');
    if (local.JSLINT(scriptParsed)) {
        return script;
    }
    // if error occurred, then print colorized error messages
    local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
    local.JSLINT.errors
        .filter(function (error) {
            return error;
...
```

#### <a name="apidoc.element.utility2.jslint.jslintAndPrint"></a>[function <span class="apidocSignatureSpan">utility2.jslint.</span>jslintAndPrint (script, file)](#apidoc.element.utility2.jslint.jslintAndPrint)
- description and source-code
```javascript
jslintAndPrint = function (script, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will jslint / csslint the script and print any errors to stderr
 */
</span>    var ignoreDict, lineno, scriptParsed;
    // cleanup errors
    local.errorCounter = 0;
    local.errorText = '';
    // do nothing for empty script
    if (!script.length) {
        return script;
    }
    // init ignoreDict
    ignoreDict = {};
    // init lineno
    lineno = 0;
    // parse script
    scriptParsed = script
        // indent text-block
        // /* jslint-indent-begin */ ... /* jslint-indent-end */
        .replace(
/* jslint-indent-begin 20 */
(function () {
    /*jslint maxlen: 256*/
    return (/^ *?\/\* jslint-indent-begin (\d+?) \*\/$[\S\s]+?^ *?\/\* jslint-indent-end \*\/$/gm);
}()),
/* jslint-indent-end */
            function (match0, match1) {
                return match0.replace(
                    (/(^ *\S)/gm),
                    new Array(Number(match1) + 1).join(' ') + '$1'
                );
            }
        )
        // ignore text-block
        // /* jslint-ignore-begin */ ... /* jslint-ignore-end */
        .replace(
/* jslint-ignore-begin */
(/^ *?\/\* jslint-ignore-begin \*\/$[\S\s]+?^ *?\/\* jslint-ignore-end \*\/$/gm),
/* jslint-ignore-end */
            function (match0) {
                return match0.replace((/.*/g), '');
            }
        )
        // ignore next-line
        // /* jslint-ignore-next-line */
        .replace(
/* jslint-ignore-next-line */
(/^ *?\/\* jslint-ignore-next-line \*\/\n.*/gm),
            function (match0) {
                return match0.replace((/.*/g), '');
            }
        );
    // csslint script
    if (file.slice(-4) === '.css') {
        scriptParsed = scriptParsed.replace(new RegExp([
            // handle flexbox
            ' display: flex;',
            ' flex: .+?;',
            ' flex-.+?: .+?;'
        ].join('|'), 'g'), function () {
            return ' background: url(' + Math.random() + ');';
        });
        local.CSSLint.errors = local.CSSLint.verify(scriptParsed).messages
            .filter(function (error) {
                return !ignoreDict[error.rule.id];
            });
        // if error occurred, then print colorized error messages
        if (!local.CSSLint.errors.length) {
            return script;
        }
        local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
        local.CSSLint.errors
            .filter(function (error) {
                return error;
            })
            .forEach(function (error) {
                local.errorCounter += 1;
                lineno += 1;
                local.errorText +=
                    (' #' + String(lineno) + ' ').slice(-4) +
                    '\u001b[33m' + error.type + ' - ' + error.rule.id +
                    ' - ' + error.message + '\n    ' + error.rule.desc +
                    '\u001b[39m\n    ' + String(error.evidence).trim() +
                    '\u001b[90m \/\/ line ' + error.line +
                    ', col ' + error.col + '\u001b[39m\n';
            });
    // jslint es6-script
    } else if ((/^\/\*jslint\b[\s\w,:]*?\bes6: true\b/m)
            .test(scriptParsed.slice(0, 0x1000))) {
        // comment shebang
        scriptParsed = scriptParsed.replace((/^#!/), '//');
        local.jslintEs6.errors = local.jslintEs6(scriptParsed).warnings;
        if (!local.jslintEs6.errors.length) {
            return script;
        }
        // if error occurred, then print colorized error messages
        local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
        local.jslintEs6.errors
            .filter(function (error) {
                return error;
            })
            .forEach(function (error) {
                local.errorCounter += 1;
                lineno += 1;
                local.errorText +=
                    (' #' + String(lineno) + ' ').slice(-4) +
                    '\u001b[33m' + error.message +
                    '\u001b[39m\n    ' + String(error.a).trim() +
                    '\u001b[90m \/\/ Line ' + (error.line + 1) +
                    ', Pos ' + (error.column + 1) + '\u001 ...
```
- example usage
```shell
...
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
local.jslint.errorText = '';
if (document.querySelector('#inputTextareaEval1').value
        .indexOf('/*jslint') >= 0) {
    local.jslint.jslintAndPrint(
        document.querySelector('#inputTextareaEval1').value,
        'inputTextareaEval1.js'
    );
}
document.querySelector('#outputPreJslint1').textContent =
    local.jslint.errorText
    .replace((/\u001b\[\d+m/g), '')
...
```

#### <a name="apidoc.element.utility2.jslint.jslintEs6"></a>[function <span class="apidocSignatureSpan">utility2.jslint.</span>jslintEs6 (e, i, s)](#apidoc.element.utility2.jslint.jslintEs6)
- description and source-code
```javascript
jslintEs6 = function (e, i, s){try{ft=[],Y=i||t(),H="anonymous",j=[],F=t(),q=!0,I=[],R=!0,U=t(
),z=[],W=Y.fudge?1:0,V=[],$={id:"(global)",body:!0,context:t(),from:0,level:0,line
:0,live:[],loop:0,"switch":0,thru:0},B=$,X=$,J=!1,et=!1,Q=!1,G=$,Z=t(),tt=[],ot=
undefined,rt=$,it=0,at=undefined,n(F,a,!1),s!==undefined&&n(F,s,!1),Object.keys(
Y).forEach(function(e){if(Y[e]===!0){var t=r[e];Array.isArray(t)&&n(F,t,!1)}}),gt
(e),Et(),J?(ut=St(),Et("(end)")):(Y.browser?G.id===";"&&Et(";"):G.value==="use strict"&&
($.strict=G,Et("(string)"),Et(";")),ut=Ot(),Et("(end)"),X=$,on(ut),Q&&$.strict!==
undefined&&vt("unexpected_a",$.strict),gn(),Y.white||yn()),Y.browser||I.forEach(
function(e){e.directive==="global"&&vt("missing_browser",e)}),R=!1}catch(o){o.name!=="JSLintError"&&
ft.push(o)}return{directives:I,edition:"2016-10-24",exports:U,froms:z,functions:
V,global:$,id:"(JSLint)",json:J,lines:K,module:Q===!0,ok:ft.length===0&&!R,option
:Y,property:Z,stop:R,tokens:st,tree:ut,warnings:ft.sort(function(e,t){return e.line-
t.line||e.column-t.column})}}
```
- example usage
```shell
...
                ', col ' + error.col + '\u001b[39m\n';
        });
// jslint es6-script
} else if ((/^\/\*jslint\b[\s\w,:]*?\bes6: true\b/m)
        .test(scriptParsed.slice(0, 0x1000))) {
    // comment shebang
    scriptParsed = scriptParsed.replace((/^#!/), '//');
    local.jslintEs6.errors = local.jslintEs6(scriptParsed).warnings;
    if (!local.jslintEs6.errors.length) {
        return script;
    }
    // if error occurred, then print colorized error messages
    local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
    local.jslintEs6.errors
        .filter(function (error) {
...
```



# <a name="apidoc.module.utility2.jslint.CSSLint"></a>[module utility2.jslint.CSSLint](#apidoc.module.utility2.jslint.CSSLint)

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>_Reporter (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter)
- description and source-code
```javascript
function Reporter(e, t){this.messages=
[],this.stats=[],this.lines=e,this.ruleset=t}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.addFormatter"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>addFormatter (e)](#apidoc.element.utility2.jslint.CSSLint.addFormatter)
- description and source-code
```javascript
addFormatter = function (e){
t[e.id]=e}
```
- example usage
```shell
...
({id:"checkstyle-xml",name:"Checkstyle XML format",startFormat:function(){return'<?xml version="1.0" encoding="utf-8"?><checkstyle
>'
},endFormat:function(){return"</checkstyle>"},readError:function(t,n){return'<file name="'+
e(t)+'"><error line="0" column="0" severty="error" message="'+e(n)+'"></error></file>'
},formatResults:function(t,n,r){var i=t.messages,s=[],o=function(e){return!!e&&"name"in
e?"net.csslint."+e.name.replace(/\s/g,""):""};return i.length>0&&(s.push('<file name="'+
n+'">'),CSSLint.Util.forEach(i,function(t,n){t.rollup||s.push('<error line="'+t.
line+'" column="'+t.col+'" severity="'+t.type+'"'+' message="'+e(t.message)+'" source="'+
o(t.rule)+'"/>')}),s.push("</file>")),s.join("")}})}(),CSSLint.addFormatter({id:"compact"
,name:"Compact, 'porcelain' format",startFormat:function(){return""},endFormat:function(
){return""},formatResults:function(e,t,n){var r=e.messages,i="";n=n||{};var s=function(
e){return e.charAt(0).toUpperCase()+e.slice(1)};return r.length===0?n.quiet?"":t+": Lint Free!"
:(CSSLint.Util.forEach(r,function(e,n){e.rollup?i+=t+": "+s(e.type)+" - "+e.message+"\n"
:i+=t+": "+"line "+e.line+", col "+e.col+", "+s(e.type)+" - "+e.message+"\n"}),i
)}}),CSSLint.addFormatter({id:"csslint-xml",name:"CSSLint XML format",startFormat
:function(){return'<?xml version="1.0" encoding="utf-8"?><csslint>'},endFormat:function(
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.addRule"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>addRule (t )](#apidoc.element.utility2.jslint.CSSLint.addRule)
- description and source-code
```javascript
addRule = function (t ){e.push(t),e[t.id]=t}
```
- example usage
```shell
...
.push({type:"info",line:t,col:n,message:e,evidence:this.lines[t-1],rule:r})},rollupError
:function(e,t){this.messages.push({type:"error",rollup:!0,message:e,rule:t})},rollupWarn
:function(e,t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})},
stat:function(e,t){this.stats[e]=t}},CSSLint._Reporter=Reporter,CSSLint.Util={mix
:function(e,t){var n;for(n in t)t.hasOwnProperty(n)&&(e[n]=t[n]);return n},indexOf
:function(e,t){if(e.indexOf)return e.indexOf(t);for(var n=0,r=e.length;n<r;n++)if(
e[n]===t)return n;return-1},forEach:function(e,t){if(e.forEach)return e.forEach(
t);for(var n=0,r=e.length;n<r;n++)t(e[n],n,e)}},CSSLint.addRule({id:"adjoining-classes"
,name:"Disallow adjoining classes",desc:"Don't use adjoining classes.",browsers:"IE6"
,init:function(e,t){var n=this;e.addListener("startrule",function(r){var i=r.selectors
,s,o,u,a,f,l,c;for(f=0;f<i.length;f++){s=i[f];for(l=0;l<s.parts.length;l++){o=s.
parts[l];if(o.type==e.SELECTOR_PART_TYPE){a=0;for(c=0;c<o.modifiers.length;c++)u=
o.modifiers[c],u.type=="class"&&a++,a>1&&t.report("Don't use adjoining classes."
,o.line,o.col,n)}}}})}}),CSSLint.addRule({id:"box-model",name:"Beware of broken box size"
,desc:"Don't use width or height when using padding or border.",browsers:"All",init
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.clearRules"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>clearRules ()](#apidoc.element.utility2.jslint.CSSLint.clearRules)
- description and source-code
```javascript
clearRules = function (){e=[]}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.format"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>format (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint.format)
- description and source-code
```javascript
format = function (e, t, n, r){var i=
this.getFormatter(n),s=null;return i&&(s=i.startFormat(),s+=i.formatResults(e,t,
r||{}),s+=i.endFormat()),s}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.getFormatter"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getFormatter (e)](#apidoc.element.utility2.jslint.CSSLint.getFormatter)
- description and source-code
```javascript
getFormatter = function (e){return t[e]}
```
- example usage
```shell
...
:0,2:2,1:1,0:0},s.toLowerCase().split(",").forEach(function(e){var n=e.split(":"
),i=n[0]||"",s=n[1]||"";t[i.trim()]=r[s.trim()]})),t}var e=[],t=[],n=/\/\*csslint([^\*]*)\*\//
,r=new parserlib.util.EventTarget;return r.version="0.10.0",r.addRule=function(t
){e.push(t),e[t.id]=t},r.clearRules=function(){e=[]},r.getRules=function(){return[
].concat(e).sort(function(e,t){return e.id>t.id?1:0})},r.getRuleset=function(){var t=
{},n=0,r=e.length;while(n<r)t[e[n++].id]=1;return t},r.addFormatter=function(e){
t[e.id]=e},r.getFormatter=function(e){return t[e]},r.format=function(e,t,n,r){var i=
this.getFormatter(n),s=null;return i&&(s=i.startFormat(),s+=i.formatResults(e,t,
r||{}),s+=i.endFormat()),s},r.hasFormat=function(e){return t.hasOwnProperty(e)},
r.verify=function(t,r){var s=0,o=e.length,u,a,f,l=new parserlib.css.Parser({starHack
:!0,ieFilters:!0,underscoreHack:!0,strict:!1});a=t.replace(/\n\r?/g,"$split$").split
("$split$"),r||(r=this.getRuleset()),n.test(t)&&(r=i(t,r)),u=new Reporter(a,r),r
.errors=2;for(s in r)r.hasOwnProperty(s)&&r[s]&&e[s]&&e[s].init(l,u);try{l.parse
(t)}catch(c){u.error("Fatal error, cannot continue: "+c.message,c.line,c.col,{})
}return f={messages:u.messages,stats:u.stats,ruleset:u.ruleset},f.messages.sort(
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.getRules"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getRules ()](#apidoc.element.utility2.jslint.CSSLint.getRules)
- description and source-code
```javascript
getRules = function (){return[
].concat(e).sort(function(e,t){return e.id>t.id?1:0})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.getRuleset"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>getRuleset ()](#apidoc.element.utility2.jslint.CSSLint.getRuleset)
- description and source-code
```javascript
getRuleset = function (){var t=
{},n=0,r=e.length;while(n<r)t[e[n++].id]=1;return t}
```
- example usage
```shell
...
].concat(e).sort(function(e,t){return e.id>t.id?1:0})},r.getRuleset=function(){var t=
{},n=0,r=e.length;while(n<r)t[e[n++].id]=1;return t},r.addFormatter=function(e){
t[e.id]=e},r.getFormatter=function(e){return t[e]},r.format=function(e,t,n,r){var i=
this.getFormatter(n),s=null;return i&&(s=i.startFormat(),s+=i.formatResults(e,t,
r||{}),s+=i.endFormat()),s},r.hasFormat=function(e){return t.hasOwnProperty(e)},
r.verify=function(t,r){var s=0,o=e.length,u,a,f,l=new parserlib.css.Parser({starHack
:!0,ieFilters:!0,underscoreHack:!0,strict:!1});a=t.replace(/\n\r?/g,"$split$").split
("$split$"),r||(r=this.getRuleset()),n.test(t)&&(r=i(t,r)),u=new Reporter(a,r),r
.errors=2;for(s in r)r.hasOwnProperty(s)&&r[s]&&e[s]&&e[s].init(l,u);try{l.parse
(t)}catch(c){u.error("Fatal error, cannot continue: "+c.message,c.line,c.col,{})
}return f={messages:u.messages,stats:u.stats,ruleset:u.ruleset},f.messages.sort(
function(e,t){return e.rollup&&!t.rollup?1:!e.rollup&&t.rollup?-1:e.line-t.line}
),f},r}();return Reporter.prototype={constructor:Reporter,error:function(e,t,n,r
){this.messages.push({type:"error",line:t,col:n,message:e,evidence:this.lines[t-1
],rule:r||{}})},warn:function(e,t,n,r){this.report(e,t,n,r)},report:function(e,t
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.hasFormat"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>hasFormat (e)](#apidoc.element.utility2.jslint.CSSLint.hasFormat)
- description and source-code
```javascript
hasFormat = function (e){return t.hasOwnProperty(e)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint.verify"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint.</span>verify (t, r)](#apidoc.element.utility2.jslint.CSSLint.verify)
- description and source-code
```javascript
verify = function (t, r){var s=0,o=e.length,u,a,f,l=new parserlib.css.Parser({starHack
:!0,ieFilters:!0,underscoreHack:!0,strict:!1});a=t.replace(/\n\r?/g,"$split$").split
("$split$"),r||(r=this.getRuleset()),n.test(t)&&(r=i(t,r)),u=new Reporter(a,r),r
.errors=2;for(s in r)r.hasOwnProperty(s)&&r[s]&&e[s]&&e[s].init(l,u);try{l.parse
(t)}catch(c){u.error("Fatal error, cannot continue: "+c.message,c.line,c.col,{})
}return f={messages:u.messages,stats:u.stats,ruleset:u.ruleset},f.messages.sort(
function(e,t){return e.rollup&&!t.rollup?1:!e.rollup&&t.rollup?-1:e.line-t.line}
),f}
```
- example usage
```shell
...
    // handle flexbox
    ' display: flex;',
    ' flex: .+?;',
    ' flex-.+?: .+?;'
].join('|'), 'g'), function () {
    return ' background: url(' + Math.random() + ');';
});
local.CSSLint.errors = local.CSSLint.verify(scriptParsed).messages
    .filter(function (error) {
        return !ignoreDict[error.rule.id];
    });
// if error occurred, then print colorized error messages
if (!local.CSSLint.errors.length) {
    return script;
}
...
```



# <a name="apidoc.module.utility2.jslint.CSSLint._Reporter.prototype"></a>[module utility2.jslint.CSSLint._Reporter.prototype](#apidoc.module.utility2.jslint.CSSLint._Reporter.prototype)

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.constructor"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>constructor (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.constructor)
- description and source-code
```javascript
function Reporter(e, t){this.messages=
[],this.stats=[],this.lines=e,this.ruleset=t}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.error"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>error (e, t, n, r )](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.error)
- description and source-code
```javascript
error = function (e, t, n, r ){this.messages.push({type:"error",line:t,col:n,message:e,evidence:this.lines[t-1
],rule:r||{}})}
```
- example usage
```shell
...
            );
        eval(document.querySelector('#outputTextarea1').value);
        document.querySelector('#coverageReportDiv1').innerHTML =
            local.istanbul.coverageReportCreate({
                coverage: window.__coverage__
            });
    } catch (errorCaught) {
        console.error(errorCaught.stack);
    }
}
if (document.querySelector('#inputTextareaEval1') && (!event || (event &&
        event.currentTarget &&
        event.currentTarget.className &&
        event.currentTarget.className.includes &&
        event.currentTarget.className.includes('oneval')))) {
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.info"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>info (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.info)
- description and source-code
```javascript
info = function (e, t, n, r){this.messages
.push({type:"info",line:t,col:n,message:e,evidence:this.lines[t-1],rule:r})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.report"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>report (e, t , n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.report)
- description and source-code
```javascript
report = function (e, t , n, r){this.messages.push({type:this.ruleset[r.id]==2?"error":"warning",line:t,col
:n,message:e,evidence:this.lines[t-1],rule:r})}
```
- example usage
```shell
...
("$split$"),r||(r=this.getRuleset()),n.test(t)&&(r=i(t,r)),u=new Reporter(a,r),r
.errors=2;for(s in r)r.hasOwnProperty(s)&&r[s]&&e[s]&&e[s].init(l,u);try{l.parse
(t)}catch(c){u.error("Fatal error, cannot continue: "+c.message,c.line,c.col,{})
}return f={messages:u.messages,stats:u.stats,ruleset:u.ruleset},f.messages.sort(
function(e,t){return e.rollup&&!t.rollup?1:!e.rollup&&t.rollup?-1:e.line-t.line}
),f},r}();return Reporter.prototype={constructor:Reporter,error:function(e,t,n,r
){this.messages.push({type:"error",line:t,col:n,message:e,evidence:this.lines[t-1
],rule:r||{}})},warn:function(e,t,n,r){this.report(e,t,n,r)},report:function(e,t
,n,r){this.messages.push({type:this.ruleset[r.id]==2?"error":"warning",line:t,col
:n,message:e,evidence:this.lines[t-1],rule:r})},info:function(e,t,n,r){this.messages
.push({type:"info",line:t,col:n,message:e,evidence:this.lines[t-1],rule:r})},rollupError
:function(e,t){this.messages.push({type:"error",rollup:!0,message:e,rule:t})},rollupWarn
:function(e,t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})},
stat:function(e,t){this.stats[e]=t}},CSSLint._Reporter=Reporter,CSSLint.Util={mix
:function(e,t){var n;for(n in t)t.hasOwnProperty(n)&&(e[n]=t[n]);return n},indexOf
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupError"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>rollupError (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupError)
- description and source-code
```javascript
rollupError = function (e, t){this.messages.push({type:"error",rollup:!0,message:e,rule:t})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupWarn"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>rollupWarn (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.rollupWarn)
- description and source-code
```javascript
rollupWarn = function (e, t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})}
```
- example usage
```shell
...
a<l)u[a].type=="color"&&("alpha"in u[a]||"hue"in u[a]?(/([^\)]+)\(/.test(u[a])&&
(f=RegExp.$1.toUpperCase()),(!r||r.property.text.toLowerCase()!=o||r.colorType!="compat"
)&&t.report("Fallback "+o+" (hex or RGB) should precede "+f+" "+o+".",e.line,e.col
,n)):e.colorType="compat"),a++;r=e})}}),CSSLint.addRule({id:"floats",name:"Disallow too many floats"
,desc:"This rule tests if the float property is used too many times",browsers:"All"
,init:function(e,t){var n=this,r=0;e.addListener("property",function(e){e.property
.text.toLowerCase()=="float"&&e.value.text.toLowerCase()!="none"&&r++}),e.addListener
("endstylesheet",function(){t.stat("floats",r),r>=10&&t.rollupWarn("Too many floats ("+
r+"), you're probably using them for layout. Consider using a grid system instead."
,n)})}}),CSSLint.addRule({id:"font-faces",name:"Don't use too many web fonts",desc
:"Too many different web fonts in the same stylesheet.",browsers:"All",init:function(
e,t){var n=this,r=0;e.addListener("startfontface",function(){r++}),e.addListener
("endstylesheet",function(){r>5&&t.rollupWarn("Too many @font-face declarations ("+
r+").",n)})}}),CSSLint.addRule({id:"font-sizes",name:"Disallow too many font sizes"
,desc:"Checks the number of font-size declarations.",browsers:"All",init:function(
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.stat"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>stat (e, t)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.stat)
- description and source-code
```javascript
stat = function (e, t){this.stats[e]=t}
```
- example usage
```shell
...
a<l)u[a].type=="color"&&("alpha"in u[a]||"hue"in u[a]?(/([^\)]+)\(/.test(u[a])&&
(f=RegExp.$1.toUpperCase()),(!r||r.property.text.toLowerCase()!=o||r.colorType!="compat"
)&&t.report("Fallback "+o+" (hex or RGB) should precede "+f+" "+o+".",e.line,e.col
,n)):e.colorType="compat"),a++;r=e})}}),CSSLint.addRule({id:"floats",name:"Disallow too many floats"
,desc:"This rule tests if the float property is used too many times",browsers:"All"
,init:function(e,t){var n=this,r=0;e.addListener("property",function(e){e.property
.text.toLowerCase()=="float"&&e.value.text.toLowerCase()!="none"&&r++}),e.addListener
("endstylesheet",function(){t.stat("floats",r),r>=10&&t.rollupWarn("Too many floats ("+
r+"), you're probably using them for layout. Consider using a grid system instead."
,n)})}}),CSSLint.addRule({id:"font-faces",name:"Don't use too many web fonts",desc
:"Too many different web fonts in the same stylesheet.",browsers:"All",init:function(
e,t){var n=this,r=0;e.addListener("startfontface",function(){r++}),e.addListener
("endstylesheet",function(){r>5&&t.rollupWarn("Too many @font-face declarations ("+
r+").",n)})}}),CSSLint.addRule({id:"font-sizes",name:"Disallow too many font sizes"
,desc:"Checks the number of font-size declarations.",browsers:"All",init:function(
...
```

#### <a name="apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.warn"></a>[function <span class="apidocSignatureSpan">utility2.jslint.CSSLint._Reporter.prototype.</span>warn (e, t, n, r)](#apidoc.element.utility2.jslint.CSSLint._Reporter.prototype.warn)
- description and source-code
```javascript
warn = function (e, t, n, r){this.report(e,t,n,r)}
```
- example usage
```shell
...
),M.rhino&&(st(I),M.rhino=!1)}function ut(e){return e||(e=O),e.id==="(number)"?e
.number:e.string}function at(e,t,n){throw{name:"JSLintError",line:t,character:n,
message:u.scanned_a_b.supplant({a:u[e]||e,b:Math.floor(t/N.length*100)})}}function ft
(e,t,n,r,i,s,o){var a={id:"(error)",raw:u[e]||e,code:e,evidence:N[t-1]||"",line:
t,character:n,a:r||ut(this),b:i,c:s,d:o};return a.reason=a.raw.supplant(a),S.errors
.push(a),M.passfail&&at("stopping",t,n),J+=1,J>=M.maxerr&&at("too_many",t,n),a}function lt
(e,t,n,r,i,s,o){var u=ft(e,t,n,r,i,s,o);at("stopping",u.line,u.character)}function ct
(e){!M.white&&O.from!==e&&O.warn("expected_a_at_b_c","",e,O.from)}function ht(e,
t){var n=t.string,r=q[n];t.dead=!1,t.init=!1,t.kind=e,t.master=r,t.used=0,t.writeable=!0
,e==="var"&&m===y?r||(_[n]===!1&&(t.writeable=!1),b[n]=t):(r&&(r.function===m?(r
.kind!=="exception"||e!=="exception"||!r.dead)&&t.warn("already_defined",n):r.function!==
y&&e==="var"&&t.warn("redefinition_a_b",n,r.line)),q[n]=t,e==="var"&&s.push(n))}
function pt(e){var t,n=0;e=e||0;while(n<=e)t=C[n],t||(t=C[n]=T.token()),n+=1;return t
}function dt(e,t){if(E){if($&&O.line!==X.line){if(($!==E||!O.edge)&&O.from===E.at-
(O.edge?M.indent:0)){var r=E;for(;;){r.at-=M.indent;if(r===$)break;r=r.was}r.open=!1
...
```



# <a name="apidoc.module.utility2.jslint.JSLINT"></a>[module utility2.jslint.JSLINT](#apidoc.module.utility2.jslint.JSLINT)

#### <a name="apidoc.element.utility2.jslint.JSLINT.JSLINT"></a>[function <span class="apidocSignatureSpan">utility2.jslint.</span>JSLINT (t, n)](#apidoc.element.utility2.jslint.JSLINT.JSLINT)
- description and source-code
```javascript
JSLINT = function (t, n){var r,o,u;S.errors=[],S.tree="",S.properties="",i=P=X=O=Object
.create(W["(begin)"]),V=[],_=Object.create(null),st(U),H=Object.create(null);if(
n){M=Object.create(n),o=M.predef;if(o)if(Array.isArray(o))for(r=0;r<o.length;r+=1
)_[o[r]]=!0;else typeof o=="object"&&st(o)}else M=Object.create(null);M.indent=+
M.indent||4,M.maxerr=+M.maxerr||50,b=q=Object.create(null),y=m={scope:q,loopage:0
,level:0},g=[m],s=[],f=[],l=!1,w=!1,E=null,x=!1,C=[],L=!1,D=!0,z=!1,$=null,J=0,T
.init(t),ot();try{dt();if(O.id==="(number)")O.stop("unexpected_a");else switch(O
.id){case"{":case"[":l=!0,x=!0,ln();break;default:bt(1),O.id===";"&&!L&&(O.edge=!0
,dt(";")),u=tn(),i.first=u,S.tree=i,u.disrupt&&P.warn("weird_program")}E=null,dt
("(end)"),S.property=H}catch(a){a&&S.errors.push({reason:a.message,line:a.line||
O.line,character:a.character||O.from},null)}return S.errors.length===0}
```
- example usage
```shell
...
                '\u001b[90m \/\/ Line ' + (error.line + 1) +
                ', Pos ' + (error.column + 1) + '\u001b[39m\n';
        });
// jslint es5 script
} else {
    // comment shebang
    scriptParsed = scriptParsed.replace((/^#!/), '//');
    if (local.JSLINT(scriptParsed)) {
        return script;
    }
    // if error occurred, then print colorized error messages
    local.errorText = '\n\u001b[1m' + file + '\u001b[22m\n';
    local.JSLINT.errors
        .filter(function (error) {
            return error;
...
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.color"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>color (e)](#apidoc.element.utility2.jslint.JSLINT.color)
- description and source-code
```javascript
color = function (e){var t,n=1,r,i,s=[],o,u=e.tokens[0];
while(u&&u.id!=="(end)"){t=u.from,i=u.line,o=u.thru,r=u.function.level;do o=u.thru
,u=e.tokens[n],n+=1;while(u&&u.line===i&&u.from-o<5&&r===u.function.level);s.push
({line:i,level:r,from:t,thru:o})}return s}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.data"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>data ( )](#apidoc.element.utility2.jslint.JSLINT.data)
- description and source-code
```javascript
data = function ( ){function s(e){var n=i[e].kind;switch(n){case"var":case"exception":case"label":
t[n].push(e)}}var e={functions:[]},t,n,r,i;e.errors=S.errors,e.json=x,e.global=cn
(Object.keys(b));for(n=1;n<g.length;n+=1)r=g[n],t={name:r.name,line:r.line,level
:r.level,parameter:r.parameter,"var":[],exception:[],closure:cn(r.closure),outer
:cn(r.outer),global:cn(r.global),label:[]},i=r.scope,Object.keys(i).forEach(s),t
.var.sort(),t.exception.sort(),t.label.sort(),e.functions.push(t);return e.tokens=
V,e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.error_report"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>error_report (e)](#apidoc.element.utility2.jslint.JSLINT.error_report)
- description and source-code
```javascript
error_report = function (e){var t,n,r=[],i;if(e.errors.length){e.json&&r.push
("<cite>JSON: bad.</cite><br>");for(n=0;n<e.errors.length;n+=1)i=e.errors[n],i&&
(t=i.evidence||"",r.push("<cite>"),isFinite(i.line)&&r.push("<address>line "+String
(i.line)+" character "+String(i.character)+"</address>"),r.push(i.reason.entityify
()+"</cite>"),t&&r.push("<pre>"+t.entityify()+"</pre>"))}return r.join("")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.jslint"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>jslint (t, n)](#apidoc.element.utility2.jslint.JSLINT.jslint)
- description and source-code
```javascript
jslint = function (t, n){var r,o,u;S.errors=[],S.tree="",S.properties="",i=P=X=O=Object
.create(W["(begin)"]),V=[],_=Object.create(null),st(U),H=Object.create(null);if(
n){M=Object.create(n),o=M.predef;if(o)if(Array.isArray(o))for(r=0;r<o.length;r+=1
)_[o[r]]=!0;else typeof o=="object"&&st(o)}else M=Object.create(null);M.indent=+
M.indent||4,M.maxerr=+M.maxerr||50,b=q=Object.create(null),y=m={scope:q,loopage:0
,level:0},g=[m],s=[],f=[],l=!1,w=!1,E=null,x=!1,C=[],L=!1,D=!0,z=!1,$=null,J=0,T
.init(t),ot();try{dt();if(O.id==="(number)")O.stop("unexpected_a");else switch(O
.id){case"{":case"[":l=!0,x=!0,ln();break;default:bt(1),O.id===";"&&!L&&(O.edge=!0
,dt(";")),u=tn(),i.first=u,S.tree=i,u.disrupt&&P.warn("weird_program")}E=null,dt
("(end)"),S.property=H}catch(a){a&&S.errors.push({reason:a.message,line:a.line||
O.line,character:a.character||O.from},null)}return S.errors.length===0}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.properties_report"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>properties_report (e)](#apidoc.element.utility2.jslint.JSLINT.properties_report)
- description and source-code
```javascript
properties_report = function (e){if(!
e)return"";var t,n,r=Object.keys(e).sort(),i="   ",s,o=!1,u=["/*properties"];for(
t=0;t<r.length;t+=1)n=r[t],e[n]>0&&(o&&(i+=","),s=G.test(n)?n:"'"+n.replace(et,it
)+"'",i.length+s.length>=80?(u.push(i),i="    "):i+=" ",i+=s,o=!0);return u.push
(i,"*/\n"),u.join("\n")}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.jslint.JSLINT.report"></a>[function <span class="apidocSignatureSpan">utility2.jslint.JSLINT.</span>report (e)](#apidoc.element.utility2.jslint.JSLINT.report)
- description and source-code
```javascript
report = function (e){function u(e,t){var n=!1;t.length&&(s.push("<dt>"+e+"</dt><dd>"),t.forEach
(function(e){s.push((n?", ":"")+e),n=!0}),s.push("</dd>"))}var t,n,r,i,s=[],o;s.
push("<dl class=level0>"),e.global.length?(u("global",e.global),t=!0):e.json?e.errors
.length||s.push("<dt>JSON: good.</dt>"):s.push("<dt><i>No new global variables introduced.</i></dt>"
),t?s.push("</dl>"):s[0]="";if(e.functions)for(n=0;n<e.functions.length;n+=1){o=
e.functions[n],i=[];if(o.params)for(r=0;r<o.params.length;r+=1)i[r]=o.params[r].
string;s.push("<dl class=level"+o.level+"><address>line "+String(o.line)+"</address>"+
o.name.entityify()),u("parameter",o.parameter),u("variable",o.var),u("exception"
,o.exception),u("closure",o.closure),u("outer",o.outer),u("global",o.global),u("label"
,o.label),s.push("</dl>")}return s.join("")}
```
- example usage
```shell
...
("$split$"),r||(r=this.getRuleset()),n.test(t)&&(r=i(t,r)),u=new Reporter(a,r),r
.errors=2;for(s in r)r.hasOwnProperty(s)&&r[s]&&e[s]&&e[s].init(l,u);try{l.parse
(t)}catch(c){u.error("Fatal error, cannot continue: "+c.message,c.line,c.col,{})
}return f={messages:u.messages,stats:u.stats,ruleset:u.ruleset},f.messages.sort(
function(e,t){return e.rollup&&!t.rollup?1:!e.rollup&&t.rollup?-1:e.line-t.line}
),f},r}();return Reporter.prototype={constructor:Reporter,error:function(e,t,n,r
){this.messages.push({type:"error",line:t,col:n,message:e,evidence:this.lines[t-1
],rule:r||{}})},warn:function(e,t,n,r){this.report(e,t,n,r)},report:function(e,t
,n,r){this.messages.push({type:this.ruleset[r.id]==2?"error":"warning",line:t,col
:n,message:e,evidence:this.lines[t-1],rule:r})},info:function(e,t,n,r){this.messages
.push({type:"info",line:t,col:n,message:e,evidence:this.lines[t-1],rule:r})},rollupError
:function(e,t){this.messages.push({type:"error",rollup:!0,message:e,rule:t})},rollupWarn
:function(e,t){this.messages.push({type:"warning",rollup:!0,message:e,rule:t})},
stat:function(e,t){this.stats[e]=t}},CSSLint._Reporter=Reporter,CSSLint.Util={mix
:function(e,t){var n;for(n in t)t.hasOwnProperty(n)&&(e[n]=t[n]);return n},indexOf
...
```



# <a name="apidoc.module.utility2.sjcl"></a>[module utility2.sjcl](#apidoc.module.utility2.sjcl)

#### <a name="apidoc.element.utility2.sjcl.decrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.</span>decrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.decrypt)
- description and source-code
```javascript
decrypt = function (e, t, n, r){var i=sjcl.json;return i.X(e,i.decode(t),n,r)}
```
- example usage
```shell
...
;o+4<t.length;o+=4)c=t.slice(o,o+4),l=f(l,c),h=h.concat(f(n,e.encrypt(f(n,c)))),
n=u(n);return c=t.slice(o),t=a.bitLength(c),o=e.encrypt(f(n,[0,0,0,t])),c=a.clamp
(f(c.concat([0,0,0]),o),t),l=f(l,f(c.concat([0,0,0]),o)),l=e.encrypt(f(l,f(n,u(n
)))),r.length&&(l=f(l,s?r:sjcl.mode.ocb2.pmac(e,r))),h.concat(a.concat(c,a.clamp
(l,i)))},decrypt:function(e,t,n,r,i,s){128!==sjcl.bitArray.bitLength(n)&&q(new sjcl
.exception.invalid("ocb iv must be 128 bits")),i=i||64;var o=sjcl.mode.ocb2.H,u=
sjcl.bitArray,a=u.l,f=[0,0,0,0],l=o(e.encrypt(n)),c,h,p=sjcl.bitArray.bitLength(
t)-i,d=[];r=r||[];for(n=0;n+4<p/32;n+=4)c=a(l,e.decrypt(a(l,t.slice(n,n+4)))),f=
a(f,c),d=d.concat(c),l=o(l);return h=p-32*n,c=e.encrypt(a(l,[0,0,0,h])),c=a(c,u.
clamp(t.slice(n),h).concat([0,0,0])),f=a(f,c),f=e.encrypt(a(f,a(l,o(l)))),r.length&&
(f=a(f,s?r:sjcl.mode.ocb2.pmac(e,r))),u.equal(u.clamp(f,i),u.bitSlice(t,p))||q(new
sjcl.exception.corrupt("ocb: tag doesn't match")),d.concat(u.clamp(c,h))},pmac:function(
e,t){var n,r=sjcl.mode.ocb2.H,i=sjcl.bitArray,s=i.l,o=[0,0,0,0],u=e.encrypt([0,0
,0,0]),u=s(u,r(r(u)));for(n=0;n+4<t.length;n+=4)u=r(u),o=s(o,e.encrypt(s(u,t.slice
(n,n+4))));return n=t.slice(n),128>i.bitLength(n)&&(u=s(u,r(u)),n=i.concat(n,[-2147483648
...
```

#### <a name="apidoc.element.utility2.sjcl.encrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.</span>encrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.encrypt)
- description and source-code
```javascript
encrypt = function (e, t, n, r){var i=sjcl.json,s=i.Y.apply(i,arguments);return i
.encode(s)}
```
- example usage
```shell
...
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
...
```

#### <a name="apidoc.element.utility2.sjcl.prng"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.</span>prng (e)](#apidoc.element.utility2.sjcl.prng)
- description and source-code
```javascript
prng = function (e){this.c=[new sjcl.hash.sha256
],this.i=[0],this.F=0,this.s={},this.C=0,this.K={},this.O=this.d=this.j=this.W=0
,this.b=[0,0,0,0,0,0,0,0],this.f=[0,0,0,0],this.A=s,this.B=e,this.q=u,this.w={progress
:{},seeded:{}},this.m=this.V=0,this.t=1,this.u=2,this.S=65536,this.I=[0,48,64,96
,128,192,256,384,512,768,1024],this.T=3e4,this.R=80}
```
- example usage
```shell
...
s[n],delete i[r]},$:function(){E(1)},ba:function(e){var t,n;try{t=e.x||e.clientX||
e.offsetX||0,n=e.y||e.clientY||e.offsetY||0}catch(r){n=t=0}0!=t&&0!=n&&sjcl.random
.addEntropy([t,n],2,"mouse"),E(0)},da:function(e){e=e.touches[0]||e.changedTouches
[0],sjcl.random.addEntropy([e.pageX||e.clientX,e.pageY||e.clientY],1,"touch"),E(0
)},aa:function(){E(2)},U:function(e){e=e.accelerationIncludingGravity.x||e.accelerationIncludingGravity
.y||e.accelerationIncludingGravity.z;if(window.orientation){var t=window.orientation
;"number"==typeof t&&sjcl.random.addEntropy(t,1,"accelerometer")}e&&sjcl.random.
addEntropy(e,2,"accelerometer"),E(0)}},sjcl.random=new sjcl.prng(6);e:try{var F,
G,H,I;if(I="undefined"!=typeof module){var J;if(J=module.exports){var K;try{K=require
("crypto")}catch(L){K=null}J=(G=K)&&G.randomBytes}I=J}if(I)F=G.randomBytes(128),
F=new Uint32Array((new Uint8Array(F)).buffer),sjcl.random.addEntropy(F,1024,"crypto['randomBytes']"
);else if("undefined"!=typeof window&&"undefined"!=typeof Uint32Array){H=new Uint32Array
(32);if(window.crypto&&window.crypto.getRandomValues)window.crypto.getRandomValues
(H);else{if(!window.msCrypto||!window.msCrypto.getRandomValues)break e;window.msCrypto
.getRandomValues(H)}sjcl.random.addEntropy(H,1024,"crypto['getRandomValues']")}}
...
```



# <a name="apidoc.module.utility2.sjcl.bitArray"></a>[module utility2.sjcl.bitArray](#apidoc.module.utility2.sjcl.bitArray)

#### <a name="apidoc.element.utility2.sjcl.bitArray.P"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>P (e, t, n, r)](#apidoc.element.utility2.sjcl.bitArray.P)
- description and source-code
```javascript
P = function (e, t, n, r){var i;i=0;for(r===s&&(r=[]);32<=t;t-=32)r.push
(n),n=0;if(0===t)return r.concat(e);for(i=0;i<e.length;i++)r.push(n|e[i]>>>t),n=
e[i]<<32-t;return i=e.length?e[e.length-1]:0,e=sjcl.bitArray.getPartial(i),r.push
(sjcl.bitArray.partial(t+e&31,32<t+e?n:r.pop(),1)),r}
```
- example usage
```shell
...
.cipher.aes.prototype={encrypt:function(e){return w(this,e,0)},decrypt:function(
e){return w(this,e,1)},k:[[[],[],[],[],[]],[[],[],[],[],[]]],D:function(){var e=
this.k[0],t=this.k[1],n=e[4],r=t[4],i,s,o,u=[],a=[],f,l,c,h;for(i=0;256>i;i++)a[
(u[i]=i<<1^283*(i>>7))^i]=i;for(s=o=0;!n[s];s^=f||1,o=a[o]||1){c=o^o<<1^o<<2^o<<3^
o<<4,c=c>>8^c&255^99,n[s]=c,r[c]=s,l=u[i=u[f=u[s]]],h=16843009*l^65537*i^257*f^16843008*
s,l=257*u[c]^16843008*c;for(i=0;4>i;i++)e[i][s]=l=l<<24^l>>>8,t[i][c]=h=h<<24^h>>>8
}for(i=0;5>i;i++)e[i]=e[i].slice(0),t[i]=t[i].slice(0)}},sjcl.bitArray={bitSlice
:function(e,t,n){return e=sjcl.bitArray.P(e.slice(t/32),32-(t&31)).slice(1),n===
s?e:sjcl.bitArray.clamp(e,n-t)},extract:function(e,t,n){var r=Math.floor(-t-n&31
);return((t+n-1^t)&-32?e[t/32|0]<<32-r^e[t/32+1|0]>>>r:e[t/32|0]>>>r)&(1<<n)-1},
concat:function(e,t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))},bitLength:function(e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])},clamp:function(e,t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.bitLength"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>bitLength (e)](#apidoc.element.utility2.sjcl.bitArray.bitLength)
- description and source-code
```javascript
bitLength = function (e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])}
```
- example usage
```shell
...
concat:function(e,t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))},bitLength:function(e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])},clamp:function(e,t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
]=sjcl.bitArray.partial(t,e[n-1]&2147483648>>t-1,1)),e},partial:function(e,t,n){
return 32===e?t:(n?t|0:t<<32-e)+1099511627776*e},getPartial:function(e){return Math
.round(e/1099511627776)||32},equal:function(e,t){if(sjcl.bitArray.bitLength(e)!==
sjcl.bitArray.bitLength(t))return u;var n=0,r;for(r=0;r<e.length;r++)n|=e[r]^t[r
];return 0===n},P:function(e,t,n,r){var i;i=0;for(r===s&&(r=[]);32<=t;t-=32)r.push
(n),n=0;if(0===t)return r.concat(e);for(i=0;i<e.length;i++)r.push(n|e[i]>>>t),n=
e[i]<<32-t;return i=e.length?e[e.length-1]:0,e=sjcl.bitArray.getPartial(i),r.push
(sjcl.bitArray.partial(t+e&31,32<t+e?n:r.pop(),1)),r},l:function(e,t){return[e[0
]^t[0],e[1]^t[1],e[2]^t[2],e[3]^t[3]]},byteswapM:function(e){var t,n;for(t=0;t<e
.length;++t)n=e[t],e[t]=n>>>24|n>>>8&65280|(n&65280)<<8|n<<24;return e}},sjcl.codec
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.bitSlice"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>bitSlice (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.bitSlice)
- description and source-code
```javascript
bitSlice = function (e, t, n){return e=sjcl.bitArray.P(e.slice(t/32),32-(t&31)).slice(1),n===
s?e:sjcl.bitArray.clamp(e,n-t)}
```
- example usage
```shell
...
;r*r<=n;r++)if(0===n%r)continue e;8>t&&(this.N[t]=e(Math.pow(n,.5))),this.b[t]=e
(Math.pow(n,1/3)),t++}}},sjcl.mode.ccm={name:"ccm",encrypt:function(e,t,n,r,i){var s
,o=t.slice(0),u=sjcl.bitArray,a=u.bitLength(n)/8,f=u.bitLength(o)/8;i=i||64,r=r||
[],7>a&&q(new sjcl.exception.invalid("ccm: iv must be at least 7 bytes"));for(s=2
;4>s&&f>>>8*s;s++);return s<15-a&&(s=15-a),n=u.clamp(n,8*(15-s)),t=sjcl.mode.ccm
.L(e,t,n,r,i,s),o=sjcl.mode.ccm.p(e,o,n,t,i,s),u.concat(o.data,o.tag)},decrypt:function(
e,t,n,r,i){i=i||64,r=r||[];var s=sjcl.bitArray,o=s.bitLength(n)/8,u=s.bitLength(
t),a=s.clamp(t,u-i),f=s.bitSlice(t,u-i),u=(u-i)/8;7>o&&q(new sjcl.exception.invalid
("ccm: iv must be at least 7 bytes"));for(t=2;4>t&&u>>>8*t;t++);return t<15-o&&(
t=15-o),n=s.clamp(n,8*(15-t)),a=sjcl.mode.ccm.p(e,a,n,f,i,t),e=sjcl.mode.ccm.L(e
,a.data,n,r,i,t),s.equal(a.tag,e)||q(new sjcl.exception.corrupt("ccm: tag doesn't match"
)),a.data},L:function(e,t,n,r,i,s){var o=[],u=sjcl.bitArray,a=u.l;i/=8,(i%2||4>i||16<
i)&&q(new sjcl.exception.invalid("ccm: invalid tag length")),(4294967295<r.length||4294967295<
t.length)&&q(new sjcl.exception.bug("ccm: can't deal with 4GiB or more data")),s=
[u.partial(8,(r.length?64:0)|i-2<<2|s-1)],s=u.concat(s,n),s[3]|=u.bitLength(t)/8
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.byteswapM"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>byteswapM (e)](#apidoc.element.utility2.sjcl.bitArray.byteswapM)
- description and source-code
```javascript
byteswapM = function (e){var t,n;for(t=0;t<e
.length;++t)n=e[t],e[t]=n>>>24|n>>>8&65280|(n&65280)<<8|n<<24;return e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.clamp"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>clamp (e, t)](#apidoc.element.utility2.sjcl.bitArray.clamp)
- description and source-code
```javascript
clamp = function (e, t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
]=sjcl.bitArray.partial(t,e[n-1]&2147483648>>t-1,1)),e}
```
- example usage
```shell
...
e){return w(this,e,1)},k:[[[],[],[],[],[]],[[],[],[],[],[]]],D:function(){var e=
this.k[0],t=this.k[1],n=e[4],r=t[4],i,s,o,u=[],a=[],f,l,c,h;for(i=0;256>i;i++)a[
(u[i]=i<<1^283*(i>>7))^i]=i;for(s=o=0;!n[s];s^=f||1,o=a[o]||1){c=o^o<<1^o<<2^o<<3^
o<<4,c=c>>8^c&255^99,n[s]=c,r[c]=s,l=u[i=u[f=u[s]]],h=16843009*l^65537*i^257*f^16843008*
s,l=257*u[c]^16843008*c;for(i=0;4>i;i++)e[i][s]=l=l<<24^l>>>8,t[i][c]=h=h<<24^h>>>8
}for(i=0;5>i;i++)e[i]=e[i].slice(0),t[i]=t[i].slice(0)}},sjcl.bitArray={bitSlice
:function(e,t,n){return e=sjcl.bitArray.P(e.slice(t/32),32-(t&31)).slice(1),n===
s?e:sjcl.bitArray.clamp(e,n-t)},extract:function(e,t,n){var r=Math.floor(-t-n&31
);return((t+n-1^t)&-32?e[t/32|0]<<32-r^e[t/32+1|0]>>>r:e[t/32|0]>>>r)&(1<<n)-1},
concat:function(e,t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))},bitLength:function(e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])},clamp:function(e,t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
]=sjcl.bitArray.partial(t,e[n-1]&2147483648>>t-1,1)),e},partial:function(e,t,n){
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.concat"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>concat (e, t)](#apidoc.element.utility2.sjcl.bitArray.concat)
- description and source-code
```javascript
concat = function (e, t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))}
```
- example usage
```shell
...
    exampleList: [],
    html: '',
    moduleDict: {},
    moduleExtraDict: {},
    template: local.templateApidocHtml
});
// init exampleList
options.exampleList = options.exampleList.concat(options.exampleFileList.concat(
    local.fs.readdirSync(options.dir)
        .sort()
        .filter(function (file) {
            return file.indexOf(options.env.npm_package_main) === 0 ||
                (/^(?:readme)\b/i).test(file) ||
                (/^(?:index|lib|test)\b.*\.js$/i).test(file);
        })
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.equal"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>equal (e, t)](#apidoc.element.utility2.sjcl.bitArray.equal)
- description and source-code
```javascript
equal = function (e, t){if(sjcl.bitArray.bitLength(e)!==
sjcl.bitArray.bitLength(t))return u;var n=0,r;for(r=0;r<e.length;r++)n|=e[r]^t[r
];return 0===n}
```
- example usage
```shell
...
[],7>a&&q(new sjcl.exception.invalid("ccm: iv must be at least 7 bytes"));for(s=2
;4>s&&f>>>8*s;s++);return s<15-a&&(s=15-a),n=u.clamp(n,8*(15-s)),t=sjcl.mode.ccm
.L(e,t,n,r,i,s),o=sjcl.mode.ccm.p(e,o,n,t,i,s),u.concat(o.data,o.tag)},decrypt:function(
e,t,n,r,i){i=i||64,r=r||[];var s=sjcl.bitArray,o=s.bitLength(n)/8,u=s.bitLength(
t),a=s.clamp(t,u-i),f=s.bitSlice(t,u-i),u=(u-i)/8;7>o&&q(new sjcl.exception.invalid
("ccm: iv must be at least 7 bytes"));for(t=2;4>t&&u>>>8*t;t++);return t<15-o&&(
t=15-o),n=s.clamp(n,8*(15-t)),a=sjcl.mode.ccm.p(e,a,n,f,i,t),e=sjcl.mode.ccm.L(e
,a.data,n,r,i,t),s.equal(a.tag,e)||q(new sjcl.exception.corrupt("ccm: tag doesn't match"
)),a.data},L:function(e,t,n,r,i,s){var o=[],u=sjcl.bitArray,a=u.l;i/=8,(i%2||4>i||16<
i)&&q(new sjcl.exception.invalid("ccm: invalid tag length")),(4294967295<r.length||4294967295<
t.length)&&q(new sjcl.exception.bug("ccm: can't deal with 4GiB or more data")),s=
[u.partial(8,(r.length?64:0)|i-2<<2|s-1)],s=u.concat(s,n),s[3]|=u.bitLength(t)/8
,s=e.encrypt(s);if(r.length){n=u.bitLength(r)/8,65279>=n?o=[u.partial(16,n)]:4294967295>=
n&&(o=u.concat([u.partial(16,65534)],[n])),o=u.concat(o,r);for(r=0;r<o.length;r+=4
)s=e.encrypt(a(s,o.slice(r,r+4).concat([0,0,0])))}for(r=0;r<t.length;r+=4)s=e.encrypt
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.extract"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>extract (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.extract)
- description and source-code
```javascript
extract = function (e, t, n){var r=Math.floor(-t-n&31
);return((t+n-1^t)&-32?e[t/32|0]<<32-r^e[t/32+1|0]>>>r:e[t/32|0]>>>r)&(1<<n)-1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.getPartial"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>getPartial (e)](#apidoc.element.utility2.sjcl.bitArray.getPartial)
- description and source-code
```javascript
getPartial = function (e){return Math
.round(e/1099511627776)||32}
```
- example usage
```shell
...
o<<4,c=c>>8^c&255^99,n[s]=c,r[c]=s,l=u[i=u[f=u[s]]],h=16843009*l^65537*i^257*f^16843008*
s,l=257*u[c]^16843008*c;for(i=0;4>i;i++)e[i][s]=l=l<<24^l>>>8,t[i][c]=h=h<<24^h>>>8
}for(i=0;5>i;i++)e[i]=e[i].slice(0),t[i]=t[i].slice(0)}},sjcl.bitArray={bitSlice
:function(e,t,n){return e=sjcl.bitArray.P(e.slice(t/32),32-(t&31)).slice(1),n===
s?e:sjcl.bitArray.clamp(e,n-t)},extract:function(e,t,n){var r=Math.floor(-t-n&31
);return((t+n-1^t)&-32?e[t/32|0]<<32-r^e[t/32+1|0]>>>r:e[t/32|0]>>>r)&(1<<n)-1},
concat:function(e,t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))},bitLength:function(e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])},clamp:function(e,t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
]=sjcl.bitArray.partial(t,e[n-1]&2147483648>>t-1,1)),e},partial:function(e,t,n){
return 32===e?t:(n?t|0:t<<32-e)+1099511627776*e},getPartial:function(e){return Math
.round(e/1099511627776)||32},equal:function(e,t){if(sjcl.bitArray.bitLength(e)!==
sjcl.bitArray.bitLength(t))return u;var n=0,r;for(r=0;r<e.length;r++)n|=e[r]^t[r
...
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.l"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>l (e, t)](#apidoc.element.utility2.sjcl.bitArray.l)
- description and source-code
```javascript
l = function (e, t){return[e[0
]^t[0],e[1]^t[1],e[2]^t[2],e[3]^t[3]]}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.bitArray.partial"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.bitArray.</span>partial (e, t, n)](#apidoc.element.utility2.sjcl.bitArray.partial)
- description and source-code
```javascript
partial = function (e, t, n){
return 32===e?t:(n?t|0:t<<32-e)+1099511627776*e}
```
- example usage
```shell
...
s?e:sjcl.bitArray.clamp(e,n-t)},extract:function(e,t,n){var r=Math.floor(-t-n&31
);return((t+n-1^t)&-32?e[t/32|0]<<32-r^e[t/32+1|0]>>>r:e[t/32|0]>>>r)&(1<<n)-1},
concat:function(e,t){if(0===e.length||0===t.length)return e.concat(t);var n=e[e.
length-1],r=sjcl.bitArray.getPartial(n);return 32===r?e.concat(t):sjcl.bitArray.
P(t,r,n|0,e.slice(0,e.length-1))},bitLength:function(e){var t=e.length;return 0===
t?0:32*(t-1)+sjcl.bitArray.getPartial(e[t-1])},clamp:function(e,t){if(32*e.length<
t)return e;e=e.slice(0,Math.ceil(t/32));var n=e.length;return t&=31,0<n&&t&&(e[n-1
]=sjcl.bitArray.partial(t,e[n-1]&2147483648>>t-1,1)),e},partial:function(e,t,n){
return 32===e?t:(n?t|0:t<<32-e)+1099511627776*e},getPartial:function(e){return Math
.round(e/1099511627776)||32},equal:function(e,t){if(sjcl.bitArray.bitLength(e)!==
sjcl.bitArray.bitLength(t))return u;var n=0,r;for(r=0;r<e.length;r++)n|=e[r]^t[r
];return 0===n},P:function(e,t,n,r){var i;i=0;for(r===s&&(r=[]);32<=t;t-=32)r.push
(n),n=0;if(0===t)return r.concat(e);for(i=0;i<e.length;i++)r.push(n|e[i]>>>t),n=
e[i]<<32-t;return i=e.length?e[e.length-1]:0,e=sjcl.bitArray.getPartial(i),r.push
(sjcl.bitArray.partial(t+e&31,32<t+e?n:r.pop(),1)),r},l:function(e,t){return[e[0
...
```



# <a name="apidoc.module.utility2.sjcl.cipher"></a>[module utility2.sjcl.cipher](#apidoc.module.utility2.sjcl.cipher)

#### <a name="apidoc.element.utility2.sjcl.cipher.aes"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.cipher.</span>aes (e)](#apidoc.element.utility2.sjcl.cipher.aes)
- description and source-code
```javascript
aes = function (e){this.k[0][0][0]||this.D();var t,n,r,i,s=this.k[0][4],o=this
.k[1];t=e.length;var u=1;4!==t&&6!==t&&8!==t&&q(new sjcl.exception.invalid("invalid aes key size"
)),this.b=[r=e.slice(0),i=[]];for(e=t;e<4*t+28;e++){n=r[e-1];if(0===e%t||8===t&&4===
e%t)n=s[n>>>24]<<24^s[n>>16&255]<<16^s[n>>8&255]<<8^s[n&255],0===e%t&&(n=n<<8^n>>>24^
u<<24,u=u<<1^283*(u>>7));r[e]=r[e-t]^n}for(t=0;e;t++,e--)n=r[t&3?e:e-4],i[t]=4>=
e||4>t?n:o[0][s[n>>>24]]^o[1][s[n>>16&255]]^o[2][s[n>>8&255]]^o[3][s[n&255]]}
```
- example usage
```shell
...
r|0,c=l,l=f,f=a,a=r+(f&l^c&(f^l))+(f>>>2^f>>>13^f>>>22^f<<30^f<<19^f<<10)|0;o[0]=
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
...
```



# <a name="apidoc.module.utility2.sjcl.cipher.aes.prototype"></a>[module utility2.sjcl.cipher.aes.prototype](#apidoc.module.utility2.sjcl.cipher.aes.prototype)

#### <a name="apidoc.element.utility2.sjcl.cipher.aes.prototype.D"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>D ()](#apidoc.element.utility2.sjcl.cipher.aes.prototype.D)
- description and source-code
```javascript
D = function (){var e=
this.k[0],t=this.k[1],n=e[4],r=t[4],i,s,o,u=[],a=[],f,l,c,h;for(i=0;256>i;i++)a[
(u[i]=i<<1^283*(i>>7))^i]=i;for(s=o=0;!n[s];s^=f||1,o=a[o]||1){c=o^o<<1^o<<2^o<<3^
o<<4,c=c>>8^c&255^99,n[s]=c,r[c]=s,l=u[i=u[f=u[s]]],h=16843009*l^65537*i^257*f^16843008*
s,l=257*u[c]^16843008*c;for(i=0;4>i;i++)e[i][s]=l=l<<24^l>>>8,t[i][c]=h=h<<24^h>>>8
}for(i=0;5>i;i++)e[i]=e[i].slice(0),t[i]=t[i].slice(0)}
```
- example usage
```shell
...
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
.cipher.aes=function(e){this.k[0][0][0]||this.D();var t,n,r,i,s=this.k[0][4],o=this
.k[1];t=e.length;var u=1;4!==t&&6!==t&&8!==t&&q(new sjcl.exception.invalid("invalid aes key size"
)),this.b=[r=e.slice(0),i=[]];for(e=t;e<4*t+28;e++){n=r[e-1];if(0===e%t||8===t&&4===
e%t)n=s[n>>>24]<<24^s[n>>16&255]<<16^s[n>>8&255]<<8^s[n&255],0===e%t&&(n=n<<8^n>>>24^
u<<24,u=u<<1^283*(u>>7));r[e]=r[e-t]^n}for(t=0;e;t++,e--)n=r[t&3?e:e-4],i[t]=4>=
e||4>t?n:o[0][s[n>>>24]]^o[1][s[n>>16&255]]^o[2][s[n>>8&255]]^o[3][s[n&255]]},sjcl
.cipher.aes.prototype={encrypt:function(e){return w(this,e,0)},decrypt:function(
e){return w(this,e,1)},k:[[[],[],[],[],[]],[[],[],[],[],[]]],D:function(){var e=
...
```

#### <a name="apidoc.element.utility2.sjcl.cipher.aes.prototype.decrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>decrypt ( e)](#apidoc.element.utility2.sjcl.cipher.aes.prototype.decrypt)
- description and source-code
```javascript
decrypt = function ( e){return w(this,e,1)}
```
- example usage
```shell
...
;o+4<t.length;o+=4)c=t.slice(o,o+4),l=f(l,c),h=h.concat(f(n,e.encrypt(f(n,c)))),
n=u(n);return c=t.slice(o),t=a.bitLength(c),o=e.encrypt(f(n,[0,0,0,t])),c=a.clamp
(f(c.concat([0,0,0]),o),t),l=f(l,f(c.concat([0,0,0]),o)),l=e.encrypt(f(l,f(n,u(n
)))),r.length&&(l=f(l,s?r:sjcl.mode.ocb2.pmac(e,r))),h.concat(a.concat(c,a.clamp
(l,i)))},decrypt:function(e,t,n,r,i,s){128!==sjcl.bitArray.bitLength(n)&&q(new sjcl
.exception.invalid("ocb iv must be 128 bits")),i=i||64;var o=sjcl.mode.ocb2.H,u=
sjcl.bitArray,a=u.l,f=[0,0,0,0],l=o(e.encrypt(n)),c,h,p=sjcl.bitArray.bitLength(
t)-i,d=[];r=r||[];for(n=0;n+4<p/32;n+=4)c=a(l,e.decrypt(a(l,t.slice(n,n+4)))),f=
a(f,c),d=d.concat(c),l=o(l);return h=p-32*n,c=e.encrypt(a(l,[0,0,0,h])),c=a(c,u.
clamp(t.slice(n),h).concat([0,0,0])),f=a(f,c),f=e.encrypt(a(f,a(l,o(l)))),r.length&&
(f=a(f,s?r:sjcl.mode.ocb2.pmac(e,r))),u.equal(u.clamp(f,i),u.bitSlice(t,p))||q(new
sjcl.exception.corrupt("ocb: tag doesn't match")),d.concat(u.clamp(c,h))},pmac:function(
e,t){var n,r=sjcl.mode.ocb2.H,i=sjcl.bitArray,s=i.l,o=[0,0,0,0],u=e.encrypt([0,0
,0,0]),u=s(u,r(r(u)));for(n=0;n+4<t.length;n+=4)u=r(u),o=s(o,e.encrypt(s(u,t.slice
(n,n+4))));return n=t.slice(n),128>i.bitLength(n)&&(u=s(u,r(u)),n=i.concat(n,[-2147483648
...
```

#### <a name="apidoc.element.utility2.sjcl.cipher.aes.prototype.encrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.cipher.aes.prototype.</span>encrypt (e)](#apidoc.element.utility2.sjcl.cipher.aes.prototype.encrypt)
- description and source-code
```javascript
encrypt = function (e){return w(this,e,0)}
```
- example usage
```shell
...
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
...
```



# <a name="apidoc.module.utility2.sjcl.exception"></a>[module utility2.sjcl.exception](#apidoc.module.utility2.sjcl.exception)

#### <a name="apidoc.element.utility2.sjcl.exception.bug"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>bug (e)](#apidoc.element.utility2.sjcl.exception.bug)
- description and source-code
```javascript
bug = function (e){this.toString=function(){return"BUG: "+
this.message},this.message=e}
```
- example usage
```shell
...
e,t,n,r,i){i=i||64,r=r||[];var s=sjcl.bitArray,o=s.bitLength(n)/8,u=s.bitLength(
t),a=s.clamp(t,u-i),f=s.bitSlice(t,u-i),u=(u-i)/8;7>o&&q(new sjcl.exception.invalid
("ccm: iv must be at least 7 bytes"));for(t=2;4>t&&u>>>8*t;t++);return t<15-o&&(
t=15-o),n=s.clamp(n,8*(15-t)),a=sjcl.mode.ccm.p(e,a,n,f,i,t),e=sjcl.mode.ccm.L(e
,a.data,n,r,i,t),s.equal(a.tag,e)||q(new sjcl.exception.corrupt("ccm: tag doesn't match"
)),a.data},L:function(e,t,n,r,i,s){var o=[],u=sjcl.bitArray,a=u.l;i/=8,(i%2||4>i||16<
i)&&q(new sjcl.exception.invalid("ccm: invalid tag length")),(4294967295<r.length||4294967295<
t.length)&&q(new sjcl.exception.bug("ccm: can't deal with 4GiB or more data")),s=
[u.partial(8,(r.length?64:0)|i-2<<2|s-1)],s=u.concat(s,n),s[3]|=u.bitLength(t)/8
,s=e.encrypt(s);if(r.length){n=u.bitLength(r)/8,65279>=n?o=[u.partial(16,n)]:4294967295>=
n&&(o=u.concat([u.partial(16,65534)],[n])),o=u.concat(o,r);for(r=0;r<o.length;r+=4
)s=e.encrypt(a(s,o.slice(r,r+4).concat([0,0,0])))}for(r=0;r<t.length;r+=4)s=e.encrypt
(a(s,t.slice(r,r+4).concat([0,0,0])));return u.clamp(s,8*i)},p:function(e,t,n,r,
i,s){var o,u=sjcl.bitArray;o=u.l;var a=t.length,f=u.bitLength(t);n=u.concat([u.partial
(8,s-1)],n).concat([0,0,0]).slice(0,4),r=u.bitSlice(o(r,e.encrypt(n)),0,i);if(!a
...
```

#### <a name="apidoc.element.utility2.sjcl.exception.corrupt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>corrupt (e)](#apidoc.element.utility2.sjcl.exception.corrupt)
- description and source-code
```javascript
corrupt = function (e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e}
```
- example usage
```shell
...
[],7>a&&q(new sjcl.exception.invalid("ccm: iv must be at least 7 bytes"));for(s=2
;4>s&&f>>>8*s;s++);return s<15-a&&(s=15-a),n=u.clamp(n,8*(15-s)),t=sjcl.mode.ccm
.L(e,t,n,r,i,s),o=sjcl.mode.ccm.p(e,o,n,t,i,s),u.concat(o.data,o.tag)},decrypt:function(
e,t,n,r,i){i=i||64,r=r||[];var s=sjcl.bitArray,o=s.bitLength(n)/8,u=s.bitLength(
t),a=s.clamp(t,u-i),f=s.bitSlice(t,u-i),u=(u-i)/8;7>o&&q(new sjcl.exception.invalid
("ccm: iv must be at least 7 bytes"));for(t=2;4>t&&u>>>8*t;t++);return t<15-o&&(
t=15-o),n=s.clamp(n,8*(15-t)),a=sjcl.mode.ccm.p(e,a,n,f,i,t),e=sjcl.mode.ccm.L(e
,a.data,n,r,i,t),s.equal(a.tag,e)||q(new sjcl.exception.corrupt("ccm: tag doesn't match"
)),a.data},L:function(e,t,n,r,i,s){var o=[],u=sjcl.bitArray,a=u.l;i/=8,(i%2||4>i||16<
i)&&q(new sjcl.exception.invalid("ccm: invalid tag length")),(4294967295<r.length||4294967295<
t.length)&&q(new sjcl.exception.bug("ccm: can't deal with 4GiB or more data")),s=
[u.partial(8,(r.length?64:0)|i-2<<2|s-1)],s=u.concat(s,n),s[3]|=u.bitLength(t)/8
,s=e.encrypt(s);if(r.length){n=u.bitLength(r)/8,65279>=n?o=[u.partial(16,n)]:4294967295>=
n&&(o=u.concat([u.partial(16,65534)],[n])),o=u.concat(o,r);for(r=0;r<o.length;r+=4
)s=e.encrypt(a(s,o.slice(r,r+4).concat([0,0,0])))}for(r=0;r<t.length;r+=4)s=e.encrypt
...
```

#### <a name="apidoc.element.utility2.sjcl.exception.invalid"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>invalid (e)](#apidoc.element.utility2.sjcl.exception.invalid)
- description and source-code
```javascript
invalid = function (e){this.toString=function(){return"INVALID: "+
this.message},this.message=e}
```
- example usage
```shell
...

// init lib sjcl
/* jslint-ignore-begin */
// https://github.com/bitwiseshiftleft/sjcl/blob/1.0.3/sjcl.js
// utility2-uglify https://raw.githubusercontent.com/bitwiseshiftleft/sjcl/1.0.3/sjcl.js
(function () { var module;
"use strict";function q(e){throw e}function w(e,t,n){4!==t.length&&q(new sjcl.exception
.invalid("invalid aes block size"));var r=e.b[n],i=t[0]^r[0],s=t[n?3:1]^r[1],o=t
[2]^r[2];t=t[n?1:3]^r[3];var u,a,f,l=r.length/4-2,c,h=4,p=[0,0,0,0];u=e.k[n],e=u
[0];var d=u[1],v=u[2],m=u[3],g=u[4];for(c=0;c<l;c++)u=e[i>>>24]^d[s>>16&255]^v[o>>8&255
]^m[t&255]^r[h],a=e[s>>>24]^d[o>>16&255]^v[t>>8&255]^m[i&255]^r[h+1],f=e[o>>>24]^
d[t>>16&255]^v[i>>8&255]^m[s&255]^r[h+2],t=e[t>>>24]^d[i>>16&255]^v[s>>8&255]^m[
o&255]^r[h+3],h+=4,i=u,s=a,o=f;for(c=0;4>c;c++)p[n?3&-c:c]=g[i>>>24]<<24^g[s>>16&255
]<<16^g[o>>8&255]<<8^g[t&255]^r[h++],u=i,i=s,s=o,o=t,t=u;return p}function x(e,t
){var n,r,i,s=t.slice(0),o=e.r,u=e.b,a=o[0],f=o[1],l=o[2],c=o[3],h=o[4],p=o[5],d=
...
```

#### <a name="apidoc.element.utility2.sjcl.exception.notReady"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.exception.</span>notReady (e)](#apidoc.element.utility2.sjcl.exception.notReady)
- description and source-code
```javascript
notReady = function (e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}
```
- example usage
```shell
...
);for(o=1;o<n;o++){s=e.encrypt(s);for(u=0;u<s.length;u++)i[u]^=s[u]}f=f.concat(i
)}return r&&(f=l.clamp(f,r)),f},sjcl.prng=function(e){this.c=[new sjcl.hash.sha256
],this.i=[0],this.F=0,this.s={},this.C=0,this.K={},this.O=this.d=this.j=this.W=0
,this.b=[0,0,0,0,0,0,0,0],this.f=[0,0,0,0],this.A=s,this.B=e,this.q=u,this.w={progress
:{},seeded:{}},this.m=this.V=0,this.t=1,this.u=2,this.S=65536,this.I=[0,48,64,96
,128,192,256,384,512,768,1024],this.T=3e4,this.R=80},sjcl.prng.prototype={randomWords
:function(e,t){var n=[],r;r=this.isReady(t);var i;r===this.m&&q(new sjcl.exception
.notReady("generator isn't seeded"));if(r&this.u){r=!(r&this.t),i=[];var s=0,o;this
.O=i[0]=(new Date).valueOf()+this.T;for(o=0;16>o;o++)i.push(4294967296*Math.random
()|0);for(o=0;o<this.c.length&&!(i=i.concat(this.c[o].finalize()),s+=this.i[o],this
.i[o]=0,!r&&this.F&1<<o);o++);this.F>=1<<this.c.length&&(this.c.push(new sjcl.hash
.sha256),this.i.push(0)),this.d-=s,s>this.j&&(this.j=s),this.F++,this.b=sjcl.hash
.sha256.hash(this.b.concat(i)),this.A=new sjcl.cipher.aes(this.b);for(r=0;4>r&&(
this.f[r]=this.f[r]+1|0,!this.f[r]);r++);}for(r=0;r<e;r+=4)0===(r+1)%this.S&&A(this
),i=B(this),n.push(i[0],i[1],i[2],i[3]);return A(this),n.slice(0,e)},setDefaultParanoia
...
```



# <a name="apidoc.module.utility2.sjcl.hash"></a>[module utility2.sjcl.hash](#apidoc.module.utility2.sjcl.hash)

#### <a name="apidoc.element.utility2.sjcl.hash.sha256"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.hash.</span>sha256 (e)](#apidoc.element.utility2.sjcl.hash.sha256)
- description and source-code
```javascript
sha256 = function (e){this.b[0]||this.D(),e?(this.r=e.r.slice(0),this.o=e.o.slice
(0),this.h=e.h):this.reset()}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.sjcl.hash.sha256.prototype"></a>[module utility2.sjcl.hash.sha256.prototype](#apidoc.module.utility2.sjcl.hash.sha256.prototype)

#### <a name="apidoc.element.utility2.sjcl.hash.sha256.prototype.D"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>D ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.D)
- description and source-code
```javascript
D = function (){function e
(e){return 4294967296*(e-Math.floor(e))|0}var t=0,n=2,r;e:for(;64>t;n++){for(r=2
;r*r<=n;r++)if(0===n%r)continue e;8>t&&(this.N[t]=e(Math.pow(n,.5))),this.b[t]=e
(Math.pow(n,1/3)),t++}}
```
- example usage
```shell
...
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
.cipher.aes=function(e){this.k[0][0][0]||this.D();var t,n,r,i,s=this.k[0][4],o=this
.k[1];t=e.length;var u=1;4!==t&&6!==t&&8!==t&&q(new sjcl.exception.invalid("invalid aes key size"
)),this.b=[r=e.slice(0),i=[]];for(e=t;e<4*t+28;e++){n=r[e-1];if(0===e%t||8===t&&4===
e%t)n=s[n>>>24]<<24^s[n>>16&255]<<16^s[n>>8&255]<<8^s[n&255],0===e%t&&(n=n<<8^n>>>24^
u<<24,u=u<<1^283*(u>>7));r[e]=r[e-t]^n}for(t=0;e;t++,e--)n=r[t&3?e:e-4],i[t]=4>=
e||4>t?n:o[0][s[n>>>24]]^o[1][s[n>>16&255]]^o[2][s[n>>8&255]]^o[3][s[n&255]]},sjcl
.cipher.aes.prototype={encrypt:function(e){return w(this,e,0)},decrypt:function(
e){return w(this,e,1)},k:[[[],[],[],[],[]],[[],[],[],[],[]]],D:function(){var e=
...
```

#### <a name="apidoc.element.utility2.sjcl.hash.sha256.prototype.finalize"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>finalize ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.finalize)
- description and source-code
```javascript
finalize = function (){var e,t=this
.o,n=this.r,t=sjcl.bitArray.concat(t,[sjcl.bitArray.partial(1,1)]);for(e=t.length+2
;e&15;e++)t.push(0);t.push(Math.floor(this.h/4294967296));for(t.push(this.h|0);t
.length;)x(this,t.splice(0,16));return this.reset(),n}
```
- example usage
```shell
...
.J,o=0,u;t&&(s=s.substr(0,62)+"-_");for(r=0;r<e.length;r++)u=s.indexOf(e.charAt(
r)),0>u&&q(new sjcl.exception.invalid("this isn't base64!")),26<i?(i-=26,n.push(
o^u>>>i),o=u<<32-i):(i+=6,o^=u<<32-i);return i&56&&n.push(sjcl.bitArray.partial(
i&56,o,1)),n}},sjcl.codec.base64url={fromBits:function(e){return sjcl.codec.base64
.fromBits(e,1,1)},toBits:function(e){return sjcl.codec.base64.toBits(e,1)}},sjcl
.hash.sha256=function(e){this.b[0]||this.D(),e?(this.r=e.r.slice(0),this.o=e.o.slice
(0),this.h=e.h):this.reset()},sjcl.hash.sha256.hash=function(e){return(new sjcl.
hash.sha256).update(e).finalize()},sjcl.hash.sha256.prototype={blockSize:512,reset
:function(){return this.r=this.N.slice(0),this.o=[],this.h=0,this},update:function(
e){"string"==typeof e&&(e=sjcl.codec.utf8String.toBits(e));var t,n=this.o=sjcl.bitArray
.concat(this.o,e);t=this.h,e=this.h=t+sjcl.bitArray.bitLength(e);for(t=512+t&-512
;t<=e;t+=512)x(this,n.splice(0,16));return this},finalize:function(){var e,t=this
.o,n=this.r,t=sjcl.bitArray.concat(t,[sjcl.bitArray.partial(1,1)]);for(e=t.length+2
;e&15;e++)t.push(0);t.push(Math.floor(this.h/4294967296));for(t.push(this.h|0);t
.length;)x(this,t.splice(0,16));return this.reset(),n},N:[],b:[],D:function(){function e
...
```

#### <a name="apidoc.element.utility2.sjcl.hash.sha256.prototype.reset"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>reset ()](#apidoc.element.utility2.sjcl.hash.sha256.prototype.reset)
- description and source-code
```javascript
reset = function (){return this.r=this.N.slice(0),this.o=[],this.h=0,this}
```
- example usage
```shell
...
numberToken(t,i,s):isWhitespace(t)?r=this.whitespaceToken(t,i,s):isIdentStart(t)?
r=this.identOrFunctionToken(t,i,s):r=this.charToken(t,i,s)}break}return!r&&t===null&&
(r=this.createToken(Tokens.EOF,null,i,s)),r},createToken:function(e,t,n,r,i){var s=
this._reader;return i=i||{},{value:t,type:e,channel:i.channel,hide:i.hide||!1,startLine
:n,startCol:r,endLine:s.getLine(),endCol:s.getCol()}},atRuleToken:function(e,t,n
){var r=e,i=this._reader,s=Tokens.CHAR,o=!1,u,a;i.mark(),u=this.readName(),r=e+u
,s=Tokens.type(r.toLowerCase());if(s==Tokens.CHAR||s==Tokens.UNKNOWN)r.length>1?
s=Tokens.UNKNOWN_SYM:(s=Tokens.CHAR,r=e,i.reset());return this.createToken(s,r,t
,n)},charToken:function(e,t,n){var r=Tokens.type(e);return r==-1&&(r=Tokens.CHAR
),this.createToken(r,e,t,n)},commentToken:function(e,t,n){var r=this._reader,i=this
.readComment(e);return this.createToken(Tokens.COMMENT,i,t,n)},comparisonToken:function(
e,t,n){var r=this._reader,i=e+r.read(),s=Tokens.type(i)||Tokens.CHAR;return this
.createToken(s,i,t,n)},hashToken:function(e,t,n){var r=this._reader,i=this.readName
(e);return this.createToken(Tokens.HASH,i,t,n)},htmlCommentStartToken:function(e
,t,n){var r=this._reader,i=e;return r.mark(),i+=r.readCount(3),i=="<!--"?this.createToken
...
```

#### <a name="apidoc.element.utility2.sjcl.hash.sha256.prototype.update"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.hash.sha256.prototype.</span>update ( e)](#apidoc.element.utility2.sjcl.hash.sha256.prototype.update)
- description and source-code
```javascript
update = function ( e){"string"==typeof e&&(e=sjcl.codec.utf8String.toBits(e));var t,n=this.o=sjcl.bitArray
.concat(this.o,e);t=this.h,e=this.h=t+sjcl.bitArray.bitLength(e);for(t=512+t&-512
;t<=e;t+=512)x(this,n.splice(0,16));return this}
```
- example usage
```shell
...
// init lib istanbul.instrumenter
/* jslint-ignore-begin */
// https://github.com/gotwarlost/istanbul/blob/v0.3.20/lib/instrumenter.js
// utility2-uglifyjs https://raw.githubusercontent.com/gotwarlost/istanbul/v0.3.20/lib/instrumenter.js
// replace '(t?"":r)' with 'Math.random().toString(16).slice(2)'
(function () { var escodegen, esprima, module, window; escodegen = local.escodegen; esprima = local.esprima; module = undefined;
window = local;
(function(e){"use strict";function p(e,t){var n,r;return s!==null?(n=s.createHash
("md5"),n.update(e),r=n.digest("base64"),r=r.replace(new RegExp("=","g"),"").replace
(new RegExp("\\+","g"),"_").replace(new RegExp("/","g"),"$")):(window.__cov_seq=
window.__cov_seq||0,window.__cov_seq+=1,r=window.__cov_seq),"__cov_"+Math.random().toString(16).slice(2)}function d
(e,t){h(t)||(t=[t]),Array.prototype.push.apply(e,t)}function v(e,t,n,r){this.walkMap=
e,this.preprocessor=t,this.scope=n,this.debug=r,this.debug&&(this.level=0,this.seq=!0
)}function m(e,n){var r=e.type,i,s,o=t[r],u=!!e.loc||e.type===t.Program.name,a=u?
n.walkMap[r]:null,f,l,c,p,v,m,g,y,b,w,E;if(!t[r]){console.error(e),console.error
("Unsupported node type:"+r);return}o=t[r].children;if(e.walking)throw new Error
...
```



# <a name="apidoc.module.utility2.sjcl.json"></a>[module utility2.sjcl.json](#apidoc.module.utility2.sjcl.json)

#### <a name="apidoc.element.utility2.sjcl.json.X"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>X (e, t, n, r)](#apidoc.element.utility2.sjcl.json.X)
- description and source-code
```javascript
X = function (e, t, n, r){n=n||{},r=r||{};var i=sjcl.json;t=i.e(i.e(i.e({}
,i.defaults),t),n,!0);var s,o;return s=t.adata,"string"==typeof t.salt&&(t.salt=
sjcl.codec.base64.toBits(t.salt)),"string"==typeof t.iv&&(t.iv=sjcl.codec.base64
.toBits(t.iv)),(!sjcl.mode[t.mode]||!sjcl.cipher[t.cipher]||"string"==typeof e&&100>=
t.iter||64!==t.ts&&96!==t.ts&&128!==t.ts||128!==t.ks&&192!==t.ks&&256!==t.ks||!t
.iv||2>t.iv.length||4<t.iv.length)&&q(new sjcl.exception.invalid("json decrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,t),e=o.key.slice(0,t.ks/32),t.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.secretKey&&(e=e.unkem(sjcl.
codec.base64.toBits(t.kemtag)).slice(0,t.ks/32)),"string"==typeof s&&(s=sjcl.codec
.utf8String.toBits(s)),o=new sjcl.cipher[t.cipher](e),s=sjcl.mode[t.mode].decrypt
(o,t.ct,t.iv,s,t.ts),i.e(r,t),r.key=e,1===n.raw?s:sjcl.codec.utf8String.fromBits
(s)}
```
- example usage
```shell
...
t.iter||64!==t.ts&&96!==t.ts&&128!==t.ts||128!==t.ks&&192!==t.ks&&256!==t.ks||!t
.iv||2>t.iv.length||4<t.iv.length)&&q(new sjcl.exception.invalid("json decrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,t),e=o.key.slice(0,t.ks/32),t.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.secretKey&&(e=e.unkem(sjcl.
codec.base64.toBits(t.kemtag)).slice(0,t.ks/32)),"string"==typeof s&&(s=sjcl.codec
.utf8String.toBits(s)),o=new sjcl.cipher[t.cipher](e),s=sjcl.mode[t.mode].decrypt
(o,t.ct,t.iv,s,t.ts),i.e(r,t),r.key=e,1===n.raw?s:sjcl.codec.utf8String.fromBits
(s)},decrypt:function(e,t,n,r){var i=sjcl.json;return i.X(e,i.decode(t),n,r)},encode
:function(e){var t,n="{",r="";for(t in e)if(e.hasOwnProperty(t))switch(t.match(/^[a-z0-9]+$/i
)||q(new sjcl.exception.invalid("json encode: invalid property name")),n+=r+'"'+
t+'":',r=",",typeof e[t]){case"number":case"boolean":n+=e[t];break;case"string":
n+='"'+escape(e[t])+'"';break;case"object":n+='"'+sjcl.codec.base64.fromBits(e[t
],0)+'"';break;default:q(new sjcl.exception.bug("json encode: unsupported type")
)}return n+"}"},decode:function(e){e=e.replace(/\s/g,""),e.match(/^\{.*\}$/)||q(new
sjcl.exception.invalid("json decode: this isn't json!")),e=e.replace(/^\{|\}$/g,""
...
```

#### <a name="apidoc.element.utility2.sjcl.json.Y"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>Y (e, t, n, r)](#apidoc.element.utility2.sjcl.json.Y)
- description and source-code
```javascript
Y = function (e, t, n, r){n=n||{},r=r||{};var i=sjcl.json,s=i.e({iv:
sjcl.random.randomWords(4,0)},i.defaults),o;return i.e(s,n),n=s.adata,"string"==typeof
s.salt&&(s.salt=sjcl.codec.base64.toBits(s.salt)),"string"==typeof s.iv&&(s.iv=sjcl
.codec.base64.toBits(s.iv)),(!sjcl.mode[s.mode]||!sjcl.cipher[s.cipher]||"string"==typeof
e&&100>=s.iter||64!==s.ts&&96!==s.ts&&128!==s.ts||128!==s.ks&&192!==s.ks&&256!==
s.ks||2>s.iv.length||4<s.iv.length)&&q(new sjcl.exception.invalid("json encrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,s),e=o.key.slice(0,s.ks/32),s.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.publicKey&&(o=e.kem(),s.kemtag=
o.tag,e=o.key.slice(0,s.ks/32)),"string"==typeof t&&(t=sjcl.codec.utf8String.toBits
(t)),"string"==typeof n&&(s.adata=n=sjcl.codec.utf8String.toBits(n)),o=new sjcl.
cipher[s.cipher](e),i.e(r,s),r.key=e,s.ct=sjcl.mode[s.mode].encrypt(o,t,s.iv,n,s
.ts),s}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.json.decode"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>decode (e)](#apidoc.element.utility2.sjcl.json.decode)
- description and source-code
```javascript
decode = function (e){e=e.replace(/\s/g,""),e.match(/^\{.*\}$/)||q(new
sjcl.exception.invalid("json decode: this isn't json!")),e=e.replace(/^\{|\}$/g,""
).split(/,/);var t={},n,r;for(n=0;n<e.length;n++)(r=e[n].match(/^\s*(?:(["']?)([a-z][a-z0-9]*)\1)\s*:\s*(?:(-?\d+)|"([a-z0-9+\/%*
_.@=\-]*)"|(true|false))$/i
))||q(new sjcl.exception.invalid("json decode: this isn't json!")),r[3]?t[r[2]]=
parseInt(r[3],10):r[4]?t[r[2]]=r[2].match(/^(ct|adata|salt|iv)$/)?sjcl.codec.base64
.toBits(r[4]):unescape(r[4]):r[5]&&(t[r[2]]="true"===r[5]);return t}
```
- example usage
```shell
...
t.iter||64!==t.ts&&96!==t.ts&&128!==t.ts||128!==t.ks&&192!==t.ks&&256!==t.ks||!t
.iv||2>t.iv.length||4<t.iv.length)&&q(new sjcl.exception.invalid("json decrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,t),e=o.key.slice(0,t.ks/32),t.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.secretKey&&(e=e.unkem(sjcl.
codec.base64.toBits(t.kemtag)).slice(0,t.ks/32)),"string"==typeof s&&(s=sjcl.codec
.utf8String.toBits(s)),o=new sjcl.cipher[t.cipher](e),s=sjcl.mode[t.mode].decrypt
(o,t.ct,t.iv,s,t.ts),i.e(r,t),r.key=e,1===n.raw?s:sjcl.codec.utf8String.fromBits
(s)},decrypt:function(e,t,n,r){var i=sjcl.json;return i.X(e,i.decode(t),n,r)},encode
:function(e){var t,n="{",r="";for(t in e)if(e.hasOwnProperty(t))switch(t.match(/^[a-z0-9]+$/i
)||q(new sjcl.exception.invalid("json encode: invalid property name")),n+=r+'"'+
t+'":',r=",",typeof e[t]){case"number":case"boolean":n+=e[t];break;case"string":
n+='"'+escape(e[t])+'"';break;case"object":n+='"'+sjcl.codec.base64.fromBits(e[t
],0)+'"';break;default:q(new sjcl.exception.bug("json encode: unsupported type")
)}return n+"}"},decode:function(e){e=e.replace(/\s/g,""),e.match(/^\{.*\}$/)||q(new
sjcl.exception.invalid("json decode: this isn't json!")),e=e.replace(/^\{|\}$/g,""
...
```

#### <a name="apidoc.element.utility2.sjcl.json.decrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>decrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.json.decrypt)
- description and source-code
```javascript
decrypt = function (e, t, n, r){var i=sjcl.json;return i.X(e,i.decode(t),n,r)}
```
- example usage
```shell
...
;o+4<t.length;o+=4)c=t.slice(o,o+4),l=f(l,c),h=h.concat(f(n,e.encrypt(f(n,c)))),
n=u(n);return c=t.slice(o),t=a.bitLength(c),o=e.encrypt(f(n,[0,0,0,t])),c=a.clamp
(f(c.concat([0,0,0]),o),t),l=f(l,f(c.concat([0,0,0]),o)),l=e.encrypt(f(l,f(n,u(n
)))),r.length&&(l=f(l,s?r:sjcl.mode.ocb2.pmac(e,r))),h.concat(a.concat(c,a.clamp
(l,i)))},decrypt:function(e,t,n,r,i,s){128!==sjcl.bitArray.bitLength(n)&&q(new sjcl
.exception.invalid("ocb iv must be 128 bits")),i=i||64;var o=sjcl.mode.ocb2.H,u=
sjcl.bitArray,a=u.l,f=[0,0,0,0],l=o(e.encrypt(n)),c,h,p=sjcl.bitArray.bitLength(
t)-i,d=[];r=r||[];for(n=0;n+4<p/32;n+=4)c=a(l,e.decrypt(a(l,t.slice(n,n+4)))),f=
a(f,c),d=d.concat(c),l=o(l);return h=p-32*n,c=e.encrypt(a(l,[0,0,0,h])),c=a(c,u.
clamp(t.slice(n),h).concat([0,0,0])),f=a(f,c),f=e.encrypt(a(f,a(l,o(l)))),r.length&&
(f=a(f,s?r:sjcl.mode.ocb2.pmac(e,r))),u.equal(u.clamp(f,i),u.bitSlice(t,p))||q(new
sjcl.exception.corrupt("ocb: tag doesn't match")),d.concat(u.clamp(c,h))},pmac:function(
e,t){var n,r=sjcl.mode.ocb2.H,i=sjcl.bitArray,s=i.l,o=[0,0,0,0],u=e.encrypt([0,0
,0,0]),u=s(u,r(r(u)));for(n=0;n+4<t.length;n+=4)u=r(u),o=s(o,e.encrypt(s(u,t.slice
(n,n+4))));return n=t.slice(n),128>i.bitLength(n)&&(u=s(u,r(u)),n=i.concat(n,[-2147483648
...
```

#### <a name="apidoc.element.utility2.sjcl.json.e"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>e ( e, t, n)](#apidoc.element.utility2.sjcl.json.e)
- description and source-code
```javascript
e = function ( e, t, n){e===s&&(e={});if(t===s)return e;for(var r in t)t.hasOwnProperty(r)&&(n&&e
[r]!==s&&e[r]!==t[r]&&q(new sjcl.exception.invalid("required parameter overridden"
)),e[r]=t[r]);return e}
```
- example usage
```shell
...
F=new Uint32Array((new Uint8Array(F)).buffer),sjcl.random.addEntropy(F,1024,"crypto['randomBytes']"
);else if("undefined"!=typeof window&&"undefined"!=typeof Uint32Array){H=new Uint32Array
(32);if(window.crypto&&window.crypto.getRandomValues)window.crypto.getRandomValues
(H);else{if(!window.msCrypto||!window.msCrypto.getRandomValues)break e;window.msCrypto
.getRandomValues(H)}sjcl.random.addEntropy(H,1024,"crypto['getRandomValues']")}}
catch(M){"undefined"!=typeof window&&window.console&&(console.log("There was an error collecting entropy from the browser:"
),console.log(M))}sjcl.json={defaults:{v:1,iter:1e3,ks:128,ts:64,mode:"ccm",adata
:"",cipher:"aes"},Y:function(e,t,n,r){n=n||{},r=r||{};var i=sjcl.json,s=i.e({iv:
sjcl.random.randomWords(4,0)},i.defaults),o;return i.e(s,n),n=s.adata,"string"==typeof
s.salt&&(s.salt=sjcl.codec.base64.toBits(s.salt)),"string"==typeof s.iv&&(s.iv=sjcl
.codec.base64.toBits(s.iv)),(!sjcl.mode[s.mode]||!sjcl.cipher[s.cipher]||"string"==typeof
e&&100>=s.iter||64!==s.ts&&96!==s.ts&&128!==s.ts||128!==s.ks&&192!==s.ks&&256!==
s.ks||2>s.iv.length||4<s.iv.length)&&q(new sjcl.exception.invalid("json encrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,s),e=o.key.slice(0,s.ks/32),s.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.publicKey&&(o=e.kem(),s.kemtag=
...
```

#### <a name="apidoc.element.utility2.sjcl.json.ea"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>ea (e, t)](#apidoc.element.utility2.sjcl.json.ea)
- description and source-code
```javascript
ea = function (e, t){var n={},r;for(r=0;r<t.length
;r++)e[t[r]]!==s&&(n[t[r]]=e[t[r]]);return n}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.json.encode"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>encode (e)](#apidoc.element.utility2.sjcl.json.encode)
- description and source-code
```javascript
encode = function (e){var t,n="{",r="";for(t in e)if(e.hasOwnProperty(t))switch(t.match(/^[a-z0-9]+$/i
)||q(new sjcl.exception.invalid("json encode: invalid property name")),n+=r+'"'+
t+'":',r=",",typeof e[t]){case"number":case"boolean":n+=e[t];break;case"string":
n+='"'+escape(e[t])+'"';break;case"object":n+='"'+sjcl.codec.base64.fromBits(e[t
],0)+'"';break;default:q(new sjcl.exception.bug("json encode: unsupported type")
)}return n+"}"}
```
- example usage
```shell
...
s.ks||2>s.iv.length||4<s.iv.length)&&q(new sjcl.exception.invalid("json encrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,s),e=o.key.slice(0,s.ks/32),s.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.publicKey&&(o=e.kem(),s.kemtag=
o.tag,e=o.key.slice(0,s.ks/32)),"string"==typeof t&&(t=sjcl.codec.utf8String.toBits
(t)),"string"==typeof n&&(s.adata=n=sjcl.codec.utf8String.toBits(n)),o=new sjcl.
cipher[s.cipher](e),i.e(r,s),r.key=e,s.ct=sjcl.mode[s.mode].encrypt(o,t,s.iv,n,s
.ts),s},encrypt:function(e,t,n,r){var i=sjcl.json,s=i.Y.apply(i,arguments);return i
.encode(s)},X:function(e,t,n,r){n=n||{},r=r||{};var i=sjcl.json;t=i.e(i.e(i.e({}
,i.defaults),t),n,!0);var s,o;return s=t.adata,"string"==typeof t.salt&&(t.salt=
sjcl.codec.base64.toBits(t.salt)),"string"==typeof t.iv&&(t.iv=sjcl.codec.base64
.toBits(t.iv)),(!sjcl.mode[t.mode]||!sjcl.cipher[t.cipher]||"string"==typeof e&&100>=
t.iter||64!==t.ts&&96!==t.ts&&128!==t.ts||128!==t.ks&&192!==t.ks&&256!==t.ks||!t
.iv||2>t.iv.length||4<t.iv.length)&&q(new sjcl.exception.invalid("json decrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,t),e=o.key.slice(0,t.ks/32),t.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.secretKey&&(e=e.unkem(sjcl.
...
```

#### <a name="apidoc.element.utility2.sjcl.json.encrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>encrypt (e, t, n, r)](#apidoc.element.utility2.sjcl.json.encrypt)
- description and source-code
```javascript
encrypt = function (e, t, n, r){var i=sjcl.json,s=i.Y.apply(i,arguments);return i
.encode(s)}
```
- example usage
```shell
...
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
...
```

#### <a name="apidoc.element.utility2.sjcl.json.fa"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.json.</span>fa (e, t)](#apidoc.element.utility2.sjcl.json.fa)
- description and source-code
```javascript
fa = function (e, t){var n={},r;for(r in e)e.hasOwnProperty(
r)&&e[r]!==t[r]&&(n[r]=e[r]);return n}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.sjcl.misc"></a>[module utility2.sjcl.misc](#apidoc.module.utility2.sjcl.misc)

#### <a name="apidoc.element.utility2.sjcl.misc.cachedPbkdf2"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>cachedPbkdf2 (e, t)](#apidoc.element.utility2.sjcl.misc.cachedPbkdf2)
- description and source-code
```javascript
cachedPbkdf2 = function (e, t){
var n=sjcl.misc.ca,r;return t=t||{},r=t.iter||1e3,n=n[e]=n[e]||{},r=n[r]=n[r]||{
firstSalt:t.salt&&t.salt.length?t.salt.slice(0):sjcl.random.randomWords(2,0)},n=
t.salt===s?r.firstSalt:t.salt,r[n]=r[n]||sjcl.misc.pbkdf2(e,n,t.iter),{key:r[n].
slice(0),salt:n.slice(0)}}
```
- example usage
```shell
...
),console.log(M))}sjcl.json={defaults:{v:1,iter:1e3,ks:128,ts:64,mode:"ccm",adata
:"",cipher:"aes"},Y:function(e,t,n,r){n=n||{},r=r||{};var i=sjcl.json,s=i.e({iv:
sjcl.random.randomWords(4,0)},i.defaults),o;return i.e(s,n),n=s.adata,"string"==typeof
s.salt&&(s.salt=sjcl.codec.base64.toBits(s.salt)),"string"==typeof s.iv&&(s.iv=sjcl
.codec.base64.toBits(s.iv)),(!sjcl.mode[s.mode]||!sjcl.cipher[s.cipher]||"string"==typeof
e&&100>=s.iter||64!==s.ts&&96!==s.ts&&128!==s.ts||128!==s.ks&&192!==s.ks&&256!==
s.ks||2>s.iv.length||4<s.iv.length)&&q(new sjcl.exception.invalid("json encrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,s),e=o.key.slice(0,s.ks/32),s.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.publicKey&&(o=e.kem(),s.kemtag=
o.tag,e=o.key.slice(0,s.ks/32)),"string"==typeof t&&(t=sjcl.codec.utf8String.toBits
(t)),"string"==typeof n&&(s.adata=n=sjcl.codec.utf8String.toBits(n)),o=new sjcl.
cipher[s.cipher](e),i.e(r,s),r.key=e,s.ct=sjcl.mode[s.mode].encrypt(o,t,s.iv,n,s
.ts),s},encrypt:function(e,t,n,r){var i=sjcl.json,s=i.Y.apply(i,arguments);return i
.encode(s)},X:function(e,t,n,r){n=n||{},r=r||{};var i=sjcl.json;t=i.e(i.e(i.e({}
,i.defaults),t),n,!0);var s,o;return s=t.adata,"string"==typeof t.salt&&(t.salt=
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.hmac"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>hmac (e, t)](#apidoc.element.utility2.sjcl.misc.hmac)
- description and source-code
```javascript
hmac = function (e, t){this.M=t=t||sjcl.hash.sha256;var n=
[[],[]],r,i=t.prototype.blockSize/32;this.n=[new t,new t],e.length>i&&(e=t.hash(
e));for(r=0;r<i;r++)n[0][r]=e[r]^909522486,n[1][r]=e[r]^1549556828;this.n[0].update
(n[0]),this.n[1].update(n[1]),this.G=new t(this.n[0])}
```
- example usage
```shell
...
// try to decode the token
return local.tryCatchOnError(function () {
    token = token.split('.');
    // validate header
    local.assert(token[0] === 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9', token);
    // validate signature
    local.assert(local.sjcl.codec.base64url.fromBits(
        new local.sjcl.misc.hmac(local.sjcl.codec.base64url.toBits(
            local.jwtAes256KeyInit(key)
        )).encrypt(token[0] + '.' + token[1])
    ) === token[2]);
    // return decoded data
    token = JSON.parse(local.base64ToString(token[1]));
    // https://tools.ietf.org/html/rfc7519#section-4.1
    // validate jwt-registered-headers
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.pbkdf2"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>pbkdf2 (e, t, n, r, i)](#apidoc.element.utility2.sjcl.misc.pbkdf2)
- description and source-code
```javascript
pbkdf2 = function (e, t, n, r, i){n=n||1e3,(0>r||0>n)&&q(sjcl.exception.invalid("invalid params to pbkdf2"
)),"string"==typeof e&&(e=sjcl.codec.utf8String.toBits(e)),"string"==typeof t&&(
t=sjcl.codec.utf8String.toBits(t)),i=i||sjcl.misc.hmac,e=new i(e);var s,o,u,a,f=
[],l=sjcl.bitArray;for(a=1;32*f.length<(r||1);a++){i=s=e.encrypt(l.concat(t,[a])
);for(o=1;o<n;o++){s=e.encrypt(s);for(u=0;u<s.length;u++)i[u]^=s[u]}f=f.concat(i
)}return r&&(f=l.clamp(f,r)),f}
```
- example usage
```shell
...
[r]!==s&&e[r]!==t[r]&&q(new sjcl.exception.invalid("required parameter overridden"
)),e[r]=t[r]);return e},fa:function(e,t){var n={},r;for(r in e)e.hasOwnProperty(
r)&&e[r]!==t[r]&&(n[r]=e[r]);return n},ea:function(e,t){var n={},r;for(r=0;r<t.length
;r++)e[t[r]]!==s&&(n[t[r]]=e[t[r]]);return n}},sjcl.encrypt=sjcl.json.encrypt,sjcl
.decrypt=sjcl.json.decrypt,sjcl.misc.ca={},sjcl.misc.cachedPbkdf2=function(e,t){
var n=sjcl.misc.ca,r;return t=t||{},r=t.iter||1e3,n=n[e]=n[e]||{},r=n[r]=n[r]||{
firstSalt:t.salt&&t.salt.length?t.salt.slice(0):sjcl.random.randomWords(2,0)},n=
t.salt===s?r.firstSalt:t.salt,r[n]=r[n]||sjcl.misc.pbkdf2(e,n,t.iter),{key:r[n].
slice(0),salt:n.slice(0)}}
local.sjcl = sjcl; }());
/* jslint-ignore-end */



// init lib sjcl.misc.scrypt
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.scrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.</span>scrypt (password, salt, N, r, p, length, Prff)](#apidoc.element.utility2.sjcl.misc.scrypt)
- description and source-code
```javascript
scrypt = function (password, salt, N, r, p, length, Prff) {
  var SIZE_MAX = Math.pow(2, 32) - 1,
      self = sjcl.misc.scrypt;

  N = N || 16384;
  r = r || 8;
  p = p || 1;

  if (r * p >= Math.pow(2, 30)) {
    throw sjcl.exception.invalid("The parameters r, p must satisfy r * p < 2^30");
  }

  if ((N < 2) || (N & (N - 1) != 0)) {
    throw sjcl.exception.invalid("The parameter N must be a power of 2.");
  }

  if (N > SIZE_MAX / 128 / r) {
    throw sjcl.exception.invalid("N too big.");
  }

  if (r > SIZE_MAX / 128 / p) {
    throw sjcl.exception.invalid("r too big.");
  }

  var blocks = sjcl.misc.pbkdf2(password, salt, 1, p * 128 * r * 8, Prff),
      len = blocks.length / p;

  self.reverse(blocks);

  for (var i = 0; i < p; i++) {
    var block = blocks.slice(i * len, (i + 1) * len);
    self.blockcopy(self.ROMix(block, N), 0, blocks, i * len);
  }

  self.reverse(blocks);

  return sjcl.misc.pbkdf2(password, blocks, 1, length, Prff);
}
```
- example usage
```shell
...
if (!options[3]) {
    options[3] = local.sjcl.codec.base64.fromBits(
        local.sjcl.random.randomWords(4, 0)
    );
}
// init hash
options[4] = local.sjcl.codec.base64.fromBits(
    local.sjcl.misc.scrypt(
        password || '',
        local.sjcl.codec.base64.toBits(options[3]),
        Math.pow(2, parseInt(options[2].slice(0, 1), 16)),
        parseInt(options[2].slice(1, 2), 16),
        parseInt(options[2].slice(3, 4), 16)
    )
);
...
```



# <a name="apidoc.module.utility2.sjcl.misc.hmac.prototype"></a>[module utility2.sjcl.misc.hmac.prototype](#apidoc.module.utility2.sjcl.misc.hmac.prototype)

#### <a name="apidoc.element.utility2.sjcl.misc.hmac.prototype.digest"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>digest ()](#apidoc.element.utility2.sjcl.misc.hmac.prototype.digest)
- description and source-code
```javascript
digest = function (){var e=this.G.finalize(),e=(new this.M(this
.n[1])).update(e).finalize();return this.reset(),e}
```
- example usage
```shell
...
// init lib istanbul.instrumenter
/* jslint-ignore-begin */
// https://github.com/gotwarlost/istanbul/blob/v0.3.20/lib/instrumenter.js
// utility2-uglifyjs https://raw.githubusercontent.com/gotwarlost/istanbul/v0.3.20/lib/instrumenter.js
// replace '(t?"":r)' with 'Math.random().toString(16).slice(2)'
(function () { var escodegen, esprima, module, window; escodegen = local.escodegen; esprima = local.esprima; module = undefined;
window = local;
(function(e){"use strict";function p(e,t){var n,r;return s!==null?(n=s.createHash
("md5"),n.update(e),r=n.digest("base64"),r=r.replace(new RegExp("=","g"),"").replace
(new RegExp("\\+","g"),"_").replace(new RegExp("/","g"),"$")):(window.__cov_seq=
window.__cov_seq||0,window.__cov_seq+=1,r=window.__cov_seq),"__cov_"+Math.random().toString(16).slice(2)}function d
(e,t){h(t)||(t=[t]),Array.prototype.push.apply(e,t)}function v(e,t,n,r){this.walkMap=
e,this.preprocessor=t,this.scope=n,this.debug=r,this.debug&&(this.level=0,this.seq=!0
)}function m(e,n){var r=e.type,i,s,o=t[r],u=!!e.loc||e.type===t.Program.name,a=u?
n.walkMap[r]:null,f,l,c,p,v,m,g,y,b,w,E;if(!t[r]){console.error(e),console.error
("Unsupported node type:"+r);return}o=t[r].children;if(e.walking)throw new Error
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.hmac.prototype.encrypt"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>encrypt (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.encrypt)
- description and source-code
```javascript
encrypt = function (e){return this.Q&&q(new sjcl.exception
.invalid("encrypt on already updated hmac called!")),this.update(e),this.digest(
e)}
```
- example usage
```shell
...
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
this.message},this.message=e},notReady:function(e){this.toString=function(){return"NOT READY: "+
this.message},this.message=e}}};"undefined"!=typeof module&&module.exports&&(module
.exports=sjcl),"function"==typeof define&&define([],function(){return sjcl}),sjcl
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.hmac.prototype.mac"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>mac (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.mac)
- description and source-code
```javascript
mac = function (e){return this.Q&&q(new sjcl.exception
.invalid("encrypt on already updated hmac called!")),this.update(e),this.digest(
e)}
```
- example usage
```shell
...
 * this function will create a base64-encoded sha-256 hmac
 * from the base64-encoded key and string data
 */
    return local.sjcl.codec.base64.fromBits(
        (new local.sjcl.misc.hmac(
            local.sjcl.codec.base64.toBits(key),
            local.sjcl.hash.sha256
        )).mac(local.sjcl.codec.utf8String.toBits(data))
    );
};

local.streamListCleanup = function (streamList) {
/*
 * this function will end or destroy the streams in streamList
 */
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.hmac.prototype.reset"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>reset ()](#apidoc.element.utility2.sjcl.misc.hmac.prototype.reset)
- description and source-code
```javascript
reset = function (){this.G=new this.M(this.n[0]),this.
Q=u}
```
- example usage
```shell
...
numberToken(t,i,s):isWhitespace(t)?r=this.whitespaceToken(t,i,s):isIdentStart(t)?
r=this.identOrFunctionToken(t,i,s):r=this.charToken(t,i,s)}break}return!r&&t===null&&
(r=this.createToken(Tokens.EOF,null,i,s)),r},createToken:function(e,t,n,r,i){var s=
this._reader;return i=i||{},{value:t,type:e,channel:i.channel,hide:i.hide||!1,startLine
:n,startCol:r,endLine:s.getLine(),endCol:s.getCol()}},atRuleToken:function(e,t,n
){var r=e,i=this._reader,s=Tokens.CHAR,o=!1,u,a;i.mark(),u=this.readName(),r=e+u
,s=Tokens.type(r.toLowerCase());if(s==Tokens.CHAR||s==Tokens.UNKNOWN)r.length>1?
s=Tokens.UNKNOWN_SYM:(s=Tokens.CHAR,r=e,i.reset());return this.createToken(s,r,t
,n)},charToken:function(e,t,n){var r=Tokens.type(e);return r==-1&&(r=Tokens.CHAR
),this.createToken(r,e,t,n)},commentToken:function(e,t,n){var r=this._reader,i=this
.readComment(e);return this.createToken(Tokens.COMMENT,i,t,n)},comparisonToken:function(
e,t,n){var r=this._reader,i=e+r.read(),s=Tokens.type(i)||Tokens.CHAR;return this
.createToken(s,i,t,n)},hashToken:function(e,t,n){var r=this._reader,i=this.readName
(e);return this.createToken(Tokens.HASH,i,t,n)},htmlCommentStartToken:function(e
,t,n){var r=this._reader,i=e;return r.mark(),i+=r.readCount(3),i=="<!--"?this.createToken
...
```

#### <a name="apidoc.element.utility2.sjcl.misc.hmac.prototype.update"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.misc.hmac.prototype.</span>update (e)](#apidoc.element.utility2.sjcl.misc.hmac.prototype.update)
- description and source-code
```javascript
update = function (e){this.Q=!0,this.G.update(e)}
```
- example usage
```shell
...
// init lib istanbul.instrumenter
/* jslint-ignore-begin */
// https://github.com/gotwarlost/istanbul/blob/v0.3.20/lib/instrumenter.js
// utility2-uglifyjs https://raw.githubusercontent.com/gotwarlost/istanbul/v0.3.20/lib/instrumenter.js
// replace '(t?"":r)' with 'Math.random().toString(16).slice(2)'
(function () { var escodegen, esprima, module, window; escodegen = local.escodegen; esprima = local.esprima; module = undefined;
window = local;
(function(e){"use strict";function p(e,t){var n,r;return s!==null?(n=s.createHash
("md5"),n.update(e),r=n.digest("base64"),r=r.replace(new RegExp("=","g"),"").replace
(new RegExp("\\+","g"),"_").replace(new RegExp("/","g"),"$")):(window.__cov_seq=
window.__cov_seq||0,window.__cov_seq+=1,r=window.__cov_seq),"__cov_"+Math.random().toString(16).slice(2)}function d
(e,t){h(t)||(t=[t]),Array.prototype.push.apply(e,t)}function v(e,t,n,r){this.walkMap=
e,this.preprocessor=t,this.scope=n,this.debug=r,this.debug&&(this.level=0,this.seq=!0
)}function m(e,n){var r=e.type,i,s,o=t[r],u=!!e.loc||e.type===t.Program.name,a=u?
n.walkMap[r]:null,f,l,c,p,v,m,g,y,b,w,E;if(!t[r]){console.error(e),console.error
("Unsupported node type:"+r);return}o=t[r].children;if(e.walking)throw new Error
...
```



# <a name="apidoc.module.utility2.sjcl.prng"></a>[module utility2.sjcl.prng](#apidoc.module.utility2.sjcl.prng)

#### <a name="apidoc.element.utility2.sjcl.prng.prng"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.</span>prng (e)](#apidoc.element.utility2.sjcl.prng.prng)
- description and source-code
```javascript
prng = function (e){this.c=[new sjcl.hash.sha256
],this.i=[0],this.F=0,this.s={},this.C=0,this.K={},this.O=this.d=this.j=this.W=0
,this.b=[0,0,0,0,0,0,0,0],this.f=[0,0,0,0],this.A=s,this.B=e,this.q=u,this.w={progress
:{},seeded:{}},this.m=this.V=0,this.t=1,this.u=2,this.S=65536,this.I=[0,48,64,96
,128,192,256,384,512,768,1024],this.T=3e4,this.R=80}
```
- example usage
```shell
...
s[n],delete i[r]},$:function(){E(1)},ba:function(e){var t,n;try{t=e.x||e.clientX||
e.offsetX||0,n=e.y||e.clientY||e.offsetY||0}catch(r){n=t=0}0!=t&&0!=n&&sjcl.random
.addEntropy([t,n],2,"mouse"),E(0)},da:function(e){e=e.touches[0]||e.changedTouches
[0],sjcl.random.addEntropy([e.pageX||e.clientX,e.pageY||e.clientY],1,"touch"),E(0
)},aa:function(){E(2)},U:function(e){e=e.accelerationIncludingGravity.x||e.accelerationIncludingGravity
.y||e.accelerationIncludingGravity.z;if(window.orientation){var t=window.orientation
;"number"==typeof t&&sjcl.random.addEntropy(t,1,"accelerometer")}e&&sjcl.random.
addEntropy(e,2,"accelerometer"),E(0)}},sjcl.random=new sjcl.prng(6);e:try{var F,
G,H,I;if(I="undefined"!=typeof module){var J;if(J=module.exports){var K;try{K=require
("crypto")}catch(L){K=null}J=(G=K)&&G.randomBytes}I=J}if(I)F=G.randomBytes(128),
F=new Uint32Array((new Uint8Array(F)).buffer),sjcl.random.addEntropy(F,1024,"crypto['randomBytes']"
);else if("undefined"!=typeof window&&"undefined"!=typeof Uint32Array){H=new Uint32Array
(32);if(window.crypto&&window.crypto.getRandomValues)window.crypto.getRandomValues
(H);else{if(!window.msCrypto||!window.msCrypto.getRandomValues)break e;window.msCrypto
.getRandomValues(H)}sjcl.random.addEntropy(H,1024,"crypto['getRandomValues']")}}
...
```



# <a name="apidoc.module.utility2.sjcl.prng.prototype"></a>[module utility2.sjcl.prng.prototype](#apidoc.module.utility2.sjcl.prng.prototype)

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.U"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>U (e)](#apidoc.element.utility2.sjcl.prng.prototype.U)
- description and source-code
```javascript
U = function (e){e=e.accelerationIncludingGravity.x||e.accelerationIncludingGravity
.y||e.accelerationIncludingGravity.z;if(window.orientation){var t=window.orientation
;"number"==typeof t&&sjcl.random.addEntropy(t,1,"accelerometer")}e&&sjcl.random.
addEntropy(e,2,"accelerometer"),E(0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.aa"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>aa ()](#apidoc.element.utility2.sjcl.prng.prototype.aa)
- description and source-code
```javascript
aa = function (){E(2)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.addEntropy"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>addEntropy (e, t, n)](#apidoc.element.utility2.sjcl.prng.prototype.addEntropy)
- description and source-code
```javascript
addEntropy = function (e, t, n){n=n||"user";var r,i,o=(new Date).valueOf(),u=this
.s[n],a=this.isReady(),f=0;r=this.K[n],r===s&&(r=this.K[n]=this.W++),u===s&&(u=this
.s[n]=0),this.s[n]=(this.s[n]+1)%this.c.length;switch(typeof e){case"number":t===
s&&(t=1),this.c[u].update([r,this.C++,1,t,o,1,e|0]);break;case"object":n=Object.
prototype.toString.call(e);if("[object Uint32Array]"===n){i=[];for(n=0;n<e.length
;n++)i.push(e[n]);e=i}else{"[object Array]"!==n&&(f=1);for(n=0;n<e.length&&!f;n++
)"number"!=typeof e[n]&&(f=1)}if(!f){if(t===s)for(n=t=0;n<e.length;n++)for(i=e[n
];0<i;)t++,i>>>=1;this.c[u].update([r,this.C++,2,t,o,e.length].concat(e))}break;
case"string":t===s&&(t=e.length),this.c[u].update([r,this.C++,3,t,o,e.length]),this
.c[u].update(e);break;default:f=1}f&&q(new sjcl.exception.bug("random: addEntropy only supports number, array of numbers or string
"
)),this.i[u]+=t,this.d+=t,a===this.m&&(this.isReady()!==this.m&&C("seeded",Math.
max(this.j,this.d)),C("progress",this.getProgress()))}
```
- example usage
```shell
...
r>>>18^r>>>3^r<<25^r<<14)+(i>>>17^i>>>19^i>>>10^i<<15^i<<13)+s[n&15]+s[n+9&15]|0
),r=r+v+(h>>>6^h>>>11^h>>>25^h<<26^h<<21^h<<7)+(d^h&(p^d))+u[n],v=d,d=p,p=h,h=c+
r|0,c=l,l=f,f=a,a=r+(f&l^c&(f^l))+(f>>>2^f>>>13^f>>>22^f<<30^f<<19^f<<10)|0;o[0]=
o[0]+a|0,o[1]=o[1]+f|0,o[2]=o[2]+l|0,o[3]=o[3]+c|0,o[4]=o[4]+h|0,o[5]=o[5]+p|0,o
[6]=o[6]+d|0,o[7]=o[7]+v|0}function C(e,t){var n,r=sjcl.random.w[e],i=[];for(n in
r)r.hasOwnProperty(n)&&i.push(r[n]);for(n=0;n<i.length;n++)i[n](t)}function E(e)
{"undefined"!=typeof window&&window.performance&&"function"==typeof window.performance
.now?sjcl.random.addEntropy(window.performance.now(),e,"loadtime"):sjcl.random.addEntropy
((new Date).valueOf(),e,"loadtime")}function A(e){e.b=B(e).concat(B(e)),e.A=new
sjcl.cipher.aes(e.b)}function B(e){for(var t=0;4>t&&(e.f[t]=e.f[t]+1|0,!e.f[t]);
t++);return e.A.encrypt(e.f)}function D(e,t){return function(){t.apply(e,arguments
)}}var s=void 0,u=!1,sjcl={cipher:{},hash:{},keyexchange:{},mode:{},misc:{},codec
:{},exception:{corrupt:function(e){this.toString=function(){return"CORRUPT: "+this
.message},this.message=e},invalid:function(e){this.toString=function(){return"INVALID: "+
this.message},this.message=e},bug:function(e){this.toString=function(){return"BUG: "+
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.addEventListener"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>addEventListener (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.addEventListener)
- description and source-code
```javascript
addEventListener = function (e, t)
{this.w[e][this.V++]=t}
```
- example usage
```shell
...
        // scroll textarea to bottom
        element.scrollTop = element.scrollHeight;
    };
});
// init event-handling
['change', 'click', 'keyup'].forEach(function (event) {
    Array.from(document.querySelectorAll('.on' + event)).forEach(function (element) {
        element.addEventListener(event, local.testRunBrowser);
    });
});
// run tests
local.testRunBrowser();
break;
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.ba"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>ba (e)](#apidoc.element.utility2.sjcl.prng.prototype.ba)
- description and source-code
```javascript
ba = function (e){var t,n;try{t=e.x||e.clientX||
e.offsetX||0,n=e.y||e.clientY||e.offsetY||0}catch(r){n=t=0}0!=t&&0!=n&&sjcl.random
.addEntropy([t,n],2,"mouse"),E(0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.da"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>da (e)](#apidoc.element.utility2.sjcl.prng.prototype.da)
- description and source-code
```javascript
da = function (e){e=e.touches[0]||e.changedTouches
[0],sjcl.random.addEntropy([e.pageX||e.clientX,e.pageY||e.clientY],1,"touch"),E(0
)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.getProgress"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>getProgress ( e)](#apidoc.element.utility2.sjcl.prng.prototype.getProgress)
- description and source-code
```javascript
getProgress = function ( e){return e=this.I[e?e:this.B],this.j>=e?1:this.d>e?1:this.d/e}
```
- example usage
```shell
...
prototype.toString.call(e);if("[object Uint32Array]"===n){i=[];for(n=0;n<e.length
;n++)i.push(e[n]);e=i}else{"[object Array]"!==n&&(f=1);for(n=0;n<e.length&&!f;n++
)"number"!=typeof e[n]&&(f=1)}if(!f){if(t===s)for(n=t=0;n<e.length;n++)for(i=e[n
];0<i;)t++,i>>>=1;this.c[u].update([r,this.C++,2,t,o,e.length].concat(e))}break;
case"string":t===s&&(t=e.length),this.c[u].update([r,this.C++,3,t,o,e.length]),this
.c[u].update(e);break;default:f=1}f&&q(new sjcl.exception.bug("random: addEntropy only supports number, array of numbers or string
"
)),this.i[u]+=t,this.d+=t,a===this.m&&(this.isReady()!==this.m&&C("seeded",Math.
max(this.j,this.d)),C("progress",this.getProgress()))},isReady:function(e){return e=
this.I[e!==s?e:this.B],this.j&&this.j>=e?this.i[0]>this.R&&(new Date).valueOf()>
this.O?this.u|this.t:this.t:this.d>=e?this.u|this.m:this.m},getProgress:function(
e){return e=this.I[e?e:this.B],this.j>=e?1:this.d>e?1:this.d/e},startCollectors:
function(){this.q||(this.a={loadTimeCollector:D(this,this.aa),mouseCollector:D(this
,this.ba),keyboardCollector:D(this,this.$),accelerometerCollector:D(this,this.U)
,touchCollector:D(this,this.da)},window.addEventListener?(window.addEventListener
("load",this.a.loadTimeCollector,u),window.addEventListener("mousemove",this.a.mouseCollector
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.isReady"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>isReady (e)](#apidoc.element.utility2.sjcl.prng.prototype.isReady)
- description and source-code
```javascript
isReady = function (e){return e=
this.I[e!==s?e:this.B],this.j&&this.j>=e?this.i[0]>this.R&&(new Date).valueOf()>
this.O?this.u|this.t:this.t:this.d>=e?this.u|this.m:this.m}
```
- example usage
```shell
...
[],l=sjcl.bitArray;for(a=1;32*f.length<(r||1);a++){i=s=e.encrypt(l.concat(t,[a])
);for(o=1;o<n;o++){s=e.encrypt(s);for(u=0;u<s.length;u++)i[u]^=s[u]}f=f.concat(i
)}return r&&(f=l.clamp(f,r)),f},sjcl.prng=function(e){this.c=[new sjcl.hash.sha256
],this.i=[0],this.F=0,this.s={},this.C=0,this.K={},this.O=this.d=this.j=this.W=0
,this.b=[0,0,0,0,0,0,0,0],this.f=[0,0,0,0],this.A=s,this.B=e,this.q=u,this.w={progress
:{},seeded:{}},this.m=this.V=0,this.t=1,this.u=2,this.S=65536,this.I=[0,48,64,96
,128,192,256,384,512,768,1024],this.T=3e4,this.R=80},sjcl.prng.prototype={randomWords
:function(e,t){var n=[],r;r=this.isReady(t);var i;r===this.m&&q(new sjcl.exception
.notReady("generator isn't seeded"));if(r&this.u){r=!(r&this.t),i=[];var s=0,o;this
.O=i[0]=(new Date).valueOf()+this.T;for(o=0;16>o;o++)i.push(4294967296*Math.random
()|0);for(o=0;o<this.c.length&&!(i=i.concat(this.c[o].finalize()),s+=this.i[o],this
.i[o]=0,!r&&this.F&1<<o);o++);this.F>=1<<this.c.length&&(this.c.push(new sjcl.hash
.sha256),this.i.push(0)),this.d-=s,s>this.j&&(this.j=s),this.F++,this.b=sjcl.hash
.sha256.hash(this.b.concat(i)),this.A=new sjcl.cipher.aes(this.b);for(r=0;4>r&&(
this.f[r]=this.f[r]+1|0,!this.f[r]);r++);}for(r=0;r<e;r+=4)0===(r+1)%this.S&&A(this
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.randomWords"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>randomWords (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.randomWords)
- description and source-code
```javascript
randomWords = function (e, t){var n=[],r;r=this.isReady(t);var i;r===this.m&&q(new sjcl.exception
.notReady("generator isn't seeded"));if(r&this.u){r=!(r&this.t),i=[];var s=0,o;this
.O=i[0]=(new Date).valueOf()+this.T;for(o=0;16>o;o++)i.push(4294967296*Math.random
()|0);for(o=0;o<this.c.length&&!(i=i.concat(this.c[o].finalize()),s+=this.i[o],this
.i[o]=0,!r&&this.F&1<<o);o++);this.F>=1<<this.c.length&&(this.c.push(new sjcl.hash
.sha256),this.i.push(0)),this.d-=s,s>this.j&&(this.j=s),this.F++,this.b=sjcl.hash
.sha256.hash(this.b.concat(i)),this.A=new sjcl.cipher.aes(this.b);for(r=0;4>r&&(
this.f[r]=this.f[r]+1|0,!this.f[r]);r++);}for(r=0;r<e;r+=4)0===(r+1)%this.S&&A(this
),i=B(this),n.push(i[0],i[1],i[2],i[3]);return A(this),n.slice(0,e)}
```
- example usage
```shell
...
);else if("undefined"!=typeof window&&"undefined"!=typeof Uint32Array){H=new Uint32Array
(32);if(window.crypto&&window.crypto.getRandomValues)window.crypto.getRandomValues
(H);else{if(!window.msCrypto||!window.msCrypto.getRandomValues)break e;window.msCrypto
.getRandomValues(H)}sjcl.random.addEntropy(H,1024,"crypto['getRandomValues']")}}
catch(M){"undefined"!=typeof window&&window.console&&(console.log("There was an error collecting entropy from the browser:"
),console.log(M))}sjcl.json={defaults:{v:1,iter:1e3,ks:128,ts:64,mode:"ccm",adata
:"",cipher:"aes"},Y:function(e,t,n,r){n=n||{},r=r||{};var i=sjcl.json,s=i.e({iv:
sjcl.random.randomWords(4,0)},i.defaults),o;return i.e(s,n),n=s.adata,"string"==typeof
s.salt&&(s.salt=sjcl.codec.base64.toBits(s.salt)),"string"==typeof s.iv&&(s.iv=sjcl
.codec.base64.toBits(s.iv)),(!sjcl.mode[s.mode]||!sjcl.cipher[s.cipher]||"string"==typeof
e&&100>=s.iter||64!==s.ts&&96!==s.ts&&128!==s.ts||128!==s.ks&&192!==s.ks&&256!==
s.ks||2>s.iv.length||4<s.iv.length)&&q(new sjcl.exception.invalid("json encrypt: invalid parameters"
)),"string"==typeof e?(o=sjcl.misc.cachedPbkdf2(e,s),e=o.key.slice(0,s.ks/32),s.
salt=o.salt):sjcl.ecc&&e instanceof sjcl.ecc.elGamal.publicKey&&(o=e.kem(),s.kemtag=
o.tag,e=o.key.slice(0,s.ks/32)),"string"==typeof t&&(t=sjcl.codec.utf8String.toBits
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.removeEventListener"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>removeEventListener (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.removeEventListener)
- description and source-code
```javascript
removeEventListener = function (e, t){var n,r,i=this.w[e],s=
[];for(r in i)i.hasOwnProperty(r)&&i[r]===t&&s.push(r);for(n=0;n<s.length;n++)r=
s[n],delete i[r]}
```
- example usage
```shell
...
("load",this.a.loadTimeCollector,u),window.addEventListener("mousemove",this.a.mouseCollector
,u),window.addEventListener("keypress",this.a.keyboardCollector,u),window.addEventListener
("devicemotion",this.a.accelerometerCollector,u),window.addEventListener("touchmove"
,this.a.touchCollector,u)):document.attachEvent?(document.attachEvent("onload",this
.a.loadTimeCollector),document.attachEvent("onmousemove",this.a.mouseCollector),
document.attachEvent("keypress",this.a.keyboardCollector)):q(new sjcl.exception.
bug("can't attach event")),this.q=!0)},stopCollectors:function(){this.q&&(window
.removeEventListener?(window.removeEventListener("load",this.a.loadTimeCollector
,u),window.removeEventListener("mousemove",this.a.mouseCollector,u),window.removeEventListener
("keypress",this.a.keyboardCollector,u),window.removeEventListener("devicemotion"
,this.a.accelerometerCollector,u),window.removeEventListener("touchmove",this.a.
touchCollector,u)):document.detachEvent&&(document.detachEvent("onload",this.a.loadTimeCollector
),document.detachEvent("onmousemove",this.a.mouseCollector),document.detachEvent
("keypress",this.a.keyboardCollector)),this.q=u)},addEventListener:function(e,t)
{this.w[e][this.V++]=t},removeEventListener:function(e,t){var n,r,i=this.w[e],s=
...
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.setDefaultParanoia"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>setDefaultParanoia (e, t)](#apidoc.element.utility2.sjcl.prng.prototype.setDefaultParanoia)
- description and source-code
```javascript
setDefaultParanoia = function (e, t){0===e&&"Setting paranoia=0 will ruin your security; use it only for testing"!==
t&&q("Setting paranoia=0 will ruin your security; use it only for testing"),this
.B=e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.startCollectors"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>startCollectors ()](#apidoc.element.utility2.sjcl.prng.prototype.startCollectors)
- description and source-code
```javascript
startCollectors = function (){this.q||(this.a={loadTimeCollector:D(this,this.aa),mouseCollector:D(this
,this.ba),keyboardCollector:D(this,this.$),accelerometerCollector:D(this,this.U)
,touchCollector:D(this,this.da)},window.addEventListener?(window.addEventListener
("load",this.a.loadTimeCollector,u),window.addEventListener("mousemove",this.a.mouseCollector
,u),window.addEventListener("keypress",this.a.keyboardCollector,u),window.addEventListener
("devicemotion",this.a.accelerometerCollector,u),window.addEventListener("touchmove"
,this.a.touchCollector,u)):document.attachEvent?(document.attachEvent("onload",this
.a.loadTimeCollector),document.attachEvent("onmousemove",this.a.mouseCollector),
document.attachEvent("keypress",this.a.keyboardCollector)):q(new sjcl.exception.
bug("can't attach event")),this.q=!0)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.sjcl.prng.prototype.stopCollectors"></a>[function <span class="apidocSignatureSpan">utility2.sjcl.prng.prototype.</span>stopCollectors ()](#apidoc.element.utility2.sjcl.prng.prototype.stopCollectors)
- description and source-code
```javascript
stopCollectors = function (){this.q&&(window
.removeEventListener?(window.removeEventListener("load",this.a.loadTimeCollector
,u),window.removeEventListener("mousemove",this.a.mouseCollector,u),window.removeEventListener
("keypress",this.a.keyboardCollector,u),window.removeEventListener("devicemotion"
,this.a.accelerometerCollector,u),window.removeEventListener("touchmove",this.a.
touchCollector,u)):document.detachEvent&&(document.detachEvent("onload",this.a.loadTimeCollector
),document.detachEvent("onmousemove",this.a.mouseCollector),document.detachEvent
("keypress",this.a.keyboardCollector)),this.q=u)}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.utility2.uglifyjs"></a>[module utility2.uglifyjs](#apidoc.module.utility2.uglifyjs)

#### <a name="apidoc.element.utility2.uglifyjs.MAP"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP)
- description and source-code
```javascript
MAP = function (r, i, s){function f(){var f=i.call(s,r[a],a);f instanceof t?(f=f.v,f instanceof n?u.
push.apply(u,f.v):u.push(f)):f!=e&&(f instanceof n?o.push.apply(o,f.v):o.push(f)
)}var o=[],u=[],a;if(r instanceof Array)for(a=0;a<r.length;++a)f();else for(a in
r)HOP(r,a)&&f();return u.concat(o)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.array_to_hash"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>array_to_hash (e)](#apidoc.element.utility2.uglifyjs.array_to_hash)
- description and source-code
```javascript
function array_to_hash(e){var t={};for(var n=0
;n<e.length;++n)t[e[n]]=!0;return t}
```
- example usage
```shell
...
s){case"string":o=["string",s];break;case"number":o=["num",s];break;case"boolean"
:o=["name",String(s)];break;default:if(s===null){o=["atom","null"];break}throw new
Error("Can't handle constant of type: "+typeof s)}return r.call(n,o,s)}catch(u){
if(u===e){if(n[0]!="binary"||n[1]!="==="&&n[1]!="!=="||!(is_string(n[2])&&is_string
(n[3])||boolean_expr(n[2])&&boolean_expr(n[3]))){if(i&&n[0]=="binary"&&(n[1]=="||"||
n[1]=="&&"))try{var a=t(n[2]);n=n[1]=="&&"&&(a?n[3]:a)||n[1]=="||"&&(a?a:n[3])||
n}catch(f){}}else n[1]=n[1].substr(0,2);return i?i.call(n,n):null}throw u}}}(),DOT_CALL_NO_PARENS=
jsp.array_to_hash(["name","array","object","string","dot","sub","call","regexp","defun"
]),SPLICE_NEEDS_BRACKETS=jsp.array_to_hash(["if","while","do","for","for-in","with"
]),MAP;(function(){function t(e){this.v=e}function n(e){this.v=e}MAP=function(r,
i,s){function f(){var f=i.call(s,r[a],a);f instanceof t?(f=f.v,f instanceof n?u.
push.apply(u,f.v):u.push(f)):f!=e&&(f instanceof n?o.push.apply(o,f.v):o.push(f)
)}var o=[],u=[],a;if(r instanceof Array)for(a=0;a<r.length;++a)f();else for(a in
r)HOP(r,a)&&f();return u.concat(o)},MAP.at_top=function(e){return new t(e)},MAP.
splice=function(e){return new n(e)};var e=MAP.skip={}})(),exports.ast_walker=ast_walker
...
```

#### <a name="apidoc.element.utility2.uglifyjs.ast_add_scope"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_add_scope (e)](#apidoc.element.utility2.uglifyjs.ast_add_scope)
- description and source-code
```javascript
function ast_add_scope(e){function s(e){t=new Scope(t),t.labels=new Scope;var n=
t.body=e();return n.scope=t,t=t.parent,n}function o(e,n){return t.define(e,n)}function u
(e){t.refs[e]=!0}function a(e,t,n){var i=this[0]=="defun";return[this[0],i?o(e,"defun"
):e,t,s(function(){return i||o(e,"lambda"),MAP(t,function(e){o(e,"arg")}),MAP(n,
r)})]}function f(e){return function(t){MAP(t,function(t){o(t[0],e),t[1]&&u(t[0])
})}}function l(e){e&&(t.labels.refs[e]=!0)}var t=null,n=ast_walker(),r=n.walk,i=
[];return s(function(){function c(e,t){for(t=e.children.length;--t>=0;)c(e.children
[t]);for(t in e.refs)if(HOP(e.refs,t))for(var n=e.has(t),r=e;r;r=r.parent){r.refs
[t]=n;if(r===n)break}}var s=n.with_walkers({"function":a,defun:a,label:function(
e,n){t.labels.define(e)},"break":l,"continue":l,"with":function(e,n){for(var r=t
;r;r=r.parent)r.uses_with=!0},"var":f("var"),"const":f("const"),"try":function(e
,t,n){if(t!=null)return[this[0],MAP(e,r),[o(t[0],"catch"),MAP(t[1],r)],n!=null?MAP
(n,r):null]},name:function(e){e=="eval"&&i.push(t),u(e)}},function(){return r(e)
});return MAP(i,function(e){if(!e.has("eval"))while(e)e.uses_eval=!0,e=e.parent}
),c(t),s})}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.ast_lift_variables"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_lift_variables (e)](#apidoc.element.utility2.uglifyjs.ast_lift_variables)
- description and source-code
```javascript
function ast_lift_variables(e){function i(e,t){var i=r;r=t,e=MAP(e,n);var s=
{},o=MAP(t.names,function(e,n){return e!="var"?MAP.skip:t.references(n)?(s[n]=!0
,[n]):MAP.skip});return o.length>0&&(for_side_effects(["block",e],function(e,t,n
,r){if(e[0]=="assign"&&e[1]===!0&&e[2][0]=="name"&&HOP(s,e[2][1])){for(var i=o.length
;--i>=0;)if(o[i][0]==e[2][1]){o[i][1]&&n(),o[i][1]=e[3],o.push(o.splice(i,1)[0])
;break}var u=t.parent();if(u[0]=="seq"){var a=u[2];a.unshift(0,u.length),u.splice
.apply(u,a)}else u[0]=="stat"?u.splice(0,u.length,"block"):n();r()}n()}),e.unshift
(["var",o])),r=i,e}function s(e){var n=null;for(var r=e.length;--r>=0;){var i=e[
r];if(!i[1])continue;i=["assign",!0,["name",i[0]],i[1]],n==null?n=i:n=["seq",i,n
]}return n==null&&t.parent()[0]!="for"?t.parent()[0]=="for-in"?["name",e[0][0]]:
MAP.skip:["stat",n]}function o(e){return[this[0],i(e,this.scope)]}var t=ast_walker
(),n=t.walk,r;return t.with_walkers({"function":function(e,t,n){for(var r=t.length
;--r>=0&&!n.scope.references(t[r]);)t.pop();return n.scope.references(e)||(e=null
),[this[0],e,t,i(n,n.scope)]},defun:function(e,t,n){if(!r.references(e))return MAP
.skip;for(var s=t.length;--s>=0&&!n.scope.references(t[s]);)t.pop();return[this[0
],e,t,i(n,n.scope)]},"var":s,toplevel:o},function(){return n(ast_add_scope(e))})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.ast_mangle"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_mangle (e, t)](#apidoc.element.utility2.uglifyjs.ast_mangle)
- description and source-code
```javascript
function ast_mangle(e, t){function s(e,n){return t.mangle?!t.toplevel&&!
i.parent?e:t.except&&member(e,t.except)?e:t.no_functions&&HOP(i.names,e)&&(i.names
[e]=="defun"||i.names[e]=="lambda")?e:i.get_mangled(e,n):e}function o(e){if(t.defines
)return!i.has(e)&&HOP(t.defines,e)?t.defines[e]:null}function u(e,n,o){if(!t.no_functions&&
t.mangle){var u=this[0]=="defun",f;e&&(u?e=s(e):o.scope.references(e)?(f={},!i.uses_eval&&!
i.uses_with?e=f[e]=i.next_mangled():f[e]=e):e=null)}return o=a(o.scope,function(
){return n=MAP(n,function(e){return s(e)}),MAP(o,r)},f),[this[0],e,n,o]}function a
(e,t,n){var r=i;i=e;if(n)for(var o in n)HOP(n,o)&&e.set_mangle(o,n[o]);for(var o in
e.names)HOP(e.names,o)&&s(o,!0);var u=t();return u.scope=e,i=r,u}function f(e){return[
this[0],MAP(e,function(e){return[s(e[0]),r(e[1])]})]}function l(e){if(e)return[this
[0],i.labels.get_mangled(e)]}var n=ast_walker(),r=n.walk,i;return t=defaults(t,{
mangle:!0,toplevel:!1,defines:null,except:null,no_functions:!1}),n.with_walkers(
{"function":u,defun:function(){var e=u.apply(this,arguments);switch(n.parent()[0
]){case"toplevel":case"function":case"defun":return MAP.at_top(e)}return e},label
:function(e,t){return i.labels.refs[e]?[this[0],i.labels.get_mangled(e,!0),r(t)]
:r(t)},"break":l,"continue":l,"var":f,"const":f,name:function(e){return o(e)||[this
[0],s(e)]},"try":function(e,t,n){return[this[0],MAP(e,r),t!=null?[s(t[0]),MAP(t[1
],r)]:null,n!=null?MAP(n,r):null]},toplevel:function(e){var t=this;return a(t.scope
,function(){return[t[0],MAP(e,r)]})},directive:function(){return MAP.at_top(this
)}},function(){return r(ast_add_scope(e))})}
```
- example usage
```shell
...
        }
        // parse code and get the initial AST
        ast = local.parse(code
            .trim()
            // comment shebang
            .replace((/^#!/), '//'));
        // get a new AST with mangled names
        ast = local.ast_mangle(ast);
        // get an AST with compression optimizations
        ast = local.ast_squeeze(ast);
        // compressed code here
        return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
    };
}());
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.uglifyjs.ast_squeeze"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_squeeze (e, t)](#apidoc.element.utility2.uglifyjs.ast_squeeze)
- description and source-code
```javascript
function ast_squeeze(e, t){return e=squeeze_1(e,t),e=squeeze_2(e,t),e}
```
- example usage
```shell
...
        ast = local.parse(code
            .trim()
            // comment shebang
            .replace((/^#!/), '//'));
        // get a new AST with mangled names
        ast = local.ast_mangle(ast);
        // get an AST with compression optimizations
        ast = local.ast_squeeze(ast);
        // compressed code here
        return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
    };
}());
switch (local.modeJs) {
...
```

#### <a name="apidoc.element.utility2.uglifyjs.ast_walker"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>ast_walker ()](#apidoc.element.utility2.uglifyjs.ast_walker)
- description and source-code
```javascript
function ast_walker(){function e(e){return[this[0],MAP(e,function(e){var t=[e[0]
];return e.length>1&&(t[1]=s(e[1])),t})]}function t(e){var t=[this[0]];return e!=
null&&t.push(MAP(e,s)),t}function s(e){if(e==null)return null;try{i.push(e);var t=
e[0],s=r[t];if(s){var o=s.apply(e,e.slice(1));if(o!=null)return o}return s=n[t],
s.apply(e,e.slice(1))}finally{i.pop()}}function o(e){if(e==null)return null;try{
return i.push(e),n[e[0]].apply(e,e.slice(1))}finally{i.pop()}}function u(e,t){var n=
{},i;for(i in e)HOP(e,i)&&(n[i]=r[i],r[i]=e[i]);var s=t();for(i in n)HOP(n,i)&&(
n[i]?r[i]=n[i]:delete r[i]);return s}var n={string:function(e){return[this[0],e]
},num:function(e){return[this[0],e]},name:function(e){return[this[0],e]},toplevel
:function(e){return[this[0],MAP(e,s)]},block:t,splice:t,"var":e,"const":e,"try":
function(e,t,n){return[this[0],MAP(e,s),t!=null?[t[0],MAP(t[1],s)]:null,n!=null?
MAP(n,s):null]},"throw":function(e){return[this[0],s(e)]},"new":function(e,t){return[
this[0],s(e),MAP(t,s)]},"switch":function(e,t){return[this[0],s(e),MAP(t,function(
e){return[e[0]?s(e[0]):null,MAP(e[1],s)]})]},"break":function(e){return[this[0],
e]},"continue":function(e){return[this[0],e]},conditional:function(e,t,n){return[
this[0],s(e),s(t),s(n)]},assign:function(e,t,n){return[this[0],e,s(t),s(n)]},dot
:function(e){return[this[0],s(e)].concat(slice(arguments,1))},call:function(e,t)
{return[this[0],s(e),MAP(t,s)]},"function":function(e,t,n){return[this[0],e,t.slice
(),MAP(n,s)]},"debugger":function(){return[this[0]]},defun:function(e,t,n){return[
this[0],e,t.slice(),MAP(n,s)]},"if":function(e,t,n){return[this[0],s(e),s(t),s(n
)]},"for":function(e,t,n,r){return[this[0],s(e),s(t),s(n),s(r)]},"for-in":function(
e,t,n,r){return[this[0],s(e),s(t),s(n),s(r)]},"while":function(e,t){return[this[0
],s(e),s(t)]},"do":function(e,t){return[this[0],s(e),s(t)]},"return":function(e)
{return[this[0],s(e)]},binary:function(e,t,n){return[this[0],e,s(t),s(n)]},"unary-prefix"
:function(e,t){return[this[0],e,s(t)]},"unary-postfix":function(e,t){return[this
[0],e,s(t)]},sub:function(e,t){return[this[0],s(e),s(t)]},object:function(e){return[
this[0],MAP(e,function(e){return e.length==2?[e[0],s(e[1])]:[e[0],s(e[1]),e[2]]}
)]},regexp:function(e,t){return[this[0],e,t]},array:function(e){return[this[0],MAP
(e,s)]},stat:function(e){return[this[0],s(e)]},seq:function(){return[this[0]].concat
(MAP(slice(arguments),s))},label:function(e,t){return[this[0],e,s(t)]},"with":function(
e,t){return[this[0],s(e),s(t)]},atom:function(e){return[this[0],e]},directive:function(
e){return[this[0],e]}},r={},i=[];return{walk:s,dive:o,with_walkers:u,parent:function(
){return i[i.length-2]},stack:function(){return i}}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.curry"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>curry (e)](#apidoc.element.utility2.uglifyjs.curry)
- description and source-code
```javascript
function curry(e){var t=
slice(arguments,1);return function(){return e.apply(this,t.concat(slice(arguments
)))}}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.gen_code"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>gen_code (e, t)](#apidoc.element.utility2.uglifyjs.gen_code)
- description and source-code
```javascript
function gen_code(e, t){function o(
e){var n=make_string(e,t.ascii_only);return t.inline_script&&(n=n.replace(/<\x2fscript([>\/\t\n\f\r ])/gi
,"<\\/script$1")),n}function u(e){return e=e.toString(),t.ascii_only&&(e=to_ascii
(e)),e}function a(e){return e==null&&(e=""),n&&(e=repeat_string(" ",t.indent_start+
r*t.indent_level)+e),e}function f(e,t){t==null&&(t=1),r+=t;try{return e.apply(null
,slice(arguments,1))}finally{r-=t}}function l(e){return e=e.toString(),e.charAt(
e.length-1)}function c(e){return e.toString().charAt(0)}function h(e){if(n)return e
.join(" ");var t=[];for(var r=0;r<e.length;++r){var i=e[r+1];t.push(e[r]),i&&(is_identifier_char
(l(e[r]))&&(is_identifier_char(c(i))||c(i)=="\\")||/[\+\-]$/.test(e[r].toString(
))&&/^[\+\-]/.test(i.toString())||l(e[r])=="/"&&c(i)=="/")&&t.push(" ")}return t
.join("")}function p(e){return e.join(","+s)}function d(e){var t=b(e);for(var n=1
;n<arguments.length;++n){var r=arguments[n];if(r instanceof Function&&r(e)||e[0]==
r)return"("+t+")"}return t}function v(e){if(e.length==1)return e[0];if(e.length==2
){var t=e[1];return e=e[0],e.length<=t.length?e:t}return v([e[0],v(e.slice(1))])
}function m(e){if(e[0]=="function"||e[0]=="object"){var t=slice(y.stack()),n=t.pop
(),r=t.pop();while(r){if(r[0]=="stat")return!0;if((r[0]!="seq"&&r[0]!="call"&&r[0
]!="dot"&&r[0]!="sub"&&r[0]!="conditional"||r[1]!==n)&&(r[0]!="binary"&&r[0]!="assign"&&
r[0]!="unary-postfix"||r[2]!==n))return!1;n=r,r=t.pop()}}return!HOP(DOT_CALL_NO_PARENS
,e[0])}function g(e){var t=e.toString(10),n=[t.replace(/^0\./,".").replace("e+","e"
)],r;return Math.floor(e)===e?(e>=0?n.push("0x"+e.toString(16).toLowerCase(),"0"+
e.toString(8)):n.push("-0x"+(-e).toString(16).toLowerCase(),"-0"+(-e).toString(8
)),(r=/^(.*?)(0+)$/.exec(e))&&n.push(r[1]+"e"+r[2].length)):(r=/^0?\.(0+)(.*)$/.
exec(e))&&n.push(r[2]+"e-"+(r[1].length+r[2].length),t.substr(t.indexOf("."))),v
(n)}function w(e){if(e==null)return";";if(e[0]=="do")return N([e]);var t=e;for(;
;){var n=t[0];if(n=="if"){if(!t[3])return b(["block",[e]]);t=t[3]}else if(n=="while"||
n=="do")t=t[2];else{if(n!="for"&&n!="for-in")break;t=t[4]}}return b(e)}function E
(e,t,n,r,i){var s=r||"function";return e&&(s+=" "+u(e)),s+="("+p(MAP(t,u))+")",s=
h([s,N(n)]),!i&&m(this)?"("+s+")":s}function S(e){switch(e[0]){case"with":case"while"
:return empty(e[2])||S(e[2]);case"for":case"for-in":return empty(e[4])||S(e[4]);
case"if":if(empty(e[2])&&!e[3])return!0;if(e[3])return empty(e[3])?!0:S(e[3]);return S
(e[2]);case"directive":return!0}}function x(e,t){for(var r=[],i=e.length-1,s=0;s<=
i;++s){var o=e[s],u=b(o);u!=";"&&(!n&&s==i&&!S(o)&&(u=u.replace(/;+\s*$/,"")),r.
push(u))}return t?r:MAP(r,a)}function T(e){var t=e.length;return t==0?"{}":"{"+i+
MAP(e,function(e,r){var s=e[1].length>0,o=f(function(){return a(e[0]?h(["case",b
(e[0])+":"]):"default:")},.5)+(s?i+f(function(){return x(e[1]).join(i)}):"");return!
n&&s&&r<t-1&&(o+=";"),o}).join(i)+i+a("}")}function N(e){return e?e.length==0?"{}"
:"{"+i+f(function(){return x(e).join(i)})+i+a("}"):";"}function C(e){var t=e[0],
n=e[1];return n!=null&&(t=h([u(t),"=",d(n,"seq")])),t}t=defaults(t,{indent_start
:0,indent_level:4,quote_keys:!1,space_colon:!1,beautify:!1,ascii_only:!1,inline_script
:!1});var n=!!t.beautify,r=0,i=n?"\n":"",s=n?" ":"",y=ast_walker(),b=y.walk;return y
.with_walkers({string:o,num:g,name:u,"debugger":function(){return"debugger;"},toplevel
:function(e){return x(e).join(i+i)},splice:function(e){var t=y.parent();return HOP
(SPLICE_NEEDS_BRACKETS,t)?N.apply(this,arguments):MAP(x(e,!0),function(e,t){return t>0?
a(e):e}).join(i)},block:N,"var":function(e){return"var "+p(MAP(e,C))+";"},"const"
:function(e){return"const "+p(MAP(e,C))+";"},"try":function(e,t,n){var r=["try",
N(e)];return t&&r.push("catch","("+t[0]+")",N(t[1])),n&&r.push("finally",N(n)),h
(r)},"throw":function(e){return h(["throw",b(e)])+";"},"new":function(e,t){return t=
t.length>0?"("+p(MAP(t,function(e){return d(e,"seq")}))+")":"",h(["new",d(e,"seq"
,"binary","conditional","assign",function(e){var t=ast_walker(),n={};try{t.with_walkers
({call:function(){throw n},"fun ...
```
- example usage
```shell
...
            // comment shebang
            .replace((/^#!/), '//'));
        // get a new AST with mangled names
        ast = local.ast_mangle(ast);
        // get an AST with compression optimizations
        ast = local.ast_squeeze(ast);
        // compressed code here
        return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
    };
}());
switch (local.modeJs) {



/* istanbul ignore next */
...
```

#### <a name="apidoc.element.utility2.uglifyjs.is_alphanumeric_char"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_alphanumeric_char (e)](#apidoc.element.utility2.uglifyjs.is_alphanumeric_char)
- description and source-code
```javascript
function is_alphanumeric_char(e){return is_digit(e)||is_letter(e)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.is_identifier_char"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_identifier_char (e)](#apidoc.element.utility2.uglifyjs.is_identifier_char)
- description and source-code
```javascript
function is_identifier_char(e){return is_identifier_start
(e)||is_unicode_combining_mark(e)||is_unicode_digit(e)||is_unicode_connector_punctuation
(e)||e=="\u200c"||e=="\u200d"}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.is_identifier_start"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>is_identifier_start (e)](#apidoc.element.utility2.uglifyjs.is_identifier_start)
- description and source-code
```javascript
function is_identifier_start(e)
{return e=="$"||e=="_"||is_letter(e)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.make_string"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>make_string (e, t)](#apidoc.element.utility2.uglifyjs.make_string)
- description and source-code
```javascript
function make_string(e, t){var n=0,r=0;return e=
e.replace(/[\\\b\f\n\r\t\x22\x27\u2028\u2029\0]/g,function(e){switch(e){case"\\"
:return"\\\\";case"\b":return"\\b";case"\f":return"\\f";case"\n":return"\\n";case"\r"
:return"\\r";case"\u2028":return"\\u2028";case"\u2029":return"\\u2029";case'"':return++
n,'"';case"'":return++r,"'";case"\0":return"\\0"}return e}),t&&(e=to_ascii(e)),n>
r?"'"+e.replace(/\x27/g,"\\'")+"'":'"'+e.replace(/\x22/g,'\\"')+'"'}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.member"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>member (e, t)](#apidoc.element.utility2.uglifyjs.member)
- description and source-code
```javascript
function member(e, t){for(
var n=t.length;--n>=0;)if(t[n]==e)return!0;return!1}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.parse"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>parse (e, t, n)](#apidoc.element.utility2.uglifyjs.parse)
- description and source-code
```javascript
function parse(e, t, n){function i(e,t){return is_token(r.token,e,t)}function s(){return r.peeked||
(r.peeked=r.input())}function o(){return r.prev=r.token,r.peeked?(r.token=r.peeked
,r.peeked=null):r.token=r.input(),r.in_directives=r.in_directives&&(r.token.type=="string"||
i("punc",";")),r.token}function u(){return r.prev}function a(e,t,n,i){var s=r.input
.context();js_error(e,t!=null?t:s.tokline,n!=null?n:s.tokcol,i!=null?i:s.tokpos)
}function f(e,t){a(t,e.line,e.col)}function l(e){e==null&&(e=r.token),f(e,"Unexpected token: "+
e.type+" ("+e.value+")")}function c(e,t){if(i(e,t))return o();f(r.token,"Unexpected token "+
r.token.type+", expected "+e)}function h(e){return c("punc",e)}function p(){return!
t&&(r.token.nlb||i("eof")||i("punc","}"))}function d(){i("punc",";")?o():p()||l(
)}function v(){return slice(arguments)}function m(){h("(");var e=K();return h(")"
),e}function g(e,t,n){return e instanceof NodeWithToken?e:new NodeWithToken(e,t,
n)}function y(e){return n?function(){var t=r.token,n=e.apply(this,arguments);return n
[0]=g(n[0],t,u()),n}:e}function w(e){r.labels.push(e);var n=r.token,i=b();return t&&!
HOP(STATEMENTS_WITH_LABELS,i[0])&&l(n),r.labels.pop(),v("label",e,i)}function E(
){return v("stat",prog1(K,d))}function S(e){var t;return p()||(t=i("name")?r.token
.value:null),t!=null?(o(),member(t,r.labels)||a("Label "+t+" without matching loop or statement"
)):r.in_loop==0&&a(e+" not inside a loop or switch"),d(),v(e,t)}function x(){h("("
);var e=null;if(!i("punc",";")){e=i("keyword","var")?(o(),_(!0)):K(!0,!0);if(i("operator"
,"in"))return e[0]=="var"&&e[1].length>1&&a("Only one variable declaration allowed in for..in loop"
),N(e)}return T(e)}function T(e){h(";");var t=i("punc",";")?null:K();h(";");var n=
i("punc",")")?null:K();return h(")"),v("for",e,t,n,Q(b))}function N(e){var t=e[0
]=="var"?v("name",e[1][0]):e;o();var n=K();return h(")"),v("for-in",e,t,n,Q(b))}
function k(){var e=m(),t=b(),n;return i("keyword","else")&&(o(),n=b()),v("if",e,
t,n)}function L(){h("{");var e=[];while(!i("punc","}"))i("eof")&&l(),e.push(b())
;return o(),e}function O(){var e=L(),t,n;if(i("keyword","catch")){o(),h("("),i("name"
)||a("Name expected");var s=r.token.value;o(),h(")"),t=[s,L()]}return i("keyword"
,"finally")&&(o(),n=L()),!t&&!n&&a("Missing catch/finally blocks"),v("try",e,t,n
)}function M(e){var t=[];for(;;){i("name")||l();var n=r.token.value;o(),i("operator"
,"=")?(o(),t.push([n,K(!1,e)])):t.push([n]);if(!i("punc",","))break;o()}return t
}function _(e){return v("var",M(e))}function D(){return v("const",M())}function P
(){var e=H(!1),t;return i("punc","(")?(o(),t=B(")")):t=[],R(v("new",e,t),!0)}function B
(e,t,n){var r=!0,s=[];while(!i("punc",e)){r?r=!1:h(",");if(t&&i("punc",e))break;
i("punc",",")&&n?s.push(["atom","undefined"]):s.push(K(!1))}return o(),s}function j
(){return v("array",B("]",!t,!0))}function F(){var e=!0,n=[];while(!i("punc","}"
)){e?e=!1:h(",");if(!t&&i("punc","}"))break;var s=r.token.type,u=I();s!="name"||
u!="get"&&u!="set"||!!i("punc",":")?(h(":"),n.push([u,K(!1)])):n.push([q(),C(!1)
,u])}return o(),v("object",n)}function I(){switch(r.token.type){case"num":case"string"
:return prog1(r.token.value,o)}return q()}function q(){switch(r.token.type){case"name"
:case"operator":case"keyword":case"atom":return prog1(r.token.value,o);default:l
()}}function R(e,t){return i("punc",".")?(o(),R(v("dot",e,q()),t)):i("punc","[")?
(o(),R(v("sub",e,prog1(K,curry(h,"]"))),t)):t&&i("punc","(")?(o(),R(v("call",e,B
(")")),!0)):e}function U(e){if(i("operator")&&HOP(UNARY_PREFIX,r.token.value))return z
("unary-prefix",prog1(r.token.value,o),U(e));var t=H(e);while(i("operator")&&HOP
(UNARY_POSTFIX,r.token.value)&&!r.token.nlb)t=z("unary-postfix",r.token.value,t)
,o();return t}function z(e,t,n){return(t=="++"||t=="--")&&!$(n)&&a("Invalid use of "+
t+" operator"),v(e,t,n)}function W(e,t,n){var s=i("operator")?r.token.value:null
;s&&s=="in"&&n&&(s=null);var u=s!=null?PRECEDENCE[s]:null;if(u!=null&&u>t){o();var a=
W(U(!0),u,n);return W(v("binary",s,e,a),t,n)}return e}function X(e){return W(U(!0
),0,e)}function V(e){var t=X(e); ...
```
- example usage
```shell
...
    return;
}
// try to JSON.stringify #inputTextareaEval1
try {
    document.querySelector('#outputPreJsonStringify1').textContent = '';
    document.querySelector('#outputPreJsonStringify1').textContent =
        local.jsonStringifyOrdered(
            JSON.parse(document.querySelector('#inputTextareaEval1').value),
            null,
            4
        );
} catch (ignore) {
}
// jslint #inputTextareaEval1
local.jslint.errorText = '';
...
```

#### <a name="apidoc.element.utility2.uglifyjs.set_logger"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>set_logger (e)](#apidoc.element.utility2.uglifyjs.set_logger)
- description and source-code
```javascript
set_logger = function (e){warn=e}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.slice"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>slice (e, t)](#apidoc.element.utility2.uglifyjs.slice)
- description and source-code
```javascript
function slice(e, t){return Array.prototype.slice
.call(e,t||0)}
```
- example usage
```shell
...
        }).join('')
        : '';
case 'if':
    partial = partial.split('{{#unless ' + key + '}}');
    partial = getValue(key)
        ? partial[0]
        // handle 'unless' case
        : partial.slice(1).join('{{#unless ' + key + '}}');
    // recurse with partial
    return local.templateRender(partial, dict);
case 'unless':
    return getValue(key)
        ? ''
        // recurse with partial
        : local.templateRender(partial, dict);
...
```

#### <a name="apidoc.element.utility2.uglifyjs.split_lines"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>split_lines (e, t)](#apidoc.element.utility2.uglifyjs.split_lines)
- description and source-code
```javascript
function split_lines(e, t){var n=[0];return jsp
.parse(function(){function o(e){return e.pos-i}function u(e){i=e.pos,n.push(i)}function a
(){var e=r.apply(this,arguments);e:{if(s&&s.type=="keyword")break e;if(o(e)>t)switch(
e.type){case"keyword":case"atom":case"name":case"punc":u(e);break e}}return s=e,
e}var r=jsp.tokenizer(e),i=0,s;return a.context=function(){return r.context.apply
(this,arguments)},a}()),n.map(function(t,r){return e.substring(t,n[r+1]||e.length
)}).join("\n")}
```
- example usage
```shell
...
            // comment shebang
            .replace((/^#!/), '//'));
        // get a new AST with mangled names
        ast = local.ast_mangle(ast);
        // get an AST with compression optimizations
        ast = local.ast_squeeze(ast);
        // compressed code here
        return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
    };
}());
switch (local.modeJs) {



/* istanbul ignore next */
...
```

#### <a name="apidoc.element.utility2.uglifyjs.tokenizer"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>tokenizer (e)](#apidoc.element.utility2.uglifyjs.tokenizer)
- description and source-code
```javascript
function tokenizer(e){function n
(){return t.text.charAt(t.pos)}function r(e,n){var r=t.text.charAt(t.pos++);if(e&&!
r)throw EX_EOF;return r=="\n"?(t.newline_before=t.newline_before||!n,++t.line,t.
col=0):++t.col,r}function i(){return!t.peek()}function s(e,n){var r=t.text.indexOf
(e,t.pos);if(n&&r==-1)throw EX_EOF;return r}function o(){t.tokline=t.line,t.tokcol=
t.col,t.tokpos=t.pos}function u(e,n,r){t.regex_allowed=e=="operator"&&!HOP(UNARY_POSTFIX
,n)||e=="keyword"&&HOP(KEYWORDS_BEFORE_EXPRESSION,n)||e=="punc"&&HOP(PUNC_BEFORE_EXPRESSION
,n);var i={type:e,value:n,line:t.tokline,col:t.tokcol,pos:t.tokpos,endpos:t.pos,
nlb:t.newline_before};if(!r){i.comments_before=t.comments_before,t.comments_before=
[];for(var s=0,o=i.comments_before.length;s<o;s++)i.nlb=i.nlb||i.comments_before
[s].nlb}return t.newline_before=!1,i}function a(){while(HOP(WHITESPACE_CHARS,n()
))r()}function f(e){var t="",i=n(),s=0;while(i&&e(i,s++))t+=r(),i=n();return t}function l
(e){js_error(e,t.tokline,t.tokcol,t.tokpos)}function c(e){var t=!1,n=!1,r=!1,i=e=="."
,s=f(function(s,o){return s=="x"||s=="X"?r?!1:r=!0:!!r||s!="E"&&s!="e"?s=="-"?n||
o==0&&!e?!0:!1:s=="+"?n:(n=!1,s=="."?!i&&!r&&!t?i=!0:!1:is_alphanumeric_char(s))
:t?!1:t=n=!0});e&&(s=e+s);var o=parse_js_number(s);if(!isNaN(o))return u("num",o
);l("Invalid syntax: "+s)}function h(e){var t=r(!0,e);switch(t){case"n":return"\n"
;case"r":return"\r";case"t":return"	";case"b":return"\b";case"v":return"";case"f"
:return"\f";case"0":return"\0";case"x":return String.fromCharCode(p(2));case"u":
return String.fromCharCode(p(4));case"\n":return"";default:return t}}function p(
e){var t=0;for(;e>0;--e){var n=parseInt(r(!0),16);isNaN(n)&&l("Invalid hex-character pattern in string"
),t=t<<4|n}return t}function d(){return x("Unterminated string constant",function(
){var e=r(),t="";for(;;){var n=r(!0);if(n=="\\"){var i=0,s=null;n=f(function(e){
if(e>="0"&&e<="7"){if(!s)return s=e,++i;if(s<="3"&&i<=2)return++i;if(s>="4"&&i<=1
)return++i}return!1}),i>0?n=String.fromCharCode(parseInt(n,8)):n=h(!0)}else{if(n==
e)break;if(n=="\n")throw EX_EOF}t+=n}return u("string",t)})}function v(){r();var e=
s("\n"),n;return e==-1?(n=t.text.substr(t.pos),t.pos=t.text.length):(n=t.text.substring
(t.pos,e),t.pos=e),u("comment1",n,!0)}function m(){return r(),x("Unterminated multiline comment"
,function(){var e=s("*/",!0),n=t.text.substring(t.pos,e);return t.pos=e+2,t.line+=
n.split("\n").length-1,t.newline_before=t.newline_before||n.indexOf("\n")>=0,/^@cc_on/i
.test(n)&&(warn("WARNING: at line "+t.line),warn('*** Found "conditional comment": '+
n),warn("*** UglifyJS DISCARDS ALL COMMENTS.  This means your code might no longer work properly in Internet Explorer."
)),u("comment2",n,!0)})}function g(){var e=!1,t="",i,s=!1,o;while((i=n())!=null)
if(!e)if(i=="\\")s=e=!0,r();else{if(!is_identifier_char(i))break;t+=r()}else i!="u"&&
l("Expecting UnicodeEscapeSequence -- uXXXX"),i=h(),is_identifier_char(i)||l("Unicode char: "+
i.charCodeAt(0)+" is not valid in identifier"),t+=i,e=!1;return HOP(KEYWORDS,t)&&
s&&(o=t.charCodeAt(0).toString(16).toUpperCase(),t="\\u"+"0000".substr(o.length)+
o+t.slice(1)),t}function y(e){return x("Unterminated regular expression",function(
){var t=!1,n,i=!1;while(n=r(!0))if(t)e+="\\"+n,t=!1;else if(n=="[")i=!0,e+=n;else if(
n=="]"&&i)i=!1,e+=n;else{if(n=="/"&&!i)break;n=="\\"?t=!0:e+=n}var s=g();return u
("regexp",[e,s])})}function b(e){function t(e){if(!n())return e;var i=e+n();return HOP
(OPERATORS,i)?(r(),t(i)):e}return u("operator",t(e||r()))}function w(){r();var e=
t.regex_allowed;switch(n()){case"/":return t.comments_before.push(v()),t.regex_allowed=
e,T();case"*":return t.comments_before.push(m()),t.regex_allowed=e,T()}return t.
regex_allowed?y(""):b("/")}function E(){return r(),is_digit(n())?c("."):u("punc"
,".")}function S(){var e=g();return HOP(KEYWORDS,e)?HOP(OPERATORS,e)?u("operator"
,e):HOP(KEYWORDS_ATOM,e)?u("atom",e):u("keyword",e):u("name",e)}function x(e,t){
try{return t()}catch(n){if(n!==EX_EOF)throw n;l(e)}}function T(e){if(e!=null)return y
(e);a(),o();var t=n();if(!t)return u("eof");if(is_d ...
```
- example usage
```shell
...
replace(/;*\s*$/,";"):";"},seq:function(){return p(MAP(slice(arguments),b))},label
:function(e,t){return h([u(e),":",b(t)])},"with":function(e,t){return h(["with","("+
b(e)+")",b(t)])},atom:function(e){return u(e)},directive:function(e){return make_string
(e)+";"}},function(){return b(e)})}function split_lines(e,t){var n=[0];return jsp
.parse(function(){function o(e){return e.pos-i}function u(e){i=e.pos,n.push(i)}function a
(){var e=r.apply(this,arguments);e:{if(s&&s.type=="keyword")break e;if(o(e)>t)switch(
e.type){case"keyword":case"atom":case"name":case"punc":u(e);break e}}return s=e,
e}var r=jsp.tokenizer(e),i=0,s;return a.context=function(){return r.context.apply
(this,arguments)},a}()),n.map(function(t,r){return e.substring(t,n[r+1]||e.length
)}).join("\n")}function repeat_string(e,t){if(t<=0)return"";if(t==1)return e;var n=
repeat_string(e,t>>1);return n+=n,t&1&&(n+=e),n}function defaults(e,t){var n={};
e===!0&&(e={});for(var r in t)HOP(t,r)&&(n[r]=e&&HOP(e,r)?e[r]:t[r]);return n}function is_identifier
(e){return/^[a-z_$][a-z0-9_$]*$/i.test(e)&&e!="this"&&!HOP(jsp.KEYWORDS_ATOM,e)&&!
HOP(jsp.RESERVED_WORDS,e)&&!HOP(jsp.KEYWORDS,e)}function HOP(e,t){return Object.
prototype.hasOwnProperty.call(e,t)}var jsp=require("./parse-js"),curry=jsp.curry
...
```

#### <a name="apidoc.element.utility2.uglifyjs.uglify"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>uglify (code, file)](#apidoc.element.utility2.uglifyjs.uglify)
- description and source-code
```javascript
uglify = function (code, file) {
<span class="apidocCodeCommentSpan">/*
 * this function will uglify the js-code
 */
</span>    var ast;
    // uglify css
    if ((file || '').slice(-4) === '.css') {
        return code
            // remove comment /**/
            .replace((/\/\*[\S\s]*?\*\//g), '')
            // remove comment //
            .replace((/\/\/.*/g), '')
            // remove whitespace
            .replace((/\t/g), ' ')
            .replace((/ {2,}/g), ' ')
            .replace((/ *?([\n,:;{}]) */g), '$1')
            .replace((/\n\n+/g), '\n')
            .trim();
    }
    // parse code and get the initial AST
    ast = local.parse(code
        .trim()
        // comment shebang
        .replace((/^#!/), '//'));
    // get a new AST with mangled names
    ast = local.ast_mangle(ast);
    // get an AST with compression optimizations
    ast = local.ast_squeeze(ast);
    // compressed code here
    return local.split_lines(local.gen_code(ast, { ascii_only: true }), 79);
}
```
- example usage
```shell
...
), function (response) {
    local.chunkList = [];
    response
        .on('data', function (chunk) {
            local.chunkList.push(chunk);
        })
        .on('end', function () {
            console.log(local.uglify(
                Buffer.concat(local.chunkList).toString(),
                local.url.parse(process.argv[2]).pathname
            ));
        });
})
    .end();
break;
...
```



# <a name="apidoc.module.utility2.uglifyjs.MAP"></a>[module utility2.uglifyjs.MAP](#apidoc.module.utility2.uglifyjs.MAP)

#### <a name="apidoc.element.utility2.uglifyjs.MAP.MAP"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.</span>MAP (r, i, s)](#apidoc.element.utility2.uglifyjs.MAP.MAP)
- description and source-code
```javascript
MAP = function (r, i, s){function f(){var f=i.call(s,r[a],a);f instanceof t?(f=f.v,f instanceof n?u.
push.apply(u,f.v):u.push(f)):f!=e&&(f instanceof n?o.push.apply(o,f.v):o.push(f)
)}var o=[],u=[],a;if(r instanceof Array)for(a=0;a<r.length;++a)f();else for(a in
r)HOP(r,a)&&f();return u.concat(o)}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.utility2.uglifyjs.MAP.at_top"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.MAP.</span>at_top (e)](#apidoc.element.utility2.uglifyjs.MAP.at_top)
- description and source-code
```javascript
at_top = function (e){return new t(e)}
```
- example usage
```shell
...
){return n=MAP(n,function(e){return s(e)}),MAP(o,r)},f),[this[0],e,n,o]}function a
(e,t,n){var r=i;i=e;if(n)for(var o in n)HOP(n,o)&&e.set_mangle(o,n[o]);for(var o in
e.names)HOP(e.names,o)&&s(o,!0);var u=t();return u.scope=e,i=r,u}function f(e){return[
this[0],MAP(e,function(e){return[s(e[0]),r(e[1])]})]}function l(e){if(e)return[this
[0],i.labels.get_mangled(e)]}var n=ast_walker(),r=n.walk,i;return t=defaults(t,{
mangle:!0,toplevel:!1,defines:null,except:null,no_functions:!1}),n.with_walkers(
{"function":u,defun:function(){var e=u.apply(this,arguments);switch(n.parent()[0
]){case"toplevel":case"function":case"defun":return MAP.at_top(e)}return e},label
:function(e,t){return i.labels.refs[e]?[this[0],i.labels.get_mangled(e,!0),r(t)]
:r(t)},"break":l,"continue":l,"var":f,"const":f,name:function(e){return o(e)||[this
[0],s(e)]},"try":function(e,t,n){return[this[0],MAP(e,r),t!=null?[s(t[0]),MAP(t[1
],r)]:null,n!=null?MAP(n,r):null]},toplevel:function(e){var t=this;return a(t.scope
,function(){return[t[0],MAP(e,r)]})},directive:function(){return MAP.at_top(this
)}},function(){return r(ast_add_scope(e))})}function best_of(e,t){return gen_code
(e).length>gen_code(t[0]=="stat"?t[1]:t).length?t:e}function last_stat(e){return e
...
```

#### <a name="apidoc.element.utility2.uglifyjs.MAP.splice"></a>[function <span class="apidocSignatureSpan">utility2.uglifyjs.MAP.</span>splice (e)](#apidoc.element.utility2.uglifyjs.MAP.splice)
- description and source-code
```javascript
splice = function (e){return new n(e)}
```
- example usage
```shell
...
,InvalidModuleSpecifier:"Unexpected token",IllegalImportDeclaration:"Unexpected token"
,IllegalExportDeclaration:"Unexpected token",DuplicateBinding:"Duplicate binding %0"
},u={NonAsciiIdentifierStart:/[\xAA\xB5\xBA\xC0-\xD6\xD8-\xF6\xF8-\u02C1\u02C6-\u02D1\u02E0-\u02E4\u02EC\u02EE\u0370-\u0374\u0376\u0377\u037A-\u037D\u037F\u0386\u0388-\u038A\u038C\u038E-\u03A1\u03A3-\u03F5\u03F7-\u0481\u048A-\u052F\u0531-\u0556\u0559\u0561-\u0587\u05D0-\u05EA\u05F0-\u05F2\u0620-\u064A\u066E\u066F\u0671-\u06D3\u06D5\u06E5\u06E6\u06EE\u06EF\u06FA-\u06FC\u06FF\u0710\u0712-\u072F\u074D-\u07A5\u07B1\u07CA-\u07EA\u07F4\u07F5\u07FA\u0800-\u0815\u081A\u0824\u0828\u0840-\u0858\u08A0-\u08B2\u0904-\u0939\u093D\u0950\u0958-\u0961\u0971-\u0980\u0985-\u098C\u098F\u0990\u0993-\u09A8\u09AA-\u09B0\u09B2\u09B6-\u09B9\u09BD\u09CE\u09DC\u09DD\u09DF-\u09E1\u09F0\u09F1\u0A05-\u0A0A\u0A0F\u0A10\u0A13-\u0A28\u0A2A-\u0A30\u0A32\u0A33\u0A35\u0A36\u0A38\u0A39\u0A59-\u0A5C\u0A5E\u0A72-\u0A74\u0A85-\u0A8D\u0A8F-\u0A91\u0A93-\u0AA8\u0AAA-\u0AB0\u0AB2\u0AB3\u0AB5-\u0AB9\u0ABD\u0AD0\u0AE0\u0AE1\u0B05-\u0B0C\u0B0F\u0B10\u0B13-\u0B28\u0B2A-\u0B30\u0B32\u0B33\u0B35-\u0B39\u0B3D\u0B5C\u0B5D\u0B5F-\u0B61\u0B71\u0B83\u0B85-\u0B8A\u0B8E-\u0B90\u0B92-\u0B95\u0B99\u0B9A\u0B9C\u0B9E\u0B9F\u0BA3\u0BA4\u0BA8-\u0BAA\u0BAE-\u0BB9\u0BD0\u0C05-\u0C0C\u0C0E-\u0C10\u0C12-\u0C28\u0C2A-\u0C39\u0C3D\u0C58\u0C59\u0C60\u0C61\u0C85-\u0C8C\u0C8E-\u0C90\u0C92-\u0CA8\u0CAA-\u0CB3\u0CB5-\u0CB9\u0CBD\u0CDE\u0CE0\u0CE1\u0CF1\u0CF2\u0D05-\u0D0C\u0D0E-\u0D10\u0D12-\u0D3A\u0D3D\u0D4E\u0D60\u0D61\u0D7A-\u0D7F\u0D85-\u0D96\u0D9A-\u0DB1\u0DB3-\u0DBB\u0DBD\u0DC0-\u0DC6\u0E01-\u0E30\u0E32\u0E33\u0E40-\u0E46\u0E81\u0E82\u0E84\u0E87\u0E88\u0E8A\u0E8D\u0E94-\u0E97\u0E99-\u0E9F\u0EA1-\u0EA3\u0EA5\u0EA7\u0EAA\u0EAB\u0EAD-\u0EB0\u0EB2\u0EB3\u0EBD\u0EC0-\u0EC4\u0EC6\u0EDC-\u0EDF\u0F00\u0F40-\u0F47\u0F49-\u0F6C\u0F88-\u0F8C\u1000-\u102A\u103F\u1050-\u1055\u105A-\u105D\u1061\u1065\u1066\u106E-\u1070\u1075-\u1081\u108E\u10A0-\u10C5\u10C7\u10CD\u10D0-\u10FA\u10FC-\u1248\u124A-\u124D\u1250-\u1256\u1258\u125A-\u125D\u1260-\u1288\u128A-\u128D\u1290-\u12B0\u12B2-\u12B5\u12B8-\u12BE\u12C0\u12C2-\u12C5\u12C8-\u12D6\u12D8-\u1310\u1312-\u1315\u1318-\u135A\u1380-\u138F\u13A0-\u13F4\u1401-\u166C\u166F-\u167F\u1681-\u169A\u16A0-\u16EA\u16EE-\u16F8\u1700-\u170C\u170E-\u1711\u1720-\u1731\u1740-\u1751\u1760-\u176C\u176E-\u1770\u1780-\u17B3\u17D7\u17DC\u1820-\u1877\u1880-\u18A8\u18AA\u18B0-\u18F5\u1900-\u191E\u1950-\u196D\u1970-\u1974\u1980-\u19AB\u19C1-\u19C7\u1A00-\u1A16\u1A20-\u1A54\u1AA7\u1B05-\u1B33\u1B45-\u1B4B\u1B83-\u1BA0\u1BAE\u1BAF\u1BBA-\u1BE5\u1C00-\u1C23\u1C4D-\u1C4F\u1C5A-\u1C7D\u1CE9-\u1CEC\u1CEE-\u1CF1\u1CF5\u1CF6\u1D00-\u1DBF\u1E00-\u1F15\u1F18-\u1F1D\u1F20-\u1F45\u1F48-\u1F4D\u1F50-\u1F57\u1F59\u1F5B\u1F5D\u1F5F-\u1F7D\u1F80-\u1FB4\u1FB6-\u1FBC\u1FBE\u1FC2-\u1FC4\u1FC6-\u1FCC\u1FD0-\u1FD3\u1FD6-\u1FDB\u1FE0-\u1FEC\u1FF2-\u1FF4\u1FF6-\u1FFC\u2071\u207F\u2090-\u209C\u2102\u2107\u210A-\u2113\u2115\u2118-\u211D\u2124\u2126\u2128\u212A-\u2139\u213C-\u213F\u2145-\u2149\u214E\u2160-\u2188\u2C00-\u2C2E\u2C30-\u2C5E\u2C60-\u2CE4\u2CEB-\u2CEE\u2CF2\u2CF3\u2D00-\u2D25\u2D27\u2D2D\u2D30-\u2D67\u2D6F\u2D80-\u2D96\u2DA0-\u2DA6\u2DA8-\u2DAE\u2DB0-\u2DB6\u2DB8-\u2DBE\u2DC0-\u2DC6\u2DC8-\u2DCE\u2DD0-\u2DD6\u2DD8-\u2DDE\u3005-\u3007\u3021-\u3029\u3031-\u3035\u3038-\u303C\u3041-\u3096\u309B-\u309F\u30A1-\u30FA\u30FC-\u30FF\u3105-\u312D\u3131-\u318E\u31A0-\u31BA\u31F0-\u31FF\u3400-\u4DB5\u4E00-\u9FCC\uA000-\uA48C\uA4D0-\uA4FD\uA500-\uA60C\uA610-\uA61F\uA62A\uA62B\uA640-\uA66E\uA67F-\uA69D\uA6A0-\uA6EF\uA717-\uA71F\uA722-\uA788\uA78B-\uA78E\uA790-\uA7AD\uA7B0\uA7B1\uA7F7-\uA801\uA803-\uA805\uA807-\uA80A\uA80C-\uA822\uA840-\uA873\uA882-\uA8B3\uA8F2-\uA8F7\uA8FB\uA90A-\uA925\uA930-\uA946\uA960-\uA97C\uA984-\uA9B2\uA9CF\uA9E0-\uA9E4\uA9E6-\uA9EF\uA9FA-\uA9FE\uAA00-\uAA28\uAA40-\uAA42\uAA44-\uAA4B\uAA60-\uAA76\uAA7A\uAA7E-\uAAAF\uAAB1\uAAB5\uAAB6\uAAB9-\uAABD\uAAC0\uAAC2\uAADB-\uAADD\uAAE0-\uAAEA\uAAF2-\uAAF4\uAB01-\uAB06\uAB09-\uAB0E\uAB11-\uAB16\uAB20-\uAB26\uAB28-\uAB2E\uAB30-\uAB5A\uAB5C-\uAB5F\uAB64\uAB65\uABC0-\uABE2\uAC00-\uD7A3\uD7B0-\uD7C6\uD7CB-\uD7FB\uF900-\uFA6D\uFA70-\uFAD9\uFB00-\uFB06\uFB13-\uFB17\uFB1D\uFB1F-\uFB28\uFB2A-\uFB36\uFB38-\uFB3C\uFB3E\uFB40\uFB41\uFB43\uFB44\uFB46-\uFBB1\uFBD3-\uFD3D\uFD50-\uFD8F\uFD92-\uFDC7\uFDF0-\uFDFB\uFE70-\uFE74\uFE76-\uFEFC\uFF21-\uFF3A\uFF41-\uFF5A\uFF66-\uFFBE\uFFC2-\uFFC7\uFFCA-\uFFCF\uFFD2-\uFFD7\uFFDA-\uFFDC]|\uD800[\uDC00-\uDC0B\uDC0D-\uDC26\uDC28-\uDC3A\uDC3C\uDC3D\uDC3F-\uDC4D\uDC50-\uDC5D\uDC80-\uDCFA\uDD40-\uDD74\uDE80-\uDE9C\uDEA0-\uDED0\uDF00-\uDF1F\uDF30-\uDF4A\uDF50-\uDF75\uDF80-\uDF9D\uDFA0-\uDFC3\uDFC8-\uDFCF\uDFD1-\uDFD5]|\uD801[\uDC00-\uDC9D\uDD00-\uDD27\uDD30-\uDD63\uDE00-\uDF36\uDF40-\uDF55\uDF60-\uDF67]|\uD802[\uDC00-\uDC05\uDC08\uDC0A-\uDC35\uDC37\uDC38\uDC3C\uDC3F-\uDC55\uDC60-\uDC76\uDC80-\uDC9E\uDD00-\uDD15\uDD20-\uDD39\uDD80-\uDDB7\uDDBE\uDDBF\uDE00\uDE10-\uDE13\uDE15-\uDE17\uDE19-\uDE33\uDE60-\uDE7C\uDE80-\uDE9C\uDEC0-\uDEC7\uDEC9-\uDEE4\uDF00-\uDF35\uDF40-\uDF55\uDF60-\uDF72\uDF80-\uDF91]|\uD803[\uDC00-\uDC48]|\uD804[\uDC03-\uDC37\uDC83-\uDCAF\uDCD0-\uDCE8\uDD03-\uDD26\uDD50-\uDD72\uDD76\uDD83-\uDDB2\uDDC1-\uDDC4\uDDDA\uDE00-\uDE11\uDE13-\uDE2B\uDEB0-\uDEDE\uDF05-\uDF0C\uDF0F\uDF10\uDF13-\uDF28\uDF2A-\uDF30\uDF32\uDF33\uDF35-\uDF39\uDF3D\uDF5D-\uDF61]|\uD805[\uDC80-\uDCAF\uDCC4\uDCC5\uDCC7\uDD80-\uDDAE\uDE00-\uDE2F\uDE44\uDE80-\uDEAA]|\uD806[\uDCA0-\uDCDF\uDCFF\uDEC0-\uDEF8]|\uD808[\uDC00-\uDF98]|\uD809[\uDC00-\uDC6E]|[\uD80C\uD840-\uD868\uD86A-\uD86C][\uDC00-\uDFFF]|\uD80D[\uDC00-\uDC2E]|\uD81A[\uDC00-\uDE38\uDE40-\uDE5E\uDED0-\uDEED\uDF00-\uDF2F\uDF40-\uDF43\uDF63-\uDF77\uDF7D-\uDF8F]|\uD81B[\uDF00-\uDF44\uDF50\uDF93-\uDF9F]|\uD82C[\uDC00\uDC01]|\uD82F[\uDC00-\uDC6A\uDC70-\uDC7C\uDC80-\uDC88\uDC90-\uDC99]|\uD835[\uDC00-\uDC54\uDC56-\uDC9C\uDC9E\uDC9F\uDCA2\uDCA5\uDCA6\uDCA9-\uDCAC\uDCAE-\uDCB9\uDCBB\uDCBD-\uDCC3\uDCC5-\uDD05\uDD07-\uDD0A\uDD0D-\uDD14\uDD16-\uDD1C\uDD1E-\uDD39\uDD3B-\uDD3E\uDD40-\uDD44\uDD46\uDD4A-\uDD50\uDD52-\uDEA5\uDEA8-\uDEC0\uDEC2-\uDEDA\uDEDC-\uDEFA\uDEFC-\uDF14\uDF16-\uDF34\uDF36-\uDF4E\uDF50-\uDF6E\uDF70-\uDF88\uDF8A-\uDFA8\uDFAA-\uDFC2\uDFC4-\uDFCB]|\uD83A[\uDC00-\uDCC4]|\uD83B[\uDE00-\uDE03\uDE05-\uDE1F\uDE21\uDE22\uDE24\uDE27\uDE29-\uDE32\uDE34-\uDE37\uDE39\uDE3B\uDE42\uDE47\uDE49\uDE4B\uDE4D-\uDE4F\uDE51\uDE52\uDE54\uDE57\uDE59\uDE5B\uDE5D\uDE5F\uDE61\uDE62\uDE64\uDE67-\uDE6A\uDE6C-\uDE72\uDE74-\uDE77\uDE79-\uDE7C\uDE7E\uDE80-\uDE89\uDE8B-\uDE9B\uDEA1-\uDEA3\uDEA5-\uDEA9\uDEAB-\uDEBB]|\uD869[\uDC00-\uDED6\uDF00-\uDFFF]|\uD86D[\uDC00-\uDF34\uDF40-\uDFFF]|\uD86E[\uDC00-\uDC1D]|\uD87E[\uDC00-\uDE1D]/
,NonAsciiIdentifierPart:/[\xAA\xB5\xB7\xBA\xC0-\xD6\xD8-\xF6\xF8-\u02C1\u02C6-\u02D1\u02E0-\u02E4\u02EC\u02EE\u0300-\u0374\u0376\u0377\u037A-\u037D\u037F\u0386-\u038A\u038C\u038E-\u03A1\u03A3-\u03F5\u03F7-\u0481\u0483-\u0487\u048A-\u052F\u0531-\u0556\u0559\u0561-\u0587\u0591-\u05BD\u05BF\u05C1\u05C2\u05C4\u05C5\u05C7\u05D0-\u05EA\u05F0-\u05F2\u0610-\u061A\u0620-\u0669\u066E-\u06D3\u06D5-\u06DC\u06DF-\u06E8\u06EA-\u06FC\u06FF\u0710-\u074A\u074D-\u07B1\u07C0-\u07F5\u07FA\u0800-\u082D\u0840-\u085B\u08A0-\u08B2\u08E4-\u0963\u0966-\u096F\u0971-\u0983\u0985-\u098C\u098F\u0990\u0993-\u09A8\u09AA-\u09B0\u09B2\u09B6-\u09B9\u09BC-\u09C4\u09C7\u09C8\u09CB-\u09CE\u09D7\u09DC\u09DD\u09DF-\u09E3\u09E6-\u09F1\u0A01-\u0A03\u0A05-\u0A0A\u0A0F\u0A10\u0A13-\u0A28\u0A2A-\u0A30\u0A32\u0A33\u0A35\u0A36\u0A38\u0A39\u0A3C\u0A3E-\u0A42\u0A47\u0A48\u0A4B-\u0A4D\u0A51\u0A59-\u0A5C\u0A5E\u0A66-\u0A75\u0A81-\u0A83\u0A85-\u0A8D\u0A8F-\u0A91\u0A93-\u0AA8\u0AAA-\u0AB0\u0AB2\u0AB3\u0AB5-\u0AB9\u0ABC-\u0AC5\u0AC7-\u0AC9\u0ACB-\u0ACD\u0AD0\u0AE0-\u0AE3\u0AE6-\u0AEF\u0B01-\u0B03\u0B05-\u0B0C\u0B0F\u0B10\u0B13-\u0B28\u0B2A-\u0B30\u0B32\u0B33\u0B35-\u0B39\u0B3C-\u0B44\u0B47\u0B48\u0B4B-\u0B4D\u0B56\u0B57\u0B5C\u0B5D\u0B5F-\u0B63\u0B66-\u0B6F\u0B71\u0B82\u0B83\u0B85-\u0B8A\u0B8E-\u0B90\u0B92-\u0B95\u0B99\u0B9A\u0B9C\u0B9E\u0B9F\u0BA3\u0BA4\u0BA8-\u0BAA\u0BAE-\u0BB9\u0BBE-\u0BC2\u0BC6-\u0BC8\u0BCA-\u0BCD\u0BD0\u0BD7\u0BE6-\u0BEF\u0C00-\u0C03\u0C05-\u0C0C\u0C0E-\u0C10\u0C12-\u0C28\u0C2A-\u0C39\u0C3D-\u0C44\u0C46-\u0C48\u0C4A-\u0C4D\u0C55\u0C56\u0C58\u0C59\u0C60-\u0C63\u0C66-\u0C6F\u0C81-\u0C83\u0C85-\u0C8C\u0C8E-\u0C90\u0C92-\u0CA8\u0CAA-\u0CB3\u0CB5-\u0CB9\u0CBC-\u0CC4\u0CC6-\u0CC8\u0CCA-\u0CCD\u0CD5\u0CD6\u0CDE\u0CE0-\u0CE3\u0CE6-\u0CEF\u0CF1\u0CF2\u0D01-\u0D03\u0D05-\u0D0C\u0D0E-\u0D10\u0D12-\u0D3A\u0D3D-\u0D44\u0D46-\u0D48\u0D4A-\u0D4E\u0D57\u0D60-\u0D63\u0D66-\u0D6F\u0D7A-\u0D7F\u0D82\u0D83\u0D85-\u0D96\u0D9A-\u0DB1\u0DB3-\u0DBB\u0DBD\u0DC0-\u0DC6\u0DCA\u0DCF-\u0DD4\u0DD6\u0DD8-\u0DDF\u0DE6-\u0DEF\u0DF2\u0DF3\u0E01-\u0E3A\u0E40-\u0E4E\u0E50-\u0E59\u0E81\u0E82\u0E84\u0E87\u0E88\u0E8A\u0E8D\u0E94-\u0E97\u0E99-\u0E9F\u0EA1-\u0EA3\u0EA5\u0EA7\u0EAA\u0EAB\u0EAD-\u0EB9\u0EBB-\u0EBD\u0EC0-\u0EC4\u0EC6\u0EC8-\u0ECD\u0ED0-\u0ED9\u0EDC-\u0EDF\u0F00\u0F18\u0F19\u0F20-\u0F29\u0F35\u0F37\u0F39\u0F3E-\u0F47\u0F49-\u0F6C\u0F71-\u0F84\u0F86-\u0F97\u0F99-\u0FBC\u0FC6\u1000-\u1049\u1050-\u109D\u10A0-\u10C5\u10C7\u10CD\u10D0-\u10FA\u10FC-\u1248\u124A-\u124D\u1250-\u1256\u1258\u125A-\u125D\u1260-\u1288\u128A-\u128D\u1290-\u12B0\u12B2-\u12B5\u12B8-\u12BE\u12C0\u12C2-\u12C5\u12C8-\u12D6\u12D8-\u1310\u1312-\u1315\u1318-\u135A\u135D-\u135F\u1369-\u1371\u1380-\u138F\u13A0-\u13F4\u1401-\u166C\u166F-\u167F\u1681-\u169A\u16A0-\u16EA\u16EE-\u16F8\u1700-\u170C\u170E-\u1714\u1720-\u1734\u1740-\u1753\u1760-\u176C\u176E-\u1770\u1772\u1773\u1780-\u17D3\u17D7\u17DC\u17DD\u17E0-\u17E9\u180B-\u180D\u1810-\u1819\u1820-\u1877\u1880-\u18AA\u18B0-\u18F5\u1900-\u191E\u1920-\u192B\u1930-\u193B\u1946-\u196D\u1970-\u1974\u1980-\u19AB\u19B0-\u19C9\u19D0-\u19DA\u1A00-\u1A1B\u1A20-\u1A5E\u1A60-\u1A7C\u1A7F-\u1A89\u1A90-\u1A99\u1AA7\u1AB0-\u1ABD\u1B00-\u1B4B\u1B50-\u1B59\u1B6B-\u1B73\u1B80-\u1BF3\u1C00-\u1C37\u1C40-\u1C49\u1C4D-\u1C7D\u1CD0-\u1CD2\u1CD4-\u1CF6\u1CF8\u1CF9\u1D00-\u1DF5\u1DFC-\u1F15\u1F18-\u1F1D\u1F20-\u1F45\u1F48-\u1F4D\u1F50-\u1F57\u1F59\u1F5B\u1F5D\u1F5F-\u1F7D\u1F80-\u1FB4\u1FB6-\u1FBC\u1FBE\u1FC2-\u1FC4\u1FC6-\u1FCC\u1FD0-\u1FD3\u1FD6-\u1FDB\u1FE0-\u1FEC\u1FF2-\u1FF4\u1FF6-\u1FFC\u200C\u200D\u203F\u2040\u2054\u2071\u207F\u2090-\u209C\u20D0-\u20DC\u20E1\u20E5-\u20F0\u2102\u2107\u210A-\u2113\u2115\u2118-\u211D\u2124\u2126\u2128\u212A-\u2139\u213C-\u213F\u2145-\u2149\u214E\u2160-\u2188\u2C00-\u2C2E\u2C30-\u2C5E\u2C60-\u2CE4\u2CEB-\u2CF3\u2D00-\u2D25\u2D27\u2D2D\u2D30-\u2D67\u2D6F\u2D7F-\u2D96\u2DA0-\u2DA6\u2DA8-\u2DAE\u2DB0-\u2DB6\u2DB8-\u2DBE\u2DC0-\u2DC6\u2DC8-\u2DCE\u2DD0-\u2DD6\u2DD8-\u2DDE\u2DE0-\u2DFF\u3005-\u3007\u3021-\u302F\u3031-\u3035\u3038-\u303C\u3041-\u3096\u3099-\u309F\u30A1-\u30FA\u30FC-\u30FF\u3105-\u312D\u3131-\u318E\u31A0-\u31BA\u31F0-\u31FF\u3400-\u4DB5\u4E00-\u9FCC\uA000-\uA48C\uA4D0-\uA4FD\uA500-\uA60C\uA610-\uA62B\uA640-\uA66F\uA674-\uA67D\uA67F-\uA69D\uA69F-\uA6F1\uA717-\uA71F\uA722-\uA788\uA78B-\uA78E\uA790-\uA7AD\uA7B0\uA7B1\uA7F7-\uA827\uA840-\uA873\uA880-\uA8C4\uA8D0-\uA8D9\uA8E0-\uA8F7\uA8FB\uA900-\uA92D\uA930-\uA953\uA960-\uA97C\uA980-\uA9C0\uA9CF-\uA9D9\uA9E0-\uA9FE\uAA00-\uAA36\uAA40-\uAA4D\uAA50-\uAA59\uAA60-\uAA76\uAA7A-\uAAC2\uAADB-\uAADD\uAAE0-\uAAEF\uAAF2-\uAAF6\uAB01-\uAB06\uAB09-\uAB0E\uAB11-\uAB16\uAB20-\uAB26\uAB28-\uAB2E\uAB30-\uAB5A\uAB5C-\uAB5F\uAB64\uAB65\uABC0-\uABEA\uABEC\uABED\uABF0-\uABF9\uAC00-\uD7A3\uD7B0-\uD7C6\uD7CB-\uD7FB\uF900-\uFA6D\uFA70-\uFAD9\uFB00-\uFB06\uFB13-\uFB17\uFB1D-\uFB28\uFB2A-\uFB36\uFB38-\uFB3C\uFB3E\uFB40\uFB41\uFB43\uFB44\uFB46-\uFBB1\uFBD3-\uFD3D\uFD50-\uFD8F\uFD92-\uFDC7\uFDF0-\uFDFB\uFE00-\uFE0F\uFE20-\uFE2D\uFE33\uFE34\uFE4D-\uFE4F\uFE70-\uFE74\uFE76-\uFEFC\uFF10-\uFF19\uFF21-\uFF3A\uFF3F\uFF41-\uFF5A\uFF66-\uFFBE\uFFC2-\uFFC7\uFFCA-\uFFCF\uFFD2-\uFFD7\uFFDA-\uFFDC]|\uD800[\uDC00-\uDC0B\uDC0D-\uDC26\uDC28-\uDC3A\uDC3C\uDC3D\uDC3F-\uDC4D\uDC50-\uDC5D\uDC80-\uDCFA\uDD40-\uDD74\uDDFD\uDE80-\uDE9C\uDEA0-\uDED0\uDEE0\uDF00-\uDF1F\uDF30-\uDF4A\uDF50-\uDF7A\uDF80-\uDF9D\uDFA0-\uDFC3\uDFC8-\uDFCF\uDFD1-\uDFD5]|\uD801[\uDC00-\uDC9D\uDCA0-\uDCA9\uDD00-\uDD27\uDD30-\uDD63\uDE00-\uDF36\uDF40-\uDF55\uDF60-\uDF67]|\uD802[\uDC00-\uDC05\uDC08\uDC0A-\uDC35\uDC37\uDC38\uDC3C\uDC3F-\uDC55\uDC60-\uDC76\uDC80-\uDC9E\uDD00-\uDD15\uDD20-\uDD39\uDD80-\uDDB7\uDDBE\uDDBF\uDE00-\uDE03\uDE05\uDE06\uDE0C-\uDE13\uDE15-\uDE17\uDE19-\uDE33\uDE38-\uDE3A\uDE3F\uDE60-\uDE7C\uDE80-\uDE9C\uDEC0-\uDEC7\uDEC9-\uDEE6\uDF00-\uDF35\uDF40-\uDF55\uDF60-\uDF72\uDF80-\uDF91]|\uD803[\uDC00-\uDC48]|\uD804[\uDC00-\uDC46\uDC66-\uDC6F\uDC7F-\uDCBA\uDCD0-\uDCE8\uDCF0-\uDCF9\uDD00-\uDD34\uDD36-\uDD3F\uDD50-\uDD73\uDD76\uDD80-\uDDC4\uDDD0-\uDDDA\uDE00-\uDE11\uDE13-\uDE37\uDEB0-\uDEEA\uDEF0-\uDEF9\uDF01-\uDF03\uDF05-\uDF0C\uDF0F\uDF10\uDF13-\uDF28\uDF2A-\uDF30\uDF32\uDF33\uDF35-\uDF39\uDF3C-\uDF44\uDF47\uDF48\uDF4B-\uDF4D\uDF57\uDF5D-\uDF63\uDF66-\uDF6C\uDF70-\uDF74]|\uD805[\uDC80-\uDCC5\uDCC7\uDCD0-\uDCD9\uDD80-\uDDB5\uDDB8-\uDDC0\uDE00-\uDE40\uDE44\uDE50-\uDE59\uDE80-\uDEB7\uDEC0-\uDEC9]|\uD806[\uDCA0-\uDCE9\uDCFF\uDEC0-\uDEF8]|\uD808[\uDC00-\uDF98]|\uD809[\uDC00-\uDC6E]|[\uD80C\uD840-\uD868\uD86A-\uD86C][\uDC00-\uDFFF]|\uD80D[\uDC00-\uDC2E]|\uD81A[\uDC00-\uDE38\uDE40-\uDE5E\uDE60-\uDE69\uDED0-\uDEED\uDEF0-\uDEF4\uDF00-\uDF36\uDF40-\uDF43\uDF50-\uDF59\uDF63-\uDF77\uDF7D-\uDF8F]|\uD81B[\uDF00-\uDF44\uDF50-\uDF7E\uDF8F-\uDF9F]|\uD82C[\uDC00\uDC01]|\uD82F[\uDC00-\uDC6A\uDC70-\uDC7C\uDC80-\uDC88\uDC90-\uDC99\uDC9D\uDC9E]|\uD834[\uDD65-\uDD69\uDD6D-\uDD72\uDD7B-\uDD82\uDD85-\uDD8B\uDDAA-\uDDAD\uDE42-\uDE44]|\uD835[\uDC00-\uDC54\uDC56-\uDC9C\uDC9E\uDC9F\uDCA2\uDCA5\uDCA6\uDCA9-\uDCAC\uDCAE-\uDCB9\uDCBB\uDCBD-\uDCC3\uDCC5-\uDD05\uDD07-\uDD0A\uDD0D-\uDD14\uDD16-\uDD1C\uDD1E-\uDD39\uDD3B-\uDD3E\uDD40-\uDD44\uDD46\uDD4A-\uDD50\uDD52-\uDEA5\uDEA8-\uDEC0\uDEC2-\uDEDA\uDEDC-\uDEFA\uDEFC-\uDF14\uDF16-\uDF34\uDF36-\uDF4E\uDF50-\uDF6E\uDF70-\uDF88\uDF8A-\uDFA8\uDFAA-\uDFC2\uDFC4-\uDFCB\uDFCE-\uDFFF]|\uD83A[\uDC00-\uDCC4\uDCD0-\uDCD6]|\uD83B[\uDE00-\uDE03\uDE05-\uDE1F\uDE21\uDE22\uDE24\uDE27\uDE29-\uDE32\uDE34-\uDE37\uDE39\uDE3B\uDE42\uDE47\uDE49\uDE4B\uDE4D-\uDE4F\uDE51\uDE52\uDE54\uDE57\uDE59\uDE5B\uDE5D\uDE5F\uDE61\uDE62\uDE64\uDE67-\uDE6A\uDE6C-\uDE72\uDE74-\uDE77\uDE79-\uDE7C\uDE7E\uDE80-\uDE89\uDE8B-\uDE9B\uDEA1-\uDEA3\uDEA5-\uDEA9\uDEAB-\uDEBB]|\uD869[\uDC00-\uDED6\uDF00-\uDFFF]|\uD86D[\uDC00-\uDF34\uDF40-\uDFFF]|\uD86E[\uDC00-\uDC1D]|\uD87E[\uDC00-\uDE1D]|\uDB40[\uDD00-\uDDEF]/
},St.prototype=Et.prototype={processComment:function(){var e,t,n,r=N.bottomRightStack
,s,o,u=r[r.length-1];if(this.type===i.Program&&this.body.length>0)return;if(N.trailingComments
.length>0){n=[];for(s=N.trailingComments.length-1;s>=0;--s)o=N.trailingComments[
s],o.range[0]>=this.range[1]&&(n.unshift(o),N.trailingComments.splice(s,1));N.trailingComments=
[]}else u&&u.trailingComments&&u.trailingComments[0].range[0]>=this.range[1]&&(n=
u.trailingComments,delete u.trailingComments);while(u&&u.range[0]>=this.range[0]
)e=r.pop(),u=r[r.length-1];if(e){if(e.leadingComments){t=[];for(s=e.leadingComments
.length-1;s>=0;--s)o=e.leadingComments[s],o.range[1]<=this.range[0]&&(t.unshift(
o),e.leadingComments.splice(s,1));e.leadingComments.length||(e.leadingComments=undefined
)}}else if(N.leadingComments.length>0){t=[];for(s=N.leadingComments.length-1;s>=0
;--s)o=N.leadingComments[s],o.range[1]<=this.range[0]&&(t.unshift(o),N.leadingComments
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
