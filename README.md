Latest pre-compiled binary of  OpenCV (3.4.1 dev) along with TBB (2018-Update 3) for the Raspberry Pi 

## Head over to https://github.com/abhiTronix/TBB_Raspberry_pi for installing TBB first.

# OpenCV[ TBB + VFVP3 + NEON] (Update -2018):
Inspiration from amazing tutorial from Adrian (https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/)

Inside the tutorial, there is three possible ways of optimizing OpenCV:

1. NEON 
2. VFPV3 
3. Threading Building Blocks (TBB)

TBB is successfully installed on my Rpi3 and available precompiled at  https://github.com/abhiTronix/TBB_Raspberry_pi
Hence i created this pre-compiled Latest binary of OpenCV (3.3.1-dev ) along with Latest (2018 Update 2) of TBB for the Raspberry Pi 3. It is available in a ".deb" package and will save you countless hours not having to compile it yourself.  This may or may not stay updated as I have to manually compile this version.  I will try to make available most major versions.  This was compiled on a Raspberry Pi 3 Model B running raspbian stretch .  This enables TBB Support which helps multithreading in many OpenCV algorithms and significant 3x~5x (https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/) increase in performance along with 'NEON' and 'VFVP3'.


# TBB ( Intel(R) Threading Building Blocks )
TBB is a library that helps you leverage multi-core processor performance without having to be a threading expert. It represents a higher-level, task-based parallelism that abstracts platform details and threading mechanism for performance and scalability.
More info. at https://www.threadingbuildingblocks.org/

# Proof:

![alt text](https://raw.githubusercontent.com/abhiTronix/OpenCV_Raspberry_pi_TBB/new.gif)

# Installation Instructions :
## (Tested on Raspberry pi 3 with Raspbarian stretch)
Simple (but straight forward):
  ```
sudo dpkg -i <path to *deb file[e.g OpenCV_release_fp_tbb_armhf.deb]>
sudo ldconfig

  ```
# Files:
Support my hardwork and Email me at abhi.una12@gmail.com for Latest .deb files of precompiled Opencv with TBB. 

# Huge thanks to:
https://www.pyimagesearch.com/2017/10/09/optimizing-opencv-on-the-raspberry-pi/ & https://www.theimpossiblecode.com/blog/build-faster-opencv-raspberry-pi3/ for guiding me through.

https://github.com/opencv for Latest OpenCV binaries.

https://github.com/01org/tbb for TBB binaries.

Love from india ;)
