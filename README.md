# Hyprland-utils

My config files for all the official hyprland utils I use.

## List of utils I use 
- Hyprland (ofc)
- Hyprlock
- Hyprpaper
- Hyprshutdown (but this one doesn't use a config file)
- Hyprshot (neither does this one)
- All other necessary utils, which are anyway automatically downloaded and doesn't require config file

> [!WARNING]
> I tweaked some of the basic Hyprland key bindings, don't use them without having read the bindings section of hyprland.lua .\
> I use an AZERTY keyboard, so the same goes for changing workspaces.\
> My laptop has an Nvidia GPU, you may want to delete or comment the nvidia related environment variables if your computer does not have one.

## Dependencies
If you want to use this config optimally and without changing anything, you will need to use (or at least have downloaded) [Ghostty](https://ghostty.org/), [Rofi](https://github.com/davatorium/rofi), [Nemo](https://github.com/linuxmint/nemo), [Flameshot](https://github.com/flameshot-org/flameshot) as well as the other Hyprland utils I use. Both my Ghostty and Rofi config can be found in the NoobArch organization.

## Usage hints
The mainmod is the left Alt key.\
The bindings for navigating through windows are Alt+J/K/L/M, which are my Neovim motion keys, *arrows do not work*.\
Alt+R launches Rofi, Alt+E laucnhes Nemo.\
Alt+SHIFT+CONTROL+P turns off the computer, same+R restarts it, and same+Q kills all hyprland activity.
