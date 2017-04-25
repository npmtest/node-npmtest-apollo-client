# npmtest-apollo-client

#### basic test coverage for  [apollo-client (v1.0.4)](https://github.com/apollographql/apollo-client#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apollo-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apollo-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apollo-client.svg)](https://travis-ci.org/npmtest/node-npmtest-apollo-client)

#### A simple yet functional GraphQL client.

[![NPM](https://nodei.co/npm/apollo-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apollo-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apollo-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apollo-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apollo-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apollo-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apollo-client/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-apollo-client/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-apollo-client/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apollo-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apollo-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apollo-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apollo-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apollo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apollo-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apollo-client/build/test-report.html](https://npmtest.github.io/node-npmtest-apollo-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apollo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apollo-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apollo-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apollo-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apollo-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apollo-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apollo-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apollo-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sashko Stubailo"
    },
    "bugs": {
        "url": "https://github.com/apollographql/apollo-client/issues"
    },
    "dependencies": {
        "@types/async": "^2.0.31",
        "@types/graphql": "^0.9.0",
        "@types/isomorphic-fetch": "0.0.33",
        "graphql": "^0.9.3",
        "graphql-anywhere": "^3.0.1",
        "graphql-tag": "^2.0.0",
        "redux": "^3.4.0",
        "symbol-observable": "^1.0.2",
        "whatwg-fetch": "^2.0.0"
    },
    "description": "A simple yet functional GraphQL client.",
    "devDependencies": {
        "@types/benchmark": "^1.0.30",
        "@types/chai": "3.4.35",
        "@types/chai-as-promised": "0.0.30",
        "@types/lodash": "^4.14.62",
        "@types/mocha": "^2.2.31",
        "@types/node": "^7.0.5",
        "@types/promises-a-plus": "0.0.27",
        "@types/sinon": "^2.1.0",
        "benchmark": "^2.1.3",
        "browserify": "^14.3.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "colors": "^1.1.2",
        "concurrently": "^3.1.0",
        "es6-promise": "^4.0.4",
        "fetch-mock": "^5.10.0",
        "grunt": "1.0.1",
        "grunt-tslint": "^5.0.1",
        "gzip-size": "^3.0.0",
        "isomorphic-fetch": "^2.2.1",
        "istanbul": "^0.4.5",
        "lodash": "^4.17.1",
        "minimist": "^1.2.0",
        "mocha": "^3.0.0",
        "nodemon": "^1.11.0",
        "pretty-bytes": "^4.0.0",
        "remap-istanbul": "0.8.0",
        "request": "^2.75.0",
        "rollup": "^0.41.3",
        "rxjs": "^5.0.0-beta.11",
        "sinon": "^2.1.0",
        "source-map-support": "^0.4.0",
        "tslint": "^5.1.0",
        "typescript": "2.2.2",
        "uglify-js": "^2.6.2",
        "webpack": "^2.1.0-beta.28",
        "webpack-bundle-analyzer": "^2.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "af75db8cdd27e08a835ddfb39807849e178540f9",
        "tarball": "https://registry.npmjs.org/apollo-client/-/apollo-client-1.0.4.tgz"
    },
    "homepage": "https://github.com/apollographql/apollo-client#readme",
    "jsnext:main": "index.js",
    "keywords": [
        "ecmascript",
        "es2015",
        "jsnext",
        "javascript",
        "relay",
        "npm",
        "react"
    ],
    "license": "MIT",
    "main": "apollo.umd.js",
    "maintainers": [
        {
            "name": "calebmer"
        },
        {
            "name": "glasser"
        },
        {
            "name": "helfer"
        },
        {
            "name": "mdg"
        },
        {
            "name": "sashko"
        },
        {
            "name": "tmeasday"
        }
    ],
    "module": "index.js",
    "name": "apollo-client",
    "optionalDependencies": {
        "@types/async": "^2.0.31",
        "@types/graphql": "^0.9.0",
        "@types/isomorphic-fetch": "0.0.33"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/apollographql/apollo-client.git"
    },
    "scripts": {},
    "typings": "index.d.ts",
    "version": "1.0.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
