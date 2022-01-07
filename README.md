# lambda2022

- commit1 from hsk
- commit2 from hskstudy

- `git remote add upstream git://github.com/hskstudy/lambda2022.git`

- `git branch -a` で upstream リポジトリの確認

```
$ git branch -a
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```

まず git fetch upstream

```
$ git fetch upstream
```

次に git merge

git fetch で取得した差分を current branch へ merge させます。

```
$ git merge upstream/main
```
