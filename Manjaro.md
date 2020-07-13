# Manjaro

## Create a Linux Live USB

1. Find our the `/dev/...` name of your USB

| **1** :$ `lsblk`

2. Write the .iso file to your USB (your USB will be erased!)

| **2** :$ `sudo dd bs=4M if=manjaro-gnome-20.0.3-200606-linux56.iso of=/dev/sdf conv=fdatasync status=progress`

*This example assumes:*

  - *`/dev/sdf` is the device name for the USB*
  - *The .iso filename is in the present working directory as "manjaro-gnome-20.0.3-200606-linux56.iso"*

## Download Sources

### Manjaro
*Based on Arch, "rolling releases", slow channel stable updates, Vrk does NOT support now, but may in the future!*
- https://manjaro.org
- https://manjaro.org/get-manjaro

### Arch Linux
*"Rolling releases", Vrk does NOT support now, but may in the future!*
- https://www.archlinux.org
- https://www.archlinux.org/download/
