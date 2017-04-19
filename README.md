# npmdoc-bows

#### api documentation for  [bows (v1.6.0)](https://github.com/latentflip/bows#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bows.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bows) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bows.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bows)

#### Rainbowed console logs for chrome, opera and firefox in development.

[![NPM](https://nodei.co/npm/bows.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bows)

- [https://npmdoc.github.io/node-npmdoc-bows/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bows/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bows/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bows/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bows/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bows/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Philip Roberts"
    },
    "bugs": {
        "url": "https://github.com/latentflip/bows/issues"
    },
    "dependencies": {
        "andlog": "^1.0.0"
    },
    "description": "Rainbowed console logs for chrome, opera and firefox in development.",
    "devDependencies": {
        "browserify": "^5.10.0",
        "phantomjs": "^1.9.7-8",
        "uglify-js": "^2.3.6"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "0c7d65c9682ce8adedac50d709cc498c9628da05",
        "tarball": "https://registry.npmjs.org/bows/-/bows-1.6.0.tgz"
    },
    "gitHead": "bd7b0c00f47771a342ddc098cdc7e5ee5b4a53b3",
    "homepage": "https://github.com/latentflip/bows#readme",
    "keywords": [
        "color",
        "logging",
        "chrome",
        "console"
    ],
    "license": "MIT",
    "main": "bows.js",
    "maintainers": [
        {
            "name": "latentflip"
        },
        {
            "name": "nlf"
        }
    ],
    "name": "bows",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/latentflip/bows.git"
    },
    "scripts": {
        "build": "node build.js",
        "preversion": "git checkout master && git pull && npm ls",
        "publish-major": "npm run preversion && npm version major && git push origin master --tags && npm publish",
        "publish-minor": "npm run preversion && npm version minor && git push origin master --tags && npm publish",
        "publish-patch": "npm run preversion && npm version patch && git push origin master --tags && npm publish",
        "test": "node build.js && phantomjs test/index.js"
    },
    "version": "1.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
