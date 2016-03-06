![http://www.sph1re.fr/liquid/LCR.jpg](http://www.sph1re.fr/liquid/LCR.jpg)

This is a bugtracker for the Community ROM for the Acer Liquid based on Android 2.1.
Feel free to provide us suggestions here too :)

# Latest version is LCR-F 2.0 #

# BE CARREFUL : WE NOW HAVE OUR OWN WEBSERVER http://lcr-team.org #
Please go there to stay tuned



**Be sure to follow http://twitter.com/LCR_Updates to get notifications for updates!**

# If you have used apps2sd before, always do a WIPE SD in sdcard menu within the recovery before installing LCR #

<a href='Hidden comment: 
==QRCode for CM-Updater==

http://acer-liquid-community-rom-bugtracker.googlecode.com/files/qrcode.png



http://acer-liquid-community-rom-bugtracker.googlecode.com/file//qrcode_updateLCR_json_S.png

Cyanognenmod Updater is included in LCR since 1.4 and can be found on market
'></a>

---


The HowTo Install is here:
http://code.google.com/p/acer-liquid-community-rom-bugtracker/wiki/HowToRootAndFlashLiquidCommunityROM


---



Apps2SD HOW-TO: http://code.google.com/p/acer-liquid-community-rom-bugtracker/wiki/Apps2SD

<a href='Hidden comment: 
-------------------------------------------------------------------

Screenshots: http://picasaweb.google.com/c.brueggemann94/ScreenshotsOfTheROM

-------------------------------------------------------------------
'></a>

---




## IMPORTANT ##

**` If you encounter crash when accessing Accounts & sync, you need to do a factory reset, acore crash also. Factory reset, even if not required, will delete all incompatibiliy issues that could after restorin some application with apps like Titanium backup. Be aware than restoring datas from one version to another can produce crashed.Never restore system data or email data`**

# Always reboot at least once after installing and configuring a new rom or patch #



## Changelog: ##

---

### Current ###



**Please use bug tracker to indicate closed bugs, append to existing ones or open new issues. Thank you all**

__LCR\_E\_1.8.2patch2 (patch file to apply on top of LCR 1.8.2)
  * update to 1.8.2.2_

LCR\_E\_1.8.2.2 (full rom, wipe all)_
  * same as 1.8.2.1
  * fixed Filter Ads feature
  * Lcr Settings updated to 0.2 (fix slow issue + some translated parts)

**_LCR\_E\_1.8.2.1 (full rom, wipe all)_
  * same as 1.8.2 with updated apps**

**_LCR\_E\_1.8.2 (full rom, wipe all)_**

<table>
<tr>
<td><a href='http://img408.imageshack.us/i/previewpq.png/'><img src='http://img408.imageshack.us/img408/1944/previewpq.th.png' border='0' /></a></td><td><a href='http://img828.imageshack.us/i/device8.png/'><img src='http://img828.imageshack.us/img828/2979/device8.th.png' border='0' /></a></td>
<td><a href='http://img811.imageshack.us/i/device7.png/'><img src='http://img811.imageshack.us/img811/9158/device7.th.png' border='0' /></a></td>
<td><a href='http://img837.imageshack.us/i/device3t.png/'><img src='http://img837.imageshack.us/img837/5927/device3t.th.png' border='0' /></a></td>
</tr>
</table>

An overclocked kernel (up to 960 Mhz, use at you own risk) and the standard one (to revert) are available for download. Base kernel is not overclocked (safer)


Big big changes compared to previous version. The rom has never been so fast and so stable with a really good battery consumption.
It is difficults to make a changelog, there is many internal changes.
  * Based on 2.100.07 binary (was also tested on F 0.007 with success.)
  * Superuser updated to 2.3.6.1 (Credits to ChainDD)
  * New framwork with battery purcent fully customisable : battery a png (100 png for battery !), or activate it as a service that will overwrite current icon.
  * Global interface spedd improvement
  * Dialing tone is back !
  * Better sound on call (can be configurer via LCR Settings)
  * You can activate swap on ram (ramzswap) or on fat32 sdcard, or on both. You have full control
  * You can choose your dialer : Acer or AOSP one
  * You can choose your camera app : Liquid or Stream
  * You can switch off any UI sound
  * No need of patch for Arabic, Persian, Hebrew font : just tick a check and reboot
  * All the settings  are now done via a single application called LCR Settings. It will allow your do do a lot of think


View rom info, check for update, generate a log, report issues, tweak many parts of the rom (sound, battery indicator, filter ads....)
Fix common issues (gallery, market, su), Configure memory settings, reboot phone in normal, recovery mode
Flash a boot image, a new recovery, an update. Run a nandroid backup restore, uninstall/install apps in system (from local sdcard, our server or market
Change bootanimation, full theme manager with description and preview : just store you zip on sd and press the button...

We hope you will enjoy



## If you own a liquidE, you don't have to install any other bin file (but you need to have latest baseband) ##

<a href='Hidden comment: 
== To upgrade from 1.X  to 1.4, you need to install the new Acer_LiquidE_0.010.00_EMEA_GEN1 bin file first ==
bin file and howto are here http://code.google.com/p/acer-liquid-community-rom-bugtracker/wiki/HowToRootAndFlashLiquidCommunityROM

== To upgrade from 1.X <3 to 1.3, you need to install the new Acer_LiquidE_0.008.06_EMEA_GEN1 bin file first ==
bin file and howto are here http://code.google.com/p/acer-liquid-community-rom-bugtracker/wiki/HowToRootAndFlashLiquidCommunityROM
'></a>

### Previous ###

_**LCR\_1.8patch1**_ (patch file, not a full rom)
  * Fix some issues with some networking/tethering tools
  * Liquid tether should now work even if your provider tries to block you. If you "regenerate" files in Liquid Tether you will lose the correction for liquid tether.


_**LCR 1.8.0.1**_ (full rom, will wipe all)
  * Same as 1.8 with updated Titanium Backup (no more FC), esFileExplorer and LauncherPro
  * battery usage seems better
 don't forget "Mount /system/sd" before applying the patch if you use apps2sd 

_**LCR 1.8**_ (full rom, will wipe all)
  * Based on 1.100.39 bin (not on a stream dump) with fixed bugs
  * Strongly optimized
  * Really fast and stable
  * Superuser 2.2.2 (Credits to ChainsDD)
  * Hack by azuwis Use volume up/down keys as d-pad left/right
  * A lot of gscripts with shortcuts (you can choose you dialer by changeDialer.sh, and so one. put list here)
  * GPS settings tweaked for faster and better positioning
  * Enhanced sound (but no dolby yet)
  * Netfilter enabled and liquid tether provided (by Gengaro)
  * V8 Webkit from xaueious
  * Galaxy S Live Wallpaper (can be easily uninstalled)
  * Updated bootsplash + animation
  * Updated added applications
  * Modified autostart to run ramzswap
  * Added possibility to switch between AOSP and Acer diler
  * Cleaned/Updated scripts
  * And much more.......


---


_**From 1.7.2 to 1.7.3**_ (this version is a **patch**, not a full rom. Flash in on top of LCR 1.7, no data loss EXCEPT your launchers configuration (can be easily backed up) and updated apps)
  * Added Froyo Gallery3D (for real ;) )
  * fixed SD card issue
  * fixed dxdrm logging
  * modified setUIval.sh / getUIval.sh to be able to choose the requested setting table OK
  * ramzswap enabled
  * fixed filterAds.sh
  * modified audiocall.sh to add another audio filter (quiet to loud) OK
  * added a gscript to clean logs (logs are stored in /cache use about 100k/each boot) OK
  * updated apps
  * wake on camera (Credits to xaueious)
  * modified cleanRom : 30sec timer to let user poweroff the phone in case a wrong run + removed VoiceSearch + sendlog
  * addded sms.sh to backup/restore sms /system/sbin/sms.sh gscript OK
  * update uiconf tool with screenshots
  * no more freq limit
  * Google Maps moved to /data/app
  * Speed Up Android 2.1 Browser, Default javascript engine in Froyo. Enabled
animated GIF support (Credits to Auxx / g4rb4g3 / xaueious )

_From 1.7.1 to 1.7.2_ (this version is a full version). We advice you to install latest Acer Update to eclair first.

  * Fixed sound on call
  * New application to configure UI (developped by reppad grandgto@gmail.com)
  * Additionnal fonts were removed, so asian languages are back
  * Gallery app from froyo
  * Purge DxDrm logs on reboot
  * Purge aPanic on reboot
  * Wifi tethering (many thanks to gengaro86)
  * Fixed some UI issues
  * All apn were updated
  * Bluetouth file transfer
  * Added cleanROM.sh in gscript : will remove all 3rd apps included in the rom
  * Added filterAds.sh/unfilterAds.sh in gscript to remove adds
  * Added audiocallLoud.sh / audiocallStandard.sh / audiocallQuietToLoud.sh to change audiocall sound
  * Other fixes


_From 1.7 to 1.7.1 (for the moment only a patch is provided, not a full rom, so install it on trop of the 1.7. You won't lose any application or data._
  * Fixed battery usage (use full android UI, stream UI uses a lot a battery)
  * Audio hack for in call sound (a bit louder)
  * Fix sound reverb on app like Sipdroid
  * Fix slow gallery
  * Fix camera (note that zoom in camera is available when taking picture under 2M resolution)
  * Ability to use standard eclair AOSP dialer in LCR\_UI.txt
  * will remove Notes application (Titanium backup it before applying if you want to keep it)
  * Updated Google Maps 4.3
  * Updated sendlog
  * Updated Launcher Pro 0.6.3
  * Updated ADW 0.8.9 => If you slide up, status bar will hide/show. If you slide down, notification bar will display
  * Updated Titanium Backup 3.2.7
  * Updated android term


**To gain in space usage**, it is recommanded you **uninstall all updates** for these application before applying (they can be removed after but you won't have the preconf for launchers in this case).

ALWAYS DO A NANDROID BACKUP FIRST

Always reboot at leat once after first boot to be sure everything is well applied.


_From 1.6 to 1.7_
  * **based on Acer\_LiquidE\_1.100.05\_EMEA bin file. Flash THIS bin file before installing  Update recovery to at least 0.5.3 too**
  * Based on stream dump
  * New fully cusomizable User Interface : Notification type, notification position, dialer, lock screen (See the file LCR\_UI.txt on sdcard for more infos. To apply changes, just reboot. You will need to remove/re-add widgets after applying a change.  Use Stream lock stream will break widget refresh on reboot))
  * really faster than original bin and than 1.6
  * Incredible sound with Dolby Mobile
  * Read Divx / Xvid
  * New Camera app with a lot of settings
  * Voice Recognition
  * sensivity patch included but not applied (use gscript to load increaseSensitivity.sh and it will be applied permanently / to remove run restoreSensitivity.sh)
  * better open GL
  * black themed
  * optimized network for better performances (can be disabled)
  * fixed Bouygues Telecom MMS issues ([issue 78](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=78)) no more need to use Hancent to send mms.
  * fixed Add APN to list  ([issue 96](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=96))
  * fixed Sms notification sender is wrong ([issue 100](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=100))
  * fixed Wifi doesn't work after wake up ([issue 101](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=101))
  * fixed issue Phone stay in standby if switching from 3g to 2g  ([issue 102](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=102))
  * Launcher choice at startup (to unselect default one : Settings  / Application / Filter ALL / Select defaut launcher and choose 'remove default action' )
  * fixed Widget load on reboot
  * many optimizations (Framework, Contacts, Live wallpapers, Mms)
  * New bootsplash / bootanimation (thanks to paulf66)
  * New supported fonts : Greek, Cyrillic, Georgian, Armenian, Hebrew, N'ko, Tifinagh, Lao, Canadian Aboriginal Syllabics, Ogham, Arabic
  * updated HTC keyboard
  * update Launcher Pro and AWT Launcheradb shell
  * updated Maps 4.2
  * updated Barcode scanner
  * updated titanium backup 3.2.4
  * updated Deskclock Launcher
  * updated ES File explorer
  * updated ES Task manager
  * Updated quickboot
  * and more....
  * of course apps2sd is still here
  * **know bug** : if you use acer stream lock screen, your widgets won't refresh well. You will have to remove and re-add them after reboot.
  * **know bug** battery indicator will always indicate a little less battery than you really have. Use battery time lite widget for exemple to know the exact amount of battery available.
  * **know bug** : home decor and acer widget conf crash when selecting a not-included wallapaper or playing with the ball (this apps are nearly never userd)
  * **Chinese users need to install LCR-1.7\_chinese\_patch\_NO\_SIGN.zip** (install with NO SIGN check). This will remove support for newly added fonts.

  * If you have network issues with 2G/3G, you can disable network opitmizations with "adb shell network.sh standard". To re-enable optimizations : "adb shell network.sh high"

  * system will automatically reboot after first boot ( about 30s after sim panel ) : this is normal 

**Many thanks to Vache** who has joint LCR and worked on this rom.

**If you want better battery performance**, disable haptic feedback (use spare part) and vibration in HTC mod keyboard (keyboard settings / Text input / Vibrate on input)

**Launcher management**

To revert to the launcher choice when you have selected a default launcher : Settings / Applications / Filter ALL / Select defaut launcher and choose 'remove default action'

**You can remove integrated launcher** from the rom : run gscript lite / Option / Add script / Load file choose the removeXXXX.sh that suits your wish / Save /Run it.




_From 1.5 to 1.6_
  * **based on Acer\_LiquidE\_1.100.05\_EMEA bin file. Flash THIS bin file before installing is recommanded but you can also flash the rom on top of 0.14 or 0.16 bin. Update recovery to at least 0.5.3 too**
  * really faster than original bin
  * some battery optimizations
  * black themed (white theme patch will be provided)
  * optimized network for better performances (can be disabled)
  * fixed Bouygues Telecom MMS issues ([issue 78](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=78)) use Hancent to send mms.
  * Launcher choice at startup (to unselect default one : Settings  / Application / Filter ALL / Select defaut launcher and choose 'remove default action' )
  * many optimizations (Framework, Contacts, Live wallpapers, Mms)
  * added a Notes app
  * removed xt9
  * removed Voice search and accessibility tools
  * updated Maps
  * updated Barcode scanner
  * updated titanium backup
  * updated Deskclock Launcher
  * and more....

**Many thanks to Piter who has joint LCR**
If you want better battery performance, disable haptic feedback (use spare part) and vibration in HTC mod keyboard (keyboard settings / Text input / Vibrate on input)


_From 1.4.1 to 1.5_

  * **based on Acer\_LiquidE\_0.014f.01\_EMEA\_GEN1 bin file. Flash THIS bin file before installing or you will have no network and no adb access. Update recovery to at least 0.5.3 too**
  * really faster than original bin
  * AppsOrganizer, Cardock, Carmode, Tetherbot removed. Will be provided as addon pack
  * Themes will be provided as patch too
  * Acer apps removed
  * DeskClock Launcher (big thanks to Cedric Gatay)
  * Maps 4.1.1
  * Titanium backup 3.0.16
  * es File explorer 1.3.12
  * es Task manager 1.0.8.0
  * barcode scanner 3.22
  * Meridian player pioneer 0.16.0
  * fixed 3D games are slow or not working at all on 1.3.  ([issue 66](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=66))
  * fixed Compass doesn't work probably causing backwards navigation in all navigation programs ([issue 68](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=68))
  * fixed Compass doesn't work probably causing backwards navigation in all navigation programs ([issue 73](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=73))
  * fixed Keybord vibration not workingHTC\_IME  ([issue 75](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=75))
  * fixed Contacts pictures ([issue 77](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=77))
  * partially fixed Bouygues Telecom MMS issues ([issue 78](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=78)) change default,mms  to wap in settings to fix
  * fixed Message led is on if a notification icon in a taskbar  ([issue 79](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=79))
  * even better sound


_From 1.4.1 to 1.4_

**To upgrade from LCR 1.4, just flash the zip file. If you have not LCR 1.4 installed do a FACTORY RESET before flashing**

  * fixed vodafone it apn ([issue 73](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=73))
  * fixed Sometimes connection don't work after disabling/enabling data connection  ([issue 83](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=83))
  * fixed Clock alarm bug with daily alarm when it was first reapeted  ([issue 85](https://code.google.com/p/acer-liquid-community-rom-bugtracker/issues/detail?id=85))

_From 1.3 to 1.4_

> Video : http://www.youtube.com/watch?v=RHuL8-159q8 (thanks to fastreward)

  * Fully rebased on new bin (Acer\_LiquidE\_0.010.00\_EMEA\_GEN1)
  * BusyBox v1.16.0
  * Superuser 2.0.1 (Chain DD)
  * HTC IME with voice and mods (Jonasl)
  * New black theme (AdamZ - Baisangour)
  * New boot and wallpaper (Paul 66)
  * New boot animation (liquid\_it)
  * Helix 2 Launcher
  * Nemo player
  * Flac player
  * New calculator
  * NavLauncher => 2.2.4
  * Titanium backup => 3.0.4
  * MoreLocale => 2.2.0
  * AppsOrganizer => 1.4.10
  * Barcode Scanner => 3.22
  * GoogleMaps => 4.1.1
  * Removed facebook
  * Removed battery graph (addon)
  * Removed AutoKiller
  * Fixed Nexus Live wallpaper (bais)
  * Better Audio No distorsion at all (Metlus)
  * Added Flac support (AndLess)
  * Added Meridian Player Pioneer 0.15.3
  * Added Gscript lite : (change defaut launcher)

Big Big thanks to Paul66, Fastreward, Neo, Natsumi, Liquid\_it and all members that have supported this version. Thank you all. It's for you. Malez


_1.3 addon pack_ (LCR 1.3 required) = **Addon pack v3 fixed**
  * script to fix su request issues
  * clock weather widget (HTC style)
  * animated wallpaper (Earth / HTC Sense)
  * online wallpaper app
  * Original laucher with app/photo widgets from acer (use adb shell launcher stock/helixir/status  to switch)
  * NemoPlayer

See wiki page for pictures and documentation


_From 1.2.4 to 1.3_ **wipe made on install**

  * Rebuilt on new liquid Acer\_LiquidE\_0.008.06\_EMEA\_GEN1 bin (compatible with baseband A1-03.10.03 only)
  * Multitouch
  * Added more locale 2 for internationalization (settings in app list)
  * Added international keybord
  * Added titanium backup 2.9.7.4
  * Added tetherbot
  * Added navlaucher
  * Added more ringtones
  * Added sqlite
  * Bootsplash graphics by Cyril Bardelang
  * Of course fully working apps2sd

_From 1.2.3 to 1.2.4_ **factory reset recommended**

  * **compatible with ACER\_LiquidE\_0.004.01\_EMEA\_GEN1 bin only** (baseband A1-03.05.02)
  * **Do a factory reset to be sure to benefit of all fixes in this version**

  * auto fix boot if data/dalvik are symlink and no sd card
  * fixed MMS send
  * fixed memPrint
  * added cardock + carmode
  * added file explorer + task manager
  * added sendLog
  * added tetherbot.apk
  * added AppsOrganizer\_1.4.8.apk
  * added barecodeScanner.apk
  * added battery graph
  * removed auto flash malez recovery
  * added wysie contact
  * fixed sipdroid (if not uninstall/resinstall sipdroid)


_From 1.2.2 to 1.2.3_

BIG THANKS TO MALEZ FOR HIS HUGE CONTRIBUTIONS! :)

  * Voice Search is fixed!
  * Apps2SD will now check if there's enough space free on your SD
  * Apps2SD won't break if you don't have an app installed anymore
  * Apps2SD now can move dalvik-cache and data (data not recommended!) also (See Wiki for instructions)
  * ROM keeps the autostart log now
  * Added logboot to display all autostart logs
  * Added logbootclear to erase all autostart logs
  * Added memPrint command to display memory usage and settings
  * Fixed ins\_run and ins\_runOnce for args
  * Changed oom settings for less cpu and battery
  * Corrected log-debug for better structure of logs
  * No more need to reinstall update.zip after factory reset/data wipe
  * Automatic memory settings adjusted
  * Autokiller updated to 2.2 (personnal preset)
  * MapView fix which affected for example Places Directory (credit to shafty)

_From 1.2.1.1 to 1.2.2_

  * Fixed rights on autorun scripts
  * All apks are zipaligned on boot for even better performance



_From 1.2.1 to 1.2.1.1_

  * Boot logs are now stored in /data/logs/
  * Little boot speed up

_From 1.2 to 1.2.1_

  * Fixed terminal emulator FC
  * Added Quickboot

_From 1.1.1 to 1.2_

BIG CHANGES! Apps2SD wiki will be updated tomorrow by Malez on how-to switch apps2sd on :)

  * A lot of speed improvements
  * HelixLauncher with modifications! Thanks to Faruq!

  * Some apps moved to /data partition for easly uninstallation
    * SpareParts
    * AutoKiller - By ratson at htcpedia, thanks!
    * Maps Brut.ALL's hacked maps for Non-us navigation, thanks!
    * SetCPU

  * Apps2SD fully working with ON/OF/STATUS feature and auto fix (if sd fails on boot). - Big thanks to Malez for his work on this!

  * Terminal Emulator added for doing commands when you dont have access to a computer
  * Recovery flashed on first boot - Malez Recovery 0.2.1!
  * Zipalign of data on boot, lowers apps footprint which gives faster loading of them!
  * Some other things missed out!


_From 1.1 to 1.1.1_

Only slight changes..

- Exchange Calendar Sync

- Added Talkback, Kickback and Soundback

- Fixed T-Mobile US APN (Thanks to eVil)

- Fixed build number

- Nexus themed Launcher.apk

_From 1.0 to 1.1_

- Zipalign on-install, Thanks to Wes Gerner for that script

- SpareParts (added)

- Launcher2 replaced with Standard Android Launcher for more speed (Live Wallpapers are still working !!), update.zip provided for those who want it back look in downloads section - Thanks to DocRambone@xda for launcher

- Apps2SD with on/off feature (disabled by default) (You need an ext2 partition of course), read Wiki for guide howto activate - Thanks to LoxdevK, Cyanogen and more for that script


_From ACR to 1.0_

-Kept Acer's Contacts.apk as it provides an HTC like speed dialer and some other functions

-Nexus One bootlogo (Thanks to g4rb4g3) & bootanimation

-Removed the automatic wipe, if you have problems, please wipe first and retry!

-Zipalign on boot

-Increased VM Heapsize for speed

-Zipaligned and Optipng'ed all the apk's aka optimized them for speed :)