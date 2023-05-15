# AOSP Master with PHH patches | WIP
> !> WARNING | Highly experimental! | Unstable!

These are phh patches made for AOSP.MASTER (based on VanillaIceCream)

## Building
- Init AOSP's platform/manifest with branch master
- Add manifest.xml from TrebleDroid manifest
- Sync, remove device/phh/treble 
- Clone [device/phh/treble for AOSP Master](https://github.com/KrutosVIP/master_device_phh_treble)
- In device/phh/treble, execute `generate.sh`
- Apply patches

If everything is fine, try to build. Keep in mind, these patches may fail as AOSP.Master is updated frequently
> | Work in progress!
