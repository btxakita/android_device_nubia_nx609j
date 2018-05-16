## How-to compile it:

To build:

```sh
. build/envsetup.sh
lunch omni_nx609-eng
mka adbd recoveryimage
```

TO flash

```sh
fastboot oem nubia_unlock NUBIA_NX609J
fastboot flash recovery recovery.img
```
