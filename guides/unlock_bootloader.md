# Unlocking Bootloader

## Check if phone's already on unlocked bootloader or not
> **Make sure you already have Mi Account logged in on your device, already link the account to your phone number, and remember the account. This will be useful later.**
> 
> **This will delete your user data and internal storage. So, make sure you already backed up your data before doing this.**



1. Go to your phone's settings. Find "About phone" by scrolling down and clicking on it.
2. Look for the "MIUI version" option.
3. Tap on it seven times in fast succession. This will enable developer options on your phone.
4. Head to the main settings menu and navigate to the "Additional settings" section.
5. Tap on "Developer options".
6. Scroll down to "Mi Unlock Status" or "OEM Unlocking" and check the status. If it says "Locked" your phone’s bootloader is locked. If it says "Unlocked", your phone’s bootloader is already unlocked.
7. Tap on "Add account and device" to link the device. This might need mobile data and phone number linked to your phone.  

## Official Method

### Pre-requisite

> Download the [Mi Unlock Tool here](https://en.miui.com/unlock/download_en.html)!

### Step-steps
1. Before proceeding, ensure that Developer Options and USB Debugging are enabled on your phone.
2. Download and extract the Mi Unlock Tool to somewhere you know and remember.
3. Run "driver_install.exe" or "driver_install_64.exe" for 64-bit PCs to install the prerequisite drivers.
4. Plug your phone to your PC using a USB cable. Then launch the Mi Unlock Tool and sign in with your Mi account.
   
   ![image](https://github.com/naokoshoto/camellia-stuffs/assets/25972975/dbdc7f0f-0996-4cff-bad9-fc7531156f41)
6. Follow the instruction to switch off the phone and then hold Power and Lower Volume button simultaneously to enter Fastboot mode.
   
   ![image](https://github.com/naokoshoto/camellia-stuffs/assets/25972975/eae8febc-2dad-4db0-87f3-8191904995c8)
8. A new message will appear on the screen, "Phone connected". After that, you can safely click the "Unlock" button to start unlocking.

   ![image](https://github.com/naokoshoto/camellia-stuffs/assets/25972975/53479ec4-f568-4523-a71e-863c7ae4a02a)
10. On your first attempt, the Mi unlock tool will flash the message, "Couldn’t unlock, Please unlock 168 hours later". This is the waiting period where sometimes, users end up waiting for months. Come back after the time period shown to unlock.
    ![image](https://github.com/naokoshoto/camellia-stuffs/assets/25972975/a1999bac-6e76-4247-a69c-ca69db06648c)
12. If the waiting period is over, repeat the process from the 1st step then press "Reboot Phone" on the PC.

    ![image](https://github.com/naokoshoto/camellia-stuffs/assets/25972975/735c872c-46e1-4713-bdad-604c2ea21010)
14. Again, head to the Mi Unlock Status in the developer settings and see if the tab is flashing "Locked" or "Unlocked".

    <img src="https://github.com/naokoshoto/camellia-stuffs/assets/25972975/b541499b-a24f-4080-b4d8-a5a045201b6d" height="512"/>


> Source cited from [FOSSBytes](https://fossbytes.com/how-to-unlock-bootloader-on-xiaomi-devices-using-mi-unlock-tool/)


## Force Unlock Method

> I wouldn't recommend to do this, so do it with your own risk.

Please refer to this video below for tutorial.

[![Watch the video](https://img.youtube.com/vi/PU-aOJgkSEE/hqdefault.jpg)](https://youtu.be/PU-aOJgkSEE)


## Termux Method

> This method is experimental and might removed someday. I wouldn't recommend either.

[Please refer to this tutorial linked by popMODS.](https://t.me/popMODS/3621)


