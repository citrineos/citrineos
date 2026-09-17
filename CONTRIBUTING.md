# Contributing to CitrineOS

Thank you for your interest in contributing to CitrineOS. This document explains our contribution process and procedures.

For a description of the roles and responsibilities of the various members of the CitrineOS community, refer to our [governance policies].

For the guidelines surrounding AI usage in CitrineOS, refer to our [AI guidelines](AI.md).

## How to Contribute a Bug Fix or Change

To contribute code to the project, first read over the [governance policies] page to understand the roles involved.

Each contribution must meet the [TypeScript](.eslintrc.json) *coding style* (part of every repository) and:

* Include tests and documentation to explain the functionality.
* Include the appropriate [copyright and license headers] in any new files.
* Be submitted to the project as a pull request.

CitrineOS is licensed under the [Apache License 2.0](LICENSE.md) license. Contributions should abide by that standard license.

If you are unfamiliar with contributing to projects on GitHub, [refer to this guide](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

Project committers will review the contribution in a timely manner, and advise of any changes needed to merge the request.

### Pull Requests

If you are unfamiliar with GitHub pull requests, [refer to this guide](https://docs.github.com/en/pull-requests/reference/pull-requests).

#### Branching

Branch from the most up-to-date development branch for that repository (for example, in `citrineos-core` it's the `next` branch).

Branch names should follow the [conventional branch](https://conventionalbranch.org/) specification to ensure
consistency and clarity. An example branch name for a new feature:

```
feat/new-ocpp-16-request-handler
```

#### Commit Messages
Commit messages should follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification
to ensure clean commit history and clarity. An example commit for a `core` feature:

```
feat(ocpp): adding new message handler in Module for new-request-type from OCPP 1.6.
```

#### Opening a Pull Request

When opening a pull request, descriptions should include:

1. What the change is.
2. Why the change is needed.
3. Reproduction steps (if it's for fixing a bug).
4. Any further context that will help reviewers understand the purpose and impact of the change.

### License Headers
Every file that is not purposely exempt from license headers must include the appropriate license headers:

```ts
// SPDX-FileCopyrightText: 2026 Contributors to the CitrineOS Project
//
// SPDX-License-Identifier: Apache-2.0
```

[governance policies]: GOVERNANCE.md
[copyright and license headers]: ##license-specification