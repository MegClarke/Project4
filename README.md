# Hey! I'm Filing Here

Meagan Clarke, UID: 706058350
In this lab, I successfully implemented a replica of a ext2 file system with 2 directories, 1 regular file, and 1 symbolic link.

## Building
make
mkdir mnt //creates a directory to mnt your filesystem to 


## Running
./ext2-create
sudo mount -o loop cs111-base.img mnt

//to test use
fsck.ext2 cs111-base.img 

//to debug use
dumpe2fs cs111-base.img


## Cleaning up
sudo umount mnt
rmdir mnt 
make clean
