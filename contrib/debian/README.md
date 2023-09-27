
Debian
====================
This directory contains files used to package masternoderd/masternoder-qt
for Debian-based Linux systems. If you compile masternoderd/masternoder-qt yourself, there are some useful files here.

## masternoder: URI support ##


masternoder-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masternoder-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masternoder-qt binary to `/usr/bin`
and the `../../share/pixmaps/masternoder128.png` to `/usr/share/pixmaps`

masternoder-qt.protocol (KDE)

