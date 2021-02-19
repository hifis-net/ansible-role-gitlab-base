<!--
SPDX-FileCopyrightText: 2020 Helmholtz Centre for Environmental Research (UFZ)
SPDX-FileCopyrightText: 2020 Helmholtz-Zentrum Dresden-Rossendorf (HZDR)

SPDX-License-Identifier: Apache-2.0
-->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Group your changes into these categories:

`Added`, `Changed`, `Deprecated`, `Removed`, `Fixed`, `Security`.

## [0.3.1](https://gitlab.com/hifis/ansible/gitlab-base-role/-/releases/v0.3.1) - 2021-02-22

[List of commits](https://gitlab.com/hifis/ansible/gitlab-base-role/-/compare/v0.3.0...v0.3.1)

### Fixed
- Check that command gitlab-rails exists before executing it
  ([!15](https://gitlab.com/hifis/ansible/gitlab-base-role/-/merge_requests/15)
  by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).

## [0.3.0](https://gitlab.com/hifis/ansible/gitlab-base-role/-/releases/v0.3.0) - 2021-02-02

[List of commits](https://gitlab.com/hifis/ansible/gitlab-base-role/-/compare/v0.2.1...v0.3.0)

### Changed
- Improve and speed up the CI pipeline
  ([!9](https://gitlab.com/hifis/ansible/gitlab-base-role/-/merge_requests/9)
  by [tobiashuste](https://gitlab.com/tobiashuste)).

### Fixed
- Check for background migrations before updating GitLab
  ([!13](https://gitlab.com/hifis/ansible/gitlab-base-role/-/merge_requests/13)
  by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).

## [0.2.1](https://gitlab.com/hifis/ansible/gitlab-base-role/-/releases/v0.2.1) - 2020-09-10

[List of commits](https://gitlab.com/hifis/ansible/gitlab-base-role/-/compare/v0.2.0...v0.2.1)

### Fixed
- Add trigger for handler 'GitLab reconfigure' if GitLab upgrade has been performed
  ([!8](https://gitlab.com/hifis/ansible/gitlab-base-role/-/merge_requests/8)
  by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).

## [0.2.0](https://gitlab.com/hifis/ansible/gitlab-base-role/-/releases/v0.2.0) - 2020-09-08

[List of commits](https://gitlab.com/hifis/ansible/gitlab-base-role/-/compare/v0.1.0...v0.2.0)

### Added
- Set Ansible fact that GitLab is upgraded during provisioning
  ([!6](https://gitlab.com/hifis/ansible/gitlab-base-role/-/merge_requests/6)
  by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).

## [0.1.0](https://gitlab.com/hifis/ansible/gitlab-base-role/-/releases/v0.1.0) - 2020-08-20

### Added

Initial release of the Ansible GitLab Base Role.
