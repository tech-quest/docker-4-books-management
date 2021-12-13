# 🐳

## 環境構築

### 1. 「docker-4-books-manager」リポジトリをテンプレートとして、自身のGithubに「books_manager」リポジトリを作成

### 2. ローカルにcloneする

### 3. 「Dockerの起動」と「Laravelのインストール」

```bash
$ make create-project # Install the latest Laravel project
```

### 4. Laravelがインストールできているか確認

http://localhost

### 5. 「.env」ファイルの作成

1. 「.env.example」をコピし、「.env」ファイルを作成
2. 下記のように「DB_NAME」と「DB_USER」を書き換えましょう

※ 「backend/.env.example」ではないので注意してください

```bash
WEB_PORT=80
DB_PORT=3306
DB_NAME=books_manager
DB_USER=tech_quest
DB_PASS=secret
```
