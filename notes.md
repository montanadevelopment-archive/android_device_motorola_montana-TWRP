Recommended build script:
https://github.com/JarlPenguin/scripts/blob/master/TWRP.sh

Notes on compiling:

* Recommended sources:
** [OmniROM base](https://github.com/omnirom/android/tree/android-7.1)
** [TWRP recovery](https://github.com/omnirom/android_bootable_recovery/tree/android-9.0) - replace recovery folder inside bootable/recovery
* Export ALLOW_MISSING_DEPENDENCIES=true to compile without errors about missing dependencies.
* Export LC_ALL=C if you encounter errors in compiling the kernel.
* It is recommended that you clean the build directory every time you build.
