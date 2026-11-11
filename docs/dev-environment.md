# Development environment

How to start the project. This is the page the agent must find when asked
"how do I start the project?".

Write commands exactly as they are typed. If a command differs on Windows,
give both versions.

## Requirements

Docker with Compose and Git. Node 24 and Yarn 4 (via corepack) come from the
image in .docker/; do not install them on the host.

## Start

```
docker compose run --rm --service-ports app sh
```

Inside the container, run the dev server once package.json has scripts
(Vite is not set up yet; the human does it). It will open at
http://localhost:5173, the port compose.yaml publishes.

## Stop

Press Ctrl+C, then `exit`. If a container is left over:

```
docker compose down
```

## Common problems

None recorded yet.
