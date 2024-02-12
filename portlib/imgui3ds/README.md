# Imgui-3ds Portlib

## Building
Call `make` under the this (portlib/imgui) directory.

## Installing
Copy the generated `lib` and `include` folders to `portlib/3ds` of your devKitPro instalation.

## Using the lib
### Make
Add -limgui to LIBS on your Makefile's option

`LIBS	:= -limgui -lctru -lm`