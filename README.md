# Cryptobox #

A script that wraps **cryptsetup**, **mkfs** and **losetup** to make it easy to create, mount and unmount encrypted image files using LUKS.

## Usage ##

* **cryptobox**: displays the list of commands
* **cryptobox c filename.img filesystem size-in-mb**: creates an image file __filename.img__ with the filesystem __filesystem__ and size of __size-in-mb__. eg: `cryptobox c myimg.img ext4 128`
* **cryptobox m filename.img /mount/point**: mounts the image file __filename.img__ on the directory __/mount/point__. eg: `cryptobox m myimg.img /mnt/cryptoimg`
* **cryptobox u /mount/point**: unmounts the image file mounted on the directory __/mount/point__. eg: `cryptobox u /mnt/cryptoimg`

## License ##

This script is open source and licensed under the [GPLv3](http://www.gnu.org/copyleft/gpl.html).
