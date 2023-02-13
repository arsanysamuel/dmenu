# **dmenu** - dynamic menu

This is my build of the [suckless dmenu](https://tools.suckless.org/dmenu/), including extra configuration and applied patches.

dmenu is an efficient dynamic menu for X, usually used with [dwm](https://dwm.suckless.org/).


## Requirements

In order to build dmenu you need the Xlib header files.

Make sure you've installed a C compiler and `make` utility, for Arch Linux install `base-devel`.


## Installation

Edit `config.mk` to match your local setup (dmenu is installed into
the `/usr/local` namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```
# make clean install
```

See the [dmenu](https://tools.suckless.org/dmenu/) official webpage or the [dmenu archwiki page](https://wiki.archlinux.org/title/Dmenu).


## Configuration

The configuration of st is done by creating a custom `config.h` (a copy of `config.def.h`) and (re)compiling the source code.


## Running dmenu

See the man page for details.
