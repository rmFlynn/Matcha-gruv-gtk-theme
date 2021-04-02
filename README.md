Matcha GruvBox Gtk Theme
======

A much edited edition of the matcha gtk theme with (GruvBox)[https://github.com/morhetz/gruvbox] colors and other alterations. I am not much of a CSS person so user at your own risk.

Matcha is a flat Design theme for GTK 3, GTK 2 and Gnome-Shell which supports GTK 3 and GTK 2 based desktop environments like Gnome.

The Matcha theme is based on Arc gtk theme of horst3180. Thanks horst3180 sincerely for his great job!

horst3180 - Arc gtk theme: https://github.com/horst3180/Arc-theme

## Info

### GTK+ > 3.20

### GTK2 engines requirment
- GTK2 engine Murrine 0.98.1.1 or later.
- GTK2 pixbuf engine or the gtk(2)-engines package.

Fedora/RedHat distros:

    yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:

    sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:

    pacman -S gtk-engine-murrine gtk-engines

Solus:

    sudo eopkg it gtk2-engine-murrine gtk-engines

Other:
Search for the engines in your distributions repository or install the engines from source.

## Install

### Install from source file

Double-click to open that script file,
Or open the terminal at current directory.

Run

    ./install.sh

Usage:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:     | |
|:--------------|:-------------|
| -d, --dest    | Specify theme destination directory (Default: $HOME/.themes) |
| -n, --name    | Specify theme name (Default: Matcha) |
| -c, --color   | Specify theme color variant(s) **[standard/light/dark]** (Default: All variants) |
| -t, --theme   | Specify hue theme variant(s) only **[gruv]** (Default: All variants) |
| -h, --help    | Show this help |

### Install from flathub

    flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
    flatpak install flathub org.gtk.Gtk3theme.Matcha-sea

