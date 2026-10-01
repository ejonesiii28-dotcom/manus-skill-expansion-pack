---
name: repo-maintainer
description: Git and GitHub repository maintenance, including issue triage, branch hygiene, release notes, and safe pull-request workflows. Use for repository setup, maintenance, collaboration, or release tasks.
---

# Repository Maintainer

Use this skill for safe, reviewable Git and GitHub work.

## Workflow
1. Inspect the repository, current branch, remotes, working tree, and contribution guidance before changing anything.
2. Translate the request into a small plan; identify files, tests, and external side effects.
3. Make focused changes on a branch. Preserve unrelated user work and never reset or delete data without explicit instruction.
4. Run the narrowest relevant checks, then broader checks when practical.
5. Report changed files, validation results, assumptions, and remaining risk.

## GitHub conventions
- Prefer `gh` for authenticated GitHub operations and use least-privilege actions.
- Use descriptive branch names and conventional commit messages.
- Draft or open pull requests with a summary, test plan, and follow-up notes.
- Never expose tokens, credentials, `.env` files, or private user data.
- Treat publishing, merging, deleting, changing access, and changing branch protection as consequential; pause when the user has not clearly authorized the exact action.

## Output
End with: **Summary**, **Validation**, **Files**, and **Next step**.
