# .github

This repository contains organization-wide GitHub metadata and optional starter workflows for common technology stacks. It is not an application repository.

## Optional starter workflows

The templates in `workflow-templates/` are editable examples for application repositories. They run only after a repository adopts a template, and can be customized or removed by that repository. They are not centrally enforced checks and do not replace the organization's required pull-request workflow, which is maintained separately in `gclhub-actions-demo/required-workflows`. Organization ruleset configuration determines where that workflow is required; this metadata repository is not an application target.

| Workflow | Description |
|----------|-------------|
| **.NET CI** | Build and test .NET applications; uploads coverage and security-scan artifacts. |
| **Java CI** | Build and test Java applications with Maven; uploads test and OWASP dependency-check artifacts. |
| **Node.js CI** | Build and test Node.js applications; uploads npm audit results. |
| **Python CI** | Lint and test Python applications; uploads coverage and security-analysis artifacts. |

### Use a starter workflow

1. In an application repository, open the **Actions** tab and select **New workflow**.
2. Find the organization's starter workflows under **By [Organization Name]** and select **Configure**.
3. Review and tailor the copied workflow for the application's build, tests, and reporting needs, then commit it.

The templates use GitHub's `$default-branch` starter-workflow placeholder so the copied workflow targets the repository's default branch. Their triggers and jobs apply only to the copied workflow; they do not configure rulesets or satisfy the separate centrally required check.