# frpc for unas

```bash
docker run -d \
--name unas-frpc \
--net=host \
--restart always \
-v /etc/frpc:/app \
dhso/unas-frpc:latest
```