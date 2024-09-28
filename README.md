# Ape Framework development stack

Development stack for [Ape Framework](https://github.com/ApeFramework) using [Docker Compose](https://docs.docker.com/compose).

| Service | Description   | Docker URL       | Local URL                               |
| ------- | ------------- | ---------------- | --------------------------------------- |
| Node.js | Dev container | `node:3000-3009` | [localhost:3000](http://localhost:3000) |

## Development

Deploy stack:

```
docker compose up
```

Get a shell from the Node.js container:

```
docker compose exec node bash
```
