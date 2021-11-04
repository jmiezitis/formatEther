# formatEther
Takes a selected MAC address and reformats it for various different devices.

Built for linux and X11 systems formatEther takes whatever is in the selected buffer and upon clicking on Convert provides a list of MAC addresses formatted for different systems.

For example a MAC address from a Comware device 1cea-0bda-ef00 will be reformated for:  
CISCO = 1cea.0bda.ef00  
Linux DHCPD config = 1c:ea:0b:da:ef:00  
Eliminate all seperators = 1CEA0BDAEF00  

Choose the required format from the Convert pull down menu and the result is placed in the copy/paste buffer

Requires:
* Perl 5
* Perl/Tk
