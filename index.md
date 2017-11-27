# Welcome to Doung Doth's page#

##  Member of - AbantOS Linux!##



### Elive Enlightenment - User Reference Guide - Booting###

#### Here is some information regarding the process on how to boot an external flash drive USB and troubleshooting

## Booting via External hardrive: USB Flash Drive(Windows##

#### Power on your computer with the USB with Elive written to it plugged in. 


#### When the initial boot screen of your computer appears, hold down the Boot Menu key to load the boot menu. On many computers this is the F12 key, or one of the other F row keys. 

#### A list of common boot menu keys for various manufacturers can be found at
#### http://www.elivecd.org/ufaqs/how-to-tell-the-computer-to-boot-from-another-device/.


#### When the boot menu key appears, highlight the USB drive option and press Enter.


#### After Elive initiates, the first Elive menu asking the method of installation will appear. For running Elive from the USB, select Live sessions with Persistence. 


#### This method will allow you to run Elive direct from the USB without installing the system on your separate hardware, and Persistence will save your configurations of Elive from session to session.






## USB Booting Issues?##

#### Did you have an issue come up when your PC did not want to boot external flash drive USB even after going to Bios and selecting appropriate device? Did an Error message popped up saying something along the lines of "device is not found"? So what do you do?


#### After you install what ever that it is you want on your external flash drive USB you may find out that you are finding some trouble getting it to work. Now there are some ways to go about this.


#### Usually something needs to be configured in the ##BIOS## of your computer. That means tweaking a few settings to allow the external flash drive USB to be recognized and run. Once this is complete, your external hard drive ##USB## device should now be able to run and work.


#### One of the reasons why your are running into this problem is that, some modern computers boot immediately from the internal hard drive or SSD, paying no attention to any external bootable media first. 


#### Also some modern computers use  UEFI motherboards instead of the tradtional ##BIOS##.  Depending on the operating system, it may not support ##UEFI##  and supports BIOS. ##UEFI## motherboards support what is called ##legacy boot##, which allows the computer to boot external devices.


####  Press the power button, press the key ##F12## until the ##boot menu## comes up. If that does not work, you may need to enter the ##BIOS## and change it to allow the ##boot menu## to show. 


#### Using the ##F1## Key to enter the ##BIOS##, you wan to look for anything regarding ##UEFI/Legacy Boot##. 



#### Once you find that, change the settings to enable or on. If theres and option for both, set that as well. 


#### Then after you do that you have to set the ##priority##. Change or enable the settings to ##Legacy first##. To allow the  external flash drive to ##first## boot.




#### Here are a few links to help you out. One is a website that explains step by step on how to get it to work. The other, is a video on YouTube if you'd rather watch.


#### * If you are still having issues, try searching the make and model of your computer and possibly operating system and search USB booting


#### https://www.pcworld.com/article/3057176/hardware/the-hidden-challenges-of-booting-from-a-usb-flash-drive.html



#### https://www.youtube.com/watch?v=V95s-vxZL3k




# APPLE iOS MAC USER? #

#### If you are using an iOS - Apple Mac, and is having some issues geting your external flashdrive USB to work, try these things.



#### If your external flash drive USB contains a usable operating system or an OS X installer, you can select it at boot time using OS X’S built-in feature called Startup Manager, which can be invoked via a simple keystroke.



#### Power on your Mac by pressing the power button or restart it if it’s already on.


#### Press and hold the Option (⌥) key immediately when you heari the startup chime. Release the key after Startup Manager appears. Startup Manager will scan and list connected drives and volumes that can be booted from.


#### Select the volume you want to use by using the mouse or left and right arrow keys on the keyboard.


#### Double-click or press the Return key to boot your Mac from the selected volume.


#### You should now be able to boot from external an external flash drive USB


#### If you'd like to use system preference, with the computer on:


#### Open the System Preferences application in the Dock.


#### Now click the Startup Disk pane. You will be presented with various disk icons.


#### Select the system you would like to use to start your computer up.


#### Now click the Restart button to start up your Mac using the chosen volume.


#### *Note: If there are several USB storage devices connected to your Mac, Startup Manager will only list the ones containing bootable volumes.


#### http://www.idownloadblog.com/2015/09/14/how-to-start-up-mac-from-bootable-media/

