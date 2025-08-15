# ASUS-H97-Plus setup for MacOS
EFI folder (sans serials) for MacOS


As the title says, I've included my current (as of Sequoia 15.6 / Opencore 0105) EFI folder for the Asus H97 Plus. It has had commendable performance for years. The hardware includes
- an Intel AX210 PCIE Wifi card
- a Radeon RX 580 GPU in the slot closest to the CPU

Please note: as this is a dual-boot (Manjaro/MacOS) system running KVM/QEMU, there is a second GPU is the last PCIe slot which is passed-through in Linux; one of the Device Properties in the config.list disables this NVIDIA Quadro so that it is not active for MacOS (you can delete the entry for your system).

Everything works, sleeps/wakes/WOL are fine. Hope this helps someone, somewhere, sometime.

Greetings from Athens.

P.S. Who knows, maybe it can be upgraded for Tahoe some day ;-)
