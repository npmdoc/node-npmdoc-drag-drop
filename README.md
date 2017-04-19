# npmdoc-drag-drop

#### api documentation for  [drag-drop (v2.13.2)](https://github.com/feross/drag-drop)  [![npm package](https://img.shields.io/npm/v/npmdoc-drag-drop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-drag-drop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-drag-drop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-drag-drop)

#### HTML5 drag & drop for humans

[![NPM](https://nodei.co/npm/drag-drop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/drag-drop)

- [https://npmdoc.github.io/node-npmdoc-drag-drop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-drag-drop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-drag-drop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-drag-drop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-drag-drop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-drag-drop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Feross Aboukhadijeh",
        "url": "http://feross.org/"
    },
    "bugs": {
        "url": "https://github.com/feross/drag-drop/issues"
    },
    "dependencies": {
        "blob-to-buffer": "^1.0.2",
        "flatten": "^1.0.2",
        "run-parallel": "^1.0.0"
    },
    "description": "HTML5 drag & drop for humans",
    "devDependencies": {
        "browserify": "^14.0.0",
        "ecstatic": "^2.1.0",
        "html-inline": "^1.2.0",
        "standard": "*",
        "tape": "^4.0.0",
        "uglify-js": "^2.4.15"
    },
    "directories": {},
    "dist": {
        "shasum": "a01ff4459123f5ae0a8c8bd9bb38c625ccb81550",
        "tarball": "https://registry.npmjs.org/drag-drop/-/drag-drop-2.13.2.tgz"
    },
    "gitHead": "1c5091696aabda2e7c2939ba11bc0819fbf60abe",
    "homepage": "https://github.com/feross/drag-drop",
    "keywords": [
        "drag",
        "drop",
        "dnd",
        "drag and drop",
        "drag drop",
        "html5",
        "drag & drop",
        "frontend",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "drag-drop",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/feross/drag-drop.git"
    },
    "scripts": {
        "build": "browserify -s DragDrop -r ./ | uglifyjs -c warnings=false -m > dragdrop.min.js",
        "demo": "html-inline example.html | curl -sT- https://htmlb.in",
        "example": "npm run build && ecstatic",
        "test": "standard && tape test/*.js"
    },
    "version": "2.13.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
