# compton.config
Compton window manager configuration

Install Compton
To do that, run the following commands in a terminal window. These will add the official Compton PPA [3] and then install it:

$ sudo apt-add-repository ppa:richardgv/compton
$ sudo apt-get update
$ sudo apt-get install compton

Once it’s installed, create a text file in ~/.config/ called compton.conf.

Press Alt+F2, type compton in the Application Launcher box, then press ente

----------Set Compton to auto-start--------------------------
Assuming that worked, we’ll make Compton start at startup. Go into the Applications menu and click ‘Settings Manager’, then click ‘Session and Startup’, then select the ‘Application Autostart’ tab
