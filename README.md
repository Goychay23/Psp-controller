# Project Base
The main purpose of this project is to simulate the PlayStation joystick, which can work between mobile and computer.
It can also be used on tablets or other devices, and you can configure the make.inc file for a specific device.

| Operating System | Required Dependencies                                      |
|------------------|------------------------------------------------------------|
| Linux            | `gcc`, `ffmpeg`, `mesautils`, `x-wayland` or `xorg`        |
| Windows          | `dkm`, `vcrum2022`, `OpenGL ES`, `Vulkan`                  |
| MacOS            | `bin-utils`, `ffmpeg`, `mesautils`                         |

#  Setup
Linux
```
git clone https://github.com/Goychay23/Psp-controller
cd Psp-controller
make
./configure
make build linux
./build -es -xorg

Windows



