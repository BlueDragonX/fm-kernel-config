Kernel Configuration
====================
These are the kernel config files used across my computers. Here they reside in hopes that they're useful to someone else. They will need some amount of modification to work for you. At minimum these should include network and graphics drivers.

Naming
------
The config files are named PURPOSE.TYPE where PURPOSE is what it's for (a hostname, hardware platform, or base for base image) and TYPE is the type of kernel it's for (vanilla, aufs, gentoo, etc).

Purposes
--------
- *base*: This is a generic x86-64 kernel with a handful of options enabled and most of then disabled. It's meant to work on fairly new systems. Hardware support includes: AHCI; USB 1.1, 2.0, and 3.0; and HD Audio.
- *leviathon*: MacBook Pro Retina 15" first gen laptop.
- *makara*: Acer Aspire One (Intel Atom with Intel chipset).
- *scylla*: AMD Athlon/Phenom X4 system with Radeon graphics.
- *tiamat*: nVidia ION system (Intel Atom with nVidia chipset and graphics).
