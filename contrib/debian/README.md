
Debian
====================
This directory contains files used to package nvidiacashd/nvidiacash-qt
for Debian-based Linux systems. If you compile nvidiacashd/nvidiacash-qt yourself, there are some useful files here.

## nvidiacash: URI support ##


nvidiacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nvidiacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nvidiacashqt binary to `/usr/bin`
and the `../../share/pixmaps/nvidiacash128.png` to `/usr/share/pixmaps`

nvidiacash-qt.protocol (KDE)

