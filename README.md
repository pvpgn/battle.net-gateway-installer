Universal Battle.net Gateway Installer
============================

This script adds a new PvPGN server in the Windows registry without removing existing servers.
As a server's owner you can setup the script by once and then distribute it for your players.

![](http://habrastorage.org/storage2/e17/808/bf1/e17808bf1f80288d44e2928f326bcc41.png)


## Installation

Setup is very simple - just edit several variables in the bat file with any text editor:
```
	:: server connection
	set title=Your Server Name
	set address=127.0.0.1
	set timezone=1
	
	:: games to setup in the registry (true or false)
	set starcraft=true
	set warcraft3=true
	set diablo2=true
```
