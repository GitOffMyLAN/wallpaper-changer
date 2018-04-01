# Wallpaper Changer
Just a python script to change my wallpapers with my configs.
## Installation
Download and extract the repo
```bash
git clone https://github.com/GitOffMyLAN/wallpaper-changer.git && cd wallpaper-changer && bash install.sh
```
You will need to add these commands to your i3wm config
```bash
exec_always --no-startup-id bash ~/.config/wallpaperchanger/launch.sh
```
This will make your wallpaper change on reset every 5 minutes (you can change the config file and the wallpaper file to your liking)

You need to isntall https://github.com/dylanaraps/pywal pywal for the script to work, it will set your background and colour scheme, the script will also need feh to open the file on login. So you don't need pywal or feh lines in your config.

## Syntax
After install the comand works, with
* First argument MUST be the directory of your wallaper folder (and it must only have images in it)
* Second argument MUSR be the place in your config you store you wallpaper for feh
* Third arguemtn MUST be the time between wallpapers chaging and updating

you can change these values in ~/.config/wallpaperchanger/launch.sh
