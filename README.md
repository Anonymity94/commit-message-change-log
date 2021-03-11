# commit-message-change-log

使用 `conventional-changelog-cli` 在约定式提交的几处上生成 `changelog`。

不会覆盖以前任何的日志，基于上次提交生成新的 `changelog`。

```bash
conventional-changelog -p angular -i CHANGELOG.md -s
```

如果是第一次使用该工具，想生成历史所有的 `changelog`，你可以

```bash
conventional-changelog -p angular -i CHANGELOG.md -s -r 0
```

## Links

- [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog)
