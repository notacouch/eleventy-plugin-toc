# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 2024-03-26

### New

- Support for iOS VoiceOver
- New optional Skip to Content link

## [2.2.0] - 2022-08-15

### Changed

- Dependabot security fixes
- Upgrade dependencies

## [2.1.0] - 2021-07-09

### Changed

- Update package.json keywords
- Dependabot security fixes
- Upgrade dependencies

### Fixed

- Update package name in README

## [2.0.2] - 2020-11-30

### Fixed

- Fix `id` and `aria-labelledby` value mismatch by using the `wrapperClass`.

## [2.0.1] - 2020-09-22

### Changed

- Make the package scoped so it can be published to npm without naming issues.

## [2.0.0] - 2020-09-18

### Added

- Add CHANGELOG file.
- Add `toc.js` file from [Table of Contents (nesting) Eleventy Plugin](https://github.com/JordanShurmer/eleventy-plugin-toc).
- Add `role="navigation"` to the wrapper to define the landmark.
- Add `aria-label` attribute with `headingText` as the value when the wrapper is a `<nav>` element with no heading.
- Add `heading` option to provide a heading (`<h2>`) for the table of contents. Whose `id` attribute value matches the wrapper’s `aria-labelledby` (`headingText` value).
- Add `headingClass` option to style the heading.
- Add `headingLevel` option to set the appropriate heading level for your content.
- Add `headingText` option to provide text for the heading/label.
- Add `listType` option to choose an ordered (`<ol>`) or unordered (`<ul>`) list.
- Add `listClass` option to style the list.
- Add `listItemClass` option to style each list item.
- Add `listItemAnchorClass` option to style the anchor inside each list item.

### Changed

- Upgrade and pin dependency versions.
- Update Eleventy config file to use the new `toc.js` file.
- Use ESLint and Idiomatic JS rules.

### Fixed

- Fix ESLint issues with line endings on Windows.

### Removed

- Remove `src` folder and its JS files.
- Remove unnecessary dependencies and their config files.