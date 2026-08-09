# homebrew-tap

Homebrew tap for intern tooling.

## Usage

Tap the repo:

```bash
brew tap sbekti/tap
```

Install `internctl`:

```bash
brew install internctl
```

Or install directly from the fully qualified formula name:

```bash
brew install sbekti/tap/internctl
```

## Contents

- `internctl`
  - command-line client for the internal management platform

## Source and release flow

`internctl` is sourced and released from [sbekti/intern](https://github.com/sbekti/intern). The generated formula is updated automatically by the monorepo's signed `vX.Y.Z` release workflow using GoReleaser.
