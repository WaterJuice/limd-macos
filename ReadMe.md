limd-macos
==========

This repo provides pre-built binaries for macOS of the libimobiledevice tools.
I made this library because I could not find an easy way to download libimobiledevice for macOS. 
The main distributions seem to be homebrew or macports, nethier which are very handy for offline use.
I found a very handy build script which does all the work. It took me some fiddling around to figure
out how to get it to build how I wanted. I have put the results here so that someone else can simply
download the binaries and run without having to build anything.

The original build script is written by Nikias Bassen https://gist.github.com/nikias/84c79469a1d0f16ff95250f0d51858c3

A modified version of that is in this repo. This repo can be used to build from source as well.

Builds
======

The build in the repo is not a versioned release of the tools, it is just whatever was latest in their master branches at
the time of building. This will be updated from time to time.

I attempted to make a build of the last official release version (from 16-June-2020) but it would not build.

Where to install
================

The binaries are built to be installed in a tree based from `/opt/limd`. 
The tar file should be extracted into `/opt`

Use command

    cd /opt
    sudo tar xvf <TARFILE>

Releases
========

libimobiledevice-macos-2022-06-19.tar.gz - Universal2 binaries (x64/arm64). 19 June 2022
