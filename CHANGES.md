# Changes

This is the changelog for the basepom project. It follows [Keep a Changelog v1.0.0](http://keepachangelog.com/en/1.0.0/).

Every release of this project is potentially incompatible to the previous one even though reasonable attempts are made to be drop-in compatible. There is only a major version number which is incremented with every release.


## Unreleased

### Added

* This is a backport to JDK8 for the basepom project. It will try to keep up with the regular basepom releases which are JDK9+ since version 32.

### Changed

* Use the collecting manifest transformer to also add the main class to an executable jar. This is a workaround for a change in the shade plugin since 3.2.4.

### Deprecated

### Removed

### Fixed

### Security

