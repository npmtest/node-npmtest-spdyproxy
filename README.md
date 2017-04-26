# npmtest-spdyproxy

#### basic test coverage for  [spdyproxy (v0.2.7)](https://github.com/igrigorik/node-spdyproxy)  [![npm package](https://img.shields.io/npm/v/npmtest-spdyproxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spdyproxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spdyproxy.svg)](https://travis-ci.org/npmtest/node-npmtest-spdyproxy)

#### Fast, secure forward proxy: secure connection to proxy and ability to tunnel HTTP, HTTPS, and SPDY.

[![NPM](https://nodei.co/npm/spdyproxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spdyproxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spdyproxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spdyproxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spdyproxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spdyproxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spdyproxy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-spdyproxy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-spdyproxy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spdyproxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spdyproxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spdyproxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spdyproxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spdyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spdyproxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spdyproxy/build/test-report.html](https://npmtest.github.io/node-npmtest-spdyproxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spdyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spdyproxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spdyproxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spdyproxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spdyproxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spdyproxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spdyproxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spdyproxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ilya Grigorik",
        "url": "http://www.igvita.com"
    },
    "bin": {
        "spdyproxy": "./bin/spdyproxy"
    },
    "bugs": {
        "url": "https://github.com/igrigorik/node-spdyproxy/issues"
    },
    "contributors": [],
    "dependencies": {
        "colors": "*",
        "memory-cache": "*",
        "optimist": "~ 0.3.5",
        "radius": "~ 0.1",
        "spdy": "~ 1.26.0"
    },
    "description": "Fast, secure forward proxy: secure connection to proxy and ability to tunnel HTTP, HTTPS, and SPDY.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "1daa6362359e6d411b69ec8c087c55e72585b4cc",
        "tarball": "https://registry.npmjs.org/spdyproxy/-/spdyproxy-0.2.7.tgz"
    },
    "engines": [
        "node >= 0.8.0"
    ],
    "homepage": "https://github.com/igrigorik/node-spdyproxy",
    "keywords": [
        "spdy",
        "proxy",
        "vpn",
        "chrome"
    ],
    "main": "./lib/server.js",
    "maintainers": [
        {
            "name": "igrigorik"
        }
    ],
    "name": "spdyproxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/igrigorik/node-spdyproxy.git"
    },
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "version": "0.2.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
