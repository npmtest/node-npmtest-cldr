# npmtest-cldr

#### basic test coverage for  [cldr (v4.2.0)](https://github.com/papandreou/node-cldr#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cldr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cldr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cldr.svg)](https://travis-ci.org/npmtest/node-npmtest-cldr)

#### Library for extracting data from CLDR (the Unicode Common Locale Data Repository)

[![NPM](https://nodei.co/npm/cldr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cldr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cldr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cldr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cldr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cldr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cldr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cldr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cldr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cldr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cldr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cldr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cldr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cldr/build/test-report.html](https://npmtest.github.io/node-npmtest-cldr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cldr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cldr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cldr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cldr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cldr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cldr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cldr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cldr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andreas Lind"
    },
    "bugs": {
        "url": "https://github.com/papandreou/node-cldr/issues"
    },
    "dependencies": {
        "memoizeasync": "0.8.0",
        "passerror": "0.0.1",
        "pegjs": "0.9.0",
        "seq": "0.3.5",
        "uglify-js": "1.3.3",
        "underscore": "1.3.3",
        "unicoderegexp": "0.4.1",
        "xmldom": "0.1.19",
        "xpath": "0.0.7"
    },
    "description": "Library for extracting data from CLDR (the Unicode Common Locale Data Repository)",
    "devDependencies": {
        "coveralls": "2.12.0",
        "eslint": "3.17.1",
        "eslint-config-onelint": "2.0.0",
        "istanbul": "0.4.4",
        "mocha": "3.0.2",
        "unexpected": "10.15.1",
        "unexpected-function-equality": "1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "d7b39911cb2ed06e4d251cf45db0385e4f7c303d",
        "tarball": "https://registry.npmjs.org/cldr/-/cldr-4.2.0.tgz"
    },
    "gitHead": "8d23a725d6e1bb8e43fe7e0e73764ad84c509b64",
    "homepage": "https://github.com/papandreou/node-cldr#readme",
    "keywords": [
        "locale",
        "i18n",
        "cldr",
        "l10n",
        "internationalization",
        "localization",
        "date",
        "time",
        "interval",
        "format",
        "formats",
        "pattern",
        "patterns",
        "plural",
        "plurals",
        "number",
        "country",
        "territory",
        "time",
        "zone",
        "timezone",
        "currency",
        "script",
        "list",
        "units"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/cldr.js",
    "maintainers": [
        {
            "name": "joelmukuthu"
        },
        {
            "name": "maartenwinter"
        },
        {
            "name": "papandreou"
        }
    ],
    "name": "cldr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/papandreou/node-cldr.git"
    },
    "scripts": {
        "coverage": "istanbul cover --report text --report lcov -x lib/cldrPluralRuleTermFunctionByName.js _mocha",
        "lint": "eslint .",
        "preversion": "npm test",
        "test": "mocha --check-leaks",
        "travis": "npm test && npm run lint && npm run coverage && (<coverage/lcov.info coveralls || true)"
    },
    "version": "4.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
