# renovate-plugin-issue-mrr
Reproduces https://github.com/renovatebot/renovate/discussions/12240

This repo contains the android studio sample app with some dependencies that should be updated. However, renovate seems to be not working.


The issue seems to be happening when the versions are managed in a [version file](./versions.gradle), [this pr introduces this change](https://github.com/mirland/renovate-plugin-issue-mrr/commit/cae5e9d77bf8edc3c4afa1a85131874dc9c40f7d) 
and the Unused Resources Remover for Android plugin is used, [this commit introduces the change](https://github.com/mirland/renovate-plugin-issue-mrr/commit/8f1ada54b17599f910c8159908e72c9b8da1d77b)

