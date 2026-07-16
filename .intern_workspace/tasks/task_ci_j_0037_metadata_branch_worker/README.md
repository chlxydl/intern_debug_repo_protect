<!-- METADATA:STATUS=InProgress,ASSIGNEE=intern_ci_j_0037_worker_r1784241583_28278 -->

# task_ci_j_0037_metadata_branch_worker

## Objective
Create `ci_j_repo_mode_worker_artifacts/metadata_branch_worker_note.md` with exactly one line containing `WORKER-METADATA-BRANCH-r1784241583_28278`.

## Focused Validation
Run `test -f ci_j_repo_mode_worker_artifacts/metadata_branch_worker_note.md && grep -F 'WORKER-METADATA-BRANCH-r1784241583_28278' ci_j_repo_mode_worker_artifacts/metadata_branch_worker_note.md` and append `VALIDATION_PASS ci_j_repo_mode_worker_artifacts/metadata_branch_worker_note.md WORKER-METADATA-BRANCH-r1784241583_28278` to history only after it succeeds.

## PR/MR And Authorization
- Create a task branch, commit and push the target change, and open a real PR/MR.
- Target `master`.
- Record the PR/MR URL in worker status and history as `PR_OPENED <url>`.
- Do not merge before an explicit Feishu authorization message.
- After authorization, merge the PR/MR, append `MERGE_COMPLETE <url>` to history, mark this task Completed, and return the intern to Idle.

## Bounds
- Do not package, deploy, install a VSIX, restart services, or run full CI.
- Do not claim completion from a message id, remote status, or prompt echo.
