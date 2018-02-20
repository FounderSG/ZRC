# ZRC
Configure Universal IR Remote using smart phones
### Supproted hardware
1. Ti reference remote CC2650RC. Use Ti Flash Programmer to program cc2650zrc.hex, the hex file can be found in firmware folder. 
2. Ti CC2640R2 LaunchPad. Use Ti Flash Programmer to program launchzrc.hex, the hex file can be found in firmware folder. see [DIY BLE to IR Bridge](https://foundersg.github.io/diy-ble-to-ir-bridge.html)
### Goal
The aim of this project is to create a easy to use Universal IR Remote.
### Architecture
Remote control hardware support both IR and BLE, remote control can send IR on key press or BLE command. smart phone app contains thousands of remote conrol IR functions categories by device and brand. App can send IR by send BLE command to remote, App can assign IR function to a remote control button. 
### Why
Traditional universal IR remote is hard to use, mainly due to limited user interface, the user have to use magic key sequences to setup, the only feedback is LED blinking. with smart phone app as a front end, it is much easier to locate IR function you wanted, hence a much easier setup experience.
### App
Download [FzRemote](http://appstore.com/fzremote) from App Store.
### Known problems
CC2650RC IR signal is quite weak, the IR angle is also quite small, it is not a good remote in IR point of view.
