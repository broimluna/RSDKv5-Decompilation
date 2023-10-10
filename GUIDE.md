# Sonic Mania Decompilation: Nintendo 3DS Build Guide

***This guide is for Linux only.*** If you are running Windows, please install Windows Subsystem for Linux and use that for this guide.

## Instructions

1. Install devkitPro pacman from [here](https://devkitpro.org/wiki/devkitPro_pacman).
2. Run: `sudo dkp-pacman -S 3ds-libtheora 3ds-sdl libctru 3ds-dev`.
3. Install Git. The command to do this will vary depending on what Linux distro you're using, but for Debian/Ubuntu, that command will look like this: `sudo apt-get install git`.
4. Download the **Sonic Mania 3DS Quick Build Script** from [here](https://raw.githubusercontent.com/SaturnSH2x2/RSDKv5-Decompilation/3ds-main/buildscript.sh). **NOTE:** *you might have to copy the text into a text editor, and then save it as `buildscript.sh`*
5. Make the script executable by running `chmod +x buildscript.sh`.
6. Run it using `./buildscript.sh`.
7. When the script is done running, your 3DSX will be located in `Sonic-Mania-Decompilation/build/dependencies/v5_3DS/` and the CIA will be in `Sonic-Mania-Decompilation/dependencies/v5_3DS/3ds/out/`

## Support

If you need any support, please feel free to reach out to the Retro Engine Modding Server on Discord. Invite: http://dc.railgun.works/retroengine