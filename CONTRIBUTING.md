# Contributing to UtilityInsight

First off, thank you for considering contributing to UtilityInsight! It's people like you that make UtilityInsight such a great tool for the utility industry. We welcome contributions from everyone, regardless of their background or level of experience.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How Can I Contribute?](#how-can-i-contribute)
4. [Style Guidelines](#style-guidelines)
5. [Commit Messages](#commit-messages)
6. [Pull Requests](#pull-requests)
7. [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by the [UtilityInsight Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@utilityinsight.com](mailto:conduct@utilityinsight.com).

## Getting Started

- Make sure you have a [GitHub account](https://github.com/signup/free)
- Fork the repository on GitHub
- Clone your fork locally
- Set up the development environment as described in the README.md

## How Can I Contribute?

### Reporting Bugs

- Ensure the bug was not already reported by searching on GitHub under [Issues](https://github.com/utilityinsight/utilityinsight/issues)
- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/utilityinsight/utilityinsight/issues/new)

### Suggesting Enhancements

- Open a new issue with a clear title and detailed description
- Provide specific examples to demonstrate the steps

### Your First Code Contribution

Unsure where to begin contributing to UtilityInsight? You can start by looking through these `good-first-issue` and `help-wanted` issues:

- [Good First Issues](https://github.com/utilityinsight/utilityinsight/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) - issues which should only require a few lines of code, and a test or two
- [Help Wanted Issues](https://github.com/utilityinsight/utilityinsight/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) - issues which should be a bit more involved than `good-first-issue` issues

### Pull Requests

- Fill in the required template
- Do not include issue numbers in the PR title
- Include screenshots and animated GIFs in your pull request whenever possible
- Follow the [Python](#python-styleguide) styleguide
- Document new code based on the [Documentation Styleguide](#documentation-styleguide)
- End all files with a newline

## Style Guidelines

### Python Styleguide

All Python code must adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/). Additionally:

- Use 4 spaces for indentation (not tabs)
- Use docstrings for functions, classes, and modules
- Use type hints for function arguments and return values

### Documentation Styleguide

- Use [Markdown](https://daringfireball.net/projects/markdown/) for documentation
- Reference functions, classes, and modules in markdown using the following syntax:
    ``` markdown
    `ClassName.method_name()`
    `module_name.function_name()`
    `ClassName()`
    ```

## Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

## Pull Requests

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.
2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. The versioning scheme we use is [SemVer](http://semver.org/).
4. You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

## Community

- Join our [Slack channel](https://utilityinsight-community.slack.com)
- Attend our monthly community calls (schedule available on our website)
- Follow us on [Twitter](https://twitter.com/UtilityInsight) for the latest updates

Thank you for your contributions to make UtilityInsight better for everyone in the utility industry!
