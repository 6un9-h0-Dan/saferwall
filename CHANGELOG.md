# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.2] - 2020-04-01
### Added
- Add a cmd tool to batch upload files.

### Changed
- Fix phrasing in README from [@bf](https://github.com/bf).
- Fix bug in pe-parser related to parsing security directory.
- Fix recover from panic routine in parse-pe in consumer.
- Add exception catching in strings pkg.
- Fix resource parsing of malformed pe file with self referencing rsrc entries.
- Enable Kibana / ElasticSearch / FileBeat in helm deployments.
- Add ConextLogger in consumer to always log sha256.

## [0.0.1] - 2020-03-09
### Added
- Initiale release includes a multi-av scanner + strings + file metadata.
- UI with options to download, rescan, like a sample and share comments.
- User profile to track submissions, followers and see activities.
