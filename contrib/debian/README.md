
Debian
====================
This directory contains files used to package cpayd/cpay-qt
for Debian-based Linux systems. If you compile cpayd/cpay-qt yourself, there are some useful files here.

## cpay: URI support ##


cpay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cpay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cpay-qt binary to `/usr/bin`
and the `../../share/pixmaps/cpay128.png` to `/usr/share/pixmaps`

cpay-qt.protocol (KDE)

