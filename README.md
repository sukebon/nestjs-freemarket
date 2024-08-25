## アプリケーションの実行方法

1. `npm i`を実行しライブラリをインストール
2. dockerを起動した状態で`docker compose up -d`でデータベース環境を構築
3. `npx prisma migrate deploy`を実行してマイグレーションを適用
4. `npm run start:dev`でアプリケーションを起動
