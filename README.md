# npmdoc-shipit-deploy

#### api documentation for  [shipit-deploy (v2.4.0)](https://github.com/shipitjs/shipit-deploy)  [![npm package](https://img.shields.io/npm/v/npmdoc-shipit-deploy.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-shipit-deploy) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-shipit-deploy.svg)](https://travis-ci.org/npmdoc/node-npmdoc-shipit-deploy)

#### Set of deployment tasks for Shipit based on git and rsync commands.

[![NPM](https://nodei.co/npm/shipit-deploy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shipit-deploy)

- [https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "shipit-deploy",
    "version": "2.4.0",
    "description": "Set of deployment tasks for Shipit based on git and rsync commands. ",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "files": [
        "index.js",
        "tasks",
        "lib"
    ],
    "scripts": {
        "test": "mocha --recursive"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/shipitjs/shipit-deploy.git"
    },
    "keywords": [
        "shipit",
        "deploy",
        "task"
    ],
    "author": "Greg Bergé <berge.greg@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/shipitjs/shipit-deploy/issues"
    },
    "homepage": "https://github.com/shipitjs/shipit-deploy",
    "devDependencies": {
        "chai": "^3.4.1",
        "mocha": "^2.1.0",
        "rewire": "^2.1.4",
        "shipit-cli": "^1.4.1",
        "sinon": "^1.12.2",
        "sinon-as-promised": "^4.0.0",
        "sinon-chai": "^2.7.0"
    },
    "dependencies": {
        "bluebird": "^3.0.6",
        "chalk": "^1.0.0",
        "lodash": "^4.6.1",
        "mkdirp": "^0.5.0",
        "moment": "^2.12.0",
        "path2": "^0.1.0",
        "shipit-utils": "^1.1.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
