    Reference Implementation of the 4.3.3 Kernel with BusyBox based initrd
==================================================================================


Find the binary files

-- latest kernel binary configured nearest to allmod for i686 w/MMX

    vmlinuz-4.3.3.yaintiuall_1601IV-686mmx-allmod

-- the initrd file with all above kernels modules
and the initrd with single busybox and all scripts as of repo initramfs

    yatiny-4.3.3.yaintiuall_1601IV-686mmx-allmod.gz
    
    yaunity.gz  


---------------------------------------------------------------
These binaries boot successfully into an OpenSuSE Tumbleweed-20151221 installation
without corrective parameters. Find the modules in the zp*.sfs file to extract to your
local installation to the /lb/modules/.../kernel directory under the init repository.

2016-01-24

Dieter Miosga    

Please derive and compile your own kernels and busyboxes according the publications
under the repository folders: 

kernels/

kernels/config-templates/

toolchain/busybox

