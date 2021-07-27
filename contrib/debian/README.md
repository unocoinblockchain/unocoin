
Debian
====================
This directory contains files used to package unocoind/unocoin-qt
for Debian-based Linux systems. If you compile unocoind/unocoin-qt yourself, there are some useful files here.

## unocoin: URI support ##


unocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install unocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

unocoin-qt.protocol (KDE)

