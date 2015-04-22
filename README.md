##Why this software
####VR Headset stabilization in a nutshell
We noticed that the problem summarised here under will be a limitation to the use of VR headset on motion simulation platform.
![Problem description](http://www.vectionvr.com/img/explanation.jpg)
To simulate the acceleration of a car, a motion simulator would lean the player's seat backwards. This would be interpreted by the Oculus Rift as looking up. 
Our goal is to solve this problem by changing VR headset reference orientation according to the motion platform current orientation. This process is obviously only reliable if a fast and accurate motion platform orientation sensor is used.
Obviously we simplified the problem to ease the understanding but this problem is even stronger in case of 6 degrees of freedom platform.

####Reference implementation
Our reference implementation is a java based implementation available [here](https://github.com/VectionVR/VRHeadsetStabilizer) Please refer to it for more details
##Improvements / Custom needs
We know that this software requires a lot of improvement and we will try to keep it up to date. If you want any changes to be done and cannot do it yourself or want any custom development, feel free to [contact-us](mailto:contact@vectionvr.com).

##Disclaimer
######*VectionVR is in no way affiliated with OSVR. All source code or binary library is provided as is. VectionVR, Bnome or any of their representatives can in no way be held liable for any damages caused by using this software.*
