# Contribution Guidelines

## Issue Tracker & Bug Reporting

- Try to provide simple examples demonstrating the issue at hand; describe what happened as well as what you would have expected to happen instead.

- Reproduction-instructions shall be expressed in terms of Haskell.org's standard tooling (i.e. `cabal`).

- Be aware this is a F/OSS project; the software is provided "as is" for no charge and you're entitled in terms of support to what you payed for.

## Coding Guidelines

- Try to follow the pre-existing indentation style; avoid tabs for indentation; avoid trailing whitespace; if in doubt, try to follow [this style guide](https://github.com/hvr/haskell-style-guide/blob/master/haskell-style.md)

- Development & support is done primarily using Haskell.org's standard tooling, i.e. `cabal`; we don't have time & energy to support everyone's favourite third-party tooling.

- Haskell packages are subject to the [Haskell Package Versioning Policy](https://pvp.haskell.org/) which governs both the API versioning as well as the specification of dependency versions.

- Generally, only properly released major versions of tools and libraries are actively supported in Hackage releases; this is reflected in the dependency version constraints (see also previous item).

- When relaxing upper bounds for dependencies in order to declare compatibility with new major versions, it's **not** sufficient to merely rely on CI; make sure to review the API changes prompting the major version increment to ensure that the version relaxation is indeed safe/sound.

## FAQ

- **Can you add your packages to Stackage?** No can do; [I have been banned from Stackage](https://github.com/fpco/stackage/issues/4472) but if you haven't been blocked yet, you can try to [file an issue](https://github.com/fpco/stackage/issues/new).
