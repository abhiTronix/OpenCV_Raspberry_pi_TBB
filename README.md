Latest pre-compiled binary of Pre-released OpenCV (4.0.0) & Stable OpenCV (3.4.2) along with TBB (2018-Update 4) for the Raspberry Pi (*Tested on Rpi version 2/3 Model B/B+ with Stretch*)

## Head over to https://github.com/abhiTronix/TBB_Raspberry_pi for installing TBB first.

# OpenCV [TBB + VFVP3 + NEON] (Update - September,2018): **Unleashed The Power of Multi-Threading in OpenCV 🔥🔥**

![Github](https://img.shields.io/badge/OpenCV-Stable%20(3.4.2)%20%7C%20Alpha%20(4.0.0)-orange.svg?longCache=true&style=for-the-badge)<t>
![Github](https://img.shields.io/badge/TBB-2018%20Update%204-yellow.svg?longCache=true&style=for-the-badge)<br>
![Github](https://img.shields.io/badge/Platform-Raspberry%20Pi%202/3-blue.svg?longCache=true&style=for-the-badge)<br>
![Github](https://img.shields.io/badge/Build-Passing-green.svg?longCache=true&style=for-the-badge)<br>

Inspiration from amazing tutorial from Adrian (https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/)

Inside the tutorial, there is three possible ways of optimizing OpenCV:

1. NEON 
2. VFPV3 
3. Threading Building Blocks©️ (TBB)

TBB is already successfully installed on my Rpi and made available precompiled at  https://github.com/abhiTronix/TBB_Raspberry_pi
Hence i created this Latest pre-compiled binary of Pre-released OpenCV (4.0.0) & Stable OpenCV (3.4.2) compiled along with Latest (2018 Update 4) of TBB for the Raspberry Pi. It is made available in a ".deb" package and will save you countless hours not having to compile it yourself plus avoid worst looking compiling errors. This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions. This is compiled for Raspberry Pi 3/2 Model B/B+ running Latest raspbian Stretch. This is enabled with TBB Support which helps multithreading in many OpenCV algorithms and significant **3x~5x** (https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/) increase in performance along with 'NEON' and 'VFVP3' support and other major compilation flags.
For Files Look Down below.


# TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# Proof:

![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/Latest.gif)
1. **OpenCV (version: 4.0.0 pre) successfully compiled with TBB (version: 2018 - Update 4)] on Python 2.7.13/3.6.3 on my Raspberry Pi 3B**.

<br>
<br>
<br>

![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/Screenshot.png)
2. **OpenCV (version: 4.0.0 pre) along with 'NEON' and 'VFVP3' Support enabled**.

# Installation Instructions :
## (Tested on Raspberry pi 3 with Raspbian Stretch [Latest])
Simple (but straight forward):
  ```
sudo dpkg -i <path to *deb file[e.g OpenCV_release_fp_tbb_armhf.deb]>
sudo ldconfig

  ```
# Files📂:
Latest .deb files and full support is only provided through email (*abhi.una12@gmail.com*) . Consider supporting my countless hours of hardwork and helping me out by making small *Donation for my ongoing Independent A.I. Research. Thankyou.*

# Huge thanks to:
https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/ & https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/ for guiding me through.

https://github.com/opencv for Latest OpenCV binaries.

https://github.com/01org/tbb for TBB binaries.

Love from India ❤️
