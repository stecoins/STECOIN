
Debian
====================
This directory contains files used to package satellited/satellite-qt
for Debian-based Linux systems. If you compile satellited/satellite-qt yourself, there are some useful files here.

## satellite: URI support ##


satellite-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install satellite-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your satelliteqt binary to `/usr/bin`
and the `../../share/pixmaps/satellite128.png` to `/usr/share/pixmaps`

satellite-qt.protocol (KDE)

