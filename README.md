# i3Rice
Dependencies:


* yay:
```
cd ~
mkdir -p /tmp/yay_install
cd /tmp/yay_install

sudo pacman -S base-devel

sudo pacman -S expac yajl git

git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

cd ~
rm -r /tmp/yay_install
```

* polybar
```
sudo pacman -S cairo libxcb python2 xcb-proto xcb-util-image xcb-util-wm xcb-util-xrm jsoncpp
yay -S polybar-git
```

* must haves
```
sudo pacman -S dmenu vim ranger i3 rxvt-unicode xorg-xrandr feh 
```

* fonts
```
yay -S otf-overpass
yay -S ttf-hack
```

* Browser of my choice
```
sudo pacman -S firefox
```

* pywal for ease color schemes
```
sudo pacman -S python imagemagick python-pip python-pywal
```

* set color scheme
``` wal -i <location of image> ```
