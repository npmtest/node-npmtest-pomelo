# npmtest-pomelo

#### basic test coverage for  [pomelo (v2.2.5)](https://github.com/NetEase/pomelo)  [![npm package](https://img.shields.io/npm/v/npmtest-pomelo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pomelo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pomelo.svg)](https://travis-ci.org/npmtest/node-npmtest-pomelo)

#### Pomelo is a fast, scalable game server framework for [node.js](http://nodejs.org). It provides the basic development framework and many related components, including libraries and tools. Pomelo is also suitable for real-time web applications; its distribu

[![NPM](https://nodei.co/npm/pomelo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pomelo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pomelo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pomelo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pomelo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pomelo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pomelo/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pomelo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pomelo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pomelo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pomelo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pomelo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pomelo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pomelo/build/test-report.html](https://npmtest.github.io/node-npmtest-pomelo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pomelo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pomelo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pomelo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pomelo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pomelo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pomelo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pomelo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pomelo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "pomelo": "./bin/pomelo"
    },
    "bugs": {
        "url": "https://github.com/NetEase/pomelo/issues"
    },
    "contributors": [
        {
            "name": "* Charlie Crane"
        },
        {
            "name": "* Chang chang"
        },
        {
            "name": "* piaohai"
        },
        {
            "name": "* py8765"
        },
        {
            "name": "* Demon"
        },
        {
            "name": "* numbcoder"
        },
        {
            "name": "* halfblood"
        },
        {
            "name": "* fantasyni"
        }
    ],
    "dependencies": {
        "async": "0.2.5",
        "cliff": "0.1.8",
        "commander": "2.0.0",
        "crc": "0.2.0",
        "mkdirp": "0.3.3",
        "mqtt": "0.3.9",
        "node-bignumber": "1.2.1",
        "pomelo-admin": "1.0.0",
        "pomelo-loader": "0.0.6",
        "pomelo-logger": "0.1.7",
        "pomelo-protobuf": "0.4.0",
        "pomelo-protocol": "0.1.6",
        "pomelo-rpc": "1.0.7",
        "pomelo-scheduler": "0.3.9",
        "seq-queue": "0.0.5",
        "socket.io": "1.7.2",
        "ws": "1.1.1"
    },
    "description": "Pomelo is a fast, scalable game server framework for [node.js](http://nodejs.org). It provides the basic development framework and many related components, including libraries and tools. Pomelo is also suitable for real-time web applications; its distribu",
    "devDependencies": {
        "blanket": "~1.1.6",
        "grunt": "~0.4.2",
        "grunt-contrib-clean": "0.5.x",
        "grunt-contrib-jshint": "~0.8.0",
        "grunt-mocha-test": "0.8.x",
        "mocha": ">=0.0.1",
        "muk": ">=0.0.1",
        "should": "3.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "198ac4cb6a6485e7b0c0c618ecd8cb7c2c326de3",
        "tarball": "https://registry.npmjs.org/pomelo/-/pomelo-2.2.5.tgz"
    },
    "gitHead": "4cbeab70a8f9f7d013c1164acf691bc0654c861d",
    "homepage": "https://github.com/NetEase/pomelo",
    "keywords": [
        "pomelo",
        "framework",
        "game",
        "web",
        "realtime",
        "server"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/NetEase/pomelo#license"
        }
    ],
    "maintainers": [
        {
            "name": "changchang"
        },
        {
            "name": "cynron"
        },
        {
            "name": "fantasyni"
        },
        {
            "name": "fibonacci"
        },
        {
            "name": "halfblood369"
        },
        {
            "name": "palmtoy"
        },
        {
            "name": "piaohai"
        },
        {
            "name": "py8765"
        },
        {
            "name": "xieccy"
        },
        {
            "name": "zhangmin510"
        },
        {
            "name": "zhhxu2011"
        }
    ],
    "name": "pomelo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/NetEase/pomelo.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "2.2.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
