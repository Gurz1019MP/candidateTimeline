# candidateTimeline
Project for candidate timeline

# 前提環境
Dockerインストール済み

# 起動方法
ホストマシン
```bash
docker compose build
docker compose up -d
docker compose exec app bash
```

Dockerコンテナ内
```bash
bin/rails s
```

ブラウザで以下のURLにアクセス

http://localhost:3000/
