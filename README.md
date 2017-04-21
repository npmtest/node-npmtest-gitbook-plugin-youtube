# npmtest-gitbook-plugin-youtube

#### basic test coverage for  [gitbook-plugin-youtube (v2.0.0)](https://github.com/GitbookIO/plugin-youtube)  [![npm package](https://img.shields.io/npm/v/npmtest-gitbook-plugin-youtube.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gitbook-plugin-youtube) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gitbook-plugin-youtube.svg)](https://travis-ci.org/npmtest/node-npmtest-gitbook-plugin-youtube)

#### Insert Youtube videos in your pages.

[![NPM](https://nodei.co/npm/gitbook-plugin-youtube.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gitbook-plugin-youtube)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gitbook-plugin-youtube/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gitbook-plugin-youtube/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/test-report.html](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gitbook-plugin-youtube/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gitbook-plugin-youtube/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gitbook-plugin-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gitbook-plugin-youtube/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gitbook-plugin-youtube/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "title": "Youtube",
    "name": "gitbook-plugin-youtube",
    "description": "Insert Youtube videos in your pages.",
    "main": "index.js",
    "browser": "./_assets/plugin.js",
    "ebook": "./_assets/plugin.js",
    "version": "2.0.0",
    "engines": {
        "gitbook": ">=4.0.0-alpha"
    },
    "homepage": "https://github.com/GitbookIO/plugin-youtube",
    "repository": {
        "type": "git",
        "url": "https://github.com/GitbookIO/plugin-youtube.git"
    },
    "license": "Apache 2",
    "bugs": {
        "url": "https://github.com/GitbookIO/plugin-youtube/issues"
    },
    "scripts": {
        "build-js": "gitbook-plugin build ./src/index.js ./_assets/plugin.js",
        "prepublish": "npm run build-js"
    },
    "dependencies": {
        "get-youtube-id": "^1.0.0"
    },
    "devDependencies": {
        "eslint": "^3.7.1",
        "eslint-config-gitbook": "^1.5.0",
        "gitbook-plugin": "^4.0.0-alpha.1"
    },
    "icon": "./icon.png",
    "keywords": [
        "gitbook",
        "plugin",
        "youtube",
        "gitbook:content"
    ],
    "gitbook": {
        "blocks": {
            "youtube": {
                "title": "Youtube Video",
                "properties": {
                    "src": {
                        "type": "string",
                        "title": "URL of the video",
                        "required": true
                    }
                }
            }
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
