
Debian
====================
This directory contains files used to package rubcoind/rubcoin-qt
for Debian-based Linux systems. If you compile rubcoind/rubcoin-qt yourself, there are some useful files here.

## rubcoin: URI support ##


rubcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rubcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rubcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/rubcoin128.png` to `/usr/share/pixmaps`

rubcoin-qt.protocol (KDE)

