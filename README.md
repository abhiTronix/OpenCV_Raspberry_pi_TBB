Latest pre-compiled binary of Pre-released & Stable OpenCV (4.0.0) along with TBB (2018-Update 6) for the Raspberry Pi (*Tested on Rpi version 2/3 Model B/B+ with Stretch*)

### Head over to https://github.com/abhiTronix/TBB_Raspberry_pi for TBB installation.

# OpenCV [TBB + VFVP3 + NEON] (Update: December, 2018): **Unleashed The Power of Multi-Threading in OpenCV 🔥🔥**

![Github](https://img.shields.io/badge/OpenCV-Stable%20%20%7C%20Pre%20(4.0.0)-orange.svg?longCache=true&style=for-the-badge)   
![Github](https://img.shields.io/badge/TBB-2018%20Update%206-yellow.svg?longCache=true&style=for-the-badge)  
![Github](https://img.shields.io/badge/Platform-Raspberry%20Pi%202/3-blue.svg?longCache=true&style=for-the-badge)</t> [![GitHub](https://img.shields.io/badge/Raspberry%20Pi%20Zero/1-Not%20Tested-red.svg)](https://github.com/abhiTronix/raspberry-pi-cross-compilers) 


Inspiration from amazing tutorial from Adrian (https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/)

Inside this tutorial, there are three possible ways of optimizing OpenCV:

1. NEON 
2. VFPV3 
3. Threading Building Blocks©️ (TBB)

TBB is already successfully installed on my Rpi and made available precompiled [**here**](https://github.com/abhiTronix/TBB_Raspberry_pi)
. Hence i created this Latest pre-compiled set of binary: Pre-released & Stable OpenCV (4.0.0) compiled along with Latest (2018 Update 6) of TBB for the Raspberry Pi. It is made available in a ".deb" package and will save you countless hours not having to compile it yourself plus avoid worst looking compiling errors. This may or may not stay updated as I have to manually compile this version. I will try to make available most major versions. This is compiled for Raspberry Pi 3/2 Model B/B+ running Latest raspbian Stretch. This is enabled with TBB Support which helps multithreading in many OpenCV algorithms and significant [**3x~5x**](https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/) increase in performance along with '**NEON**' and '**VFVP3**' support and other major compilation flags without _any whatsoever change in your program_.
For Files Look Down below.


## TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# Proof:
![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/Latest.gif)
**1. OpenCV (version: 4.0.0 pre) successfully compiled with TBB (version: 2018 - Update 4)] on Python 2.7.13/3.6.0 on my Raspberry Pi 3B**.


![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/Files.png)
**2. OpenCV(version: 4.0.0 pre/dev [TBB + VFVP3 + NEON] Supported) Files on my machine**.


![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/Screenshot.png)
**3. OpenCV (version: 4.0.0 pre) along with 'NEON' and 'VFVP3' Support enabled(Demo-file Output)**.

# Installation Instructions :
### (Tested on Raspberry pi 3 with Raspbian Stretch [Latest])
Simple (but straight forward):
  ```
sudo dpkg -i <path to *.deb file[e.g OpenCV_release_fp_tbb_armhf.deb]>
sudo ldconfig
  ```
# Files📂:
**Tryout Demo OpenCV(No TBB Supported) .deb file is available here:** [opencv_4.0.0-pre-demo_armhf.deb](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/opencv_4.0.0-pre-demo_armhf.deb) (Refer Issue: [**#1**](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/issues/1#issue-391020295))   

***But if you want the latest & max optimized OpenCV([TBB + VFVP3 + NEON] Fully Supported) precompiled .deb files with installation support associated, it is only provided through email (*abhi.una12@gmail.com*)**. Also consider supporting my countless hours of hardwork and helping me out by making small *Donation for my ongoing Independent A.I. Research in return. Thankyou***

# Huge thanks to:
https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/ & https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/ for guiding me through.  
https://github.com/opencv for Latest OpenCV binaries.  
https://github.com/01org/tbb for TBB binaries.   

Love from India ❤️
