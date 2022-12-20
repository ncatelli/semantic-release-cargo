# [2.0.0](https://github.com/semantic-release-cargo/semantic-release-cargo/compare/v1.0.2...v2.0.0) (2022-12-19)


### Bug Fixes

* avoid segfault in args parsing ([4c42566](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/4c425665a8aada8d0a4053ad755f87db49d38100))
* publish semantic-release-cargo to crates.io with semantic-release ([d89213b](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/d89213b1adb9661764d2a29fa49b06bdceb9801f))
* re-enable prepare lifecycle hook ([95dd885](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/95dd88576bc8bf6b1a2c9c0bab7bf0f0ba100307))
* remove CI artifacts from cargo package list ([764e04a](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/764e04a0a73994ba4b06023886e98c96edeca43b))
* remove prepare lifecycle hook ([f1bda08](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/f1bda08cba102adf4d5536eaa9b59210441ae542))
* upload compiled CLI to GitHub Release artifacts ([34b692a](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/34b692a32e1ffe9de53497f9300264a1fa974f21))
* use x86_64-unknown-linux-gnu target ([1517c0a](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/1517c0ac4f7599f69616ac35b7fb340ba3f28bb0))


* feat!: wrap rust code in npm package ([cedc828](https://github.com/semantic-release-cargo/semantic-release-cargo/commit/cedc828fbe8f2e889febbe02e248de11e7a459e9))


### BREAKING CHANGES

* Use napi-rs to call the Rust library from Node.js.

This deletes the Rust binary. Moving forward, **semantic-release-cargo**
should be installed by npm.

# [2.0.0-beta.7](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.6...v2.0.0-beta.7) (2022-12-18)


### Bug Fixes

* avoid segfault in args parsing ([4c42566](https://github.com/semantic-release-rust/semantic-release-rust/commit/4c425665a8aada8d0a4053ad755f87db49d38100))
* remove CI artifacts from cargo package list ([764e04a](https://github.com/semantic-release-rust/semantic-release-rust/commit/764e04a0a73994ba4b06023886e98c96edeca43b))

# [2.0.0-beta.7](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.6...v2.0.0-beta.7) (2022-12-18)


### Bug Fixes

* avoid segfault in args parsing ([4c42566](https://github.com/semantic-release-rust/semantic-release-rust/commit/4c425665a8aada8d0a4053ad755f87db49d38100))

# [2.0.0-beta.6](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.5...v2.0.0-beta.6) (2022-12-18)


### Bug Fixes

* publish semantic-release-cargo to crates.io with semantic-release ([d89213b](https://github.com/semantic-release-rust/semantic-release-rust/commit/d89213b1adb9661764d2a29fa49b06bdceb9801f))

# [2.0.0-beta.5](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.4...v2.0.0-beta.5) (2022-12-18)


### Bug Fixes

* upload compiled CLI to GitHub Release artifacts ([34b692a](https://github.com/semantic-release-rust/semantic-release-rust/commit/34b692a32e1ffe9de53497f9300264a1fa974f21))

# [2.0.0-beta.4](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.3...v2.0.0-beta.4) (2022-12-18)


### Bug Fixes

* re-enable prepare lifecycle hook ([95dd885](https://github.com/semantic-release-rust/semantic-release-rust/commit/95dd88576bc8bf6b1a2c9c0bab7bf0f0ba100307))

# [2.0.0-beta.3](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2022-12-18)


### Bug Fixes

* use x86_64-unknown-linux-gnu target ([1517c0a](https://github.com/semantic-release-rust/semantic-release-rust/commit/1517c0ac4f7599f69616ac35b7fb340ba3f28bb0))

# [2.0.0-beta.2](https://github.com/semantic-release-rust/semantic-release-rust/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2022-12-18)


### Bug Fixes

* remove prepare lifecycle hook ([f1bda08](https://github.com/semantic-release-rust/semantic-release-rust/commit/f1bda08cba102adf4d5536eaa9b59210441ae542))

# [2.0.0-beta.1](https://github.com/semantic-release-rust/semantic-release-rust/compare/v1.0.2...v2.0.0-beta.1) (2022-12-18)


* feat!: wrap rust code in npm package ([cedc828](https://github.com/semantic-release-rust/semantic-release-rust/commit/cedc828fbe8f2e889febbe02e248de11e7a459e9))


### BREAKING CHANGES

* Use napi-rs to call the Rust library from Node.js.

This deletes the Rust binary. Moving forward, **semantic-release-cargo**
should be installed by npm.