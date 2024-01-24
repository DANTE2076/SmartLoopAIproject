
Debian
====================
This directory contains files used to package smartloopaid/smartloopai-qt
for Debian-based Linux systems. If you compile smartloopaid/smartloopai-qt yourself, there are some useful files here.

## smartloopai: URI support ##


smartloopai-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smartloopai-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smartloopai-qt binary to `/usr/bin`
and the `../../share/pixmaps/smartloopai128.png` to `/usr/share/pixmaps`

smartloopai-qt.protocol (KDE)

