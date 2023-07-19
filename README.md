# AirPodsPro-Motion-Sampler with OSC Forwarder

Code Examples of CMHeadphoneMotionManager in CoreMotion.

## Requirements 
 - Xcode: 15.0+
 - iOS  : 14.0+ or macOS Sonoma Beta+ on Mac computers with Apple silicon
 - iPhone, iPad (*1)
 - AirPods Pro(1st or 2nd generation) / AirPods Max / AirPods(3rd generation) or Beats Fit Pro

<small>*1: iPod Touch (7th generation) is not supported.</small>  
<small>*2: The necessary sensors are included, so it should work.</small>

## How To Build for iOS:
Open ```AirPodsProMotion.xcodeproj``` on Xcode15 or later, then connect your iPhone or iPad to build it.  

## How To Build for macOS Sonoma on Mac computers with Apple silicon:
Open ```AirPodsProMotion.xcodeproj``` on Xcode15 or later, choose My Mac (Mac Catalyst) as Run Destination and build it. 

 
## Contents
 
 |  <center> Infomation View </center> | 
 | ---- | ---- | ---- | ---- |  
 |  <center> ![](README_resources/info.gif)　</center> |  


- infomation View   
Displays the information (```CMDeviceMotion```) obtained from AirPodsPro and forwards the Yaw, Pitch and Roll data via OSC to the localhost on Port 9999. Set to autostart/recover the OSC stream whenever any AirPodsPro are connected to the device.

  
## Reference
 - [Apple Developer Documentation](https://developer.apple.com/documentation/coremotion/cmheadphonemotionmanager)


## Author of the original AirPodsPro-Motion-Sampler repository this fork is built on:
 Yoshio Tsukuda  
 - [HP](https://tukuyo.net/)
 - [Twitter](https://twitter.com/tukutuku_tukuyo)
