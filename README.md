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


1 リポジトリまで行って、新しいPRを作成する

<img width="956" alt="スクリーンショット 2024-12-17 15 58 52" src="https://github.com/user-attachments/assets/53688540-e687-4a01-97e8-a7cf88819ac1" />

2 どんな作業をしたか、詳細を記載

<img width="974" alt="スクリーンショット 2024-12-17 15 59 28" src="https://github.com/user-attachments/assets/ce32b0f2-a927-4171-b50a-d0840cfe0627" />


3 PRを出し、「LGTM」が帰ってきたらマージする

<img width="939" alt="スクリーンショット 2024-12-17 16 04 20" src="https://github.com/user-attachments/assets/2d08866c-50ce-40a3-92d8-455e8d1ef5d9" />
<img width="953" alt="スクリーンショット 2024-12-17 16 07 03" src="https://github.com/user-attachments/assets/2ba6d089-36f6-401c-b7f6-9be0b524a9cb" />
<img width="963" alt="スクリーンショット 2024-12-17 16 07 59" src="https://github.com/user-attachments/assets/15a29d79-6fde-457f-bf03-a57a42069894" />


4 vscodeのターミナルに戻り、コマンドで`main`ブランチに移動

```
$ git switch main
```

5 `main`でリモードをpullする

```
$ git pull
```

# 発展課題
1 issue > タスク管理からタスクを作成しましょう。



