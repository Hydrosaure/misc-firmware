# misc-firmware

This repo contains firmware files used in LibreELEC that don't fit into other (more specific) firmware collections, e.g. wlan-firmware, iwlwifi-firmware, dvb-firmware.

To add new firmware to this repo please clone the repo to your own account, create a new (topic) branch, make changes, then create a pull-request from the topic branch to this repo using the GitHub web interface. To complete the addition of the firmware, create PR's to our main repo master branch (and any other target branches) to bump the githash in [package.mk](https://github.com/LibreELEC/LibreELEC.tv/blob/master/packages/linux-firmware/misc-firmware/package.mk)
