# `Devlake` with `Grafana` Dora dashboard


## Installation 

1. generate new ENCRYPTION_SECRET 
```
openssl rand -base64 2000 | tr -dc 'A-Z' | fold -w 128 | head -n 1
```

2. config `.env` 


3. run 
```
docker compose up -d
```
