FitMc
===========

INSTALLATION
----

Open a terminal and run
"sudo add-apt-repository ppa:xorrito/fitmc && sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install fitmc"
Follow the onscreen instructions.
This will update and install all needed programs and FitMc.

Be Advices!!!
----
I've written this in Ubuntu and I am using tools already available to me in this environment so some things might not work in other distros.

I do not guarantee anything but I wish come close to.

Also if you happen to have a window manager other than compiz just use the "log on" part of it. with it logs you off when the thin window manager closes.

FitMc uses Technic-Launcher as a minecraft client. Vanilla is available in Technic-Launcher's modpack list.

NEWS
----

* *Version 2.5-18 <br/>
  * Changed Desktop Icon.

* *Version 2.5* <br />
  * Added Clock.

* *Verison 2.4-1* <br />
  * Fixed FitMc menu not starting until technic fully closed.

* *Version 2.4* <br/>
  * Fixed Texture and mod installer/remover.

* *Version 2.3* <br/>
  * Option to remove textures and mods.
  * Technic Log cleaner at start.

* *Version 2.2* <br/>
  * Unity integration.
  * Option to not change Window Manager.

* *Version 2.1* <br/>
  * Should have checked before uploading.

* *Version 2* <br/>
  * All Features implemented.
  * Mod installation asks for selection to avoid conflicting with other modpacks
  * Fixed Texture Installer....again but with if loop this time
  * Log cleanup moved to start up to allow troubleshooting

* *Version 1.9* <br/>
  * Fixed Texture Installer

* *Version 1.8* <br/>
  * Updated version numbers for lwgjl and Technic launcher.

* *Version 1.7* <br/>
  * Changed Release Target to raring
  * Removed TroubleShooting menu and Optimized the main menu
  * Disable Texture installing as it is broken
  * Made version controlling easier
  * Updating Launcher Version now possible but not the best

* *Version 1.6* <br/>
  * Fixed .log cleaning
  * Changed starting proses in hopes to speed up loading
  * Fixed finishing wd to avoid issues
  * Moved .deb file to ppa:xorrito/fitmc

* *Version 1.5* <br/>
  * Finished option to install texture pack
  * Changed direction where user level files reside (.technic/FitMc)
  * Fixed main starting program not pointing to the right logo
  * Fixed "force re-download for game files to be able to work with all modpacks

* *Versions 1 to 1.5 <br/>
  * Code scraped and re-writen multiple times.

* *Version 1* <br/>
  * Start of project.


Known Bugs
-----

  * Fix stiky keys seems broken with new modpacks. Not sure if its my fault or something else.

  * Log in logo dosen't seems to show up.


Future
-----

  * All images are place holders and will be changed to nicer ones

Features
-----

* Auto-fetching of Technic-Launcher
* Switch window managers to a slim one (with redundancy just in case if it dosent start on the first try)
* Menu with: 'quit, log off, turn off, install textures, install mods, Re-Fetching of the launcher, Restart of launcher/game, Force game files to re-download, and a fix to sticky keys'
* aided texture pack installation, will only add one and link from the other modpacks to lower space used
* aided mod installation for per modpack to avoid conflicts with other modpacks
* Version shown in main menu for easy tracking
* Clock Display to keep track of time (usefull only in the thin window manager)

Reasoning of troubelshoot items
-----
* For the Re-fetching of the launcher is an old problem I used to have where it will hang even before it could download anything, deleting it and re-downloading it seemed to work.
* Restart of launcher: in oldish systems minecraft likes to freeze so this is a quick way to fix that. (granted if you can release the mouse of MineCraft)
* Force game files re-download: I run a server and sometimes the clients will give me a "mod missing or outdated" and this fixes it. it forces everything to re-download (not touching saves, statistics, last-login)
* Fix Sticky keys: this downloads an updated version of lwjgl and installs it to the game files, and seems to fix the sticky key situation.

-------
Feed back is greatly appreciated!
