# npmtest-eslint-friendly-formatter

#### basic test coverage for  [eslint-friendly-formatter (v2.0.7)](https://github.com/royriojas/eslint-friendly-formatter#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-friendly-formatter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-friendly-formatter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-friendly-formatter.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-friendly-formatter)

####  simple formatter/reporter for eslint that's friendly with Sublime Text and iterm2 'click to open file' functionality

[![NPM](https://nodei.co/npm/eslint-friendly-formatter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-friendly-formatter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-friendly-formatter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-friendly-formatter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-friendly-formatter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-friendly-formatter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-friendly-formatter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-friendly-formatter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-friendly-formatter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Roy Riojas",
        "url": "http://royriojas.com"
    },
    "bugs": {
        "url": "https://github.com/royriojas/eslint-friendly-formatter/issues"
    },
    "changelogx": {
        "issueIDRegExp": "#(\\d+)",
        "commitURL": "https://github.com/royriojas/eslint-friendly-formatter/commit/{0}",
        "authorURL": "https://github.com/{0}",
        "issueIDURL": "https://github.com/royriojas/eslint-friendly-formatter/issues/{0}",
        "projectName": "eslint-friendly-formatter"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "extend": "^3.0.0",
        "minimist": "^1.2.0",
        "text-table": "^0.2.0"
    },
    "description": " simple formatter/reporter for eslint that's friendly with Sublime Text and iterm2 'click to open file' functionality",
    "devDependencies": {
        "changelogx": "^1.0.18",
        "esbeautifier": "10.1.1",
        "eslint": "^2.10.2",
        "glob-expand": "0.2.1",
        "istanbul": "^0.3.17",
        "mocha-runner": "^1.0.8",
        "precommit": "1.2.2",
        "prepush": "3.1.11",
        "proxyquire": "^1.6.0",
        "read-file": "^0.1.2",
        "read-json-sync": "^1.1.0",
        "watch-spawn": "^1.0.3",
        "write": "^0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "657f95a19af4989636afebb1cc9de6cebbd088ee",
        "tarball": "https://registry.npmjs.org/eslint-friendly-formatter/-/eslint-friendly-formatter-2.0.7.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "process.js"
    ],
    "gitHead": "9ac3e4866e5c6dba09e0185dd4a1dd284a432d57",
    "homepage": "https://github.com/royriojas/eslint-friendly-formatter#readme",
    "keywords": [
        "eslint",
        "formatter",
        "reporter",
        "eslint formatter",
        "stylish"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "royriojas"
        }
    ],
    "name": "eslint-friendly-formatter",
    "optionalDependencies": {},
    "precommit": [
        "npm run verify"
    ],
    "prepush": [
        "npm run verify"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/royriojas/eslint-friendly-formatter.git"
    },
    "scripts": {
        "beautify": "esbeautifier './index.js' 'test/specs/**/*.js'",
        "beautify-check": "esbeautifier -k './index.js' 'test/specs/**/*.js'",
        "bump-major": "npm run pre-v && npm version major -m 'BLD: Release v%s' && npm run post-v",
        "bump-minor": "npm run pre-v && npm version minor -m 'BLD: Release v%s' && npm run post-v",
        "bump-patch": "npm run pre-v && npm version patch -m 'BLD: Release v%s' && npm run post-v",
        "changelog": "changelogx -f markdown -o ./changelog.md",
        "check": "npm run beautify-check && npm run eslint",
        "cover": "istanbul cover -x 'test/specs/**/*.js' mocha-runner 'test/specs/**/*.js' html text-summary",
        "do-changelog": "npm run changelog && git add ./changelog.md && git commit -m 'DOC: Generate changelog' --no-verify",
        "eslint": "eslint --format './index.js' index.js test/specs/ -c './configs/eslint.json'",
        "install-hooks": "prepush install && changelogx install-hook && precommit install",
        "lint": "npm run beautify-check && npm run eslint",
        "lint-fix": "npm run beautify && npm run eslint -- --fix",
        "post-v": "npm run do-changelog && git push --no-verify && git push --tags --no-verify",
        "pre-v": "npm run verify",
        "test": "npm run lint && mocha-runner 'test/specs/**/*.js'",
        "verify": "npm run check && npm test",
        "watch": "npm run cover && watch-spawn -i -p 'test/specs/**/*.js' istanbul cover test/runner.js html text-summary"
    },
    "version": "2.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
