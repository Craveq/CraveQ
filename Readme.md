# Commit and Pull Request Guidelines

## Table of Contents

- [Commit Message Format](#commit-message-format)
  - [Types](#types)
  - [Scopes](#scopes)
  - [Description](#description)
  - [Examples](#examples)
- [Pull Request Format](#pull-request-format)
  - [Title](#title)
  - [Description](#description-1)
  - [Sections to Include](#sections-to-include)

## Commit Message Format

A commit message should follow this conventional format:

```
<type>(<scope>): <description>
```

### Types

The types of commits are:

- `feat`: New feature
- `fix`: Bug fix
- `chore`: Routine tasks and maintenance
- `docs`: Documentation changes
- `style`: Code formatting or style updates
- `test`: Adding or modifying tests

### Scopes

The scope could be anything specifying the place of the commit change. For example, `auth`, `user`, `repo`, etc.

### Description

The description is a short explanation (ideally under 100 characters) of the changes in the commit.

### Examples

- `feat(auth): implement JWT authentication`
- `fix(user): resolve login issue`
- `chore: update dependencies`
- `docs: update README.md`

---

## Pull Request Format

### Title

A short, descriptive title using the `<type>: <short description>` format. For example:

- `feat: Implement JWT authentication`
- `fix: Resolve login issues`

### Description

Your description should provide a detailed explanation of the changes. It may include:

- A brief summary of changes
- How to test the changes
- Any additional steps reviewers need to take to understand or test the code

### Sections to Include

#### Changes

List the major changes that this PR introduces.

#### How to Test

Provide a step-by-step guide on how to test the introduced features or fixes.

#### Commit Messages

List the commit messages included in the PR to provide context for the changes.

#### Folder Structure (if applicable)

Include an overview of the folder structure changes introduced by this PR.

