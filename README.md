# 作業に取り掛かってから、プッシュまで

1 リポジトリを手元でクローンする

```
$ git clone https://github.com/balckowl/git-renshuu.git
```

2 作成された`git-renshuu`をvscodeで開く
3 作業するために自分の名前でブランチを切ろう

```
$ git switch -c feat/<your-name>
```

4 `src`ディレクトリに自分のgithub名で`.md`ファイルを作成

ファイルの中には自分のgithub名を書いてください。


5 ステージングしよう

```
$ git add .
```

6 コミットしよう

```
$ git commit -m "feat: <what-work-did-you-do>"
```

7 リモートにpushする

```
$ git push -u origin <branch-name>
```


# プルリクを送ってから、レビュー、プルまで


1 リポジトリまで言って、新しいPRを作成する

2 どんな作業をしたか、詳細を記載

3 PRを出し、「LGTM」が帰ってきたらマージする

4 以下のコマンドで`main`ブランチに移動

```
$ git switch main
```

5 `main`でリモードをpullする

```
$ git pull
```


