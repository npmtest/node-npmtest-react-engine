# npmtest-react-engine

#### basic test coverage for  [react-engine (v4.3.0)](https://github.com/paypal/react-engine#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-engine.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-engine) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-engine.svg)](https://travis-ci.org/npmtest/node-npmtest-react-engine)

#### a composite render engine for express apps to render both plain react views and react-router views

[![NPM](https://nodei.co/npm/react-engine.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-engine)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-engine/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-engine/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-engine/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-engine/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-engine/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-engine/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-engine/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-engine/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-engine/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-engine/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-engine/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-engine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-engine/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-engine/build/test-report.html](https://npmtest.github.io/node-npmtest-react-engine/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-engine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-engine/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-engine/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-engine/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-engine/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-engine/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-engine/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-engine/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sam Selvanathan"
    },
    "bugs": {
        "url": "https://github.com/paypal/react-engine/issues"
    },
    "contributors": [
        {
            "name": "Vu Hwang"
        },
        {
            "name": "Robert Kuo"
        },
        {
            "name": "Jinto Jose"
        },
        {
            "name": "Jared Halpert"
        },
        {
            "name": "Weng Zhi Ping"
        },
        {
            "name": "Vincent Orr"
        },
        {
            "name": "skarflacka"
        },
        {
            "name": "Mark"
        }
    ],
    "dependencies": {
        "debug": "^2.1.3",
        "glob": "^7.0.5",
        "jsesc": "^2.2.0",
        "lodash": "^4.13.1",
        "parent-require": "^1.0.0"
    },
    "description": "a composite render engine for express apps to render both plain react views and react-router views",
    "devDependencies": {
        "babel-core": "^6.3.26",
        "babel-preset-react": "^6.3.13",
        "babel-register": "^6.3.13",
        "cheerio": "^0.20.0",
        "eslint": "^2.13.1",
        "eslint-config-airbnb": "^9.0.1",
        "eslint-plugin-import": "^1.9.2",
        "eslint-plugin-jsx-a11y": "^1.5.3",
        "eslint-plugin-react": "^5.2.2",
        "express": "^4.12",
        "faucet": "0.0.1",
        "jsdom": "^9.2.1",
        "react": "^15.3.2",
        "react-dom": "^15.3.2",
        "react-router": "^2.4.0",
        "rewire": "^2.3.1",
        "sinon": "^1.14.1",
        "tape": "^4.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "09ef3126d7ee057644667e21c0d6167f530e62a6",
        "tarball": "https://registry.npmjs.org/react-engine/-/react-engine-4.3.0.tgz"
    },
    "gitHead": "05ab077544beb83849b298de3a343e54603cb3ae",
    "homepage": "https://github.com/paypal/react-engine#readme",
    "keywords": [
        "react",
        "render",
        "render engine",
        "react-router",
        "view engine",
        "express",
        "jsx"
    ],
    "license": "Apache-2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "samsel"
        },
        {
            "name": "vuhwang"
        }
    ],
    "name": "react-engine",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.3.2",
        "react-dom": "^15.3.2"
    },
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/paypal/react-engine.git"
    },
    "scripts": {
        "lint": "eslint .",
        "tape": "tape test/*.js | faucet",
        "test": "npm run tape"
    },
    "version": "4.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
