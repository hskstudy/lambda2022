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
  remotes/upstream/main
```

- git fetch で差分を取得し git merge upstream/main で current branch へ merge させます。

```
$ git fetch upstream
$ git merge upstream/main
```
