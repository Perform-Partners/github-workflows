# Changelog
All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [Unreleased]
## [[0.13.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.13.0)
### Added
* Ability to use custom Packer Amazon plugin - [dmitri-pp](https://github.com/dmitri-pp)

## [[0.12.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.12.0)
### Changed
* Fix for Packer release when running in a repo with multiple AMIs - [dmitri-pp](https://github.com/dmitri-pp)

## [[0.11.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.11.0)
### Added
* Support for multiple terraform products in one repo - [danw-pp](https://github.com/danw-pp)

## [[0.10.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.10.0)
### Changed
* Fix Packer release so that GH tag value is passed to Packer - [dmitri-pp](https://github.com/dmitri-pp)

## [[0.9.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.9.0)
### Added
* Add support for optional arguments in Packer - [dmitri-pp](https://github.com/dmitri-pp)

## [[0.8.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.8.0)
### Changed
* Added permissions to and Changed naming of local release workflow - [danw-pp](https://github.com/danw-pp)
* Renaming Terraform "main" workflow to "release" to reflect the context in which it will be used - [danw-pp](https://github.com/danw-pp)
* Rewording PR workflow name - [danw-pp](https://github.com/danw-pp)
* Normalising and renaming of workflows, jobs and steps - [danw-pp](https://github.com/danw-pp)
* Splitting multiple run items into separate steps - [danw-pp](https://github.com/danw-pp)
* Made terraform plan and apply non-interactive to prevent stalled jobs on missing variables - [danw-pp](https://github.com/danw-pp)

## [[0.7.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.7.0)

## [[0.6.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.6.0)

## [[0.5.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.5.0)

## [[0.4.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.4.0)

## [[0.3.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.3.0)
### Added
* Workflows for Terraform Module PRs and Releases - [danw-pp](https://github.com/danw-pp)

## [[0.2.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.2.0)
### Added
* Checkov check argument

## [[0.1.0]](https://github.com/Perform-Partners/github-workflows/releases/tag/v0.1.0)
### Added
* Initial version with Terraform product workflows and tag creation
