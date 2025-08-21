# immichの構築
基本的には[公式ドキュメント](https://immich.app/docs/install/docker-compose/)に従って設定する。

```
mkdir ./immich-app
cd ./immich-app
wget -O docker-compose.yml https://github.com/immich-app/immich/releases/latest/download/docker-compose.yml
wget -O .env https://github.com/immich-app/immich/releases/latest/download/example.env
```

`docker compose up -d`でコンテナを立ち上げることにより`~/immich/library/library/admin/`に`2025/2025-01-01/img.png`のように保存されるようになる。

