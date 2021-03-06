# Changelog

## v0.2.3 beta

- Updated `jest` to resolve potential security issue
  - Affects dev only

## v0.2.2 beta

- Updated dev packages
  - Skipped updating `jest-fetch-mock` due to its newest update breaking our tests
- Removed Node v6 build from Travis CI for now; not sure why our integration tests have started to break there, but we're working on a different strategy for integration testing anyway
- Added Github templates
- Removed dead code path (the undeveloped subscription method)
- Minor update to Jest settings (now ignoring node_modules code path)
- Minor update to Travis build (now caches node_modules)
- Added slight clarification to LICENSE (still MIT)
- Removed unnecessary url from README

## v0.2.1 beta

- Updated documentation and tests

## v0.2.0 beta

- Significant revision of `query` and `mutate`
- Removed `subscription`; waiting on further testing

## v0.1.0 beta

MVP Release

---

View our [Contributing Guide](CONTRIBUTING.md)

Return to [README](README.md)
