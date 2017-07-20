Google Play Edition ROM Series - MarshMallow
===========

This project is based on [**AOSP-OMS**](https://github.com/AOSP-RRO) & [**AOSPExtended**](https://github.com/AOSPExtended).

##Credits
* [**AOSP-OMS**](https://github.com/AOSP-RRO)
* [**AOSPExtended (Based ROM**](https://github.com/AOSPExtended)
* [**Temasek**](https://github.com/temasek)
* [**ZephyrOS**](https://github.com/Zephyr-OS)
* [**TurboROM**](https://github.com/TurboROM)
* [**TeamSubstratum(Theme Engine)**](https://github.com/TeamSubstratum)

##How to Build?

To initialize your local repository using the AospExtended trees, use a command like this:

        repo init -u git://github.com/GooglePlayEditionRemixed/platform_manifest.git -b gpe-m

Sync up the Repo:

        repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

Build to your Device:

        . build/envsetup.sh 

        launch aosp_(codename)-userdebug 

        mka bacon

        
