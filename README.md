# af3-dag-builder-docs

Published MkDocs site for [af3-dag-builder](https://github.com/avikbesu/af3-dag-builder), built and
pushed automatically by the `Publish Docs` GitHub Actions workflow in that repo.

This repo has no `main`-branch content of its own — every branch here is a built site snapshot:

- Pushing a feature branch in af3-dag-builder publishes the built site to a branch of the same
  name here.
- Pushing a `release/*` branch or a version tag (`v*`) in af3-dag-builder publishes to the
  `release` branch here.

Each branch's history is incremental (one commit per publish), so it can be diffed like any other
generated-content branch.
