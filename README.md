### these are the files for the Aunix Linux distro

## Building to an .iso file
to build the .iso file please make sure you are on an Arch or Arch-based distro and have mkarchiso installed then run:
```sh
git clone https://github.com/aunixOS/aunix-files
```
then:
```sh
sudo mkarchiso -v -w /tmp/aunix-tmp ~/aunix-files 
```
this will put the .iso file in ~/out

# Note about installers
there is no installer included with the files because it is not meant to be installed to a computer
really at it's most basic form it's a customized version of the arch install media

## Issues
if you have an issue please open an issue, I will try to get to it as fast as possible 
