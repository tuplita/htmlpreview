# tuplita/htmlpreview

Self-hosted HTML preview tool, forked from
[htmlpreview/htmlpreview.github.com](https://github.com/htmlpreview/htmlpreview.github.com)
(Apache License 2.0).

Renders HTML files from public URLs.

## Usage

    https://tuplita.github.io/htmlpreview/?<url-to-public-html-file>

For example, to preview a file in a public GitHub repo:

    https://tuplita.github.io/htmlpreview/?https://raw.githubusercontent.com/<owner>/<repo>/<branch>/<path>.html

## Limitations

Only renders publicly accessible URLs. The tool does not handle authentication.

## License

Apache License 2.0 — see `LICENSE`. Original work copyright 2019 Jerzy Głowacki;
Tuplita modifications copyright Tuplita contributors. See `NOTICE` for attribution.

## Compliance notes

- This repository is a Tuplita fork of
  [htmlpreview/htmlpreview.github.com](https://github.com/htmlpreview/htmlpreview.github.com),
  which is licensed under Apache License 2.0.
- The fork keeps the Apache License 2.0 text in `LICENSE`, upstream attribution
  in `NOTICE`, and modification notices in changed source files.
- There is no package manager manifest, lockfile, vendored dependency tree,
  backend service, or deployment workflow in this repository.
- Security contact is documented in `SECURITY.md`.
- Code ownership is documented in `.github/CODEOWNERS`; the `@tuplita/core`
  team should have explicit write access for GitHub review requests to work.
- For Tuplita governance, keep repository-level controls enabled in GitHub:
  branch protection with required review, Dependabot alerts, secret scanning
  and push protection, and CodeQL default setup for JavaScript code scanning.
