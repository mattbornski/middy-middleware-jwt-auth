## [4.0.5](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/4.0.4...4.0.5) (2020-08-17)


### Bug Fixes

* package.json to reduce vulnerabilities ([9541b6c](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/9541b6c7df41cef50208f28d4df2d175ea294ea7))

## [4.0.4](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/4.0.3...4.0.4) (2020-08-09)


### Bug Fixes

* package.json to reduce vulnerabilities ([1c94bb5](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/1c94bb5824440c2adb5ae76a590f378f67b98deb))

## [4.0.3](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/4.0.2...4.0.3) (2020-06-20)


### Bug Fixes

* package.json & .snyk to reduce vulnerabilities ([7fde50e](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/7fde50e1129c720ccf28edfacfd226346ba08718))

## [4.0.2](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/4.0.1...4.0.2) (2020-06-20)


### Bug Fixes

* package.json & .snyk to reduce vulnerabilities ([8aeded9](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/8aeded9557c6499cbffe5d8829536d5258fd0cda))
* package.json & .snyk to reduce vulnerabilities ([677802b](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/677802b5a8598d856e11e8ed62a401d0372cfc9d))
* package.json to reduce vulnerabilities ([a384060](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/a38406017a054b57ae3fb0c4fc4474a6b91abc05))

## [4.0.1](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/4.0.0...4.0.1) (2020-06-20)


### Bug Fixes

* package.json to reduce vulnerabilities ([414d9ee](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/414d9ee0be17de15398bea5f087ad7b3eadf3190))

# [4.0.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/3.0.4...4.0.0) (2020-04-30)


### Bug Fixes

* upgrade to middy@1.0.0 ([52f7e22](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/52f7e22eab64713ad930ec25e8576f53e4c41e21))


### BREAKING CHANGES

* As of this version this middleware only supports middy@1.0.0 and upwards. See https://github.com/middyjs/middy/blob/master/UPGRADE.md for middy upgrade instructions.

## [3.0.4](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/3.0.3...3.0.4) (2020-04-18)


### Bug Fixes

* upgrade middy from 0.34.0 to 0.36.0 ([6e1ff2f](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/6e1ff2fbf23ad8a5d912edca27d58e30062466e6))

## [3.0.3](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/3.0.2...3.0.3) (2020-04-16)


### Bug Fixes

* make snyk a dev dependency ([53d72e7](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/53d72e707e6033dd6e3f97dd15a6188971896907))

## [3.0.2](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/3.0.1...3.0.2) (2020-04-10)


### Bug Fixes

* package.json & .snyk to reduce vulnerabilities ([7e56ba0](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/7e56ba05e8ddcfdb8bd28cd75c33c2effe65039b))
* package.json & .snyk to reduce vulnerabilities ([7598fbc](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/7598fbc39055366acf1a4a2ea11f7b07993adb3c))

## [3.0.1](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/3.0.0...3.0.1) (2020-03-27)


### Bug Fixes

* package.json to reduce vulnerabilities ([e6269bc](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/e6269bcbb76fad74b8eb75a876a862aad00cfff8))

# [3.0.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.4.0...3.0.0) (2019-11-19)


### Code Refactoring

* move payload to event.auth.payload ([c48a741](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/c48a741737ea01d10a8579f54493ad87eeabd022))


### Features

* give access to token in event.auth ([4ed1ef5](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/4ed1ef5b9eca68e95584d4f3a86805e00f2b5157))


### BREAKING CHANGES

* Previously the payload was found directly in event.auth, now it is in event.auth.payload to be able to put additional information into event.auth

# [2.4.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.3.0...2.4.0) (2019-07-29)


### Bug Fixes

* fix typing of before method ([034b5a9](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/034b5a9))
* log 'No authorization header found' in all cases ([be87d47](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/be87d47))


### Features

* add an option that allows making authorization mandatory ([cac01c1](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/cac01c1))
* reject unauthorized events when authorizationRequired is set ([e292328](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/e292328))
* update README.md ([c3acb83](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/c3acb83))

# [2.3.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.2.0...2.3.0) (2019-06-07)


### Features

* build module to commonjs ([a548656](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/a548656))

# [2.2.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.1.1...2.2.0) (2019-03-12)


### Features

* allow for tokenSources in middleware options ([01197c1](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/01197c1))
* get token via tokenSource if it is set in the options ([dc28c2d](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/dc28c2d))
* set default tokenSources ([e2d5593](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/e2d5593))

## [2.1.1](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.1.0...2.1.1) (2019-02-16)


### Bug Fixes

* stringify JWTAuthMiddleware options in error ([2f09634](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/2f09634))

# [2.1.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/2.0.0...2.1.0) (2019-02-16)


### Bug Fixes

* standardize date format in TokenExpired error message ([8ac46c9](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/8ac46c9))


### Features

* add logging of encryption algorithm in debug mode ([d4854b1](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/d4854b1))
* allow to check token payload with a type guard ([842232b](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/842232b))
* throw more explicit error if token expired ([50896bd](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/50896bd))
* throw more explicit error if token isn't valid yet ([3cb1c33](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/3cb1c33))

# [2.0.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/1.1.0...2.0.0) (2019-02-16)


### Features

* accept lower case authorization header ([86d9aaa](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/86d9aaa))
* add source maps to output ([74d7aab](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/74d7aab))


### BREAKING CHANGES

* Previously lowercase authorization headers were ignored. Now if both a lower case authorization and an upper case Authorization header are present, an error is thrown. Currently the middleware does not support use cases where both headers are present.

# [1.1.0](https://github.com/dbartholomae/middy-middleware-jwt-auth/compare/1.0.0...1.1.0) (2019-02-16)


### Features

* accept multivalue header format ([7d30dd1](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/7d30dd1))

# 1.0.0 (2019-02-15)


### Features

* add IAuthOptions interface ([05968f2](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/05968f2))
* add IAuthorizedEvent type ([91e785e](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/91e785e))
* add types to errors ([af89543](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/af89543))
* check if token is valid ([76bd162](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/76bd162))
* improve error message for wrong auth format ([7f40831](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/7f40831))
* save auth data to event.auth ([48d7646](https://github.com/dbartholomae/middy-middleware-jwt-auth/commit/48d7646))
