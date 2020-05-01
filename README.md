# update-tools

[![GitHub](https://img.shields.io/github/license/acim/update-tools)](LICENSE)
[![HitCount](http://hits.dwyl.com/acim/update-tools.svg)](http://hits.dwyl.com/acim/update-tools)

Bored by updating helm, kubectx, starship and similar utilities? You are at the right place 😊.

This repository contains a set of utilities to update the following binaries:

* drone (command Line Tools for Drone CI)
* github-latest (utility to find out the latest release of some project at GitHub)
* hcloud (command-line interface for Hetzner Cloud)
* helm (Helm 3)
* helm2
* helmfile
* kubectx
* kubens
* starship
* stern (multi pod and container log tailing for Kubernetes)
* terraform

More update tools are coming.

## How to use

Just copy wished utility to some of the directories in your $PATH (i.e. /usr/local/bin) and run it.

All binaries will be downloaded to /usr/local/bin. Binaries compiled by Go, i.e. hcloud, will be placed in $GOPATH/bin.

## Requirements

* hcloud requires Go compiler.
* terraform requires jq.
* update-helm and update-helm3 require github-latest which you can download by update-github-latest.

## Links

* [drone](https://github.com/drone/drone-cli)
* [github-latest](https://github.com/acim/github-latest)
* [hcloud](https://github.com/hetznercloud/cli)
* [helm2 + helm](https://github.com/helm/helm)
* [helmfile](https://github.com/roboll/helmfile)
* [kubectx + kubens](https://github.com/ahmetb/kubectx)
* [starship](https://github.com/starship/starship)
* [stern](https://github.com/wercker/stern)
* [terraform](https://github.com/hashicorp/terraform)
