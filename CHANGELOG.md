# Changelog

All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0] - 2019-08-19

### Changed
- Deprecate the `parent_id` and `parent_type` variables in favor of a single `parent` variable [#8]
- Change outputs to follow the same conventions used in the `cloud-storage` and `service-accounts` modules ([migration instructions](docs/upgrading_to_folders_v2.0.md)) [#9]
  - Rename map outputs dropping the `names_and_` prefix
  - Add resource outputs
  - Add single use outputs
  - Add list-style outputs

## [1.0.0] - 2019-07-26

### Changed

- Upgraded for usage with terraform-0.12.x [#3]

## [0.1.0] - 2019-05-28

### Added

- Initial release

[Unreleased]: https://github.com/terraform-google-modules/terraform-google-folders/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/terraform-google-modules/terraform-google-folders/compare/v0.1.0...v1.0.0
[0.1.0]: https://github.com/terraform-google-modules/terraform-google-folders/releases/tag/v0.1.0
[#3]: https://github.com/terraform-google-modules/terraform-google-folders/pull/3
