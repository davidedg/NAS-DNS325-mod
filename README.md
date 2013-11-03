NAS-DSN325-mod
==============

A set of mods to completely replace D-LINK DNS-325 NAS box firmware.



Recommended read order:

- Hardware and hack introduction: http://jamie.lentin.co.uk/devices/dlink-dns325/
	- Without his work, I would still struggle with ffp (Fonz fun plug) mod.

- u-boot/uboot.txt
	- Compile and install new U-Boot bootloader.

- rootfs-initramfs/rootfs-hdd.txt
	- Build a new RootFS for your device

- rootfs-initramfs/initramfs.txt
	- Compile Initramfs instructions

- kernel/compile-overlayfs-bt-sound.txt
	- Compile new Kernel instructions

- bt-sound/bt-sound.txt
	- Bluetooth and Sound support (NAS pairs to bluetooth speakers)

- mopidy/mopidy.txt
	- Use Mopidy to stream your playlists to bluetooth speakers.



ToDO:

- Clean documentation for UBIFS
- Document HDD installation (GDISK)
- Document Samba installation
- Document Minidlna installation
- Document OpenVPN installation
- Document Transmission-Daemon installation



CREDITS: please see each file the Credits section.
