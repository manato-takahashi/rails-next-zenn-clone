# rails-next-zenn-clone
[【独学ポートフォリオ開発応援】実務未経験から学べる！Rails×Next.js×AWSハンズオン解説](https://zenn.dev/ddpmntcpbr/books/rna-hands-on)

## 環境構築
```terminal
docker compose up -d
```
### Rails（Backend）
Railsコンテナに入り、Railsサーバーを起動
#### Mac
```terminal
docker compose exec rails /bin/bash
```
#### Windows
```terminal
docker compose exec rails bash
```
```terminal
rails s -b '0.0.0.0'
```
### Next（Frontend）
Nextコンテナに入り、開発者サーバーを起動
#### Mac
```terminal
docker compose exec next /bin/bash
```
#### Windows
```terminal
docker compose exec next bash
```
```terminal
npm run dev
```
## Prettier ESLint
本プロジェクトではPrettier（単体）ではなくPrettier ESLintの拡張機能の方を用いる
VSCodeを使用している場合は、Prettier ESLintの拡張機能をインストールし、設定のdefault fomatterをPretteir ESLintにする