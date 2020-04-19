---
layout: post
title:  "Upgrade to Android Pie on Any Xiaomi Device with the Pixel Experience ROM"
author: swapnil
categories: [ Android, Tutorial ]
image: assets/images/AndroidPie.jpg 
tags: [featured]
---

If you enjoy a hands-on experience and you own a Redmi device, this article will convince you to upgrade to Android Pie with a Pixel Experience ROM. Even if you don’t own a Redmi device, reading this article could help you to upgrade your own device.

>Xiaomi is the market leader in mid-range Android devices. Redmi Note 4 was one of the most shipped Android devices in 2017. It became more popular because of its powerful hardware specifications that make the phone super smooth. The price offered by Xiaomi at that time was much lower than phones from other companies with similar configurations. 

Note 4 runs on MIUI 10, which is based on Android Nougat 7.1. The latest version of Android to hit the market is Android Pie, and Android Q is likely to be launched in the coming months. All users of Note 4 want the upgrade to the latest OS but sadly, the company has no such plans and is not pushing security patch updates either. 

In a recent announcement, the company declared that Note 4 and prior released devices will not get a
MIUI 11 update. But don’t fret, because irrespective of this bad news, you can upgrade to the latest Android Pie using custom Android ROMs.

If you are one of those who want to enjoy the latest features and security updates of Android Pie without blowing your budget by buying a new Android device, then read this article carefully. Many of us with Note 4 or other MI devices want to upgrade to the next generation Android Pie on our devices. This article is written for Redmi Note 4, but it is applicable for all Xiaomi devices that run on MIUI (Redmi 3, Redmi Note 3, Redmi Note 4, Redmi 4, Redmi Note 4A, Redmi Note 5, Redmi Note 5 Pro, Redmi 5, Redmi 5 Pro, Redmi 5A, and others in this series).

But before installing the latest Android ROM, let us go over some basic concepts that we really need to be clear about, regarding Android and custom ROMs.

## Things you should know before actual installation of custom ROM on any Android device
### What is a custom ROM?
 The acronym ROM stands for Read Only Memory. But this is a bit confusing with respect to custom
Android ROM, which is firmware or software that has been permanently programmed into Read Only Memory, and directly interacts with hardware.

Android is an open source project, so any developer can edit, modify and compile the code for a variety of devices. Custom ROMs are developed entirely by the community, which comprises people who are passionate about modding. 

Android custom ROMs are available for smartphones, tablets, smart TVs, media players, smart watches, etc. When you buy a new Android device, it comes with company installed firmware or an
operating system which is controlled by the manufacturer and has limited functionality. Here are some benefits of switching over to a custom ROM.

**Performance:** Custom ROMs can give tremendous performance improvements. The device manufacturer locks the clock speed at an optimal level to balance heat and battery life. But custom ROMs do not have restrictions on clock speed.
 
**Battery life:** Company installed firmware has lots of bloatware or OEM installed apps that are always running in the background, consuming processor resources, which drains the battery.

**Updates:** It is very frustrating to wait for manufacturers to release updates. Custom ROMs are always
updated, depending upon the active community behind the ROM. 

Here is a list of some of the Android custom ROMs available for Note 4 and corresponding Xiaomi devices:
 1. Pixel Experience ROM
 2. Resurrection Remix ROM
 3. Lineage OS ROM
 4. Dot OS ROM
 5. cDroid ROM
  
### Why the preference for Pixel Experience?
After a lot of research, I came to the conclusion that Pixel Experience is best suited to general user
requirements, so I decided to go with it. As the name suggests, it is supposed to give you a Google Pixel like experience on your device. This ROM comes with preloaded Google apps so there’s no need to flash externally. Over the air (OTA) updates are provided by the community regularly. I have used this ROM for the past six months, and am getting monthly security patch updates with other bug
fixes and enhancements. 

Pixel Experience is a lightweight and less customizable ROM, so it consumes less battery. The battery performance is outstanding and beyond expectations.

## Are there security concerns when a custom ROM is installed?
It is not true that the installation of a custom ROM compromises the security of a phone or device. Behind every custom ROM there is a large community and thousands of users who test it.

For custom ROM installation, you don’t need to root your device — it is 100 per cent safe and secure. If we keep this discussion specific to the Pixel Experience ROM, then it is a pure vanilla Android ROM developed for Nexus and Pixel devices, and ported by developers and maintainers to specific Android devices.

Before installing a custom ROM, you need to unlock the bootloader. During the bootloader unlock process, you will see a warning from the vendor that states your phone will be less secure after unlocking the bootloader. The reason for this is that an unlocked phone can be used to install a fresh
ROM without any permission from device manufacturers or the owner of the device. So, stolen or lost devices can be reused by flashing a ROM. Anyway, there are a number of methods that can be used to unlock the bootloader unofficially and install the ROM without permission from the manufacturer.

Custom ROMs are more secure than stock ROMs because of the latest updates provided by the community. Device manufacturers are profit making companies. They want their customers to upgrade their phones after two years; so they stop providing support and stop pushing software
updates! Custom ROMs, on the other hand, are driven by non-profit communities. They run on community support and donations.

### What does it mean to root an Android device, and is this really required before flashing a custom ROM?
On a Windows machine, there is an administrator account which has all the privileges. Similarly, in Linux too, there is the concept of a root account. Android uses the Linux kernel; so all the OS internals are the same as in Linux.

Your Android phone uses Linux permissions and file system ownership. You are a user when you sign in and you can do only certain things based on your user permissions. In all Android devices,
the root user is hidden by the vendor to avoid misuse.

Rooting an Android phone is to jail-break the phone to allow the user to dive deep into the device. I personally recommend that you do not root your device, because doing so is really not required to flash a custom ROM to the device.

Here are a few reasons why you should not root your device:
 1. Rooting can give your apps complete control of the system, and there is a chance of misuse of power.
 2. Google officially does not support rooted devices.
 3. Banking applications, BHIM, UPI, Google Pay, PhonePe and Paytm will not work on rooted devices.
 4. There is a myth that rooting of a phone is required to flash a custom ROM, but that is not true. You only need to unlock the bootloader to do so.
    
### What is a bootloader and why should you unlock it before flashing a custom ROM? 
A bootloader is the proprietary image responsible for bringing up the kernel on a device. It is nothing but a guard for the device, and is responsible for initialising trust between root and user. The bootloader may directly flash the OS to the partition or we can use custom recovery to do the same thing.
![Bootloader](https://1.bp.blogspot.com/-0xYaJFjW9vg/XWwAWOFku6I/AAAAAAAAbGM/rCv0jJcUgT0HjwfHAd4tTFAEgsDksgHoQCLcBGAs/s1600/bootloader.jpg)

 In this article we will use Team Win custom recovery to flash the operating system in a device. 

In Microsoft Windows terminology, there is the concept of a BIOS which is the same as a bootloader. Let’s look at an example. When we install Linux alongside Windows on a laptop or PC, there is bootloader called GRUB which allows the user to boot either Windows or Linux. A bootloader points to the OS partition from the file system. At the press of the power button to start the phone, the bootloader initiates the process to boot the operating system installed in the file system.

Most bootloaders are locked by vendors to make sure the user sticks to the operating system specifically designed by the vendor for that particular device. With a locked bootloader, it is impossible to flash a custom ROM and a wrong attempt may brick the device. Again, this is one of the security features provided by the vendor.

The bootloader can be unlocked in two ways — one is the official method
provided by the vendor, and the other is the unofficial method which may lead to a bricked device.

## Installing Pixel Experience on a Xiaomi device
The previous section covered concepts that we needed to be clear about before flashing a custom ROM. Now let’s go through a step by step procedure to install a custom ROM on any Android
device. We’re working specifically on a Redmi device and this is based on my own experience.
Here are some points to remember before unlocking the bootloader:
- Take the phone’s backup on a PC/ laptop (you are unlikely to lose any data, and this step is just a precaution).
- Unlocking the bootloader voids the warranty.
- Make sure that the zip file of the Android ROM is downloaded to the device's internal memory or SD card.
- Make sure that the bootloader of the device is unlocked after the unlock process completes, because a wrong attempt may brick the device.

### Steps to follow on a laptop/PC
  1. On your laptop/PC, navigate to https://en.miui.com/unlock/ and click on the Unlock Now button.
  2. Log in to the MI account with the credentials you used to log into your device.
  3. Remember the credentials, since this is the most important step.
  4. As per the new MI unlock bootloader method, you don’t need permission from MI. To download the MIUI Unlock application, simply click on the button. The size is around 55MB.
  5. Go to where we downloaded the MIUI Unlock application in Step 4, and double click on miflash_unlock.exe.
  6. Log in using the MI account, which is used in Step 2.
  7. Make sure that the device is properly connected to the PC using a USB cable (the status will be shown in the application).
 
### Steps to follow on a mobile phone 
 1. Go to Settings->About phone.
 2. Tap five times on the MIUI version; it will enable the Developer option on your device.
 3. Go to Settings->Additional Settings -> Developer options and tap on OEM unlocking. Do not enable this but click on the text to go inside.
 4. Enter your password/PIN (whichever is set to the device for confirmation) and enable the option.
 5. Go to Settings->Additional Settings -> Developer options, and then go to MIUI status and tap on Add account. This step will add the MI account to unlock the bootloader. Sometimes the account does not get added, in which case, restart the phone.
 6. Enable USB debugging from Settings->Additional Settings -> Developer options.
 7. Switch off the phone and press the Power button and the ‘volume down’ key simultaneously.
 8. Connect the USB cable to the device and laptop/PC.
 
### After completing these steps on the mobile, repeat the folliwing steps on your PC/laptop
1. Click on the Unlock button.
2. A dialogue box with the following message will appear: “Unlocking the phone will erase all phone data. Do you still want to continue to unlock the phone?” Click on Unlock anyway.
3. You will see the message shown in Figure 2, if it did not unlock. There is a time specified after which you may try again. The time varies betwee n 24 hours to 360 hours. In my case it was 360 hours, which is nothing but 15 days!
5. After the specified period, carry out the same steps, and the bootloader will get unlocked and you will see the result shown in Figure
![Figure 3](https://1.bp.blogspot.com/-5Dvl43zYSJY/XWwGxpwBc9I/AAAAAAAAbGc/IPzYqq46lMwiAW3LA2xg4gvEqkrndhv0ACEwYBhgL/s1600/could%2Bnot%2Bunlock.jpg)

## Installing Team Win Recovery Project (TWRP)
Team Win Recovery Project (TWRP) is an open source custom recovery image for Android based devices. It provides a touchscreen-enabled interface that allows users to install third-party firmware and back up the current system. It is installed on an Android device when flashing, installing or rooting Android devices.

 1. Download the Pixel Experience ROM for your device from the [official website](https://download.pixelexperience.org) In my case, the device is Redmi Note 4 (Mido); download and save the zip file in the phone memory.
 2. In a Web browser, navigate to the [Android SDK tools website](https://developer.android.com/studio/releases/platform-tools.html) Under the download section you will find three links for your platform Windows, Linux and Mac. Depending on your operating system, download the SDK, which is just around 7MB.
 3. In a Web browser, navigate to [Link](https://twrp.m[Link]e/Devices/) and search for your device. Here, remember that my device is Redmi Note 4 and the name is Xiaomi Redmi Note 4(x) (mido). Go to your device by simply clicking on the link. There is a section called Download links that you can click on. Choose the latest TWRP image and download it.
 4. Head to the Downloads directory and extract the platform tool’s zip file downloaded in Step 1.
 5. Move the TWRP image file downloaded in Step 2 inside the Platform Tools folder.
 6. Connect your phone to a computer using a USB cable, and make sure that USB debugging is ON.
 7. Open a command window and CD to the Platform Tools directory.
 Run the following commands on the command prompt:
  - Run the command `adb devices` and make sure that your device is listed.
  - Run the command `adb bootloader`. It will take you to the bootloader.
  - Now type `fastboot devices`. Your device will get listed here.
  - Run the command `fastboot flash recovery twrp-image-file.img`.
  - Run the command `fastboot boot twrp-image-file.img`.
  - Wait for a few moments and you will see the Team Win Recovery Project start on your device.
![Figure 4](https://1.bp.blogspot.com/-BENEfNL25rU/XWwJclhrn4I/AAAAAAAAbGk/GhD_on9svww9TiOEJwlfImpz8-UUMIcPQCLcBGAs/s1600/command%2Badb.png)

## Steps to install custom ROMon Xiaomi device
![Figure 5](https://1.bp.blogspot.com/-L4uRcGlAeZI/XWwLsuYQBJI/AAAAAAAAbGw/5NCCkuiMitQpIjyyprwDBlwwBN4rLcz0wCLcBGAs/s1600/TWRP_2.7.0.0.png)

Now you are already booted into TWRP. It is recommended that you take a backup. Press Backup, select the following options, and swipe right to backup.
[x] ƒƒSystem
[x] Data
[x] Vendor
[x] Recovery
[x] Boot
[x] System image

1. Next, wipe the existing stock ROM
from your device. To do so, go to
Wipe->Advanced wipe options,
select the following options and
wipe them:
[x] ƒƒDalvik
[x] System
[x] Data
[x] Cache
[x] Vendor

2. Come back to the Install option and browse for the pixel experience zip file, select it and swipe to flash. It will take some time. Once it is completed, wipe the cache.
3. Press the Reboot to start button. Pixel Experience will get started on your device. 

>Congratulations, you now have successfully upgraded to Android Pie.


== This article is written by Swapnil Vivek Kulkarni and published in technical magazine Open Source For you August 2019 issue. Also available at [OpenSourceForYou.com](https://opensourceforu.com/2019/09/upgrade-to-android-pie-on-any-xiaomi-device-with-the-pixel-experience-rom/) and [PDF version](http://bit.ly/andrpie) ==

![Magzine](/assets/images/android_pie.jpg)
