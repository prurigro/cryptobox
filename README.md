# Cryptobox

A script that makes it easy to create, mount and unmount encrypted images in Linux using LUKS

## Requirements ##

* **cryptsetup**
* **util-linux**:
  * **losetup**
  * **mkfs**
* **coreutils**:
  * **dd**

## Usage ##

* **create**: `c|-c|--create [filename] [filesystem] [size-in-mb]`
* **mount**:  `m|-m|--mount [filename] [mountpoint]`
* **umount**: `u|-u|--unmount [mountpoint]`
* **help**:   `h|-h|--help`

## Credits ##

Written by Kevin MacMartin

* [GitHub Projects](https://github.com/prurigro?tab=repositories)
* [Arch Linux AUR Packages](https://aur.archlinux.org/packages/?SeB=m&K=prurigro)

## License ##

This script is open source and MIT licensed
