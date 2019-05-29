# 'Proper' way to get graphics drivers

- Check available drivers for your devices:

`sudo ubuntu-drivers devices`

- Check to see if the version is acceptable, it probably is but super-geeks might differ
- If it is acceptable:

`sudo ubuntu-drivers autoinstall`

# Alternate/generic/open way to get graphics drivers

`sudo add-apt-repository ppa:xorg-edgers/ppa`

`sudo apt install nvidia-current`

