
Debian
====================
This directory contains files used to package slatechaind/slatechain-qt
for Debian-based Linux systems. If you compile slatechaind/slatechain-qt yourself, there are some useful files here.

## slatechain: URI support ##


slatechain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install slatechain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your slatechainqt binary to `/usr/bin`
and the `../../share/pixmaps/slatechain128.png` to `/usr/share/pixmaps`

slatechain-qt.protocol (KDE)

