# Hass.io Add-on Changelog: Homebridge

All notable changes to this add-on will be documented in this file.

The format is based on [Keep a Changelog][keep-a-changelog]
and this project adheres to [Semantic Versioning][semantic-versioning].

## Unreleased

No unreleased changes yet.

## [v2.4.0] (2018-03-17)

[Full Changelog][v2.3.0-v2.4.0]

### Added

- Adds addon logo and icon
- Warns the user when not using the Hass.io Proxy address
- Adds support for auto configuring Hass.io API security key

### Changed

- Updates base image to v1.3.3
- Updates homebridge to v0.4.38 #80 (@funnybutrandom)

## [v2.3.0] (2018-01-19)

[Full Changelog][v2.2.0-v2.3.0]

### Changed

- Prevents possible future Docker login issue
- Removes Microbadger notification hooks
- Pass local CircleCI Docker socket into the build container
- Use image tagged as test as a cache resource
- Sets the default visibilit to hidden for new installs
- Upgrades add-on base image to v1.3.2
- Upgrades Homebridge to v0.4.36
- Updated maintenance year, it is 2018

## [v2.2.0] (2017-12-03)

[Full Changelog][v2.1.2-v2.2.0]

### Changed

- Upgrades add-on base image to v1.2.0
- Improves S6 service scripts
- Updates add-on URLs to new community forum URL
- Moves copy of rootfs at a later stage

## [v2.1.2] (2017-11-14)

[Full Changelog][v2.1.1-v2.1.2]

### Changed

- Upgraded Homebridge to v0.4.33
- Upgraded `homebridge-homeassistant` to v3.0.2

### Removed

- Removes `repository.json` to prevent user to install wrong repo
- Removes Gratipay from README, since it is EOL

## [v2.1.1] (2017-10-30)

[Full Changelog][v2.1.0-v2.1.1]

### Changed

- Upgraded Homebridge to v0.4.29

## [v2.1.0] (2017-10-26)

[Full Changelog][v2.0.1-v2.1.0]

### Changed

- Upgraded NodeJS to 8.x #47
- Upgraded `homebridge-homeassistant` to v3.0.1

## [v2.0.1] (2017-10-25)

[Full Changelog][v2.0.0-v2.0.1]

### Added

- Made git available by default #44

### Fixed

- Won't start; sed: unmatched '/' #45

### Changed

- Use the Hass.io to Home Assistant proxy by default
- Upgraded addon-base image to v1.0.1

## [v2.0.0] (2017-10-20)

[Full Changelog][v1.0.3-v2.0.0]

### Added

- Added CodeClimate
- Added CircleCI
- Added support for Hass.io's extended label schema
- Added support for IPv6 (but can be disabled)
- Added support for automatic detection of Avahi interfaces
- Added support for manually limiting/changing the interfaces Avahi is using
- Added automatic detection of the Avahi hostname
- Added support for manually setting an Avahi hostname
- Added support for changing Avahi's domain name
- Added support for installing custom OS packages
- Added support for executing custom commands

### Fixed

- Can't use curl with this addon #11
- Homebridge will not show in iOS app #5
- Automatic restart needed #16
- Siri will not lock or unlock a door. Home app will do this just fine. #26

### Changed

- Reduced image size significantly
- Migrated to the new Hass.io build system
- Migrated to our new base images
- Rewrite of add-on onto the S6 process supervisor
- Updated Homebridge to 0.4.28
- Updated Home Assistant Homebridge to 2.3.1
- Updated Homebridge configuration template to include latest features
- Updated all documentation files

## [v1.0.3] (2017-08-21)

[Full Changelog][v1.0.2-v1.0.3]

### Fixed

- Adds 'default_visbility' flag to the default configuration of Homebridge

## [v1.0.2] (2017-08-20)

[Full Changelog][v1.0.1-v1.0.2]

### Changed

- Updated `homebridge-homeassistant` to version v2.3.0
- Changed repository file structure
- Changed / simplyfield buildscripts
- Updated the documentation to match recent changes

### Fixes

- There was an error when installed the plugin

## [v1.0.1] (2017-08-15)

[Full Changelog][v1.0.0-v1.0.1]

### Fixes

- Homebridge pin generated with additional dash

## [v1.0.0] (2017-08-14)

### Added

- First version of the Homebridge Add-on
- This CHANGELOG file

[keep-a-changelog]: http://keepachangelog.com/en/1.0.0/
[semantic-versioning]: http://semver.org/spec/v2.0.0.html
[v1.0.0-v1.0.1]: https://github.com/hassio-addons/addon-homebridge/compare/v1.0.0...v1.0.1
[v1.0.0]: https://github.com/hassio-addons/addon-homebridge/tree/v1.0.0
[v1.0.1-v1.0.2]: https://github.com/hassio-addons/addon-homebridge/compare/v1.0.1...v1.0.2
[v1.0.1]: https://github.com/hassio-addons/addon-homebridge/tree/v1.0.1
[v1.0.2-v1.0.3]: https://github.com/hassio-addons/addon-homebridge/compare/v1.0.2...v1.0.3
[v1.0.2]: https://github.com/hassio-addons/addon-homebridge/tree/v1.0.2
[v1.0.3-v2.0.0]: https://github.com/hassio-addons/addon-homebridge/compare/v1.0.3...v2.0.0
[v1.0.3]: https://github.com/hassio-addons/addon-homebridge/tree/v1.0.3
[v2.0.0-v2.0.1]: https://github.com/hassio-addons/addon-homebridge/compare/v2.0.0...v2.0.1
[v2.0.0]: https://github.com/hassio-addons/addon-homebridge/tree/v2.0.0
[v2.0.1-v2.1.0]: https://github.com/hassio-addons/addon-homebridge/compare/v2.0.1...v2.1.0
[v2.0.1]: https://github.com/hassio-addons/addon-homebridge/tree/v2.0.1
[v2.1.0-v2.1.1]: https://github.com/hassio-addons/addon-homebridge/compare/v2.1.0...v2.1.1
[v2.1.0]: https://github.com/hassio-addons/addon-homebridge/tree/v2.1.0
[v2.1.1-v2.1.2]: https://github.com/hassio-addons/addon-homebridge/compare/v2.1.1...v2.1.2
[v2.1.1]: https://github.com/hassio-addons/addon-homebridge/tree/v2.1.1
[v2.1.2-v2.2.0]: https://github.com/hassio-addons/addon-homebridge/compare/v2.1.2...v2.2.0
[v2.1.2]: https://github.com/hassio-addons/addon-homebridge/tree/v2.1.2
[v2.2.0-v2.3.0]: https://github.com/hassio-addons/addon-homebridge/compare/v2.2.0...v2.3.0
[v2.2.0]: https://github.com/hassio-addons/addon-homebridge/tree/v2.2.0
[v2.3.0-v2.4.0]: https://github.com/hassio-addons/addon-homebridge/compare/v2.3.0...v2.4.0
[v2.3.0]: https://github.com/hassio-addons/addon-homebridge/tree/v2.3.0
[v2.4.0]: https://github.com/hassio-addons/addon-homebridge/tree/v2.4.0
