# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Unreleased

## [v0.14.1] - 2022-07-23

- Fix uppercased names of arrays

## [v0.14.0] - 2022-07-19

- Bump MSRV to 1.56.0 (2021)
- Add advanced encoder options `Config`
- BREAKING: `Encode` trait needs to implement `encode_with_config`

## [v0.13.1] - 2022-02-12

- Encode "dimIndex" ranges

## [v0.13.0] - 2022-01-04

- Bump `svd-rs`

## [v0.12.0] - 2021-11-11

- Bump `svd-rs`
- Add `protection` encoding
- Add `readAction` encoding
- Add array support for peripherals

## [v0.11.0] - 2021-10-02
- Splitted from `svd-parser`

Previous versions in common [changelog](../CHANGELOG.md).

[Unreleased]: https://github.com/rust-embedded/svd/compare/svd-encoder-v0.14.1...HEAD
[v0.14.1]: https://github.com/rust-embedded/svd/compare/v0.14.0..svd-encoder-v0.14.1
[v0.14.0]: https://github.com/rust-embedded/svd/compare/svd-rs-v0.13.1..v0.14.0
[v0.13.1]: https://github.com/rust-embedded/svd/compare/svd-parser-v0.13.1...svd-rs-v0.13.1
[v0.13.0]: https://github.com/rust-embedded/svd/compare/v0.12.0...v0.13.0
[v0.12.0]: https://github.com/rust-embedded/svd/compare/v0.11.0...v0.12.0
[v0.11.0]: https://github.com/rust-embedded/svd/compare/v0.10.2...v0.11.0
