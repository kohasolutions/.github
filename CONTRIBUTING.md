# Contributing to Koha Solutions projects

Thank you for helping. These tools are for people who run Koha, and the best improvements come from people who run it.

## Before you start

- **Found a bug?** Open an issue with the *Bug report* template. Say which Koha version and operating system you use,
  what you ran, and what it printed. Remove names, emails, card numbers and passwords from any output you paste.
- **Want a feature?** Open an issue with the *Feature request* template first, so we can agree on the shape before you
  write code.
- **Security problem?** Do **not** open a public issue. See [SECURITY.md](SECURITY.md).
- **A question about Koha itself** (not about these tools) is best asked on the Koha community's channels:
  https://koha-community.org/support/

## Making a change

1. Fork the repository and create a branch from `main`.
2. Keep the change focused: one fix or one feature per pull request.
3. Run the repository's tests (its README says how). If you changed behaviour, add or change a test that shows it.
4. If the change touches what Koha does, say which Koha version you tried it on.
5. Update the README when you change a command, an option or an output.
6. Open the pull request with the template filled in.

## What we check in review

- It works on the Koha versions listed in the repository's `TESTED.md`, or the PR says why not.
- No secrets, no real patron or library data, no hard-coded addresses.
- Commands in the README still show the output they really print.
- Plain, clear English in messages and docs: many readers do not speak English as a first language.

## Licence

By contributing you agree that your contribution is licensed under the licence of the repository you contribute to
(its `LICENSE` file).

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
