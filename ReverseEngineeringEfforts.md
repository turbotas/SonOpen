IP addressess
-------------

Start your desktop controller softare and then go into Help, About My Sonos System...
This will give you some rudimentary data about each device including the IP address of each unit seen on the local network.
Armed with this information, you can start snooping about each unit using a broswer.  REplace the IP address with your own, noting that it's plain http and the webserver is running on port 1400.  

Works, as at Jan 2020
---------------------
http://192.168.1.10:1400/status

http://192.168.1.10:1400/status/zp

http://192.168.1.10:1400/status/enetports

http://192.168.1.10:1400/status/VERSION

http://192.168.1.10:1400/status/proc/ath_rincon/status

http://192.168.1.10:1400/status/ifconfig

http://192.168.1.10:1400/status/showstp

http://192.168.1.10:1400/support/review

http://192.168.1.10:1400/tools

http://192.168.1.10:1400/region



These ones found online but seem not to work
--------------------------------------------
http://192.168.1.10:1400/status/jffs/upgrade.log

http://192.168.1.10:1400/jffs/upgrade_prev.log

http://192.168.1.10:1400//diag/cgi-bin/bin/echo%20yes%20we%20can


using nmap on the device also finds port 1443 open and this seems to respond to the same requests as the 1400 port. prompt implies that this is also the upnp port.

Other open ports: tcp\1410, tcp\1843, tcp\1443, tcp\1400



