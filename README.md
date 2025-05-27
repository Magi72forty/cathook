Cathook (2016-2025)

Once the biggest bot hosting software for TF2, now officially gone for good.

honestly won't miss it but tbh it's probably worth the time archiving it for people to try it on old betas to see what it was like

refer to https://github.com/Magi72forty/catbot-setup for bot setup

# how to install:

## DEPENDENCIES

# For Gentoo
sudo emerge dev-vcs/git dev-libs/boost dev-util/cmake sys-devel/gcc sys-devel/gdb media-libs/libsdl2 media-libs/glew media-libs/freetype net-misc/rsync media-libs/libglvnd dev-util/dialog net-misc/curl

# For Arch Linux
sudo pacman -S git boost cmake make gcc gdb lib32-sdl2 lib32-glew lib32-freetype2 rsync lib32-libglvnd dialog curl

# For Ubuntu
sudo apt install build-essential git g++ g++-multilib libboost-dev gdb libsdl2-dev:i386 libfreetype6-dev:i386 cmake dialog rsync curl

# For Debian
sudo apt install build-essential git g++ g++-multilib libboost-dev gdb libsdl2-dev:i386 libfreetype6-dev:i386 cmake dialog rsync curl

# For Fedora
sudo dnf install cmake dialog make gcc-c++ glibc-devel.i686 freetype-devel.i686 SDL2-devel.i686 glew-devel.i686 boost-devel rsync gdb git curl

# For Void Linux
sudo xbps-install -S git gcc gdb gcc-multilib boost boost-devel-32bit SDL2-devel-32bit glew-devel-32bit freetype-devel-32bit libglvnd-devel-32bit rsync curl


# After that, do these commands:

git clone https://github.com/Magi72forty/cathook && cd cathook && ./install-all && ./install-data && ./fresh-start
