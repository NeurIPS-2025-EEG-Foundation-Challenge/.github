# ⚙️ About the .github Repository

This directory contains the configuration files for our GitHub organization, including community health files, issue/pull request templates, and GitHub Actions workflows.

This document serves as a guide for contributors who wish to understand or modify these organizational settings.

##  Directory Structure

- **`/profile`**: Contains the main `README.md` for our public-facing organization profile. This is what visitors see on our main page.
- **`/workflows`**: Contains all GitHub Actions CI/CD workflows.
  - `ci.yml`: Runs tests and linting on every push and pull request.
  - `deploy.yml`: Handles deployment to our staging environment.
- **`/ISSUE_TEMPLATE`**: Contains templates for bug reports, feature requests, etc., that appear when a new issue is created.
- **`PULL_REQUEST_TEMPLATE.md`**: The default template that populates the description field when a new pull request is opened.
- **`CONTRIBUTING.md`**: Guidelines for contributing to our projects.
- **`SECURITY.md`**: Our security policy and instructions for reporting vulnerabilities.

## How to Propose Changes

If you wish to change a workflow or a template, please open an issue first to discuss the proposed changes with the maintainers.
