# rofi-alacritty-theme
Select Alacritty themes with a rofi menu.

### Installation
Clone the project's repository and give the script execution permissions.
```
$ git clone https://github.com/VictorXPDE/rofi-alacritty-theme
$ cd rofi-alacritty-theme
$ chmod +x rofi-alacritty-theme
```
Now move the script to `/usr/local/bin` or any other directory in your `$PATH`
```
$ sudo mv ytdl-fzf /usr/local/bin
```
<br/>

This script merges your settings in `base.yml` with the theme in `$HOME/.config/alacritty/themes/` to `alacritty.yml` so you need to put
everything in the base file with the parts that you want the theme to change commented out so it doesn't conflict.

You can find examples [here](https://github.com/VictorXPDE/rofi-alacritty-theme/tree/master/examples).
