certbot

# aimerzarashi.com
## step 1
```
docker compose run certbot certonly --manual --preferred-challenges dns-01 --server https://acme-v02.api.letsencrypt.org/directory -m aimerzarashi@gmail.com -d *.aimerzarashi.com
```
## step 2
```
_acme-challenge TXT xxxxxxxxxx
```

# aimerzarashi.online
## step 1
```
docker compose run certbot certonly --manual --preferred-challenges dns-01 --server https://acme-v02.api.letsencrypt.org/directory -m aimerzarashi@gmail.com -d *.aimerzarashi.online
```
## step 2
```
_acme-challenge TXT xxxxxxxxxx
```
