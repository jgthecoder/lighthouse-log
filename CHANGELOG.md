## [2.0.1](https://github.com/jgthecoder/lighthouse-log/compare/v2.0.0...v2.0.1) (2026-08-03)


### Bug Fixes

* move commit log back to root directory ([754a8d9](https://github.com/jgthecoder/lighthouse-log/commit/754a8d996e45a3179a0231d0de520c073940cc2c))

# [2.0.0](https://github.com/jgthecoder/lighthouse-log/compare/v1.0.1...v2.0.0) (2026-08-03)


* feat!: restructure lighthouse entries to strict key-value format ([1379f04](https://github.com/jgthecoder/lighthouse-log/commit/1379f0428e041acac2dff2bf2df684f4eebec2bf))
* feat!: split lighthouse catalog into per-region directories ([3242643](https://github.com/jgthecoder/lighthouse-log/commit/3242643673fe0c57c8747cc4b8e290f1a4019f12))


### Bug Fixes

* correct construction year detail for Eddystone Lighthouse ([348765c](https://github.com/jgthecoder/lighthouse-log/commit/348765c6a3e3bc8dcc1f1730f933a90df5a9675e))
* correct height_m value for Peggy's Cove lighthouse ([28b6866](https://github.com/jgthecoder/lighthouse-log/commit/28b68669ca24a2f0fa477aa9f9e77bf76627f652))
* separate rebuild history from built date for Tourlitis lighthouse ([ee8c1c9](https://github.com/jgthecoder/lighthouse-log/commit/ee8c1c9f7add30a6737577e9fd2fbe0afb2674b3))


### Features

* add automated status field to all entries ([5b846ef](https://github.com/jgthecoder/lighthouse-log/commit/5b846ef12cc86b16e239366c21752ecc10791cd6))
* add coordinates field to all lighthouse entries ([5ebc6b0](https://github.com/jgthecoder/lighthouse-log/commit/5ebc6b066ced146b4a3bdd74a3861e4ddf53b623))
* add Kjeungskjaer lighthouse entry ([7882957](https://github.com/jgthecoder/lighthouse-log/commit/788295788b5ca153dfd6c6bf1a0edcd2b27e0025))
* add lens_type field to all lighthouse entries ([8503759](https://github.com/jgthecoder/lighthouse-log/commit/8503759b0d9e08034ecfef2160ad28167c9291c9))
* add Peggy's Cove lighthouse entry ([ed0de48](https://github.com/jgthecoder/lighthouse-log/commit/ed0de48145798fb1d5a91b2e7379834b90394990))
* add Tourlitis lighthouse entry ([74c65f6](https://github.com/jgthecoder/lighthouse-log/commit/74c65f6adf852d9682e2975582800411ec54e70e))


### BREAKING CHANGES

* file paths for every entry have changed. Any script or tool referencing lighthouses/<name>.txt directly must be updated to lighthouses/<region>/<name>.txt.
* field names and casing changed (e.g. 'Height: 63 meters' -> 'height_m: 63'). Any tooling parsing the old 'Label: value' prose format will break.

## [1.0.1](https://github.com/jgthecoder/lighthouse-log/compare/v1.0.0...v1.0.1) (2026-08-03)


### Bug Fixes

* correct height measurement for Cape Hatteras lighthouse ([0e96946](https://github.com/jgthecoder/lighthouse-log/commit/0e96946145e1fb2e6d58641deee5995ff64985c3))

# 1.0.0 (2026-08-03)


### Features

* initialize lighthouse log with first three entires ([44b2812](https://github.com/jgthecoder/lighthouse-log/commit/44b281220f84aec1e69c11dc3e676daff2eba0e3))
