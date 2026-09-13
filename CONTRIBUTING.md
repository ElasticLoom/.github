# Contributing to ElasticLoom projects

Thanks for your interest in contributing! These guidelines apply to all
ElasticLoom open source projects. A project may have its own `CONTRIBUTING.md`
with build, test and style details; where the two differ, the project's file
takes precedence.

## Before you start

- Read the project's `README.md` and any design documentation it links to.
- Search existing issues and pull requests to avoid duplicate work.
- For anything beyond a small fix, open an issue to discuss the approach
  before investing time in an implementation.
- **Report security issues privately** — see
  [SECURITY.md](https://github.com/ElasticLoom/.github/blob/main/SECURITY.md).
  Do not open a public issue.

## Pull requests

- Keep each pull request focused on one change.
- Run the project's checks (formatting, linting, tests) before pushing. CI
  must pass before a change is merged.
- Add or update tests for behavior changes.
- Update documentation in the same pull request as the code it describes.
- Record user-visible changes in `CHANGELOG.md`, if the project has one.
- Write commit messages that explain *why* a change was made, not only what
  changed.
- Do not include secrets, credentials, internal hostnames or private paths in
  code, tests, examples, logs or commit messages.

## Reporting bugs and requesting features

Use the issue forms in the project's repository. For bugs, include the
version or commit you used, your platform, steps to reproduce, and what you
expected to happen. Remove sensitive information from any logs or
configuration you share.

## License

Unless a project states otherwise, contributions you submit are licensed
under the same license as the project, without any additional terms or
conditions.
