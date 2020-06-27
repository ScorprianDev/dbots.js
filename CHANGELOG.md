# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

You can see the docs for every version at [here](https://dbots.js.org/#/docs)

## [Unreleased]

## [4.1.0] - 2020-06-18
### Added
- Add new service: BotsDataBase

## [4.0.0] - 2020-06-07
### Added
- Add better error handling for when requests to services get rejected.

### Changed
- **[BREAKING]** ListMyBots: Update class methods, check the docs to see the new class.
- **[BREAKING]** GlennBotList: `.getProfile()` is now called `.getUser()` (we're skipping deprecation since we're publishing a major version anyway).

### Removed
- **[BREAKING]** DiscordBotList: removed the `.getWidgetURL()` method since the list has switched to [JavaScript widgets](https://docs.discordbotlist.com/javascript-widget).

### Fixed
- Update endpoints for ListMyBots, GlennBotList and DiscordBotList.

[Unreleased]: https://github.com/dbots-pkg/dbots.js/compare/v4.1.0...HEAD
[4.0.0]: https://github.com/dbots-pkg/dbots.js/compare/v3.0.1...v4.0.0
[4.1.0]: https://github.com/dbots-pkg/dbots.js/compare/v4.0.0...v4.1.0