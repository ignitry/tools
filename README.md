# Tools

List of various softwares use in Development.

-----

-  ~~Docker~~ (to be removed)
    - ~~Redis - Latest [`redismod`](https://github.com/RedisLabs/redismod) image~~
- Caddy 2.8.4
- Meilisearch 1.8
- Gotenberg 8
- [Faktory](#Faktory)

----
## Faktory

Refer to `docker run` command in [official docs](https://github.com/contribsys/faktory/wiki/Installation#docker)

### env

```sh
FAKTORY_PASSWORD=some_password
NETWORK_PORT=7419
WEBUI_PORT=7420
```

### volumes

```md
- ./data
```
