# githubproxy
```
docker run -d --name php-epg -v /etc/epg:/htdocs/data -p 5678:80 --restart always -e TZ=Asia/Shanghai taksss/php-epg:latest
