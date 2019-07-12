teahouse-background-fox
=======================

A simple automated background switcher for gnome and xfce, to display the teahouse fox's adventures throughout the day

history
-------
Teahouse Fox was an iGoogle theme that showed us the idyllic life of a Fox.  He fed ducks, ate lunch, and he lit paper lamps at night. His simple joy, nestled in the background of a news feed, made my days a little brighter.

But then, in 2013, iGoogle was discontinued and the Teahouse Fox no longer had a home.

I imagine he has since been wandering the wastelands of the internet, seeking shelter and a return to his rustic peace, somehow maintaining his serene countenance despite the horrors he faced out in those wild dark places.

Homeless and wandering, until now.

Today his home has been reclaimed and reconstructed, painstakingly transported (grassblade by grassblade) onto my laptop’s wallpaper, thanks to the magic of bash, GNOME, and cron.

If you’d like to give the Teahouse Fox a home on your gnu/linux machine too, you can get this simple script from my Git-Hub Repository.  Feel free to fork, send a pull request with improvements, or simply clone it and use it on your own machine.

If you have any trouble making this script work, feel free to post here and I’ll see if I can help.

installation
------------

1.	Download this script to any suitable location (perhaps ~/bin or /.opt)
	- note: You can use "git clone" or you can manually download each file

2.	Add the appropriate entries to your cron schedule as indicated in cron-entries.txt
   	- note: use crontab -e to edit your cron schedule
	- note: modify the location of the script to where you put it

3.	Copy background-fox.desktop to ~/.config/autostart/. If this directory does not exist, create it.

4.	Edit ~/.config/autostart/background-fox.desktop to match script location
	- note: the only line that needs to be changed is line 5; set that to wherever you put the script.

5.	Logout and log back in, you should see the background updated to the appropriate fox!

test status
-----------

* Ubuntu 14.10 / Gnome 3 - works
* Ubuntu 16.10 / Gnome 3 - works
* Ubuntu 16.10 / XFCE 4.12 - works
