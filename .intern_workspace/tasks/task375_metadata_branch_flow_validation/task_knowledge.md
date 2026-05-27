# task375_metadata_branch_flow_validation - Task Knowledge

<!-- METADATA:SESSION=3 -->

## Knowledge Entries

- Task is created in metadata_branch mode; code changes must use a task branch and PR rather than direct push to default or target branches.
- Session 2 environment has `gh` installed and authenticated; PR creation can use `gh pr create`.
- After explicit supervisor approval, PR merge can use `gh pr merge <number> --squash`; for PR #11 this fast-forwarded local `master` to merge commit `3ba405d`.
