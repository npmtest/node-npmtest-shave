# npmtest-shave

#### basic test coverage for  [shave (v1.0.4)](https://github.com/dollarshaveclub/shave#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-shave.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shave) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shave.svg)](https://travis-ci.org/npmtest/node-npmtest-shave)

#### Shave is a javascript plugin that truncates multi-line text within a html element based on set max height

[![NPM](https://nodei.co/npm/shave.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shave)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shave/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shave/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shave/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shave/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shave/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shave/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shave/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shave/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shave/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shave/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shave/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shave/build/test-report.html](https://npmtest.github.io/node-npmtest-shave/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shave/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shave/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shave/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shave/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shave/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shave/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shave/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shave/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Wainwright",
        "url": "jeffry.in"
    },
    "bugs": {
        "url": "https://github.com/dollarshaveclub/shave/issues"
    },
    "dependencies": {},
    "description": "Shave is a javascript plugin that truncates multi-line text within a html element based on set max height",
    "devDependencies": {
        "babel-core": "^6.14.0",
        "babel-preset-es2015": "^6.14.0",
        "babel-preset-es2015-rollup": "^1.2.0",
        "bower": "^1.7.9",
        "debug": "^2.2.0",
        "eslint": "^3.4.0",
        "eslint-config-airbnb": "6.1.0",
        "gulp": "^3.9.1",
        "gulp-header": "^1.8.8",
        "gulp-qunit": "^1.5.0",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^2.0.0",
        "node-qunit-phantomjs": "^1.5.0",
        "rollup": "^0.34.13",
        "rollup-plugin-babel": "^2.6.1",
        "rollup-plugin-commonjs": "^4.1.0",
        "rollup-plugin-eslint": "^2.0.2",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-uglify": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1503c84cf2fefbe40649fce1e8e228b3967d6f61",
        "tarball": "https://registry.npmjs.org/shave/-/shave-1.0.4.tgz"
    },
    "files": [
        "dist",
        "src"
    ],
    "gitHead": "f473333c9bcf7d059d5910638eb4717b1014c291",
    "homepage": "https://github.com/dollarshaveclub/shave#readme",
    "keywords": [
        "ellipsis",
        "truncate",
        "truncation",
        "truncated",
        "semantic",
        "js",
        "content",
        "shorten",
        "javascript",
        "text",
        "shave",
        "trim"
    ],
    "license": "MIT",
    "main": "dist/shave.js",
    "maintainers": [
        {
            "name": "dollarshaveclub-engineering"
        },
        {
            "name": "yowainwright"
        }
    ],
    "name": "shave",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dollarshaveclub/shave.git"
    },
    "scripts": {
        "postpublish": "git tag $npm_package_version && git push origin --tags",
        "test": "gulp test"
    },
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
