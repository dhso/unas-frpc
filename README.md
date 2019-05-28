# frpc for unas

```bash
docker run -d \
--name frpc \
--net=host \
--restart always \
-v frpc_app:/app \
dhso/unas-frpc:latest
```