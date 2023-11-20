![image](https://raw.githubusercontent.com/AshiVered/support-israel-banner/main/assets/support-israel-banner.jpg)


# QinPad - simple and lightweight keyboard app for Xiaomi Qin 1s and compatible keypad Android phones
Forked from https://gitlab.com/suborg/qinpad.
# Features

- Three layouts: Latin (supports at least English + Spanish + German + Latvian + Pinyin input) and Hebrew, and numbers.
- Layout switching with `#` key, Caps switching with `*` key.
- Special character input similar to Nokias (with 0 and 1 keys).
- Non-invasive passing input control to the system in number entry fields.
- Supports Android 4.4+ (including MocorDroid) devices with hardware keypads where Back key is also a Backspace key. Primary support, however, is only guaranteed for Qin 1s.

# Building

The app project is compatible with Android Studio 3.3.2. Just clone the repo, import the project and build it with the Studio distribution.

# Installation/Update

Enable Developer settings and USB debugging. Then run:

```
adb install [your_built_apk]
```

To update the version, run:

```
adb uninstall us.chronovir.qinpad
adb install [your_new_apk]
```

# Initial setup

Start the keyboard from the main menu. You'll be taken to the standard Android input method selection dialog (hidden by default on Xiaomi Qin 1s). Set the mark on QinPad and remove it from the stock keyboard.

You'll need to do this after each version update.
