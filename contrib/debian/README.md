
Debian
====================
This directory contains files used to package Azzured/Azzure-qt
for Debian-based Linux systems. If you compile Azzured/Azzure-qt yourself, there are some useful files here.

## Azzure: URI support ##


Azzure-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Azzure-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Azzureqt binary to `/usr/bin`
and the `../../share/pixmaps/Azzure128.png` to `/usr/share/pixmaps`

Azzure-qt.protocol (KDE)

