# Podcast Questions - Chapter 11

[DragonFly BSD](https://dragonflybsd.org "Dragon Fly BSD") - Listen to this podcast: [https://ia802605.us.archive.org/9/items/bsdtalk248/bsdtalk248.mp3](https://ia802605.us.archive.org/9/items/bsdtalk248/bsdtalk248.mp3 "DragonFly BSD")

* ~1:25 What did DragonFly BSD drop with the 4.0 release?

Dropping 32 bit support 


* ~1:40 What was the other major feature that DragonFly BSD added?

Workstations support for 
displays and GPU support

* ~3:40 What modification did they add to the Packet Filter?

They modified it so that it could run concurrently on multiple CPU's 

* ~10:00 What is the largest system DragonFly BSD has access to?

They have access to a 128 core hardware

* ~11:45 What is the difference between DragonFly BSD's network stack compared to BSD and Linux?

The network stack is very far diverged from all the other BSD's.  

* ~13:25 What is the limitations of the Hammer 1 Filesystem?

The clustering.  It does not do clustering 

* ~13:45 What features will Hammer 2 Filesystem add?

Significantly higher performing snapchot feature and also the addition of clustering 

* ~15:45 What is the intended use case of Hammer 2 FS?

Intended to be multiple nodes over a wide area network.  Intended to be multimaster

* ~18:00 What sub-system is still in the works needed to make DragonFly BSD a stable work station?

New sound system is in the works.  Needed to run Pulse audio

* ~25:00 What is package-ng?

It is a free BSD port system 

* ~30:00 How does DragonFly BSD handle suspend and resume functions common to laptops?

It is not reliable enough.  

* ~35:50 What is the growing issue about systemd in relation to BSD?

They have been trying to figure out how much a systemd has to be implemented in order for many of the ports that linux has targeted.  They need some sort of inferstructure 

* ~38:00 Of the 20,000 packages available in DragonFly BSD where are they primarily targeted?

to Linux

* ~38:30 Out of FreeBSD, OpenBSD, NetBSD, and DragonFly -- what is each project focusing on?

FreeBSD - working on compartimentalization of network stacks

OpenBSD - working on a Systemd replacement 

NetBSD - working on a Systemd replacement 

DragonFly - getting rid of choke points and performance 

* ~40:23 How does GPL based Linux software cross over into BSD distros?

Differnt parts of Linux runs off of different licenses.  It has not been a big issue 