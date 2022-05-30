# vscode-dev-containers

My dev-containers for GitHub Codespaces.

| Name | Description |Base|image|
|------|-------------|---|-----|
|`tex`|With texlive-full|`mcr.microsoft.com/vscode/devcontainers/base:ubuntu`|`caomingjun/devcontainer:tex`|
|`wrangler`|Nodejs16 with Cloudflare Wrangler2|`mcr.microsoft.com/vscode/devcontainers/javascript-node:16-bullseye`|`caomingjun/devcontainer:wrangler`|

The `Dockerfile` is for building and you don't need it. You can just grab `devcontainer.json` and use it in your repo.