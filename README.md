# Convetional Commit and Release

It a sample for conventional commit and release pipeline. It provides following features:
- Local commit hook using husky and commitlint
- Pipeline for commit check
- Pipeline for conventional release
- Pipeline for latest and version tag release
- Provides issue template
- Provides pull request template
- Provides stale issue configuration


## References

### [Conventional Changelog Action](https://github.com/TriPSs/conventional-changelog-action)
This action will bump version, tag commit and generate a changelog with conventional commits.


### [Conventional Pull Request Action](https://github.com/CondeNast/conventional-pull-request-action)
A github action that enforces the conventional commit spec on pull requests to ensure a clean and conventional commit history.


### [Husky](https://typicode.github.io/husky/#/)
It enforce conventional commit for local changes.


### [Conventional Changelog - Commitlint](https://github.com/conventional-changelog/commitlint)
It checks if your commit messages meet the conventional commit format.

- [commit-lint rules](https://github.com/conventional-changelog/commitlint/blob/master/docs/reference-rules.md)
- [@commitlint/config-conventional](https://github.com/conventional-changelog/commitlint/blob/master/@commitlint/config-conventional/index.js)


### [Actions Tagger](https://github.com/Actions-R-Us/actions-tagger)
Keep your action versions up-to-date by automatically promoting a major tag and a latest tag each time a release is created.

