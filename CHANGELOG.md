### [0.4.3](https://github.com/danielroe/vue-sanity/compare/v0.4.2...v0.4.3) (2020-04-14)


### Features

* allow default options to be set ([2a2d631](https://github.com/danielroe/vue-sanity/commit/2a2d631150ba487b64b09976a69a93f70be8bcbd))

### [0.4.2](https://github.com/danielroe/vue-sanity/compare/v0.4.1...v0.4.2) (2020-04-13)


### Features

* add 'client' and 'server' cache strategies ([22e9b50](https://github.com/danielroe/vue-sanity/commit/22e9b50dc55ecb2f19fe03b18eddf1b3e132aa1e))
* allow providing a custom sanity client ([ceffd8f](https://github.com/danielroe/vue-sanity/commit/ceffd8f963acd0f1d08ccb0413999f29f6f29699))
* expose any error received in fetching query ([cf388ae](https://github.com/danielroe/vue-sanity/commit/cf388ae1f9e129cd31b9088747a8cb36913eeec5))
* expose manual fetcher for preloading cache ([7702713](https://github.com/danielroe/vue-sanity/commit/77027135362a39d3fe9cb1dcefa616d15c823480))


### Bug Fixes

* prefer fetch to (deprecated) triggerFetch ([851b91d](https://github.com/danielroe/vue-sanity/commit/851b91d17b55b8c44e2566d6eb2e4bd30b47db51))

### [0.4.1](https://github.com/danielroe/vue-sanity/compare/v0.4.0...v0.4.1) (2020-04-08)

## [0.4.0](https://github.com/danielroe/vue-sanity/compare/v0.3.1...v0.4.0) (2020-04-04)


### Features

* allow passing a builder function for dynamic queries ([f2d6ac5](https://github.com/danielroe/vue-sanity/commit/f2d6ac5c74e68c1413a4aecf437be754e108546f))

### [0.3.1](https://github.com/danielroe/vue-sanity/compare/v0.3.0...v0.3.1) (2020-04-01)


### Bug Fixes

* don't compile to cjs 🤦‍♂️ ([0dd72f7](https://github.com/danielroe/vue-sanity/commit/0dd72f7454f82e5d3203018575efaf4101095212))

## [0.3.0](https://github.com/danielroe/vue-sanity/compare/v0.2.2...v0.3.0) (2020-04-01)


### Features

* add sanity-typed-queries helper function ([174f1f7](https://github.com/danielroe/vue-sanity/commit/174f1f71d58e7c35c58299702d569b703ac134ee))


### Bug Fixes

* compile to commonjs ([c017616](https://github.com/danielroe/vue-sanity/commit/c01761684e42ae34eb03cc05351ad099b82274b7))


### Performance Improvements

* minify queries before sending to cache ([ec31114](https://github.com/danielroe/vue-sanity/commit/ec3111428400d42d5e4de7961d55abd1e7be59da))

### [0.2.2](https://github.com/danielroe/vue-sanity/compare/v0.2.1...v0.2.2) (2020-03-30)

### [0.2.1](https://github.com/danielroe/vue-sanity/compare/v0.2.0...v0.2.1) (2020-03-27)


### Bug Fixes

* remove optional chaining for broader support ([d35e93d](https://github.com/danielroe/vue-sanity/commit/d35e93dafaf5cca8dd8ed2e70dc8d245efe54fb7))

## [0.2.0](https://github.com/danielroe/vue-sanity/compare/v0.1.1...v0.2.0) (2020-03-27)


### ⚠ BREAKING CHANGES

* The options for useSanityFetcher have reversed - please see type definitions for details

### Features

* add support for real time events ([a13c51a](https://github.com/danielroe/vue-sanity/commit/a13c51a247ba8634be835b505a69b1155d605527))
* improve typing and interface to fetcher ([96f7385](https://github.com/danielroe/vue-sanity/commit/96f73853dc35f947094f93cc1a19984f713b5fb7))

### [0.1.1](https://github.com/danielroe/vue-sanity/compare/v0.1.0...v0.1.1) (2020-03-27)


### Bug Fixes

* better support for ssr ([b39b7ce](https://github.com/danielroe/vue-sanity/commit/b39b7cebb4ca478cfd68be2b4781fd3956107e76))

## 0.1.0 (2020-03-26)

