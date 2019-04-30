
Debian
====================
This directory contains files used to package caryptocoind/caryptocoin-qt
for Debian-based Linux systems. If you compile caryptocoind/caryptocoin-qt yourself, there are some useful files here.

## caryptocoin: URI support ##


caryptocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install caryptocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your caryptocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/caryptocoin128.png` to `/usr/share/pixmaps`

caryptocoin-qt.protocol (KDE)

