# winesteam-launcher
A simple bash script to launch steam games through wine with multiple window options.

I created this script to facilitate the launch of games via Wine that use the platform Steam, focusing mainly on the resolution of windows.

Wine has a problem with fullscreen applications where sometimes it happens not to return to the original resolution of the desktop and this can be very annoying at times.

This script is meant to do away with this problem, I created mainly to make my life easier with games on Linux but I decided to share it with the community because maybe it could be a useful thing for some people.

# Requeriments
* Linux Based OS
* Wine
* Steam (Wine)
* xdpyinfo
* xwininfo

# Usage

```
winesteam-launcher --help                                                This help.
winesteam-launcher --nativewindow [path_to_game.exe] [parameters]        Native windowed mode.
winesteam-launcher --virtualwindow [path_to_game.exe] [parameters]       Virtual windowed mode.
winesteam-launcher --nativefullscreen [path_to_game.exe] [parameters]    Native fullscreen mode.
```
