# How to Contribute

Thank you for your interest in contributing to this project!  Read on for information on how to contribute.

## Bug Reports

Bug reports should be submitted via the Issues tab following these steps:
1. First, check whether there already is an open issue for your bug.
2. If an open issue for your bug doesn't already exist, then submit an issue.
3. Please include enough detail to reproduce the issue.
4. Please choose the relevant issue template when prompted.

## Feature Requests

Requests for new functionality or enhancements to existing functionality can also be submitted via 
the Issues tab. Just like with bug reports,
please verify that there isn't already an existing issue covering the same request. Please choose the relevant issue template when prompted.

## Requirements for All Pull Requests

The sections below have more specific guidelines specific to bug fixes and adding features. All pull requests have the following additional requirements:
1. Only maintainers are allowed to touch configuration files (e.g., pom.xml for Java projects). If your pull request changes any configuration files, it will be closed.
2. Only maintainers are allowed to touch GitHub Actions workflows, dependabot configuration, etc. If your pull request changes any such files, it will be closed.
3. No drive-by generative AI pull requests. First-time contributers must not use generative AI tools in their contribution.
4. You must use the pull request template, and you must complete the relevant parts of the checklist in that template.
5. Your pull request must be associated with an open issue, and you must be assigned to that issue. You can volunteer and request to be assigned by commenting on the issue.

## Bug Fixes

If you would like to more actively contribute with a bug fix, then follow this procedure:
1. If the bug you want to fix doesn't have an existing Issue, then start with [Bug Reports](#bug-reports) section above.
2. Fork the repository.
3. Create a branch for the patch.
4. Include a unit test (or tests) that demonstrate the bug (i.e., that fail without your patch, but passes with your patch).
5. All existing unit tests must continue to pass.
6. Submit a pull request, using the relevant pull request template for bug fixes, and link to the corresponding Issue.

## New Features and Other Contributions

If you would like to contribute new features and functionality, then follow the 
following procedure:
1. If the feature that you want to add doesn't have an existing Issue, then start with the [Feature Requests](#feature-requests) section above.
2. Fork the repository.
3. Create a branch for the feature.
4. Implement the new functionality.
5. Include unit tests that thoroughly test the new functioality.
6. All existing unit tests must continue to pass.
7. Submit a pull request, using the relevant pull request template for new features, and link to the corresponding Issue.

