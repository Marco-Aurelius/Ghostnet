Gostnet is a Linux-based free and open source reticulum chat platform inspired by the work of S2Underground.  The intention of this project is to provide any community with an easy to deploy, reasonably secure messaging service with transport across mesh radio and TCP networks.  The creator of this program did not invent reticulum.  This is merely a front end for other people's work and is intended to allow the "average joe" a means of communication for recreation, experimentation or in times of emergency.

Because reticulum is encrypted by default, mind your local laws when deploying across radio networks.  This may be illegal depending on your area in the world. 

For online installation using terminal: 
-Move the .deb file to a preferred location on a Linux machine and install using apt
  Example: sudo apt install /path/meridian-ghostnet_1.3.2_amd64.deb

For offline installation using terminal:
-Move the .tar.gz file to a preferred location on a Linux machine
-Navigate to the location you moved the .tar.gz file.
  Example: cd /path/to/meridian-ghostnet_1.3.2_amd64.tar.gz
-Extract the .tar.gz file
  Example: tar xzf meridian-ghostnet_1.3.2_amd64.tar.gz
-Navigate to the newly created directory
  Example: cd /path/to/meridian-ghostnet_1.3.2_tarball
-Install
  Example: sudo bash install.sh

After installation, Ghostnet will be served on http://localhost:8090 in your web browser or across your local network at your station's ip address on port 8090 (XX.XX.XX.XXX:8090).  A login screen for a server based deployment can be configured in settings once the program is launched.

The creator of Ghostnet relied HEAVILY on AI coding agents because he's not very good at coding. Therefore, he won't be of much help to you in troubleshooting problems with the source code.  If you're smarter than the creator of Ghostnet, you should improve it and publish it to the community.