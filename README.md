# frpc for unas

```bash
docker run -d \
--name unas-frpc \
--net=host \
--restart always \
-v frpc_app:/app \
dhso/unas-frpc:latest
```