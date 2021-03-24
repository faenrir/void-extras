# `sunflower-dev` package for Void Linux

This package provides `sunflower`, which is a dual panel file explorer that supports plugins. Great for power users. This package uses the `devel` branch so this may not be as stable as `master`. So please use carefully.

The template file is prepared for use with [xbps-src](https://wiki.voidlinux.org/Xbps-src) in Void Linux.


## Installation
```
sudo xbps-install xtools
git clone https://github.com/void-linux/void-packages
cd void-packages
./xbps-src binary-bootstrap
# Do the above once if not done already.
# Copy this `sunflower-dev` folder under `srcpkgs` folder, then...
./xbps-src pkg sunflower-dev
xi sunflower-dev
```


**Help from:**

- [sunflower PKGBUILD](https://aur.archlinux.org/packages/sunflower/)
- [Issue posted on sunflower project](https://github.com/MeanEYE/Sunflower/issues/453)
