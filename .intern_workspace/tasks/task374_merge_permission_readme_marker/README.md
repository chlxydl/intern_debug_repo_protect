# task374_merge_permission_readme_marker

<!-- METADATA:STATUS=InProgress,ASSIGNEE=intern_task374_meta_e2e -->

## 背景

主管要求验证 intern 必须在获得明确允许后，自己执行 merge 流程。

## 任务目标

通过一个最小 README marker 变更验证完整流程：创建任务、任务分支提交、PR、等待主管明确允许后由 intern 自己执行 merge。

## 验收标准

- 代码变更仅包含一个最小 README marker。
- 变更通过任务分支和 PR 提交，不直接 push 默认分支。
- 在主管明确允许 merge 后，由 intern 自己执行 merge 流程。
- merge 完成后，任务 metadata 收尾为 Completed。
