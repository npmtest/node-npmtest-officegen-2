# npmtest-officegen-2

#### test coverage for  [officegen-2 (v0.3.7)](https://github.com/vtloc/officegen#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-officegen-2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-officegen-2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-officegen-2.svg)](https://travis-ci.org/npmtest/node-npmtest-officegen-2)

#### Office Open XML Generator using Node.js streams. Supporting Microsoft Office 2007 and later Word (docx), PowerPoint (pptx,ppsx) and Excel (xlsx). This module is for all frameworks and environments. No need for any commandline tool - this module is doing everything inside it.

[![NPM](https://nodei.co/npm/officegen-2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/officegen-2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-officegen-2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-officegen-2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-officegen-2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-officegen-2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-officegen-2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-officegen-2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-officegen-2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-officegen-2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-officegen-2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-officegen-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-officegen-2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-officegen-2/build/test-report.html](https://npmtest.github.io/node-npmtest-officegen-2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-officegen-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-officegen-2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-officegen-2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-officegen-2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-officegen-2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-officegen-2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-officegen-2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-officegen-2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ziv Barber",
        "url": "http://code.zivbarber.com/"
    },
    "bugs": {
        "url": "https://github.com/vtloc/officegen/issues"
    },
    "dependencies": {
        "archiver": ">= 0.4.4",
        "coffee-script": "*",
        "fast-image-size": "*",
        "moment": "~2.5.0",
        "readable-stream": "~1.0.0",
        "setimmediate": ">= 1.0.1",
        "underscore": "*",
        "xmlbuilder": "*"
    },
    "description": "Office Open XML Generator using Node.js streams. Supporting Microsoft Office 2007 and later Word (docx), PowerPoint (pptx,ppsx) and Excel (xlsx). This module is for all frameworks and environments. No need for any commandline tool - this module is doing everything inside it.",
    "devDependencies": {
        "grunt": "~0.4.2",
        "grunt-contrib-coffee": "~0.7.0",
        "grunt-contrib-cssmin": "~0.7.0",
        "grunt-contrib-less": "~0.8.2",
        "grunt-contrib-mincss": "~0.3.2",
        "grunt-contrib-uglify": "~0.2.7",
        "grunt-contrib-watch": "~0.5.3"
    },
    "directories": {
        "lib": "lib",
        "examples": "examples"
    },
    "dist": {
        "shasum": "21815e0f06cdfc884923bfb619048a4108e622ef",
        "tarball": "https://registry.npmjs.org/officegen-2/-/officegen-2-0.3.7.tgz"
    },
    "homepage": "https://github.com/vtloc/officegen#readme",
    "keywords": [
        "officegen",
        "office",
        "microsoft",
        "2007",
        "word",
        "powerpoint",
        "excel",
        "docx",
        "pptx",
        "ppsx",
        "xlsx",
        "Office Open XML",
        "stream",
        "generate",
        "create",
        "maker",
        "generator",
        "creator"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/Ziv-Barber/officegen/blob/master/LICENSE-MIT"
        }
    ],
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "vtloc"
        }
    ],
    "name": "officegen-2",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vtloc/officegen.git"
    },
    "scripts": {
        "test": "node examples/make_pptx.js"
    },
    "url": "https://github.com/vtloc/officegen",
    "version": "0.3.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
