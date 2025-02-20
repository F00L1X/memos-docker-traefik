# memos-docker-traefik
This repo contains a dockerized Memos project which runs behind a traefik proxy

Set up this variables, from a .env file or pipevars, doesn´t matter:
```
APP_NAME=memos
APP_DOMAIN=.yourdomain.com
USER_NAME=your_username
USER_PASSWORD=your_password
MEMOS_MODE=prod
MEMOS_DOMAIN=${APP_NAME}${APP_DOMAIN}
MEMOS_ADDR=0.0.0.0
MEMOS_PORT=5432
```

Credits to: 
[neosmemo](https://hub.docker.com/r/neosmemo/memos)
[Use Memos](https://github.com/usememos/memos)
