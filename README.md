[![CI Testing](https://github.com/tillable/omni-sdk/actions/workflows/test.yml/badge.svg)](https://github.com/tillable/omni-sdk/actions/workflows/test.yml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License - MIT](https://img.shields.io/badge/license-MIT-9400d3.svg)](https://spdx.org/licenses/)
[![types - Mypy](https://img.shields.io/badge/types-Mypy-blue.svg)](https://github.com/python/mypy)
[![All Contributors](https://img.shields.io/github/all-contributors/projectOwner/projectName?color=ee8449&style=flat-square)](#contributors)

# Omni SDK 

**Unofficial  SDK for [Omni Analytics](https://omni.co/)**

## Getting Started

For installation, configuration and usage view the docs [here](https://tillable.github.io/omni-sdk//#getting-started)

## Bug Reports

Submit any issues you may encounter as a  [GitHub issue](https://github.com/dtiesling/flask-muck/issues). Please search for 
similar issues before submitting a new one.

## Questions, Concerns, Ideas, Support, Feature Requests

All non-bug-related discussions such as support or feature requests should be submitted as a
[GitHub Discussion](https://github.com/dtiesling/flask-muck/discussions). 

## License

MIT licensed. See the [LICENSE](./LICENSE) file for more details.

## Contributing

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

### Development Environment

The development environment is simple and straightforward. Dependencies are managed by Poetry and tests are run 
with pytest. If you would like to test any changes against a live server you can use any apps in the `/examples` directory.

Prerequisites:
- [Python >= 3.9](https://www.python.org/downloads/)
- [Poetry](https://python-poetry.org/docs/#installation)

Install dependencies.
```bash
poetry install
```

Run tests.
```bash
poetry run pytest
```

### Code Style

- Code is formatted using [black](https://black.readthedocs.io/en/stable/).
- Typing is enforced with [mypy](https://mypy.readthedocs.io/en/stable/).


### How should I write my commits?

This project uses [release please](https://github.com/googleapis/release-please) and [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) for versioning releases.

Per [release-please-action](https://github.com/google-github-actions/release-please-action):

> The most important prefixes you should have in mind are:
>
> - `fix``: which represents bug fixes, and correlates to a SemVer patch.
> - `feat``: which represents a new feature, and correlates to a SemVer minor.
> - `feat!``:, or fix!:, refactor!:, etc., which represent a breaking change (indicated by the !) and will result in a SemVer major.

Any PR with `fix`, `feat`, `docs`, or a conventional commit with an `!` will trigger a release PR when merged.

Other conventional commits such as `chore`, `ci`, `test`, `refactor`, etc will not trigger a release but are encouraged to form a standard around conventional commits in the commit history.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->