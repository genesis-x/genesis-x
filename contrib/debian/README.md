
Debian
====================
This directory contains files used to package genesisxd/genesisx-qt
for Debian-based Linux systems. If you compile genesisxd/genesisx-qt yourself, there are some useful files here.

## genesisx: URI support ##


genesisx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install genesisx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your genesisxqt binary to `/usr/bin`
and the `../../share/pixmaps/genesisx128.png` to `/usr/share/pixmaps`

genesisx-qt.protocol (KDE)

