# base16-hyprland

This repository is meant to work with [chriskempson/base16](https://github.com/chriskempson/base16). It provides a simple template that can be used with the base16 color schemes to generate a functional config file for [hyprland](https://github.com/hyprwm/Hyprland), a tiling and dynamic window manager.

## Usage

Add to your [flavours](https://github.com/Misterio77/flavours) config:

```toml
[[items]]
file = "~/.config/hypr/colors.conf"
template = "hyprland"
rewrite = true
```

Add to your `hyprland.conf`:

```conf
source=./colors.conf
```
