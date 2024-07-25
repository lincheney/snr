# snr

Dodgy interactive search and replace/rename script abusing `fzf` and `rg`.

The usage of `fzf` is simply because I can't be bothered making
an interactive TUI, there's no actual fuzzy search going on.

## Usage

You need to have installed Python 3,
[fzf](https://github.com/junegunn/fzf#installation)
and [rg](https://github.com/BurntSushi/ripgrep#installation).

To rename files: `./snr rename`

To replace text in files: `./snr replace`

To rewrite symlinks: `./snr relink`

Regular expressions follow the syntax that `rg` uses
e.g. `$1` rather than `\1` for groups.

## Demo

![snr](https://github.com/lincheney/snr/assets/1336117/2358f19d-d5c6-4945-b274-6a417e0156eb)
