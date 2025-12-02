# .github

This repository contains organization-wide GitHub configurations, including starter workflows for common technology stacks.

## Starter Workflows

The following starter workflows are available for use across the organization. These workflows are designed for financial services applications and include security scanning capabilities.

### Available Workflows

| Workflow | Description |
|----------|-------------|
| **.NET CI** | Build, test, and security scan .NET applications. Includes code coverage and dependency vulnerability scanning. |
| **Java CI** | Build, test, and security scan Java applications with Maven. Includes OWASP dependency vulnerability scanning. |
| **Node.js CI** | Build, test, and security scan Node.js applications. Includes npm audit for dependency vulnerability scanning. |
| **Python CI** | Build, test, and security scan Python applications. Includes Safety and Bandit for security analysis. |

### How to Use

1. Navigate to your repository
2. Click on the **Actions** tab
3. Click **New workflow**
4. Look for the organization's starter workflows under "By [Organization Name]"
5. Click **Configure** on the desired workflow
6. Customize the workflow as needed and commit

### Features

All starter workflows include:
- **Continuous Integration**: Automated build and test on push and pull request
- **Security Scanning**: Dependency vulnerability scanning and code security analysis
- **Artifact Upload**: Test results and coverage reports uploaded as artifacts
- **Multi-version Testing**: Test against multiple runtime versions where applicable