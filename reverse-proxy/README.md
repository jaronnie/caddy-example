# reverse-proxy

```shell
go install github.com/jaronnie/gnc@latest
gnc -lp 3031,3032,3033
# 反向代理 3031 端口, 可以从 3030 代理到 3031
caddy reverse-proxy --from :3030 --to :3031
```
