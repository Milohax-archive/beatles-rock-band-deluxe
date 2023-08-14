# The Beatles: Rock Band Deluxe

![Header Image](dependencies/art/beatles_dx_big.png)

# Introduction

### The Beatles: Rock Band Deluxe is a Quality-of-Life Improvement Mod by [MiloHax](https://github.com/hmxmilohax)

This guide contains full instructions on how to install The Beatles: Rock Band Deluxe for PlayStation 3 or Xbox 360.

# Table of Contents  
- [Features](#features)
  - [Quality of Life](#quality-of-life)
  - [Additional Modifications](#additional-modifications)
- [What You'll Need](#what-youll-need)
- [Downloads](#downloads)
- [How to Install](#how-to-install)
  - [Installing on RPCS3 (Recommended for PC)](#installing-on-rpcs3-recommended-for-pc)
  - [Installing on PS3](#installing-on-ps3)
  - [Installing on Xbox 360](#installing-on-xbox-360)
  - [Installing on Xenia](#installing-on-xenia) **(DEV/TESTING ONLY)**
- [Optional Upgrades](#optional-upgrades)
  - [Songs](#songs)
  - [Custom Textures](#custom-textures)
- [Repo Setup (Advanced)](#repo-setup-advanced)
- [Dependencies](#dependencies)

## Features

### Quality of Life
* No strum limit executable modification
* Fast start executable modification
* Additional intro skip scripting to skip the intro movie
* "Overshell" - a custom on-screen menu system for changing speeds. Opened by pressing `SELECT, SELECT` on most menu screens
* Bass streak effect from RB3/RB4 available on all instruments
* Selectable song speed and track speed by 5% increments
* Selectable venue framerate up to 60fps
* Manual calibration adjusts by 1ms instead of 5ms

### Additional Modifications
* Hue-shifting menu
* Nice (69%) and Fab Choke (98-99%) callouts on solo completion

# What You'll Need

### Playing The Beatles: Rock Band Deluxe requires these things:

- **A vanilla copy of The Beatles: Rock Band** for PS3 or Xbox 360 that you can extract onto your PC. The **USA** version is required for PS3 (`BLUS30282`)
- For Console: A **modded/hacked PS3 or Xbox 360** and a way to transfer files to it, we recommend using FTP
- For Emulator: A **mid-to-high-end PC** capable of running RPCS3

# Downloads

### [The Beatles: Rock Band Deluxe for PS3](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-PS3.zip)

*NOTE: The Beatles: Rock Band Deluxe on PS3/RPCS3 installs differently compared to the other Deluxe projects.*

### [The Beatles: Rock Band Deluxe for Xbox 360](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-Xbox.zip)

# How to Install

## Installing on [RPCS3](https://rpcs3.net/) (Recommended for PC)

*NOTE: The Beatles: Rock Band Deluxe on PS3/RPCS3 installs differently compared to the other Deluxe projects.*

* **Install your North American copy of The Beatles: Rock Band** through the emulator. The [**official RPCS3 site covers this nicely**](https://rpcs3.net/quickstart).
  * Remember, **you need to be running** ***BLUS30282***. RPCS3 will tell you this in the game selection GUI under the `Serial` column.

* Download [**The Beatles: Rock Band Deluxe for PS3**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-PS3.zip).
  * Extract the zip and **drag and drop the `.pkg` file on top of the main RPCS3 window** to install it.
  * Select `Yes` to confirm.

* Download [**TBRBDX: PS3 Disc Patch**](https://github.com/hmxmilohax/beatles-rock-band-deluxe/raw/main/dependencies/TBRBDX-PS3DiscPatch.zip)
  * Extract the zip and **copy the contents of the folder to where your vanilla copy of The Beatles: Rock Band is installed**.
  * Select `Yes` to overwrite the files.

***The Beatles: Rock Band Deluxe is now installed!***

**To update The Beatles: Rock Band Deluxe**, [**re-download it**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-PS3.zip) and repeat the above steps. You can click the `Watch` button (All Activity) to be notified about any updates that occur.

*Sidenote: it is normal for The Beatles: Rock Band to take longer to start up on PS3 and isn't really something we can fix.*

***Sidenote:*** *we recommend* ***enabling `Write Color Buffers`*** *for The Beatles: Rock Band to prevent any character model issues.*

![Custom Configuration](dependencies/images/customconfig.png)
![GPU Tab](dependencies/images/gputab.png)
![Write Color Buffers](dependencies/images/writecolorbuffers.png)

## Installing on PS3

**NOTE: You WILL need a HACKED/MODDED (CFW or HFW/HEN) PS3 in order to play this mod on console. We hope this is clear.**

**NOTE: The Beatles: Rock Band Deluxe only works with** ***North American (`BLUS30282`)*** **copies of the game on PS3.**

*NOTE: The Beatles: Rock Band Deluxe on PS3/RPCS3 installs differently compared to the other Deluxe projects.*

* **Dump or extract your North American copy of The Beatles: Rock Band** to your PS3's hard drive.
  * Remember, **you need to be running** ***BLUS30282***.

* Download [**The Beatles: Rock Band Deluxe for PS3**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-PS3.zip). 
  * Extract the zip and copy the `.pkg` file to the root of a FAT32 formatted USB drive.
  * Remove it from your PC and plug it in to the *rightmost* USB port on your PS3.
  * Navigate to `Package Manager > Install Package Files > Standard` in the XMB and install it just like any other package.

* Download [**TBRBDX: PS3 Disc Patch**](https://github.com/hmxmilohax/beatles-rock-band-deluxe/raw/main/dependencies/TBRBDX-PS3DiscPatch.zip)
  * Extract the zip and **copy the contents of the folder to where your vanilla copy of The Beatles: Rock Band is installed** (we recommend using FTP to do so).
    * If you used MultiMan to dump your game, it should be in `\dev_hdd0\GAMES\BLUS30282-[The Beatles Rock Band]\`.
  * Select `Yes` to overwrite the files.

***The Beatles: Rock Band Deluxe is now installed!***

**To update The Beatles: Rock Band Deluxe**, [**re-download it**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-PS3.zip) and repeat the above steps. You can click the `Watch` button (All Activity) to be notified about any updates that occur.

*Sidenote: it is normal for The Beatles: Rock Band to take longer to start up on PS3 and isn't really something we can fix.*

## Installing on Xbox 360

**NOTE: You WILL need a HACKED/MODDED (RGH or JTAG) Xbox 360 in order to play this mod on console. We hope this is clear.**

* **Install your vanilla copy of The Beatles: Rock Band** to your console's hard drive.
  * In case anything goes wrong, we recommend that you **rename `default.xex` to `default_vanilla.xex`**.

* Download [**The Beatles: Rock Band Deluxe for Xbox 360**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-Xbox.zip). 
  * **Copy the contents of it to where your copy of The Beatles: Rock Band is installed** (we recommend using FTP to do so). Select `Yes` to overwrite the files.

* We also recommend **clearing your song cache**, as well as your **system cache**.
  * *To clear your **song cache**, navigate to `System Settings > Storage > The Beatles: Rock Band` and delete the song cache.*
  * *To clear your **system cache**, navigate to `System Settings > Storage` and press `Y` to clear the system cache.*

***The Beatles: Rock Band Deluxe is now installed!***

**To update The Beatles: Rock Band Deluxe**, [**re-download it**](https://nightly.link/hmxmilohax/beatles-rock-band-deluxe/workflows/build/main/TBRBDX-Xbox.zip) and repeat the above steps. You can click the `Watch` button (All Activity) to be notified about any updates that occur.

## Installing on Xenia

### ***WARNING: THE BEATLES: ROCK BAND IS UNPLAYABLE ON XENIA AND IS USED FOR DEVELOPMENT AND TESTING PURPOSES ONLY!!!***

*Follow [**Repo Setup (Advanced)**](#repo-setup-advanced) first in order to properly follow this guide.*

* **Extract your vanilla copy of The Beatles: Rock Band** and copy the contents of the `gen` folder to `\_build\xbox\gen\`.

* Navigate to `_xenia` and **map your controller with x360ce**.
  * When it asks you to create `xinput1_3.dll`, create it and **rename it to `xinput1_4.dll`**.

* Then, **navigate to `windows_bats`** if you're on Windows or **`user_scripts`** if you're on Linux and **run `build_xenia` to automatically update, build, and run The Beatles: Rock Band Deluxe.**
  * *You need to run this script every time in order to play and update the game. `run_xenia` will run the game only and won't update and build it unless a new update is available, so you can use that if `build_xenia` takes too long.*

***The Beatles: Rock Band Deluxe is now installed!***

***Sidenote:*** *if you're experiencing issues regarding character models, navigate to `_xenia`, open `xenia-canary.config.toml` in your text editor of choice, and change `gpu` from `vulkan` to `d3d12` and `d3d12_readback_resolve` from `false` to `true` (you may need to press `CTRL + F` to find these). This will fix all texture issues but will drastically affect the framerate, you also may experience BSODs. If you don't want to deal with any of this, we recommend using* [***RPCS3***](#installing-on-rpcs3-recommended-for-pc) *instead.*

![D3D12](dependencies/images/d3d12.png)
![Readback Resolve](dependencies/images/readbackresolve.png)

# Optional Upgrades

*These are some optional, but very handy additions you can make to your The Beatles: Rock Band Deluxe installation.*

## Custom Textures

The Beatles: Rock Band Deluxe has a variety of custom textures, found in the `Deluxe Settings` menu in-game, as well as a way to import your own with relative ease.

### Importing Your Own Textures

*Follow [**Repo Setup (Advanced)**](#repo-setup-advanced) first in order to properly follow this guide.*

* Copy any `.jpg`, `.png`, or `.bmp` file into `\custom_textures\***\`, then navigate back to `windows_bats` and run `process_textures_***.bat`.
  * These will make them show up in game, resize your images accordingly (including those with arbitrary resolutions), and convert them to the proper format for The Beatles: Rock Band Deluxe to read.

***You will need to rebuild The Beatles: Rock Band Deluxe in order for these to take effect.***

# Repo Setup (Advanced)

### Installing Required Dependencies

* Install [**Git for Windows**](https://gitforwindows.org/), [**Dot Net 6.0 Runtime**](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime), and [**Python**](https://www.python.org/downloads/) (version 3.9 or later).
  * Install **Git** and **Dot Net 6.0 Runtime** with their default options, and ***select "Add python.exe to PATH"*** on the **Python** installer.

![Python PATH](dependencies/images/pythonpath.png)

* Open a **new command prompt** (press `Win+R`, type `cmd` and press Enter), type in `pip install gitpython`, and press enter. Close the command prompt when it's done installing.

### Initializing the Repo

* Go to the **[Releases](https://github.com/hmxmilohax/beatles-rock-band-deluxe/releases)** of this repo and **download `_init_repo.bat`** if you're on Windows or **`_init_repo.sh`** if you're on Linux.
  * Make a new **empty** folder, **put `_init_repo` in the folder, and run it**. This will pull the repo down for you and make sure you're completely up to date. **This will take some time.**

### ***The folder should look like this once it's done:***

![Repo Folder](dependencies/images/repofolder.png)

***The The Beatles: Rock Band Deluxe repo is now set up!*** You can now return to [**Installing on Xenia (Advanced)**](#installing-on-xenia-advanced) or [**Custom Textures**](#custom-textures).

# Dependencies

[**Git for Windows**](https://gitforwindows.org/) - CLI application to allow auto updating Deluxe repo files

[**Dot Net 6.0 Runtime**](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime) - Needed to run ArkHelper

[**Python**](https://www.python.org/downloads/) - For user script functionality (NOTE: 3.9 or newer is highly recommended!)

[**Mackiloha**](https://github.com/PikminGuts92/Mackiloha) - ArkHelper for building Deluxe - SuperFreq for building .bmp_xbox highway images

[**swap_rb_art_bytes.py**](https://github.com/PikminGuts92/re-notes/blob/master/scripts/swap_rb_art_bytes.py) - Python script for converting Xbox images to PS3

[**dtab**](https://github.com/mtolly/dtab) - For serializing `.dtb` script files
