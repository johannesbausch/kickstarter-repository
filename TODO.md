# TODO


## Linting

Set up a linting configuration file that incorporates your project's specific linting rules. This ensures consistent code quality across all contributors and helps avoid common programming mistakes. You can configure tools like ESLint for JavaScript, Pylint for Python, or Stylelint for CSS.


## Commitlint

Create a commitlint configuration file with custom rules to enforce a clear and consistent commit message format. This ensures that all commits follow a standardized format, making it easier to understand the history and intentions of each change. Popular commit message formats include Conventional Commits.

### Pre-Commit Hooks

Run these linters before committing changes to the repository.

If your project uses JavaScript, tools like Husky can help automate this process. Most tech stacks provide similar support, enabling you to execute linting and commit checks automatically before each commit is finalized. This ensures that code quality checks are applied consistently.


## deploy.yml

In this step, you will create a CI/CD pipeline using GitHub Actions that automates your deployment process. You can trigger this pipeline on events like pushing to the main branch or manually. The deploy.yml file defines the entire deployment process, including code checkout, dependency installation, building, and publishing the project.

For more details, check the official GitHub Actions documentation on workflows and actions:

https://docs.github.com/en/actions


## pull_request.yml

This file defines a workflow that triggers when a pull request is opened, synchronized, or closed. It can be used to automate checks (e.g., testing, linting) before merging changes into the main branch. Using this workflow ensures that all pull requests pass through the necessary checks before merging.

For more details, refer to the GitHub Actions pull request events documentation:

https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#pull_request


## pull_request-opened.yml

This file defines a GitHub Actions workflow that triggers only when a pull request is opened. It can be used to run checks specific to the opening of a PR, such as validation, unit tests, or ensuring all required labels are present.

For more details, refer to the GitHub Actions workflow configuration for pull request events:

https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#pull_request-opened
