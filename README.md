# Ape Framework development stack

[Ape Framework](https://github.com/ApeFramework) development stack using [Docker Compose](https://docs.docker.com/compose).

| Service | Description   | Docker URL       | Local URL                               |
| ------- | ------------- | ---------------- | --------------------------------------- |
| Node.js | Dev container | `node:3000-3009` | [localhost:3000](http://localhost:3000) |

## Development

Deploy stack:

```
docker compose up
```

Get a Node.js container shell:

```
docker compose exec node bash
```
