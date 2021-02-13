# OculusQuest2andUnity
How to setup Unity for use with Oculus Quest 2
1.	Activate Developer Mode via Oculus app
2.	Plug in Oculus Quest 2 via oculus link cable. Click Yes on any prompts on Oculus Quest
3.	Install adb manager
https://www.xda-developers.com/install-adb-windows-macos-linux/
4.	Use command prompt to connect to oculus quest 2 via adb debugging
  a. open command prompt from the directory where you installed the adb .exe C:\...\platform-tools_r30.0.5-windows\platform-tools\
  b. command is adb devices, which will generate a prompt on your Oculus Quest 2 (click yes)
5.	Start new 3D project in Unity
6.	Switch to Android Build
7.	Switch to Oculus Quest 2 device in build settings
8.	Install Oculus XR plugin
9.	Install Oculus Integration from asset store
