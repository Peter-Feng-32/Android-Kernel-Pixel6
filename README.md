# Android-Kernel-Pixel6
This repo contains everything required to mod a Pixel 6 / Pixel 6 Pro to be compatible with ChatJR.

## General Instructions

We are currently using oriole-up1a.231005.007 as the factory image for the Pixel 6.  
You can download the factory image here.  https://developers.google.com/android/images#oriole

Afterwards, use Magisk to root and flash the image.  Detailed instructions on this are here https://xdaforums.com/t/guide-january-3-2024-root-pixel-6-unlock-bootloader-pass-safetynet-both-slots-bootable-more.4388733/.

Next, install the selinux permissive mod, under selinux_permissive_v2.

You now can flash the DOLPHIN_PIXEL_KERNEL image using KernelFlasher.
Instructions for how to install the kernel are found here. https://docs.google.com/document/d/1cOgwvLvqsew3jQnh54lIxPVeK0Rjg8ESd-bkQAu9yCk/edit?usp=sharing 

Then you can modify the buttons of the phone as required using the Button Modifier app.

All files required for the current release can be found here: https://drive.google.com/drive/folders/1Czlq03VKXpaodf7GQYIv8xCqcCTN6AXi?usp=sharing

## Detailed Instructions.

The files for the modified kernel are in EBISU under /data/android-kernel-pixel6/kernel.

Detailed instructions for what has been done to the kernel (and how to recreate it for other kernels) are in the https://docs.google.com/document/d/1jiR5Z201VJ3P34zbGd1lOfCxIsx7pZ8lKoJ4TbY4vaw/

