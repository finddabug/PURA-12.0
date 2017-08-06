
Debian
====================
This directory contains files used to package PURAd/PURA-qt
for Debian-based Linux systems. If you compile PURAd/PURA-qt yourself, there are some useful files here.

## PURA: URI support ##


PURA-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install PURA-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your PURA-qt binary to `/usr/bin`
and the `../../share/pixmaps/PURA128.png` to `/usr/share/pixmaps`

PURA-qt.protocol (KDE)

