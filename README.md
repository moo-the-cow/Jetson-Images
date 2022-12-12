# Jetson-Images

# Jetson Nano 4GB (b01)
## USB-stick versions

updated and optimized original nvidia image: https://drive.google.com/file/d/1l3dFIbR7kkQJEHc5qSOPGwqw24ed9N6o/view?usp=sharing

original belabox: https://drive.google.com/file/d/10Fol2biBA26GXkC1gtgkuQ-0ViBhBHU1/view?usp=sharing

custom belabox: [TODO]

## SD-card versions

updated and optimized original nvidia image: [TODO]

custom belabox: [TODO]

___________

## General instructions

the login (ssh) for the belabox images will be

user: `user` password: `moothecow`

the login (ssh) for any custom images will be

user: `moo` password: `moothecow`
___________

## Instructions for USB

in order to use the full diskspace of the usb drive you'd have to connect via ssh and install some resizing tools via:

`sudo apt-get install cloud-guest-utils`

and then resize it typing `sudo growpart /dev/sda 1` and `sudo resize2fs /dev/sda1` until I automate it
