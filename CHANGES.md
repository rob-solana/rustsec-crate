## [0.9.0] (2018-07-26)

[0.9.0]: https://github.com/RustSec/rustsec-crate/compare/v0.8.0...v0.9.0

* [#39](https://github.com/RustSec/rustsec-crate/pull/39)
  Use "platforms" crate for platform-related functionality.

## [0.8.0] (2018-07-24)

[0.8.0]: https://github.com/RustSec/rustsec-crate/compare/v0.7.5...v0.8.0

* [#38](https://github.com/RustSec/rustsec-crate/pull/38)
  Advisory platform requirements.

* [#37](https://github.com/RustSec/rustsec-crate/pull/37)
  Cargo-like keyword support.

## [0.7.5] (2018-07-24)

[0.7.5]: https://github.com/RustSec/rustsec-crate/compare/v0.7.4...v0.7.5

* [#36](https://github.com/RustSec/rustsec-crate/pull/36)
  Allow AdvisoryId::new() to parse "RUSTSEC-0000-0000".

## [0.7.4] (2018-07-23)

[0.7.4]: https://github.com/RustSec/rustsec-crate/compare/v0.7.3...v0.7.4

* [#35](https://github.com/RustSec/rustsec-crate/pull/35)
  Add link to logo image for docs.rs.

## [0.7.3] (2018-07-23)

[0.7.3]: https://github.com/RustSec/rustsec-crate/compare/v0.7.2...v0.7.3

* [#34](https://github.com/RustSec/rustsec-crate/pull/34)
  Fix builds with --no-default-features.

## [0.7.2] (2018-07-23)

[0.7.2]: https://github.com/RustSec/rustsec-crate/compare/v0.7.1...v0.7.2

* [#32](https://github.com/RustSec/rustsec-crate/pull/32)
  README.md: Badge fixups, add gitter badge.

## [0.7.1] (2018-07-23)

[0.7.1]: https://github.com/RustSec/rustsec-crate/compare/v0.7.0...v0.7.1

* [#31](https://github.com/RustSec/rustsec-crate/pull/31)
  Cargo.toml: Formatting fixups, add "readme" attribute.

## [0.7.0] (2018-07-22)

[0.7.0]: https://github.com/RustSec/rustsec-crate/compare/v0.6.0...v0.7.0

* [#29](https://github.com/RustSec/rustsec-crate/pull/29)
  Validate dates are well-formed.

* [#28](https://github.com/RustSec/rustsec-crate/pull/28)
  Add AdvisoryIdKind and limited support for parsing advisory IDs.

* [#27](https://github.com/RustSec/rustsec-crate/pull/27)
  Add a "Vulnerabilities" collection struct.

* [#23](https://github.com/RustSec/rustsec-crate/pull/23)
  Parse aliases, references, and unaffected versions.

* [#22](https://github.com/RustSec/rustsec-crate/pull/22)
  Parse (but do not yet verify) signatures on advisory-db commits.

* [#21](https://github.com/RustSec/rustsec-crate/pull/21)
  Parse individual advisory .toml files rather than Advisories.toml.

* [#20](https://github.com/RustSec/rustsec-crate/pull/20)
  Switch to git2-based fetcher for advisory-db.

* [#18](https://github.com/RustSec/rustsec-crate/pull/18)
  Use serde to parse advisories TOML and Cargo.lock files.

* [#17](https://github.com/RustSec/rustsec-crate/pull/17)
  Use 'failure' crate for error handling.

## 0.6.0 (2017-03-05)

* [#11](https://github.com/RustSec/rustsec-crate/pull/11)
  Use semver::Version for lockfile::Package versions.
  ([@tarcieri])

* [#10](https://github.com/RustSec/rustsec-crate/pull/10)
  Move AdvisoryDatabase under the ::db module.
  ([@tarcieri])
 
* [#9](https://github.com/RustSec/rustsec-crate/pull/9)
  Lockfile support.
  ([@tarcieri])

## 0.5.2 (2017-02-26)

* [#8](https://github.com/RustSec/rustsec-crate/pull/8)
  Add `AdvisoryDatabase::fetch_from_url()`.
  ([@tarcieri])

## 0.5.1 (2017-02-26)

* [#7](https://github.com/RustSec/rustsec-crate/pull/7)
  Make `advisory` and `error` modules public.
  ([@tarcieri])

## 0.5.0 (2017-02-26)

* [#6](https://github.com/RustSec/rustsec-crate/pull/6)
  Use str version param for `AdvisoryDatabase::find_vulns_for_crate()`.
  ([@tarcieri])

## 0.4.0 (2017-02-26)

* [#5](https://github.com/RustSec/rustsec-crate/pull/5)
  Add `AdvisoryDatabase::find_vulns_for_crate()`.
  ([@tarcieri])

## 0.3.0 (2017-02-26)

* [#4](https://github.com/RustSec/rustsec-crate/pull/4)
  Rename `crate_name` TOML attribute back to `package`.
  ([@tarcieri])

## 0.2.0 (2017-02-25)

* [#3](https://github.com/RustSec/rustsec-crate/pull/3)
  Rename `package` TOML attribute to `crate_name`.
  ([@tarcieri])

* [#2](https://github.com/RustSec/rustsec-crate/pull/2)
  Add iterator support to AdvisoryDatabase.
  ([@tarcieri])

## 0.1.0 (2017-02-25)

* Initial release

[@tarcieri]: https://github.com/tarcieri
