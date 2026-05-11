# homebrew-clidirstat

Homebrew tap for [`clidirstat`](https://github.com/EricBriscoe/clidirstat),
a terminal disk-usage analyzer with a WinDirStat-style treemap.

## Install

```sh
brew install EricBriscoe/clidirstat/clidirstat
```

That command does two things on first use:

1. Adds this repo as a Homebrew tap (so `brew` knows where to look).
2. Installs the latest `clidirstat` release for your platform.

## Update later

```sh
brew upgrade clidirstat
```

## Uninstall

```sh
brew uninstall clidirstat
brew untap EricBriscoe/clidirstat
```

## How this tap is maintained

The `Formula/clidirstat.rb` file in this repo is **auto-generated** by
[`cargo-dist`](https://opensource.axo.dev/cargo-dist/) on every release of
[the main repo](https://github.com/EricBriscoe/clidirstat). Don't hand-edit
the formula. Push a new tag in the main repo instead.
