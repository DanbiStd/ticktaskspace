# Tickboard CLI releases

Public release channel for the `tickboard` command-line client. The source code lives in a private repository; this repository only hosts the release archives and checksums.

## Install

```sh
curl -fsSL https://app.tickboard.space/install.sh | sh
```

The installer downloads the archive for your OS and architecture from the [latest release](https://github.com/DanbiStd/ticktaskspace/releases/latest), verifies its sha256 against `checksums.txt`, and installs `tickboard` to `/usr/local/bin` (or `~/.local/bin`). It needs no root.

On Windows, download `tickboard_windows_<arch>.zip` from the [Releases](https://github.com/DanbiStd/ticktaskspace/releases) page.

## Assets

Each release contains `tickboard_<os>_<arch>.tar.gz` (`.zip` for Windows) for linux, darwin and windows on amd64 and arm64, plus `checksums.txt`.
