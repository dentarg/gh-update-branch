# Overview

GitHub CLI extension to:

> Updates the pull request branch with the latest upstream changes by merging HEAD from the base branch into the pull request branch.

Usage:

```bash
# Install it
gh extension install dentarg/gh-update-branch

# Update it
gh extension upgrade dentarg/gh-update-branch

# Use it in your repo
gh update-branch <number>
```

This extension uses on the [`/repo/{owner}/{repo}/pulls/{number}/update-branch` API endpoint](https://docs.github.com/en/rest/pulls/pulls?apiVersion=2022-11-28#update-a-pull-request-branch).
