# Quick Start

## Way 1: degit

```shell
pnpm i -g degit
degit time1043/docker-compose-starter/postgres/deploy deploy
degit time1043/docker-compose-starter/mysql/deploy deploy
```

## Way 2: Sparse Checkout

```shell
git clone --filter=blob:none --sparse \
https://github.com/time1043/docker-compose-starter.git

cd docker-compose-starter
git sparse-checkout set postgres
mv postgres/deploy ../deploy
```
