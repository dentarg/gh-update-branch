# Overview

`gh-update-branch` is a GitHub CLI extension that can ping the `update-branch` API.

Usage is very simple: `gh update-branch [<number>]`

This extension depends on the `/repo/{owner}/{repo}/pulls/{number}/update-branch` API:

https://docs.github.com/en/rest/pulls/pulls?apiVersion=2022-11-28#update-a-pull-request-branch
