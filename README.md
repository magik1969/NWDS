# Introduction

`NWDS` is a simple digital signage program based on NW.js platform.

## Main features
* based on modern and secure Web technologies
* support for local and remote media
* support for local and remote layouts
* easy extensible

## Usage
```
path/to/nw path/to/NWDS/.
```

## Notes
* Units used for window size and position are not pixels and depend on system screen configuration. If you want to use pixel unit, make sure screen scale is 1. To see current screen scale see Log/Screens.
* To increase A/V codecs compatibility, consider replacing ffmpeg included with NW.js. 
[Precompiled binaries from the community](https://github.com/nwjs-ffmpeg-prebuilt/nwjs-ffmpeg-prebuilt/releases)
* Media windows are frameless by default. To move window using mouse, drag it using top area, where framed windows have their title bar.

