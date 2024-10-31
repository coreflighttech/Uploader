# Uploader

Uploader (Xloader) is a firmware installer tool.

Core Flight Tech. modules can talk with the Xloader.

How to do? 
First Steps:
- Close all applications
- Connect your Module via USB
- Run Xloader.exe in the "Uploader"

Then;

For FCU: 
  - Select the device type -> A320 FCU
  - Com port is the Module USB port number (check on the Device Manager)
  - Click the "Hex file" selection button
  - Find the "A320_FCU_MF.hex" on your computer
  - Click the Upload button

For EFIS, LANDING GEAR LEVER, ATC., COMM., NAV., FLAP etc.
  - Select the device type -> "EFIS/NAV/COMM/ATC/ADF V1"
  - Com port is the Module USB port number (check on the Device Manager)
  - Click the "Hex file" selection button
  - Find the latest firmware that you installed before.
  - Click the Upload button

    If Xloader still says "Uploading" after 1 min., disconnect the USB cable and then connect it
	- Select the device as "EFIS/NAV/COMM/ATC/ADF V2"
	- Check the Com Port is the USB port which connected to the Module
	- Click the Upload button
     
If any help is needed, please feel free to contact us.
info@coreflighttech.com

www.facebook.com/coreflighttech

Discord: https://discord.gg/73GBsFAs
