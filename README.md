# IntensityProCapture
Mouse Click Image Capture with Intensity Pro 

These are instructions on how to use a simple command line capture program with the Blackmagic Intensity Pro card and a mouse driven telecine.
Hardware
Plug the card into the PC. Connect the card HDMI input to your camera.
Software
Install  desktop video from here
https://www.blackmagicdesign.com/support/family/capture-and-playback
Download the software from this repo onto your local drive.
Capture Instructions
Make sure the desktop video is properly installed.
Run Blackmagic Media Express app and test your camera setup with it.
Unzip the downloaded somewhere close to the top directory on your PC.
Open up file explorer and go to the Release directory
...\CaptureStillsMouse\x64\Release
![capture1](https://user-images.githubusercontent.com/48537944/223294699-bfe9b780-ff80-4333-9c8d-3015a65b17b6.jpg)
Now  click on the address bar in the windows explorer so that it gets highlighted.
 
![capture2](https://user-images.githubusercontent.com/48537944/223295055-470c374d-3a42-49ab-a347-b844bd86db82.png)


Then without touching anything type in
cmd
on you keyboard
and hit enter.

The command window will open up.
 
 ![capture3](https://user-images.githubusercontent.com/48537944/223295288-57c850d5-9a55-48e7-bb83-75abda6a5267.png)

 
Get the scanner and your camera ready.  
Create a capture folder such as
C:\capture\
Type in the following command in the command window:
capturestills.exe -d 0 -m 11 -n 1 -i 1 c:\capture\
Move the mouse cursor somewhere in the empty area of the desktop.
Run Workprinter
The sw will start capturing png images.
Once done stop the Workprinter and hit CTRL C in the command window to stop the capture.
Post process the images in VirtualDub. 




