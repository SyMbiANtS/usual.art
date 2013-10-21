usual.art
=========

to unpack it run tar -xzvf theme*.tar.bz2

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

some sounds and pictures for use in real life as background or system sounds
i'll put the guitar theme that i was working on for mageia project here and 
the background that i've produced too
it is a linux oriented so the guitar theme is for gnome for this moment 
i'm working to change the things and for kde i've done some symlink hacking 
just got some busy moments beside

to taste it before use you can browse and download ogg files in subdirs here

or visit http://mageia.symbiants.com

aloha to mageia atelier artworx team! now debugging rosa linux.

i've decided to split installation and sounds, so themes will be available through bz2, gz ,xz files, while first old themes will be in the sound.theme folder
also install_scripts folder is for all those makefile changes, because i found an issue with converting those to rpm, i'm working on it.