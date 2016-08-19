
![HDA Icon](https://raw.githubusercontent.com/insanelydeepak/cloverHDA/master/cloverHDA.jpg)
# cloverHDA 

This cloverHDA.kext enables audio/sound on Mac OS 


### Requirements : 
  1 - Vanilla/Native AppleHDA 
  2 - a good Kext Installer or [EastKextPro](http://www.insanelymac.com/forum/files/file/397-easykext-pro-a-minimal-and-super-fast-kext-installer/)
  3 - Property List Editors - Xcode or Property List Editor, PlistEdit Pro, TextEdit, etc.
  4 -  must have CLOVER/config.plist
       i. RtVariables/BooterConfig/0x28
       ii. RtVariables/CsrActiveConfig/0x3 


### Installation :

  1 - Download cloverHDA.kext as per your Audio ID's 
  2 - Install using EastKextPro or any Kext Installer
  3 - Now apply patches from cloverHDA.plist to your Clover config.plist 
  4 - Add Layout_ID = 13 , 11 or 12 as described in ReadME.txt 
  5 - Restart 

#### Note : for Layout_ID you can use DSDT (HDEF Patch) or Clover (Clover/Config.plist/Devices/Audio/Inject=Audio_ID) or [HDAEnabler's kexts](https://bitbucket.org/insanelydeepak/hdaenablers-applehda-for-hackintosh/downloads)

### Layout_ID/Audio ID description :

      1 - Layout_ID 11 = ​​3 ports supported (Pink, Green, Blue) (Note : without auto-switch , you have to manually select between output/input device's) 
      2 - Layout_ID 12 = 5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue) 
      3 - Layout_ID 13 = 5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue, 

### Supported Codec/DEVICE_ID :

  You must have one of the following DEVICE_ID/Codec name described below :
 
      1 - Realtek ALC to Desktop's: ALC662,ALC883,ALC887,ALC888,ALC889,ALC892
      2 - Realtek ALC to Laptop's: ALC233,ALC268,ALC269,ALC270,ALC272,ALC275,ALC280, ALC298 
      3 - Conexant for laptop's: CX20590,CX20724 
      4 - IDT for Laptop's: IDT 92HD66C3/65,IDT92HD75B3X5,IDT92HD81B1X5,IDT92HD87B1 
      5 - VIA Laptop's: VT1802 
      6 - Cirrus Logic Laptop's: CS4213 and CS4210 

###  [Troubleshooting :](https://raw.githubusercontent.com/insanelydeepak/cloverHDA/master/TroubleShoot/Troubleshoot Reporting.md)
       Repair Permission using EasyKexPro or other tool you like 
       Restart , if still not getting sound devices then :
       please report with Requested files 


This kext is based on  [PikeRAlpha's DummyHDA method](https://pikeralpha.wordpress.com/2013/12/17/new-style-of-applehda-kext-patching/) and Clover Patches on fly  method's
### Credits :
PikeRAlpha, Mirone, EmlyDinesh, The king, Master Chief, RevoGirl, toleda, bcc9, TimeWalker and many others who contributed to AppleHDA patching.

