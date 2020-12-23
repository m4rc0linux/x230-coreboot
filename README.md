# x230-coreboot

coreboot V 4.13 rom for thinkpad x230 featuring seabios v. 1.14.0 https://seabios.org/Releases#SeaBIOS_1.14.0

commit 5c186c6777c9438ff4681929c9c25c98dee28bef

Secondary payloads added https://www.coreboot.org/Payloads

Nvramcui

Coreinfo: https://www.coreboot.org/Coreinfo

Nemtest: https://www.coreboot.org/Memtest86

Tint: https://www.coreboot.org/Tint

12m image for the x230, with vga in "native" mode, seabios and all the secondary payloads added.

seabios time-wait-menu reduced to 1 second only.

Bootspash added.

me.bin file has been me_cleaned

If running skulls and wish to update to my built it is possible to flash it internally. 

For me worked:

sudo flashrom -p internal:laptop=force_I_want_a_brick -w m4rc0x230.rom --ifd --image bios -V

To compile a different version the "config" file could be a starting point.

To see how this (or my others built images) works, just have a look into my youtube https://www.youtube.com/user/marcolinoxz
