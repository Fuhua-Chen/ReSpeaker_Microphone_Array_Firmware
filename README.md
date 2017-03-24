How To Use DFU Tool To Upgrade Your ReSpeaker Microphone Array Firmware
=======================================================================

### Requirements:
+ ReSpeaker Microphone Array Driver for Windows. [Click here](https://github.com/Fuhua-Chen/ReSpeaker_Microphone_Array_Driver)
+ New Firmware document (.bin file).

### Procedure:
		Please confirm that you have installed the ReSpeaker Microphone Array Driver, then:
1.	Enter the folder: 

	For x64: C:\Program Files\SeeedStudio\ReSpeaker Microphone Array\
	
	For x86: C:\Program Files (x86)\SeeedStudio\ReSpeaker Microphone Array\
	
2.	Double click ReSpeakerMicrophoneArrayDfu.exe

3.	Click Browse and choice your bin file for upgrade.

4.	Click Start.

5.	Wait for the tool prints successful information.

### DFU details:
Please refer to XMOS official document:	
[XMOS DFU loader](https://www.xmos.com/support/boards?version=latest&product=14772&component=14441&page=5)

### Updates:
20170324 pre release
xvsm version: 0x032
raw  version: 0x080  

1. Add new Firmware which is output 8 channels mic raw data  
this firmware is without xvsm dsp support, so it does not support some functions such as DOA, AEC and so on.  

2. update xvsm version(initial version) parameters:
According to users' feedback, noise supression is not work well and cannot recognize the key words on resoeaker  
core. The parameters have been changed and are closed to XMOS official parameters. But the distance will shorter
than previous.

#### Worth the wait...
