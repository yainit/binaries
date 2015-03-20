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
  Next release >=3.18.9 with the corrected patches will be supplied
  with an INITRD file.
  
3.18.8.yainitgnuall-k8EM64T
  compiled for the Nocona core, 32bit binary, 
  containing all usual HDD (SSD/SATA) Drivers,
  can be booted without initrd :  root=PARTUUID=    rootwait
  See: kernels/3.18/Readme.md

3.16.7.yainituall33_44-k8EM64T
  compiled for the Nocona core, 32 bit binary, SSE3 cabable,
  serves with DOT.config-k8EM64T as  template for 64 bit as well,
  can be booted without initrd :  root=PARTUUID=    rootwait
  useful for all recent stable Ubuntu and OpenSuSE distibution releases.
