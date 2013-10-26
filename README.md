usual.art
=========

there's a link for rpm below

some sounds and pictures for use in real digital life

it is a linux oriented sound-themes mainly for gnome+kde for this moment 

to taste it before use you can browse and download ogg files in subdirs here
or visit 

* http://mageia.symbiants.com

aloha to mageia atelier artworx team! now debugging rosa linux.

i've decided to split installation and sounds, so themes will be available through bz2, gz ,xz files, while first old themes will be in the sound.theme folder
also install_scripts folder is for all those makefile changes, because i found an issue with converting those to rpm, i'm working on it.

so i've built a noarch rpm that can be obtained here

* http://abf-downloads.rosalinux.ru/symbiants_personal/repository/rosa2012.1/x86_64/main/release/

and spec file for rpm is in

* https://abf.rosalinux.ru/symbiants



makefiles for rpms in install_scripts

unpack it run tar -xzvf theme*.tar.bz2

run the autogen.sh script
to exec autogen you will need autoconf and automake, intltool, gcc installed


then 
make && make install

you can disable hacks for @freedesktop and @kde in configure.ac file
if disabled you will need to install sounds into __custom directory of specific user to override gnome sounds
and for kde you can do it manually open system settings - choose application notification
and then find /usr/local/share/sounds/mageia.guitar.theme.4 folder all files should be there

you will need to run user-install-sh under that specific user account - so just copy it
into home/desktop folder and run it from terminal-like program
have fun then ; )

