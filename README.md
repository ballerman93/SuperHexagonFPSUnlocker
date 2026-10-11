# SuperHexagonFPSUnlocker
an actual good fps unlocker for super hexagon for windows that smooths a lot more shit than [tarkodevs unlocker](https://github.com/tarkodev/SuperHexagonFPSUnlocker)

the game still runs at 60 updates a second like normal so gameplay and times are exactly the same. it just draws extra frames in between and smooths everything that moves so it actually looks smooth on high refresh monitors.

## how to use
1. close the game
2. run `SHFPSUNLOCK.exe` (or `SHFPSUNLOCK.py` if you have python 3.10+)
3. pick `1` to install or `2` to uninstall
4. pick your `SuperHexagon.exe` to patch
5. type your fps limit (`0` = uncapped, otherwise 61 to 1000) and if you want an fps counter

for best results, turn off vsync in super hexagon and use an fps value that runs good for you

if the game is open while installing the installer will automatically close your game

## config
after installing there's a `fpsunlock.ini` next to the game:
```
cap=240
show_fps=0
```
- `cap` = fps limit, `0` = uncapped
- `show_fps` = `1` shows an fps counter in the bottom left

## notes
- only works on the current steam version of super hexagon neo as the exe gets checked before patching
- uninstall puts the original exe back exactly
- installing adds `fpsunlock.dll` and `fpsunlock.ini` to the game folder and changes a few bytes in `SuperHexagon.exe` so it loads the dll
