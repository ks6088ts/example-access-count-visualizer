# Prerequisites
- Docker

# Steps

1. Create `.env` file in the repository root as you want.

```bash
cp .env.sample .env
```

2. Create `shared-network` as follows

```bash
docker network create shared-network
```

3. Run services
```bash
docker-compose up -d
```

# References

- [Nginx のアクセスカウントを Fluentd を使って Grafana で可視化する](https://zenn.dev/ks6088ts/articles/20210326-docker-compose-services)
