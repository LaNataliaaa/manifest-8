![](LESSAOSP.png)

</br>
HOW TO BUILD LESSAOSP ROM?</br>

1.create a directory called as **lessaosp**</br>
2.Next use this below command
    **cd lessaosp**
## Initialize local repository
```## Initialize local repository
repo init -u https://github.com/LESSAOSP/manifest -b eleven
```
## Sync
```## Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

[ IF YOU GOT INTO ANY PROBLMES JUST SIMPLY USE 'repo sync' ]
```
# Build Process
```## Set up environment
. build/envsetup.sh
        (or)
. b*/e*
```

## Choose a target
```## Choose a target
lunch lessaosp_$device-userdebug
```
## Build the code
```## Build the code
make bacon -jX
```
---
>Credits:-
* AOSP Team
* PixelExperience Team
* Evolution X Team
* Havoc-OS Team
* Lineage-OS Team
* LightHouse-OS Team
* MISTAKES ARE GOOD FOR BETTER FUTURE
## -------------------------------------------------------------------------------
## ------------------------------------LESSAOSP--------------------------------
## --------------------------------------------------------------------------------
