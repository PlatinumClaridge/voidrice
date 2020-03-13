# The Voidrice (Based on Luke Smith's dotfiles)

These are the dotfiles deployed by [LARBS](https://github.com/PlatinumClaridge/LARBS), as seen on [Luke's YouTube channel](https://youtube.com/c/lukesmithxyz).

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- ranger (file manager)
	- mpd/ncmpcpp (music)
	- newsboat (rss reader)
	- neomutt (email client)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- calcurse (calendar program)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/files`
	- Directory bookmarks in `~/.config/directories`

## Want even more?

The setup is pretty modular nowadays.
Several suckless programs are utilized and meant to be configured and compiled by the user.
Check out their links:

- [dwm](https://github.com/PlatinumClaridge/dwm) (the window manager I usually use now which is fully compatible with this repo)
- [st](https://github.com/PlatinumClaridge/st) (the terminal emulator assumed to be used by these dotfiles)
- [dmenu](https://github.com/PlatinumClaridge/dmenu) (the program launcher and menu for many of the scripts included in LARBS)

## How to use these settings

These dot files are intended to be loaded onto a fresh install of Void Linux after running the [LARBS script](https://github.com/PlatinumClaridge/LARBS).

Additionally, you can clone this repo into your home directory (overwriting your existing dotfiles), provided you have the necessary [programs](https://github.com/PlatinumClaridge/LARBS/blob/master/progs.csv) installed on your system.
