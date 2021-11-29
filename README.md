# git--eol-conflicts
模拟merge时有crlf/lf的问题

## 模拟冲突

> 在master分支

```bash
$ git merge -s recursive feature
```

## 模拟不发生冲突

> 在master分支

```bash
$ git merge -s recursive -Xignore-space-at-eol feature
```
