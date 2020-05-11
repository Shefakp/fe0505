# Изучаем git

## 1. Знакомство с Git Commit

- [x] Коммиты в GIT:

```sh
git commit
git commit
```

- [x] Ветвление в Git:

```sh
git checkout -b bugFix
```

или возможен вариант с двумя командами

```sh
git branch bugFix
git checkout bugFix
```

- [x] Ветки и слияния:

```sh
git branch bugFix
git checkout bugFix
git commit
git checkout master
git commit
git merge bugFix
```

- [x] Git Rebase

```sh
git branch bugFix
git checkout bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```