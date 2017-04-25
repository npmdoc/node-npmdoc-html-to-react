# npmdoc-html-to-react

#### basic api documentation for  [html-to-react (v1.2.7)](https://github.com/aknuds1/html-to-react)  [![npm package](https://img.shields.io/npm/v/npmdoc-html-to-react.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-html-to-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-html-to-react.svg)](https://travis-ci.org/npmdoc/node-npmdoc-html-to-react)

#### A lightweight library that converts raw HTML to a React DOM structure.

[![NPM](https://nodei.co/npm/html-to-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/html-to-react)

- [https://npmdoc.github.io/node-npmdoc-html-to-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-html-to-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-html-to-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-html-to-react/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-html-to-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-html-to-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arve Knudsen, Mike Nikles"
    },
    "bugs": {
        "url": "https://github.com/aknuds1/html-to-react/issues"
    },
    "config": {
        "blanket": {
            "pattern": [
                ""
            ],
            "data-cover-never": [
                "node_modules",
                "test"
            ]
        }
    },
    "dependencies": {
        "domhandler": "^2.3.0",
        "htmlparser2": "^3.8.3",
        "ramda": "^0.23.0",
        "underscore.string.fp": "^1.0.4"
    },
    "description": "A lightweight library that converts raw HTML to a React DOM structure.",
    "devDependencies": {
        "coveralls": "^2.11",
        "eslint": "^3.7.0",
        "istanbul": "^0.4",
        "mocha": "^3.0",
        "mocha-lcov-reporter": "^1.2.0",
        "react": "^15.0",
        "react-dom": "^15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b50b4737d020d728f1b4823543b82148372808dd",
        "tarball": "https://registry.npmjs.org/html-to-react/-/html-to-react-1.2.7.tgz"
    },
    "gitHead": "a73d19b80c56326677e96097d8fab3f5c46c5888",
    "homepage": "https://github.com/aknuds1/html-to-react",
    "keywords": [
        "react",
        "react-component",
        "html"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "arian.hosseinzadeh"
        },
        {
            "name": "arve.knudsen"
        },
        {
            "name": "mikenikles"
        }
    ],
    "name": "html-to-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aknuds1/html-to-react.git"
    },
    "scripts": {
        "test": "eslint . && ./node_modules/mocha/bin/mocha",
        "test-coverage": "eslint . && istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test-html-coverage": "eslint . && istanbul cover ./node_modules/mocha/bin/_mocha; open coverage/lcov-report/index.html"
    },
    "version": "1.2.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
