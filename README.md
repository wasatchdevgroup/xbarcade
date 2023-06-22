# XBArcade Cloud Gaming 

Simple native Electron wrapper for Xbarcade Cloud Gaming ([xbox.com/play](https://xbox.com/play))

## Features

* Windows / Mac (intel/Apple Silicon) / Linux(?)
* Alt-Enter - Toggle fullscreen
* Escape - Minimize

## Why?

* Better native experience, i.e. single window, launches full-screen, etc
* Less memory and CPU/GPU usage than vanilla Chrome, for instance
* No extensions or other junk
* Future optimisation via Electron / Chromium tweaking
* Because..

## Download

* Pre-built binaries for Windows & Mac (Intel x64 and Apple Silicon arm64) are availabe under [Releases]()
* Please be aware that these binaries are not signed so you will have to work around that.. see for [Windows](https://www.screensaversplanet.com/help/guides/windows/how-to-bypass-windows-smartscreen-49) and [Mac](https://support.apple.com/en-gb/guide/mac-help/mh40616/mac)

## Requirements

* Build - [https://nodejs.org/en/](https://nodejs.org/en/)

## Build & Make

```sh
# install dependencies
npm install

# run app (to test before build)
npm start

# Windows - package and create installer to ./out
npm run make

# OSX - package and create zip to ./out
npm run make-mac

# OSX Apple Silicon - package and create zip to ./out
npm run make-mac-aarch
```

## Install

* After ``make`` run the installer in ``./out`` folder
* On Windows, the app is installed to ``%LocalAppData%\xbarcade\`` and a shortcut is added to desktop
* Uninstalled via usual Windows app uninstall process (Settings > Apps)

Coming Soon:
connections to home xbox

Java Streaming Emulators for Retro Gaming

Nintendo
Game Boy Advance   |  Famicom / NES   |  Virtual Boy Game Boy   |  SNES   |  DS   |  64

Sega
Master System   |  Mega Drive   |  Game Gear

Saturn   |  32X   |  CD

Atari
2600   |  5200   |  7800   |  Lynx   |  Jaguar

Other
TurboGrafs 16 PC Engine   |  WanderSwan Color   |  Neo Geo Poket

PlayStation
One | Two | Three | Four

Arcade   |  MSX   |  3DO   |  MAME 2003


