# Merge log

Scroll down for the original README.md!

Base revision: 7dc472a3a78f31039b49bc058682d90a565c8398

|Pull Request|Commit|Title|Author|Merged?|
|----|----|----|----|----|
|[6](https://github.com/citra-emu/citra-canary/pull/6)|[d9c3e53d4](https://github.com/citra-emu/citra-canary/pull/6/files/)|Canary Base (MinGW Test)|[liushuyu](https://github.com/liushuyu)|Yes|
|[5355](https://github.com/citra-emu/citra/pull/5355)|[fa6f56d9b](https://github.com/citra-emu/citra/pull/5355/files/)|UDS: Only return beacons that have the desired wlan_comm_id|[FearlessTobi](https://github.com/FearlessTobi)|Yes|
|[5350](https://github.com/citra-emu/citra/pull/5350)|[4b1ec7bd0](https://github.com/citra-emu/citra/pull/5350/files/)|Interpolate circle pad motion|[xperia64](https://github.com/xperia64)|Yes|
|[5345](https://github.com/citra-emu/citra/pull/5345)|[72a8b341a](https://github.com/citra-emu/citra/pull/5345/files/)|[WIP] NCCHContainer: support for partitions if container is NCSD|[B3n30](https://github.com/B3n30)|Yes|
|[5344](https://github.com/citra-emu/citra/pull/5344)|[01b9302a2](https://github.com/citra-emu/citra/pull/5344/files/)|game_list: Fix folder reordering|[vitor-k](https://github.com/vitor-k)|Yes|
|[5342](https://github.com/citra-emu/citra/pull/5342)|[89e45b6b2](https://github.com/citra-emu/citra/pull/5342/files/)|GSP: Only process the command queue for the thread with active GPU rights|[BreadFish64](https://github.com/BreadFish64)|Yes|
|[5331](https://github.com/citra-emu/citra/pull/5331)|[7c6898fdd](https://github.com/citra-emu/citra/pull/5331/files/)|NWM_UDS: implement disconnect_reason and EjectClient|[B3n30](https://github.com/B3n30)|Yes|
|[5328](https://github.com/citra-emu/citra/pull/5328)|[0af8f1f9c](https://github.com/citra-emu/citra/pull/5328/files/)|APT: implement Set and GetWirelessRebootInfo|[B3n30](https://github.com/B3n30)|Yes|
|[5305](https://github.com/citra-emu/citra/pull/5305)|[58359fbf4](https://github.com/citra-emu/citra/pull/5305/files/)|Cheats improvement|[B3n30](https://github.com/B3n30)|Yes|
|[5281](https://github.com/citra-emu/citra/pull/5281)|[35df1f4dd](https://github.com/citra-emu/citra/pull/5281/files/)|citra-qt: Add an "Alternative Speed Limit" with its hotkey|[SutandoTsukai181](https://github.com/SutandoTsukai181)|Yes|
|[5273](https://github.com/citra-emu/citra/pull/5273)|[03145e307](https://github.com/citra-emu/citra/pull/5273/files/)|[WIP] Update FPS to roughly match the actual 3DS rate|[xperia64](https://github.com/xperia64)|Yes|
|[5266](https://github.com/citra-emu/citra/pull/5266)|[a0e8255b6](https://github.com/citra-emu/citra/pull/5266/files/)|[WIP] Adjust audio_frame_ticks|[xperia64](https://github.com/xperia64)|Yes|
|[5163](https://github.com/citra-emu/citra/pull/5163)|[26a6f6441](https://github.com/citra-emu/citra/pull/5163/files/)|input: allow mapping buttons to touchscreen|[z87](https://github.com/z87)|Yes|


End of merge log. You can find the original README.md below the break.

------

**BEFORE FILING AN ISSUE, READ THE RELEVANT SECTION IN THE [CONTRIBUTING](https://github.com/citra-emu/citra/wiki/Contributing#reporting-issues) FILE!!!**

Citra
==============
[![Travis CI Build Status](https://travis-ci.com/citra-emu/citra.svg?branch=master)](https://travis-ci.com/citra-emu/citra)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/sdf1o4kh3g1e68m9?svg=true)](https://ci.appveyor.com/project/bunnei/citra)
[![Bitrise CI Build Status](https://app.bitrise.io/app/4ccd8e5720f0d13b/status.svg?token=H32TmbCwxb3OQ-M66KbAyw&branch=master)](https://app.bitrise.io/app/4ccd8e5720f0d13b)
[![Discord](https://img.shields.io/discord/220740965957107713?color=%237289DA&label=Citra&logo=discord&logoColor=white)](https://discord.gg/FAXfZV9)

Citra is an experimental open-source Nintendo 3DS emulator/debugger written in C++. It is written with portability in mind, with builds actively maintained for Windows, Linux and macOS.

Citra emulates a subset of 3DS hardware and therefore is useful for running/debugging homebrew applications, and it is also able to run many commercial games! Some of these do not run at a playable state, but we are working every day to advance the project forward. (Playable here means compatibility of at least "Okay" on our [game compatibility list](https://citra-emu.org/game).)

Citra is licensed under the GPLv2 (or any later version). Refer to the license.txt file included. Please read the [FAQ](https://citra-emu.org/wiki/faq/) before getting started with the project.

Check out our [website](https://citra-emu.org/)!

Need help? Check out our [asking for help](https://citra-emu.org/help/reference/asking/) guide.

For development discussion, please join us on our [Discord server](https://citra-emu.org/discord/) or at #citra-dev on freenode.

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/citra-emu/citra) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](https://github.com/citra-emu/citra/wiki/Contributing) and [Developer Information](https://github.com/citra-emu/citra/wiki/Developer-Information). You should also contact any of the developers in the forum in order to know about the current state of the emulator because the [TODO list](https://docs.google.com/document/d/1SWIop0uBI9IW8VGg97TAtoT_CHNoP42FzYmvG1F4QDA) isn't maintained anymore.

If you want to contribute to the user interface translation, please checkout [citra project on transifex](https://www.transifex.com/citra/citra). We centralize the translation work there, and periodically upstream translation.

### Building

* __Windows__: [Windows Build](https://github.com/citra-emu/citra/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/citra-emu/citra/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/citra-emu/citra/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://citra-emu.org/donate/) for more information on how you can contribute to Citra. Any donations received will go towards things like:
* 3DS consoles for developers to explore the hardware
* 3DS games for testing
* Any equipment required for homebrew
* Infrastructure setup

We also more than gladly accept used 3DS consoles! If you would like to give yours away, don't hesitate to join our [Discord server](https://citra-emu.org/discord/) and talk to bunnei.
