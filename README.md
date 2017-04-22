# npmtest-emailjs

#### basic test coverage for  [emailjs (v1.0.8)](https://github.com/eleith/emailjs#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-emailjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-emailjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-emailjs.svg)](https://travis-ci.org/npmtest/node-npmtest-emailjs)

#### send text/html emails and attachments (files, streams and strings) from node.js to any smtp server

[![NPM](https://nodei.co/npm/emailjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/emailjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-emailjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-emailjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-emailjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-emailjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-emailjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-emailjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-emailjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-emailjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-emailjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-emailjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-emailjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-emailjs/build/test-report.html](https://npmtest.github.io/node-npmtest-emailjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-emailjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-emailjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-emailjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-emailjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-emailjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-emailjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-emailjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-emailjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "eleith"
    },
    "bugs": {
        "url": "https://github.com/eleith/emailjs/issues"
    },
    "contributors": [
        {
            "name": "izuzak"
        },
        {
            "name": "Hiverness"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "jimmybergman"
        }
    ],
    "dependencies": {
        "addressparser": "^0.3.2",
        "bufferjs": "=1.1.0",
        "mimelib": "0.2.14",
        "moment": "= 2.11.2",
        "starttls": "1.0.1"
    },
    "description": "send text/html emails and attachments (files, streams and strings) from node.js to any smtp server",
    "devDependencies": {
        "chai": "= 1.1.0",
        "iconv": "2.1.6",
        "mailparser": "0.4.1",
        "mocha": "= 1.7.4",
        "simplesmtp": "0.3.32"
    },
    "directories": {},
    "dist": {
        "shasum": "d4240db7670dc78aff97352092d8460edc130f66",
        "tarball": "https://registry.npmjs.org/emailjs/-/emailjs-1.0.8.tgz"
    },
    "engine": [
        "node >= 0.10"
    ],
    "gitHead": "09a3b8e899f4f2e6287220bba5584f5ec4a0df30",
    "homepage": "https://github.com/eleith/emailjs#readme",
    "license": "MIT",
    "main": "email.js",
    "maintainers": [
        {
            "name": "eleith"
        }
    ],
    "name": "emailjs",
    "optionalDependencies": {
        "bufferjs": "=1.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/eleith/emailjs.git"
    },
    "scripts": {
        "test": "mocha -R spec -t 5000"
    },
    "version": "1.0.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
