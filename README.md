Medal Of Honor : Allied Assault SDK
===================================

This package provides MOHAA SDK and tools for developers to create contents.
MOHAA has been developed with the engine `Quake3`.

This game is now free. You can download and modify it easily to create awesome contents.
To download the game: [https://classiccup.frontspawn.com/mohaa](Download MOHAA).

Contents
========

- Mapping
	- MoHRadiant (english version): original editor version to create maps.
		- This package includes also a french version translated by **Caskami Prod**.
	- MBuilder: the BSP compiler
	- Sources (maps)
		- Standard multiplayer (MP) .map files (dm/mohdm1 - dm/mohdm7, obj_team1 - obj_team4) as they were released in 2005
		- Standard single player (SP) mission 4 .map + script files
- Tools
	- BspToMap.exe: convert .bsp files to .map files (use it carefuly just in dev needs)
	- MohaaScriptEditor.exe: create/edit scripts .scr files (a basic IDE)
	- MohaaTikEditor.exe: create/edit .tik files
	- Packscape.exe: create/edit .pk3 files
	- BSP_Viewer3D.exe: a basic BSP viewer 3D.

Installation
============

Zip archive
-----------

Download ZIP file here.

Composer (PHP)
--------------

### Builder

To easily build, test and release your contents, 
I suggest you to use the PHP console provided by the package 
[https://github.com/Ang3/php-mohaa-builder](ang3/php-mohaa-builder).

### SDK only

Open a command console, enter your project directory and execute the
following command to download the latest stable version of this package:

```console
$ composer global require ang3/mohaa-sdk
```

Binaries are now accessible from your global composer binaries. 
Add the path of the Composer binaries directory in your environment variable `PATH` to launch tools easily.

Links
=====

Links for tutorials and others useful contents:

- Discord servers
	- [https://discord.gg/p3jD8h3c](MOHAA community)
- French
	- [https://www.amigos3d.fr/tutos_moh_index.php](Amigos3D): tutorials of the famous french creator **Amigos3D** from the old **Caskami Prod**
	- [http://tropheus.tropheus.free.fr/sommaire.html](Tropheus tutorials): advanced tutorials to understand the language and others basics
- English
	- [https://github.com/gtsh77/MOHTools](gtsh77/MOHTools): another repository for the MOHAA SDK where you can find more information about SDK usage.
	- [https://www.mohaaaa.co.uk/AAAAMOHAA/content/guides-and-tutorials](mohaaaa.co.uk guides and tutorials): The reference for contents
		- Scripting advices: [https://mohaaaa.co.uk/AAAAMOHAA/sites/default/files/AAAA/guide/mohaa_scripting_advice.pdf](Mohaa_Scripting_Advice) by`**chrissstrahl**
	- Scripting:
		- [https://www.x-null.net/forums/forums/75-Developer-Documentation-for-Scripting](Developer Documentation for Scripting)

You can find some others useful links or contents. I will add others later.

Have fun! ;)