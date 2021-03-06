# asdf-helm-git

[helm-git](https://github.com/aslafy-z/helm-git) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

This plugin works slightly differently from other plugins since `helm-git`
itself is not a binary. It also makes an assumption that you have `helm`
installed already, since we exec out into `helm plugin` commands for doing the
actual installation.

## Install

```
asdf plugin-add helm-git https://github.com/istreamlabs/asdf-helm-git.git
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of helm-git.
