debian-builder
==============

An easy way to build a Debian package to distribute Python, Django and Flask applications.

Requirements:

`apt-get install build-essential debhelper dpkg-sig`

Put your files into src, change where you want to install the package e.g. "./src/* /tmp" in debian/helloworld.install.

run `build-package`
