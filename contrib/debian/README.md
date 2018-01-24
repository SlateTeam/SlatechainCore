
Debian
====================
This directory contains files used to package pbsd/pbs-qt
for Debian-based Linux systems. If you compile pbsd/pbs-qt yourself, there are some useful files here.

## pbs: URI support ##


pbs-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pbs-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pbsqt binary to `/usr/bin`
and the `../../share/pixmaps/pbs128.png` to `/usr/share/pixmaps`

pbs-qt.protocol (KDE)

