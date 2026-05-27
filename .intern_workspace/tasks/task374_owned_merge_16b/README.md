# task374_owned_merge_16b

<!-- METADATA:STATUS=Open,ASSIGNEE= -->

## 背景

主管要求在 intern_debug_repo_protect 仓库新增一个 marker 文件，用于 owned merge smoke 验证。

## 任务目标

在仓库根目录新增 `task374_owned_merge_16b.txt`，并写入一行：

```text
owned merge smoke
```

## 验收标准

- 仓库根目录存在 `task374_owned_merge_16b.txt`。
- 文件内容只包含一行 `owned merge smoke`。
- 代码修改通过任务分支和 PR 流程提交，不直接 push 代码默认分支或目标分支。
