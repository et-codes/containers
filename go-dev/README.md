# go-dev

Basic configuration for Go development using VS Code dev containers. Simply copy the `.devcontainers` directory to the root directory of your project, and restart in container when prompted by VS Code.

Alternatively, use the Dockerfile alone to run a container without using VS Code:
- Start the container: `docker compose up -d`
- Run the bash shell:  `docker compose exec go-dev bash`
- Stop the container:  `docker compose down`

Container features:
- Go binaries
- golangci-lint

VS Code extensions:
- Go
- Eslint
- Makefile
