# SVD (Simple Vesc Display)
Simple Vesc Display based on esp32 

Arduino compatible FW
low HW cost (any esp + any display that is supported by the tft library)
It was designed on a 2.2" 320x240 ili9341
TESTED on vesc 6.02

It uses :
tft_eSPI from https://github.com/Bodmer/TFT_eSPI
FlickerFreePrint from https://github.com/KrisKasprzak/FlickerFreePrint
VescUart from https://github.com/SolidGeek/VescUart
and the old but good EEPROMAnything



Installation : 

1. copy tft_eSPI into Arduino\libraries\folder (eg. C:\Users\User\Documents\Arduino\libraries\TFT_eSPI)
2. copy VESCUART into Arduino\libraries\folder (eg C:\Users\User\Documents\Arduino\libraries\VescUart)
3. copy PNGDEC  into Arduino\libraries\folder (eg.C:\Users\User\Documents\Arduino\libraries\PNGdec)
4. copy FlickerFreePrint into  Arduino\libraries\folder  (eg: C:\Users\User\Documents\Arduino\libraries\FlickerFreePrint)

ps. im no programmer by any units of measurements.
all the code was inspired from roxie and davega 
