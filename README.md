# インストールしたら
```
docker compose up -d --build
# buildが終わったら
docker compose ps
# serviceが3つ出てきたらOK
docker compose exec app bash
composer create-project --prefer-dist cakephp/app:~5.0 .
```
http://localhost:8081/　にアクセス
