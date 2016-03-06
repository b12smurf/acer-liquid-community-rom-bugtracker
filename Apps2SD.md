# How to activate/deactivate Apps2SD on LCR #

# IMPORTANT NOTE #

**It is always safer to do a**nandroid backup (with ext parition)**before applying any of these operations on your system.**

If your **recovery** allows you to apply this oparation, it's safer to use it as system will be offline during operation. Malez recovery allow it since 0.4


Operations can take a very long time. While boot animation is still moving, don't worry. See last question for infos.

You must at least shutdown the phone once beetween 2 operations.

After a move, you will have to re-add your widgets to you desktop. Simply trash them, and readd them. If one app crash, try to uninstall and reinstall the application


```
Until LCR 1.2.2 (included), there is a bug when usings apps2 sd and there were not a least one app in app and one in app-private. This will be fixed soon. I am currently working on
Please Be patient

Moreover next version will include free space control before operation.

Thank you

Malez
```

## Introduction ##

apps2sd offers the ability to store your application on you sdcard instead or you phone internal memory.

The main advantage of this method is to increase the number of apps you can install on your phone by storing then a huge partition and SD card (generally 500 Mo). Moreover if you frequently flash roms that wipe your data partition, your apps will keep in a safe place on SD and you will just have to reactivate apps2sd after installation to restore your apps.

If you don't have space problems on you phone or don't frequently flash your phone, you don't really need this. You must know that if your apps are stored on sd, and the sd card is not present on boot, you will not have any apps. Fortunatly this case is now catched and the phone will boot !

So if you need space on phone
  1. move apps to sd (if that's not enough)
  1. move dalvik to sd (will free a little more space)
  1. move data to sd (not recommanded and won't be required)

## Requirements ##

LCR 1.2.3+

You must have an ext2/ext3 partition on your sd card for this to work. If that is not the case, please create an ext parition on your sdcard. This could be done in recovery mode.

## General usage ##

```
Usage
apps2sd version 2.2
Needs 'on' 'off' 'status' or 'cancel' as argument.
apps2sd on/off [--dalvik] [--data] [-e EXTRA]/status/cancel
apps2sd on --dalvik will also move dalvik-cache to sd
apps2sd on --data will also move dalvik-cache to sd
apps2sd off will restore apps /data and dalvik to phone
apps2sd off --dalvik will ONLY restore dalvik-cache to phone
-e EXTRA will check if there will be a leat EXTRA Kb of free space after move
by default EXTRA=20Mb
apps2sd cancel will cancel pending operations

```

<a href='Hidden comment: 
apps2sd off --data will ONLY restore data to phone
apps2sd off --dalvik and --data are exclusive
'></a>

## How to ##

**All operations described here must be done as root in a terminal emulator.**

So the first step is to launch "Terminal Emulator" application and then enter
```
su
```
or log via adb shell

**_Note that, after a change in location of apps, apps list will be refreshed in apps menu on the first open of the menu. Dalvik cache will also be rebuild. So first boot takes a long time._**

### Enable apps 2 sd ###

This will move your apps from phone to sd.
Apps already present on sd will be overwritten by those on phone.

```
apps2sd on
```

Then you will need to reboot your phone.
On reboot system will automatically move your apps to the sdcard, then it will reboot. That's why you will see a fixed X, then the moving X for 2 seconds, and then acer logo.

**Note** : by default dalvik cache is not moved to sd for performance. **Moving dalvik cache to sd card will make rom really slower**
If you want to move the davlik-cache to sd too, use
```
apps2sd on --dalvik
```

**Note** : by default data is not moved to sd. This directory contains apps specific parameters. **Moving data to sd card will make rom really slower** It is not recommanded.
If you want to move the data to sd too, use
```
apps2sd on --data
```

So if you want to move apps, data and dalvik to sd use
```
apps2sd on --data --dalvik
```

By default apps2sd will check wether there will be enough space on target after operation. By default operation will be done only if there will be an **extra free space** of 20Mb on target.
You can change this value using the -e EXTRA option.
EXTRA must be the number of Kb you want to be free after operation

For exemple :

```
apps2sd on -e 10000
```

Will move apps to the sd card only if there is at least 10000 Kb free space after operation.


### Disable apps 2 sd ###

This will move your apps/data/dalvik from sd card back to your phone internal memory.
Apps already present on phone will be overwritten by those on sd

```
apps2sd off
```

Then you will need to reboot your phone.
On reboot system will automatically move your apps from the sdcard back to phone, then it will reboot. That's why you will see a fixed X, then the moving X for 2 seconds, and then acer logo.

**Restore dalvik-cache to phone** : if you want to restore ONLY the dalvik-cache to your internal phone memory, use
```
apps2sd off --dalvik
```

## Warning ##


Don't use
```
apps2sd off --data
```
Or you will lose your apps
Use
```
apps2sd off
```
instead

**This will be fixed in 1.2.4**

<a href='Hidden comment: 

*Restore data to phone* : if you want to restore ONLY the data directory to your internal phone memory, (this may produce crash) use

```
apps2sd off --data
```

'></a>


**Note** : First boot will take a long time because, dalvik-cache will be rebuild

By default apps2sd will check wether there will be enough space on target after operation. By default operation will be done only if there will be an **extra free space** of 20Mb on target.
You can change this value using the -e EXTRA option.
EXTRA must be the number of Kb you want to be free after operation

For exemple :

```
apps2sd off -e 10000
```

Will move apps back to phone only if there is at least 10000 Kb free space after operation.

### Where are my apps stored / What are pending operations ? ###

This will describe you where are currently your apps stored and will display what are the pending operations.


```
apps2sd status
```

will display something like

```
=== APP2SD Status ===

ext partition is present on your SDCARD

/data/app is stored on your sdcard
/data/app-private is stored on your sdcard
dalvik-cache is on your sdcard

Pending operations :

-rwxrw-rw-    1 0        0              31 Mar 23 09:57 move_sd2apps
Reboot to apply
#

```

In this example our apps are stored on phone and will be moved to sd on next boot.


## FAQ ##

### My apps/dalvik are on my sd, my sd is broken/removed, what should I do ? ###

If you boot your phone without any sd and your apps are stored on sd, the system will detect it and will perform needed actions.

You will be able to boot but without any of your apps.

When you have restored your SD card, you can simply use "apps2sd on" (you don't need to add any other option). Reboot and control with apps2sd status.


### I have some application crash after a move ###

This king of little problems can happen. In this case, try to uninstall and reinstall the application. If there is too many apps, restore your nandroid backup and retry.

### How to cancel a pending operation ? ###

If you have a pending operation and you want to cancel it, you can use the rm\_runOnce command like this :

```
apps2sd cancel
```

For exemple

```
=== APP2SD Status ===

ext partition is present on your SDCARD

/data/app is stored on your phone
/data/app-private is stored on your phone

Pending operations :

-rwxrw-rw-    1 0        0              30 Mar 22 10:19 move_apps2sd
Reboot to apply
```

To cancel the move of apps to sd use

```
apps2sd cancel
```

If you place any apps2sd order (on or off), it will automatically replace any older one.

### It a long long time since I am waiting for my phone to boot and I have an error message in logcat telling me system will crash when booting ###

As long as you have standard messages in {{adb logcat}} you don't have to worry. Operation can take a long time.

If something goes wrong when restoring to phone. You will se a special message telling "system will crash". To fix this situation, try this command
` adb fixboot.sh `