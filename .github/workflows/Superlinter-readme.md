# 🧹 Super-Linter (Reusable Workflow)

This repository provides a **centralized reusable GitHub Actions workflow** to lint and format code across multiple languages using the powerful [Super-Linter](https://github.com/super-linter/super-linter) maintained by GitHub.

---

## 📌 What is Super-Linter?

[Super-Linter](https://github.com/super-linter/super-linter) is a simple combination of multiple linters, written in different programming languages, all wrapped in a Docker container for convenience. It helps enforce consistent code quality across your entire codebase.

It supports linting for:

- 🐍 Python (Black)
- 📄 YAML, Markdown, JSON
- ⚙️ GitHub Actions workflows
- 💻 Shell scripts (shfmt)
- 📦 Dockerfiles (Hadolint)
- 🌐 JavaScript (ESLint)

---

## 🛠️ What This Workflow Does

This workflow:

- Lints code across supported languages
- Automatically commits and pushes auto-fixes for python (e.g., from `black`.)
- Shows inline linting errors directly in GitHub Actions Menu.
- Can be reused in multiple repositories to standardize linting across teams and projects.

---

## 📦 Languages Currently Enabled

You can modify or extend these in the workflow:

- Python: Black, Flake8
- YAML: yamllint
- Markdown: markdownlint
- JSON: eslint, prettier
- GitHub Actions: actionlint
- Shell: shfmt
- Dockerfile: Hadolint
- JavaScript (ES): ESLint

---

## 📋 Example Output

When run, it gives a report like:

<img width="661" alt="image" src="https://github.com/user-attachments/assets/93732fd7-9351-4df1-9c8e-703fa5d6a79b" />

---


## 📁 Reference Structure

To use this linter in another OHR repository, simply reference it in your repo's workflow:

Create a file at:
`openhorizonrobitcs/reponame/.github/workflows/lint.yml`

```yaml
name: Lint Code Base

on:
  push:
    paths:
      - '**/*'
  pull_request:
    paths:
      - '**/*'
  workflow_dispatch:

jobs:
  call-super-linter:
    uses: openhorizonrobotics/.github/.github/workflows/Superlinter.yml@main
