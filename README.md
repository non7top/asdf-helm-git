# asdf-helm-git

[helm-git](https://github.com/aslafy-z/helm-git) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```shell
asdf plugin add helm-git https://github.com/vberezhnoi/asdf-helm-git.git
```

## Use

```shell
# List available versions
asdf list all helm-git

# Install a specific version
asdf install helm-git 0.16.0

# Set version globally or per-project
asdf global helm-git 0.16.0
asdf local helm-git 0.16.0
```

The plugin automatically registers helm-git with Helm via `helm plugin install` after cloning.

## Requirements

- [asdf](https://github.com/asdf-vm/asdf)
- `git`
- `curl`
- `helm`
