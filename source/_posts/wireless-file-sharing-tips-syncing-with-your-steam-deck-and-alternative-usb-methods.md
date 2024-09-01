---
title: "Wireless File Sharing Tips: Syncing with Your Steam Deck & Alternative USB Methods"
date: 2024-08-26 11:50:44
updated: 2024-08-29 12:50:41
tags:
  - games
  - tv
  - movies
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d50bbc29912cb43ec93cd3720edb01228fbd6306ec3185b1604a33af30298ce1.jpg
---

## Wireless File Sharing Tips: Syncing with Your Steam Deck & Alternative USB Methods

### Quick Links

* [Why Transfer Data to Your Steam Deck?](https://smart-video-editing.techidaily.com/new-best-video-makers-with-music-for-android-and-iphone-for-2024/)
* [USB Transfer](https://snapchat-videos.techidaily.com/2024-approved-sound-painting-on-snapchat-shift-your-vocal-landscape-swiftly/)
* [Wireless Transfer Through SSH](https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-iphone-6s-by-drfone-ios/)
* [Wireless Transfer via Winpinator](https://screen-video-capture.techidaily.com/new-2024-approved-essential-9-mic-recorder-selections-for-online-use-in-23/)
* [Copy Files Directly to the MicroSD Card](https://youtube-videos.techidaily.com/2024-approved-cinema-craftsmanship-unleashed-youtube-green-screens-101/)
* [Google Drive or Cloud Storage](https://unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-y100-5g-by-drfone-android/)

 The Steam Deck is a robust handheld PC, but downloading external files via the built-in internet browsers can be slow and cumbersome. Luckily, there are several ways to transfer files to Valve's portable from another PC in minutes, and some don't even require any extra hardware.

##  Why Transfer Data to Your Steam Deck?

 A major selling point of the Steam Deck is its ability to run external software like non-Steam games and retro emulators. These emulators require games in the form of ROMs or ISOs,, which are [much easier to acquire](https://facebook-videos.techidaily.com/updated-video-revenue-generation-on-facebook-tactics-for-financial-growth-for-2024/) using a desktop PC.

 The Steam Deck can also run games with mods installed, which are similarly tedious to download natively, especially the larger files. While you'd still need to install them yourself, moving the mod files to the Deck externally can cut back on a lot of time (especially if you already have these files hanging around on another device).

##  USB Transfer

 Transferring files via USB is probably the simplest method since it is mostly a drag-and-drop process, but it requires some prep work. You'll need a flash drive that has a USB-C connection, such as [this one from Sandisk](https://www.amazon.com/dp/B01EZ0X23W?ref=ppx%5Fyo2ov%5Fdt%5Fb%5Fproduct%5Fdetails&th=1&tag=hotoge-20&ascsubtag=UUhtgUeUpU2004230&asc%5Frefurl=https%3A%2F%2Fwww.howtogeek.com%2Ftransfer-files-to-steam-deck-wirelessly-via-usb-and-more%2F&asc%5Fcampaign=Evergreen), which has both USB-A and USB-C connectors (you can [also use USB-C adapters](https://printer-issues.techidaily.com/breathe-new-life-into-non-printing-brother-printer-in-windows-1011/), just make sure they support the full speed of your drive).

 You will also need to [make sure the drive is formatted properly](https://extra-approaches.techidaily.com/seamless-multi-screen-browsing-in-chrome-using-pip-for-2024/) to work across both the Steam Deck and your desktop. If you use Windows, you should format the drive to NTFS by connecting it to your PC and right-clicking it in File Explorer under This PC > Drive Name > Format.

![The "Format" option on a storage drive in Windows 10.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot-2024-07-17-130655-1.png) 

 If it is not already set to NTFS under "File System" by default, then simply click on the drop-down menu and select it, then click "Start." The drive should now be readable across both devices.

![The "Format" menu in Windows 10](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot-2024-07-17-152336.png) 

 From there, it's just a matter of dropping your files onto the drive and connecting it to the Steam Deck. You can use the trackpad or touch screen to navigate the Deck in desktop mode and move the files to wherever you need them within its internal drive or a MicroSD card.

##  Wireless Transfer Through SSH

 On a local Wi-Fi connection? You can also access your Steam Deck's file system directly from your PC wirlessly [using a secure shell or SSH](https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y78t-drfone-by-drfone-fix-android-problems-fix-android-problems/).

 First, you'll need to access your Steam Deck's console terminal in Desktop Mode. It is highly recommended that you dock your Steam Deck to a PC or use an external keyboard, but it is possible to do it via the virtual keyboard accessed by pressing the "Steam" button and "X" simultaneously.

 Hold down the power button and select "Switch to Desktop." Once it finishes rebooting, select the logo in the bottom left corner and navigate to System > Konsole and open it. Type "passwd" and press "Enter." Enter a password and confirm it in the following text entry boxes.

![The "Konsole" app on Steam Deck](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240717_153532.png) 

 You won't see your text being entered on the "Password" screen for security reasons, so be careful when you are typing it.

 Enable SSH on your Steam Deck by typing the following and hitting enter:

sudo systemctl enable sshd 

 Confirm by entering your password. Then, type the following and hit enter:

sudo systemctl start sshd

 While you're here, grab your Steam Deck's IP address by entering:

IP a

 Then hit enter "Enter." make a note of the IP address that appears following the term "inet."

![The IP address for the Steam Deck shown in the system's Konsole app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240717_154137-1.png) 

 You can also do "sudo systemctl status sshd" to verify if it is enabled or type "enable" instead of "start" to make the Deck start up the SSH connection every time it boots up.

 Now, you can move files between the two systems using your PC's command prompt window and your Steam Deck's IP address. On your PC launch command prompt by clicking "Start" and then searching for "cmd" and clicking "Command Prompt" when it appears. Now use the command:

deck@ipaddress

 Then enter the password you chose earlier. Finally type "mv filename" or "cp filename" to move or copy files back and forth between the systems. "Filename" should correspond with the location and name of the file you want to copy.

 You can also mount your Steam Deck's internal SSD as a readable drive from within Windows, using SSHFS, which is a more robust version of the same concept, which incorporates many of the steps listed above.

##  Wireless Transfer via Winpinator

 Warpinator is a remote file transfer tool built for Linux. Fortunately for Windows users, it was ported to Windows 10 under the name Winpinator. Download and install the application [from the official website](https://winpinator.swisz.cz/download.html) and ensure that your PC and Steam Deck are connected to the same network.

 You can check your Steam Deck's IP using the above method or by navigating to Settings > Internet and selecting your Wi-Fi network. Winpinator should automatically display your PC's IP address for comparison.

![The Internet Settings screen on Steam Deck](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/download.jfif) 

 You will then need to download the same app on your Steam Deck by holding down the "Power" button and selecting "Switch to Desktop." Once it reboots, navigate to the "Discover" app in the bottom right corner and search for "Warpinator" to install it to your Deck so the connection can work both ways.

 Provided both are on the same LAN network, you should see your Deck appear as an external computer, where you can click on it to access the file systems and move things around at will.

##  Copy Files Directly to the MicroSD Card

 Since the Steam Deck is compatible with [extended storage via a MicroSD card](https://media-tips.techidaily.com/quick-and-simple-turn-any-video-into-samsung-galaxy-friendly-format-with-a-mac/), it is also possible to add files to it directly by inserting it into a PC. If you have a Linux PC, you can get an adapter for a MicroSD card to insert it and just drag files onto the card as you would a flash drive.

 If you have a laptop using Linux with a MicroSD card slot, it's just a matter of opening your file directory and copy and pasting or dragging and dropping your files into the root of the SD card. Then, you should be able to access them and move them as needed from your Steam Deck by just putting it back in.

 This method will not work on any device using Windows, however, since Linux uses a different file system for which the MicroSD card needs to be formatted for the Steam Deck to read it. Technically, you can move files onto it with Windows, but you'd need to reformat it on your Steam Deck anyway, which would wipe all the files on the card.

##  Google Drive or Cloud Storage

 If all else fails, you can always do things the long way and upload your files to a cloud for download via the internet on your Steam Deck. You can upload your files to Google Drive from any device by selecting "New" in the top right of Drive's home page and selecting "File Upload."

![The "New" option in Google Drive.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot-2024-07-17-155328.png) 

 This is not ideal, since the Deck tends to struggle with download speeds in Desktop Mode, so you'd have to leave it on for quite a while. Unless you are transferring files that are not otherwise available online, it may make more sense just to download them from the source at this point.

---

 The Steam Deck's double life as a gaming system and a miniature PC makes it useful for a lot of different things, and with the ability to transfer and install files from external sources, there are more possibilities than ever.

 Many of these methods will work on other handhelds as well, [such as the ROG Ally X](https://screen-activity-recording.techidaily.com/updated-in-2024-unifying-streams-simultaneous-capture-of-camplusscreen/) or any of Valve's other competitors.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
