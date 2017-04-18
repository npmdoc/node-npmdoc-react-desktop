# api documentation for  [react-desktop (v0.2.19)](https://github.com/gabrielbull/react-desktop#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-desktop.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-desktop) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-desktop.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-desktop)
#### React UI Components for macOS Sierra and Windows 10

[![NPM](https://nodei.co/npm/react-desktop.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-desktop)

- [https://npmdoc.github.io/node-npmdoc-react-desktop/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-desktop/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-desktop/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-desktop/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-desktop/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-desktop/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gabriel Bull"
    },
    "bugs": {
        "url": "https://github.com/gabrielbull/react-desktop/issues"
    },
    "dependencies": {
        "radium": "^0.18.1"
    },
    "description": "React UI Components for macOS Sierra and Windows 10",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-core": "^6.24.0",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.4.0",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-preset-es2015": "^6.24.0",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-0": "^6.22.0",
        "chai": "^3.5.0",
        "eslint": "^3.17.1",
        "eslint-plugin-react": "^6.10.0",
        "html-webpack-plugin": "^2.28.0",
        "jsdom": "^9.12.0",
        "mocha": "^3.2.0",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-color": "^2.11.4",
        "react-dom": "^15.4.2",
        "react-hot-loader": "^1.3.1",
        "webpack": "^2.2.1",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "806335a20cbe005aadd3284660fe542c1f89b96c",
        "tarball": "https://registry.npmjs.org/react-desktop/-/react-desktop-0.2.19.tgz"
    },
    "homepage": "https://github.com/gabrielbull/react-desktop#readme",
    "keywords": [
        "react",
        "react-component",
        "electron",
        "node-webkit",
        "native",
        "desktop",
        "ui",
        "user",
        "interface",
        "component",
        "os x",
        "macOS",
        "mac",
        "windows"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "gabrielbull"
        }
    ],
    "name": "react-desktop",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.0.0",
        "react-dom": "^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gabrielbull/react-desktop.git"
    },
    "scripts": {
        "build": "babel ./build/src --out-dir ./build/src && ./node_modules/.bin/babel ./build/index.js --out-file ./build/index.js && ./node_modules/.bin/babel ./build/macOs.js --out-file ./build/osx.js && ./node_modules/.bin/babel ./build/macOs.js --out-file ./build/macOs.js && ./node_modules/.bin/babel ./build/windows.js --out-file ./build/windows.js",
        "build-publish": "npm run build && npm publish ./build",
        "eslint": "eslint ./src ./test",
        "playground": "webpack-dev-server --config ./playground/webpack.config.js --colors --inline --port 3001",
        "prebuild": "rsync -av -delete . build --exclude build --exclude .git --exclude .idea && npm run eslint && npm run test",
        "test": "mocha test"
    },
    "version": "0.2.19"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
