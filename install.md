# 安装
```shell
docker-compose -f ./docker-compose.mysql.yml up -d
```

# 初始化数据库 

```shell
export koel_container=koel_koel_1
docker exec --user www-data -it $koel_container bash
# Once inside the container, you can run commands:
php artisan koel:init --no-assets
```


# 初始化默认账号

```shell
docker exec -it $koel_container php artisan koel:admin:change-password
```


