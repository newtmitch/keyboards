Run EasyAVR to build the hex file. The .dat file is the saved EasyAVR layout that you can load and modify.

To load the hex file:

```
sudo dfu-programmer atmega32u4 erase; sudo dfu-programmer atmega32u4 flash ./myhexfile.hex; sudo dfu-programmer atmega32u4 start
```
