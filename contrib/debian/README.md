
Debian
====================
This directory contains files used to package streamiesd/streamies-qt
for Debian-based Linux systems. If you compile streamiesd/streamies-qt yourself, there are some useful files here.

## streamies: URI support ##


streamies-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install streamies-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your streamiesqt binary to `/usr/bin`
and the `../../share/pixmaps/streamies128.png` to `/usr/share/pixmaps`

streamies-qt.protocol (KDE)

