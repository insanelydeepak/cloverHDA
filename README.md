
![HDA Icon](https://raw.githubusercontent.com/insanelydeepak/cloverHDA/master/cloverHDA.jpg)
# cloverHDA

This cloverHDA.kext enables audio/sound on Mac OS 


# Requirements : 

1. Vanilla/Native AppleHDA 
2. a good Kext Installer or [EastKextPro](http://www.insanelymac.com/forum/files/file/397-easykext-pro-a-minimal-and-super-fast-kext-installer/)
3. CLOVER/config.plist/ 
 a. RtVariables/BooterConfig/0x28
 b. RtVariables/CsrActiveConfig/0x3 


# Installation :
1. Download cloverHDA.kext as per your codec 
2. Install using EastKextPro or any Kext Installer
3. Now apply patches from cloverHDA.plist to your Clover config.plist 
4. Add Layout_ID = 13 , 11 or 12 as described in ReadME.txt 
5. Restart 
## Note : for Layout_ID you can use DSDT (HDEF Patch) or Clover (devices/Audio) or [HDAEnabler's kexts](https://bitbucket.org/insanelydeepak/hdaenablers-applehda-for-hackintosh/downloads)








This kext is based on  [PikeRAlpha's DummyHDA method](https://pikeralpha.wordpress.com/2013/12/17/new-style-of-applehda-kext-patching/) and Clover Patches on fly  method's
#Credits :
PikeRAlpha, Mirone, EmlyDinesh, The king, Master Chief, RevoGirl, toleda, bcc9, TimeWalker and many others who contributed to AppleHDA patching.

