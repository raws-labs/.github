# Contributing to RAWS Labs projects

Thanks for your interest in contributing. This guide applies across the
[raws-labs](https://github.com/raws-labs) repositories. Each repository's
`README.md` documents its own build and test steps; this page covers the
conventions common to all of them.

## Ways to contribute

- **Report a bug or request a feature** by opening an issue. Include what you
  expected, what actually happened, and enough to reproduce it — versions,
  platform, and a minimal model or input where relevant.
- **Propose a change** with a pull request, as described below.
- **Improve the documentation** — corrections and clarifications are welcome.

For security-sensitive reports, please do not open a public issue; email
contact@raws.at instead.

## Development workflow

1. Fork the repository, or create a branch if you have write access.
2. Start your topic branch from `develop`.
3. Make your change with tests, and run the repository's test suite locally
   (see its `README.md`). Most repositories also run a host-side CI check that
   a pull request must pass.
4. Open a pull request against `develop`. Most repositories use a `develop`
   integration branch with `main` tracking releases; target `develop` unless the
   repository's README says otherwise.
5. Keep each pull request focused — unrelated changes are easier to review as
   separate requests.

## Commit and pull-request conventions

- Write single-line commit subjects in the form `type: short description`, for
  example `fix: handle empty input path` or `feature: add JSON output`.
- Keep commit subjects free of trailers.
- Explain the what and why in the pull-request body, and reference any related
  issue.

## Testing

Every change should keep the test suite green and add coverage for new behavior.
The exact build and test commands live in each repository's `README.md`.

## License

By contributing, you agree that your contributions are licensed under the
Apache License 2.0 that governs the repository you are contributing to.

## Code of Conduct

Participation in these projects is governed by our
[Code of Conduct](https://github.com/raws-labs/.github/blob/main/CODE_OF_CONDUCT.md).
By taking part you agree to uphold it; report unacceptable behavior to
contact@raws.at.
