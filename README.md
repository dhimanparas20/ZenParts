# ZenParts
A stand Alone repo for ZenParts

## Banner
<p align="center">
<img src="https://github.com/dhimanparas20/buildbot-2.0/blob/main/mst.jpg" />

## Changelog:
> Added option to build with GVisualMod, but its disabled by default. To enable it edit the zenparts.mk file accordingly.

> Changed the position to System

> Added doze feature

> Added Dirc support

## Calling and Compatibility
sync the ZenParts using the commands 
```sh
git clone https://github.com/dhimanparas20/ZenParts.git packages/apps/ZenParts
```

Then simply call them from device.mk using commands
```sh
$(call inherit-product, packages/apps/ZenParts/zenparts.mk)
```

Now build the rom normally like you do.
>Remember to fix the Selinux denials else issues and crashes will occur.
>I also suggest you not to include prebuilt Dolby in your roms if you are using this ZenParts else issues may occur.

# Notes
Dont be a gey by copying or importing this repo and calling it yours .
  
Any changes(pull requests) for betterment are welcome,  

If you  need any kind of help , ping me up  https://t.me/ken_kaneki_69

Im not responsible for any of your data losses , do it at your own will .

# Credits
@ElectroPerf
@SonalSingh18
