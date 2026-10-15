## 自动变基失败

`custom` 分支无法自动变基到最新的 `main`，可能存在冲突。

请手动处理：

1. `git checkout custom`
2. `git fetch origin main`
3. `git rebase origin/main`
4. 解决冲突后 `git push --force-with-lease origin custom`