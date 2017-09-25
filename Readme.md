    Reference Implementation of the 4.3.3 Kernel with BusyBox based initrd
==================================================================================


Find the binary files

-- latest 4.3 kernel binary configured nearest to allmod for i686 w/MMX

    vmlinuz-4.3.3.yaintiuall_1601IV-686mmx-allmod

-- the initrd file with all above kernels modules
and the initrd with single busybox and all scripts as of repo initramfs

    yatiny-4.3.3.yaintiuall_1601IV-686mmx-allmod.gz
    
    yaunity.gz  

--------------------------------------------------------------------------

    Reference Implementation of the 4.8.5 Kernel with BusyBox based initrd
==================================================================================


-- latest 4.8 binaries for generic32-SSSE3 archs and AMD-15h-AVX(Bulldozer,..,Kabini,Godavari) with modules

   vmlinuz-4.8.5.yainitiuall_1610IV-k15bd1234
   
   vmlinuz-4.8.5.yainitiuall_1610IV-3se3
   
   zp-4.8.5.yainitiuall_1610IV-k15bd1234-xz.sfs
   
   zp-4.8.5.yainitiuall_1610IV-3se3-xz.sfs
   

--------------------------------------------------------------------------

    Reference Implementation of the 4.9.50 Kernel with BusyBox based initrd
==================================================================================


-- latest 4.9 binaries for i686 with mmx and generic64-westmere SSE4 archs 

   vmlinuz-4.9.50.yainitiuall_1709I-i686mmx 
   
   vmlinuz-4.9.50.yainitiuall_1709I-core64
   
   zp-4.9.50.yainitiuall_1709I-i686mmx-xz.sfs
   
   zp-4.9.50.yainitiuall_1709I-core64-xz.sfs
   

--------------------------------------------------------------------------

    Reference Implementation of the 4.12.11 Kernel with BusyBox based initrd
==================================================================================


--- latest binaries for generic64 archs with modules, made with OpenSuSE-Leap-42.3 asof 8/2017

     vmlinuz-4.12.11.yainitiuall_1709I-gen64

     zp-4.12.11.yainitiuall_1709I-gen64-xz.sfs



---------------------------------------------------------------

These binaries boot successfully into an OpenSuSE Tumbleweed-20160512 
and Slackware-14.2-x86_32 installation
without corrective parameters. 
Find the modules for 4.x in the zp*.sfs file to extract to your
local installation to the 
/lib/modules/.../kernel 
directory under the init repository.
Use 'unsquashfs' at the system prompt to extract modules and copy to
/lib/modules/`uname -r`/
after booting the kernel to console.   

2017-09-25

Dieter Miosga    

Please derive and compile your own kernels and busyboxes according the publications
under the repository folders: 

kernels/

kernels/config-templates/

toolchain/busybox

