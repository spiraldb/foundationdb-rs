# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.9.1] - 2024-10-08

### <!-- 3 -->🆙 Bump

- Bump MSRV to 1.71.1
- Bump all dependencies and setup dependabot

### <!-- 4 -->⚙️ Other changes

- Generate CHANGELOG per crate

[0.9.1]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/0.9.0..0.9.1

## [0.9.0] - 2024-03-15

### <!-- 0 -->🚀 added

- Add support for 7.3
- Bump fdb crate to 0.9.0 and sim to 0.2.0

### <!-- 3 -->🆙 Bump

- Bump msrv
- Bump dependencies
- Bump dep

### <!-- 4 -->⚙️ Other changes

- Chore: link against libc

## [0.8.0] - 2023-06-07

### <!-- 3 -->🆙 Bump

- Chore: bump rust to 1.57
- Bump msrv
- Bump deps
- Bump msrv for bindgen and env_logger
- Bump dependencies

### <!-- 4 -->⚙️ Other changes

- Initial support for Nix
- Build on docs.rs with the required features
- Prepare release

## [0.7.0] - 2022-07-11

### <!-- 0 -->🚀 added

- Add support for api 630
- Bump crate version, maintainers and documentation
- Bump rust edition to 2021
- Add support for api 700
- Implement Iterator for FdbKeys
- Initial commit to support fdb 7.1

### <!-- 1 -->🐛 Bug Fixes

- Fix: nighly build by removing layout tests

### <!-- 2 -->🚜 Refactor

- Remove clikengo link in Cargo.toml

### <!-- 3 -->🆙 Bump

- Bump version to 5.0.1
- Bump deps

### <!-- 4 -->⚙️ Other changes

- Removing reference to master branch
- Prepare for 0.7.0

## [0.5.0] - 2020-09-17

### <!-- 1 -->🐛 Bug Fixes

- Cargo.toml fix docs.rs features
- Cargo.toml fix badges links
- Fix Cargo.toml repository links
- Fix #170: protect boot from undefined behavior
- Cargo clippy fixes
- Fix code coverage ci

### <!-- 3 -->🆙 Bump

- Bump version to 0.4.1

### <!-- 4 -->⚙️ Other changes

- Core: auto-generate all code at build time
- Move CI to FoundationDB 5.2.5
- Foundationdb 5.2.5 -> 6.0.15
- Update bindgen requirement from 0.36 to 0.43
- Upgrade rand from 0.4 to 0.6 (#104)
- Cleanup the fdb version features from primary crate (#99)
- Update bindgen requirement from 0.43 to 0.44
- Update bindgen requirement from 0.44 to 0.46
- Update bindgen requirement from 0.46 to 0.47
- Rust edition 2018
- Async/await: complete rewrite of foundationdb
- Update bindgen to latest version
- Foundationdb-sys version is now 0.4.0
- Update bindgen requirement from 0.47 to 0.48
- Update bindgen requirement from 0.48 to 0.49
- Update bindgen requirement from 0.49 to 0.50
- Update bindgen requirement from 0.50 to 0.51
- Update Cargo.toml authors
- Update bindgen requirement from 0.51.1 to 0.52.0
- Embed 6.2.10 fdb_c.h and fdb.options
- Embed all supported version includes
- Default to locally available foundationdb include
- Move include inside crate folders
- Foundationdb-gen/sys README
- Cargo.toml badges & docs.rs metadata
- Update bindgen requirement from 0.52.0 to 0.53.2
- Update fdb 620 includes to 6.2.20
- Update fdb 610 includes to 6.1.13
- Default to foundation 620 api
- Update bindgen to 0.55.1

## [0.3.0] - 2018-11-16

### <!-- 0 -->🚀 added

- Add some READMEs
- Add metadata
- Add docs link to Cargo.toml

### <!-- 1 -->🐛 Bug Fixes

- Fix some urls

### <!-- 3 -->🆙 Bump

- Bump versions

### <!-- 4 -->⚙️ Other changes

- Initial library create for foundationdb rust bindings
- Initial binding generation working
- Linux and macos in std header paths
- Update readme and cargo.toml
- Track bindings.rs in Git
- Update bindings from linux bindgen
- Prepare patch release of sys 0.1.1
- Win64 support
- Prepare 0.3 release

[unreleased]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/v0.9.0..HEAD
[0.9.0]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/v0.8.0..v0.9.0
[0.8.0]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/v0.7.0..v0.8.0
[0.7.0]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/0.5.0..v0.7.0
[0.5.0]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/v0.3.0..0.5.0
[0.3.0]: https://github.com/foundationdb-rs}/foundationdb-rs/compare/0.2..v0.3.0

<!-- generated by git-cliff -->
