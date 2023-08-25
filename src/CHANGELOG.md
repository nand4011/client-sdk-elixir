# Changelog

## [0.7.1](https://github.com/nand4011/client-sdk-elixir/compare/v0.7.0...v0.7.1) (2023-08-25)


### Miscellaneous

* release-please 2 ([b272777](https://github.com/nand4011/client-sdk-elixir/commit/b272777589f3fdbf9fed9d815dbb23313d8c98bb))

## [0.7.0](https://github.com/nand4011/client-sdk-elixir/compare/v0.6.2...v0.7.0) (2023-08-21)


### Features

* add control plane operations (create, list, delete cache) ([9bfc358](https://github.com/nand4011/client-sdk-elixir/commit/9bfc3580d02136d9ed34eaa3fcd296597de01182))
* Add credential parsing from string and env var ([50f5dec](https://github.com/nand4011/client-sdk-elixir/commit/50f5dec7359d99ba15e31cf130b2b66916daaf29))
* Add delete method ([2a1b826](https://github.com/nand4011/client-sdk-elixir/commit/2a1b8261816328ded777b9cedd1148ab6c0cc173))
* Add doc code snippets and readme generation ([#43](https://github.com/nand4011/client-sdk-elixir/issues/43)) ([f987077](https://github.com/nand4011/client-sdk-elixir/commit/f9870774c53ca618842e202aaf831fd2a692733d))
* Add get and set methods ([4a0875c](https://github.com/nand4011/client-sdk-elixir/commit/4a0875ce684b272392bdc12736b5f85d812d6fb7))
* Add initial grpc call example ([16e733f](https://github.com/nand4011/client-sdk-elixir/commit/16e733fe64eb632ad64ed5b1cc85c372b51090ca))
* Add pre-built configurations ([17ae286](https://github.com/nand4011/client-sdk-elixir/commit/17ae286a11a0028e5af9ff5a16b6b2c8dbd6ad4e))
* add sorted set fetch by score and remove functions ([#37](https://github.com/nand4011/client-sdk-elixir/issues/37)) ([3bdb666](https://github.com/nand4011/client-sdk-elixir/commit/3bdb6664feedf7cdbe4972bbb418db217cde63ad))
* add sorted set get score, get rank, and increment score ([#38](https://github.com/nand4011/client-sdk-elixir/issues/38)) ([c2624f2](https://github.com/nand4011/client-sdk-elixir/commit/c2624f26edff279cb26c5de80225c7c9719a0d56))
* add sorted set put and fetch by rank functions ([#36](https://github.com/nand4011/client-sdk-elixir/issues/36)) ([9f27b46](https://github.com/nand4011/client-sdk-elixir/commit/9f27b46edc766482b0fbc81620a3663e967acce4))
* loadgen example code ([dc6fe46](https://github.com/nand4011/client-sdk-elixir/commit/dc6fe467c293b0e31800cedf0f735a2e2113c1bb))
* Make the project publishable on Hex ([5f6fe36](https://github.com/nand4011/client-sdk-elixir/commit/5f6fe36b356a001698b1a046db42229df43b76c1))
* sketch of possible API ([31713a4](https://github.com/nand4011/client-sdk-elixir/commit/31713a43ea03355d7dbdb88f7b1aa19829912a0b))
* standardize the response types ([#32](https://github.com/nand4011/client-sdk-elixir/issues/32)) ([2b92ca5](https://github.com/nand4011/client-sdk-elixir/commit/2b92ca53d417d7cca3e3f33675be9a548c217d68))
* support numbers for ttls/scores ([18facba](https://github.com/nand4011/client-sdk-elixir/commit/18facba9b8ce8e57f7a98efc8cee4c2099d00b2b))
* use keyword list for cache client factory function ([ba334a2](https://github.com/nand4011/client-sdk-elixir/commit/ba334a227ae01d198f622f4628136a10c417c74b))


### Bug Fixes

* cache client functions should require cache client arg ([1080113](https://github.com/nand4011/client-sdk-elixir/commit/1080113bf6b2fa26329772855a24a09493f4f1c6))
* dialyzer errors due to opaque types ([a95a868](https://github.com/nand4011/client-sdk-elixir/commit/a95a868e94f61919805ab82bb08073dea83c1161))
* linting ([102e424](https://github.com/nand4011/client-sdk-elixir/commit/102e42429d6497b5ce8d92bf662702c94c8dbaa1))
* linting ([e649c48](https://github.com/nand4011/client-sdk-elixir/commit/e649c481c9dbef5e10da3e9b0d512e52ea186cfe))
* placeholder integration test ([6fb5668](https://github.com/nand4011/client-sdk-elixir/commit/6fb5668ff30f1bc407c1f45c7c1d9e8a25c631d4))


### Miscellaneous

* add docs generation ([#28](https://github.com/nand4011/client-sdk-elixir/issues/28)) ([9f48453](https://github.com/nand4011/client-sdk-elixir/commit/9f48453e1efd2bc27acfec3fdd0980f8b5af6dd4))
* Add docstrings to CacheClient ([#59](https://github.com/nand4011/client-sdk-elixir/issues/59)) ([8118e7a](https://github.com/nand4011/client-sdk-elixir/commit/8118e7a6316bb561cd2b6de978cda7ba019b5827))
* change how the release job updates the version ([#31](https://github.com/nand4011/client-sdk-elixir/issues/31)) ([3b2804b](https://github.com/nand4011/client-sdk-elixir/commit/3b2804b446fee4558e1cd2d039dd2402d77c0115))
* change project name ([#29](https://github.com/nand4011/client-sdk-elixir/issues/29)) ([ca27faf](https://github.com/nand4011/client-sdk-elixir/commit/ca27faf62b2606c0b93de2f526c019106fb3e64c))
* empty commit to test release plugin ([#70](https://github.com/nand4011/client-sdk-elixir/issues/70)) ([82c2406](https://github.com/nand4011/client-sdk-elixir/commit/82c24062ffb2bd4e63da6c05e24f677ea4750a6b))
* fix linting ([abfcf8e](https://github.com/nand4011/client-sdk-elixir/commit/abfcf8e35534e9658e23ea89c616ea14fe0b80a6))
* fix linting ([98f106a](https://github.com/nand4011/client-sdk-elixir/commit/98f106ac73cf90179a4d340071cd038bc5dbeead))
* grpc configuration ([#35](https://github.com/nand4011/client-sdk-elixir/issues/35)) ([b6d3416](https://github.com/nand4011/client-sdk-elixir/commit/b6d3416647e97177458c0c52cf4faf72926ac70c))
* illustrate logging ([83cdfe0](https://github.com/nand4011/client-sdk-elixir/commit/83cdfe027a6c5eef00cbebd852e2721fc6e73c6a))
* initial files for project skeleton ([7d947d3](https://github.com/nand4011/client-sdk-elixir/commit/7d947d3334a708926544966dacdde2de0e76a3ef))
* **main:** release 0.6.0 ([#65](https://github.com/nand4011/client-sdk-elixir/issues/65)) ([72cc79f](https://github.com/nand4011/client-sdk-elixir/commit/72cc79f6f103b5c64c52240073adc6be8d49672d))
* **main:** release 0.6.1 ([#68](https://github.com/nand4011/client-sdk-elixir/issues/68)) ([e2eed61](https://github.com/nand4011/client-sdk-elixir/commit/e2eed618125c39df556dcaa43791d711b5f815ad))
* **main:** release 0.6.2 ([#71](https://github.com/nand4011/client-sdk-elixir/issues/71)) ([83743fc](https://github.com/nand4011/client-sdk-elixir/commit/83743fc6dce134782259586ea1a45ac26c801f4c))
* Make error handling and validation consistent ([#60](https://github.com/nand4011/client-sdk-elixir/issues/60)) ([06f6112](https://github.com/nand4011/client-sdk-elixir/commit/06f6112de4225542570c95d85b88a557b7359182))
* make set ttl optional and misc fixes ([#42](https://github.com/nand4011/client-sdk-elixir/issues/42)) ([a3ce72f](https://github.com/nand4011/client-sdk-elixir/commit/a3ce72ff2a82884f4eb000b6664d9dbd80f796f7))
* redact auth token and response value changes ([#39](https://github.com/nand4011/client-sdk-elixir/issues/39)) ([a652f2d](https://github.com/nand4011/client-sdk-elixir/commit/a652f2d53ea27006ad8c807e774cd132fef6f873))
* refactor so that Task async/await is handled outside of the API ([33bb7b8](https://github.com/nand4011/client-sdk-elixir/commit/33bb7b8478020aa03321b69e001f2728df185710))
* release-please 1 ([d74b698](https://github.com/nand4011/client-sdk-elixir/commit/d74b698a924d4bd5a034d8d99175490d6dea8707))
* revert back to not using keyword args for create ([2a3e2f7](https://github.com/nand4011/client-sdk-elixir/commit/2a3e2f73af4e75b6d7709d863038c5d861145ecb))
* Switch to release-please for releases ([#64](https://github.com/nand4011/client-sdk-elixir/issues/64)) ([062a95c](https://github.com/nand4011/client-sdk-elixir/commit/062a95c1edf88d77a852d3fa839d8a98794302ed))
* update the hex API key secret name ([#26](https://github.com/nand4011/client-sdk-elixir/issues/26)) ([6345994](https://github.com/nand4011/client-sdk-elixir/commit/634599411b151dd8d2d8db29ca0ee1f02d07d79c))

## [0.6.2](https://github.com/momentohq/client-sdk-elixir/compare/v0.6.1...v0.6.2) (2023-08-04)


### Miscellaneous

* empty commit to test release plugin ([#70](https://github.com/momentohq/client-sdk-elixir/issues/70)) ([82c2406](https://github.com/momentohq/client-sdk-elixir/commit/82c24062ffb2bd4e63da6c05e24f677ea4750a6b))

## [0.6.1](https://github.com/momentohq/client-sdk-elixir/compare/v0.6.0...v0.6.1) (2023-08-04)


### Miscellaneous

* Make error handling and validation consistent ([#60](https://github.com/momentohq/client-sdk-elixir/issues/60)) ([06f6112](https://github.com/momentohq/client-sdk-elixir/commit/06f6112de4225542570c95d85b88a557b7359182))

## [0.6.0](https://github.com/momentohq/client-sdk-elixir/compare/v0.5.0...v0.6.0) (2023-08-04)


### Features

* loadgen example code ([dc6fe46](https://github.com/momentohq/client-sdk-elixir/commit/dc6fe467c293b0e31800cedf0f735a2e2113c1bb))


### Miscellaneous

* Add docstrings to CacheClient ([#59](https://github.com/momentohq/client-sdk-elixir/issues/59)) ([8118e7a](https://github.com/momentohq/client-sdk-elixir/commit/8118e7a6316bb561cd2b6de978cda7ba019b5827))
* Switch to release-please for releases ([#64](https://github.com/momentohq/client-sdk-elixir/issues/64)) ([062a95c](https://github.com/momentohq/client-sdk-elixir/commit/062a95c1edf88d77a852d3fa839d8a98794302ed))
