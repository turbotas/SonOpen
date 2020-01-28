IP addressess
-------------

Start your desktop controller softare and then go into Help, About My Sonos System...
This will give you some rudimentary data about each device including the IP address of each unit seen on the local network.
Armed with this information, you can start snooping about each unit using a broswer.  REplace the IP address with your own, noting that it's plain http and the webserver is running on port 1400

Works, as at Jan 2020
---------------------
http://192.168.1.10:1400/status
http://192.168.1.10:1400/status/zp
http://192.168.1.10:1400/status/enetports
http://192.168.1.10:1400/status/VERSION
http://192.168.1.10:1400/status/proc/ath_rincon/status
http://192.168.1.10:1400/status/ifconfig
http://192.168.1.10:1400/status/showstp

These ones found online but seem not to work
--------------------------------------------
http://192.168.1.10:1400/status/jffs/upgrade.log
http://192.168.1.10:1400/jffs/upgrade_prev.log
http://192.168.1.10:1400//diag/cgi-bin/bin/echo%20yes%20we%20can
