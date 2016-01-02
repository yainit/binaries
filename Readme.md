    Reference Implementation of the 4.3.3 Kernel with BusyBox based initrd
==================================================================================


Find the binary files

-- latest kernel binary configured nearest to allmod for i686 w/MMX

    vmlinuz-4.3.3.yaintuall_1512II-686mmx-allmod

-- the initrd file with all above kernels modules
and the initrd with single busybox and all scripts as of repo initramfs

    yatiny-4.3.3.yaintuall_1512II-686mmx-allmod.gz
    
    yatiny.gz  


---------------------------------------------------------------
These binaries boot successfully into an OpenSuSE Tumbleweed-20151221 installation

2016-01-02

Dieter Miosga    

Please derive and compile your own kernels and busyboxes according the publications
under the folders: 

kernels/

kernels/config-templates/

toolchain/busybox

