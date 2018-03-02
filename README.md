### Pixel 2 Experience
I made a compilation of the different mods and came up with this Pixel 2 Experience module which can be flashed with other devices on Oreo.

### Information
Searching around the internet, I've seen several mods on XDA, GitHub and other websites which have extracted files from the Pixel 2 devices. I've decided to gather them and compiled them all into a single Magisk Module. This module can be flashed with other devices on Oreo as well.

### Features
- Modded Pixel 2 Launcher by @paphonb [XDA thread](https://forum.xda-developers.com/android/apps-games/app-rootless-pixel-2-launcher-google-t3688393/)
- Modded Rootless Pixel Launcher based on AOSP 8.1 Launcher3 by @azaidi [XDA thread](https://forum.xda-developers.com/android/apps-games/launcher3-pixel-launcher-features-t3620972)
- Pixel Launcher icons
- Google Wallpapers app
- Adds Pixel-exclusive wallpapers via Google Wallpapers app
- Pixel accent (in system/vendor/overlay/Pixel)
- Google Lens enabled in Google Photos
- Google Sans font used in Google Assistant, Pixel Launcher, System Update window, SetupWizard text, lockscreen clock
- Pixel 2 audio (ringtones, notifications, ui, alarms)
- Enable Google Assistant via build.prop
- Camera2 API support
- Enables Night Light support

Features I can add in but don't think will work in all Oreo devices

- Pixel Navigation Bar style (might not work with most 8.0 devices due to changes in the SystemUI.apk)
- Automatic dark SystemUI theme depending on wallpaper (can only work in 8.1+, could possibly a different version of the module)

### Latest changelog
v1.4a:
- include Pixel 2 lockscreen font overlay
- include Night Light enabler

v1.4b:
- include Pixel 2 lockscreen font overlay
- include Night Light enabler
- replace paphonb's launcher with azaidi's version

For old changelogs, check on the [XDA Thread](https://forum.xda-developers.com/apps/magisk/module-pixel-2-experience-t3757137/)

### Compatibility
- Xiaomi Mi A1 on 8.0.0 Oreo Stock ROM (tissot)
- Wileyfox Swift on 8.1.0 crDroid (crackling)
- Cherry Mobile G1 on 8.1.0 LOS 15.1 (seed)
- Samsung Galaxy S8 Exynos - weather app crashes but no other issues found
- Nexus 5
- OnePlus 5T on OOS Beta3
- OnePlus 3T
- Essential PH-1
Provide feedback via the XDA thread by inputting your phone model, current ROM. Feel free to report if it works on other devices as well. It should work on other devices as long as they are close to stock (Stock/Custom ROMs).

### Thanks
Thanks to these people!
- @Chronzy for providing the system/vendor/overlay files as well as system/media files from his Pixel 2. [XDA thread](https://forum.xda-developers.com/showpost.php?p=74267243&postcount=14) 
- @elmkzgirxp for providing an overlay for the lockscreen font
- @paphonb for his Rootless Pixel 2 Launcher [XDA thread](https://forum.xda-developers.com/android/apps-games/app-rootless-pixel-2-launcher-google-t3688393/)
- @azaidi for his Rootless Pixel Launcher 3.2 [XDA thread](https://forum.xda-developers.com/android/apps-games/launcher3-pixel-launcher-features-t3620972)
- @Soheil_rf for his Night Light enabler overlay [XDA thread](https://forum.xda-developers.com/crossdevice-dev/sony-themes-apps/oreo-enable-night-light-tile-t3713021)
- @topjohnwu

### XDA Official thread:
[Magisk Subforum](https://forum.xda-developers.com/apps/magisk/module-pixel-2-experience-t3757137/)

### [XDA Portal feature](https://www.xda-developers.com/pixel-2-experience-magisk-module/)

### Github source: <br />
[https://github.com/joeyhuab/Pixel-2-Experience-Magisk/](https://github.com/joeyhuab/Pixel-2-Experience-Magisk/)
