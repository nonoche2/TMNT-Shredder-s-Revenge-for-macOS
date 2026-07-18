# TMNT-Shredder-s-Revenge-for-macOS

This is based on [JohnnyOnFlame](https://ko-fi.com/johnnyonflame)'s port for [Portmaster](https://github.com/PortsMaster/PortMaster-New), using [FNA](https://fna-xna.github.io/) and [mono](https://gitlab.winehq.org/mono/mono) to run the game.

You will need to provide the game files for this port to work. In the Finder, navigate to ~/Library/Application Support/, create a folder named TMNT
and drop the game files inside.

> [!CAUTION]
> Known issue: the intro video will display blocky artifacts on some frames. This is due to the YUV to RGBa conversion for OpenGL, unfortunately I haven't been able to find a way to fix it. Contributions are welcome!

## How to get the game files from Steam

1. Make sure Steam is running, then type steam://open/console in Safari.
2. In the Steam console, type: download_depot 1361510 1361511
3. For the DLC type: download_depot 1361510 2348930 (you must have purchased it for it to work)
4. It’ll take about 20 minutes to download, but then it will show you a path to where the folder is located. It’s pretty deep in the MacOS file system, the easiest way to do that is through the Library folder. Open a new Finder window, press cmd + shift + g and a window will appear, paste the location that steam gave you a few moments earlier.

## How to get the game files from Epic

Use [Heroic Game Launcher](https://heroicgameslauncher.com/) to install the game
