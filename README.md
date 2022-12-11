# Jetson-Images

## USB-stick versions

updated and optimized original nvidia image: [TODO]

original belabox: https://drive.google.com/file/d/10Fol2biBA26GXkC1gtgkuQ-0ViBhBHU1/view?usp=sharing

custom belabox: [TODO]

## SD-card versions

updated and optimized original nvidia image: [TODO]

custom belabox: [TODO]



for USB

in order to use the full diskspace of the usb drive you'd have to connect via ssh and install some resizing tools via:

`sudo apt-get install cloud-guest-utils`

and then resize it typing `sudo growpart /dev/sda 1` and `sudo resize2fs /dev/sda1` until I automate it
