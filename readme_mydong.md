## 官方Docker
https://hub.docker.com/r/lanol/filecodebox

## 安装教程
```
docker run -d --restart=always -p 12345:12345 -v /opt/FileCodeBox/:/app/data --name filecodebox lanol/filecodebox:latest
```

## 更新教程
```
docker stop filecodebox && docker rm filecodebox

docker pull lanol/filecodebox:latest

docker run -d --restart=always -p 12345:12345 -v /opt/FileCodeBox/:/app/data --name filecodebox lanol/filecodebox:latest

```
