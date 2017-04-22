# npmdoc-jquery.cookie

#### api documentation for  jquery.cookie (v1.4.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-jquery.cookie.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jquery.cookie) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jquery.cookie.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jquery.cookie)

#### A simple, lightweight jQuery plugin for reading, writing and deleting cookies.

[![NPM](https://nodei.co/npm/jquery.cookie.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jquery.cookie)

- [https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jquery.cookie/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "jquery.cookie",
    "version": "1.4.1",
    "description": "A simple, lightweight jQuery plugin for reading, writing and deleting cookies.",
    "main": "jquery.cookie.js",
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "grunt"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/carhartl/jquery-cookie.git"
    },
    "author": "Klaus Hartl",
    "license": "MIT",
    "gitHead": "bd3c9713222bace68d25fe2128c0f8633cad1269",
    "readmeFilename": "README.md",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-contrib-jshint": "~0.4.0",
        "grunt-contrib-uglify": "~0.2.0",
        "grunt-contrib-qunit": "~0.2.0",
        "grunt-contrib-watch": "~0.3.0",
        "grunt-compare-size": "~0.4.0",
        "grunt-saucelabs": "~4.1.1",
        "grunt-contrib-connect": "~0.5.0",
        "gzip-js": "~0.3.0"
    },
    "volo": {
        "url": "https://raw.github.com/carhartl/jquery-cookie/v{version}/jquery.cookie.js"
    },
    "jspm": {
        "main": "jquery.cookie",
        "files": [
            "jquery.cookie.js"
        ],
        "buildConfig": {
            "uglify": true
        }
    },
    "jam": {
        "dependencies": {
            "jquery": ">=1.2"
        },
        "main": "jquery.cookie.js",
        "include": [
            "jquery.cookie.js"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
