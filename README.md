# npmtest-nodemailer-smtp-transport

#### basic test coverage for  [nodemailer-smtp-transport (v2.7.4)](http://github.com/andris9/nodemailer-smtp-transport)  [![npm package](https://img.shields.io/npm/v/npmtest-nodemailer-smtp-transport.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodemailer-smtp-transport) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodemailer-smtp-transport.svg)](https://travis-ci.org/npmtest/node-npmtest-nodemailer-smtp-transport)

#### SMTP transport for Nodemailer

[![NPM](https://nodei.co/npm/nodemailer-smtp-transport.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodemailer-smtp-transport)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodemailer-smtp-transport/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodemailer-smtp-transport/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/test-report.html](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodemailer-smtp-transport/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodemailer-smtp-transport/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodemailer-smtp-transport/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodemailer-smtp-transport/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodemailer-smtp-transport/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nodemailer-smtp-transport",
    "version": "2.7.4",
    "description": "SMTP transport for Nodemailer",
    "main": "lib/smtp-transport.js",
    "scripts": {
        "test": "grunt mochaTest"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/andris9/nodemailer-smtp-transport.git"
    },
    "keywords": [
        "SMTP",
        "Nodemailer"
    ],
    "author": "Andris Reinman",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/andris9/nodemailer-smtp-transport/issues"
    },
    "homepage": "http://github.com/andris9/nodemailer-smtp-transport",
    "dependencies": {
        "nodemailer-shared": "1.1.0",
        "nodemailer-wellknown": "0.1.10",
        "smtp-connection": "2.12.0"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-eslint": "^19.0.0",
        "grunt-mocha-test": "^0.12.7",
        "mocha": "^3.0.2",
        "smtp-server": "^1.14.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
