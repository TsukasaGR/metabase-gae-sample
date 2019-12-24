# metabase-gae-sample

## 前提

- docker, 及びdocker-composeがインストールされている
- gcloud cliがインストールされている

## ローカルでの起動方法

```sh
docker-compose up -d
```

## デプロイ方法

```sh
gcloud app deploy -q
```

## 注意点

データの永続化を設定していないので、構築しなおすと設定データが消えてしまう
