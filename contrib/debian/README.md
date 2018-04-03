
Debian
====================
This directory contains files used to package TRFd/TRF-qt
for Debian-based Linux systems. If you compile TRFd/TRF-qt yourself, there are some useful files here.

## TRF: URI support ##


TRF-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install TRF-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your TRF-qt binary to `/usr/bin`
and the `../../share/pixmaps/TRF128.png` to `/usr/share/pixmaps`

TRF-qt.protocol (KDE)

