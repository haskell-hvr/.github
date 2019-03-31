# Contribution Guidelines

## Issue Tracker & Bug Reporting

- Try to provide simple examples demonstrating the issue at hand; describe what happened as well as what you would have expected to happen instead.

- Reproduction-instructions shall be expressed in terms of Haskell.org's standard tooling (i.e. `cabal`).

- Be aware this is a F/OSS project; the software is provided "as is" for no charge and you're entitled in terms of support to what you payed for.

## Coding Guidelines

- Try to follow the pre-existing indentation style; avoid tabs for indentation; avoid trailing whitespace; if in doubt, try to follow [this style guide](https://github.com/hvr/haskell-style-guide/blob/master/haskell-style.md)

- Development & support is done primarly using Haskell.org's standard tooling, i.e. `cabal`; we don't have time & energy to support everyone's favourite third-party tooling.

- Haskell packages are subject to the [Haskell Package Versioning Policy](https://pvp.haskell.org/) which governs both the API versioning as well as the specification of dependency versions.

- Generally, only properly released major versions of tools and libraries are actively supported in Hackage releases; this is reflected in the dependency version constraints (see also previous item).
