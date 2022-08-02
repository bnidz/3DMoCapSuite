{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # 3D MoCap Suite - Blender Addon\
3D MoCap Suite - iOS App's Blender Addon Repository\
\
## FEATURES\
\
* Track 52 - iOS ARKIT native blendshapes in real time\
* Track Head object rotation \
* Track Head object position\
* Track Client APP Camera position and position\
\
## INSTALLATION\
\
* Minimum Blender version 2.8.0 and up \
* Download the zip from this repository [MoCapSuite_A25_2.zip](https://github.com/bnidz/3DMoCapSuite/blob/main/MoCapSuite_A25_2.zip)\
* Follow the screenshot bellow in Blender 1. Edit 2. Preferences 3. Addons 4. Install \
* After that select the .zip file you downloaded and Make sure the checkbox for the addon is checked\
\
![basic_install](https://user-images.githubusercontent.com/31888418/168494888-5729e649-5470-430f-a990-cf2a811f055c.png)\
\
## USAGE\
 \
![Screenshot 2022-05-16 at 1 02 08](https://user-images.githubusercontent.com/31888418/168495701-77147539-ee65-4f47-b8c5-f69bba1c39b3.png)\
\
* Download the Defaul [.Blend file](https://github.com/bnidz/3DMoCapSuite/blob/main/3DMoCapSuite_Default_BlendFile_A001.blend) from this repository and open it on your blender\
* Have the addon installed and on the object mode, press N to open the sidebar and select the addon tab\
* Select the correct objects for the head and the camera \
* Assign correct values for the IP and PORT fields\
* After everything is set, you can press START to Start UDP server on the selected port\
* You can change values of the checkboxes while the server is running\
* Press RECORD - to start recording shapekeys, you have to have timeline running :)\
\
## CLIENT / iOS APP\
* [You can download the iOS App for free ](https://apps.apple.com/us/app/mocap-suite/id1628689936)\
* Requires Iphone / iPad with FaceID cabapilities \
\
## ACKNOWLEDGEMENTS\
* Latest version Sun 17. Jul / 2022 HotMinute\
* Full Body motion tracking update coming soon!\
\
\
\
## Known issues:\
* Close connection from the iOS app first, otherwise the used port can be left stuck. \
 * SOLUTION: use next PORT with + and start have the START going again\
 * IF using just head mesh, you dont have to have the "Rig Empty" Assigned. But if you have your own rig setup, you can assign an empty object, and it will follow the head movements\
}