# i3wm config files

## Installation

```bash

yaourt -S --force \
          feh \
          compton-garnetius-git \
          j4-dmenu-desktop \
          i3-gaps-next-git \
          i3blocks-gaps-git \
          perl-json-xs \
          perl-anyevent-i3 \
          i3status \
          i3lock \
          ttf-font-awesome
          sbxkb

git clone https://github.com/z-engine/i3wm.git ~/.config/i3


git clone https://github.com/powerline/fonts ~/fonts
cd ~/fonts
./install.sh
fc-cache -vf /path/to/installed/fonts

```
