FROM mcr.microsoft.com/devcontainers/go:1-1.22-bookworm

WORKDIR /workspace
RUN cd /workspace

# Install golangci-lint
RUN curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | \
    sh -s -- -b $(go env GOPATH)/bin v1.56.2

ENTRYPOINT /bin/bash
