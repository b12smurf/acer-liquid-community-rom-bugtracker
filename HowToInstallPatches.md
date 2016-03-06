#How to install provided patches

All files described here can be found in the downloads section http://code.google.com/p/acer-liquid-community-rom-bugtracker/downloads/list

# How to change you theme #

By default the theme is a black one but you can revert to standard white one.

Install using the recovery in the same way as you have installed LCR\_XXX-update.zip
  * LCR-1.6-white.patch.zip  (the white theme)
  * LCR-1.6-black.patch.zip  (the black theme - rom standard theme)

## Black Theme ##

![http://acer-liquid-community-rom-bugtracker.googlecode.com/files/blackPatch.jpg](http://acer-liquid-community-rom-bugtracker.googlecode.com/files/blackPatch.jpg)

## White Theme ##

![http://acer-liquid-community-rom-bugtracker.googlecode.com/files/whitePatch.jpg](http://acer-liquid-community-rom-bugtracker.googlecode.com/files/whitePatch.jpg)

# How to change the touch screen sensitivity #

The patch provided allow to increase the screen sensivity. It is provided in two different form :
  * a batch file (can be customized)
  * an update.zip (easier)

## How to apply patch ##

### Batch file sensitivity\_LCR1.6\_Shreps(batch file).zip ###


requires : windows computer + drivers + adb


It works under windows and requires that you have adb installed on you computer It allow you to specify the level of sensitivity you want.

Note that if your adb binanry in name adb-window.exe for exemple, you nedd to modifier the bat file to match your correct binary name.

  * Put both 2 file in the same directory as your adb tool
  * Plug your phone on USB
  * Under Windows Vista or Seven, right click on sensitivity\_install\_LCR1.6 => run as adminstrator, otherwise jsut click on it
  * Script will ask you the sensitivity level you want (25 is a good value). The less the value is, the more the sensibility is. Don't set less than 20


### update.zip file LCR\_1.6\_sensitivity\_patch(no sign).zip ###


Value is fixed to 25 (recommanded)

requires : malez recovery

  * Put the file on the root of your sdcard
  * reboot in recovery
  * flash/test menu
  * apply update.zip NO SIGN CHECK
  * select sensitivity\_LCR1.6\_Shreps(batch file).zip
  * install

## Change screen sensitivity when patch had been installed / Uninstallt the patch ##

To modify sensivity, re-execute the script in sensitivity\_LCR1.6\_Shreps(batch file).zip   and set another value. (can be done by hand to but it is easy with the bat file)

To uninstall run sensitivity\_uninstall\_LCR1.6 in the same way