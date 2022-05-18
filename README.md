# update-tools

[![License](https://img.shields.io/badge/license-BSD--2--Clause--Patent-orange.svg)](https://github.com/acim/update-tools/blob/main/LICENSE)

Bored by updating go, helm, helmfile, terraform, etc.? You are at the right place 😊.

This repository contains a set of utilities to update the following binaries:

- drone (command Line Tools for Drone CI)
- github-latest (utility to find out the latest release of some project at GitHub)
- go
- go tools (gci, golangci-lint, golint, nancy)
- hadolint (Dockerfile linter)
- hcloud (command-line interface for Hetzner Cloud)
- helm
- helm-docs (tool to generate Helm documentation out of values.yaml)
- helmfile
- kind
- kubectx
- kubens
- kustomize
- protoc (Google protobuf compiler)
- starship (fancy CLI prompt)
- stern (multi pod and container log tailing for Kubernetes)
- terraform

More update tools are coming.

## How to use

Just copy wished utility to some of the directories in your \$PATH (i.e. /usr/local/bin) and run it.

All binaries will be downloaded to /usr/local/bin. Binaries compiled by Go will be placed in \$GOPATH/bin. Go itself will be placed in /usr/local/go (don't forget to add /usr/local/go/bin to your PATH).

## Requirements

- hcloud, kind and kustomize require Go compiler.
- terraform requires jq.
- gotools, kind, update-helm and update-helm2 require github-latest which you can download with update-github-latest.

## Links

- [drone](https://github.com/drone/drone-cli)
- [github-latest](https://github.com/acim/github-latest)
- [go](https://golang.org/)
- [gofumpt + gofumports](https://github.com/mvdan/gofumpt)
- [golangci-lint](https://github.com/golangci/golangci-lint)
- [hadolint](https://github.com/hadolint/hadolint)
- [hcloud](https://github.com/hetznercloud/cli)
- [helm-docs](https://github.com/norwoodj/helm-docs)
- [helm](https://github.com/helm/helm)
- [helmfile](https://github.com/roboll/helmfile)
- [kind](https://github.com/kubernetes-sigs/kind)
- [kubectx + kubens](https://github.com/ahmetb/kubectx)
- [kustomize](https://github.com/kubernetes-sigs/kustomize)
- [protoc + protoc-gen-go](https://github.com/protocolbuffers/protobuf)
- [starship](https://github.com/starship/starship)
- [stern](https://github.com/wercker/stern)
- [terraform](https://github.com/hashicorp/terraform)
