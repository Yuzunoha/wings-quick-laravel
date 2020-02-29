## メモ
- 起動したコンテナに入る
  - `docker-compose exec app ash`
  - ここで `laravel` や `artisan` が使える
  - マウントポイントは `wings-quick-laravel/docker-laravel/src`
    - .envの `PROJECT_PATH=./src` で変えられる
