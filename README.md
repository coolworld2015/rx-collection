# RN Collection
git clone https://github.com/coolworld2015/rn-collection.git
-------------------------------------------------------------------------------------------------
git config --global user.name "coolworld2015"
-------------------------------------------------------------------------------------------------
git config --global user.email "wintermute2015@ukr.net"
-------------------------------------------------------------------------------------------------
npm install -g react-native-cli
-------------------------------------------------------------------------------------------------
react-native init AwesomeProject
-------------------------------------------------------------------------------------------------
cd AwesomeProject
-------------------------------------------------------------------------------------------------
react-native run-android
-------------------------------------------------------------------------------------------------
react-native start
-------------------------------------------------------------------------------------------------
react-native run-ios
-------------------------------------------------------------------------------------------------
react-native run-ios --simulator="iPhone 5"
-------------------------------------------------------------------------------------------------
http/https - NSAllowsArbitraryLoads in \ios\Cool\Info.plist
-------------------------------------------------------------------------------------------------
https://www.diawi.com/ for *.ipa
-------------------------------------------------------------------------------------------------
To install the version you need to do the following:
1) Open the build link on your device's Safari browser. You may just open this email on your device and tap that link.
2) Tap "Install application" on opened page.
3) Pop-up which propose to install an app will appear. Tap "Install".
4) Tap Home button to hide Safari, app is installing.
5) Now you need to trust ... Enterprise profile to be able to run installed app. To do that you need to: 
a) Go to Settings => General => Profiles & Device Management.
b) Select "... Professional Ooo".
c) Tap "Trust "... Professional Ooo"".
d) Pop-up will appear, tap "Trust" there.
6) That's it. Move back to springboard and run the app.
Installed.
-----------------------------------------------------------------------------------------------------
xCode 8 update
-----------------------------------------------------------------------------------------------------
RCTWebSocet -> Apple LLVM 8.0 Custom... -> other warning flags
-----------------------------------------------------------------------------------------------------
CameraRoll added
-----------------------------------------------------------------------------------------------------
get node_modules->react-native->Libraries->CameraRoll - then copy RCTCameraRoll.xcodeproj to
-----------------------------------------------------------------------------------------------------
xCode -> Libraries -> PROJECT/TARGET -> Build Phases -> Link Binary With Libraries
-----------------------------------------------------------------------------------------------------
react-native link - for Linking
-----------------------------------------------------------------------------------------------------
Info.plist ->  add <key>NSPhotoLibraryUsageDescription</key><string>$(PRODUCT_NAME) photo use</string>
-----------------------------------------------------------------------------------------------------
NativeModules add
-----------------------------------------------------------------------------------------------------
Project -> Libraries -> React.xcodeproj -> React -> Base - New file (Objective-C File)
-----------------------------------------------------------------------------------------------------
RCTCustom.m - import NativeModules from 'react-native' - use NativeModules.ReadImageData.readImage
-----------------------------------------------------------------------------------------------------