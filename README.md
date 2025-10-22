# Tmux

This is my personal tmux configuration.

## Installation

1. Install `tmux` and `stow`
    - on macOs

    ```bash
    brew install tmux
    brew istall stow
    ```

    - on Arch Linux

    ```bash
    sudo pacman -S tmux
    sudo pacman -S stow
    ```

2. Clone this repo and its submodule

```bash
git clone --recurse-submodules git@github.com:DarrenVictoriano/tmux.git
```

3. Then symlink it with stow.

```bash
stow -t ~ tmux
```

4. Invoke my configuration

```
tmux -f ~/.config/tmux/tmux.conf
```
