Disclaimer: Don't use this if you don't know what nethunter is and/or you don't know what you are doing. 

If you don't know what kernel is then don't flash it. 

You must know about it if you want to flush, otherwise. don't do it.

After doing this, if your phone gets bricked or if there is any problem with the phone, I will not be responsible for this file in any way, do it entirely on your own.


How to install kernel: 
---------------------------------------------------------------

⚠️It has only been tested running Android version 12.So 
it will work properly on Android version 12.
You can test if it works on other Android versions and let us know and we will add it.

⚠️ it's has only been tested running MIUI 12.××× and 13.0.6. 

------------------------------------------------------------------------------------------
1) you need to download the Kernel

2) must be sure your phone bootloader is unlocked 

3) Flash TWRP custom recovery with PC otherwise Android phone

4) Flash Magisk Zip with Twrp Recovery latest version

5) Reboot your phone setup magisk and check your phone is now successfully to Rooted.

6) Again reboot your phone to TWRP recovery must be backup to your currently kernel than flash Kali Nethunter kernel zip file.


After the Kernel is completely flushed, go to the mobile settings and check whether the name of the set has changed after flashing the Kernel. If the name changes, then you are sure.

If you want to use Kali NetHunter, you must install Busybox  on your phone, Busybox  is not provided in the kernel file . If you want you can install Busybox  from playstore or flash Busybox  zip through magisk. I would suggest flashing the zip!

## For Zip busybox:
https://github.com/Magisk-Modules-Repo/busybox-ndk

## Download and setup some Busybox  for your phone that works on your phone: 

🖇️

1.  https://play.google.com/store/apps/details?id=stericson.busybox

2. https://play.google.com/store/apps/details?id=com.jrummy.busybox.installer

3. https://play.google.com/store/apps/details?id=ru.meefik.busybox


## After flashing Busybox  or after installing Busybox  from playstore and setup, you can check if Busybox  is installed on your phone with this application: 

🖇️ https://play.google.com/store/apps/details?id=com.joeykrim.rootcheck


Once this is done, if you want to do wifi testing from your phone / use wifi adapter / bluetooth adapter / HID Device / Rucky / rubber ducky / USB HUMAN INTERFACE DEVICE / then flash the wifi framework zip using magisk 

 Flashing this framework zip is mandatory for doing all kinds of hardware related testing through your mobile.
 
 
## Link above 🖇️🖇️
https://forum.xda-developers.com/t/module-wireless-firmware-for-nethunter.3857465/

https://github.com/rithvikvibhu/nh-magisk-wifi-firmware

## If you don't know how to flash Wi-Fi framework with magisk then you can watch this video of mine
https://youtu.be/Ssgt1viwb2U


## Download Kali Nethunter latest version 
https://kali.download/nethunter-images/

This video shows how to download kali netHunter:

https://youtu.be/HHMo7UXf0V4

----------------------------------------------------------------------------------------
after flash kali netHunter than you need to give permissionpermission to use kali netHunter: 
Open kali terminal
click Androidsu 

``` echo "FIX NETHUNTER PERMISSIONS"

echo "in Android 12"

pm grant com.offsec.nethunter android.permission.ACCESS_FINE_LOCATION 

pm grant com.offsec.nethunter android.permission.ACCESS_COARSE_LOCATION

 pm grant com.offsec.nethunter android.permission.READ_EXTERNAL_STORAGE

 pm grant com.offsec.nethunter android.permission.WRITE_EXTERNAL_STORAGE

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT 

pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_SU

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_NH

 pm grant com.offsec.nethunter com.offsec.nhterm.permission.RUN_SCRIPT_NH_LOGIN

clear

sleep 3

echo "done"


