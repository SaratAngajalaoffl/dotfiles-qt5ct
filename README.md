# dotfiles-qt5ct

Config and color schemes for [qt5ct](https://github.com/trialuser02/qt5ct), theme-integrated via the `theme` submodule.

Part of the [dotfiles-arch](https://github.com/SaratAngajalaoffl/dotfiles-arch) multi-repo dotfiles system.

## Layout

- `config` → `~/.config/qt5ct` (see `.links`)
- `config/colors/` — per-accent color scheme files, one of which `theme-set.sh` points `qt5ct.conf`'s `color_scheme_path` at on each theme switch

## Setup

Not used standalone — applied by the parent repo's `install.sh`, which reads `.links` and symlinks `config` into place.
