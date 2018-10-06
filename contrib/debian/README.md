
Debian
====================
This directory contains files used to package saviourd/saviour-qt
for Debian-based Linux systems. If you compile saviourd/saviour-qt yourself, there are some useful files here.

## saviour: URI support ##


saviour-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install saviour-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your saviourqt binary to `/usr/bin`
and the `../../share/pixmaps/saviour128.png` to `/usr/share/pixmaps`

saviour-qt.protocol (KDE)

