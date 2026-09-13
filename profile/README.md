# ElasticLoom

ElasticLoom is a private research project. Along the way we build
infrastructure that stands on its own, and we open source those pieces so
they are useful beyond ElasticLoom.

## Open source projects

- **[Byssus](https://github.com/ElasticLoom/byssus)** — Live filesystem
  attachments between isolated workspaces. A small Linux daemon turns group
  membership, declared by creating or deleting empty files, into bind mounts
  (read-only by default) that appear in already-running containers without
  restarts. Rust, Apache-2.0.
- **[trimout](https://github.com/ElasticLoom/trimout)** — Run a command once,
  cache its full output, and send only the useful parts to your LLM. Filters
  noisy build and test output down to the lines that matter, while the cached
  original can be re-queried without rerunning the command. Go.

More projects will be released here over time.

## Contributing

Contributions are welcome. Each project's own `CONTRIBUTING.md` describes how
to build and test it; our [general contribution guidelines](https://github.com/ElasticLoom/.github/blob/main/CONTRIBUTING.md)
apply everywhere.

Please report security vulnerabilities privately, as described in our
[security policy](https://github.com/ElasticLoom/.github/blob/main/SECURITY.md).
