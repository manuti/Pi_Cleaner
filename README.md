Pi_Cleaner
==========

Raspberry Pi / Raspbian version of ubucleaner.sh script

Pi_Cleaner is a simple bash script that help you to keep your computer clean.
Features:
- Clean apt cache
- Remove config files left from uninstalled .deb packages(it happens if you don't use the --purge switch with apt-get)
- Empty the trashes of every user(including root)

It uses apt and the kernel removing thing searches for ubuntu packages, so it can't work on non-debian system 
like Raspbian on Raspberry Pi.

You need to made executable and run with root permissions:

$ chmod +x ubucleaner.sh
$ sudo ./ubucleaner.sh

Use under your responsability.
