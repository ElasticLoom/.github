# ElasticLoom/.github

Organization-wide defaults for [ElasticLoom](https://github.com/ElasticLoom)
repositories.

- [`profile/README.md`](profile/README.md) is shown on the
  [organization page](https://github.com/ElasticLoom).
- The community health files below are used by any ElasticLoom repository
  that does not provide its own. A repository overrides a default by adding a
  file with the same name (in its root, `docs/` or `.github/`).

| File | Purpose |
|------|---------|
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | General contribution guidelines |
| [`SECURITY.md`](SECURITY.md) | How to report vulnerabilities |
| [`SUPPORT.md`](SUPPORT.md) | Where to ask questions and get help |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Bug report and feature request forms |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | Pull request description and checklist |

Issue templates are inherited as a set: a repository with its own
`.github/ISSUE_TEMPLATE/` directory uses none of these.

## Open sourcing a new repository

Projects are expected to carry their own `README.md`, `LICENSE` and, once they
have project-specific build, test or security details, their own
`CONTRIBUTING.md` and `SECURITY.md`. [byssus](https://github.com/ElasticLoom/byssus)
is a good reference. Before making a repository public:

- [ ] Add a `LICENSE` (Apache-2.0 unless there is a reason to choose otherwise)
- [ ] Write a `README.md` that states what the project is, its status, and how
      to build or install it
- [ ] Enable **private vulnerability reporting** (Settings → Code security)
- [ ] Add a repository description and topics
- [ ] Check the full git history for secrets, internal hostnames and private
      paths
- [ ] Protect the default branch and require CI to pass
- [ ] Add the project to [`profile/README.md`](profile/README.md)
