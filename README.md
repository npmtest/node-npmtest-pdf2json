# npmtest-pdf2json

#### basic test coverage for  [pdf2json (v1.1.7)](https://github.com/modesty/pdf2json)  [![npm package](https://img.shields.io/npm/v/npmtest-pdf2json.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pdf2json) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pdf2json.svg)](https://travis-ci.org/npmtest/node-npmtest-pdf2json)

#### A PDF file parser that converts PDF binaries to text based JSON, powered by porting a fork of PDF.JS to Node.js

[![NPM](https://nodei.co/npm/pdf2json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pdf2json)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pdf2json/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdf2json/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pdf2json/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pdf2json/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pdf2json/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pdf2json/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pdf2json/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pdf2json/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pdf2json/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdf2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pdf2json/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pdf2json/build/test-report.html](https://npmtest.github.io/node-npmtest-pdf2json/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pdf2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pdf2json/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pdf2json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pdf2json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdf2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdf2json/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pdf2json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pdf2json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Modesty Zhang",
        "url": "http://www.codeproject.com/script/Articles/MemberArticles.aspx?amid=62372"
    },
    "bin": {
        "pdf2json": "./bin/pdf2json"
    },
    "bugs": {
        "url": "http://github.com/modesty/pdf2json/issues"
    },
    "bundleDependencies": [
        "xmldom",
        "lodash",
        "optimist",
        "async"
    ],
    "contributors": [],
    "dependencies": {
        "async": "^2.0.1",
        "lodash": "^4.15.0",
        "optimist": "^0.6.1",
        "xmldom": "^0.1.22"
    },
    "description": "A PDF file parser that converts PDF binaries to text based JSON, powered by porting a fork of PDF.JS to Node.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "a09d705ce64d82cbc7d0473d1424963f751bec32",
        "tarball": "https://registry.npmjs.org/pdf2json/-/pdf2json-1.1.7.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "c5551c298e49564a8c4d8fb0af8ed97f2f4ecfdc",
    "homepage": "https://github.com/modesty/pdf2json",
    "keywords": [
        "pdf",
        "pdf parser",
        "convert pdf to json",
        "server side PDF parser",
        "port pdf.js to node.js",
        "PDF binary to text",
        "commandline utility to parse pdf to json",
        "JSON",
        "javascript",
        "PDF canvas",
        "pdf.js fork"
    ],
    "licenses": [
        {
            "type": "Apache v2",
            "url": "https://github.com/modesty/pdf2json/blob/master/license.txt"
        }
    ],
    "main": "./pdfparser.js",
    "maintainers": [
        {
            "name": "modesty"
        }
    ],
    "name": "pdf2json",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/modesty/pdf2json.git"
    },
    "scripts": {
        "test": "cd ./test && sh p2j.forms.sh",
        "test-misc": "node pdf2json.js -f ./test/pdf/misc/ -o ./test/target/misc/ -c -m"
    },
    "version": "1.1.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
