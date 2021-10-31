# README.md

## Setup

```shell
cp .envrc_ .envrc # and set role
direnv allow
```

## Deploy

```shell
GOOS=linux go build -o main
lambroll deploy
```
