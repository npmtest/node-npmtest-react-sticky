# npmtest-react-sticky

#### basic test coverage for  [react-sticky (v5.0.8)](https://github.com/captivationsoftware/react-sticky)  [![npm package](https://img.shields.io/npm/v/npmtest-react-sticky.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-sticky) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-sticky.svg)](https://travis-ci.org/npmtest/node-npmtest-react-sticky)

#### Sticky component for React

[![NPM](https://nodei.co/npm/react-sticky.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-sticky)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-sticky/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-sticky/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-sticky/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-sticky/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-sticky/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-sticky/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-sticky/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-sticky/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-sticky/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-sticky/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-sticky/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-sticky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-sticky/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-sticky/build/test-report.html](https://npmtest.github.io/node-npmtest-react-sticky/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-sticky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-sticky/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-sticky/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-sticky/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-sticky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-sticky/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-sticky/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-sticky/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Captivation Software"
    },
    "bugs": {
        "url": "https://github.com/captivationsoftware/react-sticky/issues"
    },
    "dependencies": {
        "prop-types": "^15.5.8"
    },
    "description": "Sticky component for React",
    "devDependencies": {
        "babel-cli": "^6.6.0",
        "babel-core": "^6.6.0",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-plugin-transform-object-assign": "^6.5.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "chai": "^3.2.0",
        "jsdom": "8.0.4",
        "mocha": "^2.2.5",
        "react": "^0.14.0 || ^15.0.0",
        "react-addons-test-utils": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0",
        "rimraf": "^2.5.2",
        "webpack": "^1.12.14"
    },
    "directories": {},
    "dist": {
        "shasum": "d5f85f96977f410081d792ab81886c622c5d8b14",
        "tarball": "https://registry.npmjs.org/react-sticky/-/react-sticky-5.0.8.tgz"
    },
    "gitHead": "59df8d83cec4cb85d25c57fa94491fb6970f76c2",
    "homepage": "https://github.com/captivationsoftware/react-sticky",
    "keywords": [
        "react-component",
        "React",
        "Sticky"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "dbarbalato"
        }
    ],
    "name": "react-sticky",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/captivationsoftware/react-sticky.git"
    },
    "scripts": {
        "build": "npm run transpile && npm run dist",
        "clean": "rimraf lib dist",
        "dist": "webpack lib/index.js dist/react-sticky.js --display-modules --progress && NODE_ENV=production webpack lib/index.js dist/react-sticky.min.js --display-modules --progress",
        "prepublish": "npm run clean && npm run build",
        "test": "mocha --compilers js:babel-core/register test/unit",
        "transpile": "babel src --loose --out-dir lib"
    },
    "version": "5.0.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
