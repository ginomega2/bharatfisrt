# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository status

As of January 5, 2026, this repository contains only Git metadata (the `.git` directory) and no source code, configuration files, or documentation.

Future instances of Warp should re-scan the repository structure before acting, since project files, build configuration, and documentation may have been added after this date.

## Build, run, lint, and test commands

No language-specific or build-related configuration files were detected (for example `package.json`, `pyproject.toml`, `pom.xml`, `build.gradle`, `Makefile`, or similar). This means there are currently **no canonical project commands** for building, running, linting, or testing.

Once a tech stack is introduced, update this section with the authoritative commands. For example:

- How to install dependencies
- How to build the project
- How to run the application in development mode
- How to run the full test suite
- How to run a single test (with concrete examples)
- How to run linters / formatters / type checkers

Future Warp instances should prefer commands documented in `README.md`, `Makefile`, or language-specific tool configuration over ad-hoc guesses.

## Architecture overview

There is currently no application or library code in this repository, so there is no architecture to document yet.

When code is added, describe here **only the high-level structure that is not obvious from a quick directory listing**, for example:

- The main entrypoints (binaries, services, or CLIs) and where they live
- The core modules / packages and how they depend on each other
- Any cross-cutting concerns (configuration, logging, error handling, domain models)
- How tests are organized and how they map to the main code

Future Warp instances should update this section after inspecting the real codebase so that agents can quickly understand the big-picture design without reading every file.
