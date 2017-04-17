# api documentation for  [github-url-to-object (v3.1.0)](https://github.com/zeke/github-url-to-object#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-github-url-to-object.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-github-url-to-object) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-github-url-to-object.svg)](https://travis-ci.org/npmdoc/node-npmdoc-github-url-to-object)
#### Extract user, repo, and other interesting properties from GitHub URLs

[![NPM](https://nodei.co/npm/github-url-to-object.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/github-url-to-object)

- [https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-github-url-to-object/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "zeke"
    },
    "browser": {
        "url": "./url-browser"
    },
    "bugs": {
        "url": "https://github.com/zeke/github-url-to-object/issues"
    },
    "dependencies": {
        "is-url": "^1.1.0"
    },
    "description": "Extract user, repo, and other interesting properties from GitHub URLs",
    "devDependencies": {
        "browserify": "^13.0.1",
        "buble": "^0.15.2",
        "mocha": "^2.5.3",
        "standard": "^7.1.2",
        "uglify-js": "^2.4.15"
    },
    "directories": {},
    "dist": {
        "shasum": "160a5d55ad7cf0459e0757f7912d718076b7ed7d",
        "tarball": "https://registry.npmjs.org/github-url-to-object/-/github-url-to-object-3.1.0.tgz"
    },
    "gitHead": "272793ef9cab8df426718ad15589fcce6b61fdad",
    "homepage": "https://github.com/zeke/github-url-to-object#readme",
    "keywords": [
        "github",
        "url",
        "repo"
    ],
    "license": "MIT",
    "main": "dist/commonjs.js",
    "maintainers": [
        {
            "name": "zeke"
        }
    ],
    "name": "github-url-to-object",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zeke/github-url-to-object.git"
    },
    "scripts": {
        "build": "browserify index.js --standalone gh | buble > dist/gh.js; buble index.js > dist/commonjs.js",
        "deploy": "npm run build && git subtree push --prefix dist origin gh-pages && open https://zeke.github.io/github-url-to-object",
        "test": "mocha && standard"
    },
    "standard": {
        "ignore": [
            "dist"
        ]
    },
    "version": "3.1.0",
    "website": "https://zeke.github.io/github-url-to-object"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
