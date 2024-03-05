# Arch-Kernel-pkg-Clean
This Code emulate the pacman -Sc command only referred to the kernel packages
It works by getting all the file in /var/cache/pacman/pkg that start with 'linux' and that contains the word arch.
Once the list of file is generated ordered by filename ( ES: linux-arch2.1 will be on top of linux-arch2.2) it stores the number of elements in a variable and then use it in a for loop where it delete the file.

