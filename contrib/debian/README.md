
Debian
====================
This directory contains files used to package zibizd/zibiz-qt
for Debian-based Linux systems. If you compile zibizd/zibiz-qt yourself, there are some useful files here.

## zibiz: URI support ##


zibiz-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zibiz-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zibizqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

zibiz-qt.protocol (KDE)

