# Contributing to Project

We are glad you're interested in contributing to our project! Below are the guidelines for contributing to the project. Please read through them before making any contributions.

## How to Contribute

### Bug Request

If you find a bug, please open an issue in the repository and please follow the **Report Bug** issue template.

### Feature Request

If you'd like to propose a new feature, please open an issue and follow the **Feature Request** issue template.

### Submit Pull Requests

If you’d like to submit a fix for an open issue, please feel free to submit a pull request (PR) addressing it. We appreciate your help in fixing the bugs and adding features!

## Submitting Pull Requests

### Title

The PR title should follow the below structure to maintain consistency:

- **<[typeOfCommit](#types-of-commits)>(scope): concise title.** (e.g., `feat(auth): add login functionality.`)

Please make sure the PR title is concise and describes the changes made.

### Description

Please follow the PR template for writing description when submitting a pull request. It will help us understand the changes you have made, and ensure that we can efficiently review and merge your contribution. Failure to follow the template will result in your PR being discarded.

## Commit Discipline

We follow the principle: **“Each commit is a minimal coherent idea”**. This means that a commit should represent a single logical change, and should be atomic — meaning it should only include changes related to that idea.

Adhering to this discipline helps reviewers identify bugs more easily, and also makes the commit history a useful resource for understanding the evolution of the code.

## Setting up Commit Template

Before making your first commit, it is recommended to set up a commit template to help maintain consistency in your commit messages.

Run the following command to configure Git to use the defined commit template for this repository:

```bash
git config --local commit.template .github/.gitmessage
```

### Commit Message Structure

Commit messages are divided into two parts:

1. **Title**: A short description of what was done, prefixed with the type and scope.
2. **Body**: A detailed explanation of the changes made.

#### Commit Title Structure

The commit title should begin with a [type](#types-of-commits), followed by an scope(tells the scope of change), and a concise description of the change.

- **<[typeOfCommit](#types-of-commits)>(scope): concise title.** (e.g., `feat(auth): add login functionality.`)

#### Commit Body

The body should explain the changes made and the reason behind them. It can also reference the issue that is being addressed.
structure of commit body:

```bash
- Description of change 1.
- Description of change 2.

Fixes: #<issue_number>.
```

### Formatting Guidelines

- The commit description should be separated from the title by a blank line.
- Use full sentences with proper punctuation and capitalization.
- Avoid typos, spelling, or grammatical mistakes — commit messages are an important form of technical writing.
- Line-wrap the commit body to around 68 characters per line, but no more than 70.

### Examples

**Example 1:**

```bash
feat(auth): Add login feature.

- Added login page and authentication logic.

Fixes: #1.
```

**Example 2:**

```bash
fix(ui): Correct button alignment.

- Fixed button misalignment on the homepage.

Fixes: #2.
```

## Note

- If the commit message format and template, it will **not** be considered.
- If the PR does not follow the title format and description template, it will **not** be considered.

## Types of Commits

Below are the types of commits that should be used:

- **feat**: A new feature added to the application.
- **fix**: A bug fix or patch for an issue.
- **build**: Changes related to build processes or tools (e.g., package management, bundlers).
- **chore**: Regular maintenance or administrative tasks (e.g., updates to dependencies, refactoring config files).
- **ci**: Updates to the continuous integration setup (e.g., CI pipeline adjustments).
- **docs**: Documentation-related changes (e.g., README updates, inline comments).
- **style**: Changes that do not affect the code’s functionality (e.g., code formatting, removing extra whitespace).
- **refactor**: Code modifications without changing its behavior (e.g., cleaning up functions, restructuring code).
- **perf**: Performance improvements (e.g., optimizing algorithms, reducing load time).
- **test**: Adding or modifying tests (e.g., unit tests, integration tests).
