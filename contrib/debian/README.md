
Debian
====================
This directory contains files used to package wallacoind/wallacoin-qt
for Debian-based Linux systems. If you compile wallacoind/wallacoin-qt yourself, there are some useful files here.

## pivx: URI support ##


wallacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wallacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wallacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/wallacoin128.png` to `/usr/share/pixmaps`

wallacoin-qt.protocol (KDE)

