# Requirements #

LCR 1.2+ for log-debug

# log-debug explanation #

log-debug is  a script that will log all activity on system/radio/event in 3 differents files on you sdcard.

The script requires to be launched as root, so su is needed.

Here is the log debug usage :

  * log-debug start  --> to activate logging
  * log-debug stop   --> to stop logging
  * log-debug status --> to know if logging is running

You can also use the short usage :

  * l on  --> to activate logging
  * l off --> to stop logging
  * l s   --> to know if logging is running



# How To #

## Access terminal ##

  * Start Terminal Emulator from your running phone
  * Then enter the following lines.
Press enter after each line!

If you want to run the following command via "adb shell", don't enter su.

## Enabling log ##

```
su
log-debug start
```

or

```
su
l on
```

## Disabling log ##

```
su
log-debug stop
```

or

```
su
l off
```

## Providing logs ##

The logs will show up on the SDCard root as :

  * debug\_events.log
  * debug\_main.log
  * debug\_radio.log

Upload them zipped together and attach them to your bugreport.
Thanks :)

# SendLog #

You can also you send log (available from market) and included since LCR 1.3.
When a crash occurs in an application, launch Sendlog app, choose time, send it.