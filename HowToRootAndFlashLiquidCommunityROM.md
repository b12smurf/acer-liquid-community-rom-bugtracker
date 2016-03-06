# Tutorial to install Froyo community rom (LCR-F) #

## Important ##

# If you have used apps2sd, always do a WIPE SD in sdcard menu within the recovery before installing LCR #


## Requirements: ##

<a href='Hidden comment: 
LCR 1.4 was *only* for Acer_LiquidE_0.010.00_EMEA_GEN1 bin file

LCR 1.3 was *only* for Acer_LiquidE_0.008.06_EMEA_GEN1 bin file

LCR 1.5 was *only* for Acer_LiquidE_0.014f.01_EMEA_GEN1 bin file.

'></a>

**for LCR-F and LCR-E, We strongly advice you to update to latest bin file using acer download tool.**

 LCR-F need a froyo bin to be installed first in order to work 



### You need to flash the latest bin file in order to have better radio/battery performance and the right partition scheme ###

### bin file ###

THIS IS THE LATEST AVAILABLE UPDATE !

Acer\_Liquid\_4.002.14\_EMEA-GEN1 (modified to be flashed with liquid A1 s100 too)
http://lcr-team.org/v1/index.php?site=files&file=30

OLD VERSIONS

Links to oldest bin are provided for information only or in case you can't find the bin

Acer\_LiquidE\_4.504b.00\_EMEA-GEN1\_05.01.05 (modified to be flashed with liquid A1 s100 too)
http://lcr-team.org/v1/index.php?site=files&file=19 http://www.multiupload.com/NE5A1DADNR

Acer\_LiquidE\_4.504b.00\_EMEA-GEN1\_05.01.05 (original version. Only for Liquid E)
http://lcr-team.org/v1/index.php?site=files&file=20

Acer\_LiquidE\_4.002.02\_EMEA-GEN1\_05.01.04 (modified to be flashed with liquid and liquidE) http://www.multiupload.com/IJXG1DN5PI

2.100.07.EMEA.GEN1\_A21E\_bi​n http://hotfile.com/dl/65961727/0​5c8d92/2.100.07.EMEA.GEN1_A21E_bi​n.zip.html

2.100.07.EMEA.GEN1\_A21E http://global-download.acer.com/GDFiles/OS/OS/OS_Acer_2.100.07.EMEA.GEN1_A21E_A.zip?acerid=634187549971957507&Step1=Smart%20Handheld&Step2=Liquid&Step3=Liquid%20E&OS=a02&LC=it&BC=Acer&SC=EMEA_17


Acer\_LiquidE\_1.100.05\_EMEA\_GEN1 http://www.megaupload.com/?d=MM62W37I

Acer\_LiquidE\_1.100.05\_EMEA\_GEN1 http://rapidshare.com/files/386463804/Acer_LiquidE_1.100.05_EMEA_GEN1_2fe3feb1f695fe0b8e22c09ae14544fd.bin.zip

Acer\_LiquidE\_1.100.05\_EMEA\_GEN1 http://www.4shared.com/file/fJ2Qn_iV/Acer_LiquidE_110005_EMEA_GEN1_.html

Acer\_LiquidE\_1.100.05\_EMEA\_GEN1 http://www.multiupload.com/6EY2O1VMZL

<a href='Hidden comment: 

Acer_LiquidE_0.014f.01_EMEA_GEN1 http://www.megaupload.com/?d=VYJWX4UT

Acer_LiquidE_0.014f.01_EMEA_GEN1 http://www.speedyshare.com/files/22311663/...1_EMEA_GEN1.zip



*Since LCR 1.4 you need to use the 0.010 bin file. If you are using the old one (Baseband A1-03.05.02 or A1-03.10.03), you have to reflash the new bin first (Baseband A1-03.12.01)* To know what baseband your are currently using ggo in Settings/About phone/Baseband.

http://www.megaupload.com/?d=FIKQQVSU Acer_LiquidE_0.010.00_EMEA_GEN1

http://www.4shared.com/file/0pt2IgPK/Acer_LiquidE_001000_EMEA_GEN1_.html Acer_LiquidE_0.010.00_EMEA_GEN1 (mirror)

*Since LCR 1.3 you need to use the new bin file. If you are using the old one (Baseband A1-03.05.02), you have to reflash the new bin first (Baseband A1-03.10.03)* To know what baseband your are currently using ggo in Settings/About phone/Baseband.

'></a>


<a href='Hidden comment: 
http://www.mediafire.com/?eityv5dynnn Acer_LiquidE_0.008.06_EMEA_GEN1
'></a>

### Drivers ###

Will be installed by acer update tool

Links provided for information only

http://www.megaupload.com/?d=E5PTHL3O Acer Liquid drivers for Windows

http://www.4shared.com/file/pkdJ9oQQ/AcerLiquidDrivers.html Acer Liquid drivers for Windows

No more needed
http://www.megaupload.com/?d=EF2QNANO Acer A1 Download Tool

<a href='Hidden comment: 
http://rapidshare.com/files/362960867/Superboot.zip Superboot
'></a>

=== Superboot (don't flash the boot.img / don't run install-superboot-windows.bat
) ===

http://acer-liquid-community-rom-bugtracker.googlecode.com/files/Superboot.zip Superboot.zip


Our latest ROM, look for it here:
<a href='Hidden comment: 
http://code.google.com/p/acer-liquid-community-rom-bugtracker/downloads/list
'></a>
http://lcr-team.org/v1/index.php?site=files&cat=1

## How to install ##

# Important : If you have used apps2sd before installing, always do a WIPE SD in the sdcard menu of the recovery before flashing LCR #

**Note that if you use the superboot.zip, it will install an old version of malez recovery image that may not work with your bin file. Check here http://code.google.com/p/acer-liquid-malez-recovery/ to benefit of latest enhancements**
###  ###

### Installing the bin file ###

**1)**
Unpack the drivers.

If you have a 32-Bit version of Windows, go to the folder x86, if you have a 64-Bit version, go to the x64 folder.

Then run the setup.exe and follow the instructions.

**2)**
Unpack the Acer A1 Tool.

**important :** under windows Vista / 7 : choose Windows XP compatibility mode and "run as administrator"

Run the ACER Download Tool. Click "Browse" and select the downloaded ACER\_LiquidE...bin.
Attach your Acer Liquid and press Start. It should start flashing the stock Éclair image.

Don't interrupt this process!! In case of communication error during flash process. You can unplug and replug usb, don't power off the phone.


### Installing recovery and LCR-F rom ###

**1)**
Unpack the Superboot.zip.

**2)** Check here http://code.google.com/p/acer-liquid-malez-recovery/ if a new revovery version is available. Now an easy installer and installation script are available. Choosing them will make installation easier. If your phone is a Liquid Ferrari, you need to download malezRecovery\_X\_liquidFerrari.img.

**3)**
Boot your phone in normal mode and enable usb debugging in settings/Apps/Developpement

**4)** Put our latest ROM .zip into the root of the SDCard. You will find our latest rom in the [download section](http://lcr-team.org/v1/index.php?site=files&cat=1) of our new site http://lcr-team.org (or on this site for old LCR-E (eclair) rom. Rom is about 110Mo for Froyo.
(Rom files are named LCR-X\_Y-signed.zip where X is S for stream base, E for eclair, and F for froyo and Y is the version number.)

To access you sd card from your computer, slide down the notification bar and choose the appropriate item.(It must be something like "Connected to an usb cable, activate to copy file")

**5)** If you have choosen to download **installMalezRecovery\_X\_FULL.exe**, you just have to run it when the phone is in normal mode and recovery will be installed. Then you can **go to step 7 directly**.
Otherwise, if you don't use an installer (or if no installer is provided for your phone model, like Ferrari), take the malez\_recovery\_XXXXXX.img file and put it in in the unpacked directory and rename it to recovery.img.
Then reboot your phone in bootloader mode using reboot-bootloader-windows.bat" (windows) or launch "sh reboot-bootloader-linux.sh, or adb reboot bootloader

**6)** Run the "install-recovery-windows.bat" (windows) or "sh install-recovery-linux.sh" (linux)

This will install a custom recovery and reboot your device.

**7)** Reboot in recovery mode.
Double-Click the file "reboot-recovery-windows.bat" (windows) or launch "sh reboot-recovery-linux.sh, or use "adb reboot recovery" (both)

Then wait until the device is rebooted into recovery.

**8)** Choose "wipe" / "wipe data/factory reset" with menu button and apply with home button. Go back to main menu with < button.

**9)** Navigate to "flash/test menu" / "apply any .zip from SD" and push the menu key, and then choose the ROM and press menu again. Press home to start flashing

Wait for the installation to finish.

Reboot.

Congrats, you're done!

## Factory reset / Data wipe ##

In case of crash while accessing sychronization settings, you need to do a Factory reset.

In case you wipe your data partition (factory reset) and your LCR version os prior to 1.2.3, you need to reinstall the rom update.zip file. Just apply the zip file in recovery mode.

## Bootloader mode ##

If one of the script just keep blocked on 'waiting for device' and you phone is connected, just control that it is booted in bootloder mode.
It a black scrren with a white moving-line on top.

Here is the button conbination to force the boot in fastboot mode.

  1. Unplug the phone from usb
  1. Press Volume Up + Camera button + Power button
  1. The phone will vibrate twice but stay turned off
  1. Take the battery out, and plug the phone into the computer again using the usb cable.
  1. Phone will boot in bootloader mode

If you don't see this and the phone turns back on as normal, try it again.

  1. replace the battery.