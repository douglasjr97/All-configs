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

# How to run Native and Expo at the same time

With the android and ios folders exposed, you can open an android folder directly in Android Studio and an ios folder directly in Xcode (by clicking the file - which is actually a folder - .xcworkspace) and run it as if it were a native app . You can even create native code and expose that code to gain access through React Native. In this project that I showed there, I use Bareworkflow precisely to be able to access the native code and have a more precise control of the GPS on each platform.

# Links
[Typescript Introduction RocketSeat](https://www.notion.so/Typescript-5712aeab312d44fcba0aa88895caad36) 
   
   # Github alias
   
   
   First Execute this command: 
   ```bash
$ code ~/.gitconfig
```
   
   than:
   ```bash
$ [alias]
	st = !git status
	c = !git add --all && git commit -m
```
  

