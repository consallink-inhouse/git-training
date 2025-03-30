## git-training

Git 研修用リポジトリ

### 各ページ

`main` ブランチに変更が加わると下記のページが自動的に更新されます

- [TeamA](https://consallink-inhouse.github.io/git-training/TeamA)
- [TeamB](https://consallink-inhouse.github.io/git-training/TeamB)
- [TeamC](https://consallink-inhouse.github.io/git-training/TeamC)
- [TeamD](https://consallink-inhouse.github.io/git-training/TeamD)

### やること

前提：2 人 1 チーム（以後、`作業者A`、`作業者B` と記載）

1. `作業者A`、`作業者B` のどちらかが、`main` ブランチから `Team{アルファベット}` ブランチを作成する
   1. ブランチ名の `{アルファベット}` には各チームのアルファベットを記載
2. `作業者A`、`作業者B` 共に `1.` で作成したブランチから、自分の名前でブランチを作成する（例：`OhnoKeita`）
3. `作業者A`、`作業者B` 共に `/docs/Team{アルファベット}/index.md` に自己紹介文を書き込む（`2.` で作成したブランチで作業する）
4. `作業者A`、`作業者B` 共に `3.` の内容を `コミット` ＆ `プッシュ` し、リモートリポジトリに反映させる
5. `作業者A`、`作業者B` 共に `4.` の内容で `Pull requests` を作成する（`2.` で作成したブランチから`1.` で作成したブランチにマージするようにする）
6. `作業者A`、`作業者B` 共に、互いの `Pull requests` を確認し、問題なければ `マージ` を行い、`Pull requests` をクローズする
7. 各チームの `URL` を確認する
