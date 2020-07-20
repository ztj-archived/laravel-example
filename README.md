# Laravel 示例

### Sqlite 数据库配置
- 创建数据库文件
- 环境变量
```
DB_CONNECTION=sqlite
DB_DATABASE=database.sqlite
DB_FOREIGN_KEYS=true
```
- 执行迁移
```
php artisan migrate
```

### dingo/api
- https://github.com/dingo/api
- 执行命令
```
composer require dingo/api
php artisan vendor:publish --provider="Dingo\Api\Provider\LaravelServiceProvider"
```

### tymon/jwt-auth
- https://github.com/tymondesigns/jwt-auth
- https://jwt-auth.readthedocs.io/en/develop/
- 执行安装
```
composer require tymon/jwt-auth
php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"
php artisan jwt:secret
```
