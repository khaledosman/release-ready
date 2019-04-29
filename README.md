[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

#Features 

- Linting git commit messages and enforcing conventional commits
- Commitizen friendly, allows developers to write conventional commits by running `git cz` or `yarn commit` or optionally make it replace `git commit` command to prompt the user about changes and generate a conventional commit out of the response
- Automated changelog / release notes generation
- Automated version bumping based on semantic versioning (semver)
- Automatically creates a git tag and optionally publishes it to git and npm thanks to `standard-version` or `semantic-release`
