---
name: commit-work
description: Commit any changes made to the current git branch
---

Review all uncommitted changes with `git diff`.
Write a conventional commit message summarizing the changes.
Group related changes into a single commit.
Run `go test -race ./...` first — if tests fail, fix them before committing.
Stage and commit. Do not push.
