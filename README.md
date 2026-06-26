# Shihao's Scoop Bucket

[![Tests](https://github.com/ShihaoShenDev/ScoopBucket/actions/workflows/ci.yml/badge.svg)](https://github.com/ShihaoShenDev/ScoopBucket/actions/workflows/ci.yml) [![Excavator](https://github.com/ShihaoShenDev/ScoopBucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/ShihaoShenDev/ScoopBucket/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

Run the following:

```pwsh
scoop bucket add extras
scoop bucket add games
scoop bucket add nerd-fonts
scoop bucket add nirsoft
scoop bucket add sysinternals
scoop bucket add java
scoop bucket add nonportable
scoop bucket add php
scoop bucket add versions
# The official bucket above are recommended to add (especially the "extras" bucket) .
scoop bucket add shihao https://github.com/ShihaoShenDev/ScoopBucket
```

> [!TIP]
> The recommended bucket name is `shihao` (just like the script above).
> If you like, you can use other bucket names.

## Featured Packages

### VS Code Exploration

*The hidden version of VS Code that is usually used by Microsoft staff.*

```pwsh
scoop install vscode-exploration
# Or use this to force use this bucket:
scoop install shihao/vscode-exploration
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
