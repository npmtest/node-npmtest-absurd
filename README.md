# npmtest-absurd

#### basic test coverage for  [absurd (v0.3.8)](http://absurdjs.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-absurd.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-absurd) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-absurd.svg)](https://travis-ci.org/npmtest/node-npmtest-absurd)

#### JavaScript library with superpowers - http://absurdjs.com/

[![NPM](https://nodei.co/npm/absurd.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/absurd)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-absurd/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-absurd/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-absurd/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-absurd/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-absurd/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-absurd/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-absurd/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-absurd/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-absurd/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-absurd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-absurd/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-absurd/build/test-report.html](https://npmtest.github.io/node-npmtest-absurd/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-absurd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-absurd/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-absurd/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-absurd/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-absurd/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-absurd/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "absurd",
    "version": "0.3.8",
    "homepage": "http://absurdjs.com/",
    "description": "JavaScript library with superpowers - http://absurdjs.com/",
    "main": "./index.js",
    "browser": "./client-side/build/absurd.min.js",
    "author": {
        "name": "Krasimir Tsonev",
        "url": "http://krasimirtsonev.com"
    },
    "license": "MIT",
    "dependencies": {
        "optimist": "0.6.1",
        "colors": "0.6.2",
        "gaze": "1.1.0",
        "glob": "5.0.15",
        "js-yaml": "3.0.1",
        "js-beautify": "1.4.2"
    },
    "devDependencies": {
        "grunt": "0.4.2",
        "grunt-contrib-concat": "0.3.0",
        "grunt-contrib-watch": "0.5.3",
        "grunt-contrib-uglify": "0.3.2",
        "jasmine-node": "1.13.1"
    },
    "keywords": [
        "css",
        "preprocessor"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/krasimir/absurd.git"
    },
    "bin": {
        "absurd": "./index.js"
    },
    "scripts": {
        "test": "./node_modules/jasmine-node/bin/jasmine-node ./tests"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
