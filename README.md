[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

# POC Automated releases

## Configure git repository
1. [x] Install and configure commitlint/conventional changelog for repo
1. [x] (Optional, opinionated but very nice) Install and configure commitizen for repo

## Configure remote
1. [x] Set up a 'build' workflow
1. [x] Set up a 'release' workflow for all commits to 'main'
    - Workflow must run semantic-release to generate changelog, bump package version, tag the commit, and publish to npm (github for now)
1. [ ] Get release workflow to bump package version - https://github.com/semantic-release/git
1. [ ] Get release workflow to update and commit changelog - https://github.com/semantic-release/changelog
1. [ ] Publish package to npm
1. [ ] Configure release bot for Slack - https://github.com/juliuscc/semantic-release-slack-bot

## Bonus bits
1. [x] Ensure github actions cache node modules
