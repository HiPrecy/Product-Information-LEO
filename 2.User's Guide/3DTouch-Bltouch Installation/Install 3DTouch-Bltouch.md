# 3DTouch/Bltouch Installation Guide

## Firmware Configuration

If you want to use 3DTouch or Bltouch , you need to config Marlin firmware. Comment FIX_MOUNTED_PROBE and uncomment BLTOUCH in configuration.h file

//#define FIX_MOUNTED_PROBE

#define BLTOUCH

Then compile and upload the firmware.

## Print 3DTouch/BLtouch Dock

The STL file is in this folder , its name is "BLtouch Dock.stl".

## Installation Guide

### Material

The picture below shows what we need to finish this installation. Extra , you need a knife to cut the ribbon. 

![material.jpg](images/material.jpg)

### Uninstall extruder 

Unscrew extruder either side screws

  ![](images\step1-1.png)

![](images/step1-2.png)

### Uninstall probe

Remember to plug it out from the motherboard

![](images/step2-1.png)

![](images/step2-2.png)

![](images/step2-3.png)

![](images/step2-4.png)

### Assemble 3DTouch/Bltouch

![](images/step3-1.png)

![](images/step3-2.png)

![](images/step3-3.png)

### 3DTouch/Bltouch Wiring

Assemble the extension cord (the white part shows), and put the cable into braided hose.

![](images/step4-1.png)

![](images/step4-2.png)

### Switch cable order

As the cable order in 3DTouch/Bltouch is different from the board servo pins , we need to do this extra work.

![](images/step5-3.png)

![](images/step5-4.png)

### Motherboard wiring

Wire the cable to the mother board , pay attention to the cable color and its position. You need to double check the cable orders , from left to right are (VDD GND SIG).

![](images/step5-1.png)

![](images/step5-2.png)

### Arrange cables

![](images/step6-1.png)

### Install extruder

![](images/step7-1.png)

![](images/step7-2.png)

### Fix extruder cable

![](images/step8-1.png)

### Done ! Congratulation ! 

## Note

As you can see , we test with the 3DTouch from FYSETC , so we recommend to use it:

https://www.aliexpress.com/item/32914352952.html?spm=a2g0o.productlist.0.0.359b2be7LzeP8K&algo_pvid=87206f20-28e8-4088-a71f-8d0e848c5695&algo_expid=87206f20-28e8-4088-a71f-8d0e848c5695-0&btsid=0bb47aa615888455642068451e019c&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

You also can choose Bltouch from :

https://www.antclabs.com/store