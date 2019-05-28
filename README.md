# frpc for unas

```bash
docker run -d \
--name frpc \
--net=host \
--restart always \
-v frpc_app:/frp \
dhso/unas-fprc:latest
```