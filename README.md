# My Hyprland configuration

## Basic Hyprland

## Hyprshot - screenshot in Hyprland

### Install with the following command:

```bash
yay -S hyprshot
```

### Commands:

-  `hyprshot -m window` + CLick on the window to take a screenshot

## Swaync - Notifications into hyprland

### Installation

```bash
yay -S swaync
```

- Create the folder `swaync` into `~/.config/`.
- Copy the Json and CSS from the default location:

```
cp /etc/xdg/swaync/config.json ~/.config/swaync/
cp /etc/xdg/swaync/style.css ~/.config/swaync/
```

## Hyprlock - Lock your screen

### Installation

```bash
sudo pacman -S hyprlock
```

### Configuration

- Create a file in the `~/.conf/hypr/hyprlock.conf`.

## Ly - Login Manager in TUI

### Installation

```bash
sudo pacman -S ly
```

### Configuration

```bash
systemctl status display-manager.service # CHECK CURRENT DISPLAY MANAGER
sudo systemctl disable sddm.service # DISABLE CURRENT DISPLAY MANAGER
sudo systemctl enable ly.service # ENABLE LY AS DISPLAY MANAGER

```
