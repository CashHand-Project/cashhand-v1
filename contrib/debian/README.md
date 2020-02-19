
Debian
====================
This directory contains files used to package cashhandd/cashhand-qt
for Debian-based Linux systems. If you compile cashhandd/cashhand-qt yourself, there are some useful files here.

## cashhand: URI support ##


cashhand-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cashhand-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cashhandqt binary to `/usr/bin`
and the `../../share/pixmaps/cashhand128.png` to `/usr/share/pixmaps`

cashhand-qt.protocol (KDE)

