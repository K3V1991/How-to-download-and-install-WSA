<p align="center"><img src="https://i.ibb.co/hgh9b77/WSA.png" width="200"></a>
<h1 align="center"><b>How to download and install the Windows Subsystem for Android</b></h1>
<br />

## Requirements:
* Windows 11
* Virtual Machine Platform Feature enabled
* Microsoft UI Xaml (appx)
* Windows Subsystem for Android (msixbundle)

## Enable Developer Mode:
1. Open Settings
2. Head to Privacy and Security Settings and search for the For developers
3. Tap on the Toggle to enable the Developer Mode and confirm it by clicking on Yes 

## Enable Virtual Machine Platform:
1. Click on Start
2. Search for Turn Windows features on or off. Click on the first Option.
3. Scroll down and search Virtual Machine Platform
4. Checkbox and click OK
5. Restart Windows

## Download & install Microsoft UI Xaml:
```Includes the Framework to run Windows Subsystem for Android. Pre-installed on Windows Insider Builds.```
<br />
1. Visit the Website: [rg-adguard.net](https://store.rg-adguard.net/)
2. Change the first Option to ```ProductID```
3. Paste ```9P3395VX91NR``` in the Search Bar
4. Change the Channel to ```RP```
5. Click on the [ ✓ ] Button
6. Let it generate the List of Files
7. Download the following File:
```
Microsoft.UI.Xaml.2.6_2.62112.3002.0_x64__8wekyb3d8bbwe.appx
```
```Note: The Version may change with Time```

8. Double click the donloaded File and install it
9. You are now ready to install WSA

## Download & install Windows Subsystem for Android:
1. Visit [rg-adguard.net](https://store.rg-adguard.net/) again
2. Change the first Option to ```ProductID```
3. Paste ```9P3395VX91NR``` in the Search Bar
4. Change the Channel to ```Slow```
5. Click on the [ ✓ ] Button
6. Let it generate the List of Files
7. Download the following File:
```
MicrosoftCorporationII.WindowsSubsystemForAndroid_2205.40000.14.0_neutral_~_8wekyb3d8bbwe.msixbundle
```
```Note: The Version may change with Time```

8. Install with a double Click or use PowerShell:
9. Go to the Location where you have downloaded the WSA Bundle File
10. Right click on the WSA File and select Copy as Path
11. Now, search for Windows PowerShell in the Windows Search
12. Launch PowerShell as Administrator
13. Paste the following Code in the PowerShell Window:
```
Add-AppxPackage -Path
```
14. Right after the -Path Text, press the Spacebar and paste the "Copy as Path" Text from earlier using Keyboard Shortcut CTRL + V

Example: 
```
Add-AppxPackage -Path "C:\Users\User\Downloads\WSA\MicrosoftCorporationII.WindowsSubsystemForAndroid_2204.40000.19.0_neutral_~_8wekyb3d8bbwe.Msixbundle"
```
15. Let the installation finish
16. Once done, type Android in the Windows Search and you will see the Windows Subsystem for Android installed
17. Enjoy Android on Windows
