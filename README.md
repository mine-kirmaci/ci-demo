# CI Demo 

A simple Node.js project demonstrating Continuous Integration using GitHub Actions.

## Tech Stack
- Node.js
- Jest
- GitHub Actions

## Workflow
1. Create a feature branch
2. Open a Pull Request to `main`
3. CI runs tests automatically
4. Merge is allowed only if tests pass

## Branch Protection
- Pull request required
- Status checks must pass
- Direct pushes to `main` are blocked

## Purpose
To prevent broken code from being merged into the `main` branch.
