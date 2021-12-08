# VSCODE config

Adjuste folders in VSCODE:

1. go to settings.Json
2. "explorer.compactFolders": true,


# React Native Config ios chip M1

Start Project

1. npx react-native init seuapp
2. npx react-native run-ios

- if your project not generate archive "xcworkspace" in folder "IOS" do the following command:

1. sudo arch -arch x86_64 gem install cocoapods
2. sudo arch -arch x86_64 gem install ffi
3. arch -arch x86_64 pod install
