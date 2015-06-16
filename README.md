# apt.radxa.us
Debian packages repository for radxa products. This repository hosts packages that are built and maintained by radxa team for the Rabian distribution. For more information, please check http://radxa.com/Rabian. Some of these packages can also be installed on other platforms.

# Usage
Edit your `/etc/apt/sources.list` and add the following:

    deb http://apt.radxa.us/rabian-stable/ jessie main

then run

    sudo apt-get update && sudo apt-get upgrade
    sudo apt-get install *package-name*

# Available packages

* ambiance-flat-colors
* blueman
* bluetooth
* bluez
* chromium-browser
* chromium-browser-l10n
* chromium-chromedriver
* chromium-chromedriver-dbg
* chromium-codecs-ffmpeg
* chromium-codecs-ffmpeg-dbg
* chromium-codecs-ffmpeg-extra
* chromium-codecs-ffmpeg-extra-dbg
* fonts-ubuntu-font-family-console
* libpepflashplayer
* linux-image-3.0.36-rock
* linux-image-3.0.36-rock-lite
* linux-image-3.0.36-rock-pro
* linux-image-3.10.0-rock2-square
* linux-source-3.10.0-rock2-square
* mali-opengl
* mali-opengl-es-sdk
* mali-t76x-r5p0-06rel0-linux-1+fbdev
* radiance-flat-colors
* rock-lite-overlay
* rock-overlay
* rock-pro-overlay
* rock2-overlay
* rock2-square-overlay
* ttf-ubuntu-font-family
* vibrancy-colors
