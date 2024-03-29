# N64-Gameshark-Pro-REF1329
An optimized PCB for the N64 Gameshark Pro as well as the full schematic. This revision has full parallel port functionality. The Gameshark Pro v3.3.bin file should be programmed with the low bytes to the bottom SST and the high bytes to the top SST. The schematic includes the PIC12C508A and associated pull-up resistors that were never shipped with commercial units, though the footprints and traces exist on all commercial units. Details on the functionality of the PIC12C508A can be found [here.](https://github.com/parasyte/picard) Due to the PIC12C508A never having been implemented in the firmware of the N64 Gameshark, I have not included the associated footprints and traces on the optimized PCB.

The LZ9FC17 GALs are the same between PCB revisions. If you have a Gameshark with a Smart Card port on the back, you can migrate everything to this PCB and have a working parallel port. 

I have fully reverse engineered the LZ9FC17 GAL and implemented it in the [N64 Gameshark Clone](https://github.com/RWeick/REF1329-N64-Gameshark-Clone). 

PCB Thickness: 1.2 mm

![image](https://github.com/Modman/N64-Gameshark-Pro-REF1329/blob/main/REF1329-GS.png)
