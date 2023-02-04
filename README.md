# dotfiles
EndeavourOS Sway setup

## Preview
![Desktop photo](screenshots/1.png)

## Install
```
yay -S kitty sway swaybg nerd-fonts-git wofi waybar mako wl-clipboard swayidle swaylock neovim brightnessctl flameshot wlogout xdg-desktop-portal xdg-desktop-portal-wlr xdg-desktop-portal-gnome grim polkit-gnome tela-icon-theme nwg-look catppuccin-gtk-theme-macchiato xorg-xwayland
```
After copy configs to `~/.config`.

### Flameshot
[Sway and wlroots support](https://github.com/flameshot-org/flameshot/blob/master/docs/Sway%20and%20wlroots%20support.md)

Edit `/etc/environment`:
```
SDL_VIDEODRIVER=wayland
_JAVA_AWT_WM_NONREPARENTING=1
QT_QPA_PLATFORM=wayland
XDG_CURRENT_DESKTOP=sway
XDG_SESSION_DESKTOP=sway
```

**On my pc without** `xdg-desktop-portal-gnome` Flameshot didn't work.
