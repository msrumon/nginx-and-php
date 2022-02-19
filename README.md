# nginx & PHP

I can't make **nginx** work with **PHP**. Here I'm trying to make **nginx** act as a reverse proxy server for **PHP**, but the server crashes with `host not found in upstream "php" in /etc/nginx/conf.d/default.conf:14` error.

## Steps

Run the following command in the terminal:

```bash
docker compose up -d server
```
