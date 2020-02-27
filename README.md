# wings-quick-laravel
- 速習 Laravel 6 速習シリーズ 山田祥寛

## 使い方
- 起動方法
  - wings-quick-laravel/projects/laradock で
  - `docker-compose up -d nginx mysql workspace`

- laravelを使うコンテナのシェルを起動
  - ホストPCの任意の場所で
  - `docker exec -it laradock_workspace_1 bash`
  - このコンテナは `コンテナの/var/www` が `ホストのwings-quick-laravel/projects` をマウントしている
