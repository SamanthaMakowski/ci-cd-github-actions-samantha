# CI/CD GitHub Actions Pipeline

This project demonstrates a CI/CD pipeline using GitHub Actions.

## Features

- Feature branches are merged into `develop`
- Pull requests to `develop` trigger Cypress tests via GitHub Actions
- Merging `develop` into `main` is configured to trigger deployment to Render via deploy hook

## Current Status

- The GitHub Actions workflows are fully configured and working as intended.
- Due to time constraints and deploy errors, the Render application is not currently deployed.
- Secrets are configured in the GitHub repository to enable deployment.

## GitHub Actions

- `.github/workflows/run-cypress-tests.yml`: Runs Cypress tests on PR to `develop`
- `.github/workflows/deploy-to-render.yml`: Deploys to Render on push to `main`

## GitHub Repository

https://github.com/SamanthaMakowski/ci-cd-github-actions-samantha
