# Branch Naming Convention

We follow a **feature-branch workflow** with `main` and `dev` branches.

## Main Branches
- `main` → Always production-ready. Protected (no direct pushes).
- `dev` → Integration branch for testing features before merging to `main`.

## Feature Branches
For new work, create a branch from `dev`:
- `feature/<short-description>` → for new features
  - Example: `feature/user-dashboard`
  - Example: `feature/issue-reporting`

## Bug Fix Branches
- `fix/<short-description>` → for bug fixes
  - Example: `fix/login-validation`
  - Example: `fix/map-api-bug`

## Hotfix Branches
- `hotfix/<short-description>` → for urgent fixes on `main`
  - Example: `hotfix/broken-navbar`

## Rules
- Always branch from `dev`.
- Open a Pull Request to merge back into `dev`.
- At least **1 reviewer approval** is required before merging.
- Delete feature branches after merge to keep repo clean.
