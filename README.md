# caddy2-forwardproxy

```
docker run --restart=always  -d -p 80:80 -p 443:443 \
     -v $PWD/site:/srv \
     -v $PWD/Caddyfile:/etc/caddy/Caddyfile \
     -v caddy_data:/data \
     -v caddy_config:/config \
     luoqeng/caddy2:v2
```
