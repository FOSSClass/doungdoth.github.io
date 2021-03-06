# _Welcome to Doung Doth's page_

## Member of - AbantOS Linux!

### Elive Enlightenment - User Reference Guide - Booting

#### Here is some information regarding the process on how to boot an external flash drive _USB_ and troubleshooting

## Booting via External hardrive: _USB_ Flash Drive(Windows)

#### _Power on your computer with the _USB_ with Elive written to it plugged in._ 


#### _When the initial boot screen of your computer appears, hold down the Boot Menu key to load the boot menu. On many computers this is the  _F12 key_, or one of the other F row keys._ 

#### A list of common boot menu keys for various manufacturers can be found at
#### http://www.elivecd.org/ufaqs/how-to-tell-the-computer-to-boot-from-another-device/.


#### _When the boot menu appears, highlight the _USB_ drive option and press Enter._


#### _After Elive initiates, the first Elive menu asking the method of installation will appear. For running Elive from the USB, select Live sessions with Persistence._


#### This method will allow you to run Elive direct from the USB without installing the system on your separate hardware, and Persistence will save your configurations of Elive from session to session.






## _USB_ Booting Issues?

#### Did you have an issue come up when your computer did not want to boot external flash drive _USB_ even after going to _BIOS_ and selecting appropriate device? Did an Error message popped up saying something along the lines of "device is not found"? So what do you do?


#### After you install what ever that it is you want on your external flash drive _USB_ you may find out that you are finding some trouble getting it to work. Now there are some ways to go about this.


#### Usually something needs to be configured in the _BIOS_ of your computer. That means tweaking a few settings to allow the external flash drive _USB_ to be recognized and run. Once this is complete, your external hard drive _USB_ device should now be able to run and work.


#### One of the reasons why your are running into this problem is that, some modern computers boot immediately from the internal hard drive or SSD, paying no attention to any external bootable media first. 


#### Also some modern computers use  _UEFI_ motherboards instead of the tradtional _BIOS_.  Depending on the operating system, it may not support _UEFI_  and supports _BIOS_. _UEFI_ motherboards support what is called _legacy boot_, which allows the computer to boot external devices.


####  _Press the power button, press the key _F12_ until the boot menu comes up. If that does not work, you may need to enter the _BIOS_ and change it to allow the boot menu to show._ 


#### _Using the _F1 Key_ to enter the _BIOS_, you wan to look for anything regarding UEFI/Legacy Boot._ 



#### Once you find that, change the settings to _enable or on_. If theres and option for _both_, set that as well. 


#### _Then after you do that you have to set the priority. Change or enable the settings to Legacy first. To allow the  external flash drive to first boot._




#### _Here are a few links to help you out. One is a website that explains step by step on how to get it to work. The other, is a video on YouTube if you'd rather watch._


#### * If you are still having issues, try searching the make and model of your computer and possibly operating system and search USB booting


#### https://www.pcworld.com/article/3057176/hardware/the-hidden-challenges-of-booting-from-a-usb-flash-drive.html



#### https://www.youtube.com/watch?v=V95s-vxZL3k




# APPLE iOS MAC USER? 

#### If you are using an iOS - Apple Mac, and is having some issues geting your external flashdrive USB to work, try these things.



#### If your external flash drive USB contains a usable operating system or an OS X installer, you can select it at boot time using OS X’S built-in feature called _Startup Manager_, which can be invoked via a simple keystroke.



#### _Power on your Mac by pressing the power button or restart it if it’s already on._


#### _Press and hold the Option (⌥) key immediately when you heari the startup chime. Release the key after Startup Manager appears. Startup Manager will scan and list connected drives and volumes that can be booted from._


#### _Select the volume you want to use by using the mouse or left and right arrow keys on the keyboard._


#### _Double-click or press the Return key to boot your Mac from the selected volume._


#### You should now be able to boot from external an external flash drive USB


#### If you'd like to use _system preference_, with the computer on:


#### _Open the System Preferences application in the Dock._


#### _Now click the Startup Disk pane. You will be presented with various disk icons._


#### _Select the system you would like to use to start your computer up._


#### _Now click the Restart button to start up your Mac using the chosen volume._


#### *Note: If there are several _USB_ storage devices connected to your Mac, _Startup Manager_ will only list the ones containing bootable volumes.


#### http://www.idownloadblog.com/2015/09/14/how-to-start-up-mac-from-bootable-media/

