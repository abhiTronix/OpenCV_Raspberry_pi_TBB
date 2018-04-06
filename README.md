Latest pre-compiled binary of  OpenCV (3.4.1 dev) along with TBB (2018-Update 3) for the Raspberry Pi 

## Head over to https://github.com/abhiTronix/TBB_Raspberry_pi for installing TBB first.

# OpenCV [TBB + VFVP3 + NEON] (Update - April,2018):
Inspiration from amazing tutorial from Adrian (https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/)

Inside the tutorial, there is three possible ways of optimizing OpenCV:

1. NEON 
2. VFPV3 
3. Threading Building Blocks (TBB)

TBB is successfully installed on my Rpi3 and available precompiled at  https://github.com/abhiTronix/TBB_Raspberry_pi
Hence i created this pre-compiled Latest binary of OpenCV (3.4.1-dev ) along with Latest (2018 Update 3) of TBB for the Raspberry Pi 3. It is available in a ".deb" package and will save you countless hours not having to compile it yourself.  This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions.  This was compiled on a Raspberry Pi 3 Model B running raspbian stretch .  This enables TBB Support which helps multithreading in many OpenCV algorithms and significant **3x~5x** (https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/) increase in performance along with 'NEON' and 'VFVP3'.
For Files Look Down below.


# TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# Proof:

![](https://github.com/abhiTronix/OpenCV_Raspberry_pi_TBB/blob/master/new.gif)
My Proof of work: **OpenCV (version: 3.4.1 -dev) successfully compiled with TBB (version: 2018 - Update 3)] on Python 2.7.13 on my Raspberry Pi 3**.

# Installation Instructions :
## (Tested on Raspberry pi 3 with Raspbian Stretch [Latest])
Simple (but straight forward):
  ```
sudo dpkg -i <path to *deb file[e.g OpenCV_release_fp_tbb_armhf.deb]>
sudo ldconfig

  ```
# Files:
Latest .deb files and full support is only provided through email (*abhi.una12@gmail.com*) . Consider supporting my countless hours of hardwork and helping me out by making small *Donation for my ongoing Independent A.I. Research. Thankyou.*

# Huge thanks to:
https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/ & https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/ for guiding me through.

https://github.com/opencv for Latest OpenCV binaries.

https://github.com/01org/tbb for TBB binaries.

Love from India ;)
