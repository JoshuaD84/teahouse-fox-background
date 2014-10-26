background-fox
==============

A simple automated background switcher for gnome, to display the teahouse fox's adventures throughout the day

installation
------------

1.	Download this script to any suitable location (perhaps ~/bin or /opt)
	- note: You can use "git clone" or you can manually download each file

2.	Add the appropriate entries to your cron schedule as indicated in cron-entries.txt
   	- note: use crontab -e to edit your cron schedule
	- note: modify the location of the script to where you put it

3.	Copy background-fox.desktop to ~/.config/autostart/

4.	Edit ~/.config/autostart/background-fox.desktop to match script location
	- note: the only line that needs to be changed is line 5; set that to wherever you put the script.

5.	Logout and log back in, you should see the background updated to the appropriate fox!

test status
-----------

1. Ubuntu 14.10 - works
