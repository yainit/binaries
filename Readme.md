    Reference Implementation of the 4.3.3 Kernel with BusyBox based initrd
==================================================================================

Find the binary files

1. latest kernel binary configured nearest to allmod

vmlinuz-4.3.3.yaintuall_1512II-686mmx-allmod

2. the initrd file with all above kernels modules
and the initrd with single busybox and all scripts as of repo initramfs

yatiny-4.3.3.yaintuall_1512II-686mmx-allmod.gz
yaunity.gz  


2016-01-02
Dieter Miosga    

Please derive and compile your own kernels and busyboxes according the publications
under the folders: 
kernels/
kernels/config-templates/
toolchain/busybox

