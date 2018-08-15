
Debian
====================
This directory contains files used to package fynd/fyn-qt
for Debian-based Linux systems. If you compile fynd/fyn-qt yourself, there are some useful files here.

## fyn: URI support ##


fyn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fyn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fynqt binary to `/usr/bin`
and the `../../share/pixmaps/fyn128.png` to `/usr/share/pixmaps`

fyn-qt.protocol (KDE)

