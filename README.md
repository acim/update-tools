# update-tools

[![GitHub](https://img.shields.io/github/license/acim/update-tools)](LICENSE)
[![HitCount](http://hits.dwyl.com/acim/update-tools.svg)](http://hits.dwyl.com/acim/update-tools)

Bored by updating go, helm, helmfile, terraform, etc.? You are at the right place 😊.

This repository contains a set of utilities to update the following binaries:

* drone (command Line Tools for Drone CI)
* github-latest (utility to find out the latest release of some project at GitHub)
* go
* hcloud (command-line interface for Hetzner Cloud)
* helm (Helm 3)
* helm2
* helmfile
* kind
* kubectx
* kubens
* kustomize
* starship
* stern (multi pod and container log tailing for Kubernetes)
* terraform

More update tools are coming.

## How to use

Just copy wished utility to some of the directories in your $PATH (i.e. /usr/local/bin) and run it.

All binaries will be downloaded to /usr/local/bin. Binaries compiled by Go will be placed in $GOPATH/bin. Go itself will be placed in /usr/local/go (don't forget to add /usr/local/go/bin to your PATH).

## Requirements

* hcloud, kind and kustomize require Go compiler.
* terraform requires jq.
* update-helm and update-helm2 require github-latest which you can download by update-github-latest.

## Links

* [drone](https://github.com/drone/drone-cli)
* [github-latest](https://github.com/acim/github-latest)
* [go](https://golang.org/)
* [hcloud](https://github.com/hetznercloud/cli)
* [helm2 + helm](https://github.com/helm/helm)
* [helmfile](https://github.com/roboll/helmfile)
* [kind](https://github.com/kubernetes-sigs/kind)
* [kubectx + kubens](https://github.com/ahmetb/kubectx)
* [kustomize](https://github.com/kubernetes-sigs/kustomize)
* [starship](https://github.com/starship/starship)
* [stern](https://github.com/wercker/stern)
* [terraform](https://github.com/hashicorp/terraform)
