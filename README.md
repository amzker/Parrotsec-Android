# UPDATE 


     Project is moved at gitlab.com/ParrotSec-Android 

Unstable Environment 500 

# Parrotsec-Android
ParrotSec Custom Build For Android
# Screenshot
![screenshot](https://github.com/amzker/Parrotsec-Android/blob/master/Screenshot_Quickstep_20190226-071844.png)


# Work Left? 
1) Android chroot maintain App && Terminal need to build left 
2) ParrotSec-Android For non-root Devices 
# Custom $PATH 
IF you want to set manual $PATH , i will upload spurce code ,You can set where you have space


# Requirements 

1) 10GB+ Space need to Free &% If need only CLI then 5GB+ Enough
2) Root Access
3) Busybox 
4) 512MB RAM (CLI) && 4GB minimum (GUI)

# Installing 
 
 **METHOD 1**
 
    This Method is for ,New Guy in ROM Flashing || Andy Development
    
1) Download/Build rootfs 
if you not wanted to Build
![Download](https://drive.google.com/file/d/15QvL0XUWS_ZhDXrDp3hlTLOaMs-ltn2s/view?usp=drivesdk)
2) follow thus commands 
 
`mkdir -p /data/local/ParrotSec`
 
Then Run 

`xz -dc live-image-armhf.tar.tar.xz | tar xjvf - -C /data/local/ParrotSec` 

Now Go To /data/local/ParrotSec 

and Rename `binary` to `parrot-armhf` 

Then Simply run
 
`./bootup `

**Method-2 Flashable-ZIP**

Step 1: Download Flashable Zip 
![Download]( https://drive.google.com/file/d/1M9zSkAebTRWfWrvO_9xjiS3MoDE8Y5Tx/view?usp=drivesdk)

Step 2: Install Busybox at 

`system/xbin` 

Step 3: Flash ZIP File 

`TWRP RECOMMENDED + Remove Sing Verification check Box`

Step 4: Reboot Android 

Reboot Your Android && Opeb Any Termibal App Which You LikE

Step 5: Unpacking.
Type 
`su`

`parrot` 

IT will ask 

`First tine boot? y/n` 

Say `y` && wait For 10 min 

Step 6: Use 

Next time/Secound boot  Just type `parrot` And say `n` 

 **Mthod3** 
  1) Download Flashable zip 
  2) Put in /sdcard 
  3) run `sh post-install`
 after install simply fire up by `parrot` cmd

# Errors 

1) When You type Parrot

Possible it will say you , su not found Even You Have root 

Solution: 
A) Boot into TWRP 

B) Mount system 

C) Go to Advance & open terminal & type

`rm -r /sbin/busybox /system/xbin/busybox `

D) Then Reboot Android & Re-Install Busybox 



# Armhf-Errors

May Possible To Get errOs after install 
II added scripts 

 `sysfix` 
 
 Also , if You need latest , Download From
 This Repo `sysfix.deb`

And I Think now ii need to stops build

II will upload updates as deb 

# nightly updates

Run following commmand for installer Amzy package manager

1) Download Amzy.deb From this repo/Parrot-Andy-deb 
paclages/CommonnPackages/Amzy`
2) sudo dpkg -i Amzy.deb 

# For updates 
check list first 
At 

`amzux.site11.com/download/repo`

Then run 
2) Amzy 
3) And put your package name 

# VIDEO
https://youtu.be/swsZ5CbTUlU

![VIDEO](https://youtu.be/swsZ5CbTUlU)
