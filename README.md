# FuelRoi defaults

Org-wide defaults that every FuelRoi repository uses automatically.

**This repository is public by design.** GitHub only applies these defaults from a public `.github` repo.
Never put secrets, internal notes, or SOPs here. Those live in the private `handbook` repo.
CI is not here either: it's enforced org-wide from the private `workflows` repo.

## What's here

| Path | What it does |
|---|---|
| `ISSUE_TEMPLATE/feature.yml` | Feature issue form. Sets type Feature, adds to the Work board |
| `ISSUE_TEMPLATE/slice.yml` | Slice issue form. Sets type Slice, adds to the Work board |
| `ISSUE_TEMPLATE/task.yml` | Task issue form. Sets type Task, adds to the Work board |
| `ISSUE_TEMPLATE/bug.yml` | Bug issue form. Sets type Bug, adds to the Work board |
| `ISSUE_TEMPLATE/config.yml` | Turns off blank issues; links to the SOP and Work board |
| `pull_request_template.md` | Default PR description with `Fixes #` and the pre-merge checklist |

## Rules
- A repo with its **own** `.github/ISSUE_TEMPLATE` folder ignores these templates entirely. Only add one if a repo truly needs different templates.
- Templates add issues to the Work board only when the author has **Write** access to the project.
- Change these files through pull requests, like any other process change.
