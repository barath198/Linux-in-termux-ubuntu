# Linux-in-termux-ubuntu
Ubuntu in termux is possible now                          
 required::
  +termux
  +real vnc form playstore
  installing:;
    Firstly install Termux apk from HERE

Secondly Clone the Repository & Run the setup File

yes | pkg up
pkg install git wget -y
git clone --depth=1 https://github.com/modded-ubuntu/modded-ubuntu.git
cd modded-ubuntu
bash setup.sh
Then Restart your Termux & Type the following commands

ubuntu
bash user.sh
Type your ubuntu root username. Must be lowercase & no space included.

Then Again Restart your Termux & Type the following commands

ubuntu
sudo bash gui.sh
You have to note your VNC password !!

Ubuntu image is now successfully installed .

Type vncstart to run Vncserver
Type vncstop to stop Vncserver
Install VNC VIEWER Apk on your Device. Google Play Store

Open VNC VIEWER & Click on + Button & Enter the Address localhost:1 & Name anything you like

Set the Picture Quality to High for better Quality

Click on Connect & Input the Password

Enjoy :D

NOTE :
Type ubuntu to run Ubuntu CLI.

Type vncstart to run Vncserver

Type vncstop to stop Vncserver

Type bash remove.sh to remove Ubuntu Modded Os
