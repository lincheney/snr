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

Regular expressions follow the syntax that `rg` uses
e.g. `$1` rather than `\1` for groups.
