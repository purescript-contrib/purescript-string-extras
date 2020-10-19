# Changelog

Notable changes to this project are documented in this file. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Breaking changes (😱!!!):

New features:

Bugfixes:

Other improvements:
  - upgrade to latest package set
  - switch to `Data.String.Regex.Unsafe.unsafeRegex` instade of reinventing it + remove related dependencies for reinventing

## [v2.2.1](https://github.com/purescript-contrib/purescript-strings-extra/releases/tag/v2.2.1) - 2020-10-02

* Update casing functions internal implementation of splitting unicode words according to the lodash reference and move regexes up to the top level ([#11](https://github.com/purescript-contrib/purescript-strings-extra/pull/11))

## [v2.2.0](https://github.com/purescript-contrib/purescript-strings-extra/releases/tag/v2.2.0) - 2020-09-13

* Expose `upperCaseFirst` function

## [v2.1.0](https://github.com/purescript-contrib/purescript-strings-extra/releases/tag/v2.1.0) - 2020-04-08

Add Levenshtein distance and Sorensen-Dice coefficient functions (@flip111)

## [v2.0.0](https://github.com/purescript-contrib/purescript-strings-extra/releases/tag/v2.0.0) - 2018-06-20

This release provides compatibility with PureScript 0.12 but does not change the public API.

- Update imports to 0.12 versions
- Replace `Data.String` imports with new `Data.String.CodeUnits` imports
- Remove effect rows from test suite

## [v1.0.0](https://github.com/purescript-contrib/purescript-strings-extra/releases/tag/v1.0.0) - 2017-10-02

- Initial release
