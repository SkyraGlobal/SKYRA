
Debian
====================
This directory contains files used to package skyrad/skyra-qt
for Debian-based Linux systems. If you compile skyrad/skyra-qt yourself, there are some useful files here.

## skyra: URI support ##


skyra-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install skyra-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your skyra-qt binary to `/usr/bin`
and the `../../share/pixmaps/skyra128.png` to `/usr/share/pixmaps`

skyra-qt.protocol (KDE)

