## casdoor

```
docker run -d \
  --restart always \
  -e driverName=mysql \
  -e dataSourceName='user:password@tcp(x.x.x.x:3306)/' \
  -p 8000:8000 \
  ghcr.io/linxiqt/casdoor
```

默认后台用户名密码
```
admin
123
```
