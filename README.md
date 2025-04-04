# GE-Proton Rolling Release
GE-Proton Rolling Release (ge-proton-rr) is a software that generates a new compatibility tool for Steam based on the latest version of GE-Proton. It uses the "Rolling Release" philosophy, meaning there's only one version, and it's the final one (the latest version of GE-Proton).

![App](https://raw.githubusercontent.com/FranjeGueje/GE-Proton-RR/refs/heads/master/img/GE-Proton-RR.png)

GE-Proton Rolling Release creates a compatibility tool called "GE-Proton" with the latest version of GE-Proton downloaded from the Internet, example GE-Proton-9.11, and will be maintained to use the Rolling Release philosophy. On subsequent runs, it will update to the next version from the GE-Proton website but keep the same tool on Steam so you don't have to change anything about your games. It would use the same philosophy that "Proton Experimental" does.

The idea is to do the same as with Proton Experimental, have a single version and make it the final one, in other words, following the philosophy of Rolling Release Linux distributions.

The next time it's released, if there's a new official version of GE-Proton, it will download it and return it to Steam with the same name. How does this benefit us? If we have 40 games that use this compatibility tool, GE-Proton will already be highlighted, and we won't have to go through all 40 games to change their settings. As mentioned above, there's only one GE-Proton version, and it's the final one (that we've downloaded). An image:

![App on Steam](https://raw.githubusercontent.com/FranjeGueje/GE-Proton-RR/refs/heads/master/img/GE-Proton-RR-on_Steam.png)

## Features
- It uses the same "Rolling Release" philosophy as "Proton Experimental." There's only one version, and it's the latest.
- It doesn't interfere with other installed versions of GE-Proton.
- It creates a new compatibility tool called "GE-Proton" that uses the latest version of GE-Proton from the internet.
- It updates itself from the internet on subsequent runs.
- It backs up any changes to the tool in case you make any changes.
- It will retain the same compatibility tool on Steam so you don't have to change anything in your games.
- It works on both desktop and GameMode.
- It now updates itself.
- Option to silently launch the desktop on every boot.

## Download and Run
The current version of the program can be downloaded from releases.
To run it, simply make the executable file and double-click it.
To see the advanced options, you can run it with the --help option in the console.

## FAQ
_If I have this GE-Proton Rolling Release installed, can I have another version (GE-Proton 9.10, for example) because it works better in a specific game?_ Yes, with Proton-UP, for example, you can install as many versions of GE-Proton as you want; this program will not interfere.

_If I want to uninstall it, how can I do so?_ Yes, with Proton-UP, for example, you can do so by deleting the "/home/deck/.local/share/Steam/compatibilitytools.d/GE-Proton/" folder.