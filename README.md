# dockur-compose

## Prerequisites

```bash
apt install docker-compose
```

## Howto

Spin up new Windows 11 Enterprise container:

```bash
docker-compose -f windows11e.yml up
```

Ref: https://github.com/dockur/windows

## RDP

```bash
mstsc /v:localhost:8008
```
