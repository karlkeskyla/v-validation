# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [0.6.0](https://github.com/finnair/v-validation/compare/v0.5.0...v0.6.0) (2020-05-19)


### Bug Fixes

* Changelog + try fixing publish failing because of private package(?) ([589a896](https://github.com/finnair/v-validation/commit/589a89674b17e48148341878492f57a57f69c966))





# [0.5.0](https://github.com/finnair/v-validation/compare/v0.4.0...v0.5.0) (2020-05-19)

Path utilities:

- `Path` - concrete JSON paths used to locate, read or write a of an object (moved here from `@finnair/v-validation-core`)
- `PathMatcher` - a JsonPath like query processor.
- `Projection` - PathMatcher based include/exclude mapper for providing partial results from e.g. an API.