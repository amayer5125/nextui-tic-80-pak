# NextUI TIC-80 Pak

A [TIC-80](https://tic80.com/) [Libretro](https://www.libretro.com/) core for use with [NextUI](https://nextui.loveretro.games/) to play TIC-80 games.

## Installation

1. Download the TIC.pak.zip file from the [latest release](https://github.com/amayer5125/nextui-tic-80-pak/releases) on GitHub.
1. Extract the zip file onto your SD card in the `/Emus/tg5040` directory. You should see a new TIC.pak directory after extracting.
1. Create the `/Roms/TIC-80 (TIC)` directory on your SD card for your games.

You can download most games for free from the [TIC-80 website](https://tic80.com/play) or the [itch.io website](https://itch.io/games/tag-tic-80). Place the .tic files in the `/Roms/TIC-80 (TIC)` directory.

## Supported Languages

See [TIC-80 Supported Languages](https://github.com/nesbox/TIC-80/wiki/supported-languages) for specific information about any of the languages listed below. The goal is to include as many supported languages as possible to make playing cartridges as simple as possible.

The following languages are complied into the Libretro core.

- Fennel
- Janet
- Javascript
- Lua
- Moonscript
- Python
- Scheme
- Squirrel
- WASM (complied languages)
- Wren

The following languages **are not** compiled into the Libretro core. They may be included in the future, but for now I can not get them to build.

- Ruby

## Debug Logs

If you are having trouble launching games you can look for clues in the debug logs at `/.userdata/tg5040/logs/TIC.log`.
