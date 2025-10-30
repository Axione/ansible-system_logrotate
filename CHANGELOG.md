# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0](https://github.com/lotusnoir/ansible-system_logrotate/compare/1.0.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`c29017b`](https://github.com/lotusnoir/ansible-system_logrotate/commit/c29017bec4d8370d8187e454e777e49c518ee3fb)
- update core, molecule + gitlab-ci [`aa354e5`](https://github.com/lotusnoir/ansible-system_logrotate/commit/aa354e5e33c585017cc600febe642d44cb6d534a)
- ensure proper permission on /var/log as logrotate fails if not root:root [`5272a8e`](https://github.com/lotusnoir/ansible-system_logrotate/commit/5272a8e82a4013ae2968a96ad67a21dc942e1a39)
- add possibility to execute at the end of installation [`4ecd0bd`](https://github.com/lotusnoir/ansible-system_logrotate/commit/4ecd0bdcc0b31e0b1db4500ec1b6dc2447a5f44d)
- fix lint [`e117a5c`](https://github.com/lotusnoir/ansible-system_logrotate/commit/e117a5c865fae33b8bc599a8515e2d1cd352f75f)
- fix molecule paralelism and little updates [`c1ede3e`](https://github.com/lotusnoir/ansible-system_logrotate/commit/c1ede3e12bad843894345a90d5485b8405e26e73)
- add support for ubuntu24 [`5f5c2de`](https://github.com/lotusnoir/ansible-system_logrotate/commit/5f5c2de5e9e10742ae908339f5ec25a1d38aec0f)
- add version on molecule play image to maintain support on old release [`3011071`](https://github.com/lotusnoir/ansible-system_logrotate/commit/301107127a60993b797aa7945fb51e01e4b4968e)
- update molecule [`1256cde`](https://github.com/lotusnoir/ansible-system_logrotate/commit/1256cdec043735e0a48e293532047ef249183b33)
- add redhat 9 to default supported distrib [`cf6ddf8`](https://github.com/lotusnoir/ansible-system_logrotate/commit/cf6ddf8547172ff3d488875d5be7f736373d7ea8)

## [1.0.0](https://github.com/lotusnoir/ansible-system_logrotate/compare/0.2.0...1.0.0) - 2023-09-25

### Commits

- update vars [`8bd2a5e`](https://github.com/lotusnoir/ansible-system_logrotate/commit/8bd2a5e93bdc28d5cfb0d640e4b2eb0f2fc70dd8)
- update readme + precommit + include vars [`791c9f1`](https://github.com/lotusnoir/ansible-system_logrotate/commit/791c9f1c3e0c5ca1cd6c3aff0e15999a6bfc63f5)
- change import tasks to include in order to support facts on name [`123ed84`](https://github.com/lotusnoir/ansible-system_logrotate/commit/123ed849ac3d0a2a1c987b86e9b4e56b7cfda954)

## [0.2.0](https://github.com/lotusnoir/ansible-system_logrotate/compare/0.1.0...0.2.0) - 2023-06-14

### Commits

- add debian12 support [`ae13101`](https://github.com/lotusnoir/ansible-system_logrotate/commit/ae131015bab971dc8f582338a14e7270c42d376a)
- add galaxy id [`4b2dc25`](https://github.com/lotusnoir/ansible-system_logrotate/commit/4b2dc25206ad5bbde60432ee6b5d73faa0e2f573)

## 0.1.0 - 2023-03-23

### Commits

- add code of conduc and small changes [`7f36e4f`](https://github.com/lotusnoir/ansible-system_logrotate/commit/7f36e4f1248c91c534ea7a88629af2c90abe488c)
- add precommit for lint [`a35399e`](https://github.com/lotusnoir/ansible-system_logrotate/commit/a35399e3ac0c7c834f64e5a318f7645b5fe73805)
- fix checks [`840c4f4`](https://github.com/lotusnoir/ansible-system_logrotate/commit/840c4f4f319b366687c4ea082a1333bf74fca606)
- add new molecule all scenario [`bf5f1d2`](https://github.com/lotusnoir/ansible-system_logrotate/commit/bf5f1d228918e33d515b66dc99fda006362b1fb0)
- add missing distro [`00c91e2`](https://github.com/lotusnoir/ansible-system_logrotate/commit/00c91e217cb1f442a91cd3a6b822ba7a69f08948)
- rename molecule name instance [`2932d52`](https://github.com/lotusnoir/ansible-system_logrotate/commit/2932d52b1b59ca38bdcfaf02411dcfae59a34a42)
- add tasks conditions [`c866f65`](https://github.com/lotusnoir/ansible-system_logrotate/commit/c866f65fc60dd35f803f6ee2717d357528a69742)
