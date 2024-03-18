# docker-compose-atlas-local
A docker compose version of the Atlas CLI for creating atlas locally for dev testing.

## Prerequisites
Docker and Docker Compose installed on your machine.

## Usage
1. Clone the repository
2. Run `docker compose up -d` in the root of the repository
3. Connect to the Atlas instance at `mongodb://localhost:27017?directConnection=true`

## References
- [Atlas CLI Code](https://github.com/mongodb/mongodb-atlas-cli)
  (in particular /internal/cli/atlas/deployments/setup.go) 