Mac
The mac version is compiled from Travis-CI.

Windows
Windows executables are cross-compiled from Linux using MinGW cross-compiler.

For Windows 32 bit:

$ export BATTLESHIP_PLATFORM='windows32'
For Windows 64 bit:

$ export BATTLESHIP_PLATFORM='windows64'
Install build requirements:

$ sudo ./build/windows/requirements.sh
Build the program:

$ source ./build/windows/build.sh
Create Installation Wizard for Windows:

$ source build-dir/package.sh
Linux
$ export BATTLESHIP_PLATFORM='linux64'
Install build requirements:

$ sudo ./build/linux/requirements.sh
Build the program:

$ source ./build/linux/build.sh
$ source build-dir/package.sh
