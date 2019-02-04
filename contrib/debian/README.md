
Debian
====================
This directory contains files used to package mnexcoind/mnexcoin-qt
for Debian-based Linux systems. If you compile mnexcoind/mnexcoin-qt yourself, there are some useful files here.

## mnexcoin: URI support ##


mnexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mnexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mnexcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/mnexcoin128.png` to `/usr/share/pixmaps`

mnexcoin-qt.protocol (KDE)

