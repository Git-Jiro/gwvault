<a name="unreleased"></a>
## [Unreleased]


<a name="v1.7.2"></a>
## [v1.7.2] - 2020-08-25
### Chore
- updated release script to include publish to github
- **make:** don't update go.mod with gox

### Pull Requests
- chore(deps): update module clok/kemba to v0.7.1 ([#16](https://github.com/GoodwayGroup/gwvault/issues/16))
- chore(deps): update golang.org/x/crypto commit hash to 5c72a88 ([#13](https://github.com/GoodwayGroup/gwvault/issues/13))


<a name="v1.7.1"></a>
## [v1.7.1] - 2020-08-21
### Chore
- **deps:** update clok/kemba and clok/cdocs
- **renovate:** clean up dupe config
- **renovate:** add renovate.json

### Features
- **release:** v1.7.1

### Pull Requests
- chore(deps): update module alecaivazis/survey/v2 to v2.1.1 ([#12](https://github.com/GoodwayGroup/gwvault/issues/12))
- chore(deps): add renovate.json ([#11](https://github.com/GoodwayGroup/gwvault/issues/11))


<a name="v1.7.0"></a>
## [v1.7.0] - 2020-08-13
### Chore
- update README.md
- **docs:** updating docs for version v1.7.0

### Features
- **release:** v1.7.0

### Fest
- **cdocs:** integrate cdocs library


<a name="v1.6.0"></a>
## [v1.6.0] - 2020-08-12
### Chore
- updated make and release process
- **docs:** initial generation of docs

### Features
- **docs:** updated cli to v2, added in docs generation
- **release:** v1.6.0


<a name="v1.5.0"></a>
## [v1.5.0] - 2020-08-04
### Chore
- remove benchmark results html to decrease bloat

### Features
- **release:** v1.5.0
- **release:** 1.4.0

### Pull Requests
- feat(modernize): support go.mod, cleaned up code, brought in line with current ansible-vault ([#10](https://github.com/GoodwayGroup/gwvault/issues/10))


<a name="1.4.0"></a>
## [1.4.0] - 2020-07-19
### Chore
- update .gitignore to exclude bin dir

### DevOps
- updated release process and changelog to git-chglog

### Pull Requests
- feat: Read ANSIBLE_VAULT_PASSWORD_FILE env variable if no password provided ([#9](https://github.com/GoodwayGroup/gwvault/issues/9))


<a name="1.3.0"></a>
## [1.3.0] - 2019-08-19
### Pull Requests
- Support check for TTY terminal when using `view` ([#7](https://github.com/GoodwayGroup/gwvault/issues/7))


<a name="1.2.1"></a>
## [1.2.1] - 2019-08-18
### Pull Requests
- Patch: Use `cat` instead of `more` ([#6](https://github.com/GoodwayGroup/gwvault/issues/6))
- Support rekey method ([#4](https://github.com/GoodwayGroup/gwvault/issues/4))
- Merge pull request [#3](https://github.com/GoodwayGroup/gwvault/issues/3) from GoodwayGroup/release/v1.2.0


<a name="1.2.0"></a>
## [1.2.0] - 2018-10-30
### Pull Requests
- Support encrypt_string method ([#2](https://github.com/GoodwayGroup/gwvault/issues/2))


<a name="1.1.0"></a>
## [1.1.0] - 2018-08-20
### Pull Requests
- Added support for file globs ([#1](https://github.com/GoodwayGroup/gwvault/issues/1))


<a name="1.0.1"></a>
## [1.0.1] - 2018-08-17

<a name="1.0.0"></a>
## 1.0.0 - 2018-08-17

[Unreleased]: https://github.com/GoodwayGroup/gwvault/compare/v1.7.2...HEAD
[v1.7.2]: https://github.com/GoodwayGroup/gwvault/compare/v1.7.1...v1.7.2
[v1.7.1]: https://github.com/GoodwayGroup/gwvault/compare/v1.7.0...v1.7.1
[v1.7.0]: https://github.com/GoodwayGroup/gwvault/compare/v1.6.0...v1.7.0
[v1.6.0]: https://github.com/GoodwayGroup/gwvault/compare/v1.5.0...v1.6.0
[v1.5.0]: https://github.com/GoodwayGroup/gwvault/compare/1.4.0...v1.5.0
[1.4.0]: https://github.com/GoodwayGroup/gwvault/compare/1.3.0...1.4.0
[1.3.0]: https://github.com/GoodwayGroup/gwvault/compare/1.2.1...1.3.0
[1.2.1]: https://github.com/GoodwayGroup/gwvault/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/GoodwayGroup/gwvault/compare/1.1.0...1.2.0
[1.1.0]: https://github.com/GoodwayGroup/gwvault/compare/1.0.1...1.1.0
[1.0.1]: https://github.com/GoodwayGroup/gwvault/compare/1.0.0...1.0.1
