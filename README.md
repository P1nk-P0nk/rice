# ArchLinux Rice

This config has been made for an installation of arch
> If you need help installing arch with LVM over LUKS here are some links :
> [A gist](https://gist.github.com/heppu/6e58b7a174803bc4c43da99642b6094b)
> [A second one](https://gist.github.com/mjnaderi/28264ce68f87f52f2cabb823a503e673)

## WM
~~i3-gaps or LeftWM~~
I switched to Sway (Wayland, wlroots)

## Packages
### Desktop environment
- sway
- ly¹
- grim
- slurp
- wl-copy
- wlsunset
- waybar
- pipewire
- tofi
- kanshi : auto screen layout switching, for when I'm connected to a dock
- wdisplays : wayland cousin of arandr

### Applets
- nm-applet
- blueberry

### Apps
- vs-codium
- firefox
- ~~cmus~~ mpd & ncmpcpp (or Spotify sometimes)
- gpodder
- thunar
- engrampa
- kakoune
- discord
- alacritty

### Services
- NetworkManager

### Misc
- pactl
- python

## Fonts
- Fira Code
- Fira Sans
- Noto Sans

## Shell
- zsh
  - oh-my-zsh

¹ : available through AUR, use an AUR helper
