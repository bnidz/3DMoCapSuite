# 3D MoCap Suite - Blender Addon
3D MoCap Suite - iOS App's Blender Addon Repository

## FEATURES

* Track 52 - iOS ARKIT native blendshapes in real time
* Full body IK controls (touch from iOS app)
* Live Record
* Virtual camera - works identically in addon and in app (touch controls)

## INSTALLATION

* Minimum Blender version 2.8.0 and up 
* Download the zip from this repository [MoCapSuite.zip](https://github.com/bnidz/3DMoCapSuite/blob/main/MoCap%20Suite.zip)
* Follow the screenshot bellow in Blender 1. Edit 2. Preferences 3. Addons 4. Install 
* After that select the .zip file you downloaded and Make sure the checkbox for the addon is checked

![basic_install](https://user-images.githubusercontent.com/31888418/168494888-5729e649-5470-430f-a990-cf2a811f055c.png)

## USAGE
<img width="364" alt="app_ui_" src="https://user-images.githubusercontent.com/31888418/216853389-5c7e3f85-18bd-473b-849f-fc5b7df7efd2.png">
<img width="405" alt="app_default_model_" src="https://user-images.githubusercontent.com/31888418/216853381-cd452532-55e0-480e-8e24-9f22705be8e3.png">

* Have the addon installed and on the object mode, press N to open the sidebar and select the addon tab
* Assign correct values for the IP and PORT fields (APP actually should get your address automaticly)
* Input the same values that you have in the addon to the iOS MoCap Suite App and press START
* Select Character's Armature in Object mode
* After everything is set, you can press START from the Addon and you should see the same character movements in Blender :)
* Press RECORD - to start recording shapekeys, you have to have timeline running :)

## CLIENT / iOS APP
* [You can download the iOS App for free ](https://apps.apple.com/us/app/mocap-suite/id1628689936)
* Requires Iphone / iPad with FaceID cabapilities 

## ACKNOWLEDGEMENTS
* Latest version Sun 6. Feb / 2023 HotMinute
* Full Body motion tracking update coming soon!

## Known issues:
* IK controls disappear after using the IK button
 - workaround: use the reset character position button to respawn IK's
* with lower end devices having multiple avatar changes can cause fps drop, but bootin the app should help
 - Fix for this coming in the next update
