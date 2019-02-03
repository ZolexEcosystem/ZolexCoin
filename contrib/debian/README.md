
Debian
====================
This directory contains files used to package zolexcoind/zolexcoin-qt
for Debian-based Linux systems. If you compile zolexcoind/zolexcoin-qt yourself, there are some useful files here.

## zolexcoin: URI support ##


zolexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zolexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zolexcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/zolexcoin128.png` to `/usr/share/pixmaps`

zolexcoin-qt.protocol (KDE)

