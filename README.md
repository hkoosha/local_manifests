# Android for Raspberry Pi 4 (unfinished)

## Download Android source with patches (local_manifests)
 Refer to http://source.android.com/source/downloading.html
 ```
 $ repo init -u https://android.googlesource.com/platform/manifest -b android-10.0.0_r2
 $ git clone https://github.com/RaspberryPiFan/local_manifests .repo/local_manifests -b android-10
 $ repo sync
 ```

## Build for Raspberry Pi4
 https://github.com/RaspberryPiFan/device_brcm_rpi4/tree/android-10

Use -j[n] option on sync & build steps, if build host has a good number of CPU cores.


### If you need help:
Join my discord server!
https://discord.gg/kf4ZPqP
