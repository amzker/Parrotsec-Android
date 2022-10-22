# UPDATE 

This Repo is old and not maintained, 
You guys just install script & read
Methods from builder

# PROJECT IS CLOSED

  

Unstable Environment 500 

# Parrotsec-Android
ParrotSec Custom Build For Android

# Support Group

http://t.me/@ParrotAndy
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

`xz -dc live-image-armhf.tar.tar.xz | tar xvf - -C /data/local/ParrotSec` 

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


Then run 
2) Amzy 
3) And put your package name 



# Acknowledgement 
   ```
1. This Is Unofficial Build ,So Mkae sure you rremember You will not get support from official ParrotDev  
2. There is no chance for breack Your Andy. Because II care to much on it && Everything is Tested & fully setuped
3. Do not use Any other Package manager (except Amzy,apt)
4. nightly updates is stop for few times 
In nightly updates ,ii not touch your android Any module or any part 
 Everything is happens in cchrooted binary
 in Those updates 
Mainly 
    A. Improved Amzy 
    B. New My Custom tools 
    C. Customm profiles 
    D. Test builds of P-term
You get. 
5. I Am Responsible if you follow my steps & device get breack 
(Follow same as video)
6. Console AI, Updates starts after 29-6 
in which investigator,Mass Scann,Amzkill gets improved 

  ```
-Amzker t.me@amzker 

```

.
|-- LATEST-VERSION
|-- LICENSE
|-- Non-root
|   |-- README.md
|   `-- contributions.md
|-- Packages
|   |-- Amzkill.Amzx
|   |-- Amzy.Amzx
|   |-- console.Amzx
|   `-- null
|-- README.md
|-- Screenshot_Quickstep_20190226-071844.png
|-- _config.yml
|-- boot-up
`-- halfwork
    |-- My\ mistakes.null
    |-- _20190227_115537.JPG
    |-- null
    `-- to-do.txt

3 directories, 16 files
```
