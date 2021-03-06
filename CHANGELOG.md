# Rinvex Country Change Log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](CONTRIBUTING.md).


## [v4.0.1] - 2018-09-29
- Abandon the package in favor to rinvex/countries

## [v4.0.0] - 2018-09-22
- Simplify code by using PHP7 null coalescing operator
- Fix stupid gitattributes export-ignore issues
- Rename country variable to countryCode for naming consistency
- Remove file header docblock
- Push forward PHPUnit version
- Update composer config
- Fix deprecated PHPUnit TestCase namespace
- Disable travis email notifications
- Fix git export-ignore dotfiles
- Support the new StyleCI CSS/JS beta features
- Add PHPUnitPrettyResultPrinter
- Enforce consistency
- Require PHP 7.1.0 at least
- Tweak composer file
- Typehint method returns
- Fix wrong method return types
- Update minimum required PHP version
- Update composer packages
- Update travis php versions
- Add Laravel Auto Discovery support and validation rule
- Add missing Kosovo emoji
- Drop StyleCI multi-language support (paid feature now!)
- Prepare and tweak testing configuration
- Update PHPUnit options

## [v3.1.0] - 2017-03-07
- Format country code to small case before retrieval
- Change internal methods visibility to protected
- Update StyleCI fixers and other supplementary files
- Enforce strict type declaration
- Enforce consistency and rename Country Loader class
- Execute reflections once per test class
- Fix strict type declaration issues and tweak code
- Update Ukrainian phone prefixes and native name fix

## [v3.0.0] - 2016-12-12
- Drop PHP 5.6 support
- Drop leaking dependency
- Require PHP 7.0 as a minimum requirement
- Fix wrong CountryLoaderException namespace (close #43)
- Add test suites for Loader class & helper methods (close #42)
- Apply few tweaks and enhancements
- Fix wrong tests namespace
- Add missing test cases
- Arrange country files into specific data domains
- Update .styleci.yml and .gitignore config
- Refactor documentation for easy reading
- Enforce clean git export archive
- fixed ukrainian data
- Drop LTS support

## [v2.0.0] - 2016-11-27
- Rewrite from scratch, add massively extensive country data
  - Add emoji flags & their unicode attributes (close #6)
  - Add GeoJson data (close #20)
  - Add SVG flags (close #19)
  - Add separate country files (close #13)
  - Compress longlist for production usage
  - Add countries short list
  - Re-write form scratch for better & more intuitive API
  - Add country divisions (close #22)
  - Separate country translations into individual files (close #24)
  - Add unit testing suite
  - Add useful helpers
  - Drop illuminate dependencies
  - Refactor documentation

## v1.0.0 - 2016-08-20
- Tag first release.

[v4.0.1]: https://github.com/rinvex/country/compare/v4.0.0...v4.0.1
[v4.0.0]: https://github.com/rinvex/country/compare/v3.1.0...v4.0.0
[v3.1.0]: https://github.com/rinvex/country/compare/v3.0.0...v3.1.0
[v3.0.0]: https://github.com/rinvex/country/compare/v2.0.0...v3.0.0
[v2.0.0]: https://github.com/rinvex/country/compare/v1.0.0...v2.0.0
