# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

> [!NOTE]
> The [previous `CHANGELOG.md`](https://github.com/singerdmx/flutter-quill/blob/master/doc/OLD_CHANGELOG.md) has been archived.

## [Unreleased]

> [!IMPORTANT]
> See the [migration guide from 10.0.0 to 11.0.0](https://github.com/singerdmx/flutter-quill/blob/master/doc/migration/10_to_11.md) for the full breaking changes and migration. Ensure to read the [breaking behavior](https://github.com/singerdmx/flutter-quill/blob/master/doc/migration/10_to_11.md#-breaking-behavior) section to avoid unexpected changes.

### Changed

- Update the minimum supported SDK version to **Flutter 3.0/Dart 3.0** for compatibility, fixing [#2347](https://github.com/singerdmx/flutter-quill/issues/2347).
- Improve dependencies constraints for compatibility.
- **BREAKING**: Update configuration class names to use the suffix `Config` instead of `Configurations`.
- The `QuillSimpleToolbar` base button options now support buttons of `flutter_quill_extensions`.

### Removed

- **BREAKING**: The [`super_clipboard`](https://pub.dev/packages/super_clipboard) plugin from [flutter_quill_extensions](https://pub.dev/packages/flutter_quill_extensions).
- **BREAKING**: The deprecated support for loading YouTube videos in `flutter_quill_extensions`.

### Added

- `Insert video` string in `quill_en.arb` to support localization. Currently available **only in English**.

## [11.0.0-dev.3] - 2024-11-08

### Changed

- Updates minimum supported [`flutter_quill`](https://pub.dev/packages/flutter_quill) version to `11.0.0-dev.3`.

## [11.0.0-dev.2] - 2024-11-08

### Changed

- Separate the package version and `CHANGELOG.md` from [flutter_quill](https://pub.dev/packages/flutter_quill).
