# FlashGSI  #



### What is this ? ###

Since the releaes of Android 10, all (or at least most) phones are released with dynamic parititons, which is pretty straightforward, dynamic partitioning so OEMs can resize / add / delete partitions as their will. In current stages, most of the recoveries cannot flash a GSI directly in recovery, and people without a PC could not flash it with fastboot. This zip aims to solve the problem by flashing GSI using dd if.

### Why is this ? ###

This is made possible by ```dd if```. 

You can run the commands manually, but most people are lazy like me so I made a zip :p 

### How to use ###

Place the GSI inside /sdcard/ and name it gsi.img, so the full path should be ```/sdcard/gsi.img```

Reboot to recovery, flash the script, find the magic.

### Credits ###

[Aditya Singh](https://t.me/aditya_singh_07) - Quick scripting help // [henloboi](https://github.com/JamieHoSzeYui) - Creator of ZIP
  
### To-Do ###

Support dynamic phones that are A/B 

### Downlods ###

[Latest release](https://github.com/JamieHoSzeYui/dynamic-experiments/releases/tag/flashgsi) // [Release archives](https://github.com/JamieHoSzeYui/dynamic-experiments/releases/tag/flashgsi)


