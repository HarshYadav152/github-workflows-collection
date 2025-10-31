# GitHub Workflows Collection

A curated collection of reusable GitHub Actions workflows and automation templates to streamline CI/CD pipelines, code quality checks, and repository maintenance.

## 📋 Table of Contents

- [Overview](#overview)
- [Directory Structure](#directory-structure)
- [Workflows](#workflows)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository provides production-ready GitHub Actions workflows that can be easily integrated into your projects. It includes templates for:

- **CI/CD Pipelines** - Automated testing, building, and deployment
- **Code Quality** - Linting, testing, and coverage analysis
- **Automation** - Issue management, release automation, and reviewer assignment
- **Maintenance** - Dependency updates, stale issue management, and repository upkeep

## Directory Structure

```
workflows/
├── automation/        # Automated tasks (release, reviewer assignment, stale issues)
├── ci-cd/            # Continuous integration and deployment workflows
├── code-quality/     # Code quality checks and analysis
├── maintenance/      # Repository maintenance tasks
└── templates/        # Reusable workflow templates
```

## Workflows

### Automation Workflows
- `auto-assign-reviewers.yml` - Automatically assign reviewers to pull requests
- `release-automation.yml` - Automate release creation and publishing
- `stale-issues.yml` - Close stale issues and pull requests

### CI/CD Workflows
Comprehensive continuous integration and deployment workflows for building and testing projects.

### Code Quality Workflows
Automated code quality checks including linting, formatting, and test coverage analysis.

### Maintenance Workflows
Repository maintenance tasks and automated dependency management.

## Getting Started

1. **Copy a workflow** from this repository to your project's `.github/workflows/` directory
2. **Customize** the workflow for your specific needs
3. **Configure** required secrets and variables in your repository settings
4. **Commit and push** to enable the workflow

### Example

```bash
cp workflows/ci-cd/example.yml your-repo/.github/workflows/
```

## Documentation

For detailed guides and examples, see the `docs/` directory:

- [Common Use Cases](docs/examples/common-use-cases.md) - Real-world workflow examples
- [Script Usage Guide](docs/scripts/script-usage.md) - Helper scripts documentation
- [CI/CD Guide](docs/workflows/ci-cd-guide.md) - Comprehensive CI/CD documentation
- [Helper Scripts](docs/scripts/) - Bash, PowerShell, and Python utilities

### Scripts

Helper scripts are available in:
- `docs/scripts/bash/` - Bash utilities
- `docs/scripts/powershell/` - PowerShell utilities
- `docs/scripts/python/` - Python utilities

## Configuration

### Repository Configuration

Configuration files are located in `config/`:
- `CODEOWNERS` - Define code owners for automatic reviews
- `dependbot.yml` - Configure Dependabot for dependency updates
- `renovate.json` - Configure Renovate for automated dependency management

### GitHub Actions Configuration

Workflow templates and validation:
- `.github/workflows/` - GitHub Actions workflow files
- `.github/ISSUE_TEMPLATE/` - Issue and bug report templates

## Contributing

Contributions are welcome! Please:

1. Follow existing workflow patterns and conventions
2. Add documentation for new workflows
3. Test workflows before submitting
4. Include examples in the pull request

See [CODEOWNERS](config/CODEOWNERS) for more information.

## License

This project is licensed under the terms in the [LICENSE](LICENSE) file.

---

**Questions or Issues?** Check the GitHub Issues or contribute improvements to this collection!