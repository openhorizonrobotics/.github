# 🧹 Python Linter Workflow

This directory contains the **Python linting workflow** used to ensure code quality and consistency across repositories in the Open Horizon Robotics (OHR) organization.

## 🚀 What It Does

This GitHub Action automatically runs a **Python linter** (using `flake8`) on all `.py` files in your repository. It checks for:

- Syntax errors
- Common coding mistakes
- Style violations (e.g., PEP8)
- Unused imports or variables
- Logical issues like undefined names or variable misuse

The workflow runs **every time you push code or open a pull request** (if configured), and reports any issues in the GitHub Actions tab.

---

## 📋 Example Output

When run, it gives a report like:
![image](https://github.com/user-attachments/assets/a7c8725a-4e94-4b9b-bbf0-c52ba75a2634)

## 🔄 Triggering the Workflow

The workflow can be triggered in one of the following ways:

- Automatically on every push (default)
- Automatically on pull requests (optional)
- Manually from the Actions tab *(if `workflow_dispatch` is enabled)*


## 🔗 How to Reuse in Other Repositories

To use this linter in another OHR repository, simply reference it in your repo's workflow:

Create a file at:  
`openhorizonrobitcs/reponame/.github/workflows/lint.yml`

```yaml
name: Reuse Python Linter

on:
  push:
    paths:
      - '**.py'
  pull_request:
    paths:
      - '**.py'
  workflow_dispatch:

jobs:
  lint:
    uses: openhorizonrobotics/.github/.github/workflows/python-linting.yml@main

