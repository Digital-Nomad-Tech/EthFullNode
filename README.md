# EthFullNode


## Before you start
```
mkdir -p jwtsecret
openssl rand -hex 32 | tr -d "\n" > jwtsecret/jwt.hex
```

modify `extip`:
```
--nat "extip:<change-to-your-server-ip>"
```

## Start
```
docker-compose up -d
```

## Check Sync States
```
./eth_syncing.sh
```
