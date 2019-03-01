# Parrotsec-Android
Unofficial ParrotSec Build For Android 
THIS BUILD NOT CREATED BY OFFICIAL PARROTSEC DEVS ,SO INSTALL IN BASED OF TRUST
Latest Version at nest.parrotsec.org/Amzker-Security/ParrotSec-Amzker
# Screenshot
![screenshot](https://github.com/amzker/Parrotsec-Android/blob/master/Screenshot_Quickstep_20190226-071844.png)


# Work Left? 

1) All work done but i am still waiting if parrotsec dev Fransisco build official chroot headless otherwose i created already 
2) Android chroot maintain App && Terminal need to build left 

# Custom $PATH 
IF you want to set manual $PATH , i will upload spurce code ,You can set where you have space


# Requirements 

1) 10GB+ Space need to Free &% If need only CLI then 5GB+ Enough
2) Root Access
3) Busybox 
4) 512MB RAM (CLI) && 4GB minimum (GUI)

# Installing 

1) Download/Build rootfs 
if you not wanted to Build
![Download](https://drive.google.com/file/d/1VRhKCgFMRWfshlOGckAAXVNnBF4UH78n/view?usp=drivesdk)

2) follow thus commands 
 
`mkdir -p /data/local/ParrotSec`
 
Then Run 

`xz -dc live-image-armhf.tar.tar.xz | tar xjvf - -C /data/local/ParrotSec` 

Now Go To /data/local/ParrotSec 

and Rename `binary` to `parrot-armhf` 

Then Simply run
 
`./bootup 
