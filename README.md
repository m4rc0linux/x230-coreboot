# x230-coreboot
coreboot built for thinkpad x230.

12m image for the x230, with vga in "native" mode, seabios and all the secondary payloads added.

seabios time-wait-menu reduced to 1 second only.

Bootspash added.

me.bin file has been me_cleaned

If running skulls and wish to update to my built it is possible to flash it internally. 

For me worked:

sudo flashrom -p internal:laptop=force_I_want_a_brick -w m4rc0x230.rom --ifd --image bios -V

To compile a different version the "config" file could be a starting point.

To see how this (or my others built images) works, just have a look into my youtube https://www.youtube.com/user/marcolinoxz
