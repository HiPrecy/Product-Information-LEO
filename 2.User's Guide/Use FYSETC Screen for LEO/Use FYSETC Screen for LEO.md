# Use FYSETC Screen for LEO

You may already bought a DGUS screen from FYSETC , but you can't flash HiPrecy LEO screen firmware for this screen because FYSETC use a different folder named "SCREEN" to flash their customized firmware. And this guide will show you how to flash HiPrecy LEO firmware for FYSETC screen. **But you need to know that once you done the steps below , you can't flash FYSETC screen firmware anymore**. As they use different core file.

## Change the screen core file

I already share the core file named "T5UID1_V25.BIN" in the "SCREEN" folder. All you need is flash this core file to the screen. You need to copy "SCREEN" folder to your micro SD card , and insert it to FYSETC screen SD slot. And then power on the screen. And wait for the first line of the screen “SD Card Process... END!” shows up. Then power off the screen and pull out the SD card. Now you already changed the screen core file. 

## Flash HiPrecy LEO screen firmware

After core file changed , you need to delete the "SCREEN" folder in the SD card, and then you can follow LEO screen firmware update steps.

https://github.com/HiPrecy/Product-Information-LEO/blob/master/8.Firmware%20update/touchlcd.pdf

