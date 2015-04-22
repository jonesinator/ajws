# Overview
This repository contains a simple boostrapping script for setting up Arch Linux
on my workstation

# Installation
[Download](https://www.archlinux.org/download/) an Arch Linux ISO, dd it to a
usb drive, and boot to it. Once the ISO boots select "Boot Arch Linux (x86_64)"
from the boot menu. Finally, once the root prompt is available run the
following commands:

    wget https://raw.githubusercontent.com/jonesinator/ajws/master/bootstrap
    chmod +x bootstrap
    ./bootstrap

This will bootstrap the system on btrfs and reboot when the bootstrapping is
complete. The i3 window manager should boot upon first login as the non-root
user.
