### [1.1.2](https://github.com/libp2p/js-libp2p-mplex/compare/v1.1.1...v1.1.2) (2022-06-08)


### Bug Fixes

* add per-connection stream limit ([#173](https://github.com/libp2p/js-libp2p-mplex/issues/173)) ([21371e7](https://github.com/libp2p/js-libp2p-mplex/commit/21371e7251b1d5523d7e4e09afa9a2ea3daa8079))

### [1.1.1](https://github.com/libp2p/js-libp2p-mplex/compare/v1.1.0...v1.1.1) (2022-06-08)


### Bug Fixes

* re-enable encode from Uint8ArrayList test ([#172](https://github.com/libp2p/js-libp2p-mplex/issues/172)) ([897031f](https://github.com/libp2p/js-libp2p-mplex/commit/897031fa79cf5b8c2a746228341c8d31169c2af9))

## [1.1.0](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.5...v1.1.0) (2022-05-23)


### Features

* close read and write streams ([#170](https://github.com/libp2p/js-libp2p-mplex/issues/170)) ([3917968](https://github.com/libp2p/js-libp2p-mplex/commit/39179686ae033a2cc2821707dbec9e766fb4e099)), closes [#120](https://github.com/libp2p/js-libp2p-mplex/issues/120) [#115](https://github.com/libp2p/js-libp2p-mplex/issues/115)

### [1.0.5](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.4...v1.0.5) (2022-05-05)


### Bug Fixes

* ignore missing stream ([#169](https://github.com/libp2p/js-libp2p-mplex/issues/169)) ([f6d3dd9](https://github.com/libp2p/js-libp2p-mplex/commit/f6d3dd9f55020df93c8e7e116cb2ce1614b3404b))

### [1.0.4](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.3...v1.0.4) (2022-05-04)


### Bug Fixes

* update interfaces ([#168](https://github.com/libp2p/js-libp2p-mplex/issues/168)) ([f592f96](https://github.com/libp2p/js-libp2p-mplex/commit/f592f96adb6527da633fdc235890e32e53625906))

### [1.0.3](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.2...v1.0.3) (2022-04-09)


### Trivial Changes

* update aegir ([#167](https://github.com/libp2p/js-libp2p-mplex/issues/167)) ([0ef0c36](https://github.com/libp2p/js-libp2p-mplex/commit/0ef0c36f4d84d85ddbc06b725967bd9edac7a1cc))

### [1.0.2](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.1...v1.0.2) (2022-03-17)


### Bug Fixes

* update interfaces ([#162](https://github.com/libp2p/js-libp2p-mplex/issues/162)) ([ab9079c](https://github.com/libp2p/js-libp2p-mplex/commit/ab9079c26a5c98ea5487107e79bbf17ae9b34ad2))

### [1.0.1](https://github.com/libp2p/js-libp2p-mplex/compare/v1.0.0...v1.0.1) (2022-02-21)


### Bug Fixes

* update interfaces ([#160](https://github.com/libp2p/js-libp2p-mplex/issues/160)) ([43db1cb](https://github.com/libp2p/js-libp2p-mplex/commit/43db1cb61440859abc2cdefe5a9a362d0bf19497))


### Trivial Changes

* module name ([0137b94](https://github.com/libp2p/js-libp2p-mplex/commit/0137b9451e554a32d7e1f1c10eaacc00df225762))

## [1.0.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.7...v1.0.0) (2022-02-14)


### ⚠ BREAKING CHANGES

* switch to named exports, ESM only

Co-authored-by: Marin Petrunić <mpetrunic@users.noreply.github.com>

### Features

* convert to typescript ([#158](https://github.com/libp2p/js-libp2p-mplex/issues/158)) ([0cf727a](https://github.com/libp2p/js-libp2p-mplex/commit/0cf727ae101b3006400701b781d05a12eada59b7))

### [0.10.7](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.6...v0.10.7) (2022-01-14)


### Bug Fixes

* remove abort controller dep ([#152](https://github.com/libp2p/js-libp2p-mplex/issues/152)) ([96943cb](https://github.com/libp2p/js-libp2p-mplex/commit/96943cb68bc01efffd7045f0c5a9a3ed978fbf0e))

### [0.10.6](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.5...v0.10.6) (2022-01-14)


### Trivial Changes

* switch to unified ci ([#151](https://github.com/libp2p/js-libp2p-mplex/issues/151)) ([f14c349](https://github.com/libp2p/js-libp2p-mplex/commit/f14c34974c8b298179782f5ce3de93fb439fd764))

## [0.10.5](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.4...v0.10.5) (2021-12-07)


### Performance Improvements

* do not call varint.decode() if buffer has 0 length ([#125](https://github.com/libp2p/js-libp2p-mplex/issues/125)) ([92f1727](https://github.com/libp2p/js-libp2p-mplex/commit/92f1727342c278a8dd025623cc4fe6cb265485e9))



## [0.10.4](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.3...v0.10.4) (2021-07-08)



## [0.10.3](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.2...v0.10.3) (2021-04-16)



## [0.10.2](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.5...v0.10.2) (2021-01-29)


### Bug Fixes

* ensure stream closes on abort or reset ([#116](https://github.com/libp2p/js-libp2p-mplex/issues/116)) ([77835b3](https://github.com/libp2p/js-libp2p-mplex/commit/77835b326fbce02e3a9bf92f0084d01e4e1d9cf9))
* replace node buffers with uint8arrays ([#114](https://github.com/libp2p/js-libp2p-mplex/issues/114)) ([d005338](https://github.com/libp2p/js-libp2p-mplex/commit/d005338154b6882a22396e921ba4a38cc4e213fc))


### BREAKING CHANGES

* - All use of node Buffers has been replaced with Uint8Arrays

* fix: keep allocUnsafe for node for performance

Co-authored-by: Jacob Heun <jacobheun@gmail.com>



## [0.10.1](https://github.com/libp2p/js-libp2p-mplex/compare/v0.10.0...v0.10.1) (2020-10-22)


### Bug Fixes

* ensure stream closes on abort or reset ([#116](https://github.com/libp2p/js-libp2p-mplex/issues/116)) ([77835b3](https://github.com/libp2p/js-libp2p-mplex/commit/77835b326fbce02e3a9bf92f0084d01e4e1d9cf9))



<a name="0.10.0"></a>
# [0.10.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.5...v0.10.0) (2020-08-11)


### Bug Fixes

* replace node buffers with uint8arrays ([#114](https://github.com/libp2p/js-libp2p-mplex/issues/114)) ([d005338](https://github.com/libp2p/js-libp2p-mplex/commit/d005338))


### BREAKING CHANGES

* - All use of node Buffers has been replaced with Uint8Arrays

* fix: keep allocUnsafe for node for performance

Co-authored-by: Jacob Heun <jacobheun@gmail.com>



<a name="0.9.5"></a>
## [0.9.5](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.4...v0.9.5) (2020-03-18)


### Bug Fixes

* add buffer ([#106](https://github.com/libp2p/js-libp2p-mplex/issues/106)) ([71f3e5b](https://github.com/libp2p/js-libp2p-mplex/commit/71f3e5b))



<a name="0.9.4"></a>
## [0.9.4](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.3...v0.9.4) (2020-02-13)


### Performance Improvements

* small bl ([#101](https://github.com/libp2p/js-libp2p-mplex/issues/101)) ([7da79b6](https://github.com/libp2p/js-libp2p-mplex/commit/7da79b6))



<a name="0.9.3"></a>
## [0.9.3](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.2...v0.9.3) (2019-11-28)


### Features

* message splitting ([#100](https://github.com/libp2p/js-libp2p-mplex/issues/100)) ([fba56a5](https://github.com/libp2p/js-libp2p-mplex/commit/fba56a5))



<a name="0.9.2"></a>
## [0.9.2](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.1...v0.9.2) (2019-10-28)



<a name="0.9.1"></a>
## [0.9.1](https://github.com/libp2p/js-libp2p-mplex/compare/v0.9.0...v0.9.1) (2019-09-23)


### Features

* add better support for external stream metadata tracking ([#98](https://github.com/libp2p/js-libp2p-mplex/issues/98)) ([96f1ca0](https://github.com/libp2p/js-libp2p-mplex/commit/96f1ca0))



<a name="0.9.0"></a>
# [0.9.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.5...v0.9.0) (2019-09-18)


### Code Refactoring

* async iterators ([#94](https://github.com/libp2p/js-libp2p-mplex/issues/94)) ([c9bede5](https://github.com/libp2p/js-libp2p-mplex/commit/c9bede5))


### BREAKING CHANGES

* All places in the API that used callbacks are now replaced with async/await while pull-streams are replaced with async iterators. The API has also been updated according to the latest `interface-stream-muxer` version, https://github.com/libp2p/interface-stream-muxer/tree/v0.7.0.

License: MIT
Signed-off-by: Alan Shaw <alan.shaw@protocol.ai>



<a name="0.8.5"></a>
## [0.8.5](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.4...v0.8.5) (2019-03-18)



<a name="0.8.4"></a>
## [0.8.4](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.3...v0.8.4) (2018-11-15)



<a name="0.8.3"></a>
## [0.8.3](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.2...v0.8.3) (2018-11-08)


### Bug Fixes

* muxer.end will no longer hang ([#86](https://github.com/libp2p/js-libp2p-mplex/issues/86)) ([e23cbaf](https://github.com/libp2p/js-libp2p-mplex/commit/e23cbaf))



<a name="0.8.2"></a>
## [0.8.2](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.1...v0.8.2) (2018-10-01)


### Bug Fixes

* improve resiliency of internals _send ([#84](https://github.com/libp2p/js-libp2p-mplex/issues/84)) ([70dafb7](https://github.com/libp2p/js-libp2p-mplex/commit/70dafb7))



<a name="0.8.1"></a>
## [0.8.1](https://github.com/libp2p/js-libp2p-mplex/compare/v0.8.0...v0.8.1) (2018-10-01)


### Bug Fixes

* verify drain before new push ([#82](https://github.com/libp2p/js-libp2p-mplex/issues/82)) ([cd77e01](https://github.com/libp2p/js-libp2p-mplex/commit/cd77e01))



<a name="0.8.0"></a>
# [0.8.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.7.0...v0.8.0) (2018-06-19)


### Bug Fixes

* add setImmediatte to the call of callback ([8cdcd0d](https://github.com/libp2p/js-libp2p-mplex/commit/8cdcd0d))
* catch Multiplexer is destroyed error into callback ([#79](https://github.com/libp2p/js-libp2p-mplex/issues/79)) ([b60205f](https://github.com/libp2p/js-libp2p-mplex/commit/b60205f))
* missing dep and readme example ([#77](https://github.com/libp2p/js-libp2p-mplex/issues/77)) ([904cd7c](https://github.com/libp2p/js-libp2p-mplex/commit/904cd7c))
* package.json deps semver ([126b966](https://github.com/libp2p/js-libp2p-mplex/commit/126b966))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.6.0...v0.7.0) (2018-04-05)



<a name="0.6.0"></a>
# [0.6.0](https://github.com/libp2p/js-libp2p-mplex/compare/v0.5.1...v0.6.0) (2018-02-19)


### Features

* mplex is all here ([20cf80a](https://github.com/libp2p/js-libp2p-mplex/commit/20cf80a))
* support new Buffer ([c1384c3](https://github.com/libp2p/js-libp2p-mplex/commit/c1384c3))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.5.0...v0.5.1) (2017-12-14)


### Features

* porting to new aegir ([#70](https://github.com/libp2p/js-libp2p-multiplex/issues/70)) ([30fc825](https://github.com/libp2p/js-libp2p-multiplex/commit/30fc825))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.4.4...v0.5.0) (2017-09-03)


### Features

* p2p addrs situation ([#69](https://github.com/libp2p/js-libp2p-multiplex/issues/69)) ([d58f50e](https://github.com/libp2p/js-libp2p-multiplex/commit/d58f50e))



<a name="0.4.4"></a>
## [0.4.4](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.4.3...v0.4.4) (2017-07-08)



<a name="0.4.3"></a>
## [0.4.3](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.4.2...v0.4.3) (2017-03-21)



<a name="0.4.2"></a>
## [0.4.2](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.4.1...v0.4.2) (2017-03-21)


### Bug Fixes

* add missing setImmediate shim ([b039b81](https://github.com/libp2p/js-libp2p-multiplex/commit/b039b81)), closes [#61](https://github.com/libp2p/js-libp2p-multiplex/issues/61)



<a name="0.4.1"></a>
## [0.4.1](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.4.0...v0.4.1) (2017-02-21)


### Bug Fixes

* correct handling of multiplex options ([fa78df4](https://github.com/libp2p/js-libp2p-multiplex/commit/fa78df4))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.6...v0.4.0) (2017-02-15)



<a name="0.3.6"></a>
## [0.3.6](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.5...v0.3.6) (2017-02-09)



<a name="0.3.5"></a>
## [0.3.5](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.4...v0.3.5) (2017-01-26)



<a name="0.3.4"></a>
## [0.3.4](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.3...v0.3.4) (2017-01-24)



<a name="0.3.3"></a>
## [0.3.3](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.2...v0.3.3) (2017-01-24)


### Bug Fixes

* check for callbacks ([9ef5553](https://github.com/libp2p/js-libp2p-multiplex/commit/9ef5553))



<a name="0.3.2"></a>
## [0.3.2](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.1...v0.3.2) (2017-01-24)


### Bug Fixes

* dropped packed ([a7cfb8b](https://github.com/libp2p/js-libp2p-multiplex/commit/a7cfb8b))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.3.0...v0.3.1) (2017-01-20)


### Bug Fixes

* **docs:** Update readme.md's example and added files for it ([ccd94c8](https://github.com/libp2p/js-libp2p-multiplex/commit/ccd94c8))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.2.1...v0.3.0) (2017-01-20)



<a name="0.2.1"></a>
## [0.2.1](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.2.0...v0.2.1) (2016-03-22)



<a name="0.2.0"></a>
# [0.2.0](https://github.com/libp2p/js-libp2p-multiplex/compare/v0.1.0...v0.2.0) (2016-03-07)



<a name="0.1.0"></a>
# 0.1.0 (2016-03-07)
