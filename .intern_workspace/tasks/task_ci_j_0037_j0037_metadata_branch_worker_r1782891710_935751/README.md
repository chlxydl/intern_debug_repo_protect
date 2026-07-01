# task_ci_j_0037_j0037_metadata_branch_worker_r1782891710_935751

<!-- METADATA:STATUS=Open,ASSIGNEE=intern_ci_j_0037_j0037_worker -->

## Goal
Create `ci_j_0037_worker_artifacts/metadata_branch_worker_note.md` with marker `WORKER-METADATA-BRANCH-J0037-r1782891710_935751`.

## Validation
`test -f ci_j_0037_worker_artifacts/metadata_branch_worker_note.md && rg 'WORKER-METADATA-BRANCH-J0037-r1782891710_935751' ci_j_0037_worker_artifacts/metadata_branch_worker_note.md`

## PR/MR Strategy
Use the normal task branch and PR/MR flow.
Target branch: `master`.
Open a PR/MR after the task change and keep it unmerged until the supervisor sends a visible merge approval.
A real provider PR/MR URL or PR/MR number is required before reporting implementation done.
Provider CLI/token failure is a blocker for this task: do not record `PR=N/A`, `gh unavailable`, `token unavailable`, or `branch pushed but no PR/MR` as success.
Record the PR/MR URL or number in worker status and task metadata after creation.
After merge approval, merge the PR/MR, then mark this task Completed and return the worker to Idle.

## Boundaries
Do not run package, deploy, bootstrap, VSIX install, hook install, relay restart, or full CI for this case-scoped task.

## Evidence
Report the changed file, marker, and validation command result.
