# npmtest-vue-material

#### basic test coverage for  [vue-material (v0.7.1)](https://vuematerial.github.io)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-material.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-material) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-material.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-material)

#### Material Design for Vue.js

[![NPM](https://nodei.co/npm/vue-material.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-material)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-material/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-material/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-material/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-material/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-material/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-material/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-material/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-material/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-material/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-material/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-material/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-material/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-material/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-material/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-material/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-material/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-material/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-material/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-material/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "vue-material",
    "description": "Material Design for Vue.js",
    "version": "0.7.1",
    "author": "Marcos Moura <marcosvmmoura@gmail.com>",
    "homepage": "https://vuematerial.github.io",
    "license": "MIT",
    "registry": "github",
    "repository": {
        "type": "git",
        "url": "https://github.com/marcosmoura/vue-material.git"
    },
    "bugs": {
        "url": "https://github.com/marcosmoura/vue-material/issues"
    },
    "keywords": [
        "browser",
        "vue",
        "vue 2",
        "vue2",
        "vuejs",
        "material design",
        "material",
        "angular-material",
        "components"
    ],
    "main": "dist/vue-material.js",
    "files": [
        "dist",
        "src",
        "LICENSE",
        "README.md"
    ],
    "scripts": {
        "dev": "babel-node build/server/index.js --presets es2015,stage-0",
        "build:docs": "babel-node build/server/build-docs.js --presets es2015,stage-0",
        "build:lib": "babel-node build/server/build-lib.js --presets es2015,stage-0",
        "build": "rm -rf dist && npm run build:docs && npm run build:lib",
        "lint": "eslint --ext .js,.vue --fix src",
        "release": "bash build/release.sh"
    },
    "dependencies": {
        "vue": "^2.1.10"
    },
    "devDependencies": {
        "autoprefixer": "^6.7.2",
        "autosize": "^3.0.20",
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.10",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-runtime": "^6.22.0",
        "babel-preset-env": "^1.1.8",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-es2017": "^6.22.0",
        "babel-preset-stage-0": "^6.22.0",
        "chalk": "^1.1.3",
        "chokidar": "^1.6.1",
        "clipboard": "^1.5.16",
        "connect-history-api-fallback": "^1.3.0",
        "copy-webpack-plugin": "^4.0.1",
        "css-loader": "^0.26.1",
        "css-mqpacker": "^5.0.1",
        "element.scrollintoviewifneeded-polyfill": "^1.0.1",
        "eslint": "^3.15.0",
        "eslint-friendly-formatter": "^2.0.7",
        "eslint-loader": "^1.6.1",
        "eslint-plugin-html": "^2.0.0",
        "eventsource-polyfill": "^0.9.6",
        "express": "^4.14.1",
        "extract-text-webpack-plugin": "beta",
        "file-loader": "^0.10.0",
        "friendly-errors-webpack-plugin": "^1.1.3",
        "highlight.js": "^9.9.0",
        "html-webpack-plugin": "^2.28.0",
        "node-sass": "^4.5.0",
        "optimize-css-assets-webpack-plugin": "^1.3.0",
        "optimize-js-plugin": "^0.0.4",
        "ora": "^1.1.0",
        "raw-loader": "^0.5.1",
        "sass-loader": "^5.0.0",
        "url-loader": "^0.5.7",
        "vue-hot-reload-api": "^2.0.8",
        "vue-html-loader": "^1.2.3",
        "vue-loader": "^10.3.0",
        "vue-router": "^2.2.0",
        "vue-style-loader": "^2.0.0",
        "vue-template-compiler": "^2.1.10",
        "webpack": "^2.2.1",
        "webpack-dev-middleware": "^1.10.0",
        "webpack-hot-middleware": "^2.16.1",
        "webpack-merge": "^2.6.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
