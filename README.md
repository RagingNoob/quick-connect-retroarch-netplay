# quick-connect-retroarch-netplay
Small HTA written app that connects P2P retroarch games.
Quick Connect Retroarch Netplay v1.00b JUNE 2018
For Windows 7+
Protected under GNU General Public License v3.0

READ ME!

RETROARCH NETPLAY:
Retroarch is a powerful emulator with the best known P2P network connection available for CPS1/2/3 to date via NetPlay.
It uses the best netcode yet seen and works brilliantly on low latency connections.

This application, Quick Connect Retroarch Netplay v1.00b, when setup correctly, will quickly connect to another system that runs the same version and game.

******************************************
*This application requires the following:*
******************************************

1. You have Retroarch correctly installed and configured (video/sound, inputs joystick/pad etc).
2. This application is located in the main Retroarch directory/folder; containing "retroarch.exe"
3. You have   "Arcade (FB Alpha)"   core downloaded and installed in the "cores" folder. (fbalpha_libretro.dll)
4. Host and client must have the same core revision as well as version. The revision is the 7 hex characters number after the core name and version.

Example: 
Retroarch version - Core Name - Core Version - Core Revision
   1.7.3          - FB Alpha    v0.2.97.43     469a2ac

Utilise netplay properly:

You both need to be running the same version of retroarch
You both need to be running the same emulator (core and core revision)
You both need to have the same exact rom

4a. Make sure to share with your connected party:

When HOSTING:
Your IP Address
Your Open Port
Your Delay Frames Number
Your selected Core and ROM

When JOINING as a client:


5. Default port is 55435 TCP and if any connecting problems arise then open this port and/or port forward to your PC.

6. *IMPORTANT* All roms supported by Quick Connect Retroarch Netplay should be located in the "roms" folder (along with all the other retroarch folders
Currently 3 roms are supported:

sf2hf.zip
sfiii3nr1.zip
ssf2xjr1.zip

*************************************************************************************************
Upcoming versions:
1. Include more games on demand.
2. Allow a custom roms folder.
3. Check if the application is placed in the correct directory. (done)
3a. Check if the application can find the "roms" and the file "fbalpha_libretro.dll" (done)
4. Ability to change video_mode setting; drop down options.
5. Include custom port changing.
6. Button to copy HOST IP to the clipboard. (done)
7. Option to set a password before hosting/joining.
7. Ability to display relevant current config settings.
7. Edit essential config settings.
8. Validate IP entry (done)
*************************************************************************************************

INFORMATION:

Source: https://github.com/RetroNbcake/quick-connect-retroarch-netplay/releases

GNU General Public License v3.0
Licence: https://github.com/RetroNbcake/quick-connect-retroarch-netplay/blob/master/LICENSE

VirusTotal (4 false positives) : https://www.virustotal.com/#/file/ba8a727eea477337d9b07937356ff5dfb94b446b2e947539205b3a9b0cc2f7b3/detection

Included in this zip is the freeware "metapad.exe", an alternative and enhanced text editor, which the application uses to edit the 'retroarch.cfg'. Source: http://liquidninja.com/metapad/

*************************************************************************************************
*************************************************************************************************
*************************************************************************************************
Special thank you to TheBox for introducing the idea of a front end and all the silly hours of testing various emulators and setups.
Thank you to Air_Bacon, lo-fi, Shine, Pof, furiadeoso, RoyBisel for various help in tests, advice and sharing information.
*************************************************************************************************
*************************************************************************************************
*************************************************************************************************

