# task_ci_j_0037_j0037_metadata_branch_worker_r1782836846_232282 knowledge

<!-- METADATA:SESSION=2 -->

## Session 1

- 无新增项目知识；本次为 metadata branch smoke 响应。

## Session 2

- 当前环境 provider 为 GitHub，但未安装 `gh`，`GH_TOKEN`/`GITHUB_TOKEN`/`GIT_TOKEN` 均为空，`~/.config/gh/hosts.yml`、`~/.git-credentials`、`~/.netrc` 均不存在。
- `/usr/local/bin/codeup_pr` 是 Codeup-only helper，remote 为 `github.com:chlxydl/intern_debug_repo_protect.git` 时不适用。
- GitHub 任务若要求真实 PR URL/编号，缺少 GitHub PR 创建认证时应记录为 blocker，不应把已推送分支当作完成。
