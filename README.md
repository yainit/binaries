#			Binaries			

precompiled kernels with modules in compressed folder form
as squashfs file.
Uncompress on your distro with 

unsquashfs 

--------------------
Available Versions:
--------------------

3.18.8.yainitgnuall-allmod-686mmx
  nearest allmodconfig with PAE/TSC and Pentium-Pro MMX support
   
3.18.8.yainitgnuall-k8EM64T
  compiled for the Nocona core, 32bit binary, 
  containing all usual HDD (SSD/SATA) Drivers,
  can be booted without initrd :  root=PARTUUID=    rootwait
  See: kernels/3.18/Readme.md

