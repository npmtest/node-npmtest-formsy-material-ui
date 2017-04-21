# npmtest-formsy-material-ui

#### basic test coverage for  [formsy-material-ui (v0.6.0)](https://github.com/mbrookes/formsy-material-ui#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-formsy-material-ui.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-formsy-material-ui) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-formsy-material-ui.svg)](https://travis-ci.org/npmtest/node-npmtest-formsy-material-ui)

#### A formsy-react compatibility wrapper for Material-UI form components.

[![NPM](https://nodei.co/npm/formsy-material-ui.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/formsy-material-ui)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-formsy-material-ui/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-formsy-material-ui/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-formsy-material-ui/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-formsy-material-ui/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-formsy-material-ui/build/test-report.html](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-formsy-material-ui/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-formsy-material-ui/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-formsy-material-ui/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-formsy-material-ui/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-formsy-material-ui/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "formsy-material-ui",
    "version": "0.6.0",
    "description": "A formsy-react compatibility wrapper for Material-UI form components.",
    "main": "./lib/index.js",
    "scripts": {
        "build": "babel ./src -d ./lib",
        "prepublish": "npm run build",
        "lint": "eslint --ext .jsx,.js src test && echo \"eslint: no lint errors\"",
        "test": "PHANTOMJS_BIN=$(npm bin)/phantomjs $(npm bin)/karma start --single-run",
        "test:watch": "PHANTOMJS_BIN=$(npm bin)/phantomjs $(npm bin)/karma start"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mbrookes/formsy-material-ui.git"
    },
    "files": [
        "lib",
        "src"
    ],
    "dependencies": {
        "keycode": "^2.1.0"
    },
    "peerDependencies": {
        "formsy-react": "^0.19.0",
        "material-ui": "^0.17.0",
        "react": "^15.0.0",
        "react-dom": "^15.0.0"
    },
    "devDependencies": {
        "babel-cli": "^6.3.17",
        "babel-core": "^6.5.1",
        "babel-eslint": "^6.0.0",
        "babel-loader": "^6.2.2",
        "babel-polyfill": "^6.5.0",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babel-preset-stage-1": "^6.3.13",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.4.0",
        "cheerio": "^0.20.0",
        "enzyme": "^2.2.0",
        "eslint": "^2.5.1",
        "eslint-plugin-babel": "^3.1.0",
        "eslint-plugin-react": "^4.0.0",
        "formsy-react": "^0.19.0",
        "json-loader": "^0.5.4",
        "karma": "^0.13.19",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^0.2.2",
        "karma-mocha": "^0.2.1",
        "karma-mocha-reporter": "^1.1.5",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-phantomjs-shim": "^1.2.0",
        "karma-sinon": "^1.0.4",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "material-ui": "^0.17.0",
        "mocha": "^2.4.5",
        "phantomjs-prebuilt": "^2.1.4",
        "react": "^15.0.0",
        "react-addons-test-utils": "^15.0.0",
        "react-dom": "^15.0.0",
        "react-tap-event-plugin": "^2.0.1",
        "sinon": "^1.17.3",
        "sinon-chai": "^2.8.0",
        "webpack": "^1.12.13"
    },
    "keywords": [
        "formsy",
        "formsy-react",
        "form",
        "MUI",
        "Material-UI",
        "React",
        "jsx",
        "react-component"
    ],
    "author": {
        "name": "Matt Brookes",
        "url": "https://github.com/mbrookes"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/mbrookes/formsy-material-ui/issues"
    },
    "homepage": "https://github.com/mbrookes/formsy-material-ui#readme",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
