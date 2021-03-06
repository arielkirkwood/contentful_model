# CHANGELOG

This Changelog has been introduced after the 0.1.7 release by @errorstudio.
Since then, @contentful has taken ownership. This changelog will start reflecting
changes from that point onwards.

## Master

### Added

* Added `::validate_with` and `::validate` methods for more complex validations
* Added `#hash` and `#eql?` to `ContentfulModel::Base` for equality and set operations [#65](https://github.com/contentful/contentful_model/issues/65)

### Fixed

* Setters and Getters now work for current locale instead of only default locale
* Management SDK now properly raises errors and works properly with localized content
* Queries now properly returns `::Contentful::Array` instead of `::Array` instances [#67](https://github.com/contentful/contentful_model/issues/67)

### Changed

* Updated to CDA SDK 2.x
* Updated Specs to run mostly against real data instead of mocks
* Validations are now run by default before `#save`

## 0.2.0

### Added
* Added CMA Integration
* Added Specs for all major components
* Added Content Model Migrations
* Added Locale Search [#27](https://github.com/contentful/contentful_model/issues/27)

### Fixed
* Fixed getter method resolution

## 0.1.7 (and previous)

* CDA Integration with Query Capabilities
* Preview API Integration
