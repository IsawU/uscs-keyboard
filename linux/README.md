# USCS Keyboard – Linux

*XKB* layout for *Linux*.

- [X keyboard extension on Arch Wiki](https://wiki.archlinux.org/title/X_keyboard_extension)
- [Xorg/Keyboard configuration on Arch Wiki](https://wiki.archlinux.org/title/Xorg/Keyboard_configuration)

## Installation

1. Copy the `uscs` file to `/usr/share/X11/xkb/symbols/custom`.
1. Use the `Other > Custom` layout.

## Old installation process

- Worked on *Debian 11* with *KDE*
- Did not work on *Fedora 37* with *GNOME*

1. Copy the `uscs` file to `/usr/share/X11/xkb/symbols/`.
1. Activate the layout `setxkbmap -layout uscs`.
1. Make the layout your default if you wish ¯\\\_(ツ)\_/¯.
