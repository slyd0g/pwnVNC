# Blogpost
https://grumpy-sec.blogspot.com/2017/02/scanning-entire-internet.html

# Usage
python pwnvnc_master.py

# Input
List of IPv4 addresses with port 5900 open (obtained from nmap, masscan, etc)

# Output
Snapshots (sorted by IP) of anyone running a VNC session without any form of authentication

# Comments/Disclaimer
This script was written on Debian Jessie 8 and requires OS commands. If you want this to run on other OS, adjust the OS command that echo's current index to a file and the OS command that performs the VNC snapshot.

Usage:  <a href= "https://github.com/shamun/vncsnapshot">vncsnapshot</a> must be installed and in the user's path

Big thanks to the developers of vncsnapshot, this project would not be possible without them!

Disclaimer: This was written for informational/educational purposes only. You can use/modify this as you please, however, I (Justin Bui) am not responsible for any legal problems you may face using this information. 
