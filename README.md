# Magisk on VphoneGaga
Set up a proper minial Magisk on VphoneGaga virtual machine without patching boot image

VphoneGaga 32bit support only, 64bit will be support soon!

Good news for anyone who want to run Magisk on VMOS: Vphone have proper system and can run Magisk properly thanks to [emulator.sh](https://github.com/topjohnwu/Magisk/blob/master/scripts/emulator.sh) script by **topjohnwu**. Because VphoneGaga doesn't allow Magisk on init stage so I only put it run on late_start stage so Magisk modules cannot load which need to load after post-fs-data and before late_start stage. VphoneGaga kernel doesn't support mount namespace so impossible to make MagiskHide work. 

  1. Download `vmostool_magisk.zip`
  2. Import to VphoneGaga. You can find it at `/sdcard/Documents`, extract to any folder. For example here `/sdcard/Documents/vmostool_magisk`.
  3. Open Terminal app, grant superuser first by `su` command then run `sh <extracted_folder>/vphonegaga.sh`.
  
  For example run:
```
su
sh /sdcard/Documents/vmostool_magisk/vphonegaga
```
  4. Reboot the virtual machine.

     If you want to load Magisk then run this command:
```
su
magisk_root enable
```


Also reboot to make it work...
Download from http://github.com/HuskyDG/VMOSPro_RootXposed_Terminal
