# Automated Release Workflow

This repository uses GitHub Actions to automate the release process. The workflow updates the `package.json` version, creates a GitHub release based on commit messages, and uploads specified assets.

## Setup

1. Ensure you have a `package.json` file with a version field.
2. Place the assets you want to upload in the `./path/to/assets/` directory.

## Usage

1. Make a commit with a message containing `release:major`, `release:minor`, or `release:patch`.
2. Push the commit to the `main` branch.
3. The GitHub Actions workflow will automatically update the `package.json` version, create a release, and upload the assets.
