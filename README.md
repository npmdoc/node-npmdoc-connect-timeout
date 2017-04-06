# api documentation for  [connect-timeout (v1.8.0)](https://github.com/expressjs/timeout)  [![npm package](https://img.shields.io/npm/v/npmdoc-connect-timeout.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-connect-timeout) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-connect-timeout.svg)](https://travis-ci.org/npmdoc/node-npmdoc-connect-timeout)
#### Request timeout middleware for Connect/Express

[![NPM](https://nodei.co/npm/connect-timeout.png?downloads=true)](https://www.npmjs.com/package/connect-timeout)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-connect-timeout_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-connect-timeout/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/expressjs/timeout/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "Jonathan Ong",
            "email": "me@jongleberry.com",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "http-errors": "~1.5.1",
        "ms": "0.7.2",
        "on-finished": "~2.3.0",
        "on-headers": "~1.0.1"
    },
    "description": "Request timeout middleware for Connect/Express",
    "devDependencies": {
        "eslint": "3.10.2",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-markdown": "1.0.0-beta.3",
        "eslint-plugin-promise": "3.4.0",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4b74c58ad0303e069e4f417af388a058cfa3b839",
        "tarball": "https://registry.npmjs.org/connect-timeout/-/connect-timeout-1.8.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "31fde61ec2f9b454481e2eef0f34925dc805efb5",
    "homepage": "https://github.com/expressjs/timeout",
    "license": "MIT",
    "maintainers": [
        {
            "name": "aaron",
            "email": "aaron.heckmann+github@gmail.com"
        },
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "rauchg",
            "email": "rauchg@gmail.com"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "connect-timeout",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/timeout.git"
    },
    "scripts": {
        "lint": "eslint --plugin markdown --ext js,md .",
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter dot --check-leaks test/"
    },
    "version": "1.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module connect-timeout](#apidoc.module.connect-timeout)



# <a name="apidoc.module.connect-timeout"></a>[module connect-timeout](#apidoc.module.connect-timeout)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
