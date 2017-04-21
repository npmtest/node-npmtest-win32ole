# npmtest-win32ole

#### basic test coverage for  [win32ole (v0.1.3)](https://github.com/idobatter/node-win32ole)  [![npm package](https://img.shields.io/npm/v/npmtest-win32ole.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-win32ole) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-win32ole.svg)](https://travis-ci.org/npmtest/node-npmtest-win32ole)

#### Asynchronous, non-blocking win32ole bindings

[![NPM](https://nodei.co/npm/win32ole.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/win32ole)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-win32ole/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-win32ole/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-win32ole/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-win32ole/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-win32ole/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-win32ole/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-win32ole/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-win32ole/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-win32ole/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-win32ole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-win32ole/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-win32ole/build/test-report.html](https://npmtest.github.io/node-npmtest-win32ole/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-win32ole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-win32ole/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-win32ole/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-win32ole/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-win32ole/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-win32ole/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-win32ole/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-win32ole/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "win32ole",
    "version": "0.1.3",
    "description": "Asynchronous, non-blocking win32ole bindings",
    "homepage": "https://github.com/idobatter/node-win32ole",
    "keywords": [
        "OLE",
        "COM",
        "ActiveX",
        "ActiveXObject",
        "CreateObject",
        "WSH",
        "WMI",
        "Outlook",
        "Access",
        "Word",
        "Excel",
        "IE",
        "InternetExplorer"
    ],
    "author": {
        "name": "idobatter",
        "url": "https://github.com/idobatter"
    },
    "contributors": [
        "idobatter <idobatter@gmail.com>"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/idobatter/node-win32ole.git"
    },
    "dependencies": {
        "assert": ">= 0.4.9",
        "async": ">= 0.1.22",
        "ref-struct": ">= 0.0.5",
        "ref": ">= 0.1.3"
    },
    "devDependencies": {
        "mocha": ">= 1.8.1",
        "assert": ">= 0.4.9",
        "async": ">= 0.1.22",
        "ref-struct": ">= 0.0.5",
        "ref": ">= 0.1.3"
    },
    "engines": {
        "node": ">= 0.8.18 && < 0.9.0"
    },
    "scripts": {
        "test": "nmake /a test"
    },
    "licenses": [
        {
            "type": "BSD"
        }
    ],
    "main": "./lib/win32ole",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
