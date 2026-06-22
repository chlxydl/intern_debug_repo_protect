# task_ci_j_0037_j0037_metadata_branch_worker

<!-- METADATA:STATUS=Completed,ASSIGNEE=intern_ci_j_0037_j0037_worker -->

## Goal
Create `ci_j_0037_worker_artifacts/metadata_branch_worker_note.md` with marker `WORKER-METADATA-BRANCH-J0037-r1782143866_993860`.

## Validation
`test -f ci_j_0037_worker_artifacts/metadata_branch_worker_note.md && rg 'WORKER-METADATA-BRANCH-J0037-r1782143866_993860' ci_j_0037_worker_artifacts/metadata_branch_worker_note.md`

## PR/MR Strategy
Use the normal task branch and PR/MR flow.
Target branch: `master`.
Open a PR/MR after the task change and keep it unmerged until the supervisor sends a visible merge approval.
After merge approval, merge the PR/MR, then mark this task Completed and return the worker to Idle.

## Boundaries
Do not run package, deploy, bootstrap, VSIX install, hook install, relay restart, or full CI for this case-scoped task.

## Evidence
Report the changed file, marker, and validation command result.
