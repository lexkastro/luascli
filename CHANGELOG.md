
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] - 2020-10-28

### Added

- CI/CD pipeline allow us to build and publish the tool with a new tag is generated
- CONTRIBUTING.md document with development information
- Added initial test setup
- Added bandit for static code security analysis
- Added black as our pep8 formatting tool

### Changed

- Fixed flake8 dependency missing in the pipenv configuration

## [0.2.0] - 2020-10-27

### Added

- luas <line> map <stop> - open the location of the luas stop in a browser
- lias <line> status - shows operational status for all lines
- luas <line> stops - display the list of all stops for a particular line