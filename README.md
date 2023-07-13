# Backend

## 環境構築

.envファイルを作成して以下のようにしてください
```
POSTGRES_USERNAME=postgres
POSTGRES_PASSWORD=<自身のpgAdminに入るときのパスワード>
POSTGRES_DATABASE_NAME=Tech_Calendar
```

### パッケージインストール
```bash
bundle install
```

### データベース作成
pgAdminにてTech_Calendarというデータベースを作成してください

### マイグレーション
```bash
rails db:migrate
```

### サーバー起動
```bash
rails s
```