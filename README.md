[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

# POC Automated releases

## Configure git repository
1. [x] Install and configure commitlint/conventional changelog for repo
1. [x] (Optional, opinionated but very nice) Install and configure commitizen for repo

## Configure remote
1. [ ] Set up a 'build' workflow
1. [ ] Set up a 'release' workflow for all merges into 'main'
    - Workflow must run semantic-release to generate changelog, bump package version, tag the commit, and publish to npm (github for now)
1. [ ] Get release workflow to bump package version with `@semantic-release/git`
