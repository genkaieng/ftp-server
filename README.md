# FTPサーバー

Dockerコンテナで手っ取り早くFTPサーバーを立ち上げ

## Usage

### 環境変数の設定

.env.exampleをコピーして、適宜必要なら設定を変える

```sh
cp .env.example .env
```

### FTPサーバー立ち上げ

```sh
docker compose up
```

### 完了

あとは適宜FTPクライアントで接続
