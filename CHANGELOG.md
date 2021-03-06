# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v2.0.0-beta.1] - 2018-09-18

### Changed
- Switch from custom webpack build setup to ember-auto-import. Thanks [@jasonmit](https://github.com/jasonmit)! ([#159](https://github.com/bgentry/ember-apollo-client/pull/159))
- The old build configs (`include`, `exclude`) have been removed. Additional dependencies can be used via ember-auto-import and a regular npm install.
- The old, deprecated mixin import paths have been removed.
- The deprecated `middlewares` option has been removed from the apollo service. Users should switch to override `link` instead.

## [v1.1.0] - 2018-09-14

### Changed
- Addon config is now fetched lazily thanks to [@lennyburdette](https://github.com/lennyburdette) in [#166](https://github.com/bgentry/ember-apollo-client/pull/166).
- The old mixin import paths have been deprecated ([#167](https://github.com/bgentry/ember-apollo-client/pull/167)). Thanks [@jasonmit](https://github.com/jasonmit)!
