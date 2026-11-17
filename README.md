# Battle for Bikini Bottom Vita

<img src="shot1.png"></img><br>

Port of Spongebob: Battle for Bikini Bottom for PSVita based off [the decompilation](https://github.com/zcanann/bfbb) of the Gamecube version.

## Features

- 960x544 internal resolution.
- Support for MSAA (up to 4x, defaults to Off).
- Optional 30 FPS lock (Defaults off).
- Widescreen support (Defaults to On).
- Ability to invert X and Y axis for camera.

## Special Controls

- Additional options menu accessible by touching the top-left portion of the screen.

## How to Install

- Install `libshacccg.suprx`, if you don't have it already, by following [this guide](https://samilops2.gitbook.io/vita-troubleshooting-guide/shader-compiler/extract-libshacccg.suprx).
- Install the vpk from the Release tab.
- Extract the `setup.zip` from the Release tab in a folder in your PC.
- Place the iso file of `Spongebob: Battle for Bikini Bottom (GQPE78 NTSC-U revision 0)` for Gamecube named as `bfbb.iso` in the same folder where you extracted the zip.
- If you don't have it already, install [Python 3.10 or higher](https://www.python.org/downloads/windows/).
- Open a command line in the same folder where you extracted the zip and run: `powershell.exe -NoProfile -ExecutionPolicy Bypass -File .\prepare_data.ps1 -Source "bfbb.iso" -FFmpeg "ffmpeg.exe"`
- Place the whole content of `DataForVita\bfbb` in `ux0:data/bfbb`.

## Credits

- Everyone involved in the [decompilation of the game](https://github.com/zcanann/bfbb)
- Darth Bellic for testing the game and for the Livearea assets.
