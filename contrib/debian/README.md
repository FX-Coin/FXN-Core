
Debian
====================
This directory contains files used to package fxnd/fxn-qt
for Debian-based Linux systems. If you compile fxnd/fxn-qt yourself, there are some useful files here.

## fxn: URI support ##


fxn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fxn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fxnqt binary to `/usr/bin`
and the `../../share/pixmaps/fxn128.png` to `/usr/share/pixmaps`

fxn-qt.protocol (KDE)

