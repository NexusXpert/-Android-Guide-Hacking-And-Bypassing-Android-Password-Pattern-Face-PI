# -Android-Guide-Hacking-And-Bypassing-Android-Password-Pattern-Face-PI
[Android][Guide]Hacking And Bypassing Android Password/Pattern/Face/PI 

Description:

There is a bug in the Android password system that prevents users from unlocking their devices after entering the wrong password too many times. This bug can be bypassed by using the following methods:

Turning on Wi-Fi via ADB and then connecting to Google. Using a custom recovery to flash a zip file that disables the password. Using ADB to delete the password files from the system partition. Steps to Reproduce:

Enter the wrong password on your Android device 10 times. The device will show a message that says "Too many attempts. Try again later." Try to unlock the device with the correct password, but it will still be locked. Use one of the methods listed in the "Description" section to bypass the password. Expected Behavior:

METHOD I

(Cwm, Twrp, Xrec,Etc...) Installed:

INSTRUCTIONS:

Download this zip Pattern Password Disable (Download from attachments) on to your sdcard (using your PC, as you cant get into your phone, right )
Insert the sdcard into your phone
Reboot into recovery mode
Flash the zip
Reboot
Done!
Note: If You See The Gesture Pattern Grid Or Password After Restarting, Don't Worry. Just Try Any Random Pattern Or Password And It Should Unlock.

Method 2 Solution For Everyone Without Installed - ADB :

What You Need: =>A computer running a Linux distro or Windows+Cygwin =>USB cable to connect your phone to the PC => adb installed

How to install adb:

Open Terminal
Type: Code: sudo apt-get install android-tools-adb Hit [Enter]
Follow the instructions until everything is installed.
INSTRUCTIONS:

Connect you (turned on) Phone to the Computer via USB.

Open a terminal window.

Type: Code: adb devices adb shell cd data/system su rm*.key

Done...Now You Just Have To Reboot.

Note: If You See The Gesture Pattern Grid Or Password After Restarting, Don't Worry. Just Try Any Random Pattern Or Password And It Should Unlock.

The user should be able to unlock their device after entering the correct password, even if they have entered the wrong password too many times.

Actual Behavior:

The user is unable to unlock their device after entering the wrong password too many times.

Reproducibility:

The bug can be reproduced on all Android devices.

Severity:

This bug is a high severity bug because it prevents users from accessing their devices.

Workaround:

The following workarounds can be used to bypass the bug:

Turn on Wi-Fi via ADB and then connect to Google. Use a custom recovery to flash a zip file that disables the password. Use ADB to delete the password files from the system partition. Suggested Fix:

The bug can be fixed by changing the way that the Android password system handles incorrect passwords. The system should not prevent users from unlocking their devices after entering the wrong password too many times.

Additional Information:

I hope this bug report is helpful. Please let me know if you have any questions.
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
