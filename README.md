# lambda2022

このリポジトリは github上での貢献方法を勉強するためのリポジトリです。

## ライセンス

MIT

## 貢献方法

### 1. fork する。

1. github 上 で fork します。
2. fork した git を clone します。

    ```
    git clone git://github.com/hsk/lambda2022.git
    ```

### 2. Pull request する。

1. 変更を加え commit し、push します。
2. github上から `Pull requests` -> `New pull request` -> `Create pull request` -> `Create pull request` とボタンを押して Pull request を送ります。

### 3. Pull request をマージする。

1. `Pull Request` のページを開き、該当する pull requestのページを開きます。
2. 確認して問題なければ `Merge pull request` ボタンを押します。
3. `Confirm merge` ボタンを押します。
4. git pull でマージ結果を取得します。

### 4. fork 元に追従する。

1. fork元を upstream として追加します。(1回だけやれば良い)

    ```
    git remote add upstream git://github.com/hskstudy/lambda2022.git
    ```

2. `git branch -a` で upstream リポジトリの確認します。

    ```
    $ git branch -a
    * main
    remotes/origin/HEAD -> origin/main
    remotes/origin/main
    remotes/upstream/main
    ```

3. git fetch で差分を取得し git merge upstream/main で current branch へ merge させます。

    ```
    $ git fetch upstream
    $ git merge upstream/main
    ```
