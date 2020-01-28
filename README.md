# SonOpen
Open source version of Sonos without the end of life problem.  PLANNING. Would be wonderful to use Sonos hardware!

Mission Statement
-----------------
Many people have spend thousands on their Sonos systems.  With good reason because it's a great system.  It passed the 'Apple' test in that it 'just works'.

In January 2020, Sonos announced that some of the products would be obsoleted and would stop working.  But much more than that, any systems with those obsolete components in would stop working.  This is a terrible descision.  The functionally identical equivalents cost hundreds.  Sonos quicky undertook some corporate spin and backpedalled part of their announcement, but they didn't undo it - they just watered it down.

This has caused many to wonder if another way is possible?  this project may never write a line of code but it has lofty, but simple goals:

1) Drop in replacement for Sonos.  Support music libraries and streaming services.  Support the same file types.  Must have smartphone app and desktop controller app.

2) Must (somehow) support real Sonos hardware.  The easiest way to do this is to stream to the devices.  The (much) harder way is to replace the proprietary firmware with open (linux) firmware and software.  The mid difficulty solution is a hardware mod, for example to use the amp, PSU and speaker and drop in some other hardware (like an rPi).

Easy problems
-------------
Accessing music libraries
Making a datbase
streaming content to existing sonos devices

Medium problems
---------------
Making smartphone and desktop apps
deciding on local vs distributed music database

Hard problems
-------------
Running custom firmware on Sonos
timing different speakers playing the same thing.

Moral Problems
--------------
Sonos is a closed platform.  They may not appreciate reverse engineering their hardware.  Maybe they have legal protection.  If the hardware reverse engineering sub-project is sucessful, then an even trickier problem is what to do with units in recycle mode?  The moral problem is that the owners of these units have received discounts off new hardware in return for bricking the old ones.  Sonos will argue that they should not and must not work.  If we get as far as dumping flash from a working Sonos unit, can we return a recycle mode unit to (native) Sonos operation.  Should we? 


TurboTas January 2020
