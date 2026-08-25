_______________________________________________________________________

  G r a n d  T h e f t  A u t o  III

  ReadMe.txt

_______________________________________________________________________

 CONTENTS
__________

	CONTACT INFORMATION
	SYSTEM REQUIREMENTS
	GENERAL INFORMATION
	INSTALLATION
	KNOWN ISSUES
	3D VIDEO CARD DRIVERS		

_______________________________________________________________________
 
 CONTACT INFORMATION
_____________________

Thank you for purchasing “Grand Theft Auto III”.

This ReadMe contains last minute information and troubleshooting tips.

For news, hints, and the Grand Theft Auto III community, check out 
	 
	www.rockstargames.com 
	www.take2games.com
	www.gta3.com

For Technical Support

Web: www.take2games.com
Email: support@take2baltimore.com 
Phone 410-933-9191 Monday to Friday, 9am-5pm EST.

_______________________________________________________________________

 SYSTEM REQUIREMENTS
____________________

Supported Operating Systems:

Grand Theft Auto III uses Microsoft DirectX 8.1.
Supported Operating Systems are:

	Windows 98
	Windows 98 Second Edition
	Windows Millennium
	Windows 2000 Professional (Workstation)
	Windows XP (Home and Professional)

The following operating systems are NOT supported:

	Windows 95
	Windows NT (any version)
	Mac OS
	Linux
	BEOS

Minimum Hardware Requirements
	
	450 MHz Intel Pentium III or AMD Athlon processor
	96 MB of RAM
	4 speed CD / DVD drive
	700 MB of free hard disk space
	16 MB video card with DirectX 8.1 compatible drivers
	DirectX 8.1 compatible sound card
	Keyboard
	Mouse

Recommended Hardware Requirements
	700(+) MHz Intel Pentium III or AMD Athlon processor
	128(+) MB of RAM
	8 speed CD / DVD drive
	700 MB of free hard disk space
	32(+) MB DirectX 8.1 hardware video card
	DirectX 8.1 compatible sound card with surround sound
	Gamepad (USB or Joystick Port)
	Keyboard
	Mouse

_______________________________________________________________________

 GENERAL
_________

DirectX:
Grand Theft Auto III requires Microsoft DirectX 8.1 to run. As a 
consequence we recommend that the video and sound drivers installed are 
also DirectX 8.1 compliant. Even better, use a true hardware DirectX 
8.0 / DirectX 8.1 card.

Windows XP:
We recommend manufacturer distributed drivers for Windows XP (i.e. 
drivers that expose the user controls for changing settings on the 
particular piece of hardware), instead of the default drivers installed 
by Microsoft as part of the machine setup process.

Memory:
Grand Theft Auto III requires at least 96 MB of memory to run. For 
optimal performance at least 128 MB is recommended (256 MB preferred).

Running Applications:
Grand Theft Auto III has been designed to take best advantage of the 
available machine it is running upon, therefore we recommend that you 
close down all applications before running Grand Theft Auto III.

Video Memory:
Grand Theft Auto III requires a video card with 16 MB of video memory 
or greater to run. Grand Theft Auto III will refuse to run if it is 
launched on a machine with less than 16 MB video memory.

AMD K6/2 and K6/III processors:
These AMD processors both play Grand Theft Auto III at too low a speed 
to be acceptable.

_______________________________________________________________________

 INSTALLATION
______________

Insert Grand Theft Auto III disc one into the CD / DVD drive. 
If you have Autoplay enabled then the setup routine will automatically 
launch. 
If you do not have Autoplay enabled, then use Explorer to navigate 
Grand Theft Auto III disc one, and manually launch setup.exe

Footprint
Grand Theft Auto III requires approximately 700 MB of hard disk space.

Save Games
Grand Theft Auto III uses the “My Documents” directory of the currently 
logged in user to store the “GTA3 USER FILES” directory. This is where 
we store save games. This was chosen to allow each user on Windows 2000 
or Windows XP to have their own saves.

Uninstallation
When Grand Theft Auto III is uninstalled, we do not delete the “MP3”, 
“SKINS” and “GTA3 USER FILES” directories. It is up to the user to 
remove these manually.

_______________________________________________________________________

 CONFIGURATION
_______________

Sound Provider:
The sound API selected inside Grand Theft Auto III options can effect 
game performance - try alternative sound providers to achieve better 
results. Try Software, MSS Fast, RSX, Direct Sound Hardware, Direct 
Sound Software.

Dynamic Acoustic Modeling
Turn off Dynamic Acoustic Modeling in the Sound Options for a small 
performance gain.

Trails
Turning off the Trails effect in Grand Theft Auto III display settings 
will help increase speed.

Screen Resolution
Selecting lower Screen Resolutions in Grand Theft Auto III display 
setup will allow faster gameplay on lower end machines. Also using 16 
bit color, instead of 32 bit color, will help in these circumstances.

_______________________________________________________________________

 TROUBLESHOOTING
_________________

Windows XP + nVIDIA based cards (possibly other brands):
We have found a possible problem with Windows XP that manifests itself 
as graphical problems both in the game menu and also during game play. 
We have traced this problem to be a Windows XP problem.
Technically this problem is solved by the use of a newer version of 
d3d8.dll than is shipped on CD with Windows XP. (The version on the 
Windows XP CD that has problems is 5.1.26000.0 – versions tested 
without error include 5.1.2600.15 and 5.1.2600.29)
Currently the only way we know to update this dll file is to install 
the Windows XP Patch: “The Computer Cannot Enter Standby or Hibernate 
If a Direct3D-Based Screen Saver Is Running (Q306676)” downloadable 
from the following Web Site:
http://download.microsoft.com/download/whistler/Patch/Q306676/WXP/EN-
US/Q306676_WXP_SP1_x86_ENU.exe.
This update may in the future be available as part of an official 
Windows XP Service Pack, a Windows XP Compatibility Update, or possibly 
a DirectX 8.1 update.

Power VR Kyro 2 video cards
We have been unable to fully support this card due to the nature of 
rendering on this card, and as a consequence some texture effects do 
not display correctly, though these are minor. We recommend this video 
card is used with a 32 bit screen mode, as in 16 bit we discovered a 
rare depth buffer issue, which is solved in 32 bit. We would also 
recommend making the following settings changes:
=> Go to the advanced display properties dialogue
	Select the Direct 3D page, and create a new profile for gta3.exe,
	Then inside this profile:-
		DISABLE W buffer
		ENABLE external depth / stencil buffer format
		ENABLE Direct 3d / stencil buffer format
		ENABLE depth / stencil buffer format
		ENABLE depth / stencil buffer loading

Aureal sound cards:
We have noticed a lot of crashing problems reported with Aureal sound 
cards. This manufacturer has ceased trading and is not issuing new 
drivers. We have had many problems with supporting Aureal cards in the 
past, and with currently existing drivers these cannot be cured - 
though trying non-Aureal Sound Providers may prove to be more 
successful than the native Aureal Provider. (i.e. Software, MSS Fast, 
RSX, Direct Sound Hardware, Direct Sound Software).

Motherboard based sound chips:
We have found certain motherboard based sound chipsets do not report 
having a hardware sound buffer, and crash with Grand Theft Auto III. We 
found that running Microsoft’s “DXDIAG” and performing the sound tests, 
will present the user with an error message saying that a hardware 
buffer is not supported, and would you like to use a software buffer. 
Selecting a software buffer will allow this sound chipset to work with 
Grand Theft Auto III.

Hard Disk Defrag
If you are experiencing short, periodic slowdowns whilst driving, Grand 
Theft Auto III may be having trouble retrieving data at a fast enough 
rate from your hard disk. It is recommended that you run your systems 
Defragmentation utility regularly to allow optimum speed in the game’s 
performance.

_______________________________________________________________________

 3D VIDEO DRIVERS
__________________

We recommend using the latest available Video drivers for your video 
card. Where available use the video chipset manufacturers “Reference” 
drivers in preference to video card manufacturer customized drivers or 
Microsoft WHQL certified drivers.

Below for convenience are common video card manufacturer’s websites. 
Grand Theft Auto III may not support some or all video cards by a 
particular manufacturer. Inclusion of a manufacturer in this list does 
not mean there are any assurances of compatibility.

3Dfx Interactive 		- http://www.3dfx.com/
3Dlabs 				- http://www.3dlabs.com/
Asus 				- http://www.asus.com/
ATI 				- http://support.atitech.ca/
Aztech Labs 			- http://www.aztechlabs.com/
Canopus 			- http://www.canopuscorp.com/
Creative Labs 			- http://www.creativelabs.com/
Diamond Multimedia 		- http://www.diamondmm.com/
Elsa Technology 		- http://www.elsa.de/
Guillemot 			- http://www.guillemot.com/
Hercules (see Guillemot) 	- http://www.guillemot.com/
I/O Magic 			- http://www.iomagic.com/
Jaton 				- http://www.jaton.com/
Leadtek 			- http://www.leadtek.com/
Matrox 				- http://www.matrox.com/
NVIDIA 				- http://www.nvidia.com/
Orchid (see Diamond MM) 	- http://www.diamondmm.com/
SIII Incorporated 		- http://www.sIII.com/
SiS 				- http://www.sis.com.tw/
VIA Technologies 		- http://www.viatech.com/
VideoLogic 			- http://www.videologic.com/

_______________________________________________________________________

This software and documentation 
Copyright © 2002 Rockstar Games.