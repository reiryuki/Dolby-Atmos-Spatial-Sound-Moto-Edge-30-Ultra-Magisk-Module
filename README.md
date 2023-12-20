# Dolby Atmos and Spatial Sound Moto Edge 30 Ultra Magisk Module

## DISCLAIMER
- Motorola & Dolby apps and blobs are owned by Motorola™ & Dolby™.
- The MIT license specified here is for the Magisk Module only, not for Motorola & Dolby apps and blobs.

## Descriptions
- Equalizers soundfx ported from Motorola Edge 30 Ultra (eqs) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Dolby Atmos and Spatial Sound
- Global type soundfx
- Dolby Atmos changes/spoofs ro.product.brand to motorola which may break some system apps and features functionality
- Dolby Atmos doesn't support auxiliary cable
- Dolby Atmos conflicted with `vendor.dolby_v3_6.hardware.dms360@2.0-service` & `vendor.dolby.hardware.dms@1.0-service`

## Sources
- https://dumps.tadiphone.dev/dumps/motorola/eqs user-13-T1SQ33.15-11-137-10-71a49-release-keys
- /system/vendor/etc/aualgo: https://dumps.tadiphone.dev/dumps/motorola/rtwo user-13-T1TR33.43-20-28-8fa75-release-keys
- libswvqe.so: LENOVO TB-J606F
- libstagefrightdolby.so, libstagefright_soft_ddpdec.so, libstagefright_soft_ac4dec.so, libdeccfg.so, & media_codecs_dolby_audio.xml: https://dumps.tadiphone.dev/dumps/motorola/rhode user-12-S1SR32.38-124-3-a8403-release-keys

## Screenshots
- https://t.me/androidryukimods/1527

## Requirements
- Architecture 64 bit for Dolby Atmos
- Android 11 and up for Dolby Atmos
- Android 8 and up for Spatial Sound
- Magisk or KernelSU installed (Recommended to use Magisk Delta/Kitsune Mask for systemless early init mount manifest.xml if your ROM is Read-Only https://t.me/androidryukimodsdiscussions/100091)
- Moto Core Magisk Module installed https://github.com/reiryuki/Moto-Core-Magisk-Module except you are in Motorola ROM

## WARNING!!!
- Possibility of bootloop or even softbrick or a service failure on Read-Only ROM if you don't use Magisk Delta/Kitsune Mask.

## Installation Guide & Download Link
- Recommended to use Magisk Delta/Kitsune Mask https://t.me/androidryukimodsdiscussions/100091
- Remove any other else Dolby Magisk module with different name (no need to remove if it's the same name)
- Reboot
- Install Moto Core Magisk Module first: https://github.com/reiryuki/Moto-Core-Magisk-Module except you are in Motorola ROM
- If you have Dolby in-built in your ROM, then you need to activate data.cleanup=1 at the first time install (READ Optionals bellow!)
- Install this module https://www.pling.com/p/2105416/ via Magisk app or KernelSU app or Recovery if Magisk installed
- Install AML Magisk Module https://t.me/androidryukimodsdiscussions/29836 only if using any other audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot after
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot after
- If options doesn't show up in Bluetooth audio, try disconnect and reconnect the Bluetooth and restart the app

## Optionals
- https://t.me/androidryukimodsdiscussions/2616
- Global: https://t.me/androidryukimodsdiscussions/60861
- Stream: https://t.me/androidryukimodsdiscussions/26764

## Troubleshootings
- https://t.me/androidryukimodsdiscussions/2617
- Global: https://t.me/androidryukimodsdiscussions/29836

## Tested on
- Android 13 CrDroid ROM

## Support & Bug Report
- https://t.me/androidryukimodsdiscussions/2618
- If you don't do above, issues will be closed immediately

## Credits and contributors
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Thanks for Donations
This Magisk Module is always will be free but you can however show us that you are care by making a donations:
- https://ko-fi.com/reiryuki
- https://www.paypal.me/reiryuki
- https://t.me/androidryukimodsdiscussions/2619


