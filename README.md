adb devices

adb shell

whoami

pwd

cd /data/system

ls

sudo rm V

rm getekeeper.passwords.key

rm locksettings.db

rm locksettings.db-shm

rm locksettings.db-wal

log-files.xml

-------------------------------------------------------------------------------------------------------------------------


![REAL GHOST (2)](https://github.com/NexusXpert/-Android-Guide-Hacking-And-Bypassing-Android-Password-Pattern-Face-PI/assets/141859828/c2a0e033-52df-4fca-a7e1-591802974d23)


Download the Pattern Password Disable zip file from the attachments.

Connect your phone to your computer using a USB cable.

Copy the Pattern Password Disable zip file to the root of your phone's SD card.

Disconnect your phone from your computer.

Turn off your phone.

Press and hold the Volume Up button and the Power button at the same time.

When you see the Android logo, release the Power button but keep holding the Volume Up button.

You will now be in Recovery Mode.

Use the Volume buttons to scroll down to Install.

Press the Power button to select Install.

Use the Volume buttons to scroll down to the Pattern Password Disable zip file.

Press the Power button to select the zip file.

The zip file will now be flashed to your phone.

Once the flashing is complete, your phone will reboot.

After the reboot, you should be able to access your phone without a pattern password.
-------------------------------------------------------------------------------------------------------------------------
https://youtu.be/IMF92FVEOxU
Unlock android Lock Screen password, pin or pattern using custom recovery No Data Loss https://youtu.be/0BT2dZfyMHI
how android lock screens are bypassed! I For educational purposes only https://youtu.be/U3hO-6kKXyw

-----------------------------------------------------------------------------------------
METHOD 2
:

INSTRUCTIONS:

Primary Step for all method:
Download & Extract to anywhere - Bypass Security Hack (Download from attachments)
Open SQLite Database Browser 2.0.exe in SQLite Database Browser.
Run pull settings.db.cmd inside By-pass security Hacks folder to pull out the setting file out of your phone.
Drag settings.db and drop to SQLite Database Browser 2.0.exe program.
Navigate to Browse data tab, At table there, click to list down the selection & selete secure

Instruction To Remove Pattern Lock:
Now, find lock_pattern_autolock, Delete Record
Close & save database
Run push settings.db.cmd and reboot your phone

Instruction To Remove PIN Lock:
Now, Find Or Create lockscreen.password_type, double-click & change it's value to 65536, Apply changes!
Now, find lock_pattern_autolock, Delete Record, If doesn't exist, Ignore
Close & save database
Run push settings.db.cmd and reboot your phone

Instruction To Remove Password Lock:
Now, find lockscreen.password_salt, Delete Record
Now, find lockscreen.password_type, Delete Record
Close & save database
Run push settings.db.cmd and reboot your phone

Note : If You See The Gesture Pattern Grid Or Password After Restarting, Don't Worry. Just Try Any Random Pattern Or Password And it Should Unlock.


-----------------------------------------------------------------------------------------
METHOD 3

(Cwm, Twrp, Xrec,Etc...) Installed:

INSTRUCTIONS:

1. Download this zip Pattern Password Disable (Download from attachments) on to your sdcard (using your PC, as you cant get into your phone, right )
2. Insert the sdcard into your phone
3. Reboot into recovery mode
4. Flash the zip
5. Reboot
6. Done!

Note : If You See The Gesture Pattern Grid Or Password After Restarting, Don't Worry. Just Try Any Random Pattern Or Password And it Should Unlock.

----------------------------------------------------------------------------------------

METHOD 4
Solution For Everyone Without Recovery Installed - ADB :

What You Need:
=>A computer running a Linux distro or Windows+Cygwin
=>USB cable to connect your phone to the PC
=>Adb installed

How to install adb:
1. Open Terminal
2. Type:
Code:
sudo apt-get install android-tools-adb
Hit [Enter]
3. Follow the instructions until everything is installed.


---------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------

![2-removebg-preview](https://github.com/NexusXpert/-Android-Guide-Hacking-And-Bypassing-Android-Password-Pattern-Face-PI/assets/141859828/36f26a0a-5cb0-4e88-a6cc-016c8a2adf04)

---------------------------------------------------------------------------------------
                                 *jai shree ram*
![3571156](https://github.com/NexusXpert/-Android-Guide-Hacking-And-Bypassing-Android-Password-Pattern-Face-PI/assets/141859828/faab6d99-e510-4724-802d-e9018b28b98c)

