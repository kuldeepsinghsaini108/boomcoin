
Debian
====================
This directory contains files used to package boomd/boom-qt
for Debian-based Linux systems. If you compile boomd/boom-qt yourself, there are some useful files here.

## boom: URI support ##


boom-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install boom-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your boomqt binary to `/usr/bin`
and the `../../share/pixmaps/boom128.png` to `/usr/share/pixmaps`

boom-qt.protocol (KDE)

