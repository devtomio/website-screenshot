# Changelog

## [2.0.0](https://github.com/devtomio/website-screenshot/compare/v1.2.0...v2.0.0) (2022-06-19)


### ⚠ BREAKING CHANGES

* remove cargo releases

### Features

* add ability to add additional chrome flags (closes [#36](https://github.com/devtomio/website-screenshot/issues/36)) ([c1dfb04](https://github.com/devtomio/website-screenshot/commit/c1dfb047fb93628213d3a8b5de8ee904a33c0308))
* add more errors ([bcb7e12](https://github.com/devtomio/website-screenshot/commit/bcb7e12587a395d069bbf99208f717f078aae7a8))
* add width/height to /screenshot POST request ([#38](https://github.com/devtomio/website-screenshot/issues/38)) ([886a21b](https://github.com/devtomio/website-screenshot/commit/886a21b4f01a54531787a8e599ec0ec3bbbf199e))


### Bug Fixes

* **deps:** update all non-major dependencies ([#35](https://github.com/devtomio/website-screenshot/issues/35)) ([4888f1d](https://github.com/devtomio/website-screenshot/commit/4888f1da326d9bab230917c4545a997b93b14bc0))
* **deps:** update rust crate anyhow to 1.0.58 ([#40](https://github.com/devtomio/website-screenshot/issues/40)) ([803069d](https://github.com/devtomio/website-screenshot/commit/803069daac68ac7933069b5215af871e90668b40))
* remove cargo releases ([308332e](https://github.com/devtomio/website-screenshot/commit/308332e9709b75d673b6ebce06bf1d29eaffc785))

## [1.2.0](https://github.com/devtomio/website-screenshot/compare/v1.1.0...v1.2.0) (2022-05-25)


### Features

* allow administrators to force nsfw checks or dark mode ([a6a9ca9](https://github.com/devtomio/website-screenshot/commit/a6a9ca99369adb2131e0002e58da582c10fb678b))
* let the user provide the chromedriver address ([24e82e2](https://github.com/devtomio/website-screenshot/commit/24e82e23253426e8f5a17df8331d3d2183859792))


### Bug Fixes

* **ci:** fix docker image ([c6d92a8](https://github.com/devtomio/website-screenshot/commit/c6d92a8832ded7782769a6ffb2dbbe9b2b76979e))
* **ci:** fix publishing to crates.io ([942c822](https://github.com/devtomio/website-screenshot/commit/942c822d62dbac68924583c8618e2b285ae794bd))

## [1.1.0](https://github.com/devtomio/website-screenshot/compare/v1.0.0...v1.1.0) (2022-05-25)


### Features

* add `Procfile` for heroku ([93d429a](https://github.com/devtomio/website-screenshot/commit/93d429ad1ff8475095f4280a57097aeef00c546e))
* add a self-hosted server on heroku ([ec45896](https://github.com/devtomio/website-screenshot/commit/ec4589644d779d27ffc7bf30cdb74c089164a39d))
* add docs route ([a87ff53](https://github.com/devtomio/website-screenshot/commit/a87ff53d351f343c8646ac223d282f2692f40f3e))
* add dprint checks ([7bb9e7c](https://github.com/devtomio/website-screenshot/commit/7bb9e7c2ab4e78c28f0dba1a7bca352662644d56))
* add more checks to prevent mismatch ([1a11545](https://github.com/devtomio/website-screenshot/commit/1a11545c02ac1d8d820321c0d5550d05f159694d))
* add nsfw checks ([bcc8360](https://github.com/devtomio/website-screenshot/commit/bcc83606756e226937beacc956ce4a309e1db5ab))
* **ci:** cache deps ([931844a](https://github.com/devtomio/website-screenshot/commit/931844a9bc7c05785bc99572147bce1118fffa3d))
* dark mode ([0ca4555](https://github.com/devtomio/website-screenshot/commit/0ca4555a5bc94c79e5a2af940f1dff7daf671a54))
* prevent bot detection ([39f982d](https://github.com/devtomio/website-screenshot/commit/39f982dd6fc3924df36276c5bc180740f7013530))
* remove use of `portpicker` ([b58415e](https://github.com/devtomio/website-screenshot/commit/b58415e8b6206172b2b0ab5afa99ee09050ab2ad))
* **tests:** add basic tests ([42ce400](https://github.com/devtomio/website-screenshot/commit/42ce40002665664a76676966c8d08921a9b3b1f8))
* use docker for heroku ([6a33b8b](https://github.com/devtomio/website-screenshot/commit/6a33b8bb70bf128af074bda676f1791537869dba))


### Bug Fixes

* add whitelisted ips option ([cc6d626](https://github.com/devtomio/website-screenshot/commit/cc6d626a8e1f0f7eb87639c0cb55feef19036763))
* **deps:** update rust crate once_cell to 1.12.0 ([#27](https://github.com/devtomio/website-screenshot/issues/27)) ([96e6333](https://github.com/devtomio/website-screenshot/commit/96e6333ed89de3a89e317899cf5ea3490ff5f2d5))
* **deps:** update rust crate rayon to 1.5.3 ([#24](https://github.com/devtomio/website-screenshot/issues/24)) ([787d4e4](https://github.com/devtomio/website-screenshot/commit/787d4e4c308b6c81bc51708616e9741ff6eef858))
* **deps:** update rust crate tokio to 1.18.2 ([#20](https://github.com/devtomio/website-screenshot/issues/20)) ([76d20ac](https://github.com/devtomio/website-screenshot/commit/76d20ac893eebea36628cd140225327e9cb49fbd))
* derive `Eq` for `Error` ([4efd1ab](https://github.com/devtomio/website-screenshot/commit/4efd1ab757bcdc4806b431ee9588a648159538ac))
* docker build ([0abd36e](https://github.com/devtomio/website-screenshot/commit/0abd36e92a6ff417ae711ad888599c1c8ffafc50))
* heroku build ([14a7b12](https://github.com/devtomio/website-screenshot/commit/14a7b1286b4f466d0a2503bac8a76c0dd6626bf0))
* hide scrollbar ([72c38e5](https://github.com/devtomio/website-screenshot/commit/72c38e5d099d2a470081d2a63a3d19778afb6774))
* remove heroku ([a5b20d8](https://github.com/devtomio/website-screenshot/commit/a5b20d8843034460711c8510bf2ad3831b9999a5))
* set remote debugging address ([410bb07](https://github.com/devtomio/website-screenshot/commit/410bb078ff7150d2ba704f78add1b9896b4639a2))
* shorten `chrome_opts` declaration ([ac8456f](https://github.com/devtomio/website-screenshot/commit/ac8456f9b10806a21a89eece8f041f4865d039ce))
* sleep the main thread because chromedriver may take a while ([8eb74f9](https://github.com/devtomio/website-screenshot/commit/8eb74f9a46a08a0e49d9013c206bbfc48ab40b2a))
* wrong arg ([12ba779](https://github.com/devtomio/website-screenshot/commit/12ba77987be21d4ceb32f20d7f10b4a7528c5325))

## [1.0.0](https://github.com/devtomio/website-screenshot/compare/v0.1.1...v1.0.0) (2022-05-04)


### ⚠ BREAKING CHANGES

* msrv is now nightly 1.62

### Features

* add auth ([39514ad](https://github.com/devtomio/website-screenshot/commit/39514add03c1aca0f7d7d1ed3216288364b21e2c))
* add support for selfhosted s3 storage (closes [#9](https://github.com/devtomio/website-screenshot/issues/9)) ([da2c085](https://github.com/devtomio/website-screenshot/commit/da2c085340bc315ca32c30786c7a4d860461c8f8))
* fullscreen screenshots ([22283d2](https://github.com/devtomio/website-screenshot/commit/22283d2a4ebfaa608c39912c3de37ac956e1ad08))


### Bug Fixes

* **deps:** update all non-major dependencies ([#12](https://github.com/devtomio/website-screenshot/issues/12)) ([556fa91](https://github.com/devtomio/website-screenshot/commit/556fa9182761a357d1a10d2d948cef3c25d27c3a))
* **deps:** update all non-major dependencies ([#14](https://github.com/devtomio/website-screenshot/issues/14)) ([120f706](https://github.com/devtomio/website-screenshot/commit/120f7062736ae858b4c69263f72cfcf65aca5008))

### [0.1.1](https://github.com/devtomio/website-screenshot/compare/v0.1.0...v0.1.1) (2022-04-26)


### Bug Fixes

* also change install script ([fac46af](https://github.com/devtomio/website-screenshot/commit/fac46aff7ebfa7ac52cc8218368fc3adc7d43697))
* remove `aarch64-pc-windows-msvc` ([a42c391](https://github.com/devtomio/website-screenshot/commit/a42c3914d09953011ddd1e59e67d816eb33d82e0))

## 0.1.0 (2022-04-25)


### Features

* configure labels ([babcfdb](https://github.com/devtomio/website-screenshot/commit/babcfdb3e122cb8c7aa6b242e1510d1d894ffd28))
* first stable release ([f5b1d0f](https://github.com/devtomio/website-screenshot/commit/f5b1d0f588762ced743332a717cd55bc11cd341f))
* mvp ([866d6f4](https://github.com/devtomio/website-screenshot/commit/866d6f4cf6eb4582d50266277dfa3843924ef8d6))


### Bug Fixes

* ci ([92d137e](https://github.com/devtomio/website-screenshot/commit/92d137e62c830088677535cd4b86625d80707cba))
* **docker:** copy the build script ([4c1eb58](https://github.com/devtomio/website-screenshot/commit/4c1eb58194ad436c50c403c568c81468c05ffbd7))
* remove cargo config ([7a40b61](https://github.com/devtomio/website-screenshot/commit/7a40b613d52c964a9c8e4751a2384e61028b2155))
