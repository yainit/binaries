#			Binaries			

precompiled kernels with modules in compressed folder form
as squashfs file.
Uncompress on your distro with 

unsquashfs 

--------------------
Available Versions:
--------------------

yatiny.gz
  INITRD file containing the logic to specify kernel commandline parameters
  for booting to any block devices for any distro specified.

3.18.10.yainituall-k8EM64T
  compiled for the Nocona core and higher, 32bit binary, 
  containing all usual HDD (SSD/SATA) Drivers,
  can be booted without initrd :  root=PARTUUID=    rootwait
  See: kernels/3.18/Readme.md

3.18.10.yainitu14_15all-k8EM64T
  the Ubuntu kernel with all patches available,
  compiled for the Nocona core and higher, 32bit binary, 
  containing all usual HDD (SSD/SATA) Drivers,
  can be booted without initrd :  root=PARTUUID=    rootwait
  See: kernels/3.18/Readme.md

3.16.7.yainituall34_45-k8EM64T
  compiled for the Nocona core and higher, 32 bit binary, SSE3 cabable,
  serves with DOT.config-k8EM64T as  template for 64 bit as well,
  can be booted without initrd :  root=PARTUUID=    rootwait
  useful for all recent stable Ubuntu and OpenSuSE distibution releases.
  This version is without EFI support to avoid more vulnerability by 
  BIOS Viruses when used at changing hardware (Memstick@travel - or so). 
