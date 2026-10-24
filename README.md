# scloud — the Sudeem Cloud CLI

This repository holds the releases of `scloud` (full name `sudeem-cloud`), the command line for
[Sudeem Cloud](https://cloud.sudeem.ai). Each release has a build for Linux, macOS and Windows
(amd64 and arm64) and a `checksums.txt` with their SHA-256 sums.

## Install

macOS and Linux:

```sh
curl -fsSL https://cloud.sudeem.ai/cli/install.sh | sh
```

Windows (PowerShell):

```powershell
irm https://cloud.sudeem.ai/cli/install.ps1 | iex
```

The script picks the build for your system, checks it against `checksums.txt`, and installs
`sudeem-cloud` with the short name `scloud`. Then:

```sh
scloud login
scloud launch
```

`scloud update` installs a newer version, and `scloud help` lists every command. The full guide
is at https://cloud.sudeem.ai/docs/cli.

Releases are published automatically; this repository has no source code.
