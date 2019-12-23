# update-tools

[![GitHub](https://img.shields.io/github/license/acim/update-tools)](LICENSE)

Bored by updating helm, kubectx, starship and similar utilities? You are at the right place 😊.

This repository contains a set of utilities to update the following binaries:

* helm
* helm3 (helm 2 is named helm2 to be able to coexist with the new version 3)
* helmfile
* kubectx
* kubens
* starship
* stern
* update-github-latest (required to update helm2 and helm)

More update tools are coming.

## How to use

Just copy wished utility to some of the directories in your $PATH (i.e. /usr/local/bin) and run it.

All binaries will be downloaded to /usr/local/bin.

## Requirements

* update-helm and update-helm3 require github-latest which you can download by update-github-latest.

## Links

* [helm2 + helm](https://github.com/helm/helm)
* [helmfile](https://github.com/roboll/helmfile)
* [kubectx + kubens](https://github.com/ahmetb/kubectx)
* [starship](https://github.com/starship/starship)
* [stern](https://github.com/wercker/stern)
* [update-github-latest](https://github.com/acim/github-latest)
