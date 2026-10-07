<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/monochange/monochange/main/assets/logo-dark-280.png">
  <img src="https://raw.githubusercontent.com/monochange/monochange/main/assets/logo-280.png" alt="monochange logo" width="280" height="171">
</picture>

**Many packages. One release plan.**

[Website](https://monochange.dev) · [Documentation](https://monochange.github.io/monochange/) · [Source](https://github.com/monochange/monochange)

</div>

monochange is a free, open-source toolkit for managing versions and releases in monorepos. It brings changesets, dependency updates, and release notes into one plan, even when your packages use different languages and registries.

A Rust library, a TypeScript SDK, and a Flutter app can share a repository without sharing a version. Keep versions independent or group packages that release together.

## What you can do

- Describe a change in a changeset: which packages changed, how their versions should move, and what belongs in the release notes.
- Preview version changes, dependency updates, and changelogs before applying them.
- Plan releases for Cargo, npm, Dart and Flutter, Python, Go, and Deno/JSR packages.
- Run the CLI locally or use it in CI, with GitHub Actions for changeset checks, release previews, and release pull requests.

## Start with the CLI

```sh
npm install -g @monochange/cli
monochange --help
```

The [installation guide](https://monochange.dev/install) also covers Cargo and Nix. Follow [the book](https://monochange.github.io/monochange/) to configure your workspace and preview your first release. The walkthrough stays local and does not publish packages.

The [GitHub App](https://monochange.dev/install#github-app) is being prepared for hosted release commits and pull requests. Installation is still being finalized; the CLI is available now.

## Around the organisation

- [monochange](https://github.com/monochange/monochange) — the Rust CLI, libraries, documentation, and website.
- [actions](https://github.com/monochange/actions) — GitHub Actions for monochange release workflows.

Found a bug or have an idea? [Open an issue](https://github.com/monochange/monochange/issues). To contribute code or docs, start with the [contribution guide](https://github.com/monochange/monochange/blob/main/CONTRIBUTING.md).
