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

# 発展課題（headerを作成する際の流れ）
1 issue > タスク管理から私のコメントを編集し、タスクを追加しましょう。

タスク名は`<your name>-headerの作成`にしてください。

<img width="926" alt="スクリーンショット 2024-12-19 13 45 33" src="https://github.com/user-attachments/assets/0fe15ed3-37ac-4fb4-8e8f-9d1c027b9e51" />

2 右側をホバーするとボタンが出てくるので、クリックしてください。

<img width="979" alt="スクリーンショット 2024-12-19 13 48 45" src="https://github.com/user-attachments/assets/c60bb87b-7e3b-41c7-951b-f9f1eddab2ba" />

クリックすると自分のタスクのissueが作成されます。

<img width="1267" alt="スクリーンショット 2024-12-19 13 49 27" src="https://github.com/user-attachments/assets/0f72f276-51e2-4d82-a76f-33b3638d50d6" />


3 作業するために自分の名前でブランチを切ろう

```
$ git switch -c feat/<your-name>/header
```

4 `src`ディレクトリに`<your name>-header.md`ファイルを作成

ファイルの中には自分の`heeader`とわざとスペルミスした文字列を書いてください。

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

8 前のタスクと同様の方法でprを送ります。

今回はprを送る際に`close #<your-issue-number>`と書いてください。これをすることで、指定した番号のissueをマージと同時に閉じることができます。

9 わざと間違えたので、レビューで指摘を受けます。

指摘を受けたら、prを送ったブランチ上でミスを修正し、再度ステージング、コミット、プッシュを行います。

その際のコミットメッセージは以下のようにしてください。

```
$ git commit -m "fix: スペルミスを修正"
```

10 すでにprは立ててあるので、もうprは送る必要はありません。

「LGTM」が帰ってきたら、前のタスク同様に、マージを行なってください。

11 マージ後は自分のタスクがクローズしていることをissueから確認してください。




