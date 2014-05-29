# Cryptobox #

A script that wraps **cryptsetup**, **mkfs** and **losetup** to make it easy to create, mount and unmount encrypted image files using LUKS.

## Usage ##

* **cryptobox**: displays the list of commands
* **cryptobox c filename.img filesystem size-in-mb**: creates an image file with a given filesystem and size in megabytes. (eg: `cryptobox c myimg.img ext4 128`)
* **cryptobox m filename.img /mount/point**: mounts a given image file on a given directory. (eg: `cryptobox m myimg.img /mnt/cryptoimg`)
* **cryptobox u /mount/point**: unmounts an image file from a given directory. (eg: `cryptobox u /mnt/cryptoimg`)

## License ##

This script is open source and licensed under the [GPLv3](http://www.gnu.org/copyleft/gpl.html).
