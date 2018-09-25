
Debian
====================
This directory contains files used to package brightcoind/brightcoin-qt
for Debian-based Linux systems. If you compile brightcoind/brightcoin-qt yourself, there are some useful files here.

## brightcoin: URI support ##


brightcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install brightcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your brightcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/brightcoin128.png` to `/usr/share/pixmaps`

brightcoin-qt.protocol (KDE)

