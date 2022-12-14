# v86-NodeVM
Self-contained NodeJS ready-to-use linux virtual machine using v86!
## specs
OS : Buildroot linux

BIOS : Seabios

Compiled size : 8mb

Ram usage : ~250 - 315mb

File count : 2(Autosave and script itself...)

https://user-images.githubusercontent.com/42496449/206863423-0b327819-b7d0-44c0-9d86-dd6fc6828118.mp4
## features
 - Closure compiled
 - bundled dependency
 - Smart Ctrl+C exit
 - Start within 15 seconds
 - Auto login
 - Yes its a linux
 - Optimized for server
 - Everything compressed, current version(v1.2.0) only use 8mb of storage for main script
## TODO
 - Deprecate autosave, buildroot linux doesnt support filesystem that is compatible with autosave
 - NETWORK SUPPORT
###### repo files
 - compiler.bat - yes it compiles
 - compiler.jar - closure compiler
 - nodejs.js - source file
 - NodeVM.js - compiled file
 - compress_tool/ - Gzip compression for OS replacement
###### credits
This project cannot work without its great core, [v86](https://github.com/copy/v86/)

Linux image and bios is from [v86's images git](https://github.com/copy/images/) and [v86's seabios included in v86 master branch](https://github.com/copy/v86/blob/master/bios/seabios.bin/)
