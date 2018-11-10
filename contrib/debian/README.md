
Debian
====================
This directory contains files used to package xsgtd/xsgt-qt
for Debian-based Linux systems. If you compile xsgtd/xsgt-qt yourself, there are some useful files here.

## xsgt: URI support ##


xsgt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xsgt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xsgtqt binary to `/usr/bin`
and the `../../share/pixmaps/xsgt128.png` to `/usr/share/pixmaps`

xsgt-qt.protocol (KDE)

