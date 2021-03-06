# npmdoc-express-content-length-validator

#### api documentation for  [express-content-length-validator (v1.0.0)](https://github.com/ericmdantas/express-content-length-validator)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-content-length-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-content-length-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-content-length-validator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-content-length-validator)

#### Make sure your application is not vulnerable to large payload attacks

[![NPM](https://nodei.co/npm/express-content-length-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-content-length-validator)

- [https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-content-length-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eric Mendes Dantas"
    },
    "bugs": {
        "url": "https://github.com/ericmdantas/express-content-length-validator/issues"
    },
    "dependencies": {},
    "description": "Make sure your application is not vulnerable to large payload attacks",
    "devDependencies": {
        "chai": "^1.10.0",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.5",
        "mocha": "^2.1.0",
        "mocha-lcov-reporter": "0.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0fc842bfb2d53380ff25520f789b47f20267ff31",
        "tarball": "https://registry.npmjs.org/express-content-length-validator/-/express-content-length-validator-1.0.0.tgz"
    },
    "gitHead": "bbadc8ce8dd7306d22794ccd93caac4070bac82f",
    "homepage": "https://github.com/ericmdantas/express-content-length-validator",
    "keywords": [
        "express",
        "validator",
        "content-length",
        "payload",
        "attack",
        "express-validator",
        "middleware",
        "express-content-length-validator"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "ericmdantas"
        }
    ],
    "name": "express-content-length-validator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ericmdantas/express-content-length-validator.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- tests/*_test.js",
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha -- tests/*_test.js --report lcovonly && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage",
        "test": "mocha ./tests/*_test.js --recursive --check-leaks --reporter min"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
