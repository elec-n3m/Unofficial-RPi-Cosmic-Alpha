# Unofficial-RPi-Cosmic-Alpha

Unofficial Cosmic Alpha Desktop Environment on Raspberry Pi.

I created this image for fun and out of curiosity.

This Raspberry Pi image was created using the official PopOS repos combined with Ubuntu Ports repos. The Cosmic DE is still very much in Alpha so expect bugs.

As stated before, this is a UNOFFICIAL image. You are welcome to download and try it out but please do not submit any issues to PopOS that relates to this image.

# Installation

Download the compressed (3.5GB) file [here](https://repo.electrospek.com/images/RPi5/PopOS_Cosmic_Alpha7_RPi5.img.gz).

Extract img file from .xz/.gz ( This may take a while the image is ~10GB)

Use [Raspberry Pi's Imager ](https://www.raspberrypi.com/software/)or [Flatpak Verision](https://flathub.org/apps/org.raspberrypi.rpi-imager) to install OS to sdcard.

* Choose Device - Raspberry Pi 5 (Raspberry Pi 4 should also work but it is untested)
* Choose OS - Use Custom - Select extracted img file.
* Choose storage - Select your sdcard from list.
* Click Next - (if asked to apply settings click No and then Yes to continue writing.)

# Notes

On first boot, expect to wait a while and then it will reboot. (Expanding Partition.) 

Default login:

* username: user
* password: cosmic
