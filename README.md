----------------
Kernel thread :
----------------

http://forum.xda-developers.com/showthread.php?t=1564408

* latest version : 

----------------
Build commands :
----------------

// (old) - android-ndk

export CROSS_COMPILE=~/toolchains/arm-eabi-4.4.3/prebuilt/linux-x86/bin/arm-eabi-

----------------

// (new) - Linaro 2012.03

export CROSS_COMPILE=~/gcc-linaro-arm-linux-gnueabi-2012.03-20120326_linux/bin/arm-linux-gnueabi-

----------------

make adridu59_hallon_defconfig

make
