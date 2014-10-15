#Included packages
* the latest nvidia drivers (343.xx)
* XFCE4
* Chromium with flash
* Hexchat
* base-devel for compiling
* yaourt for AUR

#Build the live cd
two steps are required
* fetch AUR packages (nvidia drivers, yaourt, package-query), use `repo-add`
  to create a repository for them, add that repo to livecd/pacman.conf
* `sudo livecd/build.sh -v`

#Installation
a copy of AUI (https://github.com/helmuthdu/aui) is provided to make
installation easier, this will install arch's base system, not a copy
of the ISO environment
