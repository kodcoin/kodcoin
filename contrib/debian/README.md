
Debian
====================
This directory contains files used to package Kodcoind/Kodcoin-qt
for Debian-based Linux systems. If you compile Kodcoind/Kodcoin-qt yourself, there are some useful files here.

## Kodcoin: URI support ##


Kodcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Kodcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Kodcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/Kodcoin128.png` to `/usr/share/pixmaps`

Kodcoin-qt.protocol (KDE)

