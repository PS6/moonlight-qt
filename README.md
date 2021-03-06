# Moonlight PC

[Moonlight PC](http://moonlight-stream.com) is an open source implementation of NVIDIA's GameStream, as used by the NVIDIA Shield, but built to run on Windows, Mac, and Linux. This client is the successor to [Moonlight Chrome](https://github.com/moonlight-stream/moonlight-chrome) for streaming on PC.

Moonlight also has mobile versions for [Android](https://github.com/moonlight-stream/moonlight-android) and  [iOS](https://github.com/moonlight-stream/moonlight-ios).

See the [releases page](https://github.com/moonlight-stream/moonlight-qt/releases) for download links for Windows and Mac. For Linux, we're on [Flathub](https://flathub.org/apps/details/com.moonlight_stream.Moonlight).

You can follow development on our [Discord server](https://discord.gg/6ERtzFY).

 [![Windows AppVeyor Status](https://ci.appveyor.com/api/projects/status/glj5cxqwy2w3bglv/branch/master?svg=true)](https://ci.appveyor.com/project/cgutman/moonlight-qt/branch/master)
 [![Mac and Linux Travis CI Status](https://travis-ci.org/moonlight-stream/moonlight-qt.svg?branch=master)](https://travis-ci.org/moonlight-stream/moonlight-qt)

## Features
 - Hardware accelerated video decoding on Windows, Mac, and Linux
 - Supports streaming at up to 120 FPS (high refresh rate monitor recommended)
 - Supports streaming at 720p, 1080p, 1440p, 4K, and the client PC's native screen resolution
 - 5.1 surround sound audio
 - HEVC support for better image quality at reduced bandwidth
 - Keyboard and mouse support
 - Gamepad support with SDL gamepad mappings

## Building
1. Install the latest Qt SDK (and optionally, the Qt Creator IDE) from https://www.qt.io/download
    - On Windows, install Visual Studio 2017 and select MSVC 2017 toolchain during Qt installation
    - On Mac, install the latest version of XCode
    - On Linux, install your distro equivalents of: `openssl-devel qt5-devel SDL2-devel ffmpeg-devel qt5-qtquickcontrols2-devel libva-devel libvdpau-devel`
2. Run `git submodule update --init --recursive` from within `moonlight-qt/`
3. Open the project in Qt Creator or build from qmake on the command line

## Contribute
1. Fork us
2. Write code
3. Send Pull Requests

Check out our [website](http://moonlight-stream.com) for project links and information.
